# spine3-DC1
# Table of Contents

- [Management](#management)
  - [Management Interfaces](#management-interfaces)
  - [DNS Domain](#dns-domain)
  - [Name Servers](#name-servers)
  - [Management API HTTP](#management-api-http)
- [Authentication](#authentication)
  - [Local Users](#local-users)
  - [RADIUS Servers](#radius-servers)
  - [AAA Server Groups](#aaa-server-groups)
- [Monitoring](#monitoring)
  - [TerminAttr Daemon](#terminattr-daemon)
- [Spanning Tree](#spanning-tree)
  - [Spanning Tree Summary](#spanning-tree-summary)
  - [Spanning Tree Device Configuration](#spanning-tree-device-configuration)
- [Internal VLAN Allocation Policy](#internal-vlan-allocation-policy)
  - [Internal VLAN Allocation Policy Summary](#internal-vlan-allocation-policy-summary)
  - [Internal VLAN Allocation Policy Configuration](#internal-vlan-allocation-policy-configuration)
- [Interfaces](#interfaces)
  - [Ethernet Interfaces](#ethernet-interfaces)
  - [Loopback Interfaces](#loopback-interfaces)
- [Routing](#routing)
  - [Service Routing Protocols Model](#service-routing-protocols-model)
  - [IP Routing](#ip-routing)
  - [IPv6 Routing](#ipv6-routing)
  - [Static Routes](#static-routes)
  - [Router BGP](#router-bgp)
- [BFD](#bfd)
  - [Router BFD](#router-bfd)
- [Multicast](#multicast)
- [Filters](#filters)
  - [Prefix-lists](#prefix-lists)
  - [Route-maps](#route-maps)
- [ACL](#acl)
- [VRF Instances](#vrf-instances)
  - [VRF Instances Summary](#vrf-instances-summary)
  - [VRF Instances Device Configuration](#vrf-instances-device-configuration)
- [Quality Of Service](#quality-of-service)

# Management

## Management Interfaces

### Management Interfaces Summary

#### IPv4

| Management Interface | description | Type | VRF | IP Address | Gateway |
| -------------------- | ----------- | ---- | --- | ---------- | ------- |
| Management0 | oob_management | oob | default | 192.168.0.13/24 | 192.168.0.1 |

#### IPv6

| Management Interface | description | Type | VRF | IPv6 Address | IPv6 Gateway |
| -------------------- | ----------- | ---- | --- | ------------ | ------------ |
| Management0 | oob_management | oob | default | - | - |

### Management Interfaces Device Configuration

```eos
!
interface Management0
   description oob_management
   no shutdown
   ip address 192.168.0.13/24
```

## DNS Domain

### DNS domain: atd.lab

### DNS Domain Device Configuration

```eos
dns domain atd.lab
!
```

## Name Servers

### Name Servers Summary

| Name Server | Source VRF |
| ----------- | ---------- |
| 192.168.2.1 | default |
| 8.8.8.8 | default |

### Name Servers Device Configuration

```eos
ip name-server vrf default 8.8.8.8
ip name-server vrf default 192.168.2.1
```

## Management API HTTP

### Management API HTTP Summary

| HTTP | HTTPS | Default Services |
| ---- | ----- | ---------------- |
| False | True | - |

### Management API VRF Access

| VRF Name | IPv4 ACL | IPv6 ACL |
| -------- | -------- | -------- |
| default | - | - |

### Management API HTTP Configuration

```eos
!
management api http-commands
   protocol https
   no shutdown
   !
   vrf default
      no shutdown
```

# Authentication

## Local Users

### Local Users Summary

| User | Privilege | Role | Disabled |
| ---- | --------- | ---- | -------- |
| ansible_local | 15 | network-admin | False |

### Local Users Device Configuration

```eos
!
username ansible_local privilege 15 role network-admin secret sha512 $6$Dzu11L7yp9j3nCM9$FSptxMPyIL555OMO.ldnjDXgwZmrfMYwHSr0uznE5Qoqvd9a6UdjiFcJUhGLtvXVZR1r.A/iF5aAt50hf/EK4/
```

## RADIUS Servers

### RADIUS Servers

| VRF | RADIUS Servers |
| --- | ---------------|
| default | 192.168.0.1 |

### RADIUS Servers Device Configuration

```eos
!
radius-server host 192.168.0.1 key 7 0207165218120E
```

## AAA Server Groups

### AAA Server Groups Summary

| Server Group Name | Type  | VRF | IP address |
| ------------------| ----- | --- | ---------- |
| atds | radius | default | 192.168.0.1 |

### AAA Server Groups Device Configuration

```eos
!
aaa group server radius atds
   server 192.168.0.1
```

# Monitoring

## TerminAttr Daemon

### TerminAttr Daemon Summary

| CV Compression | CloudVision Servers | VRF | Authentication | Smash Excludes | Ingest Exclude | Bypass AAA |
| -------------- | ------------------- | --- | -------------- | -------------- | -------------- | ---------- |
| gzip | 192.168.0.5:9910 | default | key,atd-lab | ale,flexCounter,hardware,kni,pulse,strata | /Sysdb/cell/1/agent,/Sysdb/cell/2/agent | False |

### TerminAttr Daemon Device Configuration

```eos
!
daemon TerminAttr
   exec /usr/bin/TerminAttr -cvaddr=192.168.0.5:9910 -cvauth=key,atd-lab -cvvrf=default -smashexcludes=ale,flexCounter,hardware,kni,pulse,strata -ingestexclude=/Sysdb/cell/1/agent,/Sysdb/cell/2/agent -taillogs
   no shutdown
```

# Spanning Tree

## Spanning Tree Summary

STP mode: **none**

## Spanning Tree Device Configuration

```eos
!
spanning-tree mode none
```

# Internal VLAN Allocation Policy

## Internal VLAN Allocation Policy Summary

| Policy Allocation | Range Beginning | Range Ending |
| ------------------| --------------- | ------------ |
| ascending | 1006 | 1199 |

## Internal VLAN Allocation Policy Configuration

```eos
!
vlan internal order ascending range 1006 1199
```

# Interfaces

## Ethernet Interfaces

### Ethernet Interfaces Summary

#### L2

| Interface | Description | Mode | VLANs | Native VLAN | Trunk Group | Channel-Group |
| --------- | ----------- | ---- | ----- | ----------- | ----------- | ------------- |

*Inherited from Port-Channel Interface

#### IPv4

| Interface | Description | Type | Channel Group | IP Address | VRF |  MTU | Shutdown | ACL In | ACL Out |
| --------- | ----------- | -----| ------------- | ---------- | ----| ---- | -------- | ------ | ------- |
| Ethernet2 | P2P_LINK_TO_LEAF1-DC1_Ethernet5 | routed | - | 192.168.103.4/31 | default | 1500 | False | - | - |
| Ethernet3 | P2P_LINK_TO_LEAF2-DC1_Ethernet5 | routed | - | 192.168.103.10/31 | default | 1500 | False | - | - |
| Ethernet4 | P2P_LINK_TO_LEAF3-DC1_Ethernet5 | routed | - | 192.168.103.16/31 | default | 1500 | False | - | - |
| Ethernet5 | P2P_LINK_TO_LEAF4-DC1_Ethernet5 | routed | - | 192.168.103.22/31 | default | 1500 | False | - | - |
| Ethernet6 | P2P_LINK_TO_BORDERLEAF1-DC1_Ethernet5 | routed | - | 192.168.103.28/31 | default | 1500 | False | - | - |
| Ethernet7 | P2P_LINK_TO_BORDERLEAF2-DC1_Ethernet5 | routed | - | 192.168.103.34/31 | default | 1500 | False | - | - |

### Ethernet Interfaces Device Configuration

```eos
!
interface Ethernet2
   description P2P_LINK_TO_LEAF1-DC1_Ethernet5
   no shutdown
   mtu 1500
   no switchport
   ip address 192.168.103.4/31
!
interface Ethernet3
   description P2P_LINK_TO_LEAF2-DC1_Ethernet5
   no shutdown
   mtu 1500
   no switchport
   ip address 192.168.103.10/31
!
interface Ethernet4
   description P2P_LINK_TO_LEAF3-DC1_Ethernet5
   no shutdown
   mtu 1500
   no switchport
   ip address 192.168.103.16/31
!
interface Ethernet5
   description P2P_LINK_TO_LEAF4-DC1_Ethernet5
   no shutdown
   mtu 1500
   no switchport
   ip address 192.168.103.22/31
!
interface Ethernet6
   description P2P_LINK_TO_BORDERLEAF1-DC1_Ethernet5
   no shutdown
   mtu 1500
   no switchport
   ip address 192.168.103.28/31
!
interface Ethernet7
   description P2P_LINK_TO_BORDERLEAF2-DC1_Ethernet5
   no shutdown
   mtu 1500
   no switchport
   ip address 192.168.103.34/31
```

## Loopback Interfaces

### Loopback Interfaces Summary

#### IPv4

| Interface | Description | VRF | IP Address |
| --------- | ----------- | --- | ---------- |
| Loopback0 | EVPN_Overlay_Peering | default | 192.168.101.13/32 |

#### IPv6

| Interface | Description | VRF | IPv6 Address |
| --------- | ----------- | --- | ------------ |
| Loopback0 | EVPN_Overlay_Peering | default | - |


### Loopback Interfaces Device Configuration

```eos
!
interface Loopback0
   description EVPN_Overlay_Peering
   no shutdown
   ip address 192.168.101.13/32
```

# Routing
## Service Routing Protocols Model

Multi agent routing protocol model enabled

```eos
!
service routing protocols model multi-agent
```

## IP Routing

### IP Routing Summary

| VRF | Routing Enabled |
| --- | --------------- |
| default | True |
| default | false |

### IP Routing Device Configuration

```eos
!
ip routing
```
## IPv6 Routing

### IPv6 Routing Summary

| VRF | Routing Enabled |
| --- | --------------- |
| default | False |
| default | false |

## Static Routes

### Static Routes Summary

| VRF | Destination Prefix | Next Hop IP             | Exit interface      | Administrative Distance       | Tag               | Route Name                    | Metric         |
| --- | ------------------ | ----------------------- | ------------------- | ----------------------------- | ----------------- | ----------------------------- | -------------- |
| default | 0.0.0.0/0 | 192.168.0.1 | - | 1 | - | - | - |

### Static Routes Device Configuration

```eos
!
ip route 0.0.0.0/0 192.168.0.1
```

## Router BGP

### Router BGP Summary

| BGP AS | Router ID |
| ------ | --------- |
| 65100|  192.168.101.13 |

| BGP Tuning |
| ---------- |
| no bgp default ipv4-unicast |
| distance bgp 20 200 200 |
| graceful-restart restart-time 300 |
| graceful-restart |
| maximum-paths 4 ecmp 4 |

### Router BGP Peer Groups

#### EVPN-OVERLAY-PEERS

| Settings | Value |
| -------- | ----- |
| Address Family | evpn |
| Next-hop unchanged | True |
| Source | Loopback0 |
| BFD | True |
| Ebgp multihop | 3 |
| Send community | all |
| Maximum routes | 0 (no limit) |

#### IPv4-UNDERLAY-PEERS

| Settings | Value |
| -------- | ----- |
| Address Family | ipv4 |
| Send community | all |
| Maximum routes | 12000 |

### BGP Neighbors

| Neighbor | Remote AS | VRF | Shutdown | Send-community | Maximum-routes | Allowas-in | BFD | RIB Pre-Policy Retain | Route-Reflector Client |
| -------- | --------- | --- | -------- | -------------- | -------------- | ---------- | --- | --------------------- | ---------------------- |
| 192.168.101.1 | 65101 | default | - | Inherited from peer group EVPN-OVERLAY-PEERS | Inherited from peer group EVPN-OVERLAY-PEERS | - | Inherited from peer group EVPN-OVERLAY-PEERS | - | - |
| 192.168.101.2 | 65101 | default | - | Inherited from peer group EVPN-OVERLAY-PEERS | Inherited from peer group EVPN-OVERLAY-PEERS | - | Inherited from peer group EVPN-OVERLAY-PEERS | - | - |
| 192.168.101.3 | 65103 | default | - | Inherited from peer group EVPN-OVERLAY-PEERS | Inherited from peer group EVPN-OVERLAY-PEERS | - | Inherited from peer group EVPN-OVERLAY-PEERS | - | - |
| 192.168.101.4 | 65103 | default | - | Inherited from peer group EVPN-OVERLAY-PEERS | Inherited from peer group EVPN-OVERLAY-PEERS | - | Inherited from peer group EVPN-OVERLAY-PEERS | - | - |
| 192.168.101.5 | 65103 | default | - | Inherited from peer group EVPN-OVERLAY-PEERS | Inherited from peer group EVPN-OVERLAY-PEERS | - | Inherited from peer group EVPN-OVERLAY-PEERS | - | - |
| 192.168.101.6 | 65103 | default | - | Inherited from peer group EVPN-OVERLAY-PEERS | Inherited from peer group EVPN-OVERLAY-PEERS | - | Inherited from peer group EVPN-OVERLAY-PEERS | - | - |
| 192.168.103.5 | 65101 | default | - | Inherited from peer group IPv4-UNDERLAY-PEERS | Inherited from peer group IPv4-UNDERLAY-PEERS | - | - | - | - |
| 192.168.103.11 | 65101 | default | - | Inherited from peer group IPv4-UNDERLAY-PEERS | Inherited from peer group IPv4-UNDERLAY-PEERS | - | - | - | - |
| 192.168.103.17 | 65103 | default | - | Inherited from peer group IPv4-UNDERLAY-PEERS | Inherited from peer group IPv4-UNDERLAY-PEERS | - | - | - | - |
| 192.168.103.23 | 65103 | default | - | Inherited from peer group IPv4-UNDERLAY-PEERS | Inherited from peer group IPv4-UNDERLAY-PEERS | - | - | - | - |
| 192.168.103.29 | 65103 | default | - | Inherited from peer group IPv4-UNDERLAY-PEERS | Inherited from peer group IPv4-UNDERLAY-PEERS | - | - | - | - |
| 192.168.103.35 | 65103 | default | - | Inherited from peer group IPv4-UNDERLAY-PEERS | Inherited from peer group IPv4-UNDERLAY-PEERS | - | - | - | - |

### Router BGP EVPN Address Family

#### EVPN Peer Groups

| Peer Group | Activate |
| ---------- | -------- |
| EVPN-OVERLAY-PEERS | True |

### Router BGP Device Configuration

```eos
!
router bgp 65100
   router-id 192.168.101.13
   no bgp default ipv4-unicast
   distance bgp 20 200 200
   graceful-restart restart-time 300
   graceful-restart
   maximum-paths 4 ecmp 4
   neighbor EVPN-OVERLAY-PEERS peer group
   neighbor EVPN-OVERLAY-PEERS next-hop-unchanged
   neighbor EVPN-OVERLAY-PEERS update-source Loopback0
   neighbor EVPN-OVERLAY-PEERS bfd
   neighbor EVPN-OVERLAY-PEERS ebgp-multihop 3
   neighbor EVPN-OVERLAY-PEERS password 7 q+VNViP5i4rVjW1cxFv2wA==
   neighbor EVPN-OVERLAY-PEERS send-community
   neighbor EVPN-OVERLAY-PEERS maximum-routes 0
   neighbor IPv4-UNDERLAY-PEERS peer group
   neighbor IPv4-UNDERLAY-PEERS password 7 AQQvKeimxJu+uGQ/yYvv9w==
   neighbor IPv4-UNDERLAY-PEERS send-community
   neighbor IPv4-UNDERLAY-PEERS maximum-routes 12000
   neighbor 192.168.101.1 peer group EVPN-OVERLAY-PEERS
   neighbor 192.168.101.1 remote-as 65101
   neighbor 192.168.101.1 description leaf1-DC1
   neighbor 192.168.101.2 peer group EVPN-OVERLAY-PEERS
   neighbor 192.168.101.2 remote-as 65101
   neighbor 192.168.101.2 description leaf2-DC1
   neighbor 192.168.101.3 peer group EVPN-OVERLAY-PEERS
   neighbor 192.168.101.3 remote-as 65103
   neighbor 192.168.101.3 description leaf3-DC1
   neighbor 192.168.101.4 peer group EVPN-OVERLAY-PEERS
   neighbor 192.168.101.4 remote-as 65103
   neighbor 192.168.101.4 description leaf4-DC1
   neighbor 192.168.101.5 peer group EVPN-OVERLAY-PEERS
   neighbor 192.168.101.5 remote-as 65103
   neighbor 192.168.101.5 description borderleaf1-DC1
   neighbor 192.168.101.6 peer group EVPN-OVERLAY-PEERS
   neighbor 192.168.101.6 remote-as 65103
   neighbor 192.168.101.6 description borderleaf2-DC1
   neighbor 192.168.103.5 peer group IPv4-UNDERLAY-PEERS
   neighbor 192.168.103.5 remote-as 65101
   neighbor 192.168.103.5 description leaf1-DC1_Ethernet5
   neighbor 192.168.103.11 peer group IPv4-UNDERLAY-PEERS
   neighbor 192.168.103.11 remote-as 65101
   neighbor 192.168.103.11 description leaf2-DC1_Ethernet5
   neighbor 192.168.103.17 peer group IPv4-UNDERLAY-PEERS
   neighbor 192.168.103.17 remote-as 65103
   neighbor 192.168.103.17 description leaf3-DC1_Ethernet5
   neighbor 192.168.103.23 peer group IPv4-UNDERLAY-PEERS
   neighbor 192.168.103.23 remote-as 65103
   neighbor 192.168.103.23 description leaf4-DC1_Ethernet5
   neighbor 192.168.103.29 peer group IPv4-UNDERLAY-PEERS
   neighbor 192.168.103.29 remote-as 65103
   neighbor 192.168.103.29 description borderleaf1-DC1_Ethernet5
   neighbor 192.168.103.35 peer group IPv4-UNDERLAY-PEERS
   neighbor 192.168.103.35 remote-as 65103
   neighbor 192.168.103.35 description borderleaf2-DC1_Ethernet5
   redistribute connected route-map RM-CONN-2-BGP
   !
   address-family evpn
      neighbor EVPN-OVERLAY-PEERS activate
   !
   address-family ipv4
      no neighbor EVPN-OVERLAY-PEERS activate
      neighbor IPv4-UNDERLAY-PEERS activate
```

# BFD

## Router BFD

### Router BFD Multihop Summary

| Interval | Minimum RX | Multiplier |
| -------- | ---------- | ---------- |
| 1200 | 1200 | 3 |

### Router BFD Device Configuration

```eos
!
router bfd
   multihop interval 1200 min-rx 1200 multiplier 3
```

# Multicast

# Filters

## Prefix-lists

### Prefix-lists Summary

#### PL-LOOPBACKS-EVPN-OVERLAY

| Sequence | Action |
| -------- | ------ |
| 10 | permit 192.168.101.0/24 eq 32 |

### Prefix-lists Device Configuration

```eos
!
ip prefix-list PL-LOOPBACKS-EVPN-OVERLAY
   seq 10 permit 192.168.101.0/24 eq 32
```

## Route-maps

### Route-maps Summary

#### RM-CONN-2-BGP

| Sequence | Type | Match | Set | Sub-Route-Map | Continue |
| -------- | ---- | ----- | --- | ------------- | -------- |
| 10 | permit | ip address prefix-list PL-LOOPBACKS-EVPN-OVERLAY | - | - | - |

### Route-maps Device Configuration

```eos
!
route-map RM-CONN-2-BGP permit 10
   match ip address prefix-list PL-LOOPBACKS-EVPN-OVERLAY
```

# ACL

# VRF Instances

## VRF Instances Summary

| VRF Name | IP Routing |
| -------- | ---------- |
| default | disabled |

## VRF Instances Device Configuration

```eos
```

# Quality Of Service
