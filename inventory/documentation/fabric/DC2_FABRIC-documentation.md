# DC2_FABRIC

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
| dc2 | l3leaf | cal371-dc2 | 172.28.143.78/20 | 7050SX3 | Provisioned |
| dc2 | l3leaf | cal372-dc2 | 172.28.143.179/20 | 7050SX3 | Provisioned |
| dc2 | l3leaf | cal375-dc2 | 172.28.143.81/20 | 7050SX3 | Provisioned |
| dc2 | GWleaf | GWleaf1-dc2 | 172.28.143.200/20 | DC2_GW' | Provisioned |
| dc2 | GWleaf | GWleaf2-dc2 | 172.28.143.201/20 | DC2_GW' | Provisioned |
| dc2 | spine | hs426-dc2 | 172.28.143.89/20 | default | Provisioned |
| dc2 | spine | hs427-dc2 | 172.28.143.94/20 | default | Provisioned |
| dc2 | l3leaf | hs429-dc2 | 172.28.143.96/20 | 7280R2 | Provisioned |
| dc2 | l3leaf | hs523-dc2 | 172.28.143.47/20 | 7280R2 | Provisioned |

> Provision status is based on Ansible inventory declaration and do not represent real status from CloudVision.

## Fabric Switches with inband Management IP
| POD | Type | Node | Management IP | Inband Interface |
| --- | ---- | ---- | ------------- | ---------------- |

# Fabric Topology

| Type | Node | Node Interface | Peer Type | Peer Node | Peer Interface |
| ---- | ---- | -------------- | --------- | ----------| -------------- |
| l3leaf | cal371-dc2 | Ethernet49/1 | spine | hs426-dc2 | Ethernet49/1 |
| l3leaf | cal371-dc2 | Ethernet50/1 | spine | hs427-dc2 | Ethernet49/1 |
| l3leaf | cal371-dc2 | Ethernet53/1 | mlag_peer | cal372-dc2 | Ethernet53/1 |
| l3leaf | cal371-dc2 | Ethernet54/1 | mlag_peer | cal372-dc2 | Ethernet54/1 |
| l3leaf | cal372-dc2 | Ethernet49/1 | spine | hs426-dc2 | Ethernet50/1 |
| l3leaf | cal372-dc2 | Ethernet50/1 | spine | hs427-dc2 | Ethernet50/1 |
| l3leaf | cal375-dc2 | Ethernet49/1 | spine | hs426-dc2 | Ethernet53/1 |
| l3leaf | cal375-dc2 | Ethernet50/1 | spine | hs427-dc2 | Ethernet53/1 |
| GWleaf | GWleaf1-dc2 | Ethernet49/1 | spine | hs426-dc2 | Ethernet54/1 |
| GWleaf | GWleaf1-dc2 | Ethernet50/1 | spine | hs427-dc2 | Ethernet54/1 |
| GWleaf | GWleaf1-dc2 | Ethernet53/1 | mlag_peer | GWleaf2-dc2 | Ethernet53/1 |
| GWleaf | GWleaf1-dc2 | Ethernet54/1 | mlag_peer | GWleaf2-dc2 | Ethernet54/1 |
| GWleaf | GWleaf2-dc2 | Ethernet49/1 | spine | hs426-dc2 | Ethernet55/1 |
| GWleaf | GWleaf2-dc2 | Ethernet50/1 | spine | hs427-dc2 | Ethernet55/1 |
| spine | hs426-dc2 | Ethernet51/1 | l3leaf | hs429-dc2 | Ethernet49/1 |
| spine | hs426-dc2 | Ethernet52/1 | l3leaf | hs523-dc2 | Ethernet49/1 |
| spine | hs427-dc2 | Ethernet51/1 | l3leaf | hs429-dc2 | Ethernet50/1 |
| spine | hs427-dc2 | Ethernet52/1 | l3leaf | hs523-dc2 | Ethernet50/1 |

# Fabric IP Allocation

## Fabric Point-To-Point Links

| Uplink IPv4 Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ---------------- | ------------------- | ------------------ | ------------------ |
| 172.32.250.0/24 | 256 | 8 | 3.13 % |
| 172.32.255.0/24 | 256 | 20 | 7.82 % |

## Point-To-Point Links Node Allocation

| Node | Node Interface | Node IP Address | Peer Node | Peer Interface | Peer IP Address |
| ---- | -------------- | --------------- | --------- | -------------- | --------------- |
| cal371-dc2 | Ethernet49/1 | 172.32.255.1/31 | hs426-dc2 | Ethernet49/1 | 172.32.255.0/31 |
| cal371-dc2 | Ethernet50/1 | 172.32.255.3/31 | hs427-dc2 | Ethernet49/1 | 172.32.255.2/31 |
| cal372-dc2 | Ethernet49/1 | 172.32.255.5/31 | hs426-dc2 | Ethernet50/1 | 172.32.255.4/31 |
| cal372-dc2 | Ethernet50/1 | 172.32.255.7/31 | hs427-dc2 | Ethernet50/1 | 172.32.255.6/31 |
| cal375-dc2 | Ethernet49/1 | 172.32.255.17/31 | hs426-dc2 | Ethernet53/1 | 172.32.255.16/31 |
| cal375-dc2 | Ethernet50/1 | 172.32.255.19/31 | hs427-dc2 | Ethernet53/1 | 172.32.255.18/31 |
| GWleaf1-dc2 | Ethernet49/1 | 172.32.250.21/31 | hs426-dc2 | Ethernet54/1 | 172.32.250.20/31 |
| GWleaf1-dc2 | Ethernet50/1 | 172.32.250.23/31 | hs427-dc2 | Ethernet54/1 | 172.32.250.22/31 |
| GWleaf2-dc2 | Ethernet49/1 | 172.32.250.25/31 | hs426-dc2 | Ethernet55/1 | 172.32.250.24/31 |
| GWleaf2-dc2 | Ethernet50/1 | 172.32.250.27/31 | hs427-dc2 | Ethernet55/1 | 172.32.250.26/31 |
| hs426-dc2 | Ethernet51/1 | 172.32.255.8/31 | hs429-dc2 | Ethernet49/1 | 172.32.255.9/31 |
| hs426-dc2 | Ethernet52/1 | 172.32.255.12/31 | hs523-dc2 | Ethernet49/1 | 172.32.255.13/31 |
| hs427-dc2 | Ethernet51/1 | 172.32.255.10/31 | hs429-dc2 | Ethernet50/1 | 172.32.255.11/31 |
| hs427-dc2 | Ethernet52/1 | 172.32.255.14/31 | hs523-dc2 | Ethernet50/1 | 172.32.255.15/31 |

## Loopback Interfaces (BGP EVPN Peering)

| Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ------------- | ------------------- | ------------------ | ------------------ |
| 192.168.251.0/24 | 256 | 7 | 2.74 % |
| 192.168.253.0/24 | 256 | 2 | 0.79 % |

## Loopback0 Interfaces Node Allocation

| POD | Node | Loopback0 |
| --- | ---- | --------- |
| dc2 | cal371-dc2 | 192.168.251.3/32 |
| dc2 | cal372-dc2 | 192.168.251.4/32 |
| dc2 | cal375-dc2 | 192.168.251.7/32 |
| dc2 | GWleaf1-dc2 | 192.168.253.8/32 |
| dc2 | GWleaf2-dc2 | 192.168.253.9/32 |
| dc2 | hs426-dc2 | 192.168.251.1/32 |
| dc2 | hs427-dc2 | 192.168.251.2/32 |
| dc2 | hs429-dc2 | 192.168.251.5/32 |
| dc2 | hs523-dc2 | 192.168.251.6/32 |

## VTEP Loopback VXLAN Tunnel Source Interfaces (VTEPs Only)

| VTEP Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| --------------------- | ------------------- | ------------------ | ------------------ |
| 192.168.252.0/24 | 256 | 5 | 1.96 % |
| 192.168.254.0/24 | 256 | 2 | 0.79 % |

## VTEP Loopback Node allocation

| POD | Node | Loopback1 |
| --- | ---- | --------- |
| dc2 | cal371-dc2 | 192.168.252.3/32 |
| dc2 | cal372-dc2 | 192.168.252.3/32 |
| dc2 | cal375-dc2 | 192.168.252.7/32 |
| dc2 | GWleaf1-dc2 | 192.168.254.8/32 |
| dc2 | GWleaf2-dc2 | 192.168.254.8/32 |
| dc2 | hs429-dc2 | 192.168.252.5/32 |
| dc2 | hs523-dc2 | 192.168.252.6/32 |
