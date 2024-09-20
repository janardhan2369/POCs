# DC1_FABRIC

# Table of Contents

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

# Fabric Switches and Management IP

| POD | Type | Node | Management IP | Platform | Provisioned in CloudVision |
| --- | ---- | ---- | ------------- | -------- | -------------------------- |
| DC1_FABRIC | l3leaf | cal371 | 172.28.133.78/20 | 7050SX3 | Provisioned |
| DC1_FABRIC | l3leaf | cal372 | 172.28.131.179/20 | 7050SX3 | Provisioned |
| DC1_FABRIC | l3leaf | cal375 | 172.28.133.81/20 | 7050SX3 | Provisioned |
| DC1_FABRIC | spine | hs426 | 172.28.132.89/20 | default | Provisioned |
| DC1_FABRIC | spine | hs427 | 172.28.132.94/20 | default | Provisioned |
| DC1_FABRIC | l3leaf | hs429 | 172.28.132.96/20 | Sand-MSS | Provisioned |
| DC1_FABRIC | l3leaf | hs523 | 172.28.131.47/20 | Sand-MSS | Provisioned |

> Provision status is based on Ansible inventory declaration and do not represent real status from CloudVision.

## Fabric Switches with inband Management IP
| POD | Type | Node | Management IP | Inband Interface |
| --- | ---- | ---- | ------------- | ---------------- |

# Fabric Topology

| Type | Node | Node Interface | Peer Type | Peer Node | Peer Interface |
| ---- | ---- | -------------- | --------- | ----------| -------------- |
| l3leaf | cal371 | Ethernet49/1 | spine | hs426 | Ethernet49/1 |
| l3leaf | cal371 | Ethernet50/1 | spine | hs427 | Ethernet49/1 |
| l3leaf | cal372 | Ethernet49/1 | spine | hs426 | Ethernet50/1 |
| l3leaf | cal372 | Ethernet50/1 | spine | hs427 | Ethernet50/1 |
| l3leaf | cal375 | Ethernet49/1 | spine | hs426 | Ethernet53/1 |
| l3leaf | cal375 | Ethernet50/1 | spine | hs427 | Ethernet53/1 |
| spine | hs426 | Ethernet51/1 | l3leaf | hs429 | Ethernet49/1 |
| spine | hs426 | Ethernet52/1 | l3leaf | hs523 | Ethernet49/1 |
| spine | hs427 | Ethernet51/1 | l3leaf | hs429 | Ethernet50/1 |
| spine | hs427 | Ethernet52/1 | l3leaf | hs523 | Ethernet50/1 |

# Fabric IP Allocation

## Fabric Point-To-Point Links

| Uplink IPv4 Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ---------------- | ------------------- | ------------------ | ------------------ |
| 172.31.255.0/24 | 256 | 20 | 7.82 % |

## Point-To-Point Links Node Allocation

| Node | Node Interface | Node IP Address | Peer Node | Peer Interface | Peer IP Address |
| ---- | -------------- | --------------- | --------- | -------------- | --------------- |
| cal371 | Ethernet49/1 | 172.31.255.1/31 | hs426 | Ethernet49/1 | 172.31.255.0/31 |
| cal371 | Ethernet50/1 | 172.31.255.3/31 | hs427 | Ethernet49/1 | 172.31.255.2/31 |
| cal372 | Ethernet49/1 | 172.31.255.5/31 | hs426 | Ethernet50/1 | 172.31.255.4/31 |
| cal372 | Ethernet50/1 | 172.31.255.7/31 | hs427 | Ethernet50/1 | 172.31.255.6/31 |
| cal375 | Ethernet49/1 | 172.31.255.17/31 | hs426 | Ethernet53/1 | 172.31.255.16/31 |
| cal375 | Ethernet50/1 | 172.31.255.19/31 | hs427 | Ethernet53/1 | 172.31.255.18/31 |
| hs426 | Ethernet51/1 | 172.31.255.8/31 | hs429 | Ethernet49/1 | 172.31.255.9/31 |
| hs426 | Ethernet52/1 | 172.31.255.12/31 | hs523 | Ethernet49/1 | 172.31.255.13/31 |
| hs427 | Ethernet51/1 | 172.31.255.10/31 | hs429 | Ethernet50/1 | 172.31.255.11/31 |
| hs427 | Ethernet52/1 | 172.31.255.14/31 | hs523 | Ethernet50/1 | 172.31.255.15/31 |

## Loopback Interfaces (BGP EVPN Peering)

| Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ------------- | ------------------- | ------------------ | ------------------ |
| 192.168.255.0/24 | 256 | 7 | 2.74 % |

## Loopback0 Interfaces Node Allocation

| POD | Node | Loopback0 |
| --- | ---- | --------- |
| DC1_FABRIC | cal371 | 192.168.255.3/32 |
| DC1_FABRIC | cal372 | 192.168.255.4/32 |
| DC1_FABRIC | cal375 | 192.168.255.7/32 |
| DC1_FABRIC | hs426 | 192.168.255.1/32 |
| DC1_FABRIC | hs427 | 192.168.255.2/32 |
| DC1_FABRIC | hs429 | 192.168.255.5/32 |
| DC1_FABRIC | hs523 | 192.168.255.6/32 |

## VTEP Loopback VXLAN Tunnel Source Interfaces (VTEPs Only)

| VTEP Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| --------------------- | ------------------- | ------------------ | ------------------ |
| 192.168.254.0/24 | 256 | 5 | 1.96 % |

## VTEP Loopback Node allocation

| POD | Node | Loopback1 |
| --- | ---- | --------- |
| DC1_FABRIC | cal371 | 192.168.254.3/32 |
| DC1_FABRIC | cal372 | 192.168.254.4/32 |
| DC1_FABRIC | cal375 | 192.168.254.7/32 |
| DC1_FABRIC | hs429 | 192.168.254.5/32 |
| DC1_FABRIC | hs523 | 192.168.254.6/32 |
