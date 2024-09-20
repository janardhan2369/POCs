# GWleaf2-dc2
# Table of Contents

- [Management](#management)
  - [Management Interfaces](#management-interfaces)
  - [DNS Domain](#dns-domain)
  - [Name Servers](#name-servers)
  - [NTP](#ntp)
  - [Management API HTTP](#management-api-http)
- [Authentication](#authentication)
  - [Local Users](#local-users)
  - [AAA Authentication](#aaa-authentication)
  - [AAA Authorization](#aaa-authorization)
- [Prompt](#prompt)
- [Aliases](#aliases)
- [Monitoring](#monitoring)
  - [TerminAttr Daemon](#terminattr-daemon)
  - [SFlow](#sflow)
- [MLAG](#mlag)
  - [MLAG Summary](#mlag-summary)
  - [MLAG Device Configuration](#mlag-device-configuration)
- [Spanning Tree](#spanning-tree)
  - [Spanning Tree Summary](#spanning-tree-summary)
  - [Spanning Tree Device Configuration](#spanning-tree-device-configuration)
- [Internal VLAN Allocation Policy](#internal-vlan-allocation-policy)
  - [Internal VLAN Allocation Policy Summary](#internal-vlan-allocation-policy-summary)
  - [Internal VLAN Allocation Policy Configuration](#internal-vlan-allocation-policy-configuration)
- [VLANs](#vlans)
  - [VLANs Summary](#vlans-summary)
  - [VLANs Device Configuration](#vlans-device-configuration)
- [Interfaces](#interfaces)
  - [Switchport Default](#switchport-default)
  - [Ethernet Interfaces](#ethernet-interfaces)
  - [Port-Channel Interfaces](#port-channel-interfaces)
  - [Loopback Interfaces](#loopback-interfaces)
  - [VLAN Interfaces](#vlan-interfaces)
  - [VXLAN Interface](#vxlan-interface)
- [Routing](#routing)
  - [Service Routing Protocols Model](#service-routing-protocols-model)
  - [Virtual Router MAC Address](#virtual-router-mac-address)
  - [IP Routing](#ip-routing)
  - [IPv6 Routing](#ipv6-routing)
  - [Static Routes](#static-routes)
  - [Router BGP](#router-bgp)
- [BFD](#bfd)
  - [Router BFD](#router-bfd)
- [Multicast](#multicast)
  - [IP IGMP Snooping](#ip-igmp-snooping)
- [Filters](#filters)
  - [Prefix-lists](#prefix-lists)
  - [Route-maps](#route-maps)
- [ACL](#acl)
- [VRF Instances](#vrf-instances)
  - [VRF Instances Summary](#vrf-instances-summary)
  - [VRF Instances Device Configuration](#vrf-instances-device-configuration)
- [Virtual Source NAT](#virtual-source-nat)
  - [Virtual Source NAT Summary](#virtual-source-nat-summary)
  - [Virtual Source NAT Configuration](#virtual-source-nat-configuration)
- [Platform](#platform)
  - [Platform Summary](#platform-summary)
  - [Platform Configuration](#platform-configuration)
- [MACsec](#macsec)
  - [MACsec Summary](#macsec-summary)
  - [MACsec Device Configuration](#macsec-device-configuration)
- [Quality Of Service](#quality-of-service)
- [EOS CLI](#eos-cli)

# Management

## Management Interfaces

### Management Interfaces Summary

#### IPv4

| Management Interface | description | Type | VRF | IP Address | Gateway |
| -------------------- | ----------- | ---- | --- | ---------- | ------- |
| Management1 | oob_management | oob | MGMT | 172.28.143.97/20 | 172.28.128.1 |

#### IPv6

| Management Interface | description | Type | VRF | IPv6 Address | IPv6 Gateway |
| -------------------- | ----------- | ---- | --- | ------------ | ------------ |
| Management1 | oob_management | oob | MGMT | -  | - |

### Management Interfaces Device Configuration

```eos
!
interface Management1
   description oob_management
   no shutdown
   vrf MGMT
   ip address 172.28.143.97/20
```

## DNS Domain

### DNS domain: sjc.aristanetworks.com

### DNS Domain Device Configuration

```eos
!
dns domain sjc.aristanetworks.com
!
```

## Name Servers

### Name Servers Summary

| Name Server | Source VRF |
| ----------- | ---------- |
| 172.22.60.20 | MGMT |

### Name Servers Device Configuration

```eos
ip name-server vrf MGMT 172.22.60.20
```

## NTP

### NTP Summary

#### NTP Local Interface

| Interface | VRF |
| --------- | --- |
| Management1 | MGMT |

#### NTP Servers

| Server | VRF | Preferred | Burst | iBurst | Version | Min Poll | Max Poll | Local-interface | Key |
| ------ | --- | --------- | ----- | ------ | ------- | -------- | -------- | --------------- | --- |
| 172.22.60.22 | MGMT | True | - | - | - | - | - | - | - |

### NTP Device Configuration

```eos
!
ntp local-interface vrf MGMT Management1
ntp server vrf MGMT 172.22.60.22 prefer
```

## Management API HTTP

### Management API HTTP Summary

| HTTP | HTTPS |
| ---- | ----- |
| True | True |

### Management API VRF Access

| VRF Name | IPv4 ACL | IPv6 ACL |
| -------- | -------- | -------- |
| MGMT | - | - |

### Management API HTTP Configuration

```eos
!
management api http-commands
   protocol https
   protocol http
   no shutdown
   !
   vrf MGMT
      no shutdown
```

# Authentication

## Local Users

### Local Users Summary

| User | Privilege | Role |
| ---- | --------- | ---- |
| admin | 15 | network-admin |
| arista | 15 | network-admin |
| cvpadmin | 15 | network-admin |

### Local Users Device Configuration

```eos
!
username admin privilege 15 role network-admin nopassword
username arista privilege 15 role network-admin secret sha512 $6$fTv/8ehbz7BW408.$5uaZiXapZq7WazT6BrfDktsjLFM6MIpbnpZp62wEaCLZ6ILbw2WuQ2Z2THkiDQk.IXv2RpUZ13zbHfApT/EO81
username cvpadmin privilege 15 role network-admin secret sha512 $6$MUlXuH7QQNH4qejR$m2d./2h0PQd/Ls3V8IwSouMMIxrDMl7cobLtjKpXpAUU7f53RXp92RhKbQ.2fb7wm.TeYFO7f7D4kKmGwWKuC0
```

## AAA Authentication

### AAA Authentication Summary

| Type | Sub-type | User Stores |
| ---- | -------- | ---------- |

Policy local allow-nopassword-remote-login has been enabled.

### AAA Authentication Device Configuration

```eos
!
aaa authentication policy local allow-nopassword-remote-login
!
```

## AAA Authorization

### AAA Authorization Summary

| Type | User Stores |
| ---- | ----------- |
| Exec | local |

Authorization for configuration commands is disabled.

### AAA Authorization Device Configuration

```eos
!
aaa authorization exec default local
!
```

# Prompt

```eos
!
prompt \%H.\%D{\%H:\%M:\%S}\%P
```

# Aliases

```eos
alias cc clear counters
alias senz show interface counter error | nz
alias snz show interface counter | nz
alias sqnz show interface counter queue | nz
alias srnz show interface counter rate | nz

!
```

# Monitoring

## TerminAttr Daemon

### TerminAttr Daemon Summary

| CV Compression | CloudVision Servers | VRF | Authentication | Smash Excludes | Ingest Exclude | Bypass AAA |
| -------------- | ------------------- | --- | -------------- | -------------- | -------------- | ---------- |
| gzip | 172.28.136.142:9910 | MGMT | key,stdpoc | ale,flexCounter,hardware,kni,pulse,strata | /Sysdb/cell/1/agent,/Sysdb/cell/2/agent | False |

### TerminAttr Daemon Device Configuration

```eos
!
daemon TerminAttr
   exec /usr/bin/TerminAttr -cvaddr=172.28.136.142:9910 -cvauth=key,stdpoc -cvvrf=MGMT -smashexcludes=ale,flexCounter,hardware,kni,pulse,strata -ingestexclude=/Sysdb/cell/1/agent,/Sysdb/cell/2/agent -taillogs
   no shutdown
```

## SFlow

### SFlow Summary

| VRF | SFlow Source Interface | SFlow Destination | Port |
| --- | ---------------------- | ----------------- | ---- |
| default | - | 127.0.0.1 | 6343  |
| default | Loopback0 | - | - |

sFlow Sample Rate: 5000

sFlow is enabled.

### SFlow Device Configuration

```eos
!
sflow sample 5000
sflow destination 127.0.0.1
sflow source-interface Loopback0
sflow run
```

# MLAG

## MLAG Summary

| Domain-id | Local-interface | Peer-address | Peer-link |
| --------- | --------------- | ------------ | --------- |
| DC2_GWleaf | Vlan4094 | 10.255.252.24 | Port-Channel10 |

Dual primary detection is disabled.

## MLAG Device Configuration

```eos
!
mlag configuration
   domain-id DC2_GWleaf
   local-interface Vlan4094
   peer-address 10.255.252.24
   peer-link Port-Channel10
   reload-delay mlag 780
   reload-delay non-mlag 1020
```

# Spanning Tree

## Spanning Tree Summary

STP mode: **mstp**

### MSTP Instance and Priority

| Instance(s) | Priority |
| -------- | -------- |
| 0 | 16384 |

### Global Spanning-Tree Settings

- Spanning Tree disabled for VLANs: **4093-4094**

## Spanning Tree Device Configuration

```eos
!
spanning-tree mode mstp
no spanning-tree vlan-id 4093-4094
spanning-tree mst 0 priority 16384
```

# Internal VLAN Allocation Policy

## Internal VLAN Allocation Policy Summary

| Policy Allocation | Range Beginning | Range Ending |
| ------------------| --------------- | ------------ |
| ascending | 4020 | 4090 |

## Internal VLAN Allocation Policy Configuration

```eos
!
vlan internal order ascending range 4020 4090
```

# VLANs

## VLANs Summary

| VLAN ID | Name | Trunk Groups |
| ------- | ---- | ------------ |
| 100 | Tenant_A_FIREWALL | - |
| 200 | Tenant_B_FIREWALL | - |
| 1101 | Tenant_A_VLAN_1 | - |
| 1102 | Tenant_A_VLAN_2 | - |
| 1103 | Tenant_A_VLAN_3 | - |
| 1104 | Tenant_A_VLAN_4 | - |
| 1105 | Tenant_A_VLAN_5 | - |
| 1106 | Tenant_A_VLAN_6 | - |
| 1107 | Tenant_A_VLAN_7 | - |
| 1108 | Tenant_A_VLAN_8 | - |
| 1109 | Tenant_A_VLAN_9 | - |
| 1110 | Tenant_A_VLAN_10 | - |
| 1201 | Tenant_B_VLAN_1 | - |
| 1202 | Tenant_B_VLAN_2 | - |
| 1203 | Tenant_B_VLAN_3 | - |
| 1204 | Tenant_B_VLAN_4 | - |
| 1205 | Tenant_B_VLAN_5 | - |
| 1206 | Tenant_B_VLAN_6 | - |
| 1207 | Tenant_B_VLAN_7 | - |
| 1208 | Tenant_B_VLAN_8 | - |
| 1209 | Tenant_B_VLAN_9 | - |
| 1210 | Tenant_B_VLAN_10 | - |
| 3100 | MLAG_iBGP_Tenant_A | LEAF_PEER_L3 |
| 3101 | MLAG_iBGP_Tenant_B | LEAF_PEER_L3 |
| 4093 | LEAF_PEER_L3 | LEAF_PEER_L3 |
| 4094 | MLAG_PEER | MLAG |

## VLANs Device Configuration

```eos
!
vlan 100
   name Tenant_A_FIREWALL
!
vlan 200
   name Tenant_B_FIREWALL
!
vlan 1101
   name Tenant_A_VLAN_1
!
vlan 1102
   name Tenant_A_VLAN_2
!
vlan 1103
   name Tenant_A_VLAN_3
!
vlan 1104
   name Tenant_A_VLAN_4
!
vlan 1105
   name Tenant_A_VLAN_5
!
vlan 1106
   name Tenant_A_VLAN_6
!
vlan 1107
   name Tenant_A_VLAN_7
!
vlan 1108
   name Tenant_A_VLAN_8
!
vlan 1109
   name Tenant_A_VLAN_9
!
vlan 1110
   name Tenant_A_VLAN_10
!
vlan 1201
   name Tenant_B_VLAN_1
!
vlan 1202
   name Tenant_B_VLAN_2
!
vlan 1203
   name Tenant_B_VLAN_3
!
vlan 1204
   name Tenant_B_VLAN_4
!
vlan 1205
   name Tenant_B_VLAN_5
!
vlan 1206
   name Tenant_B_VLAN_6
!
vlan 1207
   name Tenant_B_VLAN_7
!
vlan 1208
   name Tenant_B_VLAN_8
!
vlan 1209
   name Tenant_B_VLAN_9
!
vlan 1210
   name Tenant_B_VLAN_10
!
vlan 3100
   name MLAG_iBGP_Tenant_A
   trunk group LEAF_PEER_L3
!
vlan 3101
   name MLAG_iBGP_Tenant_B
   trunk group LEAF_PEER_L3
!
vlan 4093
   name LEAF_PEER_L3
   trunk group LEAF_PEER_L3
!
vlan 4094
   name MLAG_PEER
   trunk group MLAG
```

# Interfaces

## Switchport Default

### Switchport Defaults Summary

- Default Switchport Mode: routed

### Switchport Default Configuration

```eos
!
switchport default mode routed
```

## Ethernet Interfaces

### Ethernet Interfaces Summary

#### L2

| Interface | Description | Mode | VLANs | Native VLAN | Trunk Group | Channel-Group |
| --------- | ----------- | ---- | ----- | ----------- | ----------- | ------------- |
| Ethernet10 | MLAG_PEER_GWleaf1-dc2_Ethernet10 | *trunk | *2-4094 | *- | *['LEAF_PEER_L3', 'MLAG'] | 10 |
| Ethernet11 | MLAG_PEER_GWleaf1-dc2_Ethernet11 | *trunk | *2-4094 | *- | *['LEAF_PEER_L3', 'MLAG'] | 10 |

*Inherited from Port-Channel Interface

#### IPv4

| Interface | Description | Type | Channel Group | IP Address | VRF |  MTU | Shutdown | ACL In | ACL Out |
| --------- | ----------- | -----| ------------- | ---------- | ----| ---- | -------- | ------ | ------- |
| Ethernet1 | P2P_LINK_TO_HS426-DC2_Ethernet1 | routed | - | 172.32.250.53/31 | default | 9214 | false | - | - |
| Ethernet3 | P2P_LINK_TO_HS427-DC2_Ethernet2 | routed | - | 172.32.250.55/31 | default | 9214 | false | - | - |
| Ethernet52/1 | P2P_LINK_TO_hs430_Ethernet52/1 | routed | - | 192.168.1.1/31 | default | 9214 | false | - | - |

### Ethernet Interfaces Device Configuration

```eos
!
interface Ethernet1
   description P2P_LINK_TO_HS426-DC2_Ethernet1
   no shutdown
   mtu 9214
   no switchport
   ip address 172.32.250.53/31
!
interface Ethernet3
   description P2P_LINK_TO_HS427-DC2_Ethernet2
   no shutdown
   mtu 9214
   no switchport
   ip address 172.32.250.55/31
!
interface Ethernet10
   description MLAG_PEER_GWleaf1-dc2_Ethernet10
   no shutdown
   channel-group 10 mode active
!
interface Ethernet11
   description MLAG_PEER_GWleaf1-dc2_Ethernet11
   no shutdown
   channel-group 10 mode active
!
interface Ethernet52/1
   description P2P_LINK_TO_hs430_Ethernet52/1
   no shutdown
   mac security profile MACSEC_DCI
   mtu 9214
   no switchport
   ip address 192.168.1.1/31
```

## Port-Channel Interfaces

### Port-Channel Interfaces Summary

#### L2

| Interface | Description | Type | Mode | VLANs | Native VLAN | Trunk Group | LACP Fallback Timeout | LACP Fallback Mode | MLAG ID | EVPN ESI |
| --------- | ----------- | ---- | ---- | ----- | ----------- | ------------| --------------------- | ------------------ | ------- | -------- |
| Port-Channel10 | MLAG_PEER_GWleaf1-dc2_Po10 | switched | trunk | 2-4094 | - | ['LEAF_PEER_L3', 'MLAG'] | - | - | - | - |

### Port-Channel Interfaces Device Configuration

```eos
!
interface Port-Channel10
   description MLAG_PEER_GWleaf1-dc2_Po10
   no shutdown
   switchport
   switchport trunk allowed vlan 2-4094
   switchport mode trunk
   switchport trunk group LEAF_PEER_L3
   switchport trunk group MLAG
```

## Loopback Interfaces

### Loopback Interfaces Summary

#### IPv4

| Interface | Description | VRF | IP Address |
| --------- | ----------- | --- | ---------- |
| Loopback0 | EVPN_Overlay_Peering | default | 192.168.253.16/32 |
| Loopback1 | VTEP_VXLAN_Tunnel_Source | default | 192.168.254.15/32 |
| Loopback101 | Tenant_A_VTEP_DIAGNOSTICS | Tenant_A | 11.1.255.16/32 |
| Loopback102 | Tenant_B_VTEP_DIAGNOSTICS | Tenant_B | 11.2.255.16/32 |

#### IPv6

| Interface | Description | VRF | IPv6 Address |
| --------- | ----------- | --- | ------------ |
| Loopback0 | EVPN_Overlay_Peering | default | - |
| Loopback1 | VTEP_VXLAN_Tunnel_Source | default | - |
| Loopback101 | Tenant_A_VTEP_DIAGNOSTICS | Tenant_A | - |
| Loopback102 | Tenant_B_VTEP_DIAGNOSTICS | Tenant_B | - |


### Loopback Interfaces Device Configuration

```eos
!
interface Loopback0
   description EVPN_Overlay_Peering
   no shutdown
   ip address 192.168.253.16/32
!
interface Loopback1
   description VTEP_VXLAN_Tunnel_Source
   no shutdown
   ip address 192.168.254.15/32
!
interface Loopback101
   description Tenant_A_VTEP_DIAGNOSTICS
   no shutdown
   vrf Tenant_A
   ip address 11.1.255.16/32
!
interface Loopback102
   description Tenant_B_VTEP_DIAGNOSTICS
   no shutdown
   vrf Tenant_B
   ip address 11.2.255.16/32
```

## VLAN Interfaces

### VLAN Interfaces Summary

| Interface | Description | VRF |  MTU | Shutdown |
| --------- | ----------- | --- | ---- | -------- |
| Vlan100 |  Tenant_A_FIREWALL  |  Tenant_A  |  9000  |  false  |
| Vlan200 |  Tenant_B_FIREWALL  |  Tenant_B  |  9000  |  false  |
| Vlan1101 |  Tenant_A_VLAN_1  |  Tenant_A  |  9000  |  false  |
| Vlan1102 |  Tenant_A_VLAN_2  |  Tenant_A  |  9000  |  false  |
| Vlan1103 |  Tenant_A_VLAN_3  |  Tenant_A  |  9000  |  false  |
| Vlan1104 |  Tenant_A_VLAN_4  |  Tenant_A  |  9000  |  false  |
| Vlan1105 |  Tenant_A_VLAN_5  |  Tenant_A  |  9000  |  false  |
| Vlan1106 |  Tenant_A_VLAN_6  |  Tenant_A  |  9000  |  false  |
| Vlan1107 |  Tenant_A_VLAN_7  |  Tenant_A  |  9000  |  false  |
| Vlan1108 |  Tenant_A_VLAN_8  |  Tenant_A  |  9000  |  false  |
| Vlan1109 |  Tenant_A_VLAN_9  |  Tenant_A  |  9000  |  false  |
| Vlan1110 |  Tenant_A_VLAN_10  |  Tenant_A  |  9000  |  false  |
| Vlan1201 |  Tenant_B_VLAN_1  |  Tenant_B  |  9000  |  false  |
| Vlan1202 |  Tenant_B_VLAN_2  |  Tenant_B  |  9000  |  false  |
| Vlan1203 |  Tenant_B_VLAN_3  |  Tenant_B  |  9000  |  false  |
| Vlan1204 |  Tenant_B_VLAN_4  |  Tenant_B  |  9000  |  false  |
| Vlan1205 |  Tenant_B_VLAN_5  |  Tenant_B  |  9000  |  false  |
| Vlan1206 |  Tenant_B_VLAN_6  |  Tenant_B  |  9000  |  false  |
| Vlan1207 |  Tenant_B_VLAN_7  |  Tenant_B  |  9000  |  false  |
| Vlan1208 |  Tenant_B_VLAN_8  |  Tenant_B  |  9000  |  false  |
| Vlan1209 |  Tenant_B_VLAN_9  |  Tenant_B  |  9000  |  false  |
| Vlan1210 |  Tenant_B_VLAN_10  |  Tenant_B  |  9000  |  false  |
| Vlan3100 |  MLAG_PEER_L3_iBGP: vrf Tenant_A  |  Tenant_A  |  9214  |  false  |
| Vlan3101 |  MLAG_PEER_L3_iBGP: vrf Tenant_B  |  Tenant_B  |  9214  |  false  |
| Vlan4093 |  MLAG_PEER_L3_PEERING  |  default  |  9214  |  false  |
| Vlan4094 |  MLAG_PEER  |  default  |  9214  |  false  |

#### IPv4

| Interface | VRF | IP Address | IP Address Virtual | IP Router Virtual Address | VRRP | ACL In | ACL Out |
| --------- | --- | ---------- | ------------------ | ------------------------- | ---- | ------ | ------- |
| Vlan100 |  Tenant_A  |  -  |  11.0.1.1/24  |  -  |  -  |  -  |  -  |
| Vlan200 |  Tenant_B  |  -  |  11.0.2.1/24  |  -  |  -  |  -  |  -  |
| Vlan1101 |  Tenant_A  |  -  |  11.1.1.1/24  |  -  |  -  |  -  |  -  |
| Vlan1102 |  Tenant_A  |  -  |  11.1.2.1/24  |  -  |  -  |  -  |  -  |
| Vlan1103 |  Tenant_A  |  -  |  11.1.3.1/24  |  -  |  -  |  -  |  -  |
| Vlan1104 |  Tenant_A  |  -  |  11.1.4.1/24  |  -  |  -  |  -  |  -  |
| Vlan1105 |  Tenant_A  |  -  |  11.1.5.1/24  |  -  |  -  |  -  |  -  |
| Vlan1106 |  Tenant_A  |  -  |  11.1.6.1/24  |  -  |  -  |  -  |  -  |
| Vlan1107 |  Tenant_A  |  -  |  11.1.7.1/24  |  -  |  -  |  -  |  -  |
| Vlan1108 |  Tenant_A  |  -  |  11.1.8.1/24  |  -  |  -  |  -  |  -  |
| Vlan1109 |  Tenant_A  |  -  |  11.1.9.1/24  |  -  |  -  |  -  |  -  |
| Vlan1110 |  Tenant_A  |  -  |  11.1.10.1/24  |  -  |  -  |  -  |  -  |
| Vlan1201 |  Tenant_B  |  -  |  11.2.1.1/24  |  -  |  -  |  -  |  -  |
| Vlan1202 |  Tenant_B  |  -  |  11.2.2.1/24  |  -  |  -  |  -  |  -  |
| Vlan1203 |  Tenant_B  |  -  |  11.2.3.1/24  |  -  |  -  |  -  |  -  |
| Vlan1204 |  Tenant_B  |  -  |  11.2.4.1/24  |  -  |  -  |  -  |  -  |
| Vlan1205 |  Tenant_B  |  -  |  11.2.5.1/24  |  -  |  -  |  -  |  -  |
| Vlan1206 |  Tenant_B  |  -  |  11.2.6.1/24  |  -  |  -  |  -  |  -  |
| Vlan1207 |  Tenant_B  |  -  |  11.2.7.1/24  |  -  |  -  |  -  |  -  |
| Vlan1208 |  Tenant_B  |  -  |  11.2.8.1/24  |  -  |  -  |  -  |  -  |
| Vlan1209 |  Tenant_B  |  -  |  11.2.9.1/24  |  -  |  -  |  -  |  -  |
| Vlan1210 |  Tenant_B  |  -  |  11.2.10.1/24  |  -  |  -  |  -  |  -  |
| Vlan3100 |  Tenant_A  |  10.255.251.25/31  |  -  |  -  |  -  |  -  |  -  |
| Vlan3101 |  Tenant_B  |  10.255.251.25/31  |  -  |  -  |  -  |  -  |  -  |
| Vlan4093 |  default  |  10.255.251.25/31  |  -  |  -  |  -  |  -  |  -  |
| Vlan4094 |  default  |  10.255.252.25/31  |  -  |  -  |  -  |  -  |  -  |


### VLAN Interfaces Device Configuration

```eos
!
interface Vlan100
   description Tenant_A_FIREWALL
   no shutdown
   mtu 9000
   vrf Tenant_A
   ip address virtual 11.0.1.1/24
!
interface Vlan200
   description Tenant_B_FIREWALL
   no shutdown
   mtu 9000
   vrf Tenant_B
   ip address virtual 11.0.2.1/24
!
interface Vlan1101
   description Tenant_A_VLAN_1
   no shutdown
   mtu 9000
   vrf Tenant_A
   ip address virtual 11.1.1.1/24
!
interface Vlan1102
   description Tenant_A_VLAN_2
   no shutdown
   mtu 9000
   vrf Tenant_A
   ip address virtual 11.1.2.1/24
!
interface Vlan1103
   description Tenant_A_VLAN_3
   no shutdown
   mtu 9000
   vrf Tenant_A
   ip address virtual 11.1.3.1/24
!
interface Vlan1104
   description Tenant_A_VLAN_4
   no shutdown
   mtu 9000
   vrf Tenant_A
   ip address virtual 11.1.4.1/24
!
interface Vlan1105
   description Tenant_A_VLAN_5
   no shutdown
   mtu 9000
   vrf Tenant_A
   ip address virtual 11.1.5.1/24
!
interface Vlan1106
   description Tenant_A_VLAN_6
   no shutdown
   mtu 9000
   vrf Tenant_A
   ip address virtual 11.1.6.1/24
!
interface Vlan1107
   description Tenant_A_VLAN_7
   no shutdown
   mtu 9000
   vrf Tenant_A
   ip address virtual 11.1.7.1/24
!
interface Vlan1108
   description Tenant_A_VLAN_8
   no shutdown
   mtu 9000
   vrf Tenant_A
   ip address virtual 11.1.8.1/24
!
interface Vlan1109
   description Tenant_A_VLAN_9
   no shutdown
   mtu 9000
   vrf Tenant_A
   ip address virtual 11.1.9.1/24
!
interface Vlan1110
   description Tenant_A_VLAN_10
   no shutdown
   mtu 9000
   vrf Tenant_A
   ip address virtual 11.1.10.1/24
!
interface Vlan1201
   description Tenant_B_VLAN_1
   no shutdown
   mtu 9000
   vrf Tenant_B
   ip address virtual 11.2.1.1/24
!
interface Vlan1202
   description Tenant_B_VLAN_2
   no shutdown
   mtu 9000
   vrf Tenant_B
   ip address virtual 11.2.2.1/24
!
interface Vlan1203
   description Tenant_B_VLAN_3
   no shutdown
   mtu 9000
   vrf Tenant_B
   ip address virtual 11.2.3.1/24
!
interface Vlan1204
   description Tenant_B_VLAN_4
   no shutdown
   mtu 9000
   vrf Tenant_B
   ip address virtual 11.2.4.1/24
!
interface Vlan1205
   description Tenant_B_VLAN_5
   no shutdown
   mtu 9000
   vrf Tenant_B
   ip address virtual 11.2.5.1/24
!
interface Vlan1206
   description Tenant_B_VLAN_6
   no shutdown
   mtu 9000
   vrf Tenant_B
   ip address virtual 11.2.6.1/24
!
interface Vlan1207
   description Tenant_B_VLAN_7
   no shutdown
   mtu 9000
   vrf Tenant_B
   ip address virtual 11.2.7.1/24
!
interface Vlan1208
   description Tenant_B_VLAN_8
   no shutdown
   mtu 9000
   vrf Tenant_B
   ip address virtual 11.2.8.1/24
!
interface Vlan1209
   description Tenant_B_VLAN_9
   no shutdown
   mtu 9000
   vrf Tenant_B
   ip address virtual 11.2.9.1/24
!
interface Vlan1210
   description Tenant_B_VLAN_10
   no shutdown
   mtu 9000
   vrf Tenant_B
   ip address virtual 11.2.10.1/24
!
interface Vlan3100
   description MLAG_PEER_L3_iBGP: vrf Tenant_A
   no shutdown
   mtu 9214
   vrf Tenant_A
   ip address 10.255.251.25/31
!
interface Vlan3101
   description MLAG_PEER_L3_iBGP: vrf Tenant_B
   no shutdown
   mtu 9214
   vrf Tenant_B
   ip address 10.255.251.25/31
!
interface Vlan4093
   description MLAG_PEER_L3_PEERING
   no shutdown
   mtu 9214
   ip address 10.255.251.25/31
!
interface Vlan4094
   description MLAG_PEER
   no shutdown
   mtu 9214
   no autostate
   ip address 10.255.252.25/31
```

## VXLAN Interface

### VXLAN Interface Summary

#### Source Interface: Loopback1

#### UDP port: 4789

#### EVPN MLAG Shared Router MAC : mlag-system-id

#### VLAN to VNI, Flood List and Multicast Group Mappings

| VLAN | VNI | Flood List | Multicast Group |
| ---- | --- | ---------- | --------------- |
| 100 | 10100 | - | - |
| 200 | 10200 | - | - |
| 1101 | 11101 | - | - |
| 1102 | 11102 | - | - |
| 1103 | 11103 | - | - |
| 1104 | 11104 | - | - |
| 1105 | 11105 | - | - |
| 1106 | 11106 | - | - |
| 1107 | 11107 | - | - |
| 1108 | 11108 | - | - |
| 1109 | 11109 | - | - |
| 1110 | 11110 | - | - |
| 1201 | 11201 | - | - |
| 1202 | 11202 | - | - |
| 1203 | 11203 | - | - |
| 1204 | 11204 | - | - |
| 1205 | 11205 | - | - |
| 1206 | 11206 | - | - |
| 1207 | 11207 | - | - |
| 1208 | 11208 | - | - |
| 1209 | 11209 | - | - |
| 1210 | 11210 | - | - |

#### VRF to VNI and Multicast Group Mappings

| VRF | VNI | Multicast Group |
| ---- | --- | --------------- |
| Tenant_A | 101 | - |
| Tenant_B | 102 | - |

### VXLAN Interface Device Configuration

```eos
!
interface Vxlan1
   description GWleaf2-dc2_VTEP
   vxlan source-interface Loopback1
   vxlan virtual-router encapsulation mac-address mlag-system-id
   vxlan udp-port 4789
   vxlan vlan 100 vni 10100
   vxlan vlan 200 vni 10200
   vxlan vlan 1101 vni 11101
   vxlan vlan 1102 vni 11102
   vxlan vlan 1103 vni 11103
   vxlan vlan 1104 vni 11104
   vxlan vlan 1105 vni 11105
   vxlan vlan 1106 vni 11106
   vxlan vlan 1107 vni 11107
   vxlan vlan 1108 vni 11108
   vxlan vlan 1109 vni 11109
   vxlan vlan 1110 vni 11110
   vxlan vlan 1201 vni 11201
   vxlan vlan 1202 vni 11202
   vxlan vlan 1203 vni 11203
   vxlan vlan 1204 vni 11204
   vxlan vlan 1205 vni 11205
   vxlan vlan 1206 vni 11206
   vxlan vlan 1207 vni 11207
   vxlan vlan 1208 vni 11208
   vxlan vlan 1209 vni 11209
   vxlan vlan 1210 vni 11210
   vxlan vrf Tenant_A vni 101
   vxlan vrf Tenant_B vni 102
   vxlan controller-client
   vxlan controller-client import vlan none

```

# Routing
## Service Routing Protocols Model

Multi agent routing protocol model enabled

```eos
!
service routing protocols model multi-agent
```

## Virtual Router MAC Address

### Virtual Router MAC Address Summary

#### Virtual Router MAC Address: 00:1c:73:00:dc:01e

### Virtual Router MAC Address Configuration

```eos
!
ip virtual-router mac-address 00:1c:73:00:dc:01e
```

## IP Routing

### IP Routing Summary

| VRF | Routing Enabled |
| --- | --------------- |
| default | true |
| MGMT | false |
| Tenant_A | true |
| Tenant_B | true |

### IP Routing Device Configuration

```eos
!
ip routing
no ip routing vrf MGMT
ip routing vrf Tenant_A
ip routing vrf Tenant_B
```
## IPv6 Routing

### IPv6 Routing Summary

| VRF | Routing Enabled |
| --- | --------------- |
| default | false |
| MGMT | false |
| Tenant_A | false |
| Tenant_B | false |

## Static Routes

### Static Routes Summary

| VRF | Destination Prefix | Next Hop IP             | Exit interface      | Administrative Distance       | Tag               | Route Name                    | Metric         |
| --- | ------------------ | ----------------------- | ------------------- | ----------------------------- | ----------------- | ----------------------------- | -------------- |
| MGMT  | 10.80.0.0/12 |  172.28.128.1  |  -  |  1  |  -  |  -  |  - |
| MGMT  | 10.95.0.0/16 |  172.28.128.1  |  -  |  1  |  -  |  -  |  - |
| MGMT  | 172.16.0.0/12 |  172.28.128.1  |  -  |  1  |  -  |  -  |  - |

### Static Routes Device Configuration

```eos
!
ip route vrf MGMT 10.80.0.0/12 172.28.128.1
ip route vrf MGMT 10.95.0.0/16 172.28.128.1
ip route vrf MGMT 172.16.0.0/12 172.28.128.1
```

## Router BGP

### Router BGP Summary

| BGP AS | Router ID |
| ------ | --------- |
| 65502|  192.168.253.16 |

| BGP Tuning |
| ---------- |
| update wait-install |
| no bgp default ipv4-unicast |
| distance bgp 20 200 200 |
| graceful-restart restart-time 300 |
| graceful-restart |
| maximum-paths 4 ecmp 4 |

### Router BGP Peer Groups

#### EVPN-DC1-GW

| Settings | Value |
| -------- | ----- |
| Address Family | evpn |
| Remote AS | 65501 |
| Source | Loopback0 |
| Ebgp multihop | 3 |
| Send community | all |

#### EVPN-OVERLAY-PEERS

| Settings | Value |
| -------- | ----- |
| Address Family | evpn |
| Source | Loopback0 |
| BFD | true |
| Ebgp multihop | 3 |
| Send community | all |
| Maximum routes | 0 (no limit) |

#### IPv4-UNDERLAY-PEERS

| Settings | Value |
| -------- | ----- |
| Address Family | ipv4 |
| Send community | all |
| Maximum routes | 12000 |

#### MLAG-IPv4-UNDERLAY-PEER

| Settings | Value |
| -------- | ----- |
| Address Family | ipv4 |
| Remote AS | 65502 |
| Next-hop self | True |
| Send community | all |
| Maximum routes | 12000 |

### BGP Neighbors

| Neighbor | Remote AS | VRF | Send-community | Maximum-routes | Allowas-in | BFD |
| -------- | --------- | --- | -------------- | -------------- | ---------- | --- |
| 10.255.251.24 | Inherited from peer group MLAG-IPv4-UNDERLAY-PEER | default | Inherited from peer group MLAG-IPv4-UNDERLAY-PEER | Inherited from peer group MLAG-IPv4-UNDERLAY-PEER | - | - |
| 172.32.250.52 | 65002 | default | Inherited from peer group IPv4-UNDERLAY-PEERS | Inherited from peer group IPv4-UNDERLAY-PEERS | - | - |
| 172.32.250.54 | 65002 | default | Inherited from peer group IPv4-UNDERLAY-PEERS | Inherited from peer group IPv4-UNDERLAY-PEERS | - | - |
| 192.168.1.0 | 65504 | default | Inherited from peer group IPv4-UNDERLAY-PEERS | Inherited from peer group IPv4-UNDERLAY-PEERS | - | True |
| 192.168.253.13 | - | default | - | - | - | - |
| 192.168.253.14 | - | default | - | - | - | - |
| 192.168.255.3 | 65002 | default | Inherited from peer group EVPN-OVERLAY-PEERS | Inherited from peer group EVPN-OVERLAY-PEERS | - | Inherited from peer group EVPN-OVERLAY-PEERS |
| 192.168.255.4 | 65002 | default | Inherited from peer group EVPN-OVERLAY-PEERS | Inherited from peer group EVPN-OVERLAY-PEERS | - | Inherited from peer group EVPN-OVERLAY-PEERS |
| 10.255.251.24 | Inherited from peer group MLAG-IPv4-UNDERLAY-PEER | Tenant_A | Inherited from peer group MLAG-IPv4-UNDERLAY-PEER | Inherited from peer group MLAG-IPv4-UNDERLAY-PEER | - | - |
| 10.255.251.24 | Inherited from peer group MLAG-IPv4-UNDERLAY-PEER | Tenant_B | Inherited from peer group MLAG-IPv4-UNDERLAY-PEER | Inherited from peer group MLAG-IPv4-UNDERLAY-PEER | - | - |

### Router BGP EVPN Address Family

#### EVPN Peer Groups

| Peer Group | Activate |
| ---------- | -------- |
| DC1_GW | True |
| EVPN-OVERLAY-PEERS | True |

#### EVPN Neighbor Default Encapsulation

| Neighbor Default Encapsulation | Next-hop-self Source Interface |
| ------------------------------ | ------------------------------ |
| vxlan | Loopback0 |

#### EVPN DCI Gateway Summary

| Settings | Value |
| -------- | ----- |
| L3 Gateway Inter-domain | True |

### Router BGP VLAN Aware Bundles

| VLAN Aware Bundle | Route-Distinguisher | Both Route-Target | Import Route Target | Export Route-Target | Redistribute | VLANs |
| ----------------- | ------------------- | ----------------- | ------------------- | ------------------- | ------------ | ----- |
| Tenant_A | 192.168.253.16:101 | 101:101 | remote 101:101 | remote 101:101 | learned | 1101-1110 |
| Tenant_B | 192.168.253.16:102 | 102:102 | remote 102:102 | remote 102:102 | learned | 1201-1210 |

### Router BGP VLANs

| VLAN | Route-Distinguisher | Both Route-Target | Import Route Target | Export Route-Target | Redistribute |
| ---- | ------------------- | ----------------- | ------------------- | ------------------- | ------------ |
| 100 | - | 10100:10100 | - | - | learned<br>no host-route |
| 200 | - | 10200:10200 | - | - | learned<br>no host-route |

### Router BGP VRFs

| VRF | Route-Distinguisher | Redistribute |
| --- | ------------------- | ------------ |
| Tenant_A | 192.168.253.16:101 | connected |
| Tenant_B | 192.168.253.16:102 | connected |

### Router BGP Device Configuration

```eos
!
router bgp 65502
   router-id 192.168.253.16
   update wait-install
   no bgp default ipv4-unicast
   distance bgp 20 200 200
   graceful-restart restart-time 300
   graceful-restart
   maximum-paths 4 ecmp 4
   neighbor EVPN-DC1-GW peer group
   neighbor EVPN-DC1-GW remote-as 65501
   neighbor EVPN-DC1-GW update-source Loopback0
   neighbor EVPN-DC1-GW ebgp-multihop 3
   neighbor EVPN-DC1-GW send-community
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
   neighbor MLAG-IPv4-UNDERLAY-PEER remote-as 65502
   neighbor MLAG-IPv4-UNDERLAY-PEER next-hop-self
   neighbor MLAG-IPv4-UNDERLAY-PEER password 7 vnEaG8gMeQf3d3cN6PktXQ==
   neighbor MLAG-IPv4-UNDERLAY-PEER send-community
   neighbor MLAG-IPv4-UNDERLAY-PEER maximum-routes 12000
   neighbor MLAG-IPv4-UNDERLAY-PEER route-map RM-MLAG-PEER-IN in
   neighbor 10.255.251.24 peer group MLAG-IPv4-UNDERLAY-PEER
   neighbor 10.255.251.24 description GWleaf1-dc2
   neighbor 172.32.250.52 peer group IPv4-UNDERLAY-PEERS
   neighbor 172.32.250.52 remote-as 65002
   neighbor 172.32.250.52 description hs426-dc2_Ethernet1
   neighbor 172.32.250.54 peer group IPv4-UNDERLAY-PEERS
   neighbor 172.32.250.54 remote-as 65002
   neighbor 172.32.250.54 description hs427-dc2_Ethernet2
   neighbor 192.168.1.0 peer group IPv4-UNDERLAY-PEERS
   neighbor 192.168.1.0 remote-as 65504
   neighbor 192.168.1.0 local-as 65505 no-prepend replace-as
   neighbor 192.168.1.0 description hs430
   neighbor 192.168.1.0 bfd
   neighbor 192.168.253.13 peer group DC1_GW
   neighbor 192.168.253.13 description SITE1_GW1
   neighbor 192.168.253.14 peer group DC1_GW
   neighbor 192.168.253.14 description SITE1_GW2
   neighbor 192.168.255.3 peer group EVPN-OVERLAY-PEERS
   neighbor 192.168.255.3 remote-as 65002
   neighbor 192.168.255.3 description hs426-dc2
   neighbor 192.168.255.4 peer group EVPN-OVERLAY-PEERS
   neighbor 192.168.255.4 remote-as 65002
   neighbor 192.168.255.4 description hs427-dc2
   redistribute connected route-map RM-CONN-2-BGP
   !
   vlan 100
      route-target both 10100:10100
      redistribute learned
      no redistribute host-route
   !
   vlan 200
      route-target both 10200:10200
      redistribute learned
      no redistribute host-route
   !
   vlan-aware-bundle Tenant_A
      rd 192.168.253.16:101
      route-target both 101:101
      route-target import evpn domain remote 101:101
      route-target export evpn domain remote 101:101
      redistribute learned
      vlan 1101-1110
   !
   vlan-aware-bundle Tenant_B
      rd 192.168.253.16:102
      route-target both 102:102
      route-target import evpn domain remote 102:102
      route-target export evpn domain remote 102:102
      redistribute learned
      vlan 1201-1210
   !
   address-family evpn
      domain identifier 65001:101
      neighbor DC1_GW activate
      neighbor DC1_GW domain remote
      neighbor EVPN-OVERLAY-PEERS activate
   !
   address-family ipv4
      no neighbor EVPN-OVERLAY-PEERS activate
      neighbor IPv4-UNDERLAY-PEERS activate
      neighbor MLAG-IPv4-UNDERLAY-PEER activate
   !
   vrf Tenant_A
      rd 192.168.253.16:101
      route-target import evpn 101:101
      route-target export evpn 101:101
      router-id 192.168.253.16
      neighbor 10.255.251.24 peer group MLAG-IPv4-UNDERLAY-PEER
      redistribute connected
   !
   vrf Tenant_B
      rd 192.168.253.16:102
      route-target import evpn 102:102
      route-target export evpn 102:102
      router-id 192.168.253.16
      neighbor 10.255.251.24 peer group MLAG-IPv4-UNDERLAY-PEER
      redistribute connected
```

# BFD

## Router BFD

### Router BFD Multihop Summary

| Interval | Minimum RX | Multiplier |
| -------- | ---------- | ---------- |
| 300 | 300 | 3 |

### Router BFD Device Configuration

```eos
!
router bfd
   multihop interval 300 min-rx 300 multiplier 3
```

# Multicast

## IP IGMP Snooping

### IP IGMP Snooping Summary

IGMP snooping is globally enabled.


### IP IGMP Snooping Device Configuration

```eos
```

# Filters

## Prefix-lists

### Prefix-lists Summary

#### PL-LOOPBACKS-EVPN-OVERLAY

| Sequence | Action |
| -------- | ------ |
| 10 | permit 192.168.253.0/24 eq 32 |
| 20 | permit 192.168.254.0/24 eq 32 |

### Prefix-lists Device Configuration

```eos
!
ip prefix-list PL-LOOPBACKS-EVPN-OVERLAY
   seq 10 permit 192.168.253.0/24 eq 32
   seq 20 permit 192.168.254.0/24 eq 32
```

## Route-maps

### Route-maps Summary

#### RM-CONN-2-BGP

| Sequence | Type | Match and/or Set |
| -------- | ---- | ---------------- |
| 10 | permit | match ip address prefix-list PL-LOOPBACKS-EVPN-OVERLAY |

#### RM-MLAG-PEER-IN

| Sequence | Type | Match and/or Set |
| -------- | ---- | ---------------- |
| 10 | permit | set origin incomplete |

### Route-maps Device Configuration

```eos
!
route-map RM-CONN-2-BGP permit 10
   match ip address prefix-list PL-LOOPBACKS-EVPN-OVERLAY
!
route-map RM-MLAG-PEER-IN permit 10
   description Make routes learned over MLAG Peer-link less preferred on spines to ensure optimal routing
   set origin incomplete
```

# ACL

# VRF Instances

## VRF Instances Summary

| VRF Name | IP Routing |
| -------- | ---------- |
| MGMT | disabled |
| Tenant_A | enabled |
| Tenant_B | enabled |

## VRF Instances Device Configuration

```eos
!
vrf instance MGMT
!
vrf instance Tenant_A
!
vrf instance Tenant_B
```

# Virtual Source NAT

## Virtual Source NAT Summary

| Source NAT VRF | Source NAT IP Address |
| -------------- | --------------------- |
| Tenant_A | 11.1.255.16 |
| Tenant_B | 11.2.255.16 |

## Virtual Source NAT Configuration

```eos
!
ip address virtual source-nat vrf Tenant_A address 11.1.255.16
ip address virtual source-nat vrf Tenant_B address 11.2.255.16
```

# Platform

## Platform Summary

### Platform Sand Summary

| Settings | Value |
| -------- | ----- |
| lag.hardware_only | True |

## Platform Configuration

```eos
!
platform sand lag hardware-only
```

# MACsec

## MACsec Summary

License is not installed.


### MACsec Profiles Summary

**Profile MACSEC_DCI:**

Settings:

| Cipher | Rekey-Period | SCI |
| ------ | ------------ | --- |
| aes256-gcm-xpn | - | - |

Keys:

| Key ID | Encrypted (Type 7) Key | Fallback |
| ------ | ---------------------- | -------- |
| 1abc | 1abc | - |

## MACsec Device Configuration

```eos
!
mac security
   !
   profile MACSEC_DCI
      cipher aes256-gcm-xpn
      key 1abc 7 1abc
```

# Quality Of Service

# EOS CLI

```eos
!
management cvx
  no shutdown
  server host poc-avd-cvx
  vrf MGMT
!
directflow
  no shutdown

```
