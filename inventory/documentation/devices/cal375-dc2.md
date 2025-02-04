# cal375-dc2
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
- [Aliases](#aliases)
- [Monitoring](#monitoring)
  - [TerminAttr Daemon](#terminattr-daemon)
  - [SFlow](#sflow)
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
  - [Ethernet Interfaces](#ethernet-interfaces)
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
- [Quality Of Service](#quality-of-service)
- [EOS CLI](#eos-cli)

# Management

## Management Interfaces

### Management Interfaces Summary

#### IPv4

| Management Interface | description | Type | VRF | IP Address | Gateway |
| -------------------- | ----------- | ---- | --- | ---------- | ------- |
| Management1 | oob_management | oob | MGMT | 172.28.143.81/20 | 172.28.128.1 |

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
   ip address 172.28.143.81/20
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

# Spanning Tree

## Spanning Tree Summary

STP mode: **mstp**

### MSTP Instance and Priority

| Instance(s) | Priority |
| -------- | -------- |
| 0 | 16384 |

## Spanning Tree Device Configuration

```eos
!
spanning-tree mode mstp
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

## VLANs Device Configuration

```eos
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
```

# Interfaces

## Ethernet Interfaces

### Ethernet Interfaces Summary

#### L2

| Interface | Description | Mode | VLANs | Native VLAN | Trunk Group | Channel-Group |
| --------- | ----------- | ---- | ----- | ----------- | ----------- | ------------- |
| Ethernet1 |  HarnessC_Eth5 | trunk | - | - | - | - |

*Inherited from Port-Channel Interface

#### IPv4

| Interface | Description | Type | Channel Group | IP Address | VRF |  MTU | Shutdown | ACL In | ACL Out |
| --------- | ----------- | -----| ------------- | ---------- | ----| ---- | -------- | ------ | ------- |
| Ethernet49/1 | P2P_LINK_TO_HS426-DC2_Ethernet53/1 | routed | - | 172.32.255.17/31 | default | 9214 | false | - | - |
| Ethernet50/1 | P2P_LINK_TO_HS427-DC2_Ethernet53/1 | routed | - | 172.32.255.19/31 | default | 9214 | false | - | - |

### Ethernet Interfaces Device Configuration

```eos
!
interface Ethernet1
   description HarnessC_Eth5
   no shutdown
   speed forced 10000full
   switchport
   switchport mode trunk
!
interface Ethernet49/1
   description P2P_LINK_TO_HS426-DC2_Ethernet53/1
   no shutdown
   mtu 9214
   no switchport
   ip address 172.32.255.17/31
!
interface Ethernet50/1
   description P2P_LINK_TO_HS427-DC2_Ethernet53/1
   no shutdown
   mtu 9214
   no switchport
   ip address 172.32.255.19/31
```

## Loopback Interfaces

### Loopback Interfaces Summary

#### IPv4

| Interface | Description | VRF | IP Address |
| --------- | ----------- | --- | ---------- |
| Loopback0 | EVPN_Overlay_Peering | default | 192.168.251.7/32 |
| Loopback1 | VTEP_VXLAN_Tunnel_Source | default | 192.168.252.7/32 |
| Loopback101 | Tenant_A_VTEP_DIAGNOSTICS | Tenant_A | 11.1.255.7/32 |
| Loopback102 | Tenant_B_VTEP_DIAGNOSTICS | Tenant_B | 11.2.255.7/32 |

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
   ip address 192.168.251.7/32
!
interface Loopback1
   description VTEP_VXLAN_Tunnel_Source
   no shutdown
   ip address 192.168.252.7/32
!
interface Loopback101
   description Tenant_A_VTEP_DIAGNOSTICS
   no shutdown
   vrf Tenant_A
   ip address 11.1.255.7/32
!
interface Loopback102
   description Tenant_B_VTEP_DIAGNOSTICS
   no shutdown
   vrf Tenant_B
   ip address 11.2.255.7/32
```

## VLAN Interfaces

### VLAN Interfaces Summary

| Interface | Description | VRF |  MTU | Shutdown |
| --------- | ----------- | --- | ---- | -------- |
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

#### IPv4

| Interface | VRF | IP Address | IP Address Virtual | IP Router Virtual Address | VRRP | ACL In | ACL Out |
| --------- | --- | ---------- | ------------------ | ------------------------- | ---- | ------ | ------- |
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


### VLAN Interfaces Device Configuration

```eos
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
```

## VXLAN Interface

### VXLAN Interface Summary

#### Source Interface: Loopback1

#### UDP port: 4789

#### VLAN to VNI, Flood List and Multicast Group Mappings

| VLAN | VNI | Flood List | Multicast Group |
| ---- | --- | ---------- | --------------- |
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
   description cal375-dc2_VTEP
   vxlan source-interface Loopback1
   vxlan udp-port 4789
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

#### Virtual Router MAC Address: 00:1c:73:00:dc:01

### Virtual Router MAC Address Configuration

```eos
!
ip virtual-router mac-address 00:1c:73:00:dc:01
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
| 65303|  192.168.251.7 |

| BGP Tuning |
| ---------- |
| no bgp default ipv4-unicast |
| distance bgp 20 200 200 |
| graceful-restart restart-time 300 |
| graceful-restart |
| update wait-install |
| maximum-paths 4 ecmp 4 |

### Router BGP Peer Groups

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

### BGP Neighbors

| Neighbor | Remote AS | VRF | Send-community | Maximum-routes | Allowas-in | BFD |
| -------- | --------- | --- | -------------- | -------------- | ---------- | --- |
| 172.32.255.16 | 65201 | default | Inherited from peer group IPv4-UNDERLAY-PEERS | Inherited from peer group IPv4-UNDERLAY-PEERS | - | - |
| 172.32.255.18 | 65201 | default | Inherited from peer group IPv4-UNDERLAY-PEERS | Inherited from peer group IPv4-UNDERLAY-PEERS | - | - |
| 192.168.251.1 | 65201 | default | Inherited from peer group EVPN-OVERLAY-PEERS | Inherited from peer group EVPN-OVERLAY-PEERS | - | Inherited from peer group EVPN-OVERLAY-PEERS |
| 192.168.251.2 | 65201 | default | Inherited from peer group EVPN-OVERLAY-PEERS | Inherited from peer group EVPN-OVERLAY-PEERS | - | Inherited from peer group EVPN-OVERLAY-PEERS |

### Router BGP EVPN Address Family

#### EVPN Peer Groups

| Peer Group | Activate |
| ---------- | -------- |
| EVPN-OVERLAY-PEERS | True |

### Router BGP VLAN Aware Bundles

| VLAN Aware Bundle | Route-Distinguisher | Both Route-Target | Import Route Target | Export Route-Target | Redistribute | VLANs |
| ----------------- | ------------------- | ----------------- | ------------------- | ------------------- | ------------ | ----- |
| Tenant_A | 192.168.251.7:101 | 101:101 | - | - | learned | 1101-1110 |
| Tenant_B | 192.168.251.7:102 | 102:102 | - | - | learned | 1201-1210 |

### Router BGP VRFs

| VRF | Route-Distinguisher | Redistribute |
| --- | ------------------- | ------------ |
| Tenant_A | 192.168.251.7:101 | connected |
| Tenant_B | 192.168.251.7:102 | connected |

### Router BGP Device Configuration

```eos
!
router bgp 65303
   router-id 192.168.251.7
   no bgp default ipv4-unicast
   distance bgp 20 200 200
   graceful-restart restart-time 300
   graceful-restart
   update wait-install
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
   neighbor 172.32.255.16 peer group IPv4-UNDERLAY-PEERS
   neighbor 172.32.255.16 remote-as 65201
   neighbor 172.32.255.16 description hs426-dc2_Ethernet53/1
   neighbor 172.32.255.18 peer group IPv4-UNDERLAY-PEERS
   neighbor 172.32.255.18 remote-as 65201
   neighbor 172.32.255.18 description hs427-dc2_Ethernet53/1
   neighbor 192.168.251.1 peer group EVPN-OVERLAY-PEERS
   neighbor 192.168.251.1 remote-as 65201
   neighbor 192.168.251.1 description hs426-dc2
   neighbor 192.168.251.2 peer group EVPN-OVERLAY-PEERS
   neighbor 192.168.251.2 remote-as 65201
   neighbor 192.168.251.2 description hs427-dc2
   redistribute connected route-map RM-CONN-2-BGP
   !
   vlan-aware-bundle Tenant_A
      rd 192.168.251.7:101
      route-target both 101:101
      redistribute learned
      vlan 1101-1110
   !
   vlan-aware-bundle Tenant_B
      rd 192.168.251.7:102
      route-target both 102:102
      redistribute learned
      vlan 1201-1210
   !
   address-family evpn
      neighbor EVPN-OVERLAY-PEERS activate
   !
   address-family ipv4
      no neighbor EVPN-OVERLAY-PEERS activate
      neighbor IPv4-UNDERLAY-PEERS activate
   !
   vrf Tenant_A
      rd 192.168.251.7:101
      route-target import evpn 101:101
      route-target export evpn 101:101
      router-id 192.168.251.7
      redistribute connected
   !
   vrf Tenant_B
      rd 192.168.251.7:102
      route-target import evpn 102:102
      route-target export evpn 102:102
      router-id 192.168.251.7
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
| 10 | permit 192.168.251.0/24 eq 32 |
| 20 | permit 192.168.252.0/24 eq 32 |

### Prefix-lists Device Configuration

```eos
!
ip prefix-list PL-LOOPBACKS-EVPN-OVERLAY
   seq 10 permit 192.168.251.0/24 eq 32
   seq 20 permit 192.168.252.0/24 eq 32
```

## Route-maps

### Route-maps Summary

#### RM-CONN-2-BGP

| Sequence | Type | Match and/or Set |
| -------- | ---- | ---------------- |
| 10 | permit | match ip address prefix-list PL-LOOPBACKS-EVPN-OVERLAY |

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
| Tenant_A | 11.1.255.7 |
| Tenant_B | 11.2.255.7 |

## Virtual Source NAT Configuration

```eos
!
ip address virtual source-nat vrf Tenant_A address 11.1.255.7
ip address virtual source-nat vrf Tenant_B address 11.2.255.7
```

# Quality Of Service

# EOS CLI

```eos
!
hardware speed-group 1 serdes 10g

```
