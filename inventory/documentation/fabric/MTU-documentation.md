# MTU

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
| MTU | l3leaf | dc1p1_leaf1a_cal418 | 172.28.133.17/20 | 7050SX3 | Provisioned | - |
| MTU | l3leaf | dc1p1_leaf1b_cal419 | 172.28.133.18/20 | 7050SX3 | Provisioned | - |
| MTU | l3leaf | dc1p1_leaf2a_cal421 | 172.28.134.154/20 | 7050SX3 | Provisioned | - |
| MTU | l3leaf | dc1p1_leaf2b_cal422 | 172.28.134.150/20 | 7050SX3 | Provisioned | - |
| MTU | l3leaf | dc1p1_leaf3a_smd554 | 172.28.137.27/20 | 7280R3 | Provisioned | - |
| MTU | l3leaf | dc1p1_leaf3b_smd555 | 172.28.137.28/20 | 7280R3 | Provisioned | - |
| MTU | l3leaf | dc1p1_sleaf_smv541 | 172.28.135.48/20 | 7280R3 | Provisioned | - |
| MTU | spine | dc1p1_spine1_glf437 | 172.28.135.3/20 | default | Provisioned | - |
| MTU | spine | dc1p1_spine2_btp454 | 172.28.137.55/20 | default | Provisioned | - |
| MTU | spine | dc1p1_spine3_btd452 | 172.28.137.60/20 | default | Provisioned | - |
| MTU | l3leaf | dc1p2_leaf1_mrv453 | 172.28.136.152/20 | 7050SX3 | Provisioned | - |
| MTU | l3leaf | dc1p2_leaf2_gt272 | 172.28.134.222/20 | 7280R2 | Provisioned | - |
| MTU | spine | dc1p2_spine1_ghs253 | 172.28.128.68/20 | default | Provisioned | - |
| MTU | spine | dc1p2_spine2_ghs278 | 172.28.133.167/20 | default | Provisioned | - |
| MTU | spine | dc1p2_spine3_ghs281 | 172.28.133.179/20 | default | Provisioned | - |
| MTU | l3leaf | dc2p1_leaf1a_mrv305 | 172.28.136.227/20 | 7050SX3 | Provisioned | - |
| MTU | l3leaf | dc2p1_leaf1b_mrv306 | 172.28.136.228/20 | 7050SX3 | Provisioned | - |
| MTU | l3leaf | dc2p1_sleaf_gt407 | 172.28.136.157/20 | 7280R2 | Provisioned | - |
| MTU | spine | dc2p1_spine1_ghs282 | 172.28.131.98/20 | default | Provisioned | - |
| MTU | spine | dc2p1_spine2_ghs283 | 172.28.131.100/20 | default | Provisioned | - |
| MTU | spine | dc2p1_spine3_ghs284 | 172.28.131.104/20 | default | Provisioned | - |
| MTU | l2leaf | oob_leaf1_npt325 | 172.28.137.85/20 | default | Provisioned | - |
| MTU | l2leaf | oob_spine1_pm362 | 172.28.135.233/20 | default | Provisioned | - |
| MTU | l2leaf | oob_spine2_pm363 | 172.28.135.234/20 | default | Provisioned | - |

> Provision status is based on Ansible inventory declaration and do not represent real status from CloudVision.

### Fabric Switches with inband Management IP

| POD | Type | Node | Management IP | Inband Interface |
| --- | ---- | ---- | ------------- | ---------------- |

## Fabric Topology

| Type | Node | Node Interface | Peer Type | Peer Node | Peer Interface |
| ---- | ---- | -------------- | --------- | ----------| -------------- |
| l3leaf | dc1p1_leaf1a_cal418 | Ethernet49/1 | spine | dc1p1_spine1_glf437 | Ethernet3/1/1 |
| l3leaf | dc1p1_leaf1a_cal418 | Ethernet50/1 | spine | dc1p1_spine2_btp454 | Ethernet3/1 |
| l3leaf | dc1p1_leaf1a_cal418 | Ethernet51/1 | spine | dc1p1_spine3_btd452 | Ethernet3/1 |
| l3leaf | dc1p1_leaf1a_cal418 | Ethernet53/1 | mlag_peer | dc1p1_leaf1b_cal419 | Ethernet53/1 |
| l3leaf | dc1p1_leaf1a_cal418 | Ethernet54/1 | mlag_peer | dc1p1_leaf1b_cal419 | Ethernet54/1 |
| l3leaf | dc1p1_leaf1b_cal419 | Ethernet49/1 | spine | dc1p1_spine1_glf437 | Ethernet3/2/1 |
| l3leaf | dc1p1_leaf1b_cal419 | Ethernet50/1 | spine | dc1p1_spine2_btp454 | Ethernet4/1 |
| l3leaf | dc1p1_leaf1b_cal419 | Ethernet51/1 | spine | dc1p1_spine3_btd452 | Ethernet4/1 |
| l3leaf | dc1p1_leaf2a_cal421 | Ethernet50/1 | spine | dc1p1_spine1_glf437 | Ethernet3/3/1 |
| l3leaf | dc1p1_leaf2a_cal421 | Ethernet51/1 | spine | dc1p1_spine2_btp454 | Ethernet5/1 |
| l3leaf | dc1p1_leaf2a_cal421 | Ethernet52/1 | spine | dc1p1_spine3_btd452 | Ethernet5/1 |
| l3leaf | dc1p1_leaf2a_cal421 | Ethernet53/1 | mlag_peer | dc1p1_leaf2b_cal422 | Ethernet53/1 |
| l3leaf | dc1p1_leaf2a_cal421 | Ethernet54/1 | mlag_peer | dc1p1_leaf2b_cal422 | Ethernet54/1 |
| l3leaf | dc1p1_leaf2b_cal422 | Ethernet49/1 | spine | dc1p1_spine1_glf437 | Ethernet3/4/1 |
| l3leaf | dc1p1_leaf2b_cal422 | Ethernet50/1 | spine | dc1p1_spine2_btp454 | Ethernet6/1 |
| l3leaf | dc1p1_leaf2b_cal422 | Ethernet51/1 | spine | dc1p1_spine3_btd452 | Ethernet6/1 |
| l3leaf | dc1p1_leaf3a_smd554 | Ethernet1/1 | mlag_peer | dc1p1_leaf3b_smd555 | Ethernet1/1 |
| l3leaf | dc1p1_leaf3a_smd554 | Ethernet2/1 | mlag_peer | dc1p1_leaf3b_smd555 | Ethernet2/1 |
| l3leaf | dc1p1_leaf3a_smd554 | Ethernet3/1 | mlag_peer | dc1p1_leaf3b_smd555 | Ethernet3/1 |
| l3leaf | dc1p1_leaf3a_smd554 | Ethernet4/1 | mlag_peer | dc1p1_leaf3b_smd555 | Ethernet4/1 |
| l3leaf | dc1p1_leaf3a_smd554 | Ethernet33/1 | spine | dc1p1_spine1_glf437 | Ethernet4/1/1 |
| l3leaf | dc1p1_leaf3a_smd554 | Ethernet34/1 | spine | dc1p1_spine2_btp454 | Ethernet31/1 |
| l3leaf | dc1p1_leaf3a_smd554 | Ethernet35/1 | spine | dc1p1_spine3_btd452 | Ethernet31/1 |
| l3leaf | dc1p1_leaf3b_smd555 | Ethernet33/1 | spine | dc1p1_spine1_glf437 | Ethernet4/2/1 |
| l3leaf | dc1p1_leaf3b_smd555 | Ethernet34/1 | spine | dc1p1_spine2_btp454 | Ethernet32/1 |
| l3leaf | dc1p1_leaf3b_smd555 | Ethernet35/1 | spine | dc1p1_spine3_btd452 | Ethernet32/1 |
| l3leaf | dc1p1_sleaf_smv541 | Ethernet1/1 | spine | dc1p1_spine1_glf437 | Ethernet3/5/1 |
| l3leaf | dc1p1_sleaf_smv541 | Ethernet2/1 | spine | dc1p1_spine2_btp454 | Ethernet7/1 |
| l3leaf | dc1p1_sleaf_smv541 | Ethernet3/1 | spine | dc1p1_spine3_btd452 | Ethernet7/1 |
| spine | dc1p1_spine1_glf437 | Ethernet2/1/1 | spine | dc1p2_spine1_ghs253 | Ethernet1/1 |
| spine | dc1p1_spine1_glf437 | Ethernet2/2/1 | spine | dc2p1_spine1_ghs282 | Ethernet1/1 |
| spine | dc1p1_spine2_btp454 | Ethernet1/1 | spine | dc1p2_spine2_ghs278 | Ethernet1/1 |
| spine | dc1p1_spine2_btp454 | Ethernet2/1 | spine | dc2p1_spine2_ghs283 | Ethernet1/1 |
| spine | dc1p1_spine3_btd452 | Ethernet1/1 | spine | dc1p2_spine3_ghs281 | Ethernet1/1 |
| spine | dc1p1_spine3_btd452 | Ethernet2/1 | spine | dc2p1_spine3_ghs284 | Ethernet1/1 |
| l3leaf | dc1p2_leaf1_mrv453 | Ethernet49/1 | spine | dc1p2_spine1_ghs253 | Ethernet3/1 |
| l3leaf | dc1p2_leaf1_mrv453 | Ethernet50/1 | spine | dc1p2_spine2_ghs278 | Ethernet3/1 |
| l3leaf | dc1p2_leaf1_mrv453 | Ethernet51/1 | spine | dc1p2_spine3_ghs281 | Ethernet3/1 |
| l3leaf | dc1p2_leaf2_gt272 | Ethernet49/1 | spine | dc1p2_spine1_ghs253 | Ethernet4/1 |
| l3leaf | dc1p2_leaf2_gt272 | Ethernet50/1 | spine | dc1p2_spine2_ghs278 | Ethernet4/1 |
| l3leaf | dc1p2_leaf2_gt272 | Ethernet51/1 | spine | dc1p2_spine3_ghs281 | Ethernet4/1 |
| spine | dc1p2_spine1_ghs253 | Ethernet2/1 | spine | dc2p1_spine1_ghs282 | Ethernet2/1 |
| spine | dc1p2_spine2_ghs278 | Ethernet2/1 | spine | dc2p1_spine2_ghs283 | Ethernet2/1 |
| spine | dc1p2_spine3_ghs281 | Ethernet2/1 | spine | dc2p1_spine3_ghs284 | Ethernet2/1 |
| l3leaf | dc2p1_leaf1a_mrv305 | Ethernet49/1 | spine | dc2p1_spine1_ghs282 | Ethernet3/1 |
| l3leaf | dc2p1_leaf1a_mrv305 | Ethernet50/1 | spine | dc2p1_spine2_ghs283 | Ethernet3/1 |
| l3leaf | dc2p1_leaf1a_mrv305 | Ethernet51/1 | spine | dc2p1_spine3_ghs284 | Ethernet3/1 |
| l3leaf | dc2p1_leaf1a_mrv305 | Ethernet53/1 | mlag_peer | dc2p1_leaf1b_mrv306 | Ethernet53/1 |
| l3leaf | dc2p1_leaf1a_mrv305 | Ethernet54/1 | mlag_peer | dc2p1_leaf1b_mrv306 | Ethernet54/1 |
| l3leaf | dc2p1_leaf1b_mrv306 | Ethernet49/1 | spine | dc2p1_spine1_ghs282 | Ethernet4/1 |
| l3leaf | dc2p1_leaf1b_mrv306 | Ethernet50/1 | spine | dc2p1_spine2_ghs283 | Ethernet4/1 |
| l3leaf | dc2p1_leaf1b_mrv306 | Ethernet51/1 | spine | dc2p1_spine3_ghs284 | Ethernet4/1 |
| l3leaf | dc2p1_sleaf_gt407 | Ethernet49/1 | spine | dc2p1_spine1_ghs282 | Ethernet6/1 |
| l3leaf | dc2p1_sleaf_gt407 | Ethernet50/1 | spine | dc2p1_spine2_ghs283 | Ethernet6/1 |
| l3leaf | dc2p1_sleaf_gt407 | Ethernet51/1 | spine | dc2p1_spine3_ghs284 | Ethernet6/1 |
| l2leaf | oob_spine1_pm362 | Ethernet2 | mlag_peer | oob_spine2_pm363 | Ethernet2 |
| l2leaf | oob_spine1_pm362 | Ethernet3 | mlag_peer | oob_spine2_pm363 | Ethernet3 |

## Fabric IP Allocation

### Fabric Point-To-Point Links

| Uplink IPv4 Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ---------------- | ------------------- | ------------------ | ------------------ |
| 161.1.0.0/23 | 512 | 72 | 14.07 % |

### Point-To-Point Links Node Allocation

| Node | Node Interface | Node IP Address | Peer Node | Peer Interface | Peer IP Address |
| ---- | -------------- | --------------- | --------- | -------------- | --------------- |
| dc1p1_leaf1a_cal418 | Ethernet49/1 | 161.1.0.1/31 | dc1p1_spine1_glf437 | Ethernet3/1/1 | 161.1.0.0/31 |
| dc1p1_leaf1a_cal418 | Ethernet50/1 | 161.1.0.3/31 | dc1p1_spine2_btp454 | Ethernet3/1 | 161.1.0.2/31 |
| dc1p1_leaf1a_cal418 | Ethernet51/1 | 161.1.0.5/31 | dc1p1_spine3_btd452 | Ethernet3/1 | 161.1.0.4/31 |
| dc1p1_leaf1b_cal419 | Ethernet49/1 | 161.1.0.7/31 | dc1p1_spine1_glf437 | Ethernet3/2/1 | 161.1.0.6/31 |
| dc1p1_leaf1b_cal419 | Ethernet50/1 | 161.1.0.9/31 | dc1p1_spine2_btp454 | Ethernet4/1 | 161.1.0.8/31 |
| dc1p1_leaf1b_cal419 | Ethernet51/1 | 161.1.0.11/31 | dc1p1_spine3_btd452 | Ethernet4/1 | 161.1.0.10/31 |
| dc1p1_leaf2a_cal421 | Ethernet50/1 | 161.1.0.13/31 | dc1p1_spine1_glf437 | Ethernet3/3/1 | 161.1.0.12/31 |
| dc1p1_leaf2a_cal421 | Ethernet51/1 | 161.1.0.15/31 | dc1p1_spine2_btp454 | Ethernet5/1 | 161.1.0.14/31 |
| dc1p1_leaf2a_cal421 | Ethernet52/1 | 161.1.0.17/31 | dc1p1_spine3_btd452 | Ethernet5/1 | 161.1.0.16/31 |
| dc1p1_leaf2b_cal422 | Ethernet49/1 | 161.1.0.19/31 | dc1p1_spine1_glf437 | Ethernet3/4/1 | 161.1.0.18/31 |
| dc1p1_leaf2b_cal422 | Ethernet50/1 | 161.1.0.21/31 | dc1p1_spine2_btp454 | Ethernet6/1 | 161.1.0.20/31 |
| dc1p1_leaf2b_cal422 | Ethernet51/1 | 161.1.0.23/31 | dc1p1_spine3_btd452 | Ethernet6/1 | 161.1.0.22/31 |
| dc1p1_leaf3a_smd554 | Ethernet33/1 | 161.1.0.25/31 | dc1p1_spine1_glf437 | Ethernet4/1/1 | 161.1.0.24/31 |
| dc1p1_leaf3a_smd554 | Ethernet34/1 | 161.1.0.27/31 | dc1p1_spine2_btp454 | Ethernet31/1 | 161.1.0.26/31 |
| dc1p1_leaf3a_smd554 | Ethernet35/1 | 161.1.0.29/31 | dc1p1_spine3_btd452 | Ethernet31/1 | 161.1.0.28/31 |
| dc1p1_leaf3b_smd555 | Ethernet33/1 | 161.1.0.31/31 | dc1p1_spine1_glf437 | Ethernet4/2/1 | 161.1.0.30/31 |
| dc1p1_leaf3b_smd555 | Ethernet34/1 | 161.1.0.33/31 | dc1p1_spine2_btp454 | Ethernet32/1 | 161.1.0.32/31 |
| dc1p1_leaf3b_smd555 | Ethernet35/1 | 161.1.0.35/31 | dc1p1_spine3_btd452 | Ethernet32/1 | 161.1.0.34/31 |
| dc1p1_sleaf_smv541 | Ethernet1/1 | 161.1.0.37/31 | dc1p1_spine1_glf437 | Ethernet3/5/1 | 161.1.0.36/31 |
| dc1p1_sleaf_smv541 | Ethernet2/1 | 161.1.0.39/31 | dc1p1_spine2_btp454 | Ethernet7/1 | 161.1.0.38/31 |
| dc1p1_sleaf_smv541 | Ethernet3/1 | 161.1.0.41/31 | dc1p1_spine3_btd452 | Ethernet7/1 | 161.1.0.40/31 |
| dc1p1_spine1_glf437 | Ethernet2/1/1 | 162.5.1.0/31 | dc1p2_spine1_ghs253 | Ethernet1/1 | 162.5.1.1/31 |
| dc1p1_spine1_glf437 | Ethernet2/2/1 | 162.5.1.2/31 | dc2p1_spine1_ghs282 | Ethernet1/1 | 162.5.1.3/31 |
| dc1p1_spine2_btp454 | Ethernet1/1 | 162.5.1.4/31 | dc1p2_spine2_ghs278 | Ethernet1/1 | 162.5.1.5/31 |
| dc1p1_spine2_btp454 | Ethernet2/1 | 162.5.1.6/31 | dc2p1_spine2_ghs283 | Ethernet1/1 | 162.5.1.7/31 |
| dc1p1_spine3_btd452 | Ethernet1/1 | 162.5.1.8/31 | dc1p2_spine3_ghs281 | Ethernet1/1 | 162.5.1.9/31 |
| dc1p1_spine3_btd452 | Ethernet2/1 | 162.5.1.10/31 | dc2p1_spine3_ghs284 | Ethernet1/1 | 162.5.1.11/31 |
| dc1p2_leaf1_mrv453 | Ethernet49/1 | 161.1.0.43/31 | dc1p2_spine1_ghs253 | Ethernet3/1 | 161.1.0.42/31 |
| dc1p2_leaf1_mrv453 | Ethernet50/1 | 161.1.0.45/31 | dc1p2_spine2_ghs278 | Ethernet3/1 | 161.1.0.44/31 |
| dc1p2_leaf1_mrv453 | Ethernet51/1 | 161.1.0.47/31 | dc1p2_spine3_ghs281 | Ethernet3/1 | 161.1.0.46/31 |
| dc1p2_leaf2_gt272 | Ethernet49/1 | 161.1.0.49/31 | dc1p2_spine1_ghs253 | Ethernet4/1 | 161.1.0.48/31 |
| dc1p2_leaf2_gt272 | Ethernet50/1 | 161.1.0.51/31 | dc1p2_spine2_ghs278 | Ethernet4/1 | 161.1.0.50/31 |
| dc1p2_leaf2_gt272 | Ethernet51/1 | 161.1.0.53/31 | dc1p2_spine3_ghs281 | Ethernet4/1 | 161.1.0.52/31 |
| dc1p2_spine1_ghs253 | Ethernet2/1 | 162.5.1.12/31 | dc2p1_spine1_ghs282 | Ethernet2/1 | 162.5.1.13/31 |
| dc1p2_spine2_ghs278 | Ethernet2/1 | 162.5.1.14/31 | dc2p1_spine2_ghs283 | Ethernet2/1 | 162.5.1.15/31 |
| dc1p2_spine3_ghs281 | Ethernet2/1 | 162.5.1.16/31 | dc2p1_spine3_ghs284 | Ethernet2/1 | 162.5.1.17/31 |
| dc2p1_leaf1a_mrv305 | Ethernet49/1 | 161.1.0.55/31 | dc2p1_spine1_ghs282 | Ethernet3/1 | 161.1.0.54/31 |
| dc2p1_leaf1a_mrv305 | Ethernet50/1 | 161.1.0.57/31 | dc2p1_spine2_ghs283 | Ethernet3/1 | 161.1.0.56/31 |
| dc2p1_leaf1a_mrv305 | Ethernet51/1 | 161.1.0.59/31 | dc2p1_spine3_ghs284 | Ethernet3/1 | 161.1.0.58/31 |
| dc2p1_leaf1b_mrv306 | Ethernet49/1 | 161.1.0.61/31 | dc2p1_spine1_ghs282 | Ethernet4/1 | 161.1.0.60/31 |
| dc2p1_leaf1b_mrv306 | Ethernet50/1 | 161.1.0.63/31 | dc2p1_spine2_ghs283 | Ethernet4/1 | 161.1.0.62/31 |
| dc2p1_leaf1b_mrv306 | Ethernet51/1 | 161.1.0.65/31 | dc2p1_spine3_ghs284 | Ethernet4/1 | 161.1.0.64/31 |
| dc2p1_sleaf_gt407 | Ethernet49/1 | 161.1.0.67/31 | dc2p1_spine1_ghs282 | Ethernet6/1 | 161.1.0.66/31 |
| dc2p1_sleaf_gt407 | Ethernet50/1 | 161.1.0.69/31 | dc2p1_spine2_ghs283 | Ethernet6/1 | 161.1.0.68/31 |
| dc2p1_sleaf_gt407 | Ethernet51/1 | 161.1.0.71/31 | dc2p1_spine3_ghs284 | Ethernet6/1 | 161.1.0.70/31 |

### Loopback Interfaces (BGP EVPN Peering)

| Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ------------- | ------------------- | ------------------ | ------------------ |
| 150.1.1.0/24 | 256 | 2 | 0.79 % |
| 150.1.2.0/24 | 256 | 2 | 0.79 % |
| 150.1.3.0/24 | 256 | 2 | 0.79 % |
| 150.1.4.0/24 | 256 | 1 | 0.4 % |
| 150.2.1.0/24 | 256 | 1 | 0.4 % |
| 150.2.2.0/24 | 256 | 1 | 0.4 % |
| 150.3.1.0/24 | 256 | 2 | 0.79 % |
| 150.3.2.0/24 | 256 | 1 | 0.4 % |
| 150.9.1.0/24 | 256 | 3 | 1.18 % |
| 150.9.2.0/24 | 256 | 3 | 1.18 % |
| 150.9.3.0/24 | 256 | 3 | 1.18 % |

### Loopback0 Interfaces Node Allocation

| POD | Node | Loopback0 |
| --- | ---- | --------- |
| MTU | dc1p1_leaf1a_cal418 | 150.1.1.3/32 |
| MTU | dc1p1_leaf1b_cal419 | 150.1.1.4/32 |
| MTU | dc1p1_leaf2a_cal421 | 150.1.2.5/32 |
| MTU | dc1p1_leaf2b_cal422 | 150.1.2.6/32 |
| MTU | dc1p1_leaf3a_smd554 | 150.1.3.7/32 |
| MTU | dc1p1_leaf3b_smd555 | 150.1.3.8/32 |
| MTU | dc1p1_sleaf_smv541 | 150.1.4.9/32 |
| MTU | dc1p1_spine1_glf437 | 150.9.1.1/32 |
| MTU | dc1p1_spine2_btp454 | 150.9.1.2/32 |
| MTU | dc1p1_spine3_btd452 | 150.9.1.3/32 |
| MTU | dc1p2_leaf1_mrv453 | 150.2.1.10/32 |
| MTU | dc1p2_leaf2_gt272 | 150.2.2.11/32 |
| MTU | dc1p2_spine1_ghs253 | 150.9.2.4/32 |
| MTU | dc1p2_spine2_ghs278 | 150.9.2.5/32 |
| MTU | dc1p2_spine3_ghs281 | 150.9.2.6/32 |
| MTU | dc2p1_leaf1a_mrv305 | 150.3.1.12/32 |
| MTU | dc2p1_leaf1b_mrv306 | 150.3.1.13/32 |
| MTU | dc2p1_sleaf_gt407 | 150.3.2.14/32 |
| MTU | dc2p1_spine1_ghs282 | 150.9.3.7/32 |
| MTU | dc2p1_spine2_ghs283 | 150.9.3.8/32 |
| MTU | dc2p1_spine3_ghs284 | 150.9.3.9/32 |

### VTEP Loopback VXLAN Tunnel Source Interfaces (VTEPs Only)

| VTEP Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| --------------------- | ------------------- | ------------------ | ------------------ |
| 3.1.1.0/24 | 256 | 2 | 0.79 % |
| 3.1.2.0/24 | 256 | 2 | 0.79 % |
| 3.1.3.0/24 | 256 | 2 | 0.79 % |
| 3.2.1.0/24 | 256 | 1 | 0.4 % |
| 3.2.2.0/24 | 256 | 1 | 0.4 % |
| 3.3.1.0/24 | 256 | 2 | 0.79 % |
| 9.1.1.0/24 | 256 | 1 | 0.4 % |
| 9.3.1.0/24 | 256 | 1 | 0.4 % |

### VTEP Loopback Node allocation

| POD | Node | Loopback1 |
| --- | ---- | --------- |
| MTU | dc1p1_leaf1a_cal418 | 3.1.1.3/32 |
| MTU | dc1p1_leaf1b_cal419 | 3.1.1.3/32 |
| MTU | dc1p1_leaf2a_cal421 | 3.1.2.5/32 |
| MTU | dc1p1_leaf2b_cal422 | 3.1.2.5/32 |
| MTU | dc1p1_leaf3a_smd554 | 3.1.3.7/32 |
| MTU | dc1p1_leaf3b_smd555 | 3.1.3.7/32 |
| MTU | dc1p1_sleaf_smv541 | 9.1.1.9/32 |
| MTU | dc1p2_leaf1_mrv453 | 3.2.1.10/32 |
| MTU | dc1p2_leaf2_gt272 | 3.2.2.11/32 |
| MTU | dc2p1_leaf1a_mrv305 | 3.3.1.12/32 |
| MTU | dc2p1_leaf1b_mrv306 | 3.3.1.12/32 |
| MTU | dc2p1_sleaf_gt407 | 9.3.1.14/32 |
