# ATD_FABRIC

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
| ATD_FABRIC | l3leaf | borderleaf1-DC1 | 192.168.0.25/24 | cEOS-LAB | Provisioned |
| ATD_FABRIC | l3leaf | borderleaf2-DC1 | 192.168.0.26/24 | cEOS-LAB | Provisioned |
| ATD_FABRIC | l3leaf | leaf1-DC1 | 192.168.0.21/24 | cEOS-LAB | Provisioned |
| ATD_FABRIC | l3leaf | leaf2-DC1 | 192.168.0.22/24 | cEOS-LAB | Provisioned |
| ATD_FABRIC | l3leaf | leaf3-DC1 | 192.168.0.23/24 | cEOS-LAB | Provisioned |
| ATD_FABRIC | l3leaf | leaf4-DC1 | 192.168.0.24/24 | cEOS-LAB | Provisioned |
| ATD_FABRIC | spine | spine1-DC1 | 192.168.0.11/24 | cEOS-LAB | Provisioned |
| ATD_FABRIC | spine | spine2-DC1 | 192.168.0.12/24 | cEOS-LAB | Provisioned |
| ATD_FABRIC | spine | spine3-DC1 | 192.168.0.13/24 | cEOS-LAB | Provisioned |

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
| l3leaf | borderleaf2-DC1 | Ethernet3 | spine | spine1-DC1 | Ethernet7 |
| l3leaf | borderleaf2-DC1 | Ethernet4 | spine | spine2-DC1 | Ethernet7 |
| l3leaf | borderleaf2-DC1 | Ethernet5 | spine | spine3-DC1 | Ethernet7 |
| l3leaf | leaf1-DC1 | Ethernet1 | mlag_peer | leaf2-DC1 | Ethernet1 |
| l3leaf | leaf1-DC1 | Ethernet2 | mlag_peer | leaf2-DC1 | Ethernet2 |
| l3leaf | leaf1-DC1 | Ethernet3 | spine | spine1-DC1 | Ethernet2 |
| l3leaf | leaf1-DC1 | Ethernet4 | spine | spine2-DC1 | Ethernet2 |
| l3leaf | leaf1-DC1 | Ethernet5 | spine | spine3-DC1 | Ethernet2 |
| l3leaf | leaf2-DC1 | Ethernet3 | spine | spine1-DC1 | Ethernet3 |
| l3leaf | leaf2-DC1 | Ethernet4 | spine | spine2-DC1 | Ethernet3 |
| l3leaf | leaf2-DC1 | Ethernet5 | spine | spine3-DC1 | Ethernet3 |
| l3leaf | leaf3-DC1 | Ethernet1 | mlag_peer | leaf4-DC1 | Ethernet1 |
| l3leaf | leaf3-DC1 | Ethernet2 | mlag_peer | leaf4-DC1 | Ethernet2 |
| l3leaf | leaf3-DC1 | Ethernet3 | spine | spine1-DC1 | Ethernet4 |
| l3leaf | leaf3-DC1 | Ethernet4 | spine | spine2-DC1 | Ethernet4 |
| l3leaf | leaf3-DC1 | Ethernet5 | spine | spine3-DC1 | Ethernet4 |
| l3leaf | leaf4-DC1 | Ethernet3 | spine | spine1-DC1 | Ethernet5 |
| l3leaf | leaf4-DC1 | Ethernet4 | spine | spine2-DC1 | Ethernet5 |
| l3leaf | leaf4-DC1 | Ethernet5 | spine | spine3-DC1 | Ethernet5 |

# Fabric IP Allocation

## Fabric Point-To-Point Links

| Uplink IPv4 Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ---------------- | ------------------- | ------------------ | ------------------ |
| 172.31.255.0/24 | 256 | 36 | 14.07 % |

## Point-To-Point Links Node Allocation

| Node | Node Interface | Node IP Address | Peer Node | Peer Interface | Peer IP Address |
| ---- | -------------- | --------------- | --------- | -------------- | --------------- |
| borderleaf1-DC1 | Ethernet3 | 172.31.255.25/31 | spine1-DC1 | Ethernet6 | 172.31.255.24/31 |
| borderleaf1-DC1 | Ethernet4 | 172.31.255.27/31 | spine2-DC1 | Ethernet6 | 172.31.255.26/31 |
| borderleaf1-DC1 | Ethernet5 | 172.31.255.29/31 | spine3-DC1 | Ethernet6 | 172.31.255.28/31 |
| borderleaf2-DC1 | Ethernet3 | 172.31.255.31/31 | spine1-DC1 | Ethernet7 | 172.31.255.30/31 |
| borderleaf2-DC1 | Ethernet4 | 172.31.255.33/31 | spine2-DC1 | Ethernet7 | 172.31.255.32/31 |
| borderleaf2-DC1 | Ethernet5 | 172.31.255.35/31 | spine3-DC1 | Ethernet7 | 172.31.255.34/31 |
| leaf1-DC1 | Ethernet3 | 172.31.255.1/31 | spine1-DC1 | Ethernet2 | 172.31.255.0/31 |
| leaf1-DC1 | Ethernet4 | 172.31.255.3/31 | spine2-DC1 | Ethernet2 | 172.31.255.2/31 |
| leaf1-DC1 | Ethernet5 | 172.31.255.5/31 | spine3-DC1 | Ethernet2 | 172.31.255.4/31 |
| leaf2-DC1 | Ethernet3 | 172.31.255.7/31 | spine1-DC1 | Ethernet3 | 172.31.255.6/31 |
| leaf2-DC1 | Ethernet4 | 172.31.255.9/31 | spine2-DC1 | Ethernet3 | 172.31.255.8/31 |
| leaf2-DC1 | Ethernet5 | 172.31.255.11/31 | spine3-DC1 | Ethernet3 | 172.31.255.10/31 |
| leaf3-DC1 | Ethernet3 | 172.31.255.13/31 | spine1-DC1 | Ethernet4 | 172.31.255.12/31 |
| leaf3-DC1 | Ethernet4 | 172.31.255.15/31 | spine2-DC1 | Ethernet4 | 172.31.255.14/31 |
| leaf3-DC1 | Ethernet5 | 172.31.255.17/31 | spine3-DC1 | Ethernet4 | 172.31.255.16/31 |
| leaf4-DC1 | Ethernet3 | 172.31.255.19/31 | spine1-DC1 | Ethernet5 | 172.31.255.18/31 |
| leaf4-DC1 | Ethernet4 | 172.31.255.21/31 | spine2-DC1 | Ethernet5 | 172.31.255.20/31 |
| leaf4-DC1 | Ethernet5 | 172.31.255.23/31 | spine3-DC1 | Ethernet5 | 172.31.255.22/31 |

## Loopback Interfaces (BGP EVPN Peering)

| Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ------------- | ------------------- | ------------------ | ------------------ |
| 192.0.200.0/24 | 256 | 9 | 3.52 % |

## Loopback0 Interfaces Node Allocation

| POD | Node | Loopback0 |
| --- | ---- | --------- |
| ATD_FABRIC | borderleaf1-DC1 | 192.0.200.7/32 |
| ATD_FABRIC | borderleaf2-DC1 | 192.0.200.8/32 |
| ATD_FABRIC | leaf1-DC1 | 192.0.200.3/32 |
| ATD_FABRIC | leaf2-DC1 | 192.0.200.4/32 |
| ATD_FABRIC | leaf3-DC1 | 192.0.200.5/32 |
| ATD_FABRIC | leaf4-DC1 | 192.0.200.6/32 |
| ATD_FABRIC | spine1-DC1 | 192.0.200.11/32 |
| ATD_FABRIC | spine2-DC1 | 192.0.200.12/32 |
| ATD_FABRIC | spine3-DC1 | 192.0.200.13/32 |

## VTEP Loopback VXLAN Tunnel Source Interfaces (VTEPs Only)

| VTEP Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| --------------------- | ------------------- | ------------------ | ------------------ |
| 192.0.254.0/24 | 256 | 6 | 2.35 % |

## VTEP Loopback Node allocation

| POD | Node | Loopback1 |
| --- | ---- | --------- |
| ATD_FABRIC | borderleaf1-DC1 | 192.0.254.7/32 |
| ATD_FABRIC | borderleaf2-DC1 | 192.0.254.7/32 |
| ATD_FABRIC | leaf1-DC1 | 192.0.254.3/32 |
| ATD_FABRIC | leaf2-DC1 | 192.0.254.3/32 |
| ATD_FABRIC | leaf3-DC1 | 192.0.254.5/32 |
| ATD_FABRIC | leaf4-DC1 | 192.0.254.5/32 |
