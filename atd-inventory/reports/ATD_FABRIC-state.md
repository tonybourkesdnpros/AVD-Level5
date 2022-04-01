
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
| 426 | 426 | 0 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| borderleaf1-DC1 |  47 | 47 | 0 | - |
| borderleaf2-DC1 |  47 | 47 | 0 | - |
| leaf1-DC1 |  47 | 47 | 0 | - |
| leaf2-DC1 |  47 | 47 | 0 | - |
| leaf3-DC1 |  47 | 47 | 0 | - |
| leaf4-DC1 |  47 | 47 | 0 | - |
| spine1-DC1 |  48 | 48 | 0 | - |
| spine2-DC1 |  48 | 48 | 0 | - |
| spine3-DC1 |  48 | 48 | 0 | - |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| NTP |  9 | 9 | 0 |
| Interface State |  105 | 105 | 0 |
| LLDP Topology |  48 | 48 | 0 |
| MLAG |  6 | 6 | 0 |
| IP Reachability |  36 | 36 | 0 |
| BGP |  87 | 87 | 0 |
| Routing Table |  81 | 81 | 0 |
| Loopback0 Reachability |  54 | 54 | 0 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |

## All Test Results

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | borderleaf1-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 2 | borderleaf2-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 3 | leaf1-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 4 | leaf2-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 5 | leaf3-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 6 | leaf4-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 7 | spine1-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 8 | spine2-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 9 | spine3-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 10 | borderleaf1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet1 - MLAG_PEER_borderleaf2-DC1_Ethernet1 | PASS | - |
| 11 | borderleaf1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2 - MLAG_PEER_borderleaf2-DC1_Ethernet2 | PASS | - |
| 12 | borderleaf1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet6 | PASS | - |
| 13 | borderleaf1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet6 | PASS | - |
| 14 | borderleaf1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet6 | PASS | - |
| 15 | borderleaf2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet1 - MLAG_PEER_borderleaf1-DC1_Ethernet1 | PASS | - |
| 16 | borderleaf2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2 - MLAG_PEER_borderleaf1-DC1_Ethernet2 | PASS | - |
| 17 | borderleaf2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet7 | PASS | - |
| 18 | borderleaf2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet7 | PASS | - |
| 19 | borderleaf2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet7 | PASS | - |
| 20 | leaf1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf2-DC1_Ethernet1 | PASS | - |
| 21 | leaf1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf2-DC1_Ethernet2 | PASS | - |
| 22 | leaf1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet2 | PASS | - |
| 23 | leaf1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet2 | PASS | - |
| 24 | leaf1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet2 | PASS | - |
| 25 | leaf2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf1-DC1_Ethernet1 | PASS | - |
| 26 | leaf2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf1-DC1_Ethernet2 | PASS | - |
| 27 | leaf2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet3 | PASS | - |
| 28 | leaf2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet3 | PASS | - |
| 29 | leaf2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet3 | PASS | - |
| 30 | leaf3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf4-DC1_Ethernet1 | PASS | - |
| 31 | leaf3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf4-DC1_Ethernet2 | PASS | - |
| 32 | leaf3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet4 | PASS | - |
| 33 | leaf3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet4 | PASS | - |
| 34 | leaf3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet4 | PASS | - |
| 35 | leaf4-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf3-DC1_Ethernet1 | PASS | - |
| 36 | leaf4-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf3-DC1_Ethernet2 | PASS | - |
| 37 | leaf4-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet5 | PASS | - |
| 38 | leaf4-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet5 | PASS | - |
| 39 | leaf4-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet5 | PASS | - |
| 40 | spine1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1-DC1_Ethernet3 | PASS | - |
| 41 | spine1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2-DC1_Ethernet3 | PASS | - |
| 42 | spine1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3-DC1_Ethernet3 | PASS | - |
| 43 | spine1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4-DC1_Ethernet3 | PASS | - |
| 44 | spine1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1-DC1_Ethernet3 | PASS | - |
| 45 | spine1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2-DC1_Ethernet3 | PASS | - |
| 46 | spine2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1-DC1_Ethernet4 | PASS | - |
| 47 | spine2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2-DC1_Ethernet4 | PASS | - |
| 48 | spine2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3-DC1_Ethernet4 | PASS | - |
| 49 | spine2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4-DC1_Ethernet4 | PASS | - |
| 50 | spine2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1-DC1_Ethernet4 | PASS | - |
| 51 | spine2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2-DC1_Ethernet4 | PASS | - |
| 52 | spine3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1-DC1_Ethernet5 | PASS | - |
| 53 | spine3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2-DC1_Ethernet5 | PASS | - |
| 54 | spine3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3-DC1_Ethernet5 | PASS | - |
| 55 | spine3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4-DC1_Ethernet5 | PASS | - |
| 56 | spine3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1-DC1_Ethernet5 | PASS | - |
| 57 | spine3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2-DC1_Ethernet5 | PASS | - |
| 58 | borderleaf1-DC1 | Interface State | Port-Channel Interface Status & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_borderleaf2-DC1_Po1 | PASS | - |
| 59 | borderleaf2-DC1 | Interface State | Port-Channel Interface Status & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_borderleaf1-DC1_Po1 | PASS | - |
| 60 | leaf1-DC1 | Interface State | Port-Channel Interface Status & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf2-DC1_Po1 | PASS | - |
| 61 | leaf2-DC1 | Interface State | Port-Channel Interface Status & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf1-DC1_Po1 | PASS | - |
| 62 | leaf3-DC1 | Interface State | Port-Channel Interface Status & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf4-DC1_Po1 | PASS | - |
| 63 | leaf4-DC1 | Interface State | Port-Channel Interface Status & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf3-DC1_Po1 | PASS | - |
| 64 | borderleaf1-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 65 | borderleaf1-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 66 | borderleaf1-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan110 - Tenant_A_OP_Zone_1 | PASS | - |
| 67 | borderleaf1-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf Tenant_A_OP_Zone | PASS | - |
| 68 | borderleaf2-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 69 | borderleaf2-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 70 | borderleaf2-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan110 - Tenant_A_OP_Zone_1 | PASS | - |
| 71 | borderleaf2-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf Tenant_A_OP_Zone | PASS | - |
| 72 | leaf1-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 73 | leaf1-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 74 | leaf1-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan110 - Tenant_A_OP_Zone_1 | PASS | - |
| 75 | leaf1-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf Tenant_A_OP_Zone | PASS | - |
| 76 | leaf2-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 77 | leaf2-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 78 | leaf2-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan110 - Tenant_A_OP_Zone_1 | PASS | - |
| 79 | leaf2-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf Tenant_A_OP_Zone | PASS | - |
| 80 | leaf3-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 81 | leaf3-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 82 | leaf3-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan110 - Tenant_A_OP_Zone_1 | PASS | - |
| 83 | leaf3-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf Tenant_A_OP_Zone | PASS | - |
| 84 | leaf4-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 85 | leaf4-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 86 | leaf4-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan110 - Tenant_A_OP_Zone_1 | PASS | - |
| 87 | leaf4-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf Tenant_A_OP_Zone | PASS | - |
| 88 | borderleaf1-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 89 | borderleaf2-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 90 | leaf1-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 91 | leaf2-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 92 | leaf3-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 93 | leaf4-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 94 | borderleaf1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 95 | borderleaf1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 96 | borderleaf1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback100 - Tenant_A_OP_Zone_VTEP_DIAGNOSTICS | PASS | - |
| 97 | borderleaf2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 98 | borderleaf2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 99 | borderleaf2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback100 - Tenant_A_OP_Zone_VTEP_DIAGNOSTICS | PASS | - |
| 100 | leaf1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 101 | leaf1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 102 | leaf1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback100 - Tenant_A_OP_Zone_VTEP_DIAGNOSTICS | PASS | - |
| 103 | leaf2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 104 | leaf2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 105 | leaf2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback100 - Tenant_A_OP_Zone_VTEP_DIAGNOSTICS | PASS | - |
| 106 | leaf3-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 107 | leaf3-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 108 | leaf3-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback100 - Tenant_A_OP_Zone_VTEP_DIAGNOSTICS | PASS | - |
| 109 | leaf4-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 110 | leaf4-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 111 | leaf4-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback100 - Tenant_A_OP_Zone_VTEP_DIAGNOSTICS | PASS | - |
| 112 | spine1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 113 | spine2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 114 | spine3-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 115 | borderleaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: borderleaf2-DC1_Ethernet1 | PASS | - |
| 116 | borderleaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: borderleaf2-DC1_Ethernet2 | PASS | - |
| 117 | borderleaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet6 | PASS | - |
| 118 | borderleaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet6 | PASS | - |
| 119 | borderleaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet6 | PASS | - |
| 120 | borderleaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: borderleaf1-DC1_Ethernet1 | PASS | - |
| 121 | borderleaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: borderleaf1-DC1_Ethernet2 | PASS | - |
| 122 | borderleaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet7 | PASS | - |
| 123 | borderleaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet7 | PASS | - |
| 124 | borderleaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet7 | PASS | - |
| 125 | leaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf2-DC1_Ethernet1 | PASS | - |
| 126 | leaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf2-DC1_Ethernet2 | PASS | - |
| 127 | leaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet2 | PASS | - |
| 128 | leaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet2 | PASS | - |
| 129 | leaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet2 | PASS | - |
| 130 | leaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf1-DC1_Ethernet1 | PASS | - |
| 131 | leaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC1_Ethernet2 | PASS | - |
| 132 | leaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet3 | PASS | - |
| 133 | leaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet3 | PASS | - |
| 134 | leaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet3 | PASS | - |
| 135 | leaf3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf4-DC1_Ethernet1 | PASS | - |
| 136 | leaf3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf4-DC1_Ethernet2 | PASS | - |
| 137 | leaf3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet4 | PASS | - |
| 138 | leaf3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet4 | PASS | - |
| 139 | leaf3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet4 | PASS | - |
| 140 | leaf4-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf3-DC1_Ethernet1 | PASS | - |
| 141 | leaf4-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf3-DC1_Ethernet2 | PASS | - |
| 142 | leaf4-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet5 | PASS | - |
| 143 | leaf4-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet5 | PASS | - |
| 144 | leaf4-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet5 | PASS | - |
| 145 | spine1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC1_Ethernet3 | PASS | - |
| 146 | spine1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2-DC1_Ethernet3 | PASS | - |
| 147 | spine1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3-DC1_Ethernet3 | PASS | - |
| 148 | spine1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4-DC1_Ethernet3 | PASS | - |
| 149 | spine1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1-DC1_Ethernet3 | PASS | - |
| 150 | spine1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2-DC1_Ethernet3 | PASS | - |
| 151 | spine2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC1_Ethernet4 | PASS | - |
| 152 | spine2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2-DC1_Ethernet4 | PASS | - |
| 153 | spine2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3-DC1_Ethernet4 | PASS | - |
| 154 | spine2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4-DC1_Ethernet4 | PASS | - |
| 155 | spine2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1-DC1_Ethernet4 | PASS | - |
| 156 | spine2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2-DC1_Ethernet4 | PASS | - |
| 157 | spine3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC1_Ethernet5 | PASS | - |
| 158 | spine3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2-DC1_Ethernet5 | PASS | - |
| 159 | spine3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3-DC1_Ethernet5 | PASS | - |
| 160 | spine3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4-DC1_Ethernet5 | PASS | - |
| 161 | spine3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1-DC1_Ethernet5 | PASS | - |
| 162 | spine3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2-DC1_Ethernet5 | PASS | - |
| 163 | borderleaf1-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 164 | borderleaf2-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 165 | leaf1-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 166 | leaf2-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 167 | leaf3-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 168 | leaf4-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 169 | borderleaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: borderleaf1-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet6 | PASS | - |
| 170 | borderleaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: borderleaf1-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet6 | PASS | - |
| 171 | borderleaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: borderleaf1-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet6 | PASS | - |
| 172 | borderleaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: borderleaf2-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet7 | PASS | - |
| 173 | borderleaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: borderleaf2-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet7 | PASS | - |
| 174 | borderleaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: borderleaf2-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet7 | PASS | - |
| 175 | leaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet2 | PASS | - |
| 176 | leaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet2 | PASS | - |
| 177 | leaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet2 | PASS | - |
| 178 | leaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet3 | PASS | - |
| 179 | leaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet3 | PASS | - |
| 180 | leaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet3 | PASS | - |
| 181 | leaf3-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet4 | PASS | - |
| 182 | leaf3-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet4 | PASS | - |
| 183 | leaf3-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet4 | PASS | - |
| 184 | leaf4-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet5 | PASS | - |
| 185 | leaf4-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet5 | PASS | - |
| 186 | leaf4-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet5 | PASS | - |
| 187 | spine1-DC1 | IP Reachability | ip reachability test p2p links | Source: spine1-DC1_Ethernet2 - Destination: leaf1-DC1_Ethernet3 | PASS | - |
| 188 | spine1-DC1 | IP Reachability | ip reachability test p2p links | Source: spine1-DC1_Ethernet3 - Destination: leaf2-DC1_Ethernet3 | PASS | - |
| 189 | spine1-DC1 | IP Reachability | ip reachability test p2p links | Source: spine1-DC1_Ethernet4 - Destination: leaf3-DC1_Ethernet3 | PASS | - |
| 190 | spine1-DC1 | IP Reachability | ip reachability test p2p links | Source: spine1-DC1_Ethernet5 - Destination: leaf4-DC1_Ethernet3 | PASS | - |
| 191 | spine1-DC1 | IP Reachability | ip reachability test p2p links | Source: spine1-DC1_Ethernet6 - Destination: borderleaf1-DC1_Ethernet3 | PASS | - |
| 192 | spine1-DC1 | IP Reachability | ip reachability test p2p links | Source: spine1-DC1_Ethernet7 - Destination: borderleaf2-DC1_Ethernet3 | PASS | - |
| 193 | spine2-DC1 | IP Reachability | ip reachability test p2p links | Source: spine2-DC1_Ethernet2 - Destination: leaf1-DC1_Ethernet4 | PASS | - |
| 194 | spine2-DC1 | IP Reachability | ip reachability test p2p links | Source: spine2-DC1_Ethernet3 - Destination: leaf2-DC1_Ethernet4 | PASS | - |
| 195 | spine2-DC1 | IP Reachability | ip reachability test p2p links | Source: spine2-DC1_Ethernet4 - Destination: leaf3-DC1_Ethernet4 | PASS | - |
| 196 | spine2-DC1 | IP Reachability | ip reachability test p2p links | Source: spine2-DC1_Ethernet5 - Destination: leaf4-DC1_Ethernet4 | PASS | - |
| 197 | spine2-DC1 | IP Reachability | ip reachability test p2p links | Source: spine2-DC1_Ethernet6 - Destination: borderleaf1-DC1_Ethernet4 | PASS | - |
| 198 | spine2-DC1 | IP Reachability | ip reachability test p2p links | Source: spine2-DC1_Ethernet7 - Destination: borderleaf2-DC1_Ethernet4 | PASS | - |
| 199 | spine3-DC1 | IP Reachability | ip reachability test p2p links | Source: spine3-DC1_Ethernet2 - Destination: leaf1-DC1_Ethernet5 | PASS | - |
| 200 | spine3-DC1 | IP Reachability | ip reachability test p2p links | Source: spine3-DC1_Ethernet3 - Destination: leaf2-DC1_Ethernet5 | PASS | - |
| 201 | spine3-DC1 | IP Reachability | ip reachability test p2p links | Source: spine3-DC1_Ethernet4 - Destination: leaf3-DC1_Ethernet5 | PASS | - |
| 202 | spine3-DC1 | IP Reachability | ip reachability test p2p links | Source: spine3-DC1_Ethernet5 - Destination: leaf4-DC1_Ethernet5 | PASS | - |
| 203 | spine3-DC1 | IP Reachability | ip reachability test p2p links | Source: spine3-DC1_Ethernet6 - Destination: borderleaf1-DC1_Ethernet5 | PASS | - |
| 204 | spine3-DC1 | IP Reachability | ip reachability test p2p links | Source: spine3-DC1_Ethernet7 - Destination: borderleaf2-DC1_Ethernet5 | PASS | - |
| 205 | borderleaf1-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 206 | borderleaf2-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 207 | leaf1-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 208 | leaf2-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 209 | leaf3-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 210 | leaf4-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 211 | spine1-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 212 | spine2-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 213 | spine3-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 214 | borderleaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.9 | PASS | - |
| 215 | borderleaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.24 | PASS | - |
| 216 | borderleaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.26 | PASS | - |
| 217 | borderleaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.28 | PASS | - |
| 218 | borderleaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.8 | PASS | - |
| 219 | borderleaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.30 | PASS | - |
| 220 | borderleaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.32 | PASS | - |
| 221 | borderleaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.34 | PASS | - |
| 222 | leaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.1 | PASS | - |
| 223 | leaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.0 | PASS | - |
| 224 | leaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.2 | PASS | - |
| 225 | leaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.4 | PASS | - |
| 226 | leaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.0 | PASS | - |
| 227 | leaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.6 | PASS | - |
| 228 | leaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.8 | PASS | - |
| 229 | leaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.10 | PASS | - |
| 230 | leaf3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.5 | PASS | - |
| 231 | leaf3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.12 | PASS | - |
| 232 | leaf3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.14 | PASS | - |
| 233 | leaf3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.16 | PASS | - |
| 234 | leaf4-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.4 | PASS | - |
| 235 | leaf4-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.18 | PASS | - |
| 236 | leaf4-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.20 | PASS | - |
| 237 | leaf4-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.22 | PASS | - |
| 238 | spine1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.1 | PASS | - |
| 239 | spine1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.7 | PASS | - |
| 240 | spine1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.13 | PASS | - |
| 241 | spine1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.19 | PASS | - |
| 242 | spine1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.25 | PASS | - |
| 243 | spine1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.31 | PASS | - |
| 244 | spine2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.3 | PASS | - |
| 245 | spine2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.9 | PASS | - |
| 246 | spine2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.15 | PASS | - |
| 247 | spine2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.21 | PASS | - |
| 248 | spine2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.27 | PASS | - |
| 249 | spine2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.33 | PASS | - |
| 250 | spine3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.5 | PASS | - |
| 251 | spine3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.11 | PASS | - |
| 252 | spine3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.17 | PASS | - |
| 253 | spine3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.23 | PASS | - |
| 254 | spine3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.29 | PASS | - |
| 255 | spine3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.35 | PASS | - |
| 256 | borderleaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.11 | PASS | - |
| 257 | borderleaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.12 | PASS | - |
| 258 | borderleaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.13 | PASS | - |
| 259 | borderleaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.11 | PASS | - |
| 260 | borderleaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.12 | PASS | - |
| 261 | borderleaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.13 | PASS | - |
| 262 | leaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.11 | PASS | - |
| 263 | leaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.12 | PASS | - |
| 264 | leaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.13 | PASS | - |
| 265 | leaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.11 | PASS | - |
| 266 | leaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.12 | PASS | - |
| 267 | leaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.13 | PASS | - |
| 268 | leaf3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.11 | PASS | - |
| 269 | leaf3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.12 | PASS | - |
| 270 | leaf3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.13 | PASS | - |
| 271 | leaf4-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.11 | PASS | - |
| 272 | leaf4-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.12 | PASS | - |
| 273 | leaf4-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.13 | PASS | - |
| 274 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.7 | PASS | - |
| 275 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.8 | PASS | - |
| 276 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.3 | PASS | - |
| 277 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.4 | PASS | - |
| 278 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.5 | PASS | - |
| 279 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.6 | PASS | - |
| 280 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.7 | PASS | - |
| 281 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.8 | PASS | - |
| 282 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.3 | PASS | - |
| 283 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.4 | PASS | - |
| 284 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.5 | PASS | - |
| 285 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.6 | PASS | - |
| 286 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.7 | PASS | - |
| 287 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.8 | PASS | - |
| 288 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.3 | PASS | - |
| 289 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.4 | PASS | - |
| 290 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.5 | PASS | - |
| 291 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.6 | PASS | - |
| 292 | borderleaf1-DC1 | Routing Table | Remote VTEP address | 192.0.254.7 | PASS | - |
| 293 | borderleaf1-DC1 | Routing Table | Remote VTEP address | 192.0.254.3 | PASS | - |
| 294 | borderleaf1-DC1 | Routing Table | Remote VTEP address | 192.0.254.5 | PASS | - |
| 295 | borderleaf2-DC1 | Routing Table | Remote VTEP address | 192.0.254.7 | PASS | - |
| 296 | borderleaf2-DC1 | Routing Table | Remote VTEP address | 192.0.254.3 | PASS | - |
| 297 | borderleaf2-DC1 | Routing Table | Remote VTEP address | 192.0.254.5 | PASS | - |
| 298 | leaf1-DC1 | Routing Table | Remote VTEP address | 192.0.254.7 | PASS | - |
| 299 | leaf1-DC1 | Routing Table | Remote VTEP address | 192.0.254.3 | PASS | - |
| 300 | leaf1-DC1 | Routing Table | Remote VTEP address | 192.0.254.5 | PASS | - |
| 301 | leaf2-DC1 | Routing Table | Remote VTEP address | 192.0.254.7 | PASS | - |
| 302 | leaf2-DC1 | Routing Table | Remote VTEP address | 192.0.254.3 | PASS | - |
| 303 | leaf2-DC1 | Routing Table | Remote VTEP address | 192.0.254.5 | PASS | - |
| 304 | leaf3-DC1 | Routing Table | Remote VTEP address | 192.0.254.7 | PASS | - |
| 305 | leaf3-DC1 | Routing Table | Remote VTEP address | 192.0.254.3 | PASS | - |
| 306 | leaf3-DC1 | Routing Table | Remote VTEP address | 192.0.254.5 | PASS | - |
| 307 | leaf4-DC1 | Routing Table | Remote VTEP address | 192.0.254.7 | PASS | - |
| 308 | leaf4-DC1 | Routing Table | Remote VTEP address | 192.0.254.3 | PASS | - |
| 309 | leaf4-DC1 | Routing Table | Remote VTEP address | 192.0.254.5 | PASS | - |
| 310 | spine1-DC1 | Routing Table | Remote VTEP address | 192.0.254.7 | PASS | - |
| 311 | spine1-DC1 | Routing Table | Remote VTEP address | 192.0.254.3 | PASS | - |
| 312 | spine1-DC1 | Routing Table | Remote VTEP address | 192.0.254.5 | PASS | - |
| 313 | spine2-DC1 | Routing Table | Remote VTEP address | 192.0.254.7 | PASS | - |
| 314 | spine2-DC1 | Routing Table | Remote VTEP address | 192.0.254.3 | PASS | - |
| 315 | spine2-DC1 | Routing Table | Remote VTEP address | 192.0.254.5 | PASS | - |
| 316 | spine3-DC1 | Routing Table | Remote VTEP address | 192.0.254.7 | PASS | - |
| 317 | spine3-DC1 | Routing Table | Remote VTEP address | 192.0.254.3 | PASS | - |
| 318 | spine3-DC1 | Routing Table | Remote VTEP address | 192.0.254.5 | PASS | - |
| 319 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.7 | PASS | - |
| 320 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.8 | PASS | - |
| 321 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | PASS | - |
| 322 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | PASS | - |
| 323 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | PASS | - |
| 324 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | PASS | - |
| 325 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.7 | PASS | - |
| 326 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.8 | PASS | - |
| 327 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | PASS | - |
| 328 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | PASS | - |
| 329 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | PASS | - |
| 330 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | PASS | - |
| 331 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.7 | PASS | - |
| 332 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.8 | PASS | - |
| 333 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | PASS | - |
| 334 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | PASS | - |
| 335 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | PASS | - |
| 336 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | PASS | - |
| 337 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.7 | PASS | - |
| 338 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.8 | PASS | - |
| 339 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | PASS | - |
| 340 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | PASS | - |
| 341 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | PASS | - |
| 342 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | PASS | - |
| 343 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.7 | PASS | - |
| 344 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.8 | PASS | - |
| 345 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | PASS | - |
| 346 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | PASS | - |
| 347 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | PASS | - |
| 348 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | PASS | - |
| 349 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.0.200.7 | PASS | - |
| 350 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.0.200.8 | PASS | - |
| 351 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | PASS | - |
| 352 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | PASS | - |
| 353 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | PASS | - |
| 354 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | PASS | - |
| 355 | spine1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.7 | PASS | - |
| 356 | spine1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.8 | PASS | - |
| 357 | spine1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | PASS | - |
| 358 | spine1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | PASS | - |
| 359 | spine1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | PASS | - |
| 360 | spine1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | PASS | - |
| 361 | spine2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.7 | PASS | - |
| 362 | spine2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.8 | PASS | - |
| 363 | spine2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | PASS | - |
| 364 | spine2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | PASS | - |
| 365 | spine2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | PASS | - |
| 366 | spine2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | PASS | - |
| 367 | spine3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.7 | PASS | - |
| 368 | spine3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.8 | PASS | - |
| 369 | spine3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | PASS | - |
| 370 | spine3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | PASS | - |
| 371 | spine3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | PASS | - |
| 372 | spine3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | PASS | - |
| 373 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.0.200.7 Destination: 192.0.200.7 | PASS | - |
| 374 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.0.200.7 Destination: 192.0.200.8 | PASS | - |
| 375 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.0.200.7 Destination: 192.0.200.3 | PASS | - |
| 376 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.0.200.7 Destination: 192.0.200.4 | PASS | - |
| 377 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.0.200.7 Destination: 192.0.200.5 | PASS | - |
| 378 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.0.200.7 Destination: 192.0.200.6 | PASS | - |
| 379 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.0.200.8 Destination: 192.0.200.7 | PASS | - |
| 380 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.0.200.8 Destination: 192.0.200.8 | PASS | - |
| 381 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.0.200.8 Destination: 192.0.200.3 | PASS | - |
| 382 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.0.200.8 Destination: 192.0.200.4 | PASS | - |
| 383 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.0.200.8 Destination: 192.0.200.5 | PASS | - |
| 384 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.0.200.8 Destination: 192.0.200.6 | PASS | - |
| 385 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.0.200.3 Destination: 192.0.200.7 | PASS | - |
| 386 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.0.200.3 Destination: 192.0.200.8 | PASS | - |
| 387 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.0.200.3 Destination: 192.0.200.3 | PASS | - |
| 388 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.0.200.3 Destination: 192.0.200.4 | PASS | - |
| 389 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.0.200.3 Destination: 192.0.200.5 | PASS | - |
| 390 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.0.200.3 Destination: 192.0.200.6 | PASS | - |
| 391 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.0.200.4 Destination: 192.0.200.7 | PASS | - |
| 392 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.0.200.4 Destination: 192.0.200.8 | PASS | - |
| 393 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.0.200.4 Destination: 192.0.200.3 | PASS | - |
| 394 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.0.200.4 Destination: 192.0.200.4 | PASS | - |
| 395 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.0.200.4 Destination: 192.0.200.5 | PASS | - |
| 396 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.0.200.4 Destination: 192.0.200.6 | PASS | - |
| 397 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.0.200.5 Destination: 192.0.200.7 | PASS | - |
| 398 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.0.200.5 Destination: 192.0.200.8 | PASS | - |
| 399 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.0.200.5 Destination: 192.0.200.3 | PASS | - |
| 400 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.0.200.5 Destination: 192.0.200.4 | PASS | - |
| 401 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.0.200.5 Destination: 192.0.200.5 | PASS | - |
| 402 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.0.200.5 Destination: 192.0.200.6 | PASS | - |
| 403 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.0.200.6 Destination: 192.0.200.7 | PASS | - |
| 404 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.0.200.6 Destination: 192.0.200.8 | PASS | - |
| 405 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.0.200.6 Destination: 192.0.200.3 | PASS | - |
| 406 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.0.200.6 Destination: 192.0.200.4 | PASS | - |
| 407 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.0.200.6 Destination: 192.0.200.5 | PASS | - |
| 408 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.0.200.6 Destination: 192.0.200.6 | PASS | - |
| 409 | spine1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine1-DC1 - 192.0.200.11 Destination: 192.0.200.7 | PASS | - |
| 410 | spine1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine1-DC1 - 192.0.200.11 Destination: 192.0.200.8 | PASS | - |
| 411 | spine1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine1-DC1 - 192.0.200.11 Destination: 192.0.200.3 | PASS | - |
| 412 | spine1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine1-DC1 - 192.0.200.11 Destination: 192.0.200.4 | PASS | - |
| 413 | spine1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine1-DC1 - 192.0.200.11 Destination: 192.0.200.5 | PASS | - |
| 414 | spine1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine1-DC1 - 192.0.200.11 Destination: 192.0.200.6 | PASS | - |
| 415 | spine2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine2-DC1 - 192.0.200.12 Destination: 192.0.200.7 | PASS | - |
| 416 | spine2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine2-DC1 - 192.0.200.12 Destination: 192.0.200.8 | PASS | - |
| 417 | spine2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine2-DC1 - 192.0.200.12 Destination: 192.0.200.3 | PASS | - |
| 418 | spine2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine2-DC1 - 192.0.200.12 Destination: 192.0.200.4 | PASS | - |
| 419 | spine2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine2-DC1 - 192.0.200.12 Destination: 192.0.200.5 | PASS | - |
| 420 | spine2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine2-DC1 - 192.0.200.12 Destination: 192.0.200.6 | PASS | - |
| 421 | spine3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine3-DC1 - 192.0.200.13 Destination: 192.0.200.7 | PASS | - |
| 422 | spine3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine3-DC1 - 192.0.200.13 Destination: 192.0.200.8 | PASS | - |
| 423 | spine3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine3-DC1 - 192.0.200.13 Destination: 192.0.200.3 | PASS | - |
| 424 | spine3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine3-DC1 - 192.0.200.13 Destination: 192.0.200.4 | PASS | - |
| 425 | spine3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine3-DC1 - 192.0.200.13 Destination: 192.0.200.5 | PASS | - |
| 426 | spine3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine3-DC1 - 192.0.200.13 Destination: 192.0.200.6 | PASS | - |
