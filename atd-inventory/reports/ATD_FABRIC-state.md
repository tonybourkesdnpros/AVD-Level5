
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
| 225 | 134 | 91 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| leaf1-DC1 |  42 | 25 | 17 | LLDP Topology, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| leaf2-DC1 |  42 | 26 | 16 | LLDP Topology, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| leaf3-DC1 |  42 | 29 | 13 | LLDP Topology, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| leaf4-DC1 |  42 | 31 | 11 | LLDP Topology, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| spine1-DC1 |  19 | 4 | 15 | LLDP Topology, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| spine2-DC1 |  19 | 4 | 15 | LLDP Topology, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| spine3-DC1 |  19 | 15 | 4 | BGP, Routing Table, Loopback0 Reachability |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| NTP |  7 | 7 | 0 |
| Interface State |  62 | 62 | 0 |
| LLDP Topology |  23 | 12 | 11 |
| MLAG |  4 | 4 | 0 |
| IP Reachability |  15 | 2 | 13 |
| BGP |  50 | 17 | 33 |
| Routing Table |  36 | 17 | 19 |
| Loopback0 Reachability |  28 | 13 | 15 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 72 | leaf1-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet3 | FAIL | remote: spine1-DC1.atd.lab - "Ethernet2" |
| 73 | leaf1-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet4 | FAIL | remote: spine2-DC1.atd.lab - "Ethernet2" |
| 74 | leaf1-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet5 | FAIL | remote: spine3-DC1.atd.lab - "Ethernet2" |
| 78 | leaf2-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet4 | FAIL | remote: spine2-DC1.atd.lab - "Ethernet3" |
| 79 | leaf2-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet5 | FAIL | remote: spine3-DC1.atd.lab - "Ethernet3" |
| 82 | leaf3-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet3 | FAIL | remote: spine1-DC1.atd.lab - "Ethernet4" |
| 84 | leaf3-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet5 | FAIL | remote: spine3-DC1.atd.lab - "Ethernet4" |
| 87 | leaf4-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet3 | FAIL | remote: spine1-DC1.atd.lab - "Ethernet5" |
| 88 | leaf4-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet4 | FAIL | remote: spine2-DC1.atd.lab - "Ethernet5" |
| 90 | spine1-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3 - remote: leaf4-DC1_Ethernet3 | FAIL | remote: leaf2-DC1.atd.lab - "Ethernet3" |
| 91 | spine2-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet4 - remote: leaf4-DC1_Ethernet4 | FAIL | remote: leaf3-DC1.atd.lab - "Ethernet4" |
| 97 | leaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet3 | FAIL | 100% packet loss |
| 98 | leaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet4 | FAIL | 100% packet loss |
| 99 | leaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet5 | FAIL | 100% packet loss |
| 100 | leaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet3 | FAIL | 100% packet loss |
| 101 | leaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet4 | FAIL | 100% packet loss |
| 102 | leaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet5 | FAIL | 100% packet loss |
| 103 | leaf3-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet3 | FAIL | 100% packet loss |
| 104 | leaf3-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet4 | FAIL | 100% packet loss |
| 105 | leaf3-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet5 | FAIL | 100% packet loss |
| 106 | leaf4-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet3 | FAIL | 100% packet loss |
| 107 | leaf4-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet4 | FAIL | 100% packet loss |
| 109 | spine1-DC1 | IP Reachability | ip reachability test p2p links | Source: spine1-DC1_Ethernet3 - Destination: leaf4-DC1_Ethernet3 | FAIL | 100% packet loss |
| 110 | spine2-DC1 | IP Reachability | ip reachability test p2p links | Source: spine2-DC1_Ethernet4 - Destination: leaf4-DC1_Ethernet4 | FAIL | 100% packet loss |
| 120 | leaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.0 | FAIL | Session state "Active" |
| 121 | leaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.2 | FAIL | Session state "Active" |
| 122 | leaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.4 | FAIL | Session state "Active" |
| 124 | leaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.6 | FAIL | Session state "Active" |
| 125 | leaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.8 | FAIL | Session state "Active" |
| 126 | leaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.10 | FAIL | Session state "Active" |
| 128 | leaf3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.12 | FAIL | Session state "Active" |
| 129 | leaf3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.14 | FAIL | Session state "Active" |
| 130 | leaf3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.16 | FAIL | Session state "Active" |
| 132 | leaf4-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.18 | FAIL | Session state "Active" |
| 133 | leaf4-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.20 | FAIL | Session state "Active" |
| 135 | spine1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.19 | FAIL | Session state "Active" |
| 136 | spine2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.21 | FAIL | Session state "Active" |
| 138 | leaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.1 | FAIL | Session state "Connect" |
| 139 | leaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.2 | FAIL | Session state "Connect" |
| 140 | leaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.3 | FAIL | Session state "Active" |
| 141 | leaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.1 | FAIL | Session state "Connect" |
| 142 | leaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.2 | FAIL | Session state "Connect" |
| 143 | leaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.3 | FAIL | Session state "Connect" |
| 144 | leaf3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.1 | FAIL | Session state "Connect" |
| 145 | leaf3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.2 | FAIL | Session state "Connect" |
| 147 | leaf4-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.1 | FAIL | Session state "Connect" |
| 148 | leaf4-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.2 | FAIL | Session state "Connect" |
| 150 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.3 | FAIL | Session state "Connect" |
| 151 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.4 | FAIL | Session state "Connect" |
| 152 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.5 | FAIL | Session state "Connect" |
| 153 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.6 | FAIL | Session state "Connect" |
| 154 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.3 | FAIL | Session state "Connect" |
| 155 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.4 | FAIL | Session state "Connect" |
| 156 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.5 | FAIL | Session state "Connect" |
| 157 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.6 | FAIL | Session state "Connect" |
| 158 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.3 | FAIL | Session state "Active" |
| 159 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.4 | FAIL | Session state "Connect" |
| 163 | leaf1-DC1 | Routing Table | Remote Lo1 address | 192.0.254.5 | FAIL | Lo1 192.0.254.5 is not in the routing table |
| 165 | leaf2-DC1 | Routing Table | Remote Lo1 address | 192.0.254.5 | FAIL | Lo1 192.0.254.5 is not in the routing table |
| 166 | leaf3-DC1 | Routing Table | Remote Lo1 address | 192.0.254.3 | FAIL | Lo1 192.0.254.3 is not in the routing table |
| 168 | leaf4-DC1 | Routing Table | Remote Lo1 address | 192.0.254.3 | FAIL | Lo1 192.0.254.3 is not in the routing table |
| 172 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | FAIL | Lo0 192.0.200.5 is not in the routing table |
| 173 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | FAIL | Lo0 192.0.200.6 is not in the routing table |
| 176 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | FAIL | Lo0 192.0.200.5 is not in the routing table |
| 177 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | FAIL | Lo0 192.0.200.6 is not in the routing table |
| 179 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | FAIL | Lo0 192.0.200.4 is not in the routing table |
| 183 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | FAIL | Lo0 192.0.200.4 is not in the routing table |
| 186 | spine1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | FAIL | Lo0 192.0.200.3 is not in the routing table |
| 187 | spine1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | FAIL | Lo0 192.0.200.4 is not in the routing table |
| 188 | spine1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | FAIL | Lo0 192.0.200.5 is not in the routing table |
| 189 | spine1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | FAIL | Lo0 192.0.200.6 is not in the routing table |
| 190 | spine2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | FAIL | Lo0 192.0.200.3 is not in the routing table |
| 191 | spine2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | FAIL | Lo0 192.0.200.4 is not in the routing table |
| 192 | spine2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | FAIL | Lo0 192.0.200.5 is not in the routing table |
| 193 | spine2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | FAIL | Lo0 192.0.200.6 is not in the routing table |
| 195 | spine3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | FAIL | Lo0 192.0.200.4 is not in the routing table |
| 200 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.0.200.3 Destination: 192.0.200.5 | FAIL | 100% packet loss |
| 201 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.0.200.3 Destination: 192.0.200.6 | FAIL | 100% packet loss |
| 204 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.0.200.4 Destination: 192.0.200.5 | FAIL | 100% packet loss |
| 205 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.0.200.4 Destination: 192.0.200.6 | FAIL | 100% packet loss |
| 207 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.0.200.5 Destination: 192.0.200.4 | FAIL | 100% packet loss |
| 211 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.0.200.6 Destination: 192.0.200.4 | FAIL | 100% packet loss |
| 214 | spine1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine1-DC1 - 192.0.200.1 Destination: 192.0.200.3 | FAIL | 100% packet loss |
| 215 | spine1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine1-DC1 - 192.0.200.1 Destination: 192.0.200.4 | FAIL | 100% packet loss |
| 216 | spine1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine1-DC1 - 192.0.200.1 Destination: 192.0.200.5 | FAIL | 100% packet loss |
| 217 | spine1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine1-DC1 - 192.0.200.1 Destination: 192.0.200.6 | FAIL | 100% packet loss |
| 218 | spine2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine2-DC1 - 192.0.200.2 Destination: 192.0.200.3 | FAIL | 100% packet loss |
| 219 | spine2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine2-DC1 - 192.0.200.2 Destination: 192.0.200.4 | FAIL | 100% packet loss |
| 220 | spine2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine2-DC1 - 192.0.200.2 Destination: 192.0.200.5 | FAIL | 100% packet loss |
| 221 | spine2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine2-DC1 - 192.0.200.2 Destination: 192.0.200.6 | FAIL | 100% packet loss |
| 223 | spine3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine3-DC1 - 192.0.200.3 Destination: 192.0.200.4 | FAIL | 100% packet loss |

## All Test Results

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | leaf1-DC1 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 2 | leaf2-DC1 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 3 | leaf3-DC1 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 4 | leaf4-DC1 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 5 | spine1-DC1 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 6 | spine2-DC1 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 7 | spine3-DC1 | NTP | Synchronised with NTP server | NTP | PASS |  |
| 8 | leaf1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf2-DC1_Ethernet1 | PASS |  |
| 9 | leaf1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf2-DC1_Ethernet2 | PASS |  |
| 10 | leaf1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet3 | PASS |  |
| 11 | leaf1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet4 | PASS |  |
| 12 | leaf1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet5 | PASS |  |
| 13 | leaf2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf1-DC1_Ethernet1 | PASS |  |
| 14 | leaf2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf1-DC1_Ethernet2 | PASS |  |
| 15 | leaf2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet3 | PASS |  |
| 16 | leaf2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet4 | PASS |  |
| 17 | leaf2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet5 | PASS |  |
| 18 | leaf3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf4-DC1_Ethernet1 | PASS |  |
| 19 | leaf3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf4-DC1_Ethernet2 | PASS |  |
| 20 | leaf3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet3 | PASS |  |
| 21 | leaf3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet4 | PASS |  |
| 22 | leaf3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet5 | PASS |  |
| 23 | leaf4-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf3-DC1_Ethernet1 | PASS |  |
| 24 | leaf4-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf3-DC1_Ethernet2 | PASS |  |
| 25 | leaf4-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1-DC1_Ethernet3 | PASS |  |
| 26 | leaf4-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2-DC1_Ethernet4 | PASS |  |
| 27 | leaf4-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_SPINE3-DC1_Ethernet5 | PASS |  |
| 28 | spine1-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF4-DC1_Ethernet3 | PASS |  |
| 29 | spine2-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF4-DC1_Ethernet4 | PASS |  |
| 30 | spine3-DC1 | Interface State | Ethernet Interface Status & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4-DC1_Ethernet5 | PASS |  |
| 31 | leaf1-DC1 | Interface State | Port-Channel Interface Status & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf2-DC1_Po1 | PASS |  |
| 32 | leaf2-DC1 | Interface State | Port-Channel Interface Status & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf1-DC1_Po1 | PASS |  |
| 33 | leaf3-DC1 | Interface State | Port-Channel Interface Status & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf4-DC1_Po1 | PASS |  |
| 34 | leaf4-DC1 | Interface State | Port-Channel Interface Status & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf3-DC1_Po1 | PASS |  |
| 35 | leaf1-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS |  |
| 36 | leaf1-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS |  |
| 37 | leaf1-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan110 - Tenant_A_OP_Zone_1 | PASS |  |
| 38 | leaf1-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf Tenant_A_OP_Zone | PASS |  |
| 39 | leaf2-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS |  |
| 40 | leaf2-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS |  |
| 41 | leaf2-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan110 - Tenant_A_OP_Zone_1 | PASS |  |
| 42 | leaf2-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf Tenant_A_OP_Zone | PASS |  |
| 43 | leaf3-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS |  |
| 44 | leaf3-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS |  |
| 45 | leaf3-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan110 - Tenant_A_OP_Zone_1 | PASS |  |
| 46 | leaf3-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf Tenant_A_OP_Zone | PASS |  |
| 47 | leaf4-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS |  |
| 48 | leaf4-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS |  |
| 49 | leaf4-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan110 - Tenant_A_OP_Zone_1 | PASS |  |
| 50 | leaf4-DC1 | Interface State | Vlan Interface Status & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf Tenant_A_OP_Zone | PASS |  |
| 51 | leaf1-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS |  |
| 52 | leaf2-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS |  |
| 53 | leaf3-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS |  |
| 54 | leaf4-DC1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS |  |
| 55 | leaf1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS |  |
| 56 | leaf1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS |  |
| 57 | leaf1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback100 - Tenant_A_OP_Zone_VTEP_DIAGNOSTICS | PASS |  |
| 58 | leaf2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS |  |
| 59 | leaf2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS |  |
| 60 | leaf2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback100 - Tenant_A_OP_Zone_VTEP_DIAGNOSTICS | PASS |  |
| 61 | leaf3-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS |  |
| 62 | leaf3-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS |  |
| 63 | leaf3-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback100 - Tenant_A_OP_Zone_VTEP_DIAGNOSTICS | PASS |  |
| 64 | leaf4-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS |  |
| 65 | leaf4-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS |  |
| 66 | leaf4-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback100 - Tenant_A_OP_Zone_VTEP_DIAGNOSTICS | PASS |  |
| 67 | spine1-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS |  |
| 68 | spine2-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS |  |
| 69 | spine3-DC1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS |  |
| 70 | leaf1-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet1 - remote: leaf2-DC1_Ethernet1 | PASS |  |
| 71 | leaf1-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet2 - remote: leaf2-DC1_Ethernet2 | PASS |  |
| 72 | leaf1-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet3 | FAIL | remote: spine1-DC1.atd.lab - "Ethernet2" |
| 73 | leaf1-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet4 | FAIL | remote: spine2-DC1.atd.lab - "Ethernet2" |
| 74 | leaf1-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet5 | FAIL | remote: spine3-DC1.atd.lab - "Ethernet2" |
| 75 | leaf2-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet1 - remote: leaf1-DC1_Ethernet1 | PASS |  |
| 76 | leaf2-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet2 - remote: leaf1-DC1_Ethernet2 | PASS |  |
| 77 | leaf2-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet3 | PASS |  |
| 78 | leaf2-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet4 | FAIL | remote: spine2-DC1.atd.lab - "Ethernet3" |
| 79 | leaf2-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet5 | FAIL | remote: spine3-DC1.atd.lab - "Ethernet3" |
| 80 | leaf3-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet1 - remote: leaf4-DC1_Ethernet1 | PASS |  |
| 81 | leaf3-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet2 - remote: leaf4-DC1_Ethernet2 | PASS |  |
| 82 | leaf3-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet3 | FAIL | remote: spine1-DC1.atd.lab - "Ethernet4" |
| 83 | leaf3-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet4 | PASS |  |
| 84 | leaf3-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet5 | FAIL | remote: spine3-DC1.atd.lab - "Ethernet4" |
| 85 | leaf4-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet1 - remote: leaf3-DC1_Ethernet1 | PASS |  |
| 86 | leaf4-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet2 - remote: leaf3-DC1_Ethernet2 | PASS |  |
| 87 | leaf4-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3 - remote: spine1-DC1_Ethernet3 | FAIL | remote: spine1-DC1.atd.lab - "Ethernet5" |
| 88 | leaf4-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet4 - remote: spine2-DC1_Ethernet4 | FAIL | remote: spine2-DC1.atd.lab - "Ethernet5" |
| 89 | leaf4-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet5 - remote: spine3-DC1_Ethernet5 | PASS |  |
| 90 | spine1-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet3 - remote: leaf4-DC1_Ethernet3 | FAIL | remote: leaf2-DC1.atd.lab - "Ethernet3" |
| 91 | spine2-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet4 - remote: leaf4-DC1_Ethernet4 | FAIL | remote: leaf3-DC1.atd.lab - "Ethernet4" |
| 92 | spine3-DC1 | LLDP Topology | lldp topology - validate peer and interface | local: Ethernet5 - remote: leaf4-DC1_Ethernet5 | PASS |  |
| 93 | leaf1-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS |  |
| 94 | leaf2-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS |  |
| 95 | leaf3-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS |  |
| 96 | leaf4-DC1 | MLAG | MLAG State active & Status connected | MLAG | PASS |  |
| 97 | leaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet3 | FAIL | 100% packet loss |
| 98 | leaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet4 | FAIL | 100% packet loss |
| 99 | leaf1-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf1-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet5 | FAIL | 100% packet loss |
| 100 | leaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet3 | FAIL | 100% packet loss |
| 101 | leaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet4 | FAIL | 100% packet loss |
| 102 | leaf2-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf2-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet5 | FAIL | 100% packet loss |
| 103 | leaf3-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet3 | FAIL | 100% packet loss |
| 104 | leaf3-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet4 | FAIL | 100% packet loss |
| 105 | leaf3-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf3-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet5 | FAIL | 100% packet loss |
| 106 | leaf4-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC1_Ethernet3 - Destination: spine1-DC1_Ethernet3 | FAIL | 100% packet loss |
| 107 | leaf4-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC1_Ethernet4 - Destination: spine2-DC1_Ethernet4 | FAIL | 100% packet loss |
| 108 | leaf4-DC1 | IP Reachability | ip reachability test p2p links | Source: leaf4-DC1_Ethernet5 - Destination: spine3-DC1_Ethernet5 | PASS |  |
| 109 | spine1-DC1 | IP Reachability | ip reachability test p2p links | Source: spine1-DC1_Ethernet3 - Destination: leaf4-DC1_Ethernet3 | FAIL | 100% packet loss |
| 110 | spine2-DC1 | IP Reachability | ip reachability test p2p links | Source: spine2-DC1_Ethernet4 - Destination: leaf4-DC1_Ethernet4 | FAIL | 100% packet loss |
| 111 | spine3-DC1 | IP Reachability | ip reachability test p2p links | Source: spine3-DC1_Ethernet5 - Destination: leaf4-DC1_Ethernet5 | PASS |  |
| 112 | leaf1-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 113 | leaf2-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 114 | leaf3-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 115 | leaf4-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 116 | spine1-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 117 | spine2-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 118 | spine3-DC1 | BGP | ArBGP is configured and operating | ArBGP | PASS |  |
| 119 | leaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.1 | PASS |  |
| 120 | leaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.0 | FAIL | Session state "Active" |
| 121 | leaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.2 | FAIL | Session state "Active" |
| 122 | leaf1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.4 | FAIL | Session state "Active" |
| 123 | leaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.0 | PASS |  |
| 124 | leaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.6 | FAIL | Session state "Active" |
| 125 | leaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.8 | FAIL | Session state "Active" |
| 126 | leaf2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.10 | FAIL | Session state "Active" |
| 127 | leaf3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.5 | PASS |  |
| 128 | leaf3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.12 | FAIL | Session state "Active" |
| 129 | leaf3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.14 | FAIL | Session state "Active" |
| 130 | leaf3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.16 | FAIL | Session state "Active" |
| 131 | leaf4-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.4 | PASS |  |
| 132 | leaf4-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.18 | FAIL | Session state "Active" |
| 133 | leaf4-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.20 | FAIL | Session state "Active" |
| 134 | leaf4-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.22 | PASS |  |
| 135 | spine1-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.19 | FAIL | Session state "Active" |
| 136 | spine2-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.21 | FAIL | Session state "Active" |
| 137 | spine3-DC1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 172.31.255.23 | PASS |  |
| 138 | leaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.1 | FAIL | Session state "Connect" |
| 139 | leaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.2 | FAIL | Session state "Connect" |
| 140 | leaf1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.3 | FAIL | Session state "Active" |
| 141 | leaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.1 | FAIL | Session state "Connect" |
| 142 | leaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.2 | FAIL | Session state "Connect" |
| 143 | leaf2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.3 | FAIL | Session state "Connect" |
| 144 | leaf3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.1 | FAIL | Session state "Connect" |
| 145 | leaf3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.2 | FAIL | Session state "Connect" |
| 146 | leaf3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.3 | PASS |  |
| 147 | leaf4-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.1 | FAIL | Session state "Connect" |
| 148 | leaf4-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.2 | FAIL | Session state "Connect" |
| 149 | leaf4-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.3 | PASS |  |
| 150 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.3 | FAIL | Session state "Connect" |
| 151 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.4 | FAIL | Session state "Connect" |
| 152 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.5 | FAIL | Session state "Connect" |
| 153 | spine1-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.6 | FAIL | Session state "Connect" |
| 154 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.3 | FAIL | Session state "Connect" |
| 155 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.4 | FAIL | Session state "Connect" |
| 156 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.5 | FAIL | Session state "Connect" |
| 157 | spine2-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.6 | FAIL | Session state "Connect" |
| 158 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.3 | FAIL | Session state "Active" |
| 159 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.4 | FAIL | Session state "Connect" |
| 160 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.5 | PASS |  |
| 161 | spine3-DC1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.0.200.6 | PASS |  |
| 162 | leaf1-DC1 | Routing Table | Remote Lo1 address | 192.0.254.3 | PASS |  |
| 163 | leaf1-DC1 | Routing Table | Remote Lo1 address | 192.0.254.5 | FAIL | Lo1 192.0.254.5 is not in the routing table |
| 164 | leaf2-DC1 | Routing Table | Remote Lo1 address | 192.0.254.3 | PASS |  |
| 165 | leaf2-DC1 | Routing Table | Remote Lo1 address | 192.0.254.5 | FAIL | Lo1 192.0.254.5 is not in the routing table |
| 166 | leaf3-DC1 | Routing Table | Remote Lo1 address | 192.0.254.3 | FAIL | Lo1 192.0.254.3 is not in the routing table |
| 167 | leaf3-DC1 | Routing Table | Remote Lo1 address | 192.0.254.5 | PASS |  |
| 168 | leaf4-DC1 | Routing Table | Remote Lo1 address | 192.0.254.3 | FAIL | Lo1 192.0.254.3 is not in the routing table |
| 169 | leaf4-DC1 | Routing Table | Remote Lo1 address | 192.0.254.5 | PASS |  |
| 170 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | PASS |  |
| 171 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | PASS |  |
| 172 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | FAIL | Lo0 192.0.200.5 is not in the routing table |
| 173 | leaf1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | FAIL | Lo0 192.0.200.6 is not in the routing table |
| 174 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | PASS |  |
| 175 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | PASS |  |
| 176 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | FAIL | Lo0 192.0.200.5 is not in the routing table |
| 177 | leaf2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | FAIL | Lo0 192.0.200.6 is not in the routing table |
| 178 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | PASS |  |
| 179 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | FAIL | Lo0 192.0.200.4 is not in the routing table |
| 180 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | PASS |  |
| 181 | leaf3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | PASS |  |
| 182 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | PASS |  |
| 183 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | FAIL | Lo0 192.0.200.4 is not in the routing table |
| 184 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | PASS |  |
| 185 | leaf4-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | PASS |  |
| 186 | spine1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | FAIL | Lo0 192.0.200.3 is not in the routing table |
| 187 | spine1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | FAIL | Lo0 192.0.200.4 is not in the routing table |
| 188 | spine1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | FAIL | Lo0 192.0.200.5 is not in the routing table |
| 189 | spine1-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | FAIL | Lo0 192.0.200.6 is not in the routing table |
| 190 | spine2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | FAIL | Lo0 192.0.200.3 is not in the routing table |
| 191 | spine2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | FAIL | Lo0 192.0.200.4 is not in the routing table |
| 192 | spine2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | FAIL | Lo0 192.0.200.5 is not in the routing table |
| 193 | spine2-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | FAIL | Lo0 192.0.200.6 is not in the routing table |
| 194 | spine3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.3 | PASS |  |
| 195 | spine3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.4 | FAIL | Lo0 192.0.200.4 is not in the routing table |
| 196 | spine3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.5 | PASS |  |
| 197 | spine3-DC1 | Routing Table | Remote Lo0 address | 192.0.200.6 | PASS |  |
| 198 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.0.200.3 Destination: 192.0.200.3 | PASS |  |
| 199 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.0.200.3 Destination: 192.0.200.4 | PASS |  |
| 200 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.0.200.3 Destination: 192.0.200.5 | FAIL | 100% packet loss |
| 201 | leaf1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1-DC1 - 192.0.200.3 Destination: 192.0.200.6 | FAIL | 100% packet loss |
| 202 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.0.200.4 Destination: 192.0.200.3 | PASS |  |
| 203 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.0.200.4 Destination: 192.0.200.4 | PASS |  |
| 204 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.0.200.4 Destination: 192.0.200.5 | FAIL | 100% packet loss |
| 205 | leaf2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2-DC1 - 192.0.200.4 Destination: 192.0.200.6 | FAIL | 100% packet loss |
| 206 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.0.200.5 Destination: 192.0.200.3 | PASS |  |
| 207 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.0.200.5 Destination: 192.0.200.4 | FAIL | 100% packet loss |
| 208 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.0.200.5 Destination: 192.0.200.5 | PASS |  |
| 209 | leaf3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3-DC1 - 192.0.200.5 Destination: 192.0.200.6 | PASS |  |
| 210 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.0.200.6 Destination: 192.0.200.3 | PASS |  |
| 211 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.0.200.6 Destination: 192.0.200.4 | FAIL | 100% packet loss |
| 212 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.0.200.6 Destination: 192.0.200.5 | PASS |  |
| 213 | leaf4-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4-DC1 - 192.0.200.6 Destination: 192.0.200.6 | PASS |  |
| 214 | spine1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine1-DC1 - 192.0.200.1 Destination: 192.0.200.3 | FAIL | 100% packet loss |
| 215 | spine1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine1-DC1 - 192.0.200.1 Destination: 192.0.200.4 | FAIL | 100% packet loss |
| 216 | spine1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine1-DC1 - 192.0.200.1 Destination: 192.0.200.5 | FAIL | 100% packet loss |
| 217 | spine1-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine1-DC1 - 192.0.200.1 Destination: 192.0.200.6 | FAIL | 100% packet loss |
| 218 | spine2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine2-DC1 - 192.0.200.2 Destination: 192.0.200.3 | FAIL | 100% packet loss |
| 219 | spine2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine2-DC1 - 192.0.200.2 Destination: 192.0.200.4 | FAIL | 100% packet loss |
| 220 | spine2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine2-DC1 - 192.0.200.2 Destination: 192.0.200.5 | FAIL | 100% packet loss |
| 221 | spine2-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine2-DC1 - 192.0.200.2 Destination: 192.0.200.6 | FAIL | 100% packet loss |
| 222 | spine3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine3-DC1 - 192.0.200.3 Destination: 192.0.200.3 | PASS |  |
| 223 | spine3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine3-DC1 - 192.0.200.3 Destination: 192.0.200.4 | FAIL | 100% packet loss |
| 224 | spine3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine3-DC1 - 192.0.200.3 Destination: 192.0.200.5 | PASS |  |
| 225 | spine3-DC1 | Loopback0 Reachability | Loopback0 Reachability | Source: spine3-DC1 - 192.0.200.3 Destination: 192.0.200.6 | PASS |  |
