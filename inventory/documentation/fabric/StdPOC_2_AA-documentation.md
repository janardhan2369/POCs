# StdPOC_2_AA

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
| StdPOC_2_AA | l3leaf | gts478 | 172.28.131.18/20 | 7280R2 | Provisioned | - |
| StdPOC_2_AA | l3leaf | gts479 | 172.28.131.17/20 | 7280R2 | Provisioned | - |
| StdPOC_2_AA | l3leaf | gts480 | 172.28.131.11/20 | 7280R2 | Provisioned | - |
| StdPOC_2_AA | l3leaf | gts481 | 172.28.131.10/20 | 7280R2 | Provisioned | - |
| StdPOC_2_AA | l3leaf | hs447 | 172.28.132.64/20 | 7280R2 | Provisioned | - |
| StdPOC_2_AA | l3leaf | hs448 | 172.28.132.41/20 | 7280R2 | Provisioned | - |
| StdPOC_2_AA | l3leaf | kn254 | 172.28.129.173/20 | 7280R2 | Provisioned | - |
| StdPOC_2_AA | l3leaf | kn255 | 172.28.139.136/20 | 7280R2 | Provisioned | - |
| StdPOC_2_AA | spine | kn261 | 172.28.130.76/20 | default | Provisioned | - |
| StdPOC_2_AA | l3leaf | kn271 | 172.28.128.212/20 | 7280R2 | Provisioned | - |
| StdPOC_2_AA | spine | ph155 | 172.28.130.243/20 | default | Provisioned | - |
| StdPOC_2_AA | spine | ph156 | 172.28.130.244/20 | default | Provisioned | - |
| StdPOC_2_AA | spine | tg257 | 172.28.129.127/20 | default | Provisioned | - |
| StdPOC_2_AA | spine | tg294 | 172.28.129.4/20 | default | Provisioned | - |

> Provision status is based on Ansible inventory declaration and do not represent real status from CloudVision.

### Fabric Switches with inband Management IP

| POD | Type | Node | Management IP | Inband Interface |
| --- | ---- | ---- | ------------- | ---------------- |

## Fabric Topology

| Type | Node | Node Interface | Peer Type | Peer Node | Peer Interface |
| ---- | ---- | -------------- | --------- | ----------| -------------- |
| l3leaf | gts478 | Ethernet49/1 | spine | tg257 | Ethernet3/32/1 |
| l3leaf | gts478 | Ethernet50/1 | spine | tg294 | Ethernet3/32/1 |
| l3leaf | gts478 | Ethernet51/1 | spine | ph155 | Ethernet3/5/1 |
| l3leaf | gts478 | Ethernet52/1 | spine | ph156 | Ethernet3/5/1 |
| l3leaf | gts479 | Ethernet49/1 | spine | tg257 | Ethernet4/31/1 |
| l3leaf | gts479 | Ethernet50/1 | spine | tg294 | Ethernet3/31/1 |
| l3leaf | gts479 | Ethernet51/1 | spine | ph155 | Ethernet3/6/1 |
| l3leaf | gts479 | Ethernet52/1 | spine | ph156 | Ethernet3/6/1 |
| l3leaf | gts480 | Ethernet49/1 | spine | tg257 | Ethernet3/24/1 |
| l3leaf | gts480 | Ethernet50/1 | spine | tg294 | Ethernet3/24/1 |
| l3leaf | gts480 | Ethernet51/1 | spine | ph155 | Ethernet3/13/1 |
| l3leaf | gts480 | Ethernet52/1 | spine | ph156 | Ethernet3/13/1 |
| l3leaf | gts481 | Ethernet49/1 | spine | tg257 | Ethernet4/23/1 |
| l3leaf | gts481 | Ethernet50/1 | spine | tg294 | Ethernet3/23/1 |
| l3leaf | gts481 | Ethernet51/1 | spine | ph155 | Ethernet3/14/1 |
| l3leaf | gts481 | Ethernet52/1 | spine | ph156 | Ethernet3/14/1 |
| l3leaf | hs447 | Ethernet1 | l3leaf | kn254 | Ethernet1 |
| l3leaf | hs447 | Ethernet2 | l3leaf | kn255 | Ethernet1 |
| l3leaf | hs447 | Ethernet49/1 | spine | tg257 | Ethernet4/19/1 |
| l3leaf | hs447 | Ethernet50/1 | spine | tg294 | Ethernet3/19/1 |
| l3leaf | hs447 | Ethernet51/1 | spine | ph155 | Ethernet3/18/1 |
| l3leaf | hs447 | Ethernet52/1 | spine | ph156 | Ethernet3/18/1 |
| l3leaf | hs447 | Ethernet53/1 | mlag_peer | hs448 | Ethernet53/1 |
| l3leaf | hs447 | Ethernet54/1 | mlag_peer | hs448 | Ethernet54/1 |
| l3leaf | hs448 | Ethernet1 | l3leaf | kn254 | Ethernet2 |
| l3leaf | hs448 | Ethernet2 | l3leaf | kn255 | Ethernet2 |
| l3leaf | hs448 | Ethernet49/1 | spine | tg257 | Ethernet3/20/1 |
| l3leaf | hs448 | Ethernet50/1 | spine | tg294 | Ethernet3/20/1 |
| l3leaf | hs448 | Ethernet51/1 | spine | ph155 | Ethernet3/17/1 |
| l3leaf | hs448 | Ethernet52/1 | spine | ph156 | Ethernet3/17/1 |
| l3leaf | kn254 | Ethernet49/1 | spine | kn261 | Ethernet49/1 |
| l3leaf | kn254 | Ethernet50/1 | mlag_peer | kn255 | Ethernet50/1 |
| l3leaf | kn254 | Ethernet51/1 | mlag_peer | kn255 | Ethernet51/1 |
| l3leaf | kn255 | Ethernet49/1 | spine | kn261 | Ethernet50/1 |
| spine | kn261 | Ethernet51/1 | l3leaf | kn271 | Ethernet51/1 |

## Fabric IP Allocation

### Fabric Point-To-Point Links

| Uplink IPv4 Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ---------------- | ------------------- | ------------------ | ------------------ |
| 161.1.0.0/24 | 256 | 54 | 21.1 % |

### Point-To-Point Links Node Allocation

| Node | Node Interface | Node IP Address | Peer Node | Peer Interface | Peer IP Address |
| ---- | -------------- | --------------- | --------- | -------------- | --------------- |
| gts478 | Ethernet49/1 | 161.1.0.1/31 | tg257 | Ethernet3/32/1 | 161.1.0.0/31 |
| gts478 | Ethernet50/1 | 161.1.0.3/31 | tg294 | Ethernet3/32/1 | 161.1.0.2/31 |
| gts478 | Ethernet51/1 | 161.1.0.5/31 | ph155 | Ethernet3/5/1 | 161.1.0.4/31 |
| gts478 | Ethernet52/1 | 161.1.0.7/31 | ph156 | Ethernet3/5/1 | 161.1.0.6/31 |
| gts479 | Ethernet49/1 | 161.1.0.9/31 | tg257 | Ethernet4/31/1 | 161.1.0.8/31 |
| gts479 | Ethernet50/1 | 161.1.0.11/31 | tg294 | Ethernet3/31/1 | 161.1.0.10/31 |
| gts479 | Ethernet51/1 | 161.1.0.13/31 | ph155 | Ethernet3/6/1 | 161.1.0.12/31 |
| gts479 | Ethernet52/1 | 161.1.0.15/31 | ph156 | Ethernet3/6/1 | 161.1.0.14/31 |
| gts480 | Ethernet49/1 | 161.1.0.17/31 | tg257 | Ethernet3/24/1 | 161.1.0.16/31 |
| gts480 | Ethernet50/1 | 161.1.0.19/31 | tg294 | Ethernet3/24/1 | 161.1.0.18/31 |
| gts480 | Ethernet51/1 | 161.1.0.21/31 | ph155 | Ethernet3/13/1 | 161.1.0.20/31 |
| gts480 | Ethernet52/1 | 161.1.0.23/31 | ph156 | Ethernet3/13/1 | 161.1.0.22/31 |
| gts481 | Ethernet49/1 | 161.1.0.25/31 | tg257 | Ethernet4/23/1 | 161.1.0.24/31 |
| gts481 | Ethernet50/1 | 161.1.0.27/31 | tg294 | Ethernet3/23/1 | 161.1.0.26/31 |
| gts481 | Ethernet51/1 | 161.1.0.29/31 | ph155 | Ethernet3/14/1 | 161.1.0.28/31 |
| gts481 | Ethernet52/1 | 161.1.0.31/31 | ph156 | Ethernet3/14/1 | 161.1.0.30/31 |
| hs447 | Ethernet1 | 162.5.1.0/31 | kn254 | Ethernet1 | 162.5.1.1/31 |
| hs447 | Ethernet2 | 162.5.1.2/31 | kn255 | Ethernet1 | 162.5.1.3/31 |
| hs447 | Ethernet49/1 | 161.1.0.33/31 | tg257 | Ethernet4/19/1 | 161.1.0.32/31 |
| hs447 | Ethernet50/1 | 161.1.0.35/31 | tg294 | Ethernet3/19/1 | 161.1.0.34/31 |
| hs447 | Ethernet51/1 | 161.1.0.37/31 | ph155 | Ethernet3/18/1 | 161.1.0.36/31 |
| hs447 | Ethernet52/1 | 161.1.0.39/31 | ph156 | Ethernet3/18/1 | 161.1.0.38/31 |
| hs448 | Ethernet1 | 162.5.2.0/31 | kn254 | Ethernet2 | 162.5.2.1/31 |
| hs448 | Ethernet2 | 162.5.2.2/31 | kn255 | Ethernet2 | 162.5.2.3/31 |
| hs448 | Ethernet49/1 | 161.1.0.41/31 | tg257 | Ethernet3/20/1 | 161.1.0.40/31 |
| hs448 | Ethernet50/1 | 161.1.0.43/31 | tg294 | Ethernet3/20/1 | 161.1.0.42/31 |
| hs448 | Ethernet51/1 | 161.1.0.45/31 | ph155 | Ethernet3/17/1 | 161.1.0.44/31 |
| hs448 | Ethernet52/1 | 161.1.0.47/31 | ph156 | Ethernet3/17/1 | 161.1.0.46/31 |
| kn254 | Ethernet49/1 | 161.1.0.1/31 | kn261 | Ethernet49/1 | 161.1.0.0/31 |
| kn255 | Ethernet49/1 | 161.1.0.3/31 | kn261 | Ethernet50/1 | 161.1.0.2/31 |
| kn261 | Ethernet51/1 | 161.1.0.4/31 | kn271 | Ethernet51/1 | 161.1.0.5/31 |

### Loopback Interfaces (BGP EVPN Peering)

| Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ------------- | ------------------- | ------------------ | ------------------ |
| 150.3.0.0/24 | 256 | 6 | 2.35 % |
| 150.9.0.0/24 | 256 | 5 | 1.96 % |
| 151.1.0.0/24 | 256 | 1 | 0.4 % |
| 151.10.0.0/24 | 256 | 2 | 0.79 % |

### Loopback0 Interfaces Node Allocation

| POD | Node | Loopback0 |
| --- | ---- | --------- |
| StdPOC_2_AA | gts478 | 150.3.0.1/32 |
| StdPOC_2_AA | gts479 | 150.3.0.2/32 |
| StdPOC_2_AA | gts480 | 150.3.0.3/32 |
| StdPOC_2_AA | gts481 | 150.3.0.4/32 |
| StdPOC_2_AA | hs447 | 150.3.0.9/32 |
| StdPOC_2_AA | hs448 | 150.3.0.10/32 |
| StdPOC_2_AA | kn254 | 151.10.0.10/32 |
| StdPOC_2_AA | kn255 | 151.10.0.11/32 |
| StdPOC_2_AA | kn261 | 150.9.0.1/32 |
| StdPOC_2_AA | kn271 | 151.1.0.11/32 |
| StdPOC_2_AA | ph155 | 150.9.0.3/32 |
| StdPOC_2_AA | ph156 | 150.9.0.4/32 |
| StdPOC_2_AA | tg257 | 150.9.0.1/32 |
| StdPOC_2_AA | tg294 | 150.9.0.2/32 |

### VTEP Loopback VXLAN Tunnel Source Interfaces (VTEPs Only)

| VTEP Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| --------------------- | ------------------- | ------------------ | ------------------ |
| 3.3.3.0/24 | 256 | 0 | 0.0 % |
| 9.9.9.0/24 | 256 | 2 | 0.79 % |
| 10.10.10.0/24 | 256 | 2 | 0.79 % |
| 11.11.11.0/24 | 256 | 1 | 0.4 % |

### VTEP Loopback Node allocation

| POD | Node | Loopback1 |
| --- | ---- | --------- |
| StdPOC_2_AA | hs447 | 9.9.9.9/32 |
| StdPOC_2_AA | hs448 | 9.9.9.9/32 |
| StdPOC_2_AA | kn254 | 10.10.10.10/32 |
| StdPOC_2_AA | kn255 | 10.10.10.10/32 |
| StdPOC_2_AA | kn271 | 11.11.11.11/32 |
