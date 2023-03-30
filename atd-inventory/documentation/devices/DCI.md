# DCI
# Table of Contents

- [Management](#management)
- [Authentication](#authentication)
- [Monitoring](#monitoring)
- [Internal VLAN Allocation Policy](#internal-vlan-allocation-policy)
  - [Internal VLAN Allocation Policy Summary](#internal-vlan-allocation-policy-summary)
- [Interfaces](#interfaces)
  - [Ethernet Interfaces](#ethernet-interfaces)
- [Routing](#routing)
  - [IP Routing](#ip-routing)
  - [IPv6 Routing](#ipv6-routing)
- [Multicast](#multicast)
- [Filters](#filters)
  - [Prefix-lists](#prefix-lists)
- [ACL](#acl)
- [Quality Of Service](#quality-of-service)

# Management

# Authentication

# Monitoring

# Internal VLAN Allocation Policy

## Internal VLAN Allocation Policy Summary

**Default Allocation Policy**

| Policy Allocation | Range Beginning | Range Ending |
| ------------------| --------------- | ------------ |
| ascending | 1006 | 4094 |

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
| Ethernet1 | To borderleaf1-DC1 | routed | - | 192.168.254.1/31 | default | 9214 | False | - | - |
| Ethernet2 | To borderleaf2-DC1 | routed | - | 192.168.254.3/31 | default | 9214 | False | - | - |
| Ethernet3 | To borderleaf1-DC2 | routed | - | 192.168.254.5/31 | default | 9214 | False | - | - |
| Ethernet4 | To borderleaf2-DC2 | routed | - | 192.168.254.7/31 | default | 9214 | False | - | - |

### Ethernet Interfaces Device Configuration

```eos
!
interface Ethernet1
   description To borderleaf1-DC1
   no shutdown
   mtu 9214
   no switchport
   ip address 192.168.254.1/31
!
interface Ethernet2
   description To borderleaf2-DC1
   no shutdown
   mtu 9214
   no switchport
   ip address 192.168.254.3/31
!
interface Ethernet3
   description To borderleaf1-DC2
   no shutdown
   mtu 9214
   no switchport
   ip address 192.168.254.5/31
!
interface Ethernet4
   description To borderleaf2-DC2
   no shutdown
   mtu 9214
   no switchport
   ip address 192.168.254.7/31
```

# Routing

## IP Routing

### IP Routing Summary

| VRF | Routing Enabled |
| --- | --------------- |
| default | False |

### IP Routing Device Configuration

```eos
```
## IPv6 Routing

### IPv6 Routing Summary

| VRF | Routing Enabled |
| --- | --------------- |
| default | False |

# Multicast

# Filters

## Prefix-lists

### Prefix-lists Summary

#### LOOPBACK

| Sequence | Action |
| -------- | ------ |
| 10 | permit 192.168.101.0/24 eq 32 |
| 20 | permit 192.168.102.0/24 eq 32 |
| 30 | permit 192.168.103.0/24 eq 32 |
| 40 | permit 192.168.103.0/24 eq 32 |
| 50 | permit 192.168.253.0/24 eq 32 |

### Prefix-lists Device Configuration

```eos
!
ip prefix-list LOOPBACK
   seq 10 permit 192.168.101.0/24 eq 32
   seq 20 permit 192.168.102.0/24 eq 32
   seq 30 permit 192.168.103.0/24 eq 32
   seq 40 permit 192.168.103.0/24 eq 32
   seq 50 permit 192.168.253.0/24 eq 32
```

# ACL

# Quality Of Service
