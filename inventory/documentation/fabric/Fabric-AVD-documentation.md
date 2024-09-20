# Fabric-AVD

## Table of Contents

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

## Fabric Switches and Management IP

| POD | Type | Node | Management IP | Platform | Provisioned in CloudVision | Serial Number |
| --- | ---- | ---- | ------------- | -------- | -------------------------- | ------------- |
| Fabric-AVD | l3leaf | btd452 | 172.28.137.60/20 | default | Provisioned | - |
| Fabric-AVD | l3leaf | btd453 | 172.28.137.61/20 | default | Provisioned | - |
| Fabric-AVD | spine | btd555 | 172.28.138.46/20 | default | Provisioned | - |
| Fabric-AVD | spine | btd556 | 172.28.138.47/20 | default | Provisioned | - |
| Fabric-AVD | l3leaf | btd558 | 172.28.138.14/20 | default | Provisioned | - |
| Fabric-AVD | l3leaf | btp351 | 172.28.138.18/20 | default | Provisioned | - |

> Provision status is based on Ansible inventory declaration and do not represent real status from CloudVision.

### Fabric Switches with inband Management IP

| POD | Type | Node | Management IP | Inband Interface |
| --- | ---- | ---- | ------------- | ---------------- |

## Fabric Topology

| Type | Node | Node Interface | Peer Type | Peer Node | Peer Interface |
| ---- | ---- | -------------- | --------- | ----------| -------------- |
| l3leaf | btd452 | Ethernet14/1 | spine | btd555 | Ethernet14/1 |
| l3leaf | btd452 | Ethernet15/1 | spine | btd556 | Ethernet17/1 |
| l3leaf | btd452 | Ethernet16/1 | spine | btd556 | Ethernet17/5 |
| l3leaf | btd452 | Ethernet17/1 | spine | btd556 | Ethernet18/1 |
| l3leaf | btd453 | Ethernet6/1 | mlag_peer | btd558 | Ethernet6/1 |
| l3leaf | btd453 | Ethernet7/1 | mlag_peer | btd558 | Ethernet7/1 |
| l3leaf | btd453 | Ethernet14/1 | spine | btd555 | Ethernet15/5 |
| l3leaf | btd453 | Ethernet15/1 | spine | btd556 | Ethernet21/5 |
| l3leaf | btd453 | Ethernet16/1 | spine | btd556 | Ethernet22/1 |
| l3leaf | btd453 | Ethernet17/1 | spine | btd556 | Ethernet22/5 |
| spine | btd555 | Ethernet14/5 | l3leaf | btp351 | Ethernet14/1 |
| spine | btd555 | Ethernet15/1 | l3leaf | btd558 | Ethernet14/1 |
| spine | btd556 | Ethernet18/5 | l3leaf | btp351 | Ethernet15/1 |
| spine | btd556 | Ethernet19/1 | l3leaf | btp351 | Ethernet16/1 |
| spine | btd556 | Ethernet19/5 | l3leaf | btp351 | Ethernet17/1 |
| spine | btd556 | Ethernet20/1 | l3leaf | btd558 | Ethernet15/1 |
| spine | btd556 | Ethernet20/5 | l3leaf | btd558 | Ethernet17/1 |
| spine | btd556 | Ethernet21/1 | l3leaf | btd558 | Ethernet16/1 |

## Fabric IP Allocation

### Fabric Point-To-Point Links

| Uplink IPv4 Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ---------------- | ------------------- | ------------------ | ------------------ |
| 100.64.102.0/24 | 256 | 32 | 12.5 % |

### Point-To-Point Links Node Allocation

| Node | Node Interface | Node IP Address | Peer Node | Peer Interface | Peer IP Address |
| ---- | -------------- | --------------- | --------- | -------------- | --------------- |
| btd452 | Ethernet14/1 | 100.64.102.17/31 | btd555 | Ethernet14/1 | 100.64.102.16/31 |
| btd452 | Ethernet15/1 | 100.64.102.19/31 | btd556 | Ethernet17/1 | 100.64.102.18/31 |
| btd452 | Ethernet16/1 | 100.64.102.21/31 | btd556 | Ethernet17/5 | 100.64.102.20/31 |
| btd452 | Ethernet17/1 | 100.64.102.23/31 | btd556 | Ethernet18/1 | 100.64.102.22/31 |
| btd453 | Ethernet14/1 | 100.64.102.9/31 | btd555 | Ethernet15/5 | 100.64.102.8/31 |
| btd453 | Ethernet15/1 | 100.64.102.11/31 | btd556 | Ethernet21/5 | 100.64.102.10/31 |
| btd453 | Ethernet16/1 | 100.64.102.13/31 | btd556 | Ethernet22/1 | 100.64.102.12/31 |
| btd453 | Ethernet17/1 | 100.64.102.15/31 | btd556 | Ethernet22/5 | 100.64.102.14/31 |
| btd555 | Ethernet14/5 | 100.64.102.24/31 | btp351 | Ethernet14/1 | 100.64.102.25/31 |
| btd555 | Ethernet15/1 | 100.64.102.0/31 | btd558 | Ethernet14/1 | 100.64.102.1/31 |
| btd556 | Ethernet18/5 | 100.64.102.26/31 | btp351 | Ethernet15/1 | 100.64.102.27/31 |
| btd556 | Ethernet19/1 | 100.64.102.28/31 | btp351 | Ethernet16/1 | 100.64.102.29/31 |
| btd556 | Ethernet19/5 | 100.64.102.30/31 | btp351 | Ethernet17/1 | 100.64.102.31/31 |
| btd556 | Ethernet20/1 | 100.64.102.2/31 | btd558 | Ethernet15/1 | 100.64.102.3/31 |
| btd556 | Ethernet20/5 | 100.64.102.6/31 | btd558 | Ethernet17/1 | 100.64.102.7/31 |
| btd556 | Ethernet21/1 | 100.64.102.4/31 | btd558 | Ethernet16/1 | 100.64.102.5/31 |

### Loopback Interfaces (BGP EVPN Peering)

| Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ------------- | ------------------- | ------------------ | ------------------ |
| 1.0.0.0/24 | 256 | 2 | 0.79 % |
| 100.64.200.0/24 | 256 | 4 | 1.57 % |

### Loopback0 Interfaces Node Allocation

| POD | Node | Loopback0 |
| --- | ---- | --------- |
| Fabric-AVD | btd452 | 100.64.200.5/32 |
| Fabric-AVD | btd453 | 100.64.200.4/32 |
| Fabric-AVD | btd555 | 1.0.0.1/32 |
| Fabric-AVD | btd556 | 1.0.0.2/32 |
| Fabric-AVD | btd558 | 100.64.200.3/32 |
| Fabric-AVD | btp351 | 100.64.200.6/32 |

### VTEP Loopback VXLAN Tunnel Source Interfaces (VTEPs Only)

| VTEP Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| --------------------- | ------------------- | ------------------ | ------------------ |

### VTEP Loopback Node allocation

| POD | Node | Loopback1 |
| --- | ---- | --------- |
| Fabric-AVD | btd453 | 2.0.0.1/32 |
| Fabric-AVD | btd558 | 2.0.0.1/32 |
