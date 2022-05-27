# borderleaf2-DC1 Commands Output

## Table of Contents

- [show lldp neighbors](#show-lldp-neighbors)
- [show ip interface brief](#show-ip-interface-brief)
- [show interfaces description](#show-interfaces-description)
- [show version](#show-version)
- [show running-config](#show-running-config)
## show interfaces description

```
Interface                      Status         Protocol           Description
Et1                            up             up                 MLAG_PEER_borderleaf1-DC1_Ethernet1
Et2                            up             up                 MLAG_PEER_borderleaf1-DC1_Ethernet2
Et3                            up             up                 P2P_LINK_TO_SPINE1-DC1_Ethernet7
Et4                            up             up                 P2P_LINK_TO_SPINE2-DC1_Ethernet7
Et5                            up             up                 P2P_LINK_TO_SPINE3-DC1_Ethernet7
Et10                           up             up                 
Et11                           up             up                 
Et12                           up             up                 
Et15                           up             up                 
Lo0                            up             up                 EVPN_Overlay_Peering
Lo1                            up             up                 VTEP_VXLAN_Tunnel_Source
Lo100                          up             up                 Tenant_A_OP_Zone_VTEP_DIAGNOSTICS
Ma0                            up             up                 
Po1                            up             up                 MLAG_PEER_borderleaf1-DC1_Po1
Vl110                          up             up                 Tenant_A_OP_Zone_1
Vl1199                         up             up                 
Vl3009                         up             up                 MLAG_PEER_L3_iBGP: vrf Tenant_A_OP_Zone
Vl4093                         up             up                 MLAG_PEER_L3_PEERING
Vl4094                         up             up                 MLAG_PEER
Vx1                            up             up                 borderleaf2-DC1_VTEP
```
## show ip interface brief

```
Address
Interface       IP Address           Status     Protocol         MTU    Owner  
--------------- -------------------- ---------- ------------ ---------- -------
Ethernet3       172.31.255.31/31     up         up              9214           
Ethernet4       172.31.255.33/31     up         up              9214           
Ethernet5       172.31.255.35/31     up         up              9214           
Loopback0       192.0.200.8/32       up         up             65535           
Loopback1       192.0.254.7/32       up         up             65535           
Loopback100     10.255.1.8/32        up         up             65535           
Management0     192.168.0.26/24      up         up              1500           
Vlan110         10.1.10.1/24         up         up              1500           
Vlan1199        unassigned           up         up              9164           
Vlan3009        10.255.251.9/31      up         up              9214           
Vlan4093        10.255.251.9/31      up         up              9214           
Vlan4094        10.255.252.9/31      up         up              9214
```
## show lldp neighbors

```
Last table change time   : 0:10:41 ago
Number of table inserts  : 9
Number of table deletes  : 0
Number of table drops    : 0
Number of table age-outs : 0

Port          Neighbor Device ID            Neighbor Port ID    TTL
---------- ----------------------------- ---------------------- ---
Et1           borderleaf1-DC1.atd.lab       Ethernet1           120
Et2           borderleaf1-DC1.atd.lab       Ethernet2           120
Et3           spine1-DC1.atd.lab            Ethernet7           120
Et4           spine2-DC1.atd.lab            Ethernet7           120
Et5           spine3-DC1.atd.lab            Ethernet7           120
Et10          core2-ISP1.arista.lab         Ethernet10          120
Et11          core2-ISP2.arista.lab         Ethernet11          120
Et12          DCI.arista.lab                Ethernet2           120
Et15          OOB-DC1.arista.lab            Ethernet10          120
```
## show running-config

```
! Command: show running-config
! device: borderleaf2-DC1 (cEOSLab, EOS-4.27.2F-26069621.4272F (engineering build))
!
no aaa root
!
username Script secret sha512 $6$PNfpb9anSBQ5/aia$phaa3ar5pwkntenD9WHc6Ed5b96lbW0dc0bjtwPnFLaDiCK8D5Cjl6ewP/xdNbl4PtS6Paq.3SssN8pj05NQm.
username admin privilege 15 role network-admin secret 5 $1$5O85YVVn$HrXcfOivJEnISTMb6xrJc.
username ansible_local privilege 15 role network-admin secret sha512 $6$Dzu11L7yp9j3nCM9$FSptxMPyIL555OMO.ldnjDXgwZmrfMYwHSr0uznE5Qoqvd9a6UdjiFcJUhGLtvXVZR1r.A/iF5aAt50hf/EK4/
username arista privilege 15 role network-admin secret 5 $1$4VjIjfd1$XkUVulbNDESHFzcxDU.Tk1
username arista ssh-key ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDJxG+ukMALaEHh4rR1vqB4uPTuHNGcw6ds/gY71CUDiA/Kuj0UH2kx5k5sArydrkjM4zSmB8O0kmqb/ppxGO5h40j4WL1g8n2M5NC/oADzla/R7NGdEpO3mKOZ0M/LcPaeEYnJTYgvmFUw6l3wZXn6nSWRfU/LimlvmX44AkI5RRE3f2FfTJwjy4YigPlvYhRTUUVGCO7JBfokIxVb4/S/LCja5PA0es6N+BXHlAv2svfnTkou72fsc0uKs1qVplcMeajRnseE6VSqQXn9Az45R8cgHpvBwnRJ48z6LX2+CdGUg2ec+WVP0w105YLjzKRy+YppBns/3mjIVZwWGMI/ arista@tony-l5-nam-23-26-45ab6e3c
!
alias conint sh interface | i connected
alias mlag-reload bash /mnt/flash/shut_intfs && sudo shutdown now -r
alias senz show interface counter error | nz
alias shmc show int | awk '/^[A-Z]/ { intf = $1 } /, address is/ { print intf, $6 }'
alias snz show interface counter | nz
alias spd show port-channel %1 detail all
alias sqnz show interface counter queue | nz
alias srnz show interface counter rate | nz
!
alias intdesc
   !! Usage: intdesc interface-name description
   10 config
   20 int %1
   30 desc %2
   40 exit
!
daemon TerminAttr
   exec /usr/bin/TerminAttr -cvaddr=192.168.0.5:9910 -cvauth=key,atd-lab -cvvrf=default -smashexcludes=ale,flexCounter,hardware,kni,pulse,strata -ingestexclude=/Sysdb/cell/1/agent,/Sysdb/cell/2/agent -taillogs
   no shutdown
!
vlan internal order ascending range 1006 1199
!
transceiver qsfp default-mode 4x10G
!
service routing protocols model multi-agent
!
hostname borderleaf2-DC1
ip name-server vrf default 8.8.8.8
ip name-server vrf default 192.168.2.1
dns domain atd.lab
!
spanning-tree mode mstp
no spanning-tree vlan-id 4093-4094
spanning-tree mst 0 priority 16384
!
vlan 110
   name Tenant_A_OP_Zone_1
!
vlan 160
   name Tenant_A_VMOTION
!
vlan 3009
   name MLAG_iBGP_Tenant_A_OP_Zone
   trunk group LEAF_PEER_L3
!
vlan 4093
   name LEAF_PEER_L3
   trunk group LEAF_PEER_L3
!
vlan 4094
   name MLAG_PEER
   trunk group MLAG
!
vrf instance Tenant_A_OP_Zone
!
management api http-commands
   no shutdown
   !
   vrf default
      no shutdown
!
radius-server host 192.168.0.1 key 7 0207165218120E
!
aaa group server radius atds
   server 192.168.0.1
!
aaa authentication login default group atds local
aaa authorization exec default group atds local
aaa authorization commands all default local
!
interface Port-Channel1
   description MLAG_PEER_borderleaf1-DC1_Po1
   switchport trunk allowed vlan 2-4094
   switchport mode trunk
   switchport trunk group LEAF_PEER_L3
   switchport trunk group MLAG
!
interface Ethernet1
   description MLAG_PEER_borderleaf1-DC1_Ethernet1
   channel-group 1 mode active
!
interface Ethernet2
   description MLAG_PEER_borderleaf1-DC1_Ethernet2
   channel-group 1 mode active
!
interface Ethernet3
   description P2P_LINK_TO_SPINE1-DC1_Ethernet7
   mtu 9214
   no switchport
   ip address 172.31.255.31/31
!
interface Ethernet4
   description P2P_LINK_TO_SPINE2-DC1_Ethernet7
   mtu 9214
   no switchport
   ip address 172.31.255.33/31
!
interface Ethernet5
   description P2P_LINK_TO_SPINE3-DC1_Ethernet7
   mtu 9214
   no switchport
   ip address 172.31.255.35/31
!
interface Ethernet10
!
interface Ethernet11
!
interface Ethernet12
!
interface Ethernet15
!
interface Loopback0
   description EVPN_Overlay_Peering
   ip address 192.0.200.8/32
!
interface Loopback1
   description VTEP_VXLAN_Tunnel_Source
   ip address 192.0.254.7/32
!
interface Loopback100
   description Tenant_A_OP_Zone_VTEP_DIAGNOSTICS
   vrf Tenant_A_OP_Zone
   ip address 10.255.1.8/32
!
interface Management0
   description oob_management
   ip address 192.168.0.26/24
!
interface Vlan110
   description Tenant_A_OP_Zone_1
   vrf Tenant_A_OP_Zone
   ip address virtual 10.1.10.1/24
!
interface Vlan3009
   description MLAG_PEER_L3_iBGP: vrf Tenant_A_OP_Zone
   mtu 9214
   vrf Tenant_A_OP_Zone
   ip address 10.255.251.9/31
!
interface Vlan4093
   description MLAG_PEER_L3_PEERING
   mtu 9214
   ip address 10.255.251.9/31
!
interface Vlan4094
   description MLAG_PEER
   mtu 9214
   no autostate
   ip address 10.255.252.9/31
!
interface Vxlan1
   description borderleaf2-DC1_VTEP
   vxlan source-interface Loopback1
   vxlan virtual-router encapsulation mac-address mlag-system-id
   vxlan udp-port 4789
   vxlan vlan 110 vni 10110
   vxlan vlan 160 vni 55160
   vxlan vrf Tenant_A_OP_Zone vni 10
!
ip virtual-router mac-address 00:1c:73:00:dc:01
ip address virtual source-nat vrf Tenant_A_OP_Zone address 10.255.1.8
!
ip routing
ip routing vrf Tenant_A_OP_Zone
!
ip prefix-list PL-LOOPBACKS-EVPN-OVERLAY
   seq 10 permit 192.0.200.0/24 eq 32
   seq 20 permit 192.0.254.0/24 eq 32
!
mlag configuration
   domain-id pod3
   local-interface Vlan4094
   peer-address 10.255.252.8
   peer-link Port-Channel1
   reload-delay mlag 300
   reload-delay non-mlag 330
!
ip route 0.0.0.0/0 10.255.0.1
ip route 0.0.0.0/0 192.168.0.1
!
ntp server 192.168.0.1 iburst source Management0
!
ip radius source-interface Management0
!
route-map RM-CONN-2-BGP permit 10
   match ip address prefix-list PL-LOOPBACKS-EVPN-OVERLAY
!
route-map RM-MLAG-PEER-IN permit 10
   description Make routes learned over MLAG Peer-link less preferred on spines to ensure optimal routing
   set origin incomplete
!
router bfd
   multihop interval 1200 min-rx 1200 multiplier 3
!
router bgp 65103
   router-id 192.0.200.8
   no bgp default ipv4-unicast
   distance bgp 20 200 200
   graceful-restart restart-time 300
   graceful-restart
   maximum-paths 4 ecmp 4
   neighbor EVPN-OVERLAY-PEERS peer group
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
   neighbor MLAG-IPv4-UNDERLAY-PEER peer group
   neighbor MLAG-IPv4-UNDERLAY-PEER remote-as 65103
   neighbor MLAG-IPv4-UNDERLAY-PEER next-hop-self
   neighbor MLAG-IPv4-UNDERLAY-PEER route-map RM-MLAG-PEER-IN in
   neighbor MLAG-IPv4-UNDERLAY-PEER password 7 vnEaG8gMeQf3d3cN6PktXQ==
   neighbor MLAG-IPv4-UNDERLAY-PEER send-community
   neighbor MLAG-IPv4-UNDERLAY-PEER maximum-routes 12000
   neighbor 10.255.251.8 peer group MLAG-IPv4-UNDERLAY-PEER
   neighbor 10.255.251.8 description borderleaf1-DC1
   neighbor 172.31.255.30 peer group IPv4-UNDERLAY-PEERS
   neighbor 172.31.255.30 remote-as 65001
   neighbor 172.31.255.30 description spine1-DC1_Ethernet7
   neighbor 172.31.255.32 peer group IPv4-UNDERLAY-PEERS
   neighbor 172.31.255.32 remote-as 65001
   neighbor 172.31.255.32 description spine2-DC1_Ethernet7
   neighbor 172.31.255.34 peer group IPv4-UNDERLAY-PEERS
   neighbor 172.31.255.34 remote-as 65001
   neighbor 172.31.255.34 description spine3-DC1_Ethernet7
   neighbor 192.0.200.11 peer group EVPN-OVERLAY-PEERS
   neighbor 192.0.200.11 remote-as 65001
   neighbor 192.0.200.11 description spine1-DC1
   neighbor 192.0.200.12 peer group EVPN-OVERLAY-PEERS
   neighbor 192.0.200.12 remote-as 65001
   neighbor 192.0.200.12 description spine2-DC1
   neighbor 192.0.200.13 peer group EVPN-OVERLAY-PEERS
   neighbor 192.0.200.13 remote-as 65001
   neighbor 192.0.200.13 description spine3-DC1
   redistribute connected route-map RM-CONN-2-BGP
   !
   vlan-aware-bundle Tenant_A_OP_Zone
      rd 192.0.200.8:10
      route-target both 10:10
      redistribute learned
      vlan 110
   !
   vlan-aware-bundle Tenant_A_VMOTION
      rd 192.0.200.8:55160
      route-target both 55160:55160
      redistribute learned
      vlan 160
   !
   address-family evpn
      neighbor EVPN-OVERLAY-PEERS activate
   !
   address-family ipv4
      no neighbor EVPN-OVERLAY-PEERS activate
      neighbor IPv4-UNDERLAY-PEERS activate
      neighbor MLAG-IPv4-UNDERLAY-PEER activate
   !
   vrf Tenant_A_OP_Zone
      rd 192.0.200.8:10
      route-target import evpn 10:10
      route-target export evpn 10:10
      router-id 192.0.200.8
      neighbor 10.255.251.8 peer group MLAG-IPv4-UNDERLAY-PEER
      redistribute connected
!
end
```
## show version

```
Arista cEOSLab
Hardware version: 
Serial number: borderleaf2-DC1
Hardware MAC address: 001c.73c6.c601
System MAC address: 001c.73c6.c601

Software image version: 4.27.2F-26069621.4272F (engineering build)
Architecture: i686
Internal build version: 4.27.2F-26069621.4272F
Internal build ID: b3360a82-d532-4043-b6b0-50707eede2a9
Image format version: 1.0
Image optimization: None

cEOS tools version: 1.1
Kernel version: 5.4.132-1.el7.elrepo.x86_64

Uptime: 5 hours and 20 minutes
Total memory: 74120000 kB
Free memory: 14517752 kB
```
