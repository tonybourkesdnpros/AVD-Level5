
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
| 1110 | 1110 | 0 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| borderleaf1-DC1 |  74 | 74 | 0 | - |
| borderleaf1-DC2 |  74 | 74 | 0 | - |
| borderleaf2-DC1 |  74 | 74 | 0 | - |
| borderleaf2-DC2 |  74 | 74 | 0 | - |
| leaf1-DC1 |  77 | 77 | 0 | - |
| leaf1-DC2 |  77 | 77 | 0 | - |
| leaf2-DC1 |  77 | 77 | 0 | - |
| leaf2-DC2 |  77 | 77 | 0 | - |
| leaf3-DC1 |  77 | 77 | 0 | - |
| leaf3-DC2 |  77 | 77 | 0 | - |
| leaf4-DC1 |  77 | 77 | 0 | - |
| leaf4-DC2 |  77 | 77 | 0 | - |
| spine1-DC1 |  33 | 33 | 0 | - |
| spine1-DC2 |  33 | 33 | 0 | - |
| spine2-DC1 |  33 | 33 | 0 | - |
| spine2-DC2 |  33 | 33 | 0 | - |
| spine3-DC1 |  33 | 33 | 0 | - |
| spine3-DC2 |  33 | 33 | 0 | - |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| NTP |  18 | 18 | 0 |
| Interface State |  234 | 234 | 0 |
| LLDP Topology |  96 | 96 | 0 |
| MLAG |  12 | 12 | 0 |
| IP Reachability |  72 | 72 | 0 |
| BGP |  174 | 174 | 0 |
| Routing Table |  288 | 288 | 0 |
| Loopback0 Reachability |  216 | 216 | 0 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |

## All Test Results

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | borderleaf1-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 2 | borderleaf1-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 3 | borderleaf2-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 4 | borderleaf2-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 5 | leaf1-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 6 | leaf1-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 7 | leaf2-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 8 | leaf2-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 9 | leaf3-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 10 | leaf3-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 11 | leaf4-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 12 | leaf4-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 13 | spine1-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 14 | spine1-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 15 | spine2-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 16 | spine2-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 17 | spine3-DC1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 18 | spine3-DC2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 19 | borderleaf1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_borderleaf2-DC1_Ethernet1 | PASS | - |
| 20 | borderleaf1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_borderleaf2-DC1_Ethernet2 | PASS | - |
| 21 | borderleaf1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet6 | PASS | - |
| 22 | borderleaf1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet6 | PASS | - |
| 23 | borderleaf1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet6 | PASS | - |
| 24 | borderleaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_borderleaf2-DC2_Ethernet1 | PASS | - |
| 25 | borderleaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_borderleaf2-DC2_Ethernet2 | PASS | - |
| 26 | borderleaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC2_Ethernet6 | PASS | - |
| 27 | borderleaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC2_Ethernet6 | PASS | - |
| 28 | borderleaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC2_Ethernet6 | PASS | - |
| 29 | borderleaf2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_borderleaf1-DC1_Ethernet1 | PASS | - |
| 30 | borderleaf2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_borderleaf1-DC1_Ethernet2 | PASS | - |
| 31 | borderleaf2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet7 | PASS | - |
| 32 | borderleaf2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet7 | PASS | - |
| 33 | borderleaf2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet7 | PASS | - |
| 34 | borderleaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_borderleaf1-DC2_Ethernet1 | PASS | - |
| 35 | borderleaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_borderleaf1-DC2_Ethernet2 | PASS | - |
| 36 | borderleaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC2_Ethernet7 | PASS | - |
| 37 | borderleaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC2_Ethernet7 | PASS | - |
| 38 | borderleaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC2_Ethernet7 | PASS | - |
| 39 | leaf1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf2-DC1_Ethernet1 | PASS | - |
| 40 | leaf1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf2-DC1_Ethernet2 | PASS | - |
| 41 | leaf1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet2 | PASS | - |
| 42 | leaf1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet2 | PASS | - |
| 43 | leaf1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet2 | PASS | - |
| 44 | leaf1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - host1-DC1_Eth1 | PASS | - |
| 45 | leaf1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1-DC1_Eth2 | PASS | - |
| 46 | leaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf2-DC2_Ethernet1 | PASS | - |
| 47 | leaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf2-DC2_Ethernet2 | PASS | - |
| 48 | leaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC2_Ethernet2 | PASS | - |
| 49 | leaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC2_Ethernet2 | PASS | - |
| 50 | leaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC2_Ethernet2 | PASS | - |
| 51 | leaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - host1-DC2_Eth1 | PASS | - |
| 52 | leaf1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1-DC2_Eth2 | PASS | - |
| 53 | leaf2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf1-DC1_Ethernet1 | PASS | - |
| 54 | leaf2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf1-DC1_Ethernet2 | PASS | - |
| 55 | leaf2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet3 | PASS | - |
| 56 | leaf2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet3 | PASS | - |
| 57 | leaf2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet3 | PASS | - |
| 58 | leaf2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - host1-DC1_Eth3 | PASS | - |
| 59 | leaf2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1-DC1_Eth4 | PASS | - |
| 60 | leaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf1-DC2_Ethernet1 | PASS | - |
| 61 | leaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf1-DC2_Ethernet2 | PASS | - |
| 62 | leaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC2_Ethernet3 | PASS | - |
| 63 | leaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC2_Ethernet3 | PASS | - |
| 64 | leaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC2_Ethernet3 | PASS | - |
| 65 | leaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - host1-DC2_Eth3 | PASS | - |
| 66 | leaf2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1-DC2_Eth4 | PASS | - |
| 67 | leaf3-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf4-DC1_Ethernet1 | PASS | - |
| 68 | leaf3-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf4-DC1_Ethernet2 | PASS | - |
| 69 | leaf3-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet4 | PASS | - |
| 70 | leaf3-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet4 | PASS | - |
| 71 | leaf3-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet4 | PASS | - |
| 72 | leaf3-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - host2-DC1_Eth1 | PASS | - |
| 73 | leaf3-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2-DC1_Eth2 | PASS | - |
| 74 | leaf3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf4-DC2_Ethernet1 | PASS | - |
| 75 | leaf3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf4-DC2_Ethernet2 | PASS | - |
| 76 | leaf3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC2_Ethernet4 | PASS | - |
| 77 | leaf3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC2_Ethernet4 | PASS | - |
| 78 | leaf3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC2_Ethernet4 | PASS | - |
| 79 | leaf3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - host2-DC2_Eth1 | PASS | - |
| 80 | leaf3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2-DC2_Eth2 | PASS | - |
| 81 | leaf4-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf3-DC1_Ethernet1 | PASS | - |
| 82 | leaf4-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf3-DC1_Ethernet2 | PASS | - |
| 83 | leaf4-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet5 | PASS | - |
| 84 | leaf4-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet5 | PASS | - |
| 85 | leaf4-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet5 | PASS | - |
| 86 | leaf4-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - host2-DC1_Eth3 | PASS | - |
| 87 | leaf4-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2-DC1_Eth4 | PASS | - |
| 88 | leaf4-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf3-DC2_Ethernet1 | PASS | - |
| 89 | leaf4-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf3-DC2_Ethernet2 | PASS | - |
| 90 | leaf4-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC2_Ethernet5 | PASS | - |
| 91 | leaf4-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC2_Ethernet5 | PASS | - |
| 92 | leaf4-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC2_Ethernet5 | PASS | - |
| 93 | leaf4-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - host2-DC2_Eth3 | PASS | - |
| 94 | leaf4-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2-DC2_Eth4 | PASS | - |
| 95 | spine1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1-DC1_Ethernet3 | PASS | - |
| 96 | spine1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2-DC1_Ethernet3 | PASS | - |
| 97 | spine1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3-DC1_Ethernet3 | PASS | - |
| 98 | spine1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4-DC1_Ethernet3 | PASS | - |
| 99 | spine1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1-DC1_Ethernet3 | PASS | - |
| 100 | spine1-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2-DC1_Ethernet3 | PASS | - |
| 101 | spine1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1-DC2_Ethernet3 | PASS | - |
| 102 | spine1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2-DC2_Ethernet3 | PASS | - |
| 103 | spine1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3-DC2_Ethernet3 | PASS | - |
| 104 | spine1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4-DC2_Ethernet3 | PASS | - |
| 105 | spine1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1-DC2_Ethernet3 | PASS | - |
| 106 | spine1-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2-DC2_Ethernet3 | PASS | - |
| 107 | spine2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1-DC1_Ethernet4 | PASS | - |
| 108 | spine2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2-DC1_Ethernet4 | PASS | - |
| 109 | spine2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3-DC1_Ethernet4 | PASS | - |
| 110 | spine2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4-DC1_Ethernet4 | PASS | - |
| 111 | spine2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1-DC1_Ethernet4 | PASS | - |
| 112 | spine2-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2-DC1_Ethernet4 | PASS | - |
| 113 | spine2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1-DC2_Ethernet4 | PASS | - |
| 114 | spine2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2-DC2_Ethernet4 | PASS | - |
| 115 | spine2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3-DC2_Ethernet4 | PASS | - |
| 116 | spine2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4-DC2_Ethernet4 | PASS | - |
| 117 | spine2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1-DC2_Ethernet4 | PASS | - |
| 118 | spine2-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2-DC2_Ethernet4 | PASS | - |
| 119 | spine3-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1-DC1_Ethernet5 | PASS | - |
| 120 | spine3-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2-DC1_Ethernet5 | PASS | - |
| 121 | spine3-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3-DC1_Ethernet5 | PASS | - |
| 122 | spine3-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4-DC1_Ethernet5 | PASS | - |
| 123 | spine3-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1-DC1_Ethernet5 | PASS | - |
| 124 | spine3-DC1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2-DC1_Ethernet5 | PASS | - |
| 125 | spine3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1-DC2_Ethernet5 | PASS | - |
| 126 | spine3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2-DC2_Ethernet5 | PASS | - |
| 127 | spine3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3-DC2_Ethernet5 | PASS | - |
| 128 | spine3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4-DC2_Ethernet5 | PASS | - |
| 129 | spine3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - P2P_LINK_TO_BORDERLEAF1-DC2_Ethernet5 | PASS | - |
| 130 | spine3-DC2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - P2P_LINK_TO_BORDERLEAF2-DC2_Ethernet5 | PASS | - |
| 131 | borderleaf1-DC1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_borderleaf2-DC1_Po1 | PASS | - |
| 132 | borderleaf1-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_borderleaf2-DC2_Po1 | PASS | - |
| 133 | borderleaf2-DC1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_borderleaf1-DC1_Po1 | PASS | - |
| 134 | borderleaf2-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_borderleaf1-DC2_Po1 | PASS | - |
| 135 | leaf1-DC1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf2-DC1_Po1 | PASS | - |
| 136 | leaf1-DC1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host1-DC1_Host1-DC1 | PASS | - |
| 137 | leaf1-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf2-DC2_Po1 | PASS | - |
| 138 | leaf1-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host1-DC2_Host1-DC2 | PASS | - |
| 139 | leaf2-DC1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf1-DC1_Po1 | PASS | - |
| 140 | leaf2-DC1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host1-DC1_Host1-DC1 | PASS | - |
| 141 | leaf2-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf1-DC2_Po1 | PASS | - |
| 142 | leaf2-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host1-DC2_Host1-DC2 | PASS | - |
| 143 | leaf3-DC1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf4-DC1_Po1 | PASS | - |
| 144 | leaf3-DC1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host2-DC1_Host2-DC1 | PASS | - |
| 145 | leaf3-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf4-DC2_Po1 | PASS | - |
| 146 | leaf3-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host2-DC2_Host2-DC2 | PASS | - |
| 147 | leaf4-DC1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf3-DC1_Po1 | PASS | - |
| 148 | leaf4-DC1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host2-DC1_Host2-DC1 | PASS | - |
| 149 | leaf4-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf3-DC2_Po1 | PASS | - |
| 150 | leaf4-DC2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host2-DC2_Host2-DC2 | PASS | - |
| 151 | borderleaf1-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 152 | borderleaf1-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 153 | borderleaf1-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 154 | borderleaf1-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 155 | borderleaf1-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 156 | borderleaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 157 | borderleaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 158 | borderleaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 159 | borderleaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 160 | borderleaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 161 | borderleaf2-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 162 | borderleaf2-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 163 | borderleaf2-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 164 | borderleaf2-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 165 | borderleaf2-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 166 | borderleaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 167 | borderleaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 168 | borderleaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 169 | borderleaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 170 | borderleaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 171 | leaf1-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 172 | leaf1-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 173 | leaf1-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 174 | leaf1-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 175 | leaf1-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 176 | leaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 177 | leaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 178 | leaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 179 | leaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 180 | leaf1-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 181 | leaf2-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 182 | leaf2-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 183 | leaf2-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 184 | leaf2-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 185 | leaf2-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 186 | leaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 187 | leaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 188 | leaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 189 | leaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 190 | leaf2-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 191 | leaf3-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 192 | leaf3-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 193 | leaf3-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 194 | leaf3-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 195 | leaf3-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 196 | leaf3-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 197 | leaf3-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 198 | leaf3-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 199 | leaf3-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 200 | leaf3-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 201 | leaf4-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 202 | leaf4-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 203 | leaf4-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 204 | leaf4-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 205 | leaf4-DC1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 206 | leaf4-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 207 | leaf4-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 208 | leaf4-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - VLAN_10 | PASS | - |
| 209 | leaf4-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - VLAN_20 | PASS | - |
| 210 | leaf4-DC2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3999 - MLAG_PEER_L3_iBGP: vrf Red | PASS | - |
| 211 | borderleaf1-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 212 | borderleaf1-DC2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 213 | borderleaf2-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 214 | borderleaf2-DC2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 215 | leaf1-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 216 | leaf1-DC2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 217 | leaf2-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 218 | leaf2-DC2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 219 | leaf3-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 220 | leaf3-DC2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 221 | leaf4-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 222 | leaf4-DC2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 223 | borderleaf1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 224 | borderleaf1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 225 | borderleaf1-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 226 | borderleaf1-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 227 | borderleaf2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 228 | borderleaf2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 229 | borderleaf2-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 230 | borderleaf2-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 231 | leaf1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 232 | leaf1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 233 | leaf1-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 234 | leaf1-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 235 | leaf2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 236 | leaf2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 237 | leaf2-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 238 | leaf2-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 239 | leaf3-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 240 | leaf3-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 241 | leaf3-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 242 | leaf3-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 243 | leaf4-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 244 | leaf4-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 245 | leaf4-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 246 | leaf4-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 247 | spine1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 248 | spine1-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 249 | spine2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 250 | spine2-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 251 | spine3-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 252 | spine3-DC2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 253 | borderleaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: borderleaf2-DC1_Ethernet1 | PASS | - |
| 254 | borderleaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: borderleaf2-DC1_Ethernet2 | PASS | - |
| 255 | borderleaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet6 | PASS | - |
| 256 | borderleaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet6 | PASS | - |
| 257 | borderleaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet6 | PASS | - |
| 258 | borderleaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: borderleaf2-DC2_Ethernet1 | PASS | - |
| 259 | borderleaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: borderleaf2-DC2_Ethernet2 | PASS | - |
| 260 | borderleaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC2_Ethernet6 | PASS | - |
| 261 | borderleaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC2_Ethernet6 | PASS | - |
| 262 | borderleaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC2_Ethernet6 | PASS | - |
| 263 | borderleaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: borderleaf1-DC1_Ethernet1 | PASS | - |
| 264 | borderleaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: borderleaf1-DC1_Ethernet2 | PASS | - |
| 265 | borderleaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet7 | PASS | - |
| 266 | borderleaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet7 | PASS | - |
| 267 | borderleaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet7 | PASS | - |
| 268 | borderleaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: borderleaf1-DC2_Ethernet1 | PASS | - |
| 269 | borderleaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: borderleaf1-DC2_Ethernet2 | PASS | - |
| 270 | borderleaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC2_Ethernet7 | PASS | - |
| 271 | borderleaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC2_Ethernet7 | PASS | - |
| 272 | borderleaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC2_Ethernet7 | PASS | - |
| 273 | leaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf2-DC1_Ethernet1 | PASS | - |
| 274 | leaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf2-DC1_Ethernet2 | PASS | - |
| 275 | leaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet2 | PASS | - |
| 276 | leaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet2 | PASS | - |
| 277 | leaf1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet2 | PASS | - |
| 278 | leaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf2-DC2_Ethernet1 | PASS | - |
| 279 | leaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf2-DC2_Ethernet2 | PASS | - |
| 280 | leaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC2_Ethernet2 | PASS | - |
| 281 | leaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC2_Ethernet2 | PASS | - |
| 282 | leaf1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC2_Ethernet2 | PASS | - |
| 283 | leaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf1-DC1_Ethernet1 | PASS | - |
| 284 | leaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC1_Ethernet2 | PASS | - |
| 285 | leaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet3 | PASS | - |
| 286 | leaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet3 | PASS | - |
| 287 | leaf2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet3 | PASS | - |
| 288 | leaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf1-DC2_Ethernet1 | PASS | - |
| 289 | leaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC2_Ethernet2 | PASS | - |
| 290 | leaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC2_Ethernet3 | PASS | - |
| 291 | leaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC2_Ethernet3 | PASS | - |
| 292 | leaf2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC2_Ethernet3 | PASS | - |
| 293 | leaf3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf4-DC1_Ethernet1 | PASS | - |
| 294 | leaf3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf4-DC1_Ethernet2 | PASS | - |
| 295 | leaf3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet4 | PASS | - |
| 296 | leaf3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet4 | PASS | - |
| 297 | leaf3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet4 | PASS | - |
| 298 | leaf3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf4-DC2_Ethernet1 | PASS | - |
| 299 | leaf3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf4-DC2_Ethernet2 | PASS | - |
| 300 | leaf3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC2_Ethernet4 | PASS | - |
| 301 | leaf3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC2_Ethernet4 | PASS | - |
| 302 | leaf3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC2_Ethernet4 | PASS | - |
| 303 | leaf4-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf3-DC1_Ethernet1 | PASS | - |
| 304 | leaf4-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf3-DC1_Ethernet2 | PASS | - |
| 305 | leaf4-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet5 | PASS | - |
| 306 | leaf4-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet5 | PASS | - |
| 307 | leaf4-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet5 | PASS | - |
| 308 | leaf4-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf3-DC2_Ethernet1 | PASS | - |
| 309 | leaf4-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf3-DC2_Ethernet2 | PASS | - |
| 310 | leaf4-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC2_Ethernet5 | PASS | - |
| 311 | leaf4-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC2_Ethernet5 | PASS | - |
| 312 | leaf4-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC2_Ethernet5 | PASS | - |
| 313 | spine1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC1_Ethernet3 | PASS | - |
| 314 | spine1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2-DC1_Ethernet3 | PASS | - |
| 315 | spine1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3-DC1_Ethernet3 | PASS | - |
| 316 | spine1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4-DC1_Ethernet3 | PASS | - |
| 317 | spine1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1-DC1_Ethernet3 | PASS | - |
| 318 | spine1-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2-DC1_Ethernet3 | PASS | - |
| 319 | spine1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC2_Ethernet3 | PASS | - |
| 320 | spine1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2-DC2_Ethernet3 | PASS | - |
| 321 | spine1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3-DC2_Ethernet3 | PASS | - |
| 322 | spine1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4-DC2_Ethernet3 | PASS | - |
| 323 | spine1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1-DC2_Ethernet3 | PASS | - |
| 324 | spine1-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2-DC2_Ethernet3 | PASS | - |
| 325 | spine2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC1_Ethernet4 | PASS | - |
| 326 | spine2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2-DC1_Ethernet4 | PASS | - |
| 327 | spine2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3-DC1_Ethernet4 | PASS | - |
| 328 | spine2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4-DC1_Ethernet4 | PASS | - |
| 329 | spine2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1-DC1_Ethernet4 | PASS | - |
| 330 | spine2-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2-DC1_Ethernet4 | PASS | - |
| 331 | spine2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC2_Ethernet4 | PASS | - |
| 332 | spine2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2-DC2_Ethernet4 | PASS | - |
| 333 | spine2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3-DC2_Ethernet4 | PASS | - |
| 334 | spine2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4-DC2_Ethernet4 | PASS | - |
| 335 | spine2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1-DC2_Ethernet4 | PASS | - |
| 336 | spine2-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2-DC2_Ethernet4 | PASS | - |
| 337 | spine3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC1_Ethernet5 | PASS | - |
| 338 | spine3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2-DC1_Ethernet5 | PASS | - |
| 339 | spine3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3-DC1_Ethernet5 | PASS | - |
| 340 | spine3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4-DC1_Ethernet5 | PASS | - |
| 341 | spine3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1-DC1_Ethernet5 | PASS | - |
| 342 | spine3-DC1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2-DC1_Ethernet5 | PASS | - |
| 343 | spine3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC2_Ethernet5 | PASS | - |
| 344 | spine3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2-DC2_Ethernet5 | PASS | - |
| 345 | spine3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3-DC2_Ethernet5 | PASS | - |
| 346 | spine3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4-DC2_Ethernet5 | PASS | - |
| 347 | spine3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: borderleaf1-DC2_Ethernet5 | PASS | - |
| 348 | spine3-DC2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: borderleaf2-DC2_Ethernet5 | PASS | - |
| 349 | borderleaf1-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 350 | borderleaf1-DC2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 351 | borderleaf2-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 352 | borderleaf2-DC2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 353 | leaf1-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 354 | leaf1-DC2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 355 | leaf2-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 356 | leaf2-DC2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 357 | leaf3-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 358 | leaf3-DC2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 359 | leaf4-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 360 | leaf4-DC2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 361 | borderleaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: borderleaf1-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet6 | PASS | - |
| 362 | borderleaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: borderleaf1-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet6 | PASS | - |
| 363 | borderleaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: borderleaf1-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet6 | PASS | - |
| 364 | borderleaf1-DC2 | IP Reachability | ip reachability test p2p links | Source: borderleaf1-DC2_Ethernet3 - Destination: spine1-DC2_Ethernet6 | PASS | - |
| 365 | borderleaf1-DC2 | IP Reachability | ip reachability test p2p links | Source: borderleaf1-DC2_Ethernet4 - Destination: spine2-DC2_Ethernet6 | PASS | - |
| 366 | borderleaf1-DC2 | IP Reachability | ip reachability test p2p links | Source: borderleaf1-DC2_Ethernet5 - Destination: spine3-DC2_Ethernet6 | PASS | - |
| 367 | borderleaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: borderleaf2-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet7 | PASS | - |
| 368 | borderleaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: borderleaf2-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet7 | PASS | - |
| 369 | borderleaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: borderleaf2-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet7 | PASS | - |
| 370 | borderleaf2-DC2 | IP Reachability | ip reachability test p2p links | Source: borderleaf2-DC2_Ethernet3 - Destination: spine1-DC2_Ethernet7 | PASS | - |
| 371 | borderleaf2-DC2 | IP Reachability | ip reachability test p2p links | Source: borderleaf2-DC2_Ethernet4 - Destination: spine2-DC2_Ethernet7 | PASS | - |
| 372 | borderleaf2-DC2 | IP Reachability | ip reachability test p2p links | Source: borderleaf2-DC2_Ethernet5 - Destination: spine3-DC2_Ethernet7 | PASS | - |
| 373 | leaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet2 | PASS | - |
| 374 | leaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet2 | PASS | - |
| 375 | leaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet2 | PASS | - |
| 376 | leaf1-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC2_Ethernet3 - Destination: spine1-DC2_Ethernet2 | PASS | - |
| 377 | leaf1-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC2_Ethernet4 - Destination: spine2-DC2_Ethernet2 | PASS | - |
| 378 | leaf1-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC2_Ethernet5 - Destination: spine3-DC2_Ethernet2 | PASS | - |
| 379 | leaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet3 | PASS | - |
| 380 | leaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet3 | PASS | - |
| 381 | leaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet3 | PASS | - |
| 382 | leaf2-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC2_Ethernet3 - Destination: spine1-DC2_Ethernet3 | PASS | - |
| 383 | leaf2-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC2_Ethernet4 - Destination: spine2-DC2_Ethernet3 | PASS | - |
| 384 | leaf2-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC2_Ethernet5 - Destination: spine3-DC2_Ethernet3 | PASS | - |
| 385 | leaf3-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet4 | PASS | - |
| 386 | leaf3-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet4 | PASS | - |
| 387 | leaf3-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet4 | PASS | - |
| 388 | leaf3-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC2_Ethernet3 - Destination: spine1-DC2_Ethernet4 | PASS | - |
| 389 | leaf3-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC2_Ethernet4 - Destination: spine2-DC2_Ethernet4 | PASS | - |
| 390 | leaf3-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC2_Ethernet5 - Destination: spine3-DC2_Ethernet4 | PASS | - |
| 391 | leaf4-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet5 | PASS | - |
| 392 | leaf4-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet5 | PASS | - |
| 393 | leaf4-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet5 | PASS | - |
| 394 | leaf4-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC2_Ethernet3 - Destination: spine1-DC2_Ethernet5 | PASS | - |
| 395 | leaf4-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC2_Ethernet4 - Destination: spine2-DC2_Ethernet5 | PASS | - |
| 396 | leaf4-DC2 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC2_Ethernet5 - Destination: spine3-DC2_Ethernet5 | PASS | - |
| 397 | spine1-DC1 | IP Reachability | ip reachability test p2p links | Source: spine1-DC1_Ethernet2 - Destination: leaf1-DC1_Ethernet3 | PASS | - |
| 398 | spine1-DC1 | IP Reachability | ip reachability test p2p links | Source: spine1-DC1_Ethernet3 - Destination: leaf2-DC1_Ethernet3 | PASS | - |
| 399 | spine1-DC1 | IP Reachability | ip reachability test p2p links | Source: spine1-DC1_Ethernet4 - Destination: leaf3-DC1_Ethernet3 | PASS | - |
| 400 | spine1-DC1 | IP Reachability | ip reachability test p2p links | Source: spine1-DC1_Ethernet5 - Destination: leaf4-DC1_Ethernet3 | PASS | - |
| 401 | spine1-DC1 | IP Reachability | ip reachability test p2p links | Source: spine1-DC1_Ethernet6 - Destination: borderleaf1-DC1_Ethernet3 | PASS | - |
| 402 | spine1-DC1 | IP Reachability | ip reachability test p2p links | Source: spine1-DC1_Ethernet7 - Destination: borderleaf2-DC1_Ethernet3 | PASS | - |
| 403 | spine1-DC2 | IP Reachability | ip reachability test p2p links | Source: spine1-DC2_Ethernet2 - Destination: leaf1-DC2_Ethernet3 | PASS | - |
| 404 | spine1-DC2 | IP Reachability | ip reachability test p2p links | Source: spine1-DC2_Ethernet3 - Destination: leaf2-DC2_Ethernet3 | PASS | - |
| 405 | spine1-DC2 | IP Reachability | ip reachability test p2p links | Source: spine1-DC2_Ethernet4 - Destination: leaf3-DC2_Ethernet3 | PASS | - |
| 406 | spine1-DC2 | IP Reachability | ip reachability test p2p links | Source: spine1-DC2_Ethernet5 - Destination: leaf4-DC2_Ethernet3 | PASS | - |
| 407 | spine1-DC2 | IP Reachability | ip reachability test p2p links | Source: spine1-DC2_Ethernet6 - Destination: borderleaf1-DC2_Ethernet3 | PASS | - |
| 408 | spine1-DC2 | IP Reachability | ip reachability test p2p links | Source: spine1-DC2_Ethernet7 - Destination: borderleaf2-DC2_Ethernet3 | PASS | - |
| 409 | spine2-DC1 | IP Reachability | ip reachability test p2p links | Source: spine2-DC1_Ethernet2 - Destination: leaf1-DC1_Ethernet4 | PASS | - |
| 410 | spine2-DC1 | IP Reachability | ip reachability test p2p links | Source: spine2-DC1_Ethernet3 - Destination: leaf2-DC1_Ethernet4 | PASS | - |
| 411 | spine2-DC1 | IP Reachability | ip reachability test p2p links | Source: spine2-DC1_Ethernet4 - Destination: leaf3-DC1_Ethernet4 | PASS | - |
| 412 | spine2-DC1 | IP Reachability | ip reachability test p2p links | Source: spine2-DC1_Ethernet5 - Destination: leaf4-DC1_Ethernet4 | PASS | - |
| 413 | spine2-DC1 | IP Reachability | ip reachability test p2p links | Source: spine2-DC1_Ethernet6 - Destination: borderleaf1-DC1_Ethernet4 | PASS | - |
| 414 | spine2-DC1 | IP Reachability | ip reachability test p2p links | Source: spine2-DC1_Ethernet7 - Destination: borderleaf2-DC1_Ethernet4 | PASS | - |
| 415 | spine2-DC2 | IP Reachability | ip reachability test p2p links | Source: spine2-DC2_Ethernet2 - Destination: leaf1-DC2_Ethernet4 | PASS | - |
| 416 | spine2-DC2 | IP Reachability | ip reachability test p2p links | Source: spine2-DC2_Ethernet3 - Destination: leaf2-DC2_Ethernet4 | PASS | - |
| 417 | spine2-DC2 | IP Reachability | ip reachability test p2p links | Source: spine2-DC2_Ethernet4 - Destination: leaf3-DC2_Ethernet4 | PASS | - |
| 418 | spine2-DC2 | IP Reachability | ip reachability test p2p links | Source: spine2-DC2_Ethernet5 - Destination: leaf4-DC2_Ethernet4 | PASS | - |
| 419 | spine2-DC2 | IP Reachability | ip reachability test p2p links | Source: spine2-DC2_Ethernet6 - Destination: borderleaf1-DC2_Ethernet4 | PASS | - |
| 420 | spine2-DC2 | IP Reachability | ip reachability test p2p links | Source: spine2-DC2_Ethernet7 - Destination: borderleaf2-DC2_Ethernet4 | PASS | - |
| 421 | spine3-DC1 | IP Reachability | ip reachability test p2p links | Source: spine3-DC1_Ethernet2 - Destination: leaf1-DC1_Ethernet5 | PASS | - |
| 422 | spine3-DC1 | IP Reachability | ip reachability test p2p links | Source: spine3-DC1_Ethernet3 - Destination: leaf2-DC1_Ethernet5 | PASS | - |
| 423 | spine3-DC1 | IP Reachability | ip reachability test p2p links | Source: spine3-DC1_Ethernet4 - Destination: leaf3-DC1_Ethernet5 | PASS | - |
| 424 | spine3-DC1 | IP Reachability | ip reachability test p2p links | Source: spine3-DC1_Ethernet5 - Destination: leaf4-DC1_Ethernet5 | PASS | - |
| 425 | spine3-DC1 | IP Reachability | ip reachability test p2p links | Source: spine3-DC1_Ethernet6 - Destination: borderleaf1-DC1_Ethernet5 | PASS | - |
| 426 | spine3-DC1 | IP Reachability | ip reachability test p2p links | Source: spine3-DC1_Ethernet7 - Destination: borderleaf2-DC1_Ethernet5 | PASS | - |
| 427 | spine3-DC2 | IP Reachability | ip reachability test p2p links | Source: spine3-DC2_Ethernet2 - Destination: leaf1-DC2_Ethernet5 | PASS | - |
| 428 | spine3-DC2 | IP Reachability | ip reachability test p2p links | Source: spine3-DC2_Ethernet3 - Destination: leaf2-DC2_Ethernet5 | PASS | - |
| 429 | spine3-DC2 | IP Reachability | ip reachability test p2p links | Source: spine3-DC2_Ethernet4 - Destination: leaf3-DC2_Ethernet5 | PASS | - |
| 430 | spine3-DC2 | IP Reachability | ip reachability test p2p links | Source: spine3-DC2_Ethernet5 - Destination: leaf4-DC2_Ethernet5 | PASS | - |
| 431 | spine3-DC2 | IP Reachability | ip reachability test p2p links | Source: spine3-DC2_Ethernet6 - Destination: borderleaf1-DC2_Ethernet5 | PASS | - |
| 432 | spine3-DC2 | IP Reachability | ip reachability test p2p links | Source: spine3-DC2_Ethernet7 - Destination: borderleaf2-DC2_Ethernet5 | PASS | - |
| 433 | borderleaf1-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 434 | borderleaf1-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 435 | borderleaf2-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 436 | borderleaf2-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 437 | leaf1-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 438 | leaf1-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 439 | leaf2-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 440 | leaf2-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 441 | leaf3-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 442 | leaf3-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 443 | leaf4-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 444 | leaf4-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 445 | spine1-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 446 | spine1-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 447 | spine2-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 448 | spine2-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 449 | spine3-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 450 | spine3-DC2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 451 | borderleaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.9 | PASS | - |
| 452 | borderleaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.24 | PASS | - |
| 453 | borderleaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.26 | PASS | - |
| 454 | borderleaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.28 | PASS | - |
| 455 | borderleaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.21 | PASS | - |
| 456 | borderleaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.60 | PASS | - |
| 457 | borderleaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.62 | PASS | - |
| 458 | borderleaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.64 | PASS | - |
| 459 | borderleaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.8 | PASS | - |
| 460 | borderleaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.30 | PASS | - |
| 461 | borderleaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.32 | PASS | - |
| 462 | borderleaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.34 | PASS | - |
| 463 | borderleaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.20 | PASS | - |
| 464 | borderleaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.66 | PASS | - |
| 465 | borderleaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.68 | PASS | - |
| 466 | borderleaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.70 | PASS | - |
| 467 | leaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.1 | PASS | - |
| 468 | leaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.0 | PASS | - |
| 469 | leaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.2 | PASS | - |
| 470 | leaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.4 | PASS | - |
| 471 | leaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.13 | PASS | - |
| 472 | leaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.36 | PASS | - |
| 473 | leaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.38 | PASS | - |
| 474 | leaf1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.40 | PASS | - |
| 475 | leaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.0 | PASS | - |
| 476 | leaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.6 | PASS | - |
| 477 | leaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.8 | PASS | - |
| 478 | leaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.10 | PASS | - |
| 479 | leaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.12 | PASS | - |
| 480 | leaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.42 | PASS | - |
| 481 | leaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.44 | PASS | - |
| 482 | leaf2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.46 | PASS | - |
| 483 | leaf3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.5 | PASS | - |
| 484 | leaf3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.12 | PASS | - |
| 485 | leaf3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.14 | PASS | - |
| 486 | leaf3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.16 | PASS | - |
| 487 | leaf3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.17 | PASS | - |
| 488 | leaf3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.48 | PASS | - |
| 489 | leaf3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.50 | PASS | - |
| 490 | leaf3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.52 | PASS | - |
| 491 | leaf4-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.4 | PASS | - |
| 492 | leaf4-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.18 | PASS | - |
| 493 | leaf4-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.20 | PASS | - |
| 494 | leaf4-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.22 | PASS | - |
| 495 | leaf4-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.16 | PASS | - |
| 496 | leaf4-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.54 | PASS | - |
| 497 | leaf4-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.56 | PASS | - |
| 498 | leaf4-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.58 | PASS | - |
| 499 | spine1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.1 | PASS | - |
| 500 | spine1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.7 | PASS | - |
| 501 | spine1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.13 | PASS | - |
| 502 | spine1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.19 | PASS | - |
| 503 | spine1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.25 | PASS | - |
| 504 | spine1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.31 | PASS | - |
| 505 | spine1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.37 | PASS | - |
| 506 | spine1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.43 | PASS | - |
| 507 | spine1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.49 | PASS | - |
| 508 | spine1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.55 | PASS | - |
| 509 | spine1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.61 | PASS | - |
| 510 | spine1-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.67 | PASS | - |
| 511 | spine2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.3 | PASS | - |
| 512 | spine2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.9 | PASS | - |
| 513 | spine2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.15 | PASS | - |
| 514 | spine2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.21 | PASS | - |
| 515 | spine2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.27 | PASS | - |
| 516 | spine2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.33 | PASS | - |
| 517 | spine2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.39 | PASS | - |
| 518 | spine2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.45 | PASS | - |
| 519 | spine2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.51 | PASS | - |
| 520 | spine2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.57 | PASS | - |
| 521 | spine2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.63 | PASS | - |
| 522 | spine2-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.69 | PASS | - |
| 523 | spine3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.5 | PASS | - |
| 524 | spine3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.11 | PASS | - |
| 525 | spine3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.17 | PASS | - |
| 526 | spine3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.23 | PASS | - |
| 527 | spine3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.29 | PASS | - |
| 528 | spine3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.35 | PASS | - |
| 529 | spine3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.41 | PASS | - |
| 530 | spine3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.47 | PASS | - |
| 531 | spine3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.53 | PASS | - |
| 532 | spine3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.59 | PASS | - |
| 533 | spine3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.65 | PASS | - |
| 534 | spine3-DC2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.71 | PASS | - |
| 535 | borderleaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.111 | PASS | - |
| 536 | borderleaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.112 | PASS | - |
| 537 | borderleaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.113 | PASS | - |
| 538 | borderleaf1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.114 | PASS | - |
| 539 | borderleaf1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.115 | PASS | - |
| 540 | borderleaf1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.116 | PASS | - |
| 541 | borderleaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.111 | PASS | - |
| 542 | borderleaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.112 | PASS | - |
| 543 | borderleaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.113 | PASS | - |
| 544 | borderleaf2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.114 | PASS | - |
| 545 | borderleaf2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.115 | PASS | - |
| 546 | borderleaf2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.116 | PASS | - |
| 547 | leaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.111 | PASS | - |
| 548 | leaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.112 | PASS | - |
| 549 | leaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.113 | PASS | - |
| 550 | leaf1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.114 | PASS | - |
| 551 | leaf1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.115 | PASS | - |
| 552 | leaf1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.116 | PASS | - |
| 553 | leaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.111 | PASS | - |
| 554 | leaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.112 | PASS | - |
| 555 | leaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.113 | PASS | - |
| 556 | leaf2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.114 | PASS | - |
| 557 | leaf2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.115 | PASS | - |
| 558 | leaf2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.116 | PASS | - |
| 559 | leaf3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.111 | PASS | - |
| 560 | leaf3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.112 | PASS | - |
| 561 | leaf3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.113 | PASS | - |
| 562 | leaf3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.114 | PASS | - |
| 563 | leaf3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.115 | PASS | - |
| 564 | leaf3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.116 | PASS | - |
| 565 | leaf4-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.111 | PASS | - |
| 566 | leaf4-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.112 | PASS | - |
| 567 | leaf4-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.113 | PASS | - |
| 568 | leaf4-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.114 | PASS | - |
| 569 | leaf4-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.115 | PASS | - |
| 570 | leaf4-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.116 | PASS | - |
| 571 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.5 | PASS | - |
| 572 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.6 | PASS | - |
| 573 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 574 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 575 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 576 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 577 | spine1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 578 | spine1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 579 | spine1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.7 | PASS | - |
| 580 | spine1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.8 | PASS | - |
| 581 | spine1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.9 | PASS | - |
| 582 | spine1-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.10 | PASS | - |
| 583 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.5 | PASS | - |
| 584 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.6 | PASS | - |
| 585 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 586 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 587 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 588 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 589 | spine2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 590 | spine2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 591 | spine2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.7 | PASS | - |
| 592 | spine2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.8 | PASS | - |
| 593 | spine2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.9 | PASS | - |
| 594 | spine2-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.10 | PASS | - |
| 595 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.5 | PASS | - |
| 596 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.6 | PASS | - |
| 597 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 598 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 599 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 600 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 601 | spine3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 602 | spine3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 603 | spine3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.7 | PASS | - |
| 604 | spine3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.8 | PASS | - |
| 605 | spine3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.9 | PASS | - |
| 606 | spine3-DC2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.10 | PASS | - |
| 607 | borderleaf1-DC1 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 608 | borderleaf1-DC1 | Routing Table | Remote VTEP address | 192.168.102.11 | PASS | - |
| 609 | borderleaf1-DC1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 610 | borderleaf1-DC1 | Routing Table | Remote VTEP address | 192.168.102.7 | PASS | - |
| 611 | borderleaf1-DC1 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 612 | borderleaf1-DC1 | Routing Table | Remote VTEP address | 192.168.102.9 | PASS | - |
| 613 | borderleaf1-DC2 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 614 | borderleaf1-DC2 | Routing Table | Remote VTEP address | 192.168.102.11 | PASS | - |
| 615 | borderleaf1-DC2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 616 | borderleaf1-DC2 | Routing Table | Remote VTEP address | 192.168.102.7 | PASS | - |
| 617 | borderleaf1-DC2 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 618 | borderleaf1-DC2 | Routing Table | Remote VTEP address | 192.168.102.9 | PASS | - |
| 619 | borderleaf2-DC1 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 620 | borderleaf2-DC1 | Routing Table | Remote VTEP address | 192.168.102.11 | PASS | - |
| 621 | borderleaf2-DC1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 622 | borderleaf2-DC1 | Routing Table | Remote VTEP address | 192.168.102.7 | PASS | - |
| 623 | borderleaf2-DC1 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 624 | borderleaf2-DC1 | Routing Table | Remote VTEP address | 192.168.102.9 | PASS | - |
| 625 | borderleaf2-DC2 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 626 | borderleaf2-DC2 | Routing Table | Remote VTEP address | 192.168.102.11 | PASS | - |
| 627 | borderleaf2-DC2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 628 | borderleaf2-DC2 | Routing Table | Remote VTEP address | 192.168.102.7 | PASS | - |
| 629 | borderleaf2-DC2 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 630 | borderleaf2-DC2 | Routing Table | Remote VTEP address | 192.168.102.9 | PASS | - |
| 631 | leaf1-DC1 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 632 | leaf1-DC1 | Routing Table | Remote VTEP address | 192.168.102.11 | PASS | - |
| 633 | leaf1-DC1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 634 | leaf1-DC1 | Routing Table | Remote VTEP address | 192.168.102.7 | PASS | - |
| 635 | leaf1-DC1 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 636 | leaf1-DC1 | Routing Table | Remote VTEP address | 192.168.102.9 | PASS | - |
| 637 | leaf1-DC2 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 638 | leaf1-DC2 | Routing Table | Remote VTEP address | 192.168.102.11 | PASS | - |
| 639 | leaf1-DC2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 640 | leaf1-DC2 | Routing Table | Remote VTEP address | 192.168.102.7 | PASS | - |
| 641 | leaf1-DC2 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 642 | leaf1-DC2 | Routing Table | Remote VTEP address | 192.168.102.9 | PASS | - |
| 643 | leaf2-DC1 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 644 | leaf2-DC1 | Routing Table | Remote VTEP address | 192.168.102.11 | PASS | - |
| 645 | leaf2-DC1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 646 | leaf2-DC1 | Routing Table | Remote VTEP address | 192.168.102.7 | PASS | - |
| 647 | leaf2-DC1 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 648 | leaf2-DC1 | Routing Table | Remote VTEP address | 192.168.102.9 | PASS | - |
| 649 | leaf2-DC2 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 650 | leaf2-DC2 | Routing Table | Remote VTEP address | 192.168.102.11 | PASS | - |
| 651 | leaf2-DC2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 652 | leaf2-DC2 | Routing Table | Remote VTEP address | 192.168.102.7 | PASS | - |
| 653 | leaf2-DC2 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 654 | leaf2-DC2 | Routing Table | Remote VTEP address | 192.168.102.9 | PASS | - |
| 655 | leaf3-DC1 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 656 | leaf3-DC1 | Routing Table | Remote VTEP address | 192.168.102.11 | PASS | - |
| 657 | leaf3-DC1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 658 | leaf3-DC1 | Routing Table | Remote VTEP address | 192.168.102.7 | PASS | - |
| 659 | leaf3-DC1 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 660 | leaf3-DC1 | Routing Table | Remote VTEP address | 192.168.102.9 | PASS | - |
| 661 | leaf3-DC2 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 662 | leaf3-DC2 | Routing Table | Remote VTEP address | 192.168.102.11 | PASS | - |
| 663 | leaf3-DC2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 664 | leaf3-DC2 | Routing Table | Remote VTEP address | 192.168.102.7 | PASS | - |
| 665 | leaf3-DC2 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 666 | leaf3-DC2 | Routing Table | Remote VTEP address | 192.168.102.9 | PASS | - |
| 667 | leaf4-DC1 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 668 | leaf4-DC1 | Routing Table | Remote VTEP address | 192.168.102.11 | PASS | - |
| 669 | leaf4-DC1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 670 | leaf4-DC1 | Routing Table | Remote VTEP address | 192.168.102.7 | PASS | - |
| 671 | leaf4-DC1 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 672 | leaf4-DC1 | Routing Table | Remote VTEP address | 192.168.102.9 | PASS | - |
| 673 | leaf4-DC2 | Routing Table | Remote VTEP address | 192.168.102.5 | PASS | - |
| 674 | leaf4-DC2 | Routing Table | Remote VTEP address | 192.168.102.11 | PASS | - |
| 675 | leaf4-DC2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 676 | leaf4-DC2 | Routing Table | Remote VTEP address | 192.168.102.7 | PASS | - |
| 677 | leaf4-DC2 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 678 | leaf4-DC2 | Routing Table | Remote VTEP address | 192.168.102.9 | PASS | - |
| 679 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 680 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 681 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 682 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 683 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 684 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.7 | PASS | - |
| 685 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 686 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.8 | PASS | - |
| 687 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 688 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.9 | PASS | - |
| 689 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 690 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.10 | PASS | - |
| 691 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.111 | PASS | - |
| 692 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.114 | PASS | - |
| 693 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.112 | PASS | - |
| 694 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.115 | PASS | - |
| 695 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.113 | PASS | - |
| 696 | borderleaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.116 | PASS | - |
| 697 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 698 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 699 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 700 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 701 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 702 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.7 | PASS | - |
| 703 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 704 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.8 | PASS | - |
| 705 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 706 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.9 | PASS | - |
| 707 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 708 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.10 | PASS | - |
| 709 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.111 | PASS | - |
| 710 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.114 | PASS | - |
| 711 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.112 | PASS | - |
| 712 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.115 | PASS | - |
| 713 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.113 | PASS | - |
| 714 | borderleaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.116 | PASS | - |
| 715 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 716 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 717 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 718 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 719 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 720 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.7 | PASS | - |
| 721 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 722 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.8 | PASS | - |
| 723 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 724 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.9 | PASS | - |
| 725 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 726 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.10 | PASS | - |
| 727 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.111 | PASS | - |
| 728 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.114 | PASS | - |
| 729 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.112 | PASS | - |
| 730 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.115 | PASS | - |
| 731 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.113 | PASS | - |
| 732 | borderleaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.116 | PASS | - |
| 733 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 734 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 735 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 736 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 737 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 738 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.7 | PASS | - |
| 739 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 740 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.8 | PASS | - |
| 741 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 742 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.9 | PASS | - |
| 743 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 744 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.10 | PASS | - |
| 745 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.111 | PASS | - |
| 746 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.114 | PASS | - |
| 747 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.112 | PASS | - |
| 748 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.115 | PASS | - |
| 749 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.113 | PASS | - |
| 750 | borderleaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.116 | PASS | - |
| 751 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 752 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 753 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 754 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 755 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 756 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.7 | PASS | - |
| 757 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 758 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.8 | PASS | - |
| 759 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 760 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.9 | PASS | - |
| 761 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 762 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.10 | PASS | - |
| 763 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.111 | PASS | - |
| 764 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.114 | PASS | - |
| 765 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.112 | PASS | - |
| 766 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.115 | PASS | - |
| 767 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.113 | PASS | - |
| 768 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.168.101.116 | PASS | - |
| 769 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 770 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 771 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 772 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 773 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 774 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.7 | PASS | - |
| 775 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 776 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.8 | PASS | - |
| 777 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 778 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.9 | PASS | - |
| 779 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 780 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.10 | PASS | - |
| 781 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.111 | PASS | - |
| 782 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.114 | PASS | - |
| 783 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.112 | PASS | - |
| 784 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.115 | PASS | - |
| 785 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.113 | PASS | - |
| 786 | leaf1-DC2 | Routing Table | Remote Lo0 address | 192.168.101.116 | PASS | - |
| 787 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 788 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 789 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 790 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 791 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 792 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.7 | PASS | - |
| 793 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 794 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.8 | PASS | - |
| 795 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 796 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.9 | PASS | - |
| 797 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 798 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.10 | PASS | - |
| 799 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.111 | PASS | - |
| 800 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.114 | PASS | - |
| 801 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.112 | PASS | - |
| 802 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.115 | PASS | - |
| 803 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.113 | PASS | - |
| 804 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.168.101.116 | PASS | - |
| 805 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 806 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 807 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 808 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 809 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 810 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.7 | PASS | - |
| 811 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 812 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.8 | PASS | - |
| 813 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 814 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.9 | PASS | - |
| 815 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 816 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.10 | PASS | - |
| 817 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.111 | PASS | - |
| 818 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.114 | PASS | - |
| 819 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.112 | PASS | - |
| 820 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.115 | PASS | - |
| 821 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.113 | PASS | - |
| 822 | leaf2-DC2 | Routing Table | Remote Lo0 address | 192.168.101.116 | PASS | - |
| 823 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 824 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 825 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 826 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 827 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 828 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.7 | PASS | - |
| 829 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 830 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.8 | PASS | - |
| 831 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 832 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.9 | PASS | - |
| 833 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 834 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.10 | PASS | - |
| 835 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.111 | PASS | - |
| 836 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.114 | PASS | - |
| 837 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.112 | PASS | - |
| 838 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.115 | PASS | - |
| 839 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.113 | PASS | - |
| 840 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.168.101.116 | PASS | - |
| 841 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 842 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 843 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 844 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 845 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 846 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.7 | PASS | - |
| 847 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 848 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.8 | PASS | - |
| 849 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 850 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.9 | PASS | - |
| 851 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 852 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.10 | PASS | - |
| 853 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.111 | PASS | - |
| 854 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.114 | PASS | - |
| 855 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.112 | PASS | - |
| 856 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.115 | PASS | - |
| 857 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.113 | PASS | - |
| 858 | leaf3-DC2 | Routing Table | Remote Lo0 address | 192.168.101.116 | PASS | - |
| 859 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 860 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 861 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 862 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 863 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 864 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.7 | PASS | - |
| 865 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 866 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.8 | PASS | - |
| 867 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 868 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.9 | PASS | - |
| 869 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 870 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.10 | PASS | - |
| 871 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.111 | PASS | - |
| 872 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.114 | PASS | - |
| 873 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.112 | PASS | - |
| 874 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.115 | PASS | - |
| 875 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.113 | PASS | - |
| 876 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.168.101.116 | PASS | - |
| 877 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.5 | PASS | - |
| 878 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 879 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.6 | PASS | - |
| 880 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 881 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 882 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.7 | PASS | - |
| 883 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 884 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.8 | PASS | - |
| 885 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 886 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.9 | PASS | - |
| 887 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 888 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.10 | PASS | - |
| 889 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.111 | PASS | - |
| 890 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.114 | PASS | - |
| 891 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.112 | PASS | - |
| 892 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.115 | PASS | - |
| 893 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.113 | PASS | - |
| 894 | leaf4-DC2 | Routing Table | Remote Lo0 address | 192.168.101.116 | PASS | - |
| 895 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.5 | PASS | - |
| 896 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.11 | PASS | - |
| 897 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.6 | PASS | - |
| 898 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.12 | PASS | - |
| 899 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.1 | PASS | - |
| 900 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.7 | PASS | - |
| 901 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.2 | PASS | - |
| 902 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.8 | PASS | - |
| 903 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.3 | PASS | - |
| 904 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.9 | PASS | - |
| 905 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.4 | PASS | - |
| 906 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.10 | PASS | - |
| 907 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.111 | PASS | - |
| 908 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.114 | PASS | - |
| 909 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.112 | PASS | - |
| 910 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.115 | PASS | - |
| 911 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.113 | PASS | - |
| 912 | borderleaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC1 - 192.168.101.5 Destination: 192.168.101.116 | PASS | - |
| 913 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.5 | PASS | - |
| 914 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.11 | PASS | - |
| 915 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.6 | PASS | - |
| 916 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.12 | PASS | - |
| 917 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.1 | PASS | - |
| 918 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.7 | PASS | - |
| 919 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.2 | PASS | - |
| 920 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.8 | PASS | - |
| 921 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.3 | PASS | - |
| 922 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.9 | PASS | - |
| 923 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.4 | PASS | - |
| 924 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.10 | PASS | - |
| 925 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.111 | PASS | - |
| 926 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.114 | PASS | - |
| 927 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.112 | PASS | - |
| 928 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.115 | PASS | - |
| 929 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.113 | PASS | - |
| 930 | borderleaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf1-DC2 - 192.168.101.11 Destination: 192.168.101.116 | PASS | - |
| 931 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.5 | PASS | - |
| 932 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.11 | PASS | - |
| 933 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.6 | PASS | - |
| 934 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.12 | PASS | - |
| 935 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.1 | PASS | - |
| 936 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.7 | PASS | - |
| 937 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.2 | PASS | - |
| 938 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.8 | PASS | - |
| 939 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.3 | PASS | - |
| 940 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.9 | PASS | - |
| 941 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.4 | PASS | - |
| 942 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.10 | PASS | - |
| 943 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.111 | PASS | - |
| 944 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.114 | PASS | - |
| 945 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.112 | PASS | - |
| 946 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.115 | PASS | - |
| 947 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.113 | PASS | - |
| 948 | borderleaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC1 - 192.168.101.6 Destination: 192.168.101.116 | PASS | - |
| 949 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.5 | PASS | - |
| 950 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.11 | PASS | - |
| 951 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.6 | PASS | - |
| 952 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.12 | PASS | - |
| 953 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.1 | PASS | - |
| 954 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.7 | PASS | - |
| 955 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.2 | PASS | - |
| 956 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.8 | PASS | - |
| 957 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.3 | PASS | - |
| 958 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.9 | PASS | - |
| 959 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.4 | PASS | - |
| 960 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.10 | PASS | - |
| 961 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.111 | PASS | - |
| 962 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.114 | PASS | - |
| 963 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.112 | PASS | - |
| 964 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.115 | PASS | - |
| 965 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.113 | PASS | - |
| 966 | borderleaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: borderleaf2-DC2 - 192.168.101.12 Destination: 192.168.101.116 | PASS | - |
| 967 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.5 | PASS | - |
| 968 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.11 | PASS | - |
| 969 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.6 | PASS | - |
| 970 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.12 | PASS | - |
| 971 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.1 | PASS | - |
| 972 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.7 | PASS | - |
| 973 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.2 | PASS | - |
| 974 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.8 | PASS | - |
| 975 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.3 | PASS | - |
| 976 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.9 | PASS | - |
| 977 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.4 | PASS | - |
| 978 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.10 | PASS | - |
| 979 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.111 | PASS | - |
| 980 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.114 | PASS | - |
| 981 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.112 | PASS | - |
| 982 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.115 | PASS | - |
| 983 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.113 | PASS | - |
| 984 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.168.101.1 Destination: 192.168.101.116 | PASS | - |
| 985 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.5 | PASS | - |
| 986 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.11 | PASS | - |
| 987 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.6 | PASS | - |
| 988 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.12 | PASS | - |
| 989 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.1 | PASS | - |
| 990 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.7 | PASS | - |
| 991 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.2 | PASS | - |
| 992 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.8 | PASS | - |
| 993 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.3 | PASS | - |
| 994 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.9 | PASS | - |
| 995 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.4 | PASS | - |
| 996 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.10 | PASS | - |
| 997 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.111 | PASS | - |
| 998 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.114 | PASS | - |
| 999 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.112 | PASS | - |
| 1000 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.115 | PASS | - |
| 1001 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.113 | PASS | - |
| 1002 | leaf1-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC2 - 192.168.101.7 Destination: 192.168.101.116 | PASS | - |
| 1003 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.5 | PASS | - |
| 1004 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.11 | PASS | - |
| 1005 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.6 | PASS | - |
| 1006 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.12 | PASS | - |
| 1007 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.1 | PASS | - |
| 1008 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.7 | PASS | - |
| 1009 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.2 | PASS | - |
| 1010 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.8 | PASS | - |
| 1011 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.3 | PASS | - |
| 1012 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.9 | PASS | - |
| 1013 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.4 | PASS | - |
| 1014 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.10 | PASS | - |
| 1015 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.111 | PASS | - |
| 1016 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.114 | PASS | - |
| 1017 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.112 | PASS | - |
| 1018 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.115 | PASS | - |
| 1019 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.113 | PASS | - |
| 1020 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.168.101.2 Destination: 192.168.101.116 | PASS | - |
| 1021 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.5 | PASS | - |
| 1022 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.11 | PASS | - |
| 1023 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.6 | PASS | - |
| 1024 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.12 | PASS | - |
| 1025 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.1 | PASS | - |
| 1026 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.7 | PASS | - |
| 1027 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.2 | PASS | - |
| 1028 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.8 | PASS | - |
| 1029 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.3 | PASS | - |
| 1030 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.9 | PASS | - |
| 1031 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.4 | PASS | - |
| 1032 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.10 | PASS | - |
| 1033 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.111 | PASS | - |
| 1034 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.114 | PASS | - |
| 1035 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.112 | PASS | - |
| 1036 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.115 | PASS | - |
| 1037 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.113 | PASS | - |
| 1038 | leaf2-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC2 - 192.168.101.8 Destination: 192.168.101.116 | PASS | - |
| 1039 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.5 | PASS | - |
| 1040 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.11 | PASS | - |
| 1041 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.6 | PASS | - |
| 1042 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.12 | PASS | - |
| 1043 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.1 | PASS | - |
| 1044 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.7 | PASS | - |
| 1045 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.2 | PASS | - |
| 1046 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.8 | PASS | - |
| 1047 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.3 | PASS | - |
| 1048 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.9 | PASS | - |
| 1049 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.4 | PASS | - |
| 1050 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.10 | PASS | - |
| 1051 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.111 | PASS | - |
| 1052 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.114 | PASS | - |
| 1053 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.112 | PASS | - |
| 1054 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.115 | PASS | - |
| 1055 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.113 | PASS | - |
| 1056 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.168.101.3 Destination: 192.168.101.116 | PASS | - |
| 1057 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.5 | PASS | - |
| 1058 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.11 | PASS | - |
| 1059 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.6 | PASS | - |
| 1060 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.12 | PASS | - |
| 1061 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.1 | PASS | - |
| 1062 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.7 | PASS | - |
| 1063 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.2 | PASS | - |
| 1064 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.8 | PASS | - |
| 1065 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.3 | PASS | - |
| 1066 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.9 | PASS | - |
| 1067 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.4 | PASS | - |
| 1068 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.10 | PASS | - |
| 1069 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.111 | PASS | - |
| 1070 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.114 | PASS | - |
| 1071 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.112 | PASS | - |
| 1072 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.115 | PASS | - |
| 1073 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.113 | PASS | - |
| 1074 | leaf3-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC2 - 192.168.101.9 Destination: 192.168.101.116 | PASS | - |
| 1075 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.5 | PASS | - |
| 1076 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.11 | PASS | - |
| 1077 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.6 | PASS | - |
| 1078 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.12 | PASS | - |
| 1079 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.1 | PASS | - |
| 1080 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.7 | PASS | - |
| 1081 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.2 | PASS | - |
| 1082 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.8 | PASS | - |
| 1083 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.3 | PASS | - |
| 1084 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.9 | PASS | - |
| 1085 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.4 | PASS | - |
| 1086 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.10 | PASS | - |
| 1087 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.111 | PASS | - |
| 1088 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.114 | PASS | - |
| 1089 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.112 | PASS | - |
| 1090 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.115 | PASS | - |
| 1091 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.113 | PASS | - |
| 1092 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.168.101.4 Destination: 192.168.101.116 | PASS | - |
| 1093 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.5 | PASS | - |
| 1094 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.11 | PASS | - |
| 1095 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.6 | PASS | - |
| 1096 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.12 | PASS | - |
| 1097 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.1 | PASS | - |
| 1098 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.7 | PASS | - |
| 1099 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.2 | PASS | - |
| 1100 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.8 | PASS | - |
| 1101 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.3 | PASS | - |
| 1102 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.9 | PASS | - |
| 1103 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.4 | PASS | - |
| 1104 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.10 | PASS | - |
| 1105 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.111 | PASS | - |
| 1106 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.114 | PASS | - |
| 1107 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.112 | PASS | - |
| 1108 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.115 | PASS | - |
| 1109 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.113 | PASS | - |
| 1110 | leaf4-DC2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC2 - 192.168.101.10 Destination: 192.168.101.116 | PASS | - |
