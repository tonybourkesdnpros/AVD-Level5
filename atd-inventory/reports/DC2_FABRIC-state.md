
# Validate State Report

**Table of Contents:**

- [Validate State Report](validate-state-report)
  - [Test Results Summary](#test-results-summary)
  - [Failed Test Results Summary](#failed-test-results-summary)
  - [All Test Results](#all-test-results)

## Test Results Summary

### Summary Totals

| Total Tests | Total Tests Passed | Total Tests Failed |
| ----------- | ------------------ | ------------------ |
| 429 | 427 | 2 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| borderleaf1-DC2 |  53 | 53 | 0 | - |
| borderleaf2-DC2 |  53 | 53 | 0 | - |
| leaf1-DC2 |  56 | 56 | 0 | - |
| leaf2-DC2 |  56 | 56 | 0 | - |
| leaf3-DC2 |  56 | 55 | 1 | Interface State |
| leaf4-DC2 |  56 | 55 | 1 | Interface State |
| spine1-DC2 |  33 | 33 | 0 | - |
| spine2-DC2 |  33 | 33 | 0 | - |
| spine3-DC2 |  33 | 33 | 0 | - |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| NTP |  9 | 9 | 0 |
| Interface State |  117 | 115 | 2 |
| LLDP Topology |  48 | 48 | 0 |
| MLAG |  6 | 6 | 0 |
| IP Reachability |  36 | 36 | 0 |
| BGP |  87 | 87 | 0 |
| Routing Table |  72 | 72 | 0 |
| Loopback0 Reachability |  54 | 54 | 0 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 73 | leaf3-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host2-DC2_Host2-DC2 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 75 | leaf4-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host2-DC2_Host2-DC2 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |

## All Test Results

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | borderleaf1-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 2 | borderleaf2-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 3 | leaf1-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 4 | leaf2-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 5 | leaf3-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 6 | leaf4-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 7 | spine1-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 8 | spine2-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 9 | spine3-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 10 | borderleaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_borderleaf2-DC2_Ethernet1 | PASS | - |
| 11 | borderleaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_borderleaf2-DC2_Ethernet2 | PASS | - |
| 12 | borderleaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC2_Ethernet6 | PASS | - |
| 13 | borderleaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC2_Ethernet6 | PASS | - |
| 14 | borderleaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC2_Ethernet6 | PASS | - |
| 15 | borderleaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_borderleaf1-DC2_Ethernet1 | PASS | - |
| 16 | borderleaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_borderleaf1-DC2_Ethernet2 | PASS | - |
| 17 | borderleaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC2_Ethernet7 | PASS | - |
| 18 | borderleaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC2_Ethernet7 | PASS | - |
| 19 | borderleaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC2_Ethernet7 | PASS | - |
| 20 | leaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf2-DC2_Ethernet1 | PASS | - |
| 21 | leaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf2-DC2_Ethernet2 | PASS | - |
| 22 | leaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC2_Ethernet2 | PASS | - |
| 23 | leaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC2_Ethernet2 | PASS | - |
| 24 | leaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC2_Ethernet2 | PASS | - |
| 25 | leaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - host1-DC2_Eth1 | PASS | - |
| 26 | leaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1-DC2_Eth2 | PASS | - |
| 27 | leaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf1-DC2_Ethernet1 | PASS | - |
| 28 | leaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf1-DC2_Ethernet2 | PASS | - |
| 29 | leaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC2_Ethernet3 | PASS | - |
| 30 | leaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC2_Ethernet3 | PASS | - |
| 31 | leaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC2_Ethernet3 | PASS | - |
| 32 | leaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - host1-DC2_Eth3 | PASS | - |
| 33 | leaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1-DC2_Eth4 | PASS | - |
| 34 | leaf3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf4-DC2_Ethernet1 | PASS | - |
| 35 | leaf3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf4-DC2_Ethernet2 | PASS | - |
| 36 | leaf3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC2_Ethernet4 | PASS | - |
| 37 | leaf3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC2_Ethernet4 | PASS | - |
| 38 | leaf3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC2_Ethernet4 | PASS | - |
| 39 | leaf3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - host2-DC2_Eth1 | PASS | - |
| 40 | leaf3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2-DC2_Eth2 | PASS | - |
| 41 | leaf4-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf3-DC2_Ethernet1 | PASS | - |
| 42 | leaf4-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf3-DC2_Ethernet2 | PASS | - |
| 43 | leaf4-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC2_Ethernet5 | PASS | - |
| 44 | leaf4-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC2_Ethernet5 | PASS | - |
| 45 | leaf4-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC2_Ethernet5 | PASS | - |
| 46 | leaf4-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - host2-DC2_Eth3 | PASS | - |
| 47 | leaf4-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2-DC2_Eth4 | PASS | - |
| 48 | spine1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1-DC2_Ethernet3 | PASS | - |
| 49 | spine1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2-DC2_Ethernet3 | PASS | - |
| 50 | spine1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3-DC2_Ethernet3 | PASS | - |
| 51 | spine1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4-DC2_Ethernet3 | PASS | - |
| 52 | spine1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1-DC2_Ethernet3 | PASS | - |
| 53 | spine1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2-DC2_Ethernet3 | PASS | - |
| 54 | spine2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1-DC2_Ethernet4 | PASS | - |
| 55 | spine2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2-DC2_Ethernet4 | PASS | - |
| 56 | spine2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3-DC2_Ethernet4 | PASS | - |
| 57 | spine2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4-DC2_Ethernet4 | PASS | - |
| 58 | spine2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1-DC2_Ethernet4 | PASS | - |
| 59 | spine2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2-DC2_Ethernet4 | PASS | - |
| 60 | spine3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1-DC2_Ethernet5 | PASS | - |
| 61 | spine3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2-DC2_Ethernet5 | PASS | - |
| 62 | spine3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3-DC2_Ethernet5 | PASS | - |
| 63 | spine3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4-DC2_Ethernet5 | PASS | - |
| 64 | spine3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1-DC2_Ethernet5 | PASS | - |
| 65 | spine3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2-DC2_Ethernet5 | PASS | - |
| 66 | borderleaf1-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_borderleaf2-DC2_Po1 | PASS | - |
| 67 | borderleaf2-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_borderleaf1-DC2_Po1 | PASS | - |
| 68 | leaf1-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf2-DC2_Po1 | PASS | - |
| 69 | leaf1-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host1-DC2_Host1-DC2 | PASS | - |
| 70 | leaf2-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf1-DC2_Po1 | PASS | - |
| 71 | leaf2-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host1-DC2_Host1-DC2 | PASS | - |
| 72 | leaf3-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf4-DC2_Po1 | PASS | - |
| 73 | leaf3-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host2-DC2_Host2-DC2 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 74 | leaf4-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf3-DC2_Po1 | PASS | - |
| 75 | leaf4-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host2-DC2_Host2-DC2 | FAIL | Interface shutdown: False - interface status: down - line protocol status: lowerLayerDown |
| 76 | borderleaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 77 | borderleaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 78 | borderleaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 79 | borderleaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 80 | borderleaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 81 | borderleaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 82 | borderleaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 83 | borderleaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 84 | borderleaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 85 | borderleaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 86 | leaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 87 | leaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 88 | leaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 89 | leaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 90 | leaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 91 | leaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 92 | leaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 93 | leaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 94 | leaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 95 | leaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 96 | leaf3-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 97 | leaf3-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 98 | leaf3-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 99 | leaf3-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 100 | leaf3-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 101 | leaf4-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 102 | leaf4-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 103 | leaf4-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 104 | leaf4-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 105 | leaf4-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 106 | borderleaf1-DC2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 107 | borderleaf2-DC2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 108 | leaf1-DC2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 109 | leaf2-DC2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 110 | leaf3-DC2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 111 | leaf4-DC2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 112 | borderleaf1-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 113 | borderleaf1-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 114 | borderleaf2-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 115 | borderleaf2-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 116 | leaf1-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 117 | leaf1-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 118 | leaf2-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 119 | leaf2-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 120 | leaf3-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 121 | leaf3-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 122 | leaf4-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 123 | leaf4-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 124 | spine1-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 125 | spine2-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 126 | spine3-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 127 | borderleaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: borderleaf2-DC2_Ethernet1 | PASS | - |
| 128 | borderleaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: borderleaf2-DC2_Ethernet2 | PASS | - |
| 129 | borderleaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC2_Ethernet6 | PASS | - |
| 130 | borderleaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC2_Ethernet6 | PASS | - |
| 131 | borderleaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC2_Ethernet6 | PASS | - |
| 132 | borderleaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: borderleaf1-DC2_Ethernet1 | PASS | - |
| 133 | borderleaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: borderleaf1-DC2_Ethernet2 | PASS | - |
| 134 | borderleaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC2_Ethernet7 | PASS | - |
| 135 | borderleaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC2_Ethernet7 | PASS | - |
| 136 | borderleaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC2_Ethernet7 | PASS | - |
| 137 | leaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf2-DC2_Ethernet1 | PASS | - |
| 138 | leaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf2-DC2_Ethernet2 | PASS | - |
| 139 | leaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC2_Ethernet2 | PASS | - |
| 140 | leaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC2_Ethernet2 | PASS | - |
| 141 | leaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC2_Ethernet2 | PASS | - |
| 142 | leaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf1-DC2_Ethernet1 | PASS | - |
| 143 | leaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC2_Ethernet2 | PASS | - |
| 144 | leaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC2_Ethernet3 | PASS | - |
| 145 | leaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC2_Ethernet3 | PASS | - |
| 146 | leaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC2_Ethernet3 | PASS | - |
| 147 | leaf3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf4-DC2_Ethernet1 | PASS | - |
| 148 | leaf3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf4-DC2_Ethernet2 | PASS | - |
| 149 | leaf3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC2_Ethernet4 | PASS | - |
| 150 | leaf3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC2_Ethernet4 | PASS | - |
| 151 | leaf3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC2_Ethernet4 | PASS | - |
| 152 | leaf4-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf3-DC2_Ethernet1 | PASS | - |
| 153 | leaf4-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf3-DC2_Ethernet2 | PASS | - |
| 154 | leaf4-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC2_Ethernet5 | PASS | - |
| 155 | leaf4-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC2_Ethernet5 | PASS | - |
| 156 | leaf4-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC2_Ethernet5 | PASS | - |
| 157 | spine1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC2_Ethernet3 | PASS | - |
| 158 | spine1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2-DC2_Ethernet3 | PASS | - |
| 159 | spine1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3-DC2_Ethernet3 | PASS | - |
| 160 | spine1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4-DC2_Ethernet3 | PASS | - |
| 161 | spine1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1-DC2_Ethernet3 | PASS | - |
| 162 | spine1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2-DC2_Ethernet3 | PASS | - |
| 163 | spine2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC2_Ethernet4 | PASS | - |
| 164 | spine2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2-DC2_Ethernet4 | PASS | - |
| 165 | spine2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3-DC2_Ethernet4 | PASS | - |
| 166 | spine2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4-DC2_Ethernet4 | PASS | - |
| 167 | spine2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1-DC2_Ethernet4 | PASS | - |
| 168 | spine2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2-DC2_Ethernet4 | PASS | - |
| 169 | spine3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC2_Ethernet5 | PASS | - |
| 170 | spine3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2-DC2_Ethernet5 | PASS | - |
| 171 | spine3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3-DC2_Ethernet5 | PASS | - |
| 172 | spine3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4-DC2_Ethernet5 | PASS | - |
| 173 | spine3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1-DC2_Ethernet5 | PASS | - |
| 174 | spine3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2-DC2_Ethernet5 | PASS | - |
| 175 | borderleaf1-DC2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 176 | borderleaf2-DC2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 177 | leaf1-DC2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 178 | leaf2-DC2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 179 | leaf3-DC2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 180 | leaf4-DC2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 181 | borderleaf1-DC2 | IP Reachability | ip reachability test p2p links | Source: borderleaf1-DC2_Ethernet3 - Destination: spine1-DC2_Ethernet6 | PASS | - |
| 182 | borderleaf1-DC2 | IP Reachability | ip reachability test p2p links | Source: borderleaf1-DC2_Ethernet4 - Destination: spine2-DC2_Ethernet6 | PASS | - |
| 183 | borderleaf1-DC2 | IP Reachability | ip reachability test p2p links | Source: borderleaf1-DC2_Ethernet5 - Destination: spine3-DC2_Ethernet6 | PASS | - |
| 184 | borderleaf2-DC2 | IP Reachability | ip reachability test p2p links | Source: borderleaf2-DC2_Ethernet3 - Destination: spine1-DC2_Ethernet7 | PASS | - |
| 185 | borderleaf2-DC2 | IP Reachability | ip reachability test p2p links | Source: borderleaf2-DC2_Ethernet4 - Destination: spine2-DC2_Ethernet7 | PASS | - |
| 186 | borderleaf2-DC2 | IP Reachability | ip reachability test p2p links | Source: borderleaf2-DC2_Ethernet5 - Destination: spine3-DC2_Ethernet7 | PASS | - |
| 187 | leaf1-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC2_Ethernet3 - Destination: spine1-DC2_Ethernet2 | PASS | - |
| 188 | leaf1-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC2_Ethernet4 - Destination: spine2-DC2_Ethernet2 | PASS | - |
| 189 | leaf1-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC2_Ethernet5 - Destination: spine3-DC2_Ethernet2 | PASS | - |
| 190 | leaf2-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC2_Ethernet3 - Destination: spine1-DC2_Ethernet3 | PASS | - |
| 191 | leaf2-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC2_Ethernet4 - Destination: spine2-DC2_Ethernet3 | PASS | - |
| 192 | leaf2-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC2_Ethernet5 - Destination: spine3-DC2_Ethernet3 | PASS | - |
| 193 | leaf3-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC2_Ethernet3 - Destination: spine1-DC2_Ethernet4 | PASS | - |
| 194 | leaf3-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC2_Ethernet4 - Destination: spine2-DC2_Ethernet4 | PASS | - |
| 195 | leaf3-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC2_Ethernet5 - Destination: spine3-DC2_Ethernet4 | PASS | - |
| 196 | leaf4-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC2_Ethernet3 - Destination: spine1-DC2_Ethernet5 | PASS | - |
| 197 | leaf4-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC2_Ethernet4 - Destination: spine2-DC2_Ethernet5 | PASS | - |
| 198 | leaf4-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC2_Ethernet5 - Destination: spine3-DC2_Ethernet5 | PASS | - |
| 199 | spine1-DC2 | IP Reachability | ip reachability test p2p links | Source: spine1-DC2_Ethernet2 - Destination: leaf1-DC2_Ethernet3 | PASS | - |
| 200 | spine1-DC2 | IP Reachability | ip reachability test p2p links | Source: spine1-DC2_Ethernet3 - Destination: leaf2-DC2_Ethernet3 | PASS | - |
| 201 | spine1-DC2 | IP Reachability | ip reachability test p2p links | Source: spine1-DC2_Ethernet4 - Destination: leaf3-DC2_Ethernet3 | PASS | - |
| 202 | spine1-DC2 | IP Reachability | ip reachability test p2p links | Source: spine1-DC2_Ethernet5 - Destination: leaf4-DC2_Ethernet3 | PASS | - |
| 203 | spine1-DC2 | IP Reachability | ip reachability test p2p links | Source: spine1-DC2_Ethernet6 - Destination: borderleaf1-DC2_Ethernet3 | PASS | - |
| 204 | spine1-DC2 | IP Reachability | ip reachability test p2p links | Source: spine1-DC2_Ethernet7 - Destination: borderleaf2-DC2_Ethernet3 | PASS | - |
| 205 | spine2-DC2 | IP Reachability | ip reachability test p2p links | Source: spine2-DC2_Ethernet2 - Destination: leaf1-DC2_Ethernet4 | PASS | - |
| 206 | spine2-DC2 | IP Reachability | ip reachability test p2p links | Source: spine2-DC2_Ethernet3 - Destination: leaf2-DC2_Ethernet4 | PASS | - |
| 207 | spine2-DC2 | IP Reachability | ip reachability test p2p links | Source: spine2-DC2_Ethernet4 - Destination: leaf3-DC2_Ethernet4 | PASS | - |
| 208 | spine2-DC2 | IP Reachability | ip reachability test p2p links | Source: spine2-DC2_Ethernet5 - Destination: leaf4-DC2_Ethernet4 | PASS | - |
| 209 | spine2-DC2 | IP Reachability | ip reachability test p2p links | Source: spine2-DC2_Ethernet6 - Destination: borderleaf1-DC2_Ethernet4 | PASS | - |
| 210 | spine2-DC2 | IP Reachability | ip reachability test p2p links | Source: spine2-DC2_Ethernet7 - Destination: borderleaf2-DC2_Ethernet4 | PASS | - |
| 211 | spine3-DC2 | IP Reachability | ip reachability test p2p links | Source: spine3-DC2_Ethernet2 - Destination: leaf1-DC2_Ethernet5 | PASS | - |
| 212 | spine3-DC2 | IP Reachability | ip reachability test p2p links | Source: spine3-DC2_Ethernet3 - Destination: leaf2-DC2_Ethernet5 | PASS | - |
| 213 | spine3-DC2 | IP Reachability | ip reachability test p2p links | Source: spine3-DC2_Ethernet4 - Destination: leaf3-DC2_Ethernet5 | PASS | - |
| 214 | spine3-DC2 | IP Reachability | ip reachability test p2p links | Source: spine3-DC2_Ethernet5 - Destination: leaf4-DC2_Ethernet5 | PASS | - |
| 215 | spine3-DC2 | IP Reachability | ip reachability test p2p links | Source: spine3-DC2_Ethernet6 - Destination: borderleaf1-DC2_Ethernet5 | PASS | - |
| 216 | spine3-DC2 | IP Reachability | ip reachability test p2p links | Source: spine3-DC2_Ethernet7 - Destination: borderleaf2-DC2_Ethernet5 | PASS | - |
| 217 | borderleaf1-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 218 | borderleaf2-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 219 | leaf1-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 220 | leaf2-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 221 | leaf3-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 222 | leaf4-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 223 | spine1-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 224 | spine2-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 225 | spine3-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 226 | borderleaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.9 | PASS | - |
| 227 | borderleaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.24 | PASS | - |
| 228 | borderleaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.26 | PASS | - |
| 229 | borderleaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.28 | PASS | - |
| 230 | borderleaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.8 | PASS | - |
| 231 | borderleaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.30 | PASS | - |
| 232 | borderleaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.32 | PASS | - |
| 233 | borderleaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.34 | PASS | - |
| 234 | leaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.1 | PASS | - |
| 235 | leaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.0 | PASS | - |
| 236 | leaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.2 | PASS | - |
| 237 | leaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.4 | PASS | - |
| 238 | leaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.0 | PASS | - |
| 239 | leaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.6 | PASS | - |
| 240 | leaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.8 | PASS | - |
| 241 | leaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.10 | PASS | - |
| 242 | leaf3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.5 | PASS | - |
| 243 | leaf3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.12 | PASS | - |
| 244 | leaf3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.14 | PASS | - |
| 245 | leaf3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.16 | PASS | - |
| 246 | leaf4-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.4 | PASS | - |
| 247 | leaf4-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.18 | PASS | - |
| 248 | leaf4-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.20 | PASS | - |
| 249 | leaf4-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.22 | PASS | - |
| 250 | spine1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.1 | PASS | - |
| 251 | spine1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.7 | PASS | - |
| 252 | spine1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.13 | PASS | - |
| 253 | spine1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.19 | PASS | - |
| 254 | spine1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.25 | PASS | - |
| 255 | spine1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.31 | PASS | - |
| 256 | spine2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.3 | PASS | - |
| 257 | spine2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.9 | PASS | - |
| 258 | spine2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.15 | PASS | - |
| 259 | spine2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.21 | PASS | - |
| 260 | spine2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.27 | PASS | - |
| 261 | spine2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.33 | PASS | - |
| 262 | spine3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.5 | PASS | - |
| 263 | spine3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.11 | PASS | - |
| 264 | spine3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.17 | PASS | - |
| 265 | spine3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.23 | PASS | - |
| 266 | spine3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.29 | PASS | - |
| 267 | spine3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.203.35 | PASS | - |
| 268 | borderleaf1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.11 | PASS | - |
| 269 | borderleaf1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.12 | PASS | - |
| 270 | borderleaf1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.13 | PASS | - |
| 271 | borderleaf2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.11 | PASS | - |
| 272 | borderleaf2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.12 | PASS | - |
| 273 | borderleaf2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.13 | PASS | - |
| 274 | leaf1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.11 | PASS | - |
| 275 | leaf1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.12 | PASS | - |
| 276 | leaf1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.13 | PASS | - |
| 277 | leaf2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.11 | PASS | - |
| 278 | leaf2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.12 | PASS | - |
| 279 | leaf2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.13 | PASS | - |
| 280 | leaf3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.11 | PASS | - |
| 281 | leaf3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.12 | PASS | - |
| 282 | leaf3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.13 | PASS | - |
| 283 | leaf4-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.11 | PASS | - |
| 284 | leaf4-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.12 | PASS | - |
| 285 | leaf4-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.13 | PASS | - |
| 286 | spine1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.7 | PASS | - |
| 287 | spine1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.8 | PASS | - |
| 288 | spine1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.3 | PASS | - |
| 289 | spine1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.4 | PASS | - |
| 290 | spine1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.5 | PASS | - |
| 291 | spine1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.6 | PASS | - |
| 292 | spine2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.7 | PASS | - |
| 293 | spine2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.8 | PASS | - |
| 294 | spine2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.3 | PASS | - |
| 295 | spine2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.4 | PASS | - |
| 296 | spine2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.5 | PASS | - |
| 297 | spine2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.6 | PASS | - |
| 298 | spine3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.7 | PASS | - |
| 299 | spine3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.8 | PASS | - |
| 300 | spine3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.3 | PASS | - |
| 301 | spine3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.4 | PASS | - |
| 302 | spine3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.5 | PASS | - |
| 303 | spine3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.201.6 | PASS | - |
| 304 | borderleaf1-DC2 | Routing Table | Remote VTEP address | 192.168.202.7 | PASS | - |
| 305 | borderleaf1-DC2 | Routing Table | Remote VTEP address | 192.168.202.3 | PASS | - |
| 306 | borderleaf1-DC2 | Routing Table | Remote VTEP address | 192.168.202.5 | PASS | - |
| 307 | borderleaf2-DC2 | Routing Table | Remote VTEP address | 192.168.202.7 | PASS | - |
| 308 | borderleaf2-DC2 | Routing Table | Remote VTEP address | 192.168.202.3 | PASS | - |
| 309 | borderleaf2-DC2 | Routing Table | Remote VTEP address | 192.168.202.5 | PASS | - |
| 310 | leaf1-DC2 | Routing Table | Remote VTEP address | 192.168.202.7 | PASS | - |
| 311 | leaf1-DC2 | Routing Table | Remote VTEP address | 192.168.202.3 | PASS | - |
| 312 | leaf1-DC2 | Routing Table | Remote VTEP address | 192.168.202.5 | PASS | - |
| 313 | leaf2-DC2 | Routing Table | Remote VTEP address | 192.168.202.7 | PASS | - |
| 314 | leaf2-DC2 | Routing Table | Remote VTEP address | 192.168.202.3 | PASS | - |
| 315 | leaf2-DC2 | Routing Table | Remote VTEP address | 192.168.202.5 | PASS | - |
| 316 | leaf3-DC2 | Routing Table | Remote VTEP address | 192.168.202.7 | PASS | - |
| 317 | leaf3-DC2 | Routing Table | Remote VTEP address | 192.168.202.3 | PASS | - |
| 318 | leaf3-DC2 | Routing Table | Remote VTEP address | 192.168.202.5 | PASS | - |
| 319 | leaf4-DC2 | Routing Table | Remote VTEP address | 192.168.202.7 | PASS | - |
| 320 | leaf4-DC2 | Routing Table | Remote VTEP address | 192.168.202.3 | PASS | - |
| 321 | leaf4-DC2 | Routing Table | Remote VTEP address | 192.168.202.5 | PASS | - |
| 322 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.7 | PASS | - |
| 323 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.8 | PASS | - |
| 324 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.3 | PASS | - |
| 325 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.4 | PASS | - |
| 326 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.5 | PASS | - |
| 327 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.6 | PASS | - |
| 328 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.11 | PASS | - |
| 329 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.12 | PASS | - |
| 330 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.13 | PASS | - |
| 331 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.7 | PASS | - |
| 332 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.8 | PASS | - |
| 333 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.3 | PASS | - |
| 334 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.4 | PASS | - |
| 335 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.5 | PASS | - |
| 336 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.6 | PASS | - |
| 337 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.11 | PASS | - |
| 338 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.12 | PASS | - |
| 339 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.13 | PASS | - |
| 340 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.7 | PASS | - |
| 341 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.8 | PASS | - |
| 342 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.3 | PASS | - |
| 343 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.4 | PASS | - |
| 344 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.5 | PASS | - |
| 345 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.6 | PASS | - |
| 346 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.11 | PASS | - |
| 347 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.12 | PASS | - |
| 348 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.201.13 | PASS | - |
| 349 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.7 | PASS | - |
| 350 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.8 | PASS | - |
| 351 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.3 | PASS | - |
| 352 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.4 | PASS | - |
| 353 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.5 | PASS | - |
| 354 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.6 | PASS | - |
| 355 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.11 | PASS | - |
| 356 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.12 | PASS | - |
| 357 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.201.13 | PASS | - |
| 358 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.201.7 | PASS | - |
| 359 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.201.8 | PASS | - |
| 360 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.201.3 | PASS | - |
| 361 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.201.4 | PASS | - |
| 362 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.201.5 | PASS | - |
| 363 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.201.6 | PASS | - |
| 364 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.201.11 | PASS | - |
| 365 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.201.12 | PASS | - |
| 366 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.201.13 | PASS | - |
| 367 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.201.7 | PASS | - |
| 368 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.201.8 | PASS | - |
| 369 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.201.3 | PASS | - |
| 370 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.201.4 | PASS | - |
| 371 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.201.5 | PASS | - |
| 372 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.201.6 | PASS | - |
| 373 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.201.11 | PASS | - |
| 374 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.201.12 | PASS | - |
| 375 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.201.13 | PASS | - |
| 376 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.201.7 Destination: 192.168.201.7 | PASS | - |
| 377 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.201.7 Destination: 192.168.201.8 | PASS | - |
| 378 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.201.7 Destination: 192.168.201.3 | PASS | - |
| 379 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.201.7 Destination: 192.168.201.4 | PASS | - |
| 380 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.201.7 Destination: 192.168.201.5 | PASS | - |
| 381 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.201.7 Destination: 192.168.201.6 | PASS | - |
| 382 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.201.7 Destination: 192.168.201.11 | PASS | - |
| 383 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.201.7 Destination: 192.168.201.12 | PASS | - |
| 384 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.201.7 Destination: 192.168.201.13 | PASS | - |
| 385 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.201.8 Destination: 192.168.201.7 | PASS | - |
| 386 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.201.8 Destination: 192.168.201.8 | PASS | - |
| 387 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.201.8 Destination: 192.168.201.3 | PASS | - |
| 388 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.201.8 Destination: 192.168.201.4 | PASS | - |
| 389 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.201.8 Destination: 192.168.201.5 | PASS | - |
| 390 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.201.8 Destination: 192.168.201.6 | PASS | - |
| 391 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.201.8 Destination: 192.168.201.11 | PASS | - |
| 392 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.201.8 Destination: 192.168.201.12 | PASS | - |
| 393 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.201.8 Destination: 192.168.201.13 | PASS | - |
| 394 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.201.3 Destination: 192.168.201.7 | PASS | - |
| 395 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.201.3 Destination: 192.168.201.8 | PASS | - |
| 396 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.201.3 Destination: 192.168.201.3 | PASS | - |
| 397 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.201.3 Destination: 192.168.201.4 | PASS | - |
| 398 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.201.3 Destination: 192.168.201.5 | PASS | - |
| 399 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.201.3 Destination: 192.168.201.6 | PASS | - |
| 400 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.201.3 Destination: 192.168.201.11 | PASS | - |
| 401 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.201.3 Destination: 192.168.201.12 | PASS | - |
| 402 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.201.3 Destination: 192.168.201.13 | PASS | - |
| 403 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.201.4 Destination: 192.168.201.7 | PASS | - |
| 404 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.201.4 Destination: 192.168.201.8 | PASS | - |
| 405 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.201.4 Destination: 192.168.201.3 | PASS | - |
| 406 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.201.4 Destination: 192.168.201.4 | PASS | - |
| 407 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.201.4 Destination: 192.168.201.5 | PASS | - |
| 408 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.201.4 Destination: 192.168.201.6 | PASS | - |
| 409 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.201.4 Destination: 192.168.201.11 | PASS | - |
| 410 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.201.4 Destination: 192.168.201.12 | PASS | - |
| 411 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.201.4 Destination: 192.168.201.13 | PASS | - |
| 412 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.201.5 Destination: 192.168.201.7 | PASS | - |
| 413 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.201.5 Destination: 192.168.201.8 | PASS | - |
| 414 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.201.5 Destination: 192.168.201.3 | PASS | - |
| 415 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.201.5 Destination: 192.168.201.4 | PASS | - |
| 416 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.201.5 Destination: 192.168.201.5 | PASS | - |
| 417 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.201.5 Destination: 192.168.201.6 | PASS | - |
| 418 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.201.5 Destination: 192.168.201.11 | PASS | - |
| 419 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.201.5 Destination: 192.168.201.12 | PASS | - |
| 420 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.201.5 Destination: 192.168.201.13 | PASS | - |
| 421 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.201.6 Destination: 192.168.201.7 | PASS | - |
| 422 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.201.6 Destination: 192.168.201.8 | PASS | - |
| 423 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.201.6 Destination: 192.168.201.3 | PASS | - |
| 424 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.201.6 Destination: 192.168.201.4 | PASS | - |
| 425 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.201.6 Destination: 192.168.201.5 | PASS | - |
| 426 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.201.6 Destination: 192.168.201.6 | PASS | - |
| 427 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.201.6 Destination: 192.168.201.11 | PASS | - |
| 428 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.201.6 Destination: 192.168.201.12 | PASS | - |
| 429 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.201.6 Destination: 192.168.201.13 | PASS | - |
