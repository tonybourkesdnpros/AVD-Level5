# FABRIC

# Table of Contents

- [Fabric Switches and Management IP](#fabric-switches-and-management-ip)
  - [Fabric Switches with inband Management IP](#fabric-switches-with-inband-management-ip)
- [Fabric Topology](#fabric-topology)
- [Fabric IP Allocation](#fabric-ip-allocation)
  - [Fabric Point-To-Point Links](#fabric-point-to-point-links)
  - [Point-To-Point Links Node Allocation](#point-to-point-links-node-allocation)
  - [Loopback Interfaces (BGP EVPN Peering)](#loopback-interfaces-bgp-evpn-peering)
  - [Loopback0 Interfaces Node Allocation](#loopback0-interfaces-node-allocation)
  - [VTEP Loopback VXLAN Tunnel Source Interfaces (VTEPs Only)](#vtep-loopback-vxlan-tunnel-source-interfaces-vteps-only)
  - [VTEP Loopback Node allocation](#vtep-loopback-node-allocation)

# Fabric Switches and Management IP

| POD | Type | Node | Management IP | Platform | Provisioned in CloudVision |
| --- | ---- | ---- | ------------- | -------- | -------------------------- |
| FABRIC | l3leaf | borderleaf1-DC1 | 192.168.0.25/24 | cEOS-LAB | Provisioned |
| FABRIC | l3leaf | borderleaf1-DC2 | 192.168.0.35/24 | cEOS-LAB | Provisioned |
| FABRIC | l3leaf | borderleaf2-DC1 | 192.168.0.26/24 | cEOS-LAB | Provisioned |
| FABRIC | l3leaf | borderleaf2-DC2 | 192.168.0.36/24 | cEOS-LAB | Provisioned |
| FABRIC | l3leaf | leaf1-DC1 | 192.168.0.21/24 | cEOS-LAB | Provisioned |
| FABRIC | l3leaf | leaf1-DC2 | 192.168.0.31/24 | cEOS-LAB | Provisioned |
| FABRIC | l3leaf | leaf2-DC1 | 192.168.0.22/24 | cEOS-LAB | Provisioned |
| FABRIC | l3leaf | leaf2-DC2 | 192.168.0.32/24 | cEOS-LAB | Provisioned |
| FABRIC | l3leaf | leaf3-DC1 | 192.168.0.23/24 | cEOS-LAB | Provisioned |
| FABRIC | l3leaf | leaf3-DC2 | 192.168.0.33/24 | cEOS-LAB | Provisioned |
| FABRIC | l3leaf | leaf4-DC1 | 192.168.0.24/24 | cEOS-LAB | Provisioned |
| FABRIC | l3leaf | leaf4-DC2 | 192.168.0.34/24 | cEOS-LAB | Provisioned |
| FABRIC | spine | spine1-DC1 | 192.168.0.11/24 | cEOS-LAB | Provisioned |
| FABRIC | spine | spine1-DC2 | 192.168.0.14/24 | cEOS-LAB | Provisioned |
| FABRIC | spine | spine2-DC1 | 192.168.0.12/24 | cEOS-LAB | Provisioned |
| FABRIC | spine | spine2-DC2 | 192.168.0.15/24 | cEOS-LAB | Provisioned |
| FABRIC | spine | spine3-DC1 | 192.168.0.13/24 | cEOS-LAB | Provisioned |
| FABRIC | spine | spine3-DC2 | 192.168.0.16/24 | cEOS-LAB | Provisioned |

> Provision status is based on Ansible inventory declaration and do not represent real status from CloudVision.

## Fabric Switches with inband Management IP
| POD | Type | Node | Management IP | Inband Interface |
| --- | ---- | ---- | ------------- | ---------------- |

# Fabric Topology

| Type | Node | Node Interface | Peer Type | Peer Node | Peer Interface |
| ---- | ---- | -------------- | --------- | ----------| -------------- |
| l3leaf | borderleaf1-DC1 | Ethernet1 | mlag_peer | borderleaf2-DC1 | Ethernet1 |
| l3leaf | borderleaf1-DC1 | Ethernet2 | mlag_peer | borderleaf2-DC1 | Ethernet2 |
| l3leaf | borderleaf1-DC1 | Ethernet3 | spine | spine1-DC1 | Ethernet6 |
| l3leaf | borderleaf1-DC1 | Ethernet4 | spine | spine2-DC1 | Ethernet6 |
| l3leaf | borderleaf1-DC1 | Ethernet5 | spine | spine3-DC1 | Ethernet6 |
| l3leaf | borderleaf1-DC2 | Ethernet1 | mlag_peer | borderleaf2-DC2 | Ethernet1 |
| l3leaf | borderleaf1-DC2 | Ethernet2 | mlag_peer | borderleaf2-DC2 | Ethernet2 |
| l3leaf | borderleaf1-DC2 | Ethernet3 | spine | spine1-DC2 | Ethernet6 |
| l3leaf | borderleaf1-DC2 | Ethernet4 | spine | spine2-DC2 | Ethernet6 |
| l3leaf | borderleaf1-DC2 | Ethernet5 | spine | spine3-DC2 | Ethernet6 |
| l3leaf | borderleaf2-DC1 | Ethernet3 | spine | spine1-DC1 | Ethernet7 |
| l3leaf | borderleaf2-DC1 | Ethernet4 | spine | spine2-DC1 | Ethernet7 |
| l3leaf | borderleaf2-DC1 | Ethernet5 | spine | spine3-DC1 | Ethernet7 |
| l3leaf | borderleaf2-DC2 | Ethernet3 | spine | spine1-DC2 | Ethernet7 |
| l3leaf | borderleaf2-DC2 | Ethernet4 | spine | spine2-DC2 | Ethernet7 |
| l3leaf | borderleaf2-DC2 | Ethernet5 | spine | spine3-DC2 | Ethernet7 |
| l3leaf | leaf1-DC1 | Ethernet1 | mlag_peer | leaf2-DC1 | Ethernet1 |
| l3leaf | leaf1-DC1 | Ethernet2 | mlag_peer | leaf2-DC1 | Ethernet2 |
| l3leaf | leaf1-DC1 | Ethernet3 | spine | spine1-DC1 | Ethernet2 |
| l3leaf | leaf1-DC1 | Ethernet4 | spine | spine2-DC1 | Ethernet2 |
| l3leaf | leaf1-DC1 | Ethernet5 | spine | spine3-DC1 | Ethernet2 |
| l3leaf | leaf1-DC2 | Ethernet1 | mlag_peer | leaf2-DC2 | Ethernet1 |
| l3leaf | leaf1-DC2 | Ethernet2 | mlag_peer | leaf2-DC2 | Ethernet2 |
| l3leaf | leaf1-DC2 | Ethernet3 | spine | spine1-DC2 | Ethernet2 |
| l3leaf | leaf1-DC2 | Ethernet4 | spine | spine2-DC2 | Ethernet2 |
| l3leaf | leaf1-DC2 | Ethernet5 | spine | spine3-DC2 | Ethernet2 |
| l3leaf | leaf2-DC1 | Ethernet3 | spine | spine1-DC1 | Ethernet3 |
| l3leaf | leaf2-DC1 | Ethernet4 | spine | spine2-DC1 | Ethernet3 |
| l3leaf | leaf2-DC1 | Ethernet5 | spine | spine3-DC1 | Ethernet3 |
| l3leaf | leaf2-DC2 | Ethernet3 | spine | spine1-DC2 | Ethernet3 |
| l3leaf | leaf2-DC2 | Ethernet4 | spine | spine2-DC2 | Ethernet3 |
| l3leaf | leaf2-DC2 | Ethernet5 | spine | spine3-DC2 | Ethernet3 |
| l3leaf | leaf3-DC1 | Ethernet1 | mlag_peer | leaf4-DC1 | Ethernet1 |
| l3leaf | leaf3-DC1 | Ethernet2 | mlag_peer | leaf4-DC1 | Ethernet2 |
| l3leaf | leaf3-DC1 | Ethernet3 | spine | spine1-DC1 | Ethernet4 |
| l3leaf | leaf3-DC1 | Ethernet4 | spine | spine2-DC1 | Ethernet4 |
| l3leaf | leaf3-DC1 | Ethernet5 | spine | spine3-DC1 | Ethernet4 |
| l3leaf | leaf3-DC2 | Ethernet1 | mlag_peer | leaf4-DC2 | Ethernet1 |
| l3leaf | leaf3-DC2 | Ethernet2 | mlag_peer | leaf4-DC2 | Ethernet2 |
| l3leaf | leaf3-DC2 | Ethernet3 | spine | spine1-DC2 | Ethernet4 |
| l3leaf | leaf3-DC2 | Ethernet4 | spine | spine2-DC2 | Ethernet4 |
| l3leaf | leaf3-DC2 | Ethernet5 | spine | spine3-DC2 | Ethernet4 |
| l3leaf | leaf4-DC1 | Ethernet3 | spine | spine1-DC1 | Ethernet5 |
| l3leaf | leaf4-DC1 | Ethernet4 | spine | spine2-DC1 | Ethernet5 |
| l3leaf | leaf4-DC1 | Ethernet5 | spine | spine3-DC1 | Ethernet5 |
| l3leaf | leaf4-DC2 | Ethernet3 | spine | spine1-DC2 | Ethernet5 |
| l3leaf | leaf4-DC2 | Ethernet4 | spine | spine2-DC2 | Ethernet5 |
| l3leaf | leaf4-DC2 | Ethernet5 | spine | spine3-DC2 | Ethernet5 |

# Fabric IP Allocation

## Fabric Point-To-Point Links

| Uplink IPv4 Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ---------------- | ------------------- | ------------------ | ------------------ |
| 192.168.103.0/24 | 256 | 36 | 14.07 % |
| 192.168.203.0/24 | 256 | 36 | 14.07 % |

## Point-To-Point Links Node Allocation

| Node | Node Interface | Node IP Address | Peer Node | Peer Interface | Peer IP Address |
| ---- | -------------- | --------------- | --------- | -------------- | --------------- |
| borderleaf1-DC1 | Ethernet3 | 192.168.103.25/31 | spine1-DC1 | Ethernet6 | 192.168.103.24/31 |
| borderleaf1-DC1 | Ethernet4 | 192.168.103.27/31 | spine2-DC1 | Ethernet6 | 192.168.103.26/31 |
| borderleaf1-DC1 | Ethernet5 | 192.168.103.29/31 | spine3-DC1 | Ethernet6 | 192.168.103.28/31 |
| borderleaf1-DC2 | Ethernet3 | 192.168.203.61/31 | spine1-DC2 | Ethernet6 | 192.168.203.60/31 |
| borderleaf1-DC2 | Ethernet4 | 192.168.203.63/31 | spine2-DC2 | Ethernet6 | 192.168.203.62/31 |
| borderleaf1-DC2 | Ethernet5 | 192.168.203.65/31 | spine3-DC2 | Ethernet6 | 192.168.203.64/31 |
| borderleaf2-DC1 | Ethernet3 | 192.168.103.31/31 | spine1-DC1 | Ethernet7 | 192.168.103.30/31 |
| borderleaf2-DC1 | Ethernet4 | 192.168.103.33/31 | spine2-DC1 | Ethernet7 | 192.168.103.32/31 |
| borderleaf2-DC1 | Ethernet5 | 192.168.103.35/31 | spine3-DC1 | Ethernet7 | 192.168.103.34/31 |
| borderleaf2-DC2 | Ethernet3 | 192.168.203.67/31 | spine1-DC2 | Ethernet7 | 192.168.203.66/31 |
| borderleaf2-DC2 | Ethernet4 | 192.168.203.69/31 | spine2-DC2 | Ethernet7 | 192.168.203.68/31 |
| borderleaf2-DC2 | Ethernet5 | 192.168.203.71/31 | spine3-DC2 | Ethernet7 | 192.168.203.70/31 |
| leaf1-DC1 | Ethernet3 | 192.168.103.1/31 | spine1-DC1 | Ethernet2 | 192.168.103.0/31 |
| leaf1-DC1 | Ethernet4 | 192.168.103.3/31 | spine2-DC1 | Ethernet2 | 192.168.103.2/31 |
| leaf1-DC1 | Ethernet5 | 192.168.103.5/31 | spine3-DC1 | Ethernet2 | 192.168.103.4/31 |
| leaf1-DC2 | Ethernet3 | 192.168.203.37/31 | spine1-DC2 | Ethernet2 | 192.168.203.36/31 |
| leaf1-DC2 | Ethernet4 | 192.168.203.39/31 | spine2-DC2 | Ethernet2 | 192.168.203.38/31 |
| leaf1-DC2 | Ethernet5 | 192.168.203.41/31 | spine3-DC2 | Ethernet2 | 192.168.203.40/31 |
| leaf2-DC1 | Ethernet3 | 192.168.103.7/31 | spine1-DC1 | Ethernet3 | 192.168.103.6/31 |
| leaf2-DC1 | Ethernet4 | 192.168.103.9/31 | spine2-DC1 | Ethernet3 | 192.168.103.8/31 |
| leaf2-DC1 | Ethernet5 | 192.168.103.11/31 | spine3-DC1 | Ethernet3 | 192.168.103.10/31 |
| leaf2-DC2 | Ethernet3 | 192.168.203.43/31 | spine1-DC2 | Ethernet3 | 192.168.203.42/31 |
| leaf2-DC2 | Ethernet4 | 192.168.203.45/31 | spine2-DC2 | Ethernet3 | 192.168.203.44/31 |
| leaf2-DC2 | Ethernet5 | 192.168.203.47/31 | spine3-DC2 | Ethernet3 | 192.168.203.46/31 |
| leaf3-DC1 | Ethernet3 | 192.168.103.13/31 | spine1-DC1 | Ethernet4 | 192.168.103.12/31 |
| leaf3-DC1 | Ethernet4 | 192.168.103.15/31 | spine2-DC1 | Ethernet4 | 192.168.103.14/31 |
| leaf3-DC1 | Ethernet5 | 192.168.103.17/31 | spine3-DC1 | Ethernet4 | 192.168.103.16/31 |
| leaf3-DC2 | Ethernet3 | 192.168.203.49/31 | spine1-DC2 | Ethernet4 | 192.168.203.48/31 |
| leaf3-DC2 | Ethernet4 | 192.168.203.51/31 | spine2-DC2 | Ethernet4 | 192.168.203.50/31 |
| leaf3-DC2 | Ethernet5 | 192.168.203.53/31 | spine3-DC2 | Ethernet4 | 192.168.203.52/31 |
| leaf4-DC1 | Ethernet3 | 192.168.103.19/31 | spine1-DC1 | Ethernet5 | 192.168.103.18/31 |
| leaf4-DC1 | Ethernet4 | 192.168.103.21/31 | spine2-DC1 | Ethernet5 | 192.168.103.20/31 |
| leaf4-DC1 | Ethernet5 | 192.168.103.23/31 | spine3-DC1 | Ethernet5 | 192.168.103.22/31 |
| leaf4-DC2 | Ethernet3 | 192.168.203.55/31 | spine1-DC2 | Ethernet5 | 192.168.203.54/31 |
| leaf4-DC2 | Ethernet4 | 192.168.203.57/31 | spine2-DC2 | Ethernet5 | 192.168.203.56/31 |
| leaf4-DC2 | Ethernet5 | 192.168.203.59/31 | spine3-DC2 | Ethernet5 | 192.168.203.58/31 |

## Loopback Interfaces (BGP EVPN Peering)

| Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ------------- | ------------------- | ------------------ | ------------------ |
| 192.168.101.0/24 | 256 | 9 | 3.52 % |
| 192.168.201.0/24 | 256 | 9 | 3.52 % |

## Loopback0 Interfaces Node Allocation

| POD | Node | Loopback0 |
| --- | ---- | --------- |
| FABRIC | borderleaf1-DC1 | 192.168.101.5/32 |
| FABRIC | borderleaf1-DC2 | 192.168.201.11/32 |
| FABRIC | borderleaf2-DC1 | 192.168.101.6/32 |
| FABRIC | borderleaf2-DC2 | 192.168.201.12/32 |
| FABRIC | leaf1-DC1 | 192.168.101.1/32 |
| FABRIC | leaf1-DC2 | 192.168.201.7/32 |
| FABRIC | leaf2-DC1 | 192.168.101.2/32 |
| FABRIC | leaf2-DC2 | 192.168.201.8/32 |
| FABRIC | leaf3-DC1 | 192.168.101.3/32 |
| FABRIC | leaf3-DC2 | 192.168.201.9/32 |
| FABRIC | leaf4-DC1 | 192.168.101.4/32 |
| FABRIC | leaf4-DC2 | 192.168.201.10/32 |
| FABRIC | spine1-DC1 | 192.168.101.11/32 |
| FABRIC | spine1-DC2 | 192.168.201.14/32 |
| FABRIC | spine2-DC1 | 192.168.101.12/32 |
| FABRIC | spine2-DC2 | 192.168.201.15/32 |
| FABRIC | spine3-DC1 | 192.168.101.13/32 |
| FABRIC | spine3-DC2 | 192.168.201.16/32 |

## VTEP Loopback VXLAN Tunnel Source Interfaces (VTEPs Only)

| VTEP Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| --------------------- | ------------------- | ------------------ | ------------------ |
| 192.168.102.0/24 | 256 | 6 | 2.35 % |
| 192.168.202.0/24 | 256 | 6 | 2.35 % |

## VTEP Loopback Node allocation

| POD | Node | Loopback1 |
| --- | ---- | --------- |
| FABRIC | borderleaf1-DC1 | 192.168.102.5/32 |
| FABRIC | borderleaf1-DC2 | 192.168.202.11/32 |
| FABRIC | borderleaf2-DC1 | 192.168.102.5/32 |
| FABRIC | borderleaf2-DC2 | 192.168.202.11/32 |
| FABRIC | leaf1-DC1 | 192.168.102.1/32 |
| FABRIC | leaf1-DC2 | 192.168.202.7/32 |
| FABRIC | leaf2-DC1 | 192.168.102.1/32 |
| FABRIC | leaf2-DC2 | 192.168.202.7/32 |
| FABRIC | leaf3-DC1 | 192.168.102.3/32 |
| FABRIC | leaf3-DC2 | 192.168.202.9/32 |
| FABRIC | leaf4-DC1 | 192.168.102.3/32 |
| FABRIC | leaf4-DC2 | 192.168.202.9/32 |
