![Arista CVP Automation](https://img.shields.io/badge/Arista-CVP%20Automation-blue) ![Arista EOS Automation](https://img.shields.io/badge/Arista-EOS%20Automation-blue)

# AVD Arista Validated Design for Arista Test Drive

## About

This repository is configured to run [`arista.cvp`](https://github.com/aristanetworks/ansible-cvp) & [`arista.avd`](https://github.com/aristanetworks/ansible-avd) ansible collections against the Arista Test Drive (ATD) Topology.

To access an Arista Test Drive topology, please contact your Arista representative.

## Lab Topology

The DC1 portion of the Level 5 lab topology consists of 3 Spines, 6 Leafs and 2 Hosts.

## ATD Topology Device List

| Device | IP Address   |
| ------ | ------------ |
| spine1-DC1 |192.168.0.11 |
| spine2-DC1 |192.168.0.12 |
| spine3-DC1 |192.168.0.13 |
| leaf1-DC1  |192.168.0.21 |
| leaf2-DC1  |192.168.0.22 |
| leaf3-DC1  |192.168.0.23 |
| leaf4-DC1  |192.168.0.24 |

# Setup Your Environment

Make sure to reset your lab to the default configlet assignments (BASE configlets and ATD-INFRA). You can use the ATD-Reset-Level5 repo to do this: https://github.com/tonybourkesdnpros/ATD-Reset-Level5

### Setup your git global config (optional)
    git config --global user.email "you@example.com"
    git config --global user.name "Your Name"

### Clone this Repository
Make sure you're in the persist directory, then clone this repository:

    git clone https://github.com/tonybourkesdnpros/AVD-Level5

### Install Components
You will need to run these commands every time your lab environment starts up (most of the Linux system isn't persistent across reboots)

    ansible-galaxy collection install arista.eos
    ansible-galaxy collection install arista.cvp
    ansible-galaxy collection install arista.avd
    pip3 install cvprac --upgrade

# Work with Playbooks

### Add Lab Credentials

edit credentials in vscode: atd-inventory/inventory.yml 

(put your lab password in for ansible_password and ansible_ssh_pass)

### Run Playbook to Prepare CloudVision for AVD

The atd-prepare-lab.yml playbook will move leafs and spines in DC1 into a STAGING container to simulate switches just being discovered through ZTP

    ansible-playbook playbooks/atd-prepare-lab.yml
    
(This will likely generate an error, that's OK, you can continue)

### Execute Tasks in CVP manually

The playbook will create tasks, but not a change control, so create a change control with the open tasks and execute the change control. 

### Run Playbook to Generate Configuration files

We can make use of tags in AVD to execute a portion of the playbook, in this case generating all the configuration. 

    ansible-playbook playbooks/atd-fabric-deploy.yml --tags=generate

View the generated configuration files: 

    ls atd-inventory/intended/configs

Look at leaf1-DC1.cfg, and note the loopback0 IP address. It should be in the 192.0.255.0/24 address space (as a /32). 

You can try changing the loopback_ipv4_pool parameter in atd-inventory/group_vars/ATD_FABRIC.yml from 192.0.255.0/24 to 192.0.200.0/24

    loopback_ipv4_pool: 192.0.200.0/24

Rerun the configuration generation

    ansible-playbook playbooks/atd-fabric-deploy.yml --tags=generate

This will re-create the configuration files. Note that loopback0 has changed to the 192.0.200.0/24 address space. 

# Build the Fabric

Run the fabric deploy playbook

    ansible-playbook playbooks/atd-fabric-deploy.yml 

This will take about 2-3 minutes, and will create a series of tasks in CloudVision. When the playbook is complete, create a change control from these tasks and execute it (you may see some errors, that's OK). 

Verify the fabric is configured
    show ip bgp summary
    show bgp evpn summary


### Run the other playbooks






# Execute Tasks in CVP manually

# Run audit playbook to validate Fabric states
    ansible-playbook playbooks/atd-validate-states.yml

# Execute EOS_SNAPSHOT role to collect show commands
    ansible-playbook playbooks/atd-snapshot.yml


## License

Project is published under [Apache License]().
