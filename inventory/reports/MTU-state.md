
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
| 6717 | 6612 | 105 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| dc1p1_leaf1a_cal418 |  610 | 600 | 10 | Hardware, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| dc1p1_leaf1b_cal419 |  610 | 600 | 10 | Hardware, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| dc1p1_leaf2a_cal421 |  599 | 589 | 10 | Hardware, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| dc1p1_leaf2b_cal422 |  605 | 595 | 10 | Hardware, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| dc1p1_leaf3a_smd554 |  609 | 599 | 10 | Hardware, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| dc1p1_leaf3b_smd555 |  609 | 599 | 10 | Hardware, IP Reachability, BGP, Routing Table, Loopback0 Reachability |
| dc1p1_sleaf_smv541 |  86 | 85 | 1 | Hardware |
| dc1p1_spine1_glf437 |  63 | 42 | 21 | Hardware, IP Reachability, BGP |
| dc1p1_spine2_btp454 |  57 | 56 | 1 | Hardware |
| dc1p1_spine3_btd452 |  57 | 56 | 1 | Hardware |
| dc1p2_leaf1_mrv453 |  589 | 588 | 1 | Hardware |
| dc1p2_leaf2_gt272 |  591 | 590 | 1 | Hardware |
| dc1p2_spine1_ghs253 |  36 | 34 | 2 | Hardware |
| dc1p2_spine2_ghs278 |  38 | 36 | 2 | Hardware |
| dc1p2_spine3_ghs281 |  38 | 36 | 2 | Hardware |
| dc2p1_leaf1a_mrv305 |  605 | 603 | 2 | Hardware |
| dc2p1_leaf1b_mrv306 |  605 | 604 | 1 | Hardware |
| dc2p1_sleaf_gt407 |  87 | 86 | 1 | Hardware |
| dc2p1_spine1_ghs282 |  40 | 38 | 2 | Hardware |
| dc2p1_spine2_ghs283 |  44 | 42 | 2 | Hardware |
| dc2p1_spine3_ghs284 |  44 | 42 | 2 | Hardware |
| oob_leaf1_npt325 |  57 | 56 | 1 | Hardware |
| oob_spine1_pm362 |  19 | 18 | 1 | Hardware |
| oob_spine2_pm363 |  19 | 18 | 1 | Hardware |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| Hardware |  416 | 383 | 33 |
| NTP |  24 | 24 | 0 |
| Interface State |  5203 | 5203 | 0 |
| LLDP Topology |  114 | 114 | 0 |
| MLAG |  10 | 10 | 0 |
| IP Reachability |  90 | 78 | 12 |
| BGP |  212 | 188 | 24 |
| Routing Table |  396 | 378 | 18 |
| Loopback0 Reachability |  252 | 234 | 18 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 2 | dc1p1_leaf1a_cal418 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 4 | dc1p1_leaf1b_cal419 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 6 | dc1p1_leaf2a_cal421 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 7 | dc1p1_leaf2b_cal422 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 9 | dc1p1_leaf3a_smd554 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 11 | dc1p1_leaf3b_smd555 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 13 | dc1p1_sleaf_smv541 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 16 | dc1p1_spine1_glf437 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 18 | dc1p1_spine2_btp454 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 20 | dc1p1_spine3_btd452 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 22 | dc1p2_leaf1_mrv453 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 24 | dc1p2_leaf2_gt272 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 27 | dc1p2_spine1_ghs253 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 29 | dc1p2_spine2_ghs278 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 31 | dc1p2_spine3_ghs281 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 32 | dc2p1_leaf1a_mrv305 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 34 | dc2p1_leaf1b_mrv306 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 37 | dc2p1_sleaf_gt407 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 39 | dc2p1_spine1_ghs282 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 41 | dc2p1_spine2_ghs283 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 43 | dc2p1_spine3_ghs284 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 44 | oob_leaf1_npt325 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 46 | oob_spine1_pm362 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 48 | oob_spine2_pm363 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 65 | dc1p1_spine1_glf437 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | FAIL | Power supply fan status is powerLoss |
| 66 | dc1p1_spine1_glf437 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply3 | FAIL | Power supply fan status is notInserted |
| 77 | dc1p2_spine1_ghs253 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | FAIL | Power supply fan status is powerLoss |
| 79 | dc1p2_spine2_ghs278 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | FAIL | Power supply fan status is powerLoss |
| 81 | dc1p2_spine3_ghs281 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | FAIL | Power supply fan status is powerLoss |
| 89 | dc2p1_spine1_ghs282 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | FAIL | Power supply fan status is powerLoss |
| 91 | dc2p1_spine2_ghs283 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | FAIL | Power supply fan status is powerLoss |
| 93 | dc2p1_spine3_ghs284 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | FAIL | Power supply fan status is powerLoss |
| 156 | dc2p1_leaf1a_mrv305 | Hardware | Fan status (fan tray) | Tray 2 | FAIL | Fan status is unknownHwStatus |
| 5768 | dc1p1_leaf1a_cal418 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf1a_cal418_Ethernet49/1 - Destination: dc1p1_spine1_glf437_Ethernet3/1/1 | FAIL | 100% packet loss |
| 5771 | dc1p1_leaf1b_cal419 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf1b_cal419_Ethernet49/1 - Destination: dc1p1_spine1_glf437_Ethernet3/2/1 | FAIL | 100% packet loss |
| 5774 | dc1p1_leaf2a_cal421 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf2a_cal421_Ethernet50/1 - Destination: dc1p1_spine1_glf437_Ethernet3/3/1 | FAIL | 100% packet loss |
| 5777 | dc1p1_leaf2b_cal422 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf2b_cal422_Ethernet49/1 - Destination: dc1p1_spine1_glf437_Ethernet3/4/1 | FAIL | 100% packet loss |
| 5780 | dc1p1_leaf3a_smd554 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf3a_smd554_Ethernet33/1 - Destination: dc1p1_spine1_glf437_Ethernet4/1/1 | FAIL | 100% packet loss |
| 5783 | dc1p1_leaf3b_smd555 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf3b_smd555_Ethernet33/1 - Destination: dc1p1_spine1_glf437_Ethernet4/2/1 | FAIL | 100% packet loss |
| 5789 | dc1p1_spine1_glf437 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine1_glf437_Ethernet3/1/1 - Destination: dc1p1_leaf1a_cal418_Ethernet49/1 | FAIL | 100% packet loss |
| 5790 | dc1p1_spine1_glf437 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine1_glf437_Ethernet3/2/1 - Destination: dc1p1_leaf1b_cal419_Ethernet49/1 | FAIL | 100% packet loss |
| 5791 | dc1p1_spine1_glf437 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine1_glf437_Ethernet3/3/1 - Destination: dc1p1_leaf2a_cal421_Ethernet50/1 | FAIL | 100% packet loss |
| 5792 | dc1p1_spine1_glf437 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine1_glf437_Ethernet3/4/1 - Destination: dc1p1_leaf2b_cal422_Ethernet49/1 | FAIL | 100% packet loss |
| 5794 | dc1p1_spine1_glf437 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine1_glf437_Ethernet4/1/1 - Destination: dc1p1_leaf3a_smd554_Ethernet33/1 | FAIL | 100% packet loss |
| 5795 | dc1p1_spine1_glf437 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine1_glf437_Ethernet4/2/1 - Destination: dc1p1_leaf3b_smd555_Ethernet33/1 | FAIL | 100% packet loss |
| 5880 | dc1p1_leaf1a_cal418 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.0 | FAIL | Session state Active |
| 5884 | dc1p1_leaf1b_cal419 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.6 | FAIL | Session state Active |
| 5888 | dc1p1_leaf2a_cal421 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.12 | FAIL | Session state Active |
| 5892 | dc1p1_leaf2b_cal422 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.18 | FAIL | Session state Active |
| 5896 | dc1p1_leaf3a_smd554 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.24 | FAIL | Session state Active |
| 5900 | dc1p1_leaf3b_smd555 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.30 | FAIL | Session state Active |
| 5906 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.1 | FAIL | Session state Idle |
| 5907 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.7 | FAIL | Session state Idle |
| 5908 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.13 | FAIL | Session state Idle |
| 5909 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.19 | FAIL | Session state Idle |
| 5911 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.25 | FAIL | Session state Idle |
| 5912 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.31 | FAIL | Session state Idle |
| 5980 | dc1p1_leaf1a_cal418 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.1 | FAIL | Session state: Active |
| 5983 | dc1p1_leaf1b_cal419 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.1 | FAIL | Session state: Active |
| 5986 | dc1p1_leaf2a_cal421 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.1 | FAIL | Session state: Active |
| 5989 | dc1p1_leaf2b_cal422 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.1 | FAIL | Session state: Active |
| 5992 | dc1p1_leaf3a_smd554 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.1 | FAIL | Session state: Active |
| 5995 | dc1p1_leaf3b_smd555 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.1 | FAIL | Session state: Active |
| 6001 | dc1p1_spine1_glf437 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.1.3 | FAIL | Session state: Active |
| 6002 | dc1p1_spine1_glf437 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.1.4 | FAIL | Session state: Active |
| 6003 | dc1p1_spine1_glf437 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.2.5 | FAIL | Session state: Active |
| 6004 | dc1p1_spine1_glf437 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.2.6 | FAIL | Session state: Active |
| 6005 | dc1p1_spine1_glf437 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.3.7 | FAIL | Session state: Active |
| 6006 | dc1p1_spine1_glf437 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.3.8 | FAIL | Session state: Active |
| 6221 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.9.1.1 | FAIL | Lo0 150.9.1.1 is not in the routing table |
| 6226 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.9.2.4 | FAIL | Lo0 150.9.2.4 is not in the routing table |
| 6232 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.9.3.7 | FAIL | Lo0 150.9.3.7 is not in the routing table |
| 6242 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.9.1.1 | FAIL | Lo0 150.9.1.1 is not in the routing table |
| 6247 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.9.2.4 | FAIL | Lo0 150.9.2.4 is not in the routing table |
| 6253 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.9.3.7 | FAIL | Lo0 150.9.3.7 is not in the routing table |
| 6263 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.9.1.1 | FAIL | Lo0 150.9.1.1 is not in the routing table |
| 6268 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.9.2.4 | FAIL | Lo0 150.9.2.4 is not in the routing table |
| 6274 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.9.3.7 | FAIL | Lo0 150.9.3.7 is not in the routing table |
| 6284 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.9.1.1 | FAIL | Lo0 150.9.1.1 is not in the routing table |
| 6289 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.9.2.4 | FAIL | Lo0 150.9.2.4 is not in the routing table |
| 6295 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.9.3.7 | FAIL | Lo0 150.9.3.7 is not in the routing table |
| 6305 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.9.1.1 | FAIL | Lo0 150.9.1.1 is not in the routing table |
| 6310 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.9.2.4 | FAIL | Lo0 150.9.2.4 is not in the routing table |
| 6316 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.9.3.7 | FAIL | Lo0 150.9.3.7 is not in the routing table |
| 6326 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.9.1.1 | FAIL | Lo0 150.9.1.1 is not in the routing table |
| 6331 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.9.2.4 | FAIL | Lo0 150.9.2.4 is not in the routing table |
| 6337 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.9.3.7 | FAIL | Lo0 150.9.3.7 is not in the routing table |
| 6473 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.9.1.1 | FAIL | 100% packet loss |
| 6478 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.9.2.4 | FAIL | 100% packet loss |
| 6484 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.9.3.7 | FAIL | 100% packet loss |
| 6494 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.9.1.1 | FAIL | 100% packet loss |
| 6499 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.9.2.4 | FAIL | 100% packet loss |
| 6505 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.9.3.7 | FAIL | 100% packet loss |
| 6515 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.9.1.1 | FAIL | 100% packet loss |
| 6520 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.9.2.4 | FAIL | 100% packet loss |
| 6526 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.9.3.7 | FAIL | 100% packet loss |
| 6536 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.9.1.1 | FAIL | 100% packet loss |
| 6541 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.9.2.4 | FAIL | 100% packet loss |
| 6547 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.9.3.7 | FAIL | 100% packet loss |
| 6557 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.9.1.1 | FAIL | 100% packet loss |
| 6562 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.9.2.4 | FAIL | 100% packet loss |
| 6568 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.9.3.7 | FAIL | 100% packet loss |
| 6578 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.9.1.1 | FAIL | 100% packet loss |
| 6583 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.9.2.4 | FAIL | 100% packet loss |
| 6589 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.9.3.7 | FAIL | 100% packet loss |

## All Test Results

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | dc1p1_leaf1a_cal418 | Hardware | Power supply status | Power supply 1 | PASS | - |
| 2 | dc1p1_leaf1a_cal418 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 3 | dc1p1_leaf1b_cal419 | Hardware | Power supply status | Power supply 1 | PASS | - |
| 4 | dc1p1_leaf1b_cal419 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 5 | dc1p1_leaf2a_cal421 | Hardware | Power supply status | Power supply 1 | PASS | - |
| 6 | dc1p1_leaf2a_cal421 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 7 | dc1p1_leaf2b_cal422 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 8 | dc1p1_leaf2b_cal422 | Hardware | Power supply status | Power supply 2 | PASS | - |
| 9 | dc1p1_leaf3a_smd554 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 10 | dc1p1_leaf3a_smd554 | Hardware | Power supply status | Power supply 2 | PASS | - |
| 11 | dc1p1_leaf3b_smd555 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 12 | dc1p1_leaf3b_smd555 | Hardware | Power supply status | Power supply 2 | PASS | - |
| 13 | dc1p1_sleaf_smv541 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 14 | dc1p1_sleaf_smv541 | Hardware | Power supply status | Power supply 2 | PASS | - |
| 15 | dc1p1_spine1_glf437 | Hardware | Power supply status | Power supply 1 | PASS | - |
| 16 | dc1p1_spine1_glf437 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 17 | dc1p1_spine1_glf437 | Hardware | Power supply status | Power supply 4 | PASS | - |
| 18 | dc1p1_spine2_btp454 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 19 | dc1p1_spine2_btp454 | Hardware | Power supply status | Power supply 2 | PASS | - |
| 20 | dc1p1_spine3_btd452 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 21 | dc1p1_spine3_btd452 | Hardware | Power supply status | Power supply 2 | PASS | - |
| 22 | dc1p2_leaf1_mrv453 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 23 | dc1p2_leaf1_mrv453 | Hardware | Power supply status | Power supply 2 | PASS | - |
| 24 | dc1p2_leaf2_gt272 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 25 | dc1p2_leaf2_gt272 | Hardware | Power supply status | Power supply 2 | PASS | - |
| 26 | dc1p2_spine1_ghs253 | Hardware | Power supply status | Power supply 1 | PASS | - |
| 27 | dc1p2_spine1_ghs253 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 28 | dc1p2_spine2_ghs278 | Hardware | Power supply status | Power supply 1 | PASS | - |
| 29 | dc1p2_spine2_ghs278 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 30 | dc1p2_spine3_ghs281 | Hardware | Power supply status | Power supply 1 | PASS | - |
| 31 | dc1p2_spine3_ghs281 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 32 | dc2p1_leaf1a_mrv305 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 33 | dc2p1_leaf1a_mrv305 | Hardware | Power supply status | Power supply 2 | PASS | - |
| 34 | dc2p1_leaf1b_mrv306 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 35 | dc2p1_leaf1b_mrv306 | Hardware | Power supply status | Power supply 2 | PASS | - |
| 36 | dc2p1_sleaf_gt407 | Hardware | Power supply status | Power supply 1 | PASS | - |
| 37 | dc2p1_sleaf_gt407 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 38 | dc2p1_spine1_ghs282 | Hardware | Power supply status | Power supply 1 | PASS | - |
| 39 | dc2p1_spine1_ghs282 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 40 | dc2p1_spine2_ghs283 | Hardware | Power supply status | Power supply 1 | PASS | - |
| 41 | dc2p1_spine2_ghs283 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 42 | dc2p1_spine3_ghs284 | Hardware | Power supply status | Power supply 1 | PASS | - |
| 43 | dc2p1_spine3_ghs284 | Hardware | Power supply status | Power supply 2 | FAIL | Power supply state is powerLoss |
| 44 | oob_leaf1_npt325 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 45 | oob_leaf1_npt325 | Hardware | Power supply status | Power supply 2 | PASS | - |
| 46 | oob_spine1_pm362 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 47 | oob_spine1_pm362 | Hardware | Power supply status | Power supply 2 | PASS | - |
| 48 | oob_spine2_pm363 | Hardware | Power supply status | Power supply 1 | FAIL | Power supply state is powerLoss |
| 49 | oob_spine2_pm363 | Hardware | Power supply status | Power supply 2 | PASS | - |
| 50 | dc1p1_leaf1a_cal418 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 51 | dc1p1_leaf1a_cal418 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 52 | dc1p1_leaf1b_cal419 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 53 | dc1p1_leaf1b_cal419 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 54 | dc1p1_leaf2a_cal421 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 55 | dc1p1_leaf2a_cal421 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 56 | dc1p1_leaf2b_cal422 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 57 | dc1p1_leaf2b_cal422 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 58 | dc1p1_leaf3a_smd554 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 59 | dc1p1_leaf3a_smd554 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 60 | dc1p1_leaf3b_smd555 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 61 | dc1p1_leaf3b_smd555 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 62 | dc1p1_sleaf_smv541 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 63 | dc1p1_sleaf_smv541 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 64 | dc1p1_spine1_glf437 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 65 | dc1p1_spine1_glf437 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | FAIL | Power supply fan status is powerLoss |
| 66 | dc1p1_spine1_glf437 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply3 | FAIL | Power supply fan status is notInserted |
| 67 | dc1p1_spine1_glf437 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply4 | PASS | - |
| 68 | dc1p1_spine2_btp454 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 69 | dc1p1_spine2_btp454 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 70 | dc1p1_spine3_btd452 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 71 | dc1p1_spine3_btd452 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 72 | dc1p2_leaf1_mrv453 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 73 | dc1p2_leaf1_mrv453 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 74 | dc1p2_leaf2_gt272 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 75 | dc1p2_leaf2_gt272 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 76 | dc1p2_spine1_ghs253 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 77 | dc1p2_spine1_ghs253 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | FAIL | Power supply fan status is powerLoss |
| 78 | dc1p2_spine2_ghs278 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 79 | dc1p2_spine2_ghs278 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | FAIL | Power supply fan status is powerLoss |
| 80 | dc1p2_spine3_ghs281 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 81 | dc1p2_spine3_ghs281 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | FAIL | Power supply fan status is powerLoss |
| 82 | dc2p1_leaf1a_mrv305 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 83 | dc2p1_leaf1a_mrv305 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 84 | dc2p1_leaf1b_mrv306 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 85 | dc2p1_leaf1b_mrv306 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 86 | dc2p1_sleaf_gt407 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 87 | dc2p1_sleaf_gt407 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 88 | dc2p1_spine1_ghs282 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 89 | dc2p1_spine1_ghs282 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | FAIL | Power supply fan status is powerLoss |
| 90 | dc2p1_spine2_ghs283 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 91 | dc2p1_spine2_ghs283 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | FAIL | Power supply fan status is powerLoss |
| 92 | dc2p1_spine3_ghs284 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 93 | dc2p1_spine3_ghs284 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | FAIL | Power supply fan status is powerLoss |
| 94 | oob_spine1_pm362 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 95 | oob_spine1_pm362 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 96 | oob_spine2_pm363 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply1 | PASS | - |
| 97 | oob_spine2_pm363 | Hardware | Fan status (power supplies) | Power supply fan PowerSupply2 | PASS | - |
| 98 | dc1p1_leaf1a_cal418 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 99 | dc1p1_leaf1a_cal418 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 100 | dc1p1_leaf1a_cal418 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 101 | dc1p1_leaf1a_cal418 | Hardware | Fan status (fan tray) | Tray 4 | PASS | - |
| 102 | dc1p1_leaf1b_cal419 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 103 | dc1p1_leaf1b_cal419 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 104 | dc1p1_leaf1b_cal419 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 105 | dc1p1_leaf1b_cal419 | Hardware | Fan status (fan tray) | Tray 4 | PASS | - |
| 106 | dc1p1_leaf2a_cal421 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 107 | dc1p1_leaf2a_cal421 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 108 | dc1p1_leaf2a_cal421 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 109 | dc1p1_leaf2a_cal421 | Hardware | Fan status (fan tray) | Tray 4 | PASS | - |
| 110 | dc1p1_leaf2b_cal422 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 111 | dc1p1_leaf2b_cal422 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 112 | dc1p1_leaf2b_cal422 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 113 | dc1p1_leaf2b_cal422 | Hardware | Fan status (fan tray) | Tray 4 | PASS | - |
| 114 | dc1p1_leaf3a_smd554 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 115 | dc1p1_leaf3a_smd554 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 116 | dc1p1_leaf3a_smd554 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 117 | dc1p1_leaf3b_smd555 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 118 | dc1p1_leaf3b_smd555 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 119 | dc1p1_leaf3b_smd555 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 120 | dc1p1_sleaf_smv541 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 121 | dc1p1_sleaf_smv541 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 122 | dc1p1_sleaf_smv541 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 123 | dc1p1_spine1_glf437 | Hardware | Fan status (fan tray) | Tray 1/1 | PASS | - |
| 124 | dc1p1_spine1_glf437 | Hardware | Fan status (fan tray) | Tray 1/2 | PASS | - |
| 125 | dc1p1_spine1_glf437 | Hardware | Fan status (fan tray) | Tray 1/3 | PASS | - |
| 126 | dc1p1_spine1_glf437 | Hardware | Fan status (fan tray) | Tray 1/4 | PASS | - |
| 127 | dc1p1_spine1_glf437 | Hardware | Fan status (fan tray) | Tray 1/5 | PASS | - |
| 128 | dc1p1_spine2_btp454 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 129 | dc1p1_spine2_btp454 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 130 | dc1p1_spine2_btp454 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 131 | dc1p1_spine3_btd452 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 132 | dc1p1_spine3_btd452 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 133 | dc1p1_spine3_btd452 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 134 | dc1p2_leaf1_mrv453 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 135 | dc1p2_leaf1_mrv453 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 136 | dc1p2_leaf2_gt272 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 137 | dc1p2_leaf2_gt272 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 138 | dc1p2_leaf2_gt272 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 139 | dc1p2_leaf2_gt272 | Hardware | Fan status (fan tray) | Tray 4 | PASS | - |
| 140 | dc1p2_spine1_ghs253 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 141 | dc1p2_spine1_ghs253 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 142 | dc1p2_spine1_ghs253 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 143 | dc1p2_spine1_ghs253 | Hardware | Fan status (fan tray) | Tray 4 | PASS | - |
| 144 | dc1p2_spine1_ghs253 | Hardware | Fan status (fan tray) | Tray 5 | PASS | - |
| 145 | dc1p2_spine2_ghs278 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 146 | dc1p2_spine2_ghs278 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 147 | dc1p2_spine2_ghs278 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 148 | dc1p2_spine2_ghs278 | Hardware | Fan status (fan tray) | Tray 4 | PASS | - |
| 149 | dc1p2_spine2_ghs278 | Hardware | Fan status (fan tray) | Tray 5 | PASS | - |
| 150 | dc1p2_spine3_ghs281 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 151 | dc1p2_spine3_ghs281 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 152 | dc1p2_spine3_ghs281 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 153 | dc1p2_spine3_ghs281 | Hardware | Fan status (fan tray) | Tray 4 | PASS | - |
| 154 | dc1p2_spine3_ghs281 | Hardware | Fan status (fan tray) | Tray 5 | PASS | - |
| 155 | dc2p1_leaf1a_mrv305 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 156 | dc2p1_leaf1a_mrv305 | Hardware | Fan status (fan tray) | Tray 2 | FAIL | Fan status is unknownHwStatus |
| 157 | dc2p1_leaf1b_mrv306 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 158 | dc2p1_leaf1b_mrv306 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 159 | dc2p1_sleaf_gt407 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 160 | dc2p1_sleaf_gt407 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 161 | dc2p1_sleaf_gt407 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 162 | dc2p1_sleaf_gt407 | Hardware | Fan status (fan tray) | Tray 4 | PASS | - |
| 163 | dc2p1_spine1_ghs282 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 164 | dc2p1_spine1_ghs282 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 165 | dc2p1_spine1_ghs282 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 166 | dc2p1_spine1_ghs282 | Hardware | Fan status (fan tray) | Tray 4 | PASS | - |
| 167 | dc2p1_spine1_ghs282 | Hardware | Fan status (fan tray) | Tray 5 | PASS | - |
| 168 | dc2p1_spine2_ghs283 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 169 | dc2p1_spine2_ghs283 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 170 | dc2p1_spine2_ghs283 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 171 | dc2p1_spine2_ghs283 | Hardware | Fan status (fan tray) | Tray 4 | PASS | - |
| 172 | dc2p1_spine2_ghs283 | Hardware | Fan status (fan tray) | Tray 5 | PASS | - |
| 173 | dc2p1_spine3_ghs284 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 174 | dc2p1_spine3_ghs284 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 175 | dc2p1_spine3_ghs284 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 176 | dc2p1_spine3_ghs284 | Hardware | Fan status (fan tray) | Tray 4 | PASS | - |
| 177 | dc2p1_spine3_ghs284 | Hardware | Fan status (fan tray) | Tray 5 | PASS | - |
| 178 | oob_leaf1_npt325 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 179 | oob_leaf1_npt325 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 180 | oob_spine1_pm362 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 181 | oob_spine1_pm362 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 182 | oob_spine1_pm362 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 183 | oob_spine2_pm363 | Hardware | Fan status (fan tray) | Tray 1 | PASS | - |
| 184 | oob_spine2_pm363 | Hardware | Fan status (fan tray) | Tray 2 | PASS | - |
| 185 | oob_spine2_pm363 | Hardware | Fan status (fan tray) | Tray 3 | PASS | - |
| 186 | dc1p1_leaf1a_cal418 | Hardware | Temperature | System temperature | PASS | - |
| 187 | dc1p1_leaf1b_cal419 | Hardware | Temperature | System temperature | PASS | - |
| 188 | dc1p1_leaf2a_cal421 | Hardware | Temperature | System temperature | PASS | - |
| 189 | dc1p1_leaf2b_cal422 | Hardware | Temperature | System temperature | PASS | - |
| 190 | dc1p1_leaf3a_smd554 | Hardware | Temperature | System temperature | PASS | - |
| 191 | dc1p1_leaf3b_smd555 | Hardware | Temperature | System temperature | PASS | - |
| 192 | dc1p1_sleaf_smv541 | Hardware | Temperature | System temperature | PASS | - |
| 193 | dc1p1_spine1_glf437 | Hardware | Temperature | System temperature | PASS | - |
| 194 | dc1p1_spine2_btp454 | Hardware | Temperature | System temperature | PASS | - |
| 195 | dc1p1_spine3_btd452 | Hardware | Temperature | System temperature | PASS | - |
| 196 | dc1p2_leaf1_mrv453 | Hardware | Temperature | System temperature | PASS | - |
| 197 | dc1p2_leaf2_gt272 | Hardware | Temperature | System temperature | PASS | - |
| 198 | dc1p2_spine1_ghs253 | Hardware | Temperature | System temperature | PASS | - |
| 199 | dc1p2_spine2_ghs278 | Hardware | Temperature | System temperature | PASS | - |
| 200 | dc1p2_spine3_ghs281 | Hardware | Temperature | System temperature | PASS | - |
| 201 | dc2p1_leaf1a_mrv305 | Hardware | Temperature | System temperature | PASS | - |
| 202 | dc2p1_leaf1b_mrv306 | Hardware | Temperature | System temperature | PASS | - |
| 203 | dc2p1_sleaf_gt407 | Hardware | Temperature | System temperature | PASS | - |
| 204 | dc2p1_spine1_ghs282 | Hardware | Temperature | System temperature | PASS | - |
| 205 | dc2p1_spine2_ghs283 | Hardware | Temperature | System temperature | PASS | - |
| 206 | dc2p1_spine3_ghs284 | Hardware | Temperature | System temperature | PASS | - |
| 207 | oob_leaf1_npt325 | Hardware | Temperature | System temperature | PASS | - |
| 208 | oob_spine1_pm362 | Hardware | Temperature | System temperature | PASS | - |
| 209 | oob_spine2_pm363 | Hardware | Temperature | System temperature | PASS | - |
| 210 | dc1p1_leaf1a_cal418 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 211 | dc1p1_leaf1a_cal418 | Hardware | Transceivers manufacturers | Port 49 | PASS | - |
| 212 | dc1p1_leaf1a_cal418 | Hardware | Transceivers manufacturers | Port 50 | PASS | - |
| 213 | dc1p1_leaf1a_cal418 | Hardware | Transceivers manufacturers | Port 51 | PASS | - |
| 214 | dc1p1_leaf1a_cal418 | Hardware | Transceivers manufacturers | Port 52 | PASS | - |
| 215 | dc1p1_leaf1a_cal418 | Hardware | Transceivers manufacturers | Port 53 | PASS | - |
| 216 | dc1p1_leaf1a_cal418 | Hardware | Transceivers manufacturers | Port 54 | PASS | - |
| 217 | dc1p1_leaf1a_cal418 | Hardware | Transceivers manufacturers | Port 55 | PASS | - |
| 218 | dc1p1_leaf1a_cal418 | Hardware | Transceivers manufacturers | Port 56 | PASS | - |
| 219 | dc1p1_leaf1b_cal419 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 220 | dc1p1_leaf1b_cal419 | Hardware | Transceivers manufacturers | Port 49 | PASS | - |
| 221 | dc1p1_leaf1b_cal419 | Hardware | Transceivers manufacturers | Port 50 | PASS | - |
| 222 | dc1p1_leaf1b_cal419 | Hardware | Transceivers manufacturers | Port 51 | PASS | - |
| 223 | dc1p1_leaf1b_cal419 | Hardware | Transceivers manufacturers | Port 52 | PASS | - |
| 224 | dc1p1_leaf1b_cal419 | Hardware | Transceivers manufacturers | Port 53 | PASS | - |
| 225 | dc1p1_leaf1b_cal419 | Hardware | Transceivers manufacturers | Port 54 | PASS | - |
| 226 | dc1p1_leaf1b_cal419 | Hardware | Transceivers manufacturers | Port 55 | PASS | - |
| 227 | dc1p1_leaf1b_cal419 | Hardware | Transceivers manufacturers | Port 56 | PASS | - |
| 228 | dc1p1_leaf2a_cal421 | Hardware | Transceivers manufacturers | Port 38 | PASS | - |
| 229 | dc1p1_leaf2a_cal421 | Hardware | Transceivers manufacturers | Port 50 | PASS | - |
| 230 | dc1p1_leaf2a_cal421 | Hardware | Transceivers manufacturers | Port 51 | PASS | - |
| 231 | dc1p1_leaf2a_cal421 | Hardware | Transceivers manufacturers | Port 52 | PASS | - |
| 232 | dc1p1_leaf2a_cal421 | Hardware | Transceivers manufacturers | Port 53 | PASS | - |
| 233 | dc1p1_leaf2a_cal421 | Hardware | Transceivers manufacturers | Port 54 | PASS | - |
| 234 | dc1p1_leaf2a_cal421 | Hardware | Transceivers manufacturers | Port 55 | PASS | - |
| 235 | dc1p1_leaf2b_cal422 | Hardware | Transceivers manufacturers | Port 38 | PASS | - |
| 236 | dc1p1_leaf2b_cal422 | Hardware | Transceivers manufacturers | Port 49 | PASS | - |
| 237 | dc1p1_leaf2b_cal422 | Hardware | Transceivers manufacturers | Port 50 | PASS | - |
| 238 | dc1p1_leaf2b_cal422 | Hardware | Transceivers manufacturers | Port 51 | PASS | - |
| 239 | dc1p1_leaf2b_cal422 | Hardware | Transceivers manufacturers | Port 52 | PASS | - |
| 240 | dc1p1_leaf2b_cal422 | Hardware | Transceivers manufacturers | Port 53 | PASS | - |
| 241 | dc1p1_leaf2b_cal422 | Hardware | Transceivers manufacturers | Port 54 | PASS | - |
| 242 | dc1p1_leaf3a_smd554 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 243 | dc1p1_leaf3a_smd554 | Hardware | Transceivers manufacturers | Port 2 | PASS | - |
| 244 | dc1p1_leaf3a_smd554 | Hardware | Transceivers manufacturers | Port 3 | PASS | - |
| 245 | dc1p1_leaf3a_smd554 | Hardware | Transceivers manufacturers | Port 4 | PASS | - |
| 246 | dc1p1_leaf3a_smd554 | Hardware | Transceivers manufacturers | Port 5 | PASS | - |
| 247 | dc1p1_leaf3a_smd554 | Hardware | Transceivers manufacturers | Port 33 | PASS | - |
| 248 | dc1p1_leaf3a_smd554 | Hardware | Transceivers manufacturers | Port 34 | PASS | - |
| 249 | dc1p1_leaf3a_smd554 | Hardware | Transceivers manufacturers | Port 35 | PASS | - |
| 250 | dc1p1_leaf3b_smd555 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 251 | dc1p1_leaf3b_smd555 | Hardware | Transceivers manufacturers | Port 2 | PASS | - |
| 252 | dc1p1_leaf3b_smd555 | Hardware | Transceivers manufacturers | Port 3 | PASS | - |
| 253 | dc1p1_leaf3b_smd555 | Hardware | Transceivers manufacturers | Port 4 | PASS | - |
| 254 | dc1p1_leaf3b_smd555 | Hardware | Transceivers manufacturers | Port 5 | PASS | - |
| 255 | dc1p1_leaf3b_smd555 | Hardware | Transceivers manufacturers | Port 33 | PASS | - |
| 256 | dc1p1_leaf3b_smd555 | Hardware | Transceivers manufacturers | Port 34 | PASS | - |
| 257 | dc1p1_leaf3b_smd555 | Hardware | Transceivers manufacturers | Port 35 | PASS | - |
| 258 | dc1p1_sleaf_smv541 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 259 | dc1p1_sleaf_smv541 | Hardware | Transceivers manufacturers | Port 2 | PASS | - |
| 260 | dc1p1_sleaf_smv541 | Hardware | Transceivers manufacturers | Port 3 | PASS | - |
| 261 | dc1p1_sleaf_smv541 | Hardware | Transceivers manufacturers | Port 7 | PASS | - |
| 262 | dc1p1_sleaf_smv541 | Hardware | Transceivers manufacturers | Port 9 | PASS | - |
| 263 | dc1p1_spine1_glf437 | Hardware | Transceivers manufacturers | Port 2/1 | PASS | - |
| 264 | dc1p1_spine1_glf437 | Hardware | Transceivers manufacturers | Port 2/2 | PASS | - |
| 265 | dc1p1_spine1_glf437 | Hardware | Transceivers manufacturers | Port 3/1 | PASS | - |
| 266 | dc1p1_spine1_glf437 | Hardware | Transceivers manufacturers | Port 3/2 | PASS | - |
| 267 | dc1p1_spine1_glf437 | Hardware | Transceivers manufacturers | Port 3/3 | PASS | - |
| 268 | dc1p1_spine1_glf437 | Hardware | Transceivers manufacturers | Port 3/4 | PASS | - |
| 269 | dc1p1_spine1_glf437 | Hardware | Transceivers manufacturers | Port 3/5 | PASS | - |
| 270 | dc1p1_spine1_glf437 | Hardware | Transceivers manufacturers | Port 3/6 | PASS | - |
| 271 | dc1p1_spine1_glf437 | Hardware | Transceivers manufacturers | Port 4/1 | PASS | - |
| 272 | dc1p1_spine1_glf437 | Hardware | Transceivers manufacturers | Port 4/2 | PASS | - |
| 273 | dc1p1_spine2_btp454 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 274 | dc1p1_spine2_btp454 | Hardware | Transceivers manufacturers | Port 2 | PASS | - |
| 275 | dc1p1_spine2_btp454 | Hardware | Transceivers manufacturers | Port 3 | PASS | - |
| 276 | dc1p1_spine2_btp454 | Hardware | Transceivers manufacturers | Port 4 | PASS | - |
| 277 | dc1p1_spine2_btp454 | Hardware | Transceivers manufacturers | Port 5 | PASS | - |
| 278 | dc1p1_spine2_btp454 | Hardware | Transceivers manufacturers | Port 6 | PASS | - |
| 279 | dc1p1_spine2_btp454 | Hardware | Transceivers manufacturers | Port 7 | PASS | - |
| 280 | dc1p1_spine2_btp454 | Hardware | Transceivers manufacturers | Port 8 | PASS | - |
| 281 | dc1p1_spine2_btp454 | Hardware | Transceivers manufacturers | Port 31 | PASS | - |
| 282 | dc1p1_spine2_btp454 | Hardware | Transceivers manufacturers | Port 32 | PASS | - |
| 283 | dc1p1_spine3_btd452 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 284 | dc1p1_spine3_btd452 | Hardware | Transceivers manufacturers | Port 2 | PASS | - |
| 285 | dc1p1_spine3_btd452 | Hardware | Transceivers manufacturers | Port 3 | PASS | - |
| 286 | dc1p1_spine3_btd452 | Hardware | Transceivers manufacturers | Port 4 | PASS | - |
| 287 | dc1p1_spine3_btd452 | Hardware | Transceivers manufacturers | Port 5 | PASS | - |
| 288 | dc1p1_spine3_btd452 | Hardware | Transceivers manufacturers | Port 6 | PASS | - |
| 289 | dc1p1_spine3_btd452 | Hardware | Transceivers manufacturers | Port 7 | PASS | - |
| 290 | dc1p1_spine3_btd452 | Hardware | Transceivers manufacturers | Port 8 | PASS | - |
| 291 | dc1p1_spine3_btd452 | Hardware | Transceivers manufacturers | Port 31 | PASS | - |
| 292 | dc1p1_spine3_btd452 | Hardware | Transceivers manufacturers | Port 32 | PASS | - |
| 293 | dc1p2_leaf1_mrv453 | Hardware | Transceivers manufacturers | Port 49 | PASS | - |
| 294 | dc1p2_leaf1_mrv453 | Hardware | Transceivers manufacturers | Port 50 | PASS | - |
| 295 | dc1p2_leaf1_mrv453 | Hardware | Transceivers manufacturers | Port 51 | PASS | - |
| 296 | dc1p2_leaf1_mrv453 | Hardware | Transceivers manufacturers | Port 52 | PASS | - |
| 297 | dc1p2_leaf2_gt272 | Hardware | Transceivers manufacturers | Port 49 | PASS | - |
| 298 | dc1p2_leaf2_gt272 | Hardware | Transceivers manufacturers | Port 50 | PASS | - |
| 299 | dc1p2_leaf2_gt272 | Hardware | Transceivers manufacturers | Port 51 | PASS | - |
| 300 | dc1p2_leaf2_gt272 | Hardware | Transceivers manufacturers | Port 52 | PASS | - |
| 301 | dc1p2_spine1_ghs253 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 302 | dc1p2_spine1_ghs253 | Hardware | Transceivers manufacturers | Port 2 | PASS | - |
| 303 | dc1p2_spine1_ghs253 | Hardware | Transceivers manufacturers | Port 3 | PASS | - |
| 304 | dc1p2_spine1_ghs253 | Hardware | Transceivers manufacturers | Port 4 | PASS | - |
| 305 | dc1p2_spine1_ghs253 | Hardware | Transceivers manufacturers | Port 5 | PASS | - |
| 306 | dc1p2_spine1_ghs253 | Hardware | Transceivers manufacturers | Port 30 | PASS | - |
| 307 | dc1p2_spine2_ghs278 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 308 | dc1p2_spine2_ghs278 | Hardware | Transceivers manufacturers | Port 2 | PASS | - |
| 309 | dc1p2_spine2_ghs278 | Hardware | Transceivers manufacturers | Port 3 | PASS | - |
| 310 | dc1p2_spine2_ghs278 | Hardware | Transceivers manufacturers | Port 4 | PASS | - |
| 311 | dc1p2_spine2_ghs278 | Hardware | Transceivers manufacturers | Port 5 | PASS | - |
| 312 | dc1p2_spine3_ghs281 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 313 | dc1p2_spine3_ghs281 | Hardware | Transceivers manufacturers | Port 2 | PASS | - |
| 314 | dc1p2_spine3_ghs281 | Hardware | Transceivers manufacturers | Port 3 | PASS | - |
| 315 | dc1p2_spine3_ghs281 | Hardware | Transceivers manufacturers | Port 4 | PASS | - |
| 316 | dc1p2_spine3_ghs281 | Hardware | Transceivers manufacturers | Port 5 | PASS | - |
| 317 | dc2p1_leaf1a_mrv305 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 318 | dc2p1_leaf1a_mrv305 | Hardware | Transceivers manufacturers | Port 49 | PASS | - |
| 319 | dc2p1_leaf1a_mrv305 | Hardware | Transceivers manufacturers | Port 50 | PASS | - |
| 320 | dc2p1_leaf1a_mrv305 | Hardware | Transceivers manufacturers | Port 51 | PASS | - |
| 321 | dc2p1_leaf1a_mrv305 | Hardware | Transceivers manufacturers | Port 52 | PASS | - |
| 322 | dc2p1_leaf1a_mrv305 | Hardware | Transceivers manufacturers | Port 53 | PASS | - |
| 323 | dc2p1_leaf1a_mrv305 | Hardware | Transceivers manufacturers | Port 54 | PASS | - |
| 324 | dc2p1_leaf1b_mrv306 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 325 | dc2p1_leaf1b_mrv306 | Hardware | Transceivers manufacturers | Port 49 | PASS | - |
| 326 | dc2p1_leaf1b_mrv306 | Hardware | Transceivers manufacturers | Port 50 | PASS | - |
| 327 | dc2p1_leaf1b_mrv306 | Hardware | Transceivers manufacturers | Port 51 | PASS | - |
| 328 | dc2p1_leaf1b_mrv306 | Hardware | Transceivers manufacturers | Port 52 | PASS | - |
| 329 | dc2p1_leaf1b_mrv306 | Hardware | Transceivers manufacturers | Port 53 | PASS | - |
| 330 | dc2p1_leaf1b_mrv306 | Hardware | Transceivers manufacturers | Port 54 | PASS | - |
| 331 | dc2p1_sleaf_gt407 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 332 | dc2p1_sleaf_gt407 | Hardware | Transceivers manufacturers | Port 49 | PASS | - |
| 333 | dc2p1_sleaf_gt407 | Hardware | Transceivers manufacturers | Port 50 | PASS | - |
| 334 | dc2p1_sleaf_gt407 | Hardware | Transceivers manufacturers | Port 51 | PASS | - |
| 335 | dc2p1_sleaf_gt407 | Hardware | Transceivers manufacturers | Port 52 | PASS | - |
| 336 | dc2p1_spine1_ghs282 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 337 | dc2p1_spine1_ghs282 | Hardware | Transceivers manufacturers | Port 2 | PASS | - |
| 338 | dc2p1_spine1_ghs282 | Hardware | Transceivers manufacturers | Port 3 | PASS | - |
| 339 | dc2p1_spine1_ghs282 | Hardware | Transceivers manufacturers | Port 4 | PASS | - |
| 340 | dc2p1_spine1_ghs282 | Hardware | Transceivers manufacturers | Port 5 | PASS | - |
| 341 | dc2p1_spine1_ghs282 | Hardware | Transceivers manufacturers | Port 6 | PASS | - |
| 342 | dc2p1_spine2_ghs283 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 343 | dc2p1_spine2_ghs283 | Hardware | Transceivers manufacturers | Port 2 | PASS | - |
| 344 | dc2p1_spine2_ghs283 | Hardware | Transceivers manufacturers | Port 3 | PASS | - |
| 345 | dc2p1_spine2_ghs283 | Hardware | Transceivers manufacturers | Port 4 | PASS | - |
| 346 | dc2p1_spine2_ghs283 | Hardware | Transceivers manufacturers | Port 5 | PASS | - |
| 347 | dc2p1_spine2_ghs283 | Hardware | Transceivers manufacturers | Port 6 | PASS | - |
| 348 | dc2p1_spine3_ghs284 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 349 | dc2p1_spine3_ghs284 | Hardware | Transceivers manufacturers | Port 2 | PASS | - |
| 350 | dc2p1_spine3_ghs284 | Hardware | Transceivers manufacturers | Port 3 | PASS | - |
| 351 | dc2p1_spine3_ghs284 | Hardware | Transceivers manufacturers | Port 4 | PASS | - |
| 352 | dc2p1_spine3_ghs284 | Hardware | Transceivers manufacturers | Port 5 | PASS | - |
| 353 | dc2p1_spine3_ghs284 | Hardware | Transceivers manufacturers | Port 6 | PASS | - |
| 354 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 355 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 2 | PASS | - |
| 356 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 3 | PASS | - |
| 357 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 4 | PASS | - |
| 358 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 5 | PASS | - |
| 359 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 6 | PASS | - |
| 360 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 7 | PASS | - |
| 361 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 8 | PASS | - |
| 362 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 9 | PASS | - |
| 363 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 10 | PASS | - |
| 364 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 11 | PASS | - |
| 365 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 12 | PASS | - |
| 366 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 13 | PASS | - |
| 367 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 14 | PASS | - |
| 368 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 15 | PASS | - |
| 369 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 16 | PASS | - |
| 370 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 17 | PASS | - |
| 371 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 18 | PASS | - |
| 372 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 19 | PASS | - |
| 373 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 20 | PASS | - |
| 374 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 21 | PASS | - |
| 375 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 22 | PASS | - |
| 376 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 23 | PASS | - |
| 377 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 24 | PASS | - |
| 378 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 25 | PASS | - |
| 379 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 26 | PASS | - |
| 380 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 27 | PASS | - |
| 381 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 28 | PASS | - |
| 382 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 29 | PASS | - |
| 383 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 30 | PASS | - |
| 384 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 31 | PASS | - |
| 385 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 32 | PASS | - |
| 386 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 33 | PASS | - |
| 387 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 34 | PASS | - |
| 388 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 35 | PASS | - |
| 389 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 36 | PASS | - |
| 390 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 37 | PASS | - |
| 391 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 38 | PASS | - |
| 392 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 39 | PASS | - |
| 393 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 40 | PASS | - |
| 394 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 41 | PASS | - |
| 395 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 42 | PASS | - |
| 396 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 43 | PASS | - |
| 397 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 44 | PASS | - |
| 398 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 45 | PASS | - |
| 399 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 46 | PASS | - |
| 400 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 47 | PASS | - |
| 401 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 48 | PASS | - |
| 402 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 49 | PASS | - |
| 403 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 50 | PASS | - |
| 404 | oob_leaf1_npt325 | Hardware | Transceivers manufacturers | Port 51 | PASS | - |
| 405 | oob_spine1_pm362 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 406 | oob_spine1_pm362 | Hardware | Transceivers manufacturers | Port 2 | PASS | - |
| 407 | oob_spine1_pm362 | Hardware | Transceivers manufacturers | Port 3 | PASS | - |
| 408 | oob_spine1_pm362 | Hardware | Transceivers manufacturers | Port 4 | PASS | - |
| 409 | oob_spine1_pm362 | Hardware | Transceivers manufacturers | Port 25 | PASS | - |
| 410 | oob_spine1_pm362 | Hardware | Transceivers manufacturers | Port 26 | PASS | - |
| 411 | oob_spine2_pm363 | Hardware | Transceivers manufacturers | Port 1 | PASS | - |
| 412 | oob_spine2_pm363 | Hardware | Transceivers manufacturers | Port 2 | PASS | - |
| 413 | oob_spine2_pm363 | Hardware | Transceivers manufacturers | Port 3 | PASS | - |
| 414 | oob_spine2_pm363 | Hardware | Transceivers manufacturers | Port 4 | PASS | - |
| 415 | oob_spine2_pm363 | Hardware | Transceivers manufacturers | Port 25 | PASS | - |
| 416 | oob_spine2_pm363 | Hardware | Transceivers manufacturers | Port 26 | PASS | - |
| 417 | dc1p1_leaf1a_cal418 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 418 | dc1p1_leaf1b_cal419 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 419 | dc1p1_leaf2a_cal421 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 420 | dc1p1_leaf2b_cal422 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 421 | dc1p1_leaf3a_smd554 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 422 | dc1p1_leaf3b_smd555 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 423 | dc1p1_sleaf_smv541 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 424 | dc1p1_spine1_glf437 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 425 | dc1p1_spine2_btp454 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 426 | dc1p1_spine3_btd452 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 427 | dc1p2_leaf1_mrv453 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 428 | dc1p2_leaf2_gt272 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 429 | dc1p2_spine1_ghs253 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 430 | dc1p2_spine2_ghs278 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 431 | dc1p2_spine3_ghs281 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 432 | dc2p1_leaf1a_mrv305 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 433 | dc2p1_leaf1b_mrv306 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 434 | dc2p1_sleaf_gt407 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 435 | dc2p1_spine1_ghs282 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 436 | dc2p1_spine2_ghs283 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 437 | dc2p1_spine3_ghs284 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 438 | oob_leaf1_npt325 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 439 | oob_spine1_pm362 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 440 | oob_spine2_pm363 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 441 | dc1p1_leaf1a_cal418 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet53/1 - MLAG_PEER_dc1p1_leaf1b_cal419_Ethernet53/1 | PASS | - |
| 442 | dc1p1_leaf1a_cal418 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet54/1 - MLAG_PEER_dc1p1_leaf1b_cal419_Ethernet54/1 | PASS | - |
| 443 | dc1p1_leaf1a_cal418 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet49/1 - dc1p1_spine1_glf437-Ethernet3/1/1 | PASS | - |
| 444 | dc1p1_leaf1a_cal418 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet50/1 - dc1p1_spine2_btp454-Ethernet3/1 | PASS | - |
| 445 | dc1p1_leaf1a_cal418 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet51/1 - dc1p1_spine3_btd452-Ethernet3/1 | PASS | - |
| 446 | dc1p1_leaf1a_cal418 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet52/1 - dc1p1-Leaf1-Po1_Eth1/1 | PASS | - |
| 447 | dc1p1_leaf1a_cal418 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet55/1 - dc1p1-oob-spine_Eth25/1 | PASS | - |
| 448 | dc1p1_leaf1a_cal418 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet56/1 - dc1p1-oob-spine_Eth26/1 | PASS | - |
| 449 | dc1p1_leaf1b_cal419 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet53/1 - MLAG_PEER_dc1p1_leaf1a_cal418_Ethernet53/1 | PASS | - |
| 450 | dc1p1_leaf1b_cal419 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet54/1 - MLAG_PEER_dc1p1_leaf1a_cal418_Ethernet54/1 | PASS | - |
| 451 | dc1p1_leaf1b_cal419 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet49/1 - dc1p1_spine1_glf437-Ethernet3/2/1 | PASS | - |
| 452 | dc1p1_leaf1b_cal419 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet50/1 - dc1p1_spine2_btp454-Ethernet4/1 | PASS | - |
| 453 | dc1p1_leaf1b_cal419 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet51/1 - dc1p1_spine3_btd452-Ethernet4/1 | PASS | - |
| 454 | dc1p1_leaf1b_cal419 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet52/1 - dc1p1-Leaf1-Po1_Eth2/1 | PASS | - |
| 455 | dc1p1_leaf1b_cal419 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet55/1 - dc1p1-oob-spine_Eth25/1 | PASS | - |
| 456 | dc1p1_leaf1b_cal419 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet56/1 - dc1p1-oob-spine_Eth26/1 | PASS | - |
| 457 | dc1p1_leaf2b_cal422 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet53/1 - MLAG_PEER_dc1p1_leaf2a_cal421_Ethernet53/1 | PASS | - |
| 458 | dc1p1_leaf2b_cal422 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet54/1 - MLAG_PEER_dc1p1_leaf2a_cal421_Ethernet54/1 | PASS | - |
| 459 | dc1p1_leaf2b_cal422 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet49/1 - dc1p1_spine1_glf437-Ethernet3/4/1 | PASS | - |
| 460 | dc1p1_leaf2b_cal422 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet50/1 - dc1p1_spine2_btp454-Ethernet6/1 | PASS | - |
| 461 | dc1p1_leaf2b_cal422 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet51/1 - dc1p1_spine3_btd452-Ethernet6/1 | PASS | - |
| 462 | dc1p1_leaf2b_cal422 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet52/1 - dc1p1-Leaf2-Po1_Eth4/1 | PASS | - |
| 463 | dc1p1_leaf3a_smd554 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1/1 - MLAG_PEER_dc1p1_leaf3b_smd555_Ethernet1/1 | PASS | - |
| 464 | dc1p1_leaf3a_smd554 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2/1 - MLAG_PEER_dc1p1_leaf3b_smd555_Ethernet2/1 | PASS | - |
| 465 | dc1p1_leaf3a_smd554 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3/1 - MLAG_PEER_dc1p1_leaf3b_smd555_Ethernet3/1 | PASS | - |
| 466 | dc1p1_leaf3a_smd554 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4/1 - MLAG_PEER_dc1p1_leaf3b_smd555_Ethernet4/1 | PASS | - |
| 467 | dc1p1_leaf3a_smd554 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet33/1 - dc1p1_spine1_glf437-Ethernet4/1/1 | PASS | - |
| 468 | dc1p1_leaf3a_smd554 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet34/1 - dc1p1_spine2_btp454-Ethernet31/1 | PASS | - |
| 469 | dc1p1_leaf3a_smd554 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet35/1 - dc1p1_spine3_btd452-Ethernet31/1 | PASS | - |
| 470 | dc1p1_leaf3a_smd554 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5/1 - dc1p1-Leaf3-Po1_Eth5/1 | PASS | - |
| 471 | dc1p1_leaf3b_smd555 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1/1 - MLAG_PEER_dc1p1_leaf3a_smd554_Ethernet1/1 | PASS | - |
| 472 | dc1p1_leaf3b_smd555 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2/1 - MLAG_PEER_dc1p1_leaf3a_smd554_Ethernet2/1 | PASS | - |
| 473 | dc1p1_leaf3b_smd555 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3/1 - MLAG_PEER_dc1p1_leaf3a_smd554_Ethernet3/1 | PASS | - |
| 474 | dc1p1_leaf3b_smd555 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4/1 - MLAG_PEER_dc1p1_leaf3a_smd554_Ethernet4/1 | PASS | - |
| 475 | dc1p1_leaf3b_smd555 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet33/1 - dc1p1_spine1_glf437-Ethernet4/2/1 | PASS | - |
| 476 | dc1p1_leaf3b_smd555 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet34/1 - dc1p1_spine2_btp454-Ethernet32/1 | PASS | - |
| 477 | dc1p1_leaf3b_smd555 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet35/1 - dc1p1_spine3_btd452-Ethernet32/1 | PASS | - |
| 478 | dc1p1_leaf3b_smd555 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5/1 - dc1p1-Leaf3-Po1_Eth6/1 | PASS | - |
| 479 | dc1p2_leaf1_mrv453 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet49/1 - dc1p2_spine1_ghs253-Ethernet3/1 | PASS | - |
| 480 | dc1p2_leaf1_mrv453 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet50/1 - dc1p2_spine2_ghs278-Ethernet3/1 | PASS | - |
| 481 | dc1p2_leaf1_mrv453 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet51/1 - dc1p2_spine3_ghs281-Ethernet3/1 | PASS | - |
| 482 | dc1p2_leaf1_mrv453 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet52/1 - dc1p2-Leaf1-Po1_Eth1/1 | PASS | - |
| 483 | dc1p2_leaf2_gt272 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet49/1 - dc1p2_spine1_ghs253-Ethernet4/1 | PASS | - |
| 484 | dc1p2_leaf2_gt272 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet50/1 - dc1p2_spine2_ghs278-Ethernet4/1 | PASS | - |
| 485 | dc1p2_leaf2_gt272 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet51/1 - dc1p2_spine3_ghs281-Ethernet4/1 | PASS | - |
| 486 | dc1p2_leaf2_gt272 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet52/1 - dc1p2-Leaf2-Po1_Eth2/1 | PASS | - |
| 487 | dc1p2_spine2_ghs278 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3/1 - dc1p2_leaf1_mrv453-Ethernet50/1 | PASS | - |
| 488 | dc1p2_spine2_ghs278 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4/1 - dc1p2_leaf2_gt272-Ethernet50/1 | PASS | - |
| 489 | dc1p2_spine2_ghs278 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1/1 - P2P_LINK_TO_dc1p1_spine2_btp454_Ethernet1/1 | PASS | - |
| 490 | dc1p2_spine2_ghs278 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2/1 - P2P_LINK_TO_dc2p1_spine2_ghs283_Ethernet2/1 | PASS | - |
| 491 | dc1p2_spine3_ghs281 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3/1 - dc1p2_leaf1_mrv453-Ethernet51/1 | PASS | - |
| 492 | dc1p2_spine3_ghs281 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4/1 - dc1p2_leaf2_gt272-Ethernet51/1 | PASS | - |
| 493 | dc1p2_spine3_ghs281 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1/1 - P2P_LINK_TO_dc1p1_spine3_btd452_Ethernet1/1 | PASS | - |
| 494 | dc1p2_spine3_ghs281 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2/1 - P2P_LINK_TO_dc2p1_spine3_ghs284_Ethernet2/1 | PASS | - |
| 495 | dc2p1_leaf1a_mrv305 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet53/1 - MLAG_PEER_dc2p1_leaf1b_mrv306_Ethernet53/1 | PASS | - |
| 496 | dc2p1_leaf1a_mrv305 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet54/1 - MLAG_PEER_dc2p1_leaf1b_mrv306_Ethernet54/1 | PASS | - |
| 497 | dc2p1_leaf1a_mrv305 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet49/1 - dc2p1_spine1_ghs282-Ethernet3/1 | PASS | - |
| 498 | dc2p1_leaf1a_mrv305 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet50/1 - dc2p1_spine2_ghs283-Ethernet3/1 | PASS | - |
| 499 | dc2p1_leaf1a_mrv305 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet51/1 - dc2p1_spine3_ghs284-Ethernet3/1 | PASS | - |
| 500 | dc2p1_leaf1a_mrv305 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet52/1 - dc2p1-leaf1-Po1_Eth1/1 | PASS | - |
| 501 | dc2p1_leaf1a_mrv305 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - dc2p1-cisco-interop_Eth1/2 | PASS | - |
| 502 | dc2p1_leaf1b_mrv306 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet53/1 - MLAG_PEER_dc2p1_leaf1a_mrv305_Ethernet53/1 | PASS | - |
| 503 | dc2p1_leaf1b_mrv306 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet54/1 - MLAG_PEER_dc2p1_leaf1a_mrv305_Ethernet54/1 | PASS | - |
| 504 | dc2p1_leaf1b_mrv306 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet49/1 - dc2p1_spine1_ghs282-Ethernet4/1 | PASS | - |
| 505 | dc2p1_leaf1b_mrv306 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet50/1 - dc2p1_spine2_ghs283-Ethernet4/1 | PASS | - |
| 506 | dc2p1_leaf1b_mrv306 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet51/1 - dc2p1_spine3_ghs284-Ethernet4/1 | PASS | - |
| 507 | dc2p1_leaf1b_mrv306 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet52/1 - dc2p1-leaf1-Po1_Eth2/1 | PASS | - |
| 508 | dc2p1_leaf1b_mrv306 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - dc2p1-cisco-interop_Eth1/3 | PASS | - |
| 509 | dc2p1_spine2_ghs283 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3/1 - dc2p1_leaf1a_mrv305-Ethernet50/1 | PASS | - |
| 510 | dc2p1_spine2_ghs283 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4/1 - dc2p1_leaf1b_mrv306-Ethernet50/1 | PASS | - |
| 511 | dc2p1_spine2_ghs283 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6/1 - dc2p1_sleaf_gt407-Ethernet50/1 | PASS | - |
| 512 | dc2p1_spine2_ghs283 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1/1 - P2P_LINK_TO_dc1p1_spine2_btp454_Ethernet2/1 | PASS | - |
| 513 | dc2p1_spine2_ghs283 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2/1 - P2P_LINK_TO_dc1p2_spine2_ghs278_Ethernet2/1 | PASS | - |
| 514 | dc2p1_spine3_ghs284 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3/1 - dc2p1_leaf1a_mrv305-Ethernet51/1 | PASS | - |
| 515 | dc2p1_spine3_ghs284 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4/1 - dc2p1_leaf1b_mrv306-Ethernet51/1 | PASS | - |
| 516 | dc2p1_spine3_ghs284 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6/1 - dc2p1_sleaf_gt407-Ethernet51/1 | PASS | - |
| 517 | dc2p1_spine3_ghs284 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1/1 - P2P_LINK_TO_dc1p1_spine3_btd452_Ethernet2/1 | PASS | - |
| 518 | dc2p1_spine3_ghs284 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2/1 - P2P_LINK_TO_dc1p2_spine3_ghs281_Ethernet2/1 | PASS | - |
| 519 | dc1p1_leaf1a_cal418 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel531 - MLAG_PEER_dc1p1_leaf1b_cal419_Po531 | PASS | - |
| 520 | dc1p1_leaf1a_cal418 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel521 - dc1p1-Leaf1-Po1_dc1p1-Harness1-PO1 | PASS | - |
| 521 | dc1p1_leaf1a_cal418 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel551 - dc1p1-oob-spine_oob-spines | PASS | - |
| 522 | dc1p1_leaf1b_cal419 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel531 - MLAG_PEER_dc1p1_leaf1a_cal418_Po531 | PASS | - |
| 523 | dc1p1_leaf1b_cal419 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel521 - dc1p1-Leaf1-Po1_dc1p1-Harness1-PO1 | PASS | - |
| 524 | dc1p1_leaf1b_cal419 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel551 - dc1p1-oob-spine_oob-spines | PASS | - |
| 525 | dc1p1_leaf2a_cal421 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel531 - MLAG_PEER_dc1p1_leaf2b_cal422_Po531 | PASS | - |
| 526 | dc1p1_leaf2a_cal421 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel551 - dc1p1-Leaf2-Po1_dc1p1-Harness1-PO2 | PASS | - |
| 527 | dc1p1_leaf2b_cal422 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel531 - MLAG_PEER_dc1p1_leaf2a_cal421_Po531 | PASS | - |
| 528 | dc1p1_leaf2b_cal422 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel551 - dc1p1-Leaf2-Po1_dc1p1-Harness1-PO2 | PASS | - |
| 529 | dc1p1_leaf3a_smd554 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel11 - MLAG_PEER_dc1p1_leaf3b_smd555_Po11 | PASS | - |
| 530 | dc1p1_leaf3a_smd554 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel51 - dc1p1-Leaf3-Po1_dc1p1-Harness1-PO3 | PASS | - |
| 531 | dc1p1_leaf3b_smd555 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel11 - MLAG_PEER_dc1p1_leaf3a_smd554_Po11 | PASS | - |
| 532 | dc1p1_leaf3b_smd555 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel51 - dc1p1-Leaf3-Po1_dc1p1-Harness1-PO3 | PASS | - |
| 533 | dc1p2_leaf1_mrv453 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel521 - dc1p2-Leaf1-Po1_dc1p2-Harness1-PO1 | PASS | - |
| 534 | dc1p2_leaf2_gt272 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel521 - dc1p2-Leaf2-Po1_dc1p2-Harness1-PO2 | PASS | - |
| 535 | dc2p1_leaf1a_mrv305 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel531 - MLAG_PEER_dc2p1_leaf1b_mrv306_Po531 | PASS | - |
| 536 | dc2p1_leaf1a_mrv305 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel521 - dc2p1-leaf1-Po1_dc2p1-Harness1-PO1 | PASS | - |
| 537 | dc2p1_leaf1a_mrv305 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - dc2p1-cisco-interop_cisco_dut332 | PASS | - |
| 538 | dc2p1_leaf1b_mrv306 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel531 - MLAG_PEER_dc2p1_leaf1a_mrv305_Po531 | PASS | - |
| 539 | dc2p1_leaf1b_mrv306 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel521 - dc2p1-leaf1-Po1_dc2p1-Harness1-PO1 | PASS | - |
| 540 | dc2p1_leaf1b_mrv306 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - dc2p1-cisco-interop_cisco_dut332 | PASS | - |
| 541 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 542 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 543 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan101 - com-vrf | PASS | - |
| 544 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan102 - com-vrf | PASS | - |
| 545 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan103 - com-vrf | PASS | - |
| 546 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan104 - com-vrf | PASS | - |
| 547 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan105 - com-vrf | PASS | - |
| 548 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan106 - com-vrf | PASS | - |
| 549 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan107 - com-vrf | PASS | - |
| 550 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan108 - com-vrf | PASS | - |
| 551 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan109 - com-vrf | PASS | - |
| 552 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - com-vrf | PASS | - |
| 553 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan111 - com-vrf | PASS | - |
| 554 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan112 - com-vrf | PASS | - |
| 555 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan113 - com-vrf | PASS | - |
| 556 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan114 - com-vrf | PASS | - |
| 557 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan115 - com-vrf | PASS | - |
| 558 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan116 - com-vrf | PASS | - |
| 559 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan117 - com-vrf | PASS | - |
| 560 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan118 - com-vrf | PASS | - |
| 561 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan119 - com-vrf | PASS | - |
| 562 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - com-vrf | PASS | - |
| 563 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan121 - com-vrf | PASS | - |
| 564 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan122 - com-vrf | PASS | - |
| 565 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan123 - com-vrf | PASS | - |
| 566 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan124 - com-vrf | PASS | - |
| 567 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan125 - com-vrf | PASS | - |
| 568 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan126 - com-vrf | PASS | - |
| 569 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan127 - com-vrf | PASS | - |
| 570 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan128 - com-vrf | PASS | - |
| 571 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan129 - com-vrf | PASS | - |
| 572 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan130 - com-vrf | PASS | - |
| 573 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan131 - com-vrf | PASS | - |
| 574 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan132 - com-vrf | PASS | - |
| 575 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan133 - com-vrf | PASS | - |
| 576 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan134 - com-vrf | PASS | - |
| 577 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan135 - com-vrf | PASS | - |
| 578 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan136 - com-vrf | PASS | - |
| 579 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan137 - com-vrf | PASS | - |
| 580 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan138 - com-vrf | PASS | - |
| 581 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan139 - com-vrf | PASS | - |
| 582 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan140 - com-vrf | PASS | - |
| 583 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan141 - com-vrf | PASS | - |
| 584 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan142 - com-vrf | PASS | - |
| 585 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan143 - com-vrf | PASS | - |
| 586 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan144 - com-vrf | PASS | - |
| 587 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan145 - com-vrf | PASS | - |
| 588 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan146 - com-vrf | PASS | - |
| 589 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan147 - com-vrf | PASS | - |
| 590 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan148 - com-vrf | PASS | - |
| 591 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan149 - com-vrf | PASS | - |
| 592 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan150 - com-vrf | PASS | - |
| 593 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan151 - com-vrf | PASS | - |
| 594 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan152 - com-vrf | PASS | - |
| 595 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan153 - com-vrf | PASS | - |
| 596 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan154 - com-vrf | PASS | - |
| 597 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan155 - com-vrf | PASS | - |
| 598 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan156 - com-vrf | PASS | - |
| 599 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan157 - com-vrf | PASS | - |
| 600 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan158 - com-vrf | PASS | - |
| 601 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan159 - com-vrf | PASS | - |
| 602 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan160 - com-vrf | PASS | - |
| 603 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan161 - com-vrf | PASS | - |
| 604 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan162 - com-vrf | PASS | - |
| 605 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan163 - com-vrf | PASS | - |
| 606 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan164 - com-vrf | PASS | - |
| 607 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan165 - com-vrf | PASS | - |
| 608 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan166 - com-vrf | PASS | - |
| 609 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan167 - com-vrf | PASS | - |
| 610 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan168 - com-vrf | PASS | - |
| 611 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan169 - com-vrf | PASS | - |
| 612 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan170 - com-vrf | PASS | - |
| 613 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan171 - com-vrf | PASS | - |
| 614 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan172 - com-vrf | PASS | - |
| 615 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan173 - com-vrf | PASS | - |
| 616 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan174 - com-vrf | PASS | - |
| 617 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan175 - com-vrf | PASS | - |
| 618 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan176 - com-vrf | PASS | - |
| 619 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan177 - com-vrf | PASS | - |
| 620 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan178 - com-vrf | PASS | - |
| 621 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan179 - com-vrf | PASS | - |
| 622 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan180 - com-vrf | PASS | - |
| 623 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan181 - com-vrf | PASS | - |
| 624 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan182 - com-vrf | PASS | - |
| 625 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan183 - com-vrf | PASS | - |
| 626 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan184 - com-vrf | PASS | - |
| 627 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan185 - com-vrf | PASS | - |
| 628 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan186 - com-vrf | PASS | - |
| 629 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan187 - com-vrf | PASS | - |
| 630 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan188 - com-vrf | PASS | - |
| 631 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan189 - com-vrf | PASS | - |
| 632 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan190 - com-vrf | PASS | - |
| 633 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan191 - com-vrf | PASS | - |
| 634 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan192 - com-vrf | PASS | - |
| 635 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan193 - com-vrf | PASS | - |
| 636 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan194 - com-vrf | PASS | - |
| 637 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan195 - com-vrf | PASS | - |
| 638 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan196 - com-vrf | PASS | - |
| 639 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan197 - com-vrf | PASS | - |
| 640 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan198 - com-vrf | PASS | - |
| 641 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan199 - com-vrf | PASS | - |
| 642 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan200 - com-vrf | PASS | - |
| 643 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan201 - com-vrf | PASS | - |
| 644 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan202 - com-vrf | PASS | - |
| 645 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan203 - com-vrf | PASS | - |
| 646 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan204 - com-vrf | PASS | - |
| 647 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan205 - com-vrf | PASS | - |
| 648 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan206 - com-vrf | PASS | - |
| 649 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan207 - com-vrf | PASS | - |
| 650 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan208 - com-vrf | PASS | - |
| 651 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan209 - com-vrf | PASS | - |
| 652 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan210 - com-vrf | PASS | - |
| 653 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan211 - com-vrf | PASS | - |
| 654 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan212 - com-vrf | PASS | - |
| 655 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan213 - com-vrf | PASS | - |
| 656 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan214 - com-vrf | PASS | - |
| 657 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan215 - com-vrf | PASS | - |
| 658 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan216 - com-vrf | PASS | - |
| 659 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan217 - com-vrf | PASS | - |
| 660 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan218 - com-vrf | PASS | - |
| 661 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan219 - com-vrf | PASS | - |
| 662 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan220 - com-vrf | PASS | - |
| 663 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan221 - com-vrf | PASS | - |
| 664 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan222 - com-vrf | PASS | - |
| 665 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan223 - com-vrf | PASS | - |
| 666 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan224 - com-vrf | PASS | - |
| 667 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan225 - com-vrf | PASS | - |
| 668 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan226 - com-vrf | PASS | - |
| 669 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan227 - com-vrf | PASS | - |
| 670 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan228 - com-vrf | PASS | - |
| 671 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan229 - com-vrf | PASS | - |
| 672 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan230 - com-vrf | PASS | - |
| 673 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan231 - com-vrf | PASS | - |
| 674 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan232 - com-vrf | PASS | - |
| 675 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan233 - com-vrf | PASS | - |
| 676 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan234 - com-vrf | PASS | - |
| 677 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan235 - com-vrf | PASS | - |
| 678 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan236 - com-vrf | PASS | - |
| 679 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan237 - com-vrf | PASS | - |
| 680 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan238 - com-vrf | PASS | - |
| 681 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan239 - com-vrf | PASS | - |
| 682 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan240 - com-vrf | PASS | - |
| 683 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan241 - com-vrf | PASS | - |
| 684 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan242 - com-vrf | PASS | - |
| 685 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan243 - com-vrf | PASS | - |
| 686 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan244 - com-vrf | PASS | - |
| 687 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan245 - com-vrf | PASS | - |
| 688 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan246 - com-vrf | PASS | - |
| 689 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan247 - com-vrf | PASS | - |
| 690 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan248 - com-vrf | PASS | - |
| 691 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan249 - com-vrf | PASS | - |
| 692 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan250 - com-vrf | PASS | - |
| 693 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan251 - com-vrf | PASS | - |
| 694 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan252 - com-vrf | PASS | - |
| 695 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan253 - com-vrf | PASS | - |
| 696 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan254 - com-vrf | PASS | - |
| 697 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan255 - com-vrf | PASS | - |
| 698 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan256 - com-vrf | PASS | - |
| 699 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan257 - com-vrf | PASS | - |
| 700 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan258 - com-vrf | PASS | - |
| 701 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan259 - com-vrf | PASS | - |
| 702 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan260 - com-vrf | PASS | - |
| 703 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan261 - com-vrf | PASS | - |
| 704 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan262 - com-vrf | PASS | - |
| 705 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan263 - com-vrf | PASS | - |
| 706 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan264 - com-vrf | PASS | - |
| 707 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan265 - com-vrf | PASS | - |
| 708 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan266 - com-vrf | PASS | - |
| 709 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan267 - com-vrf | PASS | - |
| 710 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan268 - com-vrf | PASS | - |
| 711 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan269 - com-vrf | PASS | - |
| 712 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan270 - com-vrf | PASS | - |
| 713 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan271 - com-vrf | PASS | - |
| 714 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan272 - com-vrf | PASS | - |
| 715 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan273 - com-vrf | PASS | - |
| 716 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan274 - com-vrf | PASS | - |
| 717 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan275 - com-vrf | PASS | - |
| 718 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan276 - com-vrf | PASS | - |
| 719 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan277 - com-vrf | PASS | - |
| 720 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan278 - com-vrf | PASS | - |
| 721 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan279 - com-vrf | PASS | - |
| 722 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan280 - com-vrf | PASS | - |
| 723 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan281 - com-vrf | PASS | - |
| 724 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan282 - com-vrf | PASS | - |
| 725 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan283 - com-vrf | PASS | - |
| 726 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan284 - com-vrf | PASS | - |
| 727 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan285 - com-vrf | PASS | - |
| 728 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan286 - com-vrf | PASS | - |
| 729 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan287 - com-vrf | PASS | - |
| 730 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan288 - com-vrf | PASS | - |
| 731 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan289 - com-vrf | PASS | - |
| 732 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan290 - com-vrf | PASS | - |
| 733 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan291 - com-vrf | PASS | - |
| 734 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan292 - com-vrf | PASS | - |
| 735 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan293 - com-vrf | PASS | - |
| 736 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan294 - com-vrf | PASS | - |
| 737 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan295 - com-vrf | PASS | - |
| 738 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan296 - com-vrf | PASS | - |
| 739 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan297 - com-vrf | PASS | - |
| 740 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan298 - com-vrf | PASS | - |
| 741 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan299 - com-vrf | PASS | - |
| 742 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan300 - com-vrf | PASS | - |
| 743 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan301 - com-vrf | PASS | - |
| 744 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan302 - com-vrf | PASS | - |
| 745 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan303 - com-vrf | PASS | - |
| 746 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan304 - com-vrf | PASS | - |
| 747 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan305 - com-vrf | PASS | - |
| 748 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan306 - com-vrf | PASS | - |
| 749 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan307 - com-vrf | PASS | - |
| 750 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan308 - com-vrf | PASS | - |
| 751 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan309 - com-vrf | PASS | - |
| 752 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan310 - com-vrf | PASS | - |
| 753 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan311 - com-vrf | PASS | - |
| 754 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan312 - com-vrf | PASS | - |
| 755 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan313 - com-vrf | PASS | - |
| 756 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan314 - com-vrf | PASS | - |
| 757 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan315 - com-vrf | PASS | - |
| 758 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan316 - com-vrf | PASS | - |
| 759 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan317 - com-vrf | PASS | - |
| 760 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan318 - com-vrf | PASS | - |
| 761 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan319 - com-vrf | PASS | - |
| 762 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan320 - com-vrf | PASS | - |
| 763 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan321 - com-vrf | PASS | - |
| 764 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan322 - com-vrf | PASS | - |
| 765 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan323 - com-vrf | PASS | - |
| 766 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan324 - com-vrf | PASS | - |
| 767 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan325 - com-vrf | PASS | - |
| 768 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan326 - com-vrf | PASS | - |
| 769 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan327 - com-vrf | PASS | - |
| 770 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan328 - com-vrf | PASS | - |
| 771 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan329 - com-vrf | PASS | - |
| 772 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan330 - com-vrf | PASS | - |
| 773 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan331 - com-vrf | PASS | - |
| 774 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan332 - com-vrf | PASS | - |
| 775 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan333 - com-vrf | PASS | - |
| 776 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan334 - com-vrf | PASS | - |
| 777 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan335 - com-vrf | PASS | - |
| 778 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan336 - com-vrf | PASS | - |
| 779 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan337 - com-vrf | PASS | - |
| 780 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan338 - com-vrf | PASS | - |
| 781 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan339 - com-vrf | PASS | - |
| 782 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan340 - com-vrf | PASS | - |
| 783 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan341 - com-vrf | PASS | - |
| 784 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan342 - com-vrf | PASS | - |
| 785 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan343 - com-vrf | PASS | - |
| 786 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan344 - com-vrf | PASS | - |
| 787 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan345 - com-vrf | PASS | - |
| 788 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan346 - com-vrf | PASS | - |
| 789 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan347 - com-vrf | PASS | - |
| 790 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan348 - com-vrf | PASS | - |
| 791 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan349 - com-vrf | PASS | - |
| 792 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan350 - com-vrf | PASS | - |
| 793 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan351 - com-vrf | PASS | - |
| 794 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan352 - com-vrf | PASS | - |
| 795 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan353 - com-vrf | PASS | - |
| 796 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan354 - com-vrf | PASS | - |
| 797 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan355 - com-vrf | PASS | - |
| 798 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan356 - com-vrf | PASS | - |
| 799 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan357 - com-vrf | PASS | - |
| 800 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan358 - com-vrf | PASS | - |
| 801 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan359 - com-vrf | PASS | - |
| 802 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan360 - com-vrf | PASS | - |
| 803 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan361 - com-vrf | PASS | - |
| 804 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan362 - com-vrf | PASS | - |
| 805 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan363 - com-vrf | PASS | - |
| 806 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan364 - com-vrf | PASS | - |
| 807 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan365 - com-vrf | PASS | - |
| 808 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan366 - com-vrf | PASS | - |
| 809 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan367 - com-vrf | PASS | - |
| 810 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan368 - com-vrf | PASS | - |
| 811 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan369 - com-vrf | PASS | - |
| 812 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan370 - com-vrf | PASS | - |
| 813 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan371 - com-vrf | PASS | - |
| 814 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan372 - com-vrf | PASS | - |
| 815 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan373 - com-vrf | PASS | - |
| 816 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan374 - com-vrf | PASS | - |
| 817 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan375 - com-vrf | PASS | - |
| 818 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan376 - com-vrf | PASS | - |
| 819 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan377 - com-vrf | PASS | - |
| 820 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan378 - com-vrf | PASS | - |
| 821 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan379 - com-vrf | PASS | - |
| 822 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan380 - com-vrf | PASS | - |
| 823 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan381 - com-vrf | PASS | - |
| 824 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan382 - com-vrf | PASS | - |
| 825 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan383 - com-vrf | PASS | - |
| 826 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan384 - com-vrf | PASS | - |
| 827 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan385 - com-vrf | PASS | - |
| 828 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan386 - com-vrf | PASS | - |
| 829 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan387 - com-vrf | PASS | - |
| 830 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan388 - com-vrf | PASS | - |
| 831 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan389 - com-vrf | PASS | - |
| 832 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan390 - com-vrf | PASS | - |
| 833 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan391 - com-vrf | PASS | - |
| 834 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan392 - com-vrf | PASS | - |
| 835 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan393 - com-vrf | PASS | - |
| 836 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan394 - com-vrf | PASS | - |
| 837 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan395 - com-vrf | PASS | - |
| 838 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan396 - com-vrf | PASS | - |
| 839 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan397 - com-vrf | PASS | - |
| 840 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan398 - com-vrf | PASS | - |
| 841 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan399 - com-vrf | PASS | - |
| 842 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan400 - com-vrf | PASS | - |
| 843 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan401 - com-vrf | PASS | - |
| 844 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan402 - com-vrf | PASS | - |
| 845 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan403 - com-vrf | PASS | - |
| 846 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan404 - com-vrf | PASS | - |
| 847 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan405 - com-vrf | PASS | - |
| 848 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan406 - com-vrf | PASS | - |
| 849 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan407 - com-vrf | PASS | - |
| 850 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan408 - com-vrf | PASS | - |
| 851 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan409 - com-vrf | PASS | - |
| 852 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan410 - com-vrf | PASS | - |
| 853 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan411 - com-vrf | PASS | - |
| 854 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan412 - com-vrf | PASS | - |
| 855 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan413 - com-vrf | PASS | - |
| 856 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan414 - com-vrf | PASS | - |
| 857 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan415 - com-vrf | PASS | - |
| 858 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan416 - com-vrf | PASS | - |
| 859 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan417 - com-vrf | PASS | - |
| 860 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan418 - com-vrf | PASS | - |
| 861 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan419 - com-vrf | PASS | - |
| 862 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan420 - com-vrf | PASS | - |
| 863 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan421 - com-vrf | PASS | - |
| 864 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan422 - com-vrf | PASS | - |
| 865 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan423 - com-vrf | PASS | - |
| 866 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan424 - com-vrf | PASS | - |
| 867 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan425 - com-vrf | PASS | - |
| 868 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan426 - com-vrf | PASS | - |
| 869 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan427 - com-vrf | PASS | - |
| 870 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan428 - com-vrf | PASS | - |
| 871 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan429 - com-vrf | PASS | - |
| 872 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan430 - com-vrf | PASS | - |
| 873 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan431 - com-vrf | PASS | - |
| 874 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan432 - com-vrf | PASS | - |
| 875 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan433 - com-vrf | PASS | - |
| 876 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan434 - com-vrf | PASS | - |
| 877 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan435 - com-vrf | PASS | - |
| 878 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan436 - com-vrf | PASS | - |
| 879 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan437 - com-vrf | PASS | - |
| 880 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan438 - com-vrf | PASS | - |
| 881 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan439 - com-vrf | PASS | - |
| 882 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan440 - com-vrf | PASS | - |
| 883 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan441 - com-vrf | PASS | - |
| 884 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan442 - com-vrf | PASS | - |
| 885 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan443 - com-vrf | PASS | - |
| 886 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan444 - com-vrf | PASS | - |
| 887 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan445 - com-vrf | PASS | - |
| 888 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan446 - com-vrf | PASS | - |
| 889 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan447 - com-vrf | PASS | - |
| 890 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan448 - com-vrf | PASS | - |
| 891 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan449 - com-vrf | PASS | - |
| 892 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan450 - com-vrf | PASS | - |
| 893 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4050 - MLAG_PEER_L3_iBGP: vrf com | PASS | - |
| 894 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2001 - sec-vrf | PASS | - |
| 895 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2002 - sec-vrf | PASS | - |
| 896 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2003 - sec-vrf | PASS | - |
| 897 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2004 - sec-vrf | PASS | - |
| 898 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2005 - sec-vrf | PASS | - |
| 899 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2006 - sec-vrf | PASS | - |
| 900 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2007 - sec-vrf | PASS | - |
| 901 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2008 - sec-vrf | PASS | - |
| 902 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2009 - sec-vrf | PASS | - |
| 903 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2010 - sec-vrf | PASS | - |
| 904 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2011 - sec-vrf | PASS | - |
| 905 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2012 - sec-vrf | PASS | - |
| 906 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2013 - sec-vrf | PASS | - |
| 907 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2014 - sec-vrf | PASS | - |
| 908 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2015 - sec-vrf | PASS | - |
| 909 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2016 - sec-vrf | PASS | - |
| 910 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2017 - sec-vrf | PASS | - |
| 911 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2018 - sec-vrf | PASS | - |
| 912 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2019 - sec-vrf | PASS | - |
| 913 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2020 - sec-vrf | PASS | - |
| 914 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2021 - sec-vrf | PASS | - |
| 915 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2022 - sec-vrf | PASS | - |
| 916 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2023 - sec-vrf | PASS | - |
| 917 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2024 - sec-vrf | PASS | - |
| 918 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2025 - sec-vrf | PASS | - |
| 919 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2026 - sec-vrf | PASS | - |
| 920 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2027 - sec-vrf | PASS | - |
| 921 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2028 - sec-vrf | PASS | - |
| 922 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2029 - sec-vrf | PASS | - |
| 923 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2030 - sec-vrf | PASS | - |
| 924 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2031 - sec-vrf | PASS | - |
| 925 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2032 - sec-vrf | PASS | - |
| 926 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2033 - sec-vrf | PASS | - |
| 927 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2034 - sec-vrf | PASS | - |
| 928 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2035 - sec-vrf | PASS | - |
| 929 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2036 - sec-vrf | PASS | - |
| 930 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2037 - sec-vrf | PASS | - |
| 931 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2038 - sec-vrf | PASS | - |
| 932 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2039 - sec-vrf | PASS | - |
| 933 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2040 - sec-vrf | PASS | - |
| 934 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2041 - sec-vrf | PASS | - |
| 935 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2042 - sec-vrf | PASS | - |
| 936 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2043 - sec-vrf | PASS | - |
| 937 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2044 - sec-vrf | PASS | - |
| 938 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2045 - sec-vrf | PASS | - |
| 939 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2046 - sec-vrf | PASS | - |
| 940 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2047 - sec-vrf | PASS | - |
| 941 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2048 - sec-vrf | PASS | - |
| 942 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2049 - sec-vrf | PASS | - |
| 943 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2050 - sec-vrf | PASS | - |
| 944 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2051 - sec-vrf | PASS | - |
| 945 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2052 - sec-vrf | PASS | - |
| 946 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2053 - sec-vrf | PASS | - |
| 947 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2054 - sec-vrf | PASS | - |
| 948 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2055 - sec-vrf | PASS | - |
| 949 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2056 - sec-vrf | PASS | - |
| 950 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2057 - sec-vrf | PASS | - |
| 951 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2058 - sec-vrf | PASS | - |
| 952 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2059 - sec-vrf | PASS | - |
| 953 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2060 - sec-vrf | PASS | - |
| 954 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2061 - sec-vrf | PASS | - |
| 955 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2062 - sec-vrf | PASS | - |
| 956 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2063 - sec-vrf | PASS | - |
| 957 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2064 - sec-vrf | PASS | - |
| 958 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2065 - sec-vrf | PASS | - |
| 959 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2066 - sec-vrf | PASS | - |
| 960 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2067 - sec-vrf | PASS | - |
| 961 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2068 - sec-vrf | PASS | - |
| 962 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2069 - sec-vrf | PASS | - |
| 963 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2070 - sec-vrf | PASS | - |
| 964 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2071 - sec-vrf | PASS | - |
| 965 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2072 - sec-vrf | PASS | - |
| 966 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2073 - sec-vrf | PASS | - |
| 967 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2074 - sec-vrf | PASS | - |
| 968 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2075 - sec-vrf | PASS | - |
| 969 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2076 - sec-vrf | PASS | - |
| 970 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2077 - sec-vrf | PASS | - |
| 971 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2078 - sec-vrf | PASS | - |
| 972 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2079 - sec-vrf | PASS | - |
| 973 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2080 - sec-vrf | PASS | - |
| 974 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2081 - sec-vrf | PASS | - |
| 975 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2082 - sec-vrf | PASS | - |
| 976 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2083 - sec-vrf | PASS | - |
| 977 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2084 - sec-vrf | PASS | - |
| 978 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2085 - sec-vrf | PASS | - |
| 979 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2086 - sec-vrf | PASS | - |
| 980 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2087 - sec-vrf | PASS | - |
| 981 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2088 - sec-vrf | PASS | - |
| 982 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2089 - sec-vrf | PASS | - |
| 983 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2090 - sec-vrf | PASS | - |
| 984 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2091 - sec-vrf | PASS | - |
| 985 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2092 - sec-vrf | PASS | - |
| 986 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2093 - sec-vrf | PASS | - |
| 987 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2094 - sec-vrf | PASS | - |
| 988 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2095 - sec-vrf | PASS | - |
| 989 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2096 - sec-vrf | PASS | - |
| 990 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2097 - sec-vrf | PASS | - |
| 991 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2098 - sec-vrf | PASS | - |
| 992 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2099 - sec-vrf | PASS | - |
| 993 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2100 - sec-vrf | PASS | - |
| 994 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2101 - sec-vrf | PASS | - |
| 995 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2102 - sec-vrf | PASS | - |
| 996 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2103 - sec-vrf | PASS | - |
| 997 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2104 - sec-vrf | PASS | - |
| 998 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2105 - sec-vrf | PASS | - |
| 999 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2106 - sec-vrf | PASS | - |
| 1000 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2107 - sec-vrf | PASS | - |
| 1001 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2108 - sec-vrf | PASS | - |
| 1002 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2109 - sec-vrf | PASS | - |
| 1003 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2110 - sec-vrf | PASS | - |
| 1004 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2111 - sec-vrf | PASS | - |
| 1005 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2112 - sec-vrf | PASS | - |
| 1006 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2113 - sec-vrf | PASS | - |
| 1007 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2114 - sec-vrf | PASS | - |
| 1008 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2115 - sec-vrf | PASS | - |
| 1009 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2116 - sec-vrf | PASS | - |
| 1010 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2117 - sec-vrf | PASS | - |
| 1011 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2118 - sec-vrf | PASS | - |
| 1012 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2119 - sec-vrf | PASS | - |
| 1013 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2120 - sec-vrf | PASS | - |
| 1014 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2121 - sec-vrf | PASS | - |
| 1015 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2122 - sec-vrf | PASS | - |
| 1016 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2123 - sec-vrf | PASS | - |
| 1017 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2124 - sec-vrf | PASS | - |
| 1018 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2125 - sec-vrf | PASS | - |
| 1019 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2126 - sec-vrf | PASS | - |
| 1020 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2127 - sec-vrf | PASS | - |
| 1021 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2128 - sec-vrf | PASS | - |
| 1022 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2129 - sec-vrf | PASS | - |
| 1023 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2130 - sec-vrf | PASS | - |
| 1024 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2131 - sec-vrf | PASS | - |
| 1025 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2132 - sec-vrf | PASS | - |
| 1026 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2133 - sec-vrf | PASS | - |
| 1027 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2134 - sec-vrf | PASS | - |
| 1028 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2135 - sec-vrf | PASS | - |
| 1029 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2136 - sec-vrf | PASS | - |
| 1030 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2137 - sec-vrf | PASS | - |
| 1031 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2138 - sec-vrf | PASS | - |
| 1032 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2139 - sec-vrf | PASS | - |
| 1033 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2140 - sec-vrf | PASS | - |
| 1034 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2141 - sec-vrf | PASS | - |
| 1035 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2142 - sec-vrf | PASS | - |
| 1036 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2143 - sec-vrf | PASS | - |
| 1037 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2144 - sec-vrf | PASS | - |
| 1038 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2145 - sec-vrf | PASS | - |
| 1039 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2146 - sec-vrf | PASS | - |
| 1040 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2147 - sec-vrf | PASS | - |
| 1041 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2148 - sec-vrf | PASS | - |
| 1042 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2149 - sec-vrf | PASS | - |
| 1043 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2150 - sec-vrf | PASS | - |
| 1044 | dc1p1_leaf1a_cal418 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4051 - MLAG_PEER_L3_iBGP: vrf sec | PASS | - |
| 1045 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 1046 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 1047 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan101 - com-vrf | PASS | - |
| 1048 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan102 - com-vrf | PASS | - |
| 1049 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan103 - com-vrf | PASS | - |
| 1050 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan104 - com-vrf | PASS | - |
| 1051 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan105 - com-vrf | PASS | - |
| 1052 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan106 - com-vrf | PASS | - |
| 1053 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan107 - com-vrf | PASS | - |
| 1054 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan108 - com-vrf | PASS | - |
| 1055 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan109 - com-vrf | PASS | - |
| 1056 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - com-vrf | PASS | - |
| 1057 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan111 - com-vrf | PASS | - |
| 1058 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan112 - com-vrf | PASS | - |
| 1059 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan113 - com-vrf | PASS | - |
| 1060 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan114 - com-vrf | PASS | - |
| 1061 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan115 - com-vrf | PASS | - |
| 1062 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan116 - com-vrf | PASS | - |
| 1063 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan117 - com-vrf | PASS | - |
| 1064 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan118 - com-vrf | PASS | - |
| 1065 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan119 - com-vrf | PASS | - |
| 1066 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - com-vrf | PASS | - |
| 1067 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan121 - com-vrf | PASS | - |
| 1068 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan122 - com-vrf | PASS | - |
| 1069 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan123 - com-vrf | PASS | - |
| 1070 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan124 - com-vrf | PASS | - |
| 1071 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan125 - com-vrf | PASS | - |
| 1072 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan126 - com-vrf | PASS | - |
| 1073 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan127 - com-vrf | PASS | - |
| 1074 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan128 - com-vrf | PASS | - |
| 1075 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan129 - com-vrf | PASS | - |
| 1076 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan130 - com-vrf | PASS | - |
| 1077 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan131 - com-vrf | PASS | - |
| 1078 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan132 - com-vrf | PASS | - |
| 1079 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan133 - com-vrf | PASS | - |
| 1080 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan134 - com-vrf | PASS | - |
| 1081 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan135 - com-vrf | PASS | - |
| 1082 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan136 - com-vrf | PASS | - |
| 1083 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan137 - com-vrf | PASS | - |
| 1084 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan138 - com-vrf | PASS | - |
| 1085 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan139 - com-vrf | PASS | - |
| 1086 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan140 - com-vrf | PASS | - |
| 1087 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan141 - com-vrf | PASS | - |
| 1088 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan142 - com-vrf | PASS | - |
| 1089 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan143 - com-vrf | PASS | - |
| 1090 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan144 - com-vrf | PASS | - |
| 1091 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan145 - com-vrf | PASS | - |
| 1092 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan146 - com-vrf | PASS | - |
| 1093 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan147 - com-vrf | PASS | - |
| 1094 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan148 - com-vrf | PASS | - |
| 1095 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan149 - com-vrf | PASS | - |
| 1096 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan150 - com-vrf | PASS | - |
| 1097 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan151 - com-vrf | PASS | - |
| 1098 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan152 - com-vrf | PASS | - |
| 1099 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan153 - com-vrf | PASS | - |
| 1100 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan154 - com-vrf | PASS | - |
| 1101 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan155 - com-vrf | PASS | - |
| 1102 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan156 - com-vrf | PASS | - |
| 1103 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan157 - com-vrf | PASS | - |
| 1104 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan158 - com-vrf | PASS | - |
| 1105 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan159 - com-vrf | PASS | - |
| 1106 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan160 - com-vrf | PASS | - |
| 1107 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan161 - com-vrf | PASS | - |
| 1108 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan162 - com-vrf | PASS | - |
| 1109 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan163 - com-vrf | PASS | - |
| 1110 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan164 - com-vrf | PASS | - |
| 1111 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan165 - com-vrf | PASS | - |
| 1112 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan166 - com-vrf | PASS | - |
| 1113 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan167 - com-vrf | PASS | - |
| 1114 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan168 - com-vrf | PASS | - |
| 1115 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan169 - com-vrf | PASS | - |
| 1116 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan170 - com-vrf | PASS | - |
| 1117 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan171 - com-vrf | PASS | - |
| 1118 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan172 - com-vrf | PASS | - |
| 1119 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan173 - com-vrf | PASS | - |
| 1120 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan174 - com-vrf | PASS | - |
| 1121 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan175 - com-vrf | PASS | - |
| 1122 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan176 - com-vrf | PASS | - |
| 1123 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan177 - com-vrf | PASS | - |
| 1124 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan178 - com-vrf | PASS | - |
| 1125 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan179 - com-vrf | PASS | - |
| 1126 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan180 - com-vrf | PASS | - |
| 1127 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan181 - com-vrf | PASS | - |
| 1128 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan182 - com-vrf | PASS | - |
| 1129 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan183 - com-vrf | PASS | - |
| 1130 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan184 - com-vrf | PASS | - |
| 1131 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan185 - com-vrf | PASS | - |
| 1132 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan186 - com-vrf | PASS | - |
| 1133 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan187 - com-vrf | PASS | - |
| 1134 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan188 - com-vrf | PASS | - |
| 1135 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan189 - com-vrf | PASS | - |
| 1136 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan190 - com-vrf | PASS | - |
| 1137 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan191 - com-vrf | PASS | - |
| 1138 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan192 - com-vrf | PASS | - |
| 1139 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan193 - com-vrf | PASS | - |
| 1140 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan194 - com-vrf | PASS | - |
| 1141 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan195 - com-vrf | PASS | - |
| 1142 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan196 - com-vrf | PASS | - |
| 1143 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan197 - com-vrf | PASS | - |
| 1144 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan198 - com-vrf | PASS | - |
| 1145 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan199 - com-vrf | PASS | - |
| 1146 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan200 - com-vrf | PASS | - |
| 1147 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan201 - com-vrf | PASS | - |
| 1148 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan202 - com-vrf | PASS | - |
| 1149 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan203 - com-vrf | PASS | - |
| 1150 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan204 - com-vrf | PASS | - |
| 1151 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan205 - com-vrf | PASS | - |
| 1152 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan206 - com-vrf | PASS | - |
| 1153 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan207 - com-vrf | PASS | - |
| 1154 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan208 - com-vrf | PASS | - |
| 1155 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan209 - com-vrf | PASS | - |
| 1156 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan210 - com-vrf | PASS | - |
| 1157 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan211 - com-vrf | PASS | - |
| 1158 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan212 - com-vrf | PASS | - |
| 1159 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan213 - com-vrf | PASS | - |
| 1160 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan214 - com-vrf | PASS | - |
| 1161 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan215 - com-vrf | PASS | - |
| 1162 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan216 - com-vrf | PASS | - |
| 1163 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan217 - com-vrf | PASS | - |
| 1164 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan218 - com-vrf | PASS | - |
| 1165 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan219 - com-vrf | PASS | - |
| 1166 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan220 - com-vrf | PASS | - |
| 1167 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan221 - com-vrf | PASS | - |
| 1168 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan222 - com-vrf | PASS | - |
| 1169 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan223 - com-vrf | PASS | - |
| 1170 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan224 - com-vrf | PASS | - |
| 1171 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan225 - com-vrf | PASS | - |
| 1172 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan226 - com-vrf | PASS | - |
| 1173 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan227 - com-vrf | PASS | - |
| 1174 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan228 - com-vrf | PASS | - |
| 1175 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan229 - com-vrf | PASS | - |
| 1176 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan230 - com-vrf | PASS | - |
| 1177 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan231 - com-vrf | PASS | - |
| 1178 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan232 - com-vrf | PASS | - |
| 1179 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan233 - com-vrf | PASS | - |
| 1180 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan234 - com-vrf | PASS | - |
| 1181 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan235 - com-vrf | PASS | - |
| 1182 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan236 - com-vrf | PASS | - |
| 1183 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan237 - com-vrf | PASS | - |
| 1184 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan238 - com-vrf | PASS | - |
| 1185 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan239 - com-vrf | PASS | - |
| 1186 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan240 - com-vrf | PASS | - |
| 1187 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan241 - com-vrf | PASS | - |
| 1188 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan242 - com-vrf | PASS | - |
| 1189 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan243 - com-vrf | PASS | - |
| 1190 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan244 - com-vrf | PASS | - |
| 1191 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan245 - com-vrf | PASS | - |
| 1192 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan246 - com-vrf | PASS | - |
| 1193 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan247 - com-vrf | PASS | - |
| 1194 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan248 - com-vrf | PASS | - |
| 1195 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan249 - com-vrf | PASS | - |
| 1196 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan250 - com-vrf | PASS | - |
| 1197 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan251 - com-vrf | PASS | - |
| 1198 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan252 - com-vrf | PASS | - |
| 1199 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan253 - com-vrf | PASS | - |
| 1200 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan254 - com-vrf | PASS | - |
| 1201 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan255 - com-vrf | PASS | - |
| 1202 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan256 - com-vrf | PASS | - |
| 1203 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan257 - com-vrf | PASS | - |
| 1204 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan258 - com-vrf | PASS | - |
| 1205 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan259 - com-vrf | PASS | - |
| 1206 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan260 - com-vrf | PASS | - |
| 1207 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan261 - com-vrf | PASS | - |
| 1208 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan262 - com-vrf | PASS | - |
| 1209 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan263 - com-vrf | PASS | - |
| 1210 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan264 - com-vrf | PASS | - |
| 1211 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan265 - com-vrf | PASS | - |
| 1212 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan266 - com-vrf | PASS | - |
| 1213 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan267 - com-vrf | PASS | - |
| 1214 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan268 - com-vrf | PASS | - |
| 1215 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan269 - com-vrf | PASS | - |
| 1216 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan270 - com-vrf | PASS | - |
| 1217 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan271 - com-vrf | PASS | - |
| 1218 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan272 - com-vrf | PASS | - |
| 1219 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan273 - com-vrf | PASS | - |
| 1220 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan274 - com-vrf | PASS | - |
| 1221 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan275 - com-vrf | PASS | - |
| 1222 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan276 - com-vrf | PASS | - |
| 1223 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan277 - com-vrf | PASS | - |
| 1224 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan278 - com-vrf | PASS | - |
| 1225 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan279 - com-vrf | PASS | - |
| 1226 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan280 - com-vrf | PASS | - |
| 1227 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan281 - com-vrf | PASS | - |
| 1228 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan282 - com-vrf | PASS | - |
| 1229 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan283 - com-vrf | PASS | - |
| 1230 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan284 - com-vrf | PASS | - |
| 1231 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan285 - com-vrf | PASS | - |
| 1232 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan286 - com-vrf | PASS | - |
| 1233 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan287 - com-vrf | PASS | - |
| 1234 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan288 - com-vrf | PASS | - |
| 1235 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan289 - com-vrf | PASS | - |
| 1236 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan290 - com-vrf | PASS | - |
| 1237 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan291 - com-vrf | PASS | - |
| 1238 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan292 - com-vrf | PASS | - |
| 1239 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan293 - com-vrf | PASS | - |
| 1240 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan294 - com-vrf | PASS | - |
| 1241 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan295 - com-vrf | PASS | - |
| 1242 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan296 - com-vrf | PASS | - |
| 1243 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan297 - com-vrf | PASS | - |
| 1244 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan298 - com-vrf | PASS | - |
| 1245 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan299 - com-vrf | PASS | - |
| 1246 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan300 - com-vrf | PASS | - |
| 1247 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan301 - com-vrf | PASS | - |
| 1248 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan302 - com-vrf | PASS | - |
| 1249 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan303 - com-vrf | PASS | - |
| 1250 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan304 - com-vrf | PASS | - |
| 1251 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan305 - com-vrf | PASS | - |
| 1252 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan306 - com-vrf | PASS | - |
| 1253 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan307 - com-vrf | PASS | - |
| 1254 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan308 - com-vrf | PASS | - |
| 1255 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan309 - com-vrf | PASS | - |
| 1256 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan310 - com-vrf | PASS | - |
| 1257 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan311 - com-vrf | PASS | - |
| 1258 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan312 - com-vrf | PASS | - |
| 1259 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan313 - com-vrf | PASS | - |
| 1260 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan314 - com-vrf | PASS | - |
| 1261 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan315 - com-vrf | PASS | - |
| 1262 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan316 - com-vrf | PASS | - |
| 1263 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan317 - com-vrf | PASS | - |
| 1264 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan318 - com-vrf | PASS | - |
| 1265 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan319 - com-vrf | PASS | - |
| 1266 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan320 - com-vrf | PASS | - |
| 1267 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan321 - com-vrf | PASS | - |
| 1268 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan322 - com-vrf | PASS | - |
| 1269 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan323 - com-vrf | PASS | - |
| 1270 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan324 - com-vrf | PASS | - |
| 1271 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan325 - com-vrf | PASS | - |
| 1272 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan326 - com-vrf | PASS | - |
| 1273 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan327 - com-vrf | PASS | - |
| 1274 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan328 - com-vrf | PASS | - |
| 1275 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan329 - com-vrf | PASS | - |
| 1276 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan330 - com-vrf | PASS | - |
| 1277 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan331 - com-vrf | PASS | - |
| 1278 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan332 - com-vrf | PASS | - |
| 1279 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan333 - com-vrf | PASS | - |
| 1280 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan334 - com-vrf | PASS | - |
| 1281 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan335 - com-vrf | PASS | - |
| 1282 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan336 - com-vrf | PASS | - |
| 1283 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan337 - com-vrf | PASS | - |
| 1284 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan338 - com-vrf | PASS | - |
| 1285 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan339 - com-vrf | PASS | - |
| 1286 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan340 - com-vrf | PASS | - |
| 1287 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan341 - com-vrf | PASS | - |
| 1288 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan342 - com-vrf | PASS | - |
| 1289 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan343 - com-vrf | PASS | - |
| 1290 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan344 - com-vrf | PASS | - |
| 1291 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan345 - com-vrf | PASS | - |
| 1292 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan346 - com-vrf | PASS | - |
| 1293 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan347 - com-vrf | PASS | - |
| 1294 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan348 - com-vrf | PASS | - |
| 1295 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan349 - com-vrf | PASS | - |
| 1296 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan350 - com-vrf | PASS | - |
| 1297 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan351 - com-vrf | PASS | - |
| 1298 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan352 - com-vrf | PASS | - |
| 1299 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan353 - com-vrf | PASS | - |
| 1300 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan354 - com-vrf | PASS | - |
| 1301 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan355 - com-vrf | PASS | - |
| 1302 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan356 - com-vrf | PASS | - |
| 1303 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan357 - com-vrf | PASS | - |
| 1304 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan358 - com-vrf | PASS | - |
| 1305 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan359 - com-vrf | PASS | - |
| 1306 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan360 - com-vrf | PASS | - |
| 1307 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan361 - com-vrf | PASS | - |
| 1308 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan362 - com-vrf | PASS | - |
| 1309 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan363 - com-vrf | PASS | - |
| 1310 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan364 - com-vrf | PASS | - |
| 1311 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan365 - com-vrf | PASS | - |
| 1312 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan366 - com-vrf | PASS | - |
| 1313 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan367 - com-vrf | PASS | - |
| 1314 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan368 - com-vrf | PASS | - |
| 1315 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan369 - com-vrf | PASS | - |
| 1316 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan370 - com-vrf | PASS | - |
| 1317 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan371 - com-vrf | PASS | - |
| 1318 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan372 - com-vrf | PASS | - |
| 1319 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan373 - com-vrf | PASS | - |
| 1320 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan374 - com-vrf | PASS | - |
| 1321 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan375 - com-vrf | PASS | - |
| 1322 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan376 - com-vrf | PASS | - |
| 1323 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan377 - com-vrf | PASS | - |
| 1324 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan378 - com-vrf | PASS | - |
| 1325 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan379 - com-vrf | PASS | - |
| 1326 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan380 - com-vrf | PASS | - |
| 1327 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan381 - com-vrf | PASS | - |
| 1328 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan382 - com-vrf | PASS | - |
| 1329 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan383 - com-vrf | PASS | - |
| 1330 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan384 - com-vrf | PASS | - |
| 1331 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan385 - com-vrf | PASS | - |
| 1332 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan386 - com-vrf | PASS | - |
| 1333 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan387 - com-vrf | PASS | - |
| 1334 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan388 - com-vrf | PASS | - |
| 1335 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan389 - com-vrf | PASS | - |
| 1336 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan390 - com-vrf | PASS | - |
| 1337 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan391 - com-vrf | PASS | - |
| 1338 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan392 - com-vrf | PASS | - |
| 1339 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan393 - com-vrf | PASS | - |
| 1340 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan394 - com-vrf | PASS | - |
| 1341 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan395 - com-vrf | PASS | - |
| 1342 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan396 - com-vrf | PASS | - |
| 1343 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan397 - com-vrf | PASS | - |
| 1344 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan398 - com-vrf | PASS | - |
| 1345 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan399 - com-vrf | PASS | - |
| 1346 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan400 - com-vrf | PASS | - |
| 1347 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan401 - com-vrf | PASS | - |
| 1348 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan402 - com-vrf | PASS | - |
| 1349 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan403 - com-vrf | PASS | - |
| 1350 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan404 - com-vrf | PASS | - |
| 1351 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan405 - com-vrf | PASS | - |
| 1352 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan406 - com-vrf | PASS | - |
| 1353 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan407 - com-vrf | PASS | - |
| 1354 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan408 - com-vrf | PASS | - |
| 1355 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan409 - com-vrf | PASS | - |
| 1356 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan410 - com-vrf | PASS | - |
| 1357 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan411 - com-vrf | PASS | - |
| 1358 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan412 - com-vrf | PASS | - |
| 1359 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan413 - com-vrf | PASS | - |
| 1360 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan414 - com-vrf | PASS | - |
| 1361 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan415 - com-vrf | PASS | - |
| 1362 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan416 - com-vrf | PASS | - |
| 1363 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan417 - com-vrf | PASS | - |
| 1364 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan418 - com-vrf | PASS | - |
| 1365 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan419 - com-vrf | PASS | - |
| 1366 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan420 - com-vrf | PASS | - |
| 1367 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan421 - com-vrf | PASS | - |
| 1368 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan422 - com-vrf | PASS | - |
| 1369 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan423 - com-vrf | PASS | - |
| 1370 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan424 - com-vrf | PASS | - |
| 1371 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan425 - com-vrf | PASS | - |
| 1372 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan426 - com-vrf | PASS | - |
| 1373 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan427 - com-vrf | PASS | - |
| 1374 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan428 - com-vrf | PASS | - |
| 1375 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan429 - com-vrf | PASS | - |
| 1376 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan430 - com-vrf | PASS | - |
| 1377 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan431 - com-vrf | PASS | - |
| 1378 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan432 - com-vrf | PASS | - |
| 1379 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan433 - com-vrf | PASS | - |
| 1380 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan434 - com-vrf | PASS | - |
| 1381 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan435 - com-vrf | PASS | - |
| 1382 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan436 - com-vrf | PASS | - |
| 1383 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan437 - com-vrf | PASS | - |
| 1384 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan438 - com-vrf | PASS | - |
| 1385 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan439 - com-vrf | PASS | - |
| 1386 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan440 - com-vrf | PASS | - |
| 1387 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan441 - com-vrf | PASS | - |
| 1388 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan442 - com-vrf | PASS | - |
| 1389 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan443 - com-vrf | PASS | - |
| 1390 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan444 - com-vrf | PASS | - |
| 1391 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan445 - com-vrf | PASS | - |
| 1392 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan446 - com-vrf | PASS | - |
| 1393 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan447 - com-vrf | PASS | - |
| 1394 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan448 - com-vrf | PASS | - |
| 1395 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan449 - com-vrf | PASS | - |
| 1396 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan450 - com-vrf | PASS | - |
| 1397 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4050 - MLAG_PEER_L3_iBGP: vrf com | PASS | - |
| 1398 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2001 - sec-vrf | PASS | - |
| 1399 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2002 - sec-vrf | PASS | - |
| 1400 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2003 - sec-vrf | PASS | - |
| 1401 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2004 - sec-vrf | PASS | - |
| 1402 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2005 - sec-vrf | PASS | - |
| 1403 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2006 - sec-vrf | PASS | - |
| 1404 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2007 - sec-vrf | PASS | - |
| 1405 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2008 - sec-vrf | PASS | - |
| 1406 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2009 - sec-vrf | PASS | - |
| 1407 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2010 - sec-vrf | PASS | - |
| 1408 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2011 - sec-vrf | PASS | - |
| 1409 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2012 - sec-vrf | PASS | - |
| 1410 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2013 - sec-vrf | PASS | - |
| 1411 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2014 - sec-vrf | PASS | - |
| 1412 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2015 - sec-vrf | PASS | - |
| 1413 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2016 - sec-vrf | PASS | - |
| 1414 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2017 - sec-vrf | PASS | - |
| 1415 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2018 - sec-vrf | PASS | - |
| 1416 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2019 - sec-vrf | PASS | - |
| 1417 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2020 - sec-vrf | PASS | - |
| 1418 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2021 - sec-vrf | PASS | - |
| 1419 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2022 - sec-vrf | PASS | - |
| 1420 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2023 - sec-vrf | PASS | - |
| 1421 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2024 - sec-vrf | PASS | - |
| 1422 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2025 - sec-vrf | PASS | - |
| 1423 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2026 - sec-vrf | PASS | - |
| 1424 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2027 - sec-vrf | PASS | - |
| 1425 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2028 - sec-vrf | PASS | - |
| 1426 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2029 - sec-vrf | PASS | - |
| 1427 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2030 - sec-vrf | PASS | - |
| 1428 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2031 - sec-vrf | PASS | - |
| 1429 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2032 - sec-vrf | PASS | - |
| 1430 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2033 - sec-vrf | PASS | - |
| 1431 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2034 - sec-vrf | PASS | - |
| 1432 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2035 - sec-vrf | PASS | - |
| 1433 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2036 - sec-vrf | PASS | - |
| 1434 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2037 - sec-vrf | PASS | - |
| 1435 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2038 - sec-vrf | PASS | - |
| 1436 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2039 - sec-vrf | PASS | - |
| 1437 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2040 - sec-vrf | PASS | - |
| 1438 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2041 - sec-vrf | PASS | - |
| 1439 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2042 - sec-vrf | PASS | - |
| 1440 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2043 - sec-vrf | PASS | - |
| 1441 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2044 - sec-vrf | PASS | - |
| 1442 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2045 - sec-vrf | PASS | - |
| 1443 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2046 - sec-vrf | PASS | - |
| 1444 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2047 - sec-vrf | PASS | - |
| 1445 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2048 - sec-vrf | PASS | - |
| 1446 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2049 - sec-vrf | PASS | - |
| 1447 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2050 - sec-vrf | PASS | - |
| 1448 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2051 - sec-vrf | PASS | - |
| 1449 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2052 - sec-vrf | PASS | - |
| 1450 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2053 - sec-vrf | PASS | - |
| 1451 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2054 - sec-vrf | PASS | - |
| 1452 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2055 - sec-vrf | PASS | - |
| 1453 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2056 - sec-vrf | PASS | - |
| 1454 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2057 - sec-vrf | PASS | - |
| 1455 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2058 - sec-vrf | PASS | - |
| 1456 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2059 - sec-vrf | PASS | - |
| 1457 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2060 - sec-vrf | PASS | - |
| 1458 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2061 - sec-vrf | PASS | - |
| 1459 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2062 - sec-vrf | PASS | - |
| 1460 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2063 - sec-vrf | PASS | - |
| 1461 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2064 - sec-vrf | PASS | - |
| 1462 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2065 - sec-vrf | PASS | - |
| 1463 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2066 - sec-vrf | PASS | - |
| 1464 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2067 - sec-vrf | PASS | - |
| 1465 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2068 - sec-vrf | PASS | - |
| 1466 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2069 - sec-vrf | PASS | - |
| 1467 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2070 - sec-vrf | PASS | - |
| 1468 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2071 - sec-vrf | PASS | - |
| 1469 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2072 - sec-vrf | PASS | - |
| 1470 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2073 - sec-vrf | PASS | - |
| 1471 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2074 - sec-vrf | PASS | - |
| 1472 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2075 - sec-vrf | PASS | - |
| 1473 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2076 - sec-vrf | PASS | - |
| 1474 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2077 - sec-vrf | PASS | - |
| 1475 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2078 - sec-vrf | PASS | - |
| 1476 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2079 - sec-vrf | PASS | - |
| 1477 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2080 - sec-vrf | PASS | - |
| 1478 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2081 - sec-vrf | PASS | - |
| 1479 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2082 - sec-vrf | PASS | - |
| 1480 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2083 - sec-vrf | PASS | - |
| 1481 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2084 - sec-vrf | PASS | - |
| 1482 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2085 - sec-vrf | PASS | - |
| 1483 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2086 - sec-vrf | PASS | - |
| 1484 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2087 - sec-vrf | PASS | - |
| 1485 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2088 - sec-vrf | PASS | - |
| 1486 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2089 - sec-vrf | PASS | - |
| 1487 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2090 - sec-vrf | PASS | - |
| 1488 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2091 - sec-vrf | PASS | - |
| 1489 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2092 - sec-vrf | PASS | - |
| 1490 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2093 - sec-vrf | PASS | - |
| 1491 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2094 - sec-vrf | PASS | - |
| 1492 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2095 - sec-vrf | PASS | - |
| 1493 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2096 - sec-vrf | PASS | - |
| 1494 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2097 - sec-vrf | PASS | - |
| 1495 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2098 - sec-vrf | PASS | - |
| 1496 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2099 - sec-vrf | PASS | - |
| 1497 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2100 - sec-vrf | PASS | - |
| 1498 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2101 - sec-vrf | PASS | - |
| 1499 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2102 - sec-vrf | PASS | - |
| 1500 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2103 - sec-vrf | PASS | - |
| 1501 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2104 - sec-vrf | PASS | - |
| 1502 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2105 - sec-vrf | PASS | - |
| 1503 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2106 - sec-vrf | PASS | - |
| 1504 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2107 - sec-vrf | PASS | - |
| 1505 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2108 - sec-vrf | PASS | - |
| 1506 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2109 - sec-vrf | PASS | - |
| 1507 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2110 - sec-vrf | PASS | - |
| 1508 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2111 - sec-vrf | PASS | - |
| 1509 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2112 - sec-vrf | PASS | - |
| 1510 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2113 - sec-vrf | PASS | - |
| 1511 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2114 - sec-vrf | PASS | - |
| 1512 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2115 - sec-vrf | PASS | - |
| 1513 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2116 - sec-vrf | PASS | - |
| 1514 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2117 - sec-vrf | PASS | - |
| 1515 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2118 - sec-vrf | PASS | - |
| 1516 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2119 - sec-vrf | PASS | - |
| 1517 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2120 - sec-vrf | PASS | - |
| 1518 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2121 - sec-vrf | PASS | - |
| 1519 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2122 - sec-vrf | PASS | - |
| 1520 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2123 - sec-vrf | PASS | - |
| 1521 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2124 - sec-vrf | PASS | - |
| 1522 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2125 - sec-vrf | PASS | - |
| 1523 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2126 - sec-vrf | PASS | - |
| 1524 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2127 - sec-vrf | PASS | - |
| 1525 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2128 - sec-vrf | PASS | - |
| 1526 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2129 - sec-vrf | PASS | - |
| 1527 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2130 - sec-vrf | PASS | - |
| 1528 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2131 - sec-vrf | PASS | - |
| 1529 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2132 - sec-vrf | PASS | - |
| 1530 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2133 - sec-vrf | PASS | - |
| 1531 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2134 - sec-vrf | PASS | - |
| 1532 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2135 - sec-vrf | PASS | - |
| 1533 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2136 - sec-vrf | PASS | - |
| 1534 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2137 - sec-vrf | PASS | - |
| 1535 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2138 - sec-vrf | PASS | - |
| 1536 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2139 - sec-vrf | PASS | - |
| 1537 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2140 - sec-vrf | PASS | - |
| 1538 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2141 - sec-vrf | PASS | - |
| 1539 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2142 - sec-vrf | PASS | - |
| 1540 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2143 - sec-vrf | PASS | - |
| 1541 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2144 - sec-vrf | PASS | - |
| 1542 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2145 - sec-vrf | PASS | - |
| 1543 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2146 - sec-vrf | PASS | - |
| 1544 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2147 - sec-vrf | PASS | - |
| 1545 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2148 - sec-vrf | PASS | - |
| 1546 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2149 - sec-vrf | PASS | - |
| 1547 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2150 - sec-vrf | PASS | - |
| 1548 | dc1p1_leaf1b_cal419 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4051 - MLAG_PEER_L3_iBGP: vrf sec | PASS | - |
| 1549 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 1550 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 1551 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan101 - com-vrf | PASS | - |
| 1552 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan102 - com-vrf | PASS | - |
| 1553 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan103 - com-vrf | PASS | - |
| 1554 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan104 - com-vrf | PASS | - |
| 1555 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan105 - com-vrf | PASS | - |
| 1556 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan106 - com-vrf | PASS | - |
| 1557 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan107 - com-vrf | PASS | - |
| 1558 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan108 - com-vrf | PASS | - |
| 1559 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan109 - com-vrf | PASS | - |
| 1560 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - com-vrf | PASS | - |
| 1561 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan111 - com-vrf | PASS | - |
| 1562 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan112 - com-vrf | PASS | - |
| 1563 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan113 - com-vrf | PASS | - |
| 1564 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan114 - com-vrf | PASS | - |
| 1565 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan115 - com-vrf | PASS | - |
| 1566 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan116 - com-vrf | PASS | - |
| 1567 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan117 - com-vrf | PASS | - |
| 1568 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan118 - com-vrf | PASS | - |
| 1569 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan119 - com-vrf | PASS | - |
| 1570 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - com-vrf | PASS | - |
| 1571 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan121 - com-vrf | PASS | - |
| 1572 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan122 - com-vrf | PASS | - |
| 1573 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan123 - com-vrf | PASS | - |
| 1574 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan124 - com-vrf | PASS | - |
| 1575 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan125 - com-vrf | PASS | - |
| 1576 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan126 - com-vrf | PASS | - |
| 1577 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan127 - com-vrf | PASS | - |
| 1578 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan128 - com-vrf | PASS | - |
| 1579 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan129 - com-vrf | PASS | - |
| 1580 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan130 - com-vrf | PASS | - |
| 1581 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan131 - com-vrf | PASS | - |
| 1582 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan132 - com-vrf | PASS | - |
| 1583 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan133 - com-vrf | PASS | - |
| 1584 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan134 - com-vrf | PASS | - |
| 1585 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan135 - com-vrf | PASS | - |
| 1586 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan136 - com-vrf | PASS | - |
| 1587 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan137 - com-vrf | PASS | - |
| 1588 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan138 - com-vrf | PASS | - |
| 1589 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan139 - com-vrf | PASS | - |
| 1590 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan140 - com-vrf | PASS | - |
| 1591 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan141 - com-vrf | PASS | - |
| 1592 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan142 - com-vrf | PASS | - |
| 1593 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan143 - com-vrf | PASS | - |
| 1594 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan144 - com-vrf | PASS | - |
| 1595 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan145 - com-vrf | PASS | - |
| 1596 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan146 - com-vrf | PASS | - |
| 1597 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan147 - com-vrf | PASS | - |
| 1598 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan148 - com-vrf | PASS | - |
| 1599 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan149 - com-vrf | PASS | - |
| 1600 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan150 - com-vrf | PASS | - |
| 1601 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan151 - com-vrf | PASS | - |
| 1602 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan152 - com-vrf | PASS | - |
| 1603 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan153 - com-vrf | PASS | - |
| 1604 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan154 - com-vrf | PASS | - |
| 1605 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan155 - com-vrf | PASS | - |
| 1606 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan156 - com-vrf | PASS | - |
| 1607 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan157 - com-vrf | PASS | - |
| 1608 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan158 - com-vrf | PASS | - |
| 1609 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan159 - com-vrf | PASS | - |
| 1610 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan160 - com-vrf | PASS | - |
| 1611 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan161 - com-vrf | PASS | - |
| 1612 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan162 - com-vrf | PASS | - |
| 1613 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan163 - com-vrf | PASS | - |
| 1614 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan164 - com-vrf | PASS | - |
| 1615 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan165 - com-vrf | PASS | - |
| 1616 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan166 - com-vrf | PASS | - |
| 1617 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan167 - com-vrf | PASS | - |
| 1618 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan168 - com-vrf | PASS | - |
| 1619 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan169 - com-vrf | PASS | - |
| 1620 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan170 - com-vrf | PASS | - |
| 1621 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan171 - com-vrf | PASS | - |
| 1622 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan172 - com-vrf | PASS | - |
| 1623 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan173 - com-vrf | PASS | - |
| 1624 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan174 - com-vrf | PASS | - |
| 1625 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan175 - com-vrf | PASS | - |
| 1626 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan176 - com-vrf | PASS | - |
| 1627 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan177 - com-vrf | PASS | - |
| 1628 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan178 - com-vrf | PASS | - |
| 1629 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan179 - com-vrf | PASS | - |
| 1630 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan180 - com-vrf | PASS | - |
| 1631 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan181 - com-vrf | PASS | - |
| 1632 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan182 - com-vrf | PASS | - |
| 1633 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan183 - com-vrf | PASS | - |
| 1634 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan184 - com-vrf | PASS | - |
| 1635 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan185 - com-vrf | PASS | - |
| 1636 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan186 - com-vrf | PASS | - |
| 1637 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan187 - com-vrf | PASS | - |
| 1638 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan188 - com-vrf | PASS | - |
| 1639 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan189 - com-vrf | PASS | - |
| 1640 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan190 - com-vrf | PASS | - |
| 1641 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan191 - com-vrf | PASS | - |
| 1642 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan192 - com-vrf | PASS | - |
| 1643 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan193 - com-vrf | PASS | - |
| 1644 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan194 - com-vrf | PASS | - |
| 1645 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan195 - com-vrf | PASS | - |
| 1646 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan196 - com-vrf | PASS | - |
| 1647 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan197 - com-vrf | PASS | - |
| 1648 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan198 - com-vrf | PASS | - |
| 1649 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan199 - com-vrf | PASS | - |
| 1650 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan200 - com-vrf | PASS | - |
| 1651 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan201 - com-vrf | PASS | - |
| 1652 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan202 - com-vrf | PASS | - |
| 1653 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan203 - com-vrf | PASS | - |
| 1654 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan204 - com-vrf | PASS | - |
| 1655 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan205 - com-vrf | PASS | - |
| 1656 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan206 - com-vrf | PASS | - |
| 1657 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan207 - com-vrf | PASS | - |
| 1658 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan208 - com-vrf | PASS | - |
| 1659 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan209 - com-vrf | PASS | - |
| 1660 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan210 - com-vrf | PASS | - |
| 1661 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan211 - com-vrf | PASS | - |
| 1662 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan212 - com-vrf | PASS | - |
| 1663 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan213 - com-vrf | PASS | - |
| 1664 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan214 - com-vrf | PASS | - |
| 1665 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan215 - com-vrf | PASS | - |
| 1666 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan216 - com-vrf | PASS | - |
| 1667 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan217 - com-vrf | PASS | - |
| 1668 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan218 - com-vrf | PASS | - |
| 1669 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan219 - com-vrf | PASS | - |
| 1670 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan220 - com-vrf | PASS | - |
| 1671 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan221 - com-vrf | PASS | - |
| 1672 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan222 - com-vrf | PASS | - |
| 1673 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan223 - com-vrf | PASS | - |
| 1674 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan224 - com-vrf | PASS | - |
| 1675 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan225 - com-vrf | PASS | - |
| 1676 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan226 - com-vrf | PASS | - |
| 1677 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan227 - com-vrf | PASS | - |
| 1678 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan228 - com-vrf | PASS | - |
| 1679 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan229 - com-vrf | PASS | - |
| 1680 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan230 - com-vrf | PASS | - |
| 1681 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan231 - com-vrf | PASS | - |
| 1682 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan232 - com-vrf | PASS | - |
| 1683 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan233 - com-vrf | PASS | - |
| 1684 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan234 - com-vrf | PASS | - |
| 1685 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan235 - com-vrf | PASS | - |
| 1686 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan236 - com-vrf | PASS | - |
| 1687 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan237 - com-vrf | PASS | - |
| 1688 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan238 - com-vrf | PASS | - |
| 1689 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan239 - com-vrf | PASS | - |
| 1690 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan240 - com-vrf | PASS | - |
| 1691 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan241 - com-vrf | PASS | - |
| 1692 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan242 - com-vrf | PASS | - |
| 1693 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan243 - com-vrf | PASS | - |
| 1694 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan244 - com-vrf | PASS | - |
| 1695 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan245 - com-vrf | PASS | - |
| 1696 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan246 - com-vrf | PASS | - |
| 1697 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan247 - com-vrf | PASS | - |
| 1698 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan248 - com-vrf | PASS | - |
| 1699 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan249 - com-vrf | PASS | - |
| 1700 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan250 - com-vrf | PASS | - |
| 1701 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan251 - com-vrf | PASS | - |
| 1702 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan252 - com-vrf | PASS | - |
| 1703 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan253 - com-vrf | PASS | - |
| 1704 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan254 - com-vrf | PASS | - |
| 1705 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan255 - com-vrf | PASS | - |
| 1706 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan256 - com-vrf | PASS | - |
| 1707 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan257 - com-vrf | PASS | - |
| 1708 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan258 - com-vrf | PASS | - |
| 1709 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan259 - com-vrf | PASS | - |
| 1710 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan260 - com-vrf | PASS | - |
| 1711 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan261 - com-vrf | PASS | - |
| 1712 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan262 - com-vrf | PASS | - |
| 1713 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan263 - com-vrf | PASS | - |
| 1714 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan264 - com-vrf | PASS | - |
| 1715 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan265 - com-vrf | PASS | - |
| 1716 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan266 - com-vrf | PASS | - |
| 1717 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan267 - com-vrf | PASS | - |
| 1718 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan268 - com-vrf | PASS | - |
| 1719 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan269 - com-vrf | PASS | - |
| 1720 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan270 - com-vrf | PASS | - |
| 1721 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan271 - com-vrf | PASS | - |
| 1722 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan272 - com-vrf | PASS | - |
| 1723 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan273 - com-vrf | PASS | - |
| 1724 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan274 - com-vrf | PASS | - |
| 1725 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan275 - com-vrf | PASS | - |
| 1726 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan276 - com-vrf | PASS | - |
| 1727 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan277 - com-vrf | PASS | - |
| 1728 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan278 - com-vrf | PASS | - |
| 1729 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan279 - com-vrf | PASS | - |
| 1730 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan280 - com-vrf | PASS | - |
| 1731 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan281 - com-vrf | PASS | - |
| 1732 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan282 - com-vrf | PASS | - |
| 1733 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan283 - com-vrf | PASS | - |
| 1734 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan284 - com-vrf | PASS | - |
| 1735 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan285 - com-vrf | PASS | - |
| 1736 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan286 - com-vrf | PASS | - |
| 1737 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan287 - com-vrf | PASS | - |
| 1738 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan288 - com-vrf | PASS | - |
| 1739 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan289 - com-vrf | PASS | - |
| 1740 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan290 - com-vrf | PASS | - |
| 1741 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan291 - com-vrf | PASS | - |
| 1742 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan292 - com-vrf | PASS | - |
| 1743 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan293 - com-vrf | PASS | - |
| 1744 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan294 - com-vrf | PASS | - |
| 1745 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan295 - com-vrf | PASS | - |
| 1746 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan296 - com-vrf | PASS | - |
| 1747 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan297 - com-vrf | PASS | - |
| 1748 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan298 - com-vrf | PASS | - |
| 1749 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan299 - com-vrf | PASS | - |
| 1750 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan300 - com-vrf | PASS | - |
| 1751 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan301 - com-vrf | PASS | - |
| 1752 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan302 - com-vrf | PASS | - |
| 1753 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan303 - com-vrf | PASS | - |
| 1754 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan304 - com-vrf | PASS | - |
| 1755 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan305 - com-vrf | PASS | - |
| 1756 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan306 - com-vrf | PASS | - |
| 1757 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan307 - com-vrf | PASS | - |
| 1758 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan308 - com-vrf | PASS | - |
| 1759 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan309 - com-vrf | PASS | - |
| 1760 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan310 - com-vrf | PASS | - |
| 1761 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan311 - com-vrf | PASS | - |
| 1762 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan312 - com-vrf | PASS | - |
| 1763 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan313 - com-vrf | PASS | - |
| 1764 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan314 - com-vrf | PASS | - |
| 1765 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan315 - com-vrf | PASS | - |
| 1766 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan316 - com-vrf | PASS | - |
| 1767 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan317 - com-vrf | PASS | - |
| 1768 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan318 - com-vrf | PASS | - |
| 1769 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan319 - com-vrf | PASS | - |
| 1770 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan320 - com-vrf | PASS | - |
| 1771 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan321 - com-vrf | PASS | - |
| 1772 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan322 - com-vrf | PASS | - |
| 1773 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan323 - com-vrf | PASS | - |
| 1774 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan324 - com-vrf | PASS | - |
| 1775 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan325 - com-vrf | PASS | - |
| 1776 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan326 - com-vrf | PASS | - |
| 1777 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan327 - com-vrf | PASS | - |
| 1778 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan328 - com-vrf | PASS | - |
| 1779 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan329 - com-vrf | PASS | - |
| 1780 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan330 - com-vrf | PASS | - |
| 1781 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan331 - com-vrf | PASS | - |
| 1782 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan332 - com-vrf | PASS | - |
| 1783 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan333 - com-vrf | PASS | - |
| 1784 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan334 - com-vrf | PASS | - |
| 1785 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan335 - com-vrf | PASS | - |
| 1786 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan336 - com-vrf | PASS | - |
| 1787 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan337 - com-vrf | PASS | - |
| 1788 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan338 - com-vrf | PASS | - |
| 1789 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan339 - com-vrf | PASS | - |
| 1790 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan340 - com-vrf | PASS | - |
| 1791 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan341 - com-vrf | PASS | - |
| 1792 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan342 - com-vrf | PASS | - |
| 1793 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan343 - com-vrf | PASS | - |
| 1794 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan344 - com-vrf | PASS | - |
| 1795 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan345 - com-vrf | PASS | - |
| 1796 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan346 - com-vrf | PASS | - |
| 1797 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan347 - com-vrf | PASS | - |
| 1798 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan348 - com-vrf | PASS | - |
| 1799 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan349 - com-vrf | PASS | - |
| 1800 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan350 - com-vrf | PASS | - |
| 1801 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan351 - com-vrf | PASS | - |
| 1802 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan352 - com-vrf | PASS | - |
| 1803 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan353 - com-vrf | PASS | - |
| 1804 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan354 - com-vrf | PASS | - |
| 1805 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan355 - com-vrf | PASS | - |
| 1806 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan356 - com-vrf | PASS | - |
| 1807 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan357 - com-vrf | PASS | - |
| 1808 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan358 - com-vrf | PASS | - |
| 1809 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan359 - com-vrf | PASS | - |
| 1810 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan360 - com-vrf | PASS | - |
| 1811 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan361 - com-vrf | PASS | - |
| 1812 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan362 - com-vrf | PASS | - |
| 1813 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan363 - com-vrf | PASS | - |
| 1814 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan364 - com-vrf | PASS | - |
| 1815 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan365 - com-vrf | PASS | - |
| 1816 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan366 - com-vrf | PASS | - |
| 1817 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan367 - com-vrf | PASS | - |
| 1818 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan368 - com-vrf | PASS | - |
| 1819 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan369 - com-vrf | PASS | - |
| 1820 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan370 - com-vrf | PASS | - |
| 1821 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan371 - com-vrf | PASS | - |
| 1822 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan372 - com-vrf | PASS | - |
| 1823 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan373 - com-vrf | PASS | - |
| 1824 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan374 - com-vrf | PASS | - |
| 1825 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan375 - com-vrf | PASS | - |
| 1826 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan376 - com-vrf | PASS | - |
| 1827 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan377 - com-vrf | PASS | - |
| 1828 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan378 - com-vrf | PASS | - |
| 1829 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan379 - com-vrf | PASS | - |
| 1830 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan380 - com-vrf | PASS | - |
| 1831 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan381 - com-vrf | PASS | - |
| 1832 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan382 - com-vrf | PASS | - |
| 1833 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan383 - com-vrf | PASS | - |
| 1834 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan384 - com-vrf | PASS | - |
| 1835 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan385 - com-vrf | PASS | - |
| 1836 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan386 - com-vrf | PASS | - |
| 1837 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan387 - com-vrf | PASS | - |
| 1838 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan388 - com-vrf | PASS | - |
| 1839 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan389 - com-vrf | PASS | - |
| 1840 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan390 - com-vrf | PASS | - |
| 1841 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan391 - com-vrf | PASS | - |
| 1842 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan392 - com-vrf | PASS | - |
| 1843 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan393 - com-vrf | PASS | - |
| 1844 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan394 - com-vrf | PASS | - |
| 1845 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan395 - com-vrf | PASS | - |
| 1846 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan396 - com-vrf | PASS | - |
| 1847 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan397 - com-vrf | PASS | - |
| 1848 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan398 - com-vrf | PASS | - |
| 1849 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan399 - com-vrf | PASS | - |
| 1850 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan400 - com-vrf | PASS | - |
| 1851 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan401 - com-vrf | PASS | - |
| 1852 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan402 - com-vrf | PASS | - |
| 1853 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan403 - com-vrf | PASS | - |
| 1854 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan404 - com-vrf | PASS | - |
| 1855 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan405 - com-vrf | PASS | - |
| 1856 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan406 - com-vrf | PASS | - |
| 1857 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan407 - com-vrf | PASS | - |
| 1858 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan408 - com-vrf | PASS | - |
| 1859 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan409 - com-vrf | PASS | - |
| 1860 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan410 - com-vrf | PASS | - |
| 1861 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan411 - com-vrf | PASS | - |
| 1862 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan412 - com-vrf | PASS | - |
| 1863 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan413 - com-vrf | PASS | - |
| 1864 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan414 - com-vrf | PASS | - |
| 1865 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan415 - com-vrf | PASS | - |
| 1866 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan416 - com-vrf | PASS | - |
| 1867 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan417 - com-vrf | PASS | - |
| 1868 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan418 - com-vrf | PASS | - |
| 1869 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan419 - com-vrf | PASS | - |
| 1870 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan420 - com-vrf | PASS | - |
| 1871 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan421 - com-vrf | PASS | - |
| 1872 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan422 - com-vrf | PASS | - |
| 1873 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan423 - com-vrf | PASS | - |
| 1874 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan424 - com-vrf | PASS | - |
| 1875 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan425 - com-vrf | PASS | - |
| 1876 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan426 - com-vrf | PASS | - |
| 1877 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan427 - com-vrf | PASS | - |
| 1878 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan428 - com-vrf | PASS | - |
| 1879 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan429 - com-vrf | PASS | - |
| 1880 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan430 - com-vrf | PASS | - |
| 1881 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan431 - com-vrf | PASS | - |
| 1882 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan432 - com-vrf | PASS | - |
| 1883 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan433 - com-vrf | PASS | - |
| 1884 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan434 - com-vrf | PASS | - |
| 1885 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan435 - com-vrf | PASS | - |
| 1886 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan436 - com-vrf | PASS | - |
| 1887 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan437 - com-vrf | PASS | - |
| 1888 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan438 - com-vrf | PASS | - |
| 1889 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan439 - com-vrf | PASS | - |
| 1890 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan440 - com-vrf | PASS | - |
| 1891 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan441 - com-vrf | PASS | - |
| 1892 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan442 - com-vrf | PASS | - |
| 1893 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan443 - com-vrf | PASS | - |
| 1894 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan444 - com-vrf | PASS | - |
| 1895 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan445 - com-vrf | PASS | - |
| 1896 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan446 - com-vrf | PASS | - |
| 1897 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan447 - com-vrf | PASS | - |
| 1898 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan448 - com-vrf | PASS | - |
| 1899 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan449 - com-vrf | PASS | - |
| 1900 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan450 - com-vrf | PASS | - |
| 1901 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4050 - MLAG_PEER_L3_iBGP: vrf com | PASS | - |
| 1902 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2001 - sec-vrf | PASS | - |
| 1903 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2002 - sec-vrf | PASS | - |
| 1904 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2003 - sec-vrf | PASS | - |
| 1905 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2004 - sec-vrf | PASS | - |
| 1906 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2005 - sec-vrf | PASS | - |
| 1907 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2006 - sec-vrf | PASS | - |
| 1908 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2007 - sec-vrf | PASS | - |
| 1909 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2008 - sec-vrf | PASS | - |
| 1910 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2009 - sec-vrf | PASS | - |
| 1911 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2010 - sec-vrf | PASS | - |
| 1912 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2011 - sec-vrf | PASS | - |
| 1913 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2012 - sec-vrf | PASS | - |
| 1914 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2013 - sec-vrf | PASS | - |
| 1915 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2014 - sec-vrf | PASS | - |
| 1916 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2015 - sec-vrf | PASS | - |
| 1917 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2016 - sec-vrf | PASS | - |
| 1918 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2017 - sec-vrf | PASS | - |
| 1919 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2018 - sec-vrf | PASS | - |
| 1920 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2019 - sec-vrf | PASS | - |
| 1921 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2020 - sec-vrf | PASS | - |
| 1922 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2021 - sec-vrf | PASS | - |
| 1923 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2022 - sec-vrf | PASS | - |
| 1924 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2023 - sec-vrf | PASS | - |
| 1925 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2024 - sec-vrf | PASS | - |
| 1926 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2025 - sec-vrf | PASS | - |
| 1927 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2026 - sec-vrf | PASS | - |
| 1928 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2027 - sec-vrf | PASS | - |
| 1929 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2028 - sec-vrf | PASS | - |
| 1930 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2029 - sec-vrf | PASS | - |
| 1931 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2030 - sec-vrf | PASS | - |
| 1932 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2031 - sec-vrf | PASS | - |
| 1933 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2032 - sec-vrf | PASS | - |
| 1934 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2033 - sec-vrf | PASS | - |
| 1935 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2034 - sec-vrf | PASS | - |
| 1936 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2035 - sec-vrf | PASS | - |
| 1937 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2036 - sec-vrf | PASS | - |
| 1938 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2037 - sec-vrf | PASS | - |
| 1939 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2038 - sec-vrf | PASS | - |
| 1940 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2039 - sec-vrf | PASS | - |
| 1941 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2040 - sec-vrf | PASS | - |
| 1942 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2041 - sec-vrf | PASS | - |
| 1943 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2042 - sec-vrf | PASS | - |
| 1944 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2043 - sec-vrf | PASS | - |
| 1945 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2044 - sec-vrf | PASS | - |
| 1946 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2045 - sec-vrf | PASS | - |
| 1947 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2046 - sec-vrf | PASS | - |
| 1948 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2047 - sec-vrf | PASS | - |
| 1949 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2048 - sec-vrf | PASS | - |
| 1950 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2049 - sec-vrf | PASS | - |
| 1951 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2050 - sec-vrf | PASS | - |
| 1952 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2051 - sec-vrf | PASS | - |
| 1953 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2052 - sec-vrf | PASS | - |
| 1954 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2053 - sec-vrf | PASS | - |
| 1955 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2054 - sec-vrf | PASS | - |
| 1956 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2055 - sec-vrf | PASS | - |
| 1957 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2056 - sec-vrf | PASS | - |
| 1958 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2057 - sec-vrf | PASS | - |
| 1959 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2058 - sec-vrf | PASS | - |
| 1960 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2059 - sec-vrf | PASS | - |
| 1961 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2060 - sec-vrf | PASS | - |
| 1962 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2061 - sec-vrf | PASS | - |
| 1963 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2062 - sec-vrf | PASS | - |
| 1964 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2063 - sec-vrf | PASS | - |
| 1965 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2064 - sec-vrf | PASS | - |
| 1966 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2065 - sec-vrf | PASS | - |
| 1967 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2066 - sec-vrf | PASS | - |
| 1968 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2067 - sec-vrf | PASS | - |
| 1969 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2068 - sec-vrf | PASS | - |
| 1970 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2069 - sec-vrf | PASS | - |
| 1971 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2070 - sec-vrf | PASS | - |
| 1972 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2071 - sec-vrf | PASS | - |
| 1973 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2072 - sec-vrf | PASS | - |
| 1974 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2073 - sec-vrf | PASS | - |
| 1975 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2074 - sec-vrf | PASS | - |
| 1976 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2075 - sec-vrf | PASS | - |
| 1977 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2076 - sec-vrf | PASS | - |
| 1978 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2077 - sec-vrf | PASS | - |
| 1979 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2078 - sec-vrf | PASS | - |
| 1980 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2079 - sec-vrf | PASS | - |
| 1981 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2080 - sec-vrf | PASS | - |
| 1982 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2081 - sec-vrf | PASS | - |
| 1983 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2082 - sec-vrf | PASS | - |
| 1984 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2083 - sec-vrf | PASS | - |
| 1985 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2084 - sec-vrf | PASS | - |
| 1986 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2085 - sec-vrf | PASS | - |
| 1987 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2086 - sec-vrf | PASS | - |
| 1988 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2087 - sec-vrf | PASS | - |
| 1989 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2088 - sec-vrf | PASS | - |
| 1990 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2089 - sec-vrf | PASS | - |
| 1991 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2090 - sec-vrf | PASS | - |
| 1992 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2091 - sec-vrf | PASS | - |
| 1993 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2092 - sec-vrf | PASS | - |
| 1994 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2093 - sec-vrf | PASS | - |
| 1995 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2094 - sec-vrf | PASS | - |
| 1996 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2095 - sec-vrf | PASS | - |
| 1997 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2096 - sec-vrf | PASS | - |
| 1998 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2097 - sec-vrf | PASS | - |
| 1999 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2098 - sec-vrf | PASS | - |
| 2000 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2099 - sec-vrf | PASS | - |
| 2001 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2100 - sec-vrf | PASS | - |
| 2002 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2101 - sec-vrf | PASS | - |
| 2003 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2102 - sec-vrf | PASS | - |
| 2004 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2103 - sec-vrf | PASS | - |
| 2005 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2104 - sec-vrf | PASS | - |
| 2006 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2105 - sec-vrf | PASS | - |
| 2007 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2106 - sec-vrf | PASS | - |
| 2008 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2107 - sec-vrf | PASS | - |
| 2009 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2108 - sec-vrf | PASS | - |
| 2010 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2109 - sec-vrf | PASS | - |
| 2011 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2110 - sec-vrf | PASS | - |
| 2012 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2111 - sec-vrf | PASS | - |
| 2013 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2112 - sec-vrf | PASS | - |
| 2014 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2113 - sec-vrf | PASS | - |
| 2015 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2114 - sec-vrf | PASS | - |
| 2016 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2115 - sec-vrf | PASS | - |
| 2017 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2116 - sec-vrf | PASS | - |
| 2018 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2117 - sec-vrf | PASS | - |
| 2019 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2118 - sec-vrf | PASS | - |
| 2020 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2119 - sec-vrf | PASS | - |
| 2021 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2120 - sec-vrf | PASS | - |
| 2022 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2121 - sec-vrf | PASS | - |
| 2023 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2122 - sec-vrf | PASS | - |
| 2024 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2123 - sec-vrf | PASS | - |
| 2025 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2124 - sec-vrf | PASS | - |
| 2026 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2125 - sec-vrf | PASS | - |
| 2027 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2126 - sec-vrf | PASS | - |
| 2028 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2127 - sec-vrf | PASS | - |
| 2029 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2128 - sec-vrf | PASS | - |
| 2030 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2129 - sec-vrf | PASS | - |
| 2031 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2130 - sec-vrf | PASS | - |
| 2032 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2131 - sec-vrf | PASS | - |
| 2033 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2132 - sec-vrf | PASS | - |
| 2034 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2133 - sec-vrf | PASS | - |
| 2035 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2134 - sec-vrf | PASS | - |
| 2036 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2135 - sec-vrf | PASS | - |
| 2037 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2136 - sec-vrf | PASS | - |
| 2038 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2137 - sec-vrf | PASS | - |
| 2039 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2138 - sec-vrf | PASS | - |
| 2040 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2139 - sec-vrf | PASS | - |
| 2041 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2140 - sec-vrf | PASS | - |
| 2042 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2141 - sec-vrf | PASS | - |
| 2043 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2142 - sec-vrf | PASS | - |
| 2044 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2143 - sec-vrf | PASS | - |
| 2045 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2144 - sec-vrf | PASS | - |
| 2046 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2145 - sec-vrf | PASS | - |
| 2047 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2146 - sec-vrf | PASS | - |
| 2048 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2147 - sec-vrf | PASS | - |
| 2049 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2148 - sec-vrf | PASS | - |
| 2050 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2149 - sec-vrf | PASS | - |
| 2051 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2150 - sec-vrf | PASS | - |
| 2052 | dc1p1_leaf2a_cal421 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4051 - MLAG_PEER_L3_iBGP: vrf sec | PASS | - |
| 2053 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 2054 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 2055 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan101 - com-vrf | PASS | - |
| 2056 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan102 - com-vrf | PASS | - |
| 2057 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan103 - com-vrf | PASS | - |
| 2058 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan104 - com-vrf | PASS | - |
| 2059 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan105 - com-vrf | PASS | - |
| 2060 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan106 - com-vrf | PASS | - |
| 2061 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan107 - com-vrf | PASS | - |
| 2062 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan108 - com-vrf | PASS | - |
| 2063 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan109 - com-vrf | PASS | - |
| 2064 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - com-vrf | PASS | - |
| 2065 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan111 - com-vrf | PASS | - |
| 2066 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan112 - com-vrf | PASS | - |
| 2067 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan113 - com-vrf | PASS | - |
| 2068 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan114 - com-vrf | PASS | - |
| 2069 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan115 - com-vrf | PASS | - |
| 2070 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan116 - com-vrf | PASS | - |
| 2071 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan117 - com-vrf | PASS | - |
| 2072 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan118 - com-vrf | PASS | - |
| 2073 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan119 - com-vrf | PASS | - |
| 2074 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - com-vrf | PASS | - |
| 2075 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan121 - com-vrf | PASS | - |
| 2076 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan122 - com-vrf | PASS | - |
| 2077 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan123 - com-vrf | PASS | - |
| 2078 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan124 - com-vrf | PASS | - |
| 2079 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan125 - com-vrf | PASS | - |
| 2080 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan126 - com-vrf | PASS | - |
| 2081 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan127 - com-vrf | PASS | - |
| 2082 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan128 - com-vrf | PASS | - |
| 2083 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan129 - com-vrf | PASS | - |
| 2084 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan130 - com-vrf | PASS | - |
| 2085 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan131 - com-vrf | PASS | - |
| 2086 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan132 - com-vrf | PASS | - |
| 2087 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan133 - com-vrf | PASS | - |
| 2088 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan134 - com-vrf | PASS | - |
| 2089 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan135 - com-vrf | PASS | - |
| 2090 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan136 - com-vrf | PASS | - |
| 2091 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan137 - com-vrf | PASS | - |
| 2092 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan138 - com-vrf | PASS | - |
| 2093 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan139 - com-vrf | PASS | - |
| 2094 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan140 - com-vrf | PASS | - |
| 2095 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan141 - com-vrf | PASS | - |
| 2096 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan142 - com-vrf | PASS | - |
| 2097 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan143 - com-vrf | PASS | - |
| 2098 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan144 - com-vrf | PASS | - |
| 2099 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan145 - com-vrf | PASS | - |
| 2100 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan146 - com-vrf | PASS | - |
| 2101 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan147 - com-vrf | PASS | - |
| 2102 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan148 - com-vrf | PASS | - |
| 2103 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan149 - com-vrf | PASS | - |
| 2104 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan150 - com-vrf | PASS | - |
| 2105 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan151 - com-vrf | PASS | - |
| 2106 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan152 - com-vrf | PASS | - |
| 2107 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan153 - com-vrf | PASS | - |
| 2108 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan154 - com-vrf | PASS | - |
| 2109 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan155 - com-vrf | PASS | - |
| 2110 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan156 - com-vrf | PASS | - |
| 2111 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan157 - com-vrf | PASS | - |
| 2112 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan158 - com-vrf | PASS | - |
| 2113 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan159 - com-vrf | PASS | - |
| 2114 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan160 - com-vrf | PASS | - |
| 2115 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan161 - com-vrf | PASS | - |
| 2116 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan162 - com-vrf | PASS | - |
| 2117 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan163 - com-vrf | PASS | - |
| 2118 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan164 - com-vrf | PASS | - |
| 2119 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan165 - com-vrf | PASS | - |
| 2120 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan166 - com-vrf | PASS | - |
| 2121 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan167 - com-vrf | PASS | - |
| 2122 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan168 - com-vrf | PASS | - |
| 2123 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan169 - com-vrf | PASS | - |
| 2124 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan170 - com-vrf | PASS | - |
| 2125 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan171 - com-vrf | PASS | - |
| 2126 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan172 - com-vrf | PASS | - |
| 2127 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan173 - com-vrf | PASS | - |
| 2128 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan174 - com-vrf | PASS | - |
| 2129 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan175 - com-vrf | PASS | - |
| 2130 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan176 - com-vrf | PASS | - |
| 2131 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan177 - com-vrf | PASS | - |
| 2132 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan178 - com-vrf | PASS | - |
| 2133 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan179 - com-vrf | PASS | - |
| 2134 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan180 - com-vrf | PASS | - |
| 2135 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan181 - com-vrf | PASS | - |
| 2136 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan182 - com-vrf | PASS | - |
| 2137 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan183 - com-vrf | PASS | - |
| 2138 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan184 - com-vrf | PASS | - |
| 2139 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan185 - com-vrf | PASS | - |
| 2140 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan186 - com-vrf | PASS | - |
| 2141 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan187 - com-vrf | PASS | - |
| 2142 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan188 - com-vrf | PASS | - |
| 2143 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan189 - com-vrf | PASS | - |
| 2144 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan190 - com-vrf | PASS | - |
| 2145 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan191 - com-vrf | PASS | - |
| 2146 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan192 - com-vrf | PASS | - |
| 2147 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan193 - com-vrf | PASS | - |
| 2148 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan194 - com-vrf | PASS | - |
| 2149 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan195 - com-vrf | PASS | - |
| 2150 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan196 - com-vrf | PASS | - |
| 2151 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan197 - com-vrf | PASS | - |
| 2152 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan198 - com-vrf | PASS | - |
| 2153 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan199 - com-vrf | PASS | - |
| 2154 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan200 - com-vrf | PASS | - |
| 2155 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan201 - com-vrf | PASS | - |
| 2156 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan202 - com-vrf | PASS | - |
| 2157 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan203 - com-vrf | PASS | - |
| 2158 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan204 - com-vrf | PASS | - |
| 2159 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan205 - com-vrf | PASS | - |
| 2160 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan206 - com-vrf | PASS | - |
| 2161 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan207 - com-vrf | PASS | - |
| 2162 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan208 - com-vrf | PASS | - |
| 2163 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan209 - com-vrf | PASS | - |
| 2164 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan210 - com-vrf | PASS | - |
| 2165 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan211 - com-vrf | PASS | - |
| 2166 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan212 - com-vrf | PASS | - |
| 2167 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan213 - com-vrf | PASS | - |
| 2168 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan214 - com-vrf | PASS | - |
| 2169 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan215 - com-vrf | PASS | - |
| 2170 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan216 - com-vrf | PASS | - |
| 2171 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan217 - com-vrf | PASS | - |
| 2172 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan218 - com-vrf | PASS | - |
| 2173 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan219 - com-vrf | PASS | - |
| 2174 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan220 - com-vrf | PASS | - |
| 2175 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan221 - com-vrf | PASS | - |
| 2176 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan222 - com-vrf | PASS | - |
| 2177 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan223 - com-vrf | PASS | - |
| 2178 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan224 - com-vrf | PASS | - |
| 2179 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan225 - com-vrf | PASS | - |
| 2180 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan226 - com-vrf | PASS | - |
| 2181 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan227 - com-vrf | PASS | - |
| 2182 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan228 - com-vrf | PASS | - |
| 2183 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan229 - com-vrf | PASS | - |
| 2184 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan230 - com-vrf | PASS | - |
| 2185 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan231 - com-vrf | PASS | - |
| 2186 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan232 - com-vrf | PASS | - |
| 2187 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan233 - com-vrf | PASS | - |
| 2188 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan234 - com-vrf | PASS | - |
| 2189 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan235 - com-vrf | PASS | - |
| 2190 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan236 - com-vrf | PASS | - |
| 2191 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan237 - com-vrf | PASS | - |
| 2192 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan238 - com-vrf | PASS | - |
| 2193 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan239 - com-vrf | PASS | - |
| 2194 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan240 - com-vrf | PASS | - |
| 2195 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan241 - com-vrf | PASS | - |
| 2196 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan242 - com-vrf | PASS | - |
| 2197 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan243 - com-vrf | PASS | - |
| 2198 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan244 - com-vrf | PASS | - |
| 2199 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan245 - com-vrf | PASS | - |
| 2200 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan246 - com-vrf | PASS | - |
| 2201 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan247 - com-vrf | PASS | - |
| 2202 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan248 - com-vrf | PASS | - |
| 2203 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan249 - com-vrf | PASS | - |
| 2204 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan250 - com-vrf | PASS | - |
| 2205 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan251 - com-vrf | PASS | - |
| 2206 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan252 - com-vrf | PASS | - |
| 2207 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan253 - com-vrf | PASS | - |
| 2208 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan254 - com-vrf | PASS | - |
| 2209 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan255 - com-vrf | PASS | - |
| 2210 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan256 - com-vrf | PASS | - |
| 2211 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan257 - com-vrf | PASS | - |
| 2212 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan258 - com-vrf | PASS | - |
| 2213 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan259 - com-vrf | PASS | - |
| 2214 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan260 - com-vrf | PASS | - |
| 2215 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan261 - com-vrf | PASS | - |
| 2216 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan262 - com-vrf | PASS | - |
| 2217 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan263 - com-vrf | PASS | - |
| 2218 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan264 - com-vrf | PASS | - |
| 2219 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan265 - com-vrf | PASS | - |
| 2220 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan266 - com-vrf | PASS | - |
| 2221 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan267 - com-vrf | PASS | - |
| 2222 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan268 - com-vrf | PASS | - |
| 2223 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan269 - com-vrf | PASS | - |
| 2224 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan270 - com-vrf | PASS | - |
| 2225 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan271 - com-vrf | PASS | - |
| 2226 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan272 - com-vrf | PASS | - |
| 2227 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan273 - com-vrf | PASS | - |
| 2228 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan274 - com-vrf | PASS | - |
| 2229 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan275 - com-vrf | PASS | - |
| 2230 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan276 - com-vrf | PASS | - |
| 2231 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan277 - com-vrf | PASS | - |
| 2232 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan278 - com-vrf | PASS | - |
| 2233 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan279 - com-vrf | PASS | - |
| 2234 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan280 - com-vrf | PASS | - |
| 2235 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan281 - com-vrf | PASS | - |
| 2236 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan282 - com-vrf | PASS | - |
| 2237 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan283 - com-vrf | PASS | - |
| 2238 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan284 - com-vrf | PASS | - |
| 2239 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan285 - com-vrf | PASS | - |
| 2240 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan286 - com-vrf | PASS | - |
| 2241 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan287 - com-vrf | PASS | - |
| 2242 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan288 - com-vrf | PASS | - |
| 2243 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan289 - com-vrf | PASS | - |
| 2244 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan290 - com-vrf | PASS | - |
| 2245 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan291 - com-vrf | PASS | - |
| 2246 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan292 - com-vrf | PASS | - |
| 2247 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan293 - com-vrf | PASS | - |
| 2248 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan294 - com-vrf | PASS | - |
| 2249 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan295 - com-vrf | PASS | - |
| 2250 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan296 - com-vrf | PASS | - |
| 2251 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan297 - com-vrf | PASS | - |
| 2252 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan298 - com-vrf | PASS | - |
| 2253 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan299 - com-vrf | PASS | - |
| 2254 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan300 - com-vrf | PASS | - |
| 2255 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan301 - com-vrf | PASS | - |
| 2256 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan302 - com-vrf | PASS | - |
| 2257 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan303 - com-vrf | PASS | - |
| 2258 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan304 - com-vrf | PASS | - |
| 2259 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan305 - com-vrf | PASS | - |
| 2260 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan306 - com-vrf | PASS | - |
| 2261 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan307 - com-vrf | PASS | - |
| 2262 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan308 - com-vrf | PASS | - |
| 2263 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan309 - com-vrf | PASS | - |
| 2264 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan310 - com-vrf | PASS | - |
| 2265 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan311 - com-vrf | PASS | - |
| 2266 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan312 - com-vrf | PASS | - |
| 2267 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan313 - com-vrf | PASS | - |
| 2268 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan314 - com-vrf | PASS | - |
| 2269 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan315 - com-vrf | PASS | - |
| 2270 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan316 - com-vrf | PASS | - |
| 2271 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan317 - com-vrf | PASS | - |
| 2272 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan318 - com-vrf | PASS | - |
| 2273 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan319 - com-vrf | PASS | - |
| 2274 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan320 - com-vrf | PASS | - |
| 2275 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan321 - com-vrf | PASS | - |
| 2276 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan322 - com-vrf | PASS | - |
| 2277 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan323 - com-vrf | PASS | - |
| 2278 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan324 - com-vrf | PASS | - |
| 2279 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan325 - com-vrf | PASS | - |
| 2280 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan326 - com-vrf | PASS | - |
| 2281 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan327 - com-vrf | PASS | - |
| 2282 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan328 - com-vrf | PASS | - |
| 2283 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan329 - com-vrf | PASS | - |
| 2284 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan330 - com-vrf | PASS | - |
| 2285 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan331 - com-vrf | PASS | - |
| 2286 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan332 - com-vrf | PASS | - |
| 2287 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan333 - com-vrf | PASS | - |
| 2288 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan334 - com-vrf | PASS | - |
| 2289 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan335 - com-vrf | PASS | - |
| 2290 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan336 - com-vrf | PASS | - |
| 2291 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan337 - com-vrf | PASS | - |
| 2292 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan338 - com-vrf | PASS | - |
| 2293 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan339 - com-vrf | PASS | - |
| 2294 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan340 - com-vrf | PASS | - |
| 2295 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan341 - com-vrf | PASS | - |
| 2296 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan342 - com-vrf | PASS | - |
| 2297 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan343 - com-vrf | PASS | - |
| 2298 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan344 - com-vrf | PASS | - |
| 2299 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan345 - com-vrf | PASS | - |
| 2300 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan346 - com-vrf | PASS | - |
| 2301 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan347 - com-vrf | PASS | - |
| 2302 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan348 - com-vrf | PASS | - |
| 2303 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan349 - com-vrf | PASS | - |
| 2304 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan350 - com-vrf | PASS | - |
| 2305 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan351 - com-vrf | PASS | - |
| 2306 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan352 - com-vrf | PASS | - |
| 2307 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan353 - com-vrf | PASS | - |
| 2308 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan354 - com-vrf | PASS | - |
| 2309 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan355 - com-vrf | PASS | - |
| 2310 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan356 - com-vrf | PASS | - |
| 2311 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan357 - com-vrf | PASS | - |
| 2312 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan358 - com-vrf | PASS | - |
| 2313 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan359 - com-vrf | PASS | - |
| 2314 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan360 - com-vrf | PASS | - |
| 2315 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan361 - com-vrf | PASS | - |
| 2316 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan362 - com-vrf | PASS | - |
| 2317 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan363 - com-vrf | PASS | - |
| 2318 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan364 - com-vrf | PASS | - |
| 2319 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan365 - com-vrf | PASS | - |
| 2320 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan366 - com-vrf | PASS | - |
| 2321 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan367 - com-vrf | PASS | - |
| 2322 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan368 - com-vrf | PASS | - |
| 2323 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan369 - com-vrf | PASS | - |
| 2324 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan370 - com-vrf | PASS | - |
| 2325 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan371 - com-vrf | PASS | - |
| 2326 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan372 - com-vrf | PASS | - |
| 2327 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan373 - com-vrf | PASS | - |
| 2328 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan374 - com-vrf | PASS | - |
| 2329 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan375 - com-vrf | PASS | - |
| 2330 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan376 - com-vrf | PASS | - |
| 2331 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan377 - com-vrf | PASS | - |
| 2332 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan378 - com-vrf | PASS | - |
| 2333 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan379 - com-vrf | PASS | - |
| 2334 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan380 - com-vrf | PASS | - |
| 2335 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan381 - com-vrf | PASS | - |
| 2336 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan382 - com-vrf | PASS | - |
| 2337 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan383 - com-vrf | PASS | - |
| 2338 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan384 - com-vrf | PASS | - |
| 2339 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan385 - com-vrf | PASS | - |
| 2340 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan386 - com-vrf | PASS | - |
| 2341 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan387 - com-vrf | PASS | - |
| 2342 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan388 - com-vrf | PASS | - |
| 2343 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan389 - com-vrf | PASS | - |
| 2344 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan390 - com-vrf | PASS | - |
| 2345 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan391 - com-vrf | PASS | - |
| 2346 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan392 - com-vrf | PASS | - |
| 2347 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan393 - com-vrf | PASS | - |
| 2348 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan394 - com-vrf | PASS | - |
| 2349 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan395 - com-vrf | PASS | - |
| 2350 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan396 - com-vrf | PASS | - |
| 2351 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan397 - com-vrf | PASS | - |
| 2352 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan398 - com-vrf | PASS | - |
| 2353 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan399 - com-vrf | PASS | - |
| 2354 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan400 - com-vrf | PASS | - |
| 2355 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan401 - com-vrf | PASS | - |
| 2356 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan402 - com-vrf | PASS | - |
| 2357 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan403 - com-vrf | PASS | - |
| 2358 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan404 - com-vrf | PASS | - |
| 2359 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan405 - com-vrf | PASS | - |
| 2360 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan406 - com-vrf | PASS | - |
| 2361 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan407 - com-vrf | PASS | - |
| 2362 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan408 - com-vrf | PASS | - |
| 2363 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan409 - com-vrf | PASS | - |
| 2364 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan410 - com-vrf | PASS | - |
| 2365 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan411 - com-vrf | PASS | - |
| 2366 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan412 - com-vrf | PASS | - |
| 2367 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan413 - com-vrf | PASS | - |
| 2368 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan414 - com-vrf | PASS | - |
| 2369 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan415 - com-vrf | PASS | - |
| 2370 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan416 - com-vrf | PASS | - |
| 2371 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan417 - com-vrf | PASS | - |
| 2372 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan418 - com-vrf | PASS | - |
| 2373 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan419 - com-vrf | PASS | - |
| 2374 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan420 - com-vrf | PASS | - |
| 2375 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan421 - com-vrf | PASS | - |
| 2376 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan422 - com-vrf | PASS | - |
| 2377 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan423 - com-vrf | PASS | - |
| 2378 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan424 - com-vrf | PASS | - |
| 2379 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan425 - com-vrf | PASS | - |
| 2380 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan426 - com-vrf | PASS | - |
| 2381 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan427 - com-vrf | PASS | - |
| 2382 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan428 - com-vrf | PASS | - |
| 2383 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan429 - com-vrf | PASS | - |
| 2384 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan430 - com-vrf | PASS | - |
| 2385 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan431 - com-vrf | PASS | - |
| 2386 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan432 - com-vrf | PASS | - |
| 2387 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan433 - com-vrf | PASS | - |
| 2388 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan434 - com-vrf | PASS | - |
| 2389 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan435 - com-vrf | PASS | - |
| 2390 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan436 - com-vrf | PASS | - |
| 2391 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan437 - com-vrf | PASS | - |
| 2392 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan438 - com-vrf | PASS | - |
| 2393 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan439 - com-vrf | PASS | - |
| 2394 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan440 - com-vrf | PASS | - |
| 2395 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan441 - com-vrf | PASS | - |
| 2396 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan442 - com-vrf | PASS | - |
| 2397 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan443 - com-vrf | PASS | - |
| 2398 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan444 - com-vrf | PASS | - |
| 2399 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan445 - com-vrf | PASS | - |
| 2400 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan446 - com-vrf | PASS | - |
| 2401 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan447 - com-vrf | PASS | - |
| 2402 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan448 - com-vrf | PASS | - |
| 2403 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan449 - com-vrf | PASS | - |
| 2404 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan450 - com-vrf | PASS | - |
| 2405 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4050 - MLAG_PEER_L3_iBGP: vrf com | PASS | - |
| 2406 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2001 - sec-vrf | PASS | - |
| 2407 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2002 - sec-vrf | PASS | - |
| 2408 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2003 - sec-vrf | PASS | - |
| 2409 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2004 - sec-vrf | PASS | - |
| 2410 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2005 - sec-vrf | PASS | - |
| 2411 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2006 - sec-vrf | PASS | - |
| 2412 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2007 - sec-vrf | PASS | - |
| 2413 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2008 - sec-vrf | PASS | - |
| 2414 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2009 - sec-vrf | PASS | - |
| 2415 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2010 - sec-vrf | PASS | - |
| 2416 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2011 - sec-vrf | PASS | - |
| 2417 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2012 - sec-vrf | PASS | - |
| 2418 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2013 - sec-vrf | PASS | - |
| 2419 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2014 - sec-vrf | PASS | - |
| 2420 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2015 - sec-vrf | PASS | - |
| 2421 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2016 - sec-vrf | PASS | - |
| 2422 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2017 - sec-vrf | PASS | - |
| 2423 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2018 - sec-vrf | PASS | - |
| 2424 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2019 - sec-vrf | PASS | - |
| 2425 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2020 - sec-vrf | PASS | - |
| 2426 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2021 - sec-vrf | PASS | - |
| 2427 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2022 - sec-vrf | PASS | - |
| 2428 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2023 - sec-vrf | PASS | - |
| 2429 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2024 - sec-vrf | PASS | - |
| 2430 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2025 - sec-vrf | PASS | - |
| 2431 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2026 - sec-vrf | PASS | - |
| 2432 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2027 - sec-vrf | PASS | - |
| 2433 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2028 - sec-vrf | PASS | - |
| 2434 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2029 - sec-vrf | PASS | - |
| 2435 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2030 - sec-vrf | PASS | - |
| 2436 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2031 - sec-vrf | PASS | - |
| 2437 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2032 - sec-vrf | PASS | - |
| 2438 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2033 - sec-vrf | PASS | - |
| 2439 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2034 - sec-vrf | PASS | - |
| 2440 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2035 - sec-vrf | PASS | - |
| 2441 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2036 - sec-vrf | PASS | - |
| 2442 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2037 - sec-vrf | PASS | - |
| 2443 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2038 - sec-vrf | PASS | - |
| 2444 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2039 - sec-vrf | PASS | - |
| 2445 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2040 - sec-vrf | PASS | - |
| 2446 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2041 - sec-vrf | PASS | - |
| 2447 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2042 - sec-vrf | PASS | - |
| 2448 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2043 - sec-vrf | PASS | - |
| 2449 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2044 - sec-vrf | PASS | - |
| 2450 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2045 - sec-vrf | PASS | - |
| 2451 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2046 - sec-vrf | PASS | - |
| 2452 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2047 - sec-vrf | PASS | - |
| 2453 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2048 - sec-vrf | PASS | - |
| 2454 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2049 - sec-vrf | PASS | - |
| 2455 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2050 - sec-vrf | PASS | - |
| 2456 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2051 - sec-vrf | PASS | - |
| 2457 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2052 - sec-vrf | PASS | - |
| 2458 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2053 - sec-vrf | PASS | - |
| 2459 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2054 - sec-vrf | PASS | - |
| 2460 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2055 - sec-vrf | PASS | - |
| 2461 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2056 - sec-vrf | PASS | - |
| 2462 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2057 - sec-vrf | PASS | - |
| 2463 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2058 - sec-vrf | PASS | - |
| 2464 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2059 - sec-vrf | PASS | - |
| 2465 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2060 - sec-vrf | PASS | - |
| 2466 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2061 - sec-vrf | PASS | - |
| 2467 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2062 - sec-vrf | PASS | - |
| 2468 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2063 - sec-vrf | PASS | - |
| 2469 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2064 - sec-vrf | PASS | - |
| 2470 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2065 - sec-vrf | PASS | - |
| 2471 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2066 - sec-vrf | PASS | - |
| 2472 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2067 - sec-vrf | PASS | - |
| 2473 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2068 - sec-vrf | PASS | - |
| 2474 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2069 - sec-vrf | PASS | - |
| 2475 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2070 - sec-vrf | PASS | - |
| 2476 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2071 - sec-vrf | PASS | - |
| 2477 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2072 - sec-vrf | PASS | - |
| 2478 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2073 - sec-vrf | PASS | - |
| 2479 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2074 - sec-vrf | PASS | - |
| 2480 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2075 - sec-vrf | PASS | - |
| 2481 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2076 - sec-vrf | PASS | - |
| 2482 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2077 - sec-vrf | PASS | - |
| 2483 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2078 - sec-vrf | PASS | - |
| 2484 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2079 - sec-vrf | PASS | - |
| 2485 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2080 - sec-vrf | PASS | - |
| 2486 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2081 - sec-vrf | PASS | - |
| 2487 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2082 - sec-vrf | PASS | - |
| 2488 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2083 - sec-vrf | PASS | - |
| 2489 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2084 - sec-vrf | PASS | - |
| 2490 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2085 - sec-vrf | PASS | - |
| 2491 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2086 - sec-vrf | PASS | - |
| 2492 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2087 - sec-vrf | PASS | - |
| 2493 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2088 - sec-vrf | PASS | - |
| 2494 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2089 - sec-vrf | PASS | - |
| 2495 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2090 - sec-vrf | PASS | - |
| 2496 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2091 - sec-vrf | PASS | - |
| 2497 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2092 - sec-vrf | PASS | - |
| 2498 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2093 - sec-vrf | PASS | - |
| 2499 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2094 - sec-vrf | PASS | - |
| 2500 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2095 - sec-vrf | PASS | - |
| 2501 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2096 - sec-vrf | PASS | - |
| 2502 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2097 - sec-vrf | PASS | - |
| 2503 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2098 - sec-vrf | PASS | - |
| 2504 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2099 - sec-vrf | PASS | - |
| 2505 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2100 - sec-vrf | PASS | - |
| 2506 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2101 - sec-vrf | PASS | - |
| 2507 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2102 - sec-vrf | PASS | - |
| 2508 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2103 - sec-vrf | PASS | - |
| 2509 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2104 - sec-vrf | PASS | - |
| 2510 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2105 - sec-vrf | PASS | - |
| 2511 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2106 - sec-vrf | PASS | - |
| 2512 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2107 - sec-vrf | PASS | - |
| 2513 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2108 - sec-vrf | PASS | - |
| 2514 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2109 - sec-vrf | PASS | - |
| 2515 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2110 - sec-vrf | PASS | - |
| 2516 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2111 - sec-vrf | PASS | - |
| 2517 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2112 - sec-vrf | PASS | - |
| 2518 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2113 - sec-vrf | PASS | - |
| 2519 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2114 - sec-vrf | PASS | - |
| 2520 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2115 - sec-vrf | PASS | - |
| 2521 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2116 - sec-vrf | PASS | - |
| 2522 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2117 - sec-vrf | PASS | - |
| 2523 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2118 - sec-vrf | PASS | - |
| 2524 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2119 - sec-vrf | PASS | - |
| 2525 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2120 - sec-vrf | PASS | - |
| 2526 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2121 - sec-vrf | PASS | - |
| 2527 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2122 - sec-vrf | PASS | - |
| 2528 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2123 - sec-vrf | PASS | - |
| 2529 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2124 - sec-vrf | PASS | - |
| 2530 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2125 - sec-vrf | PASS | - |
| 2531 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2126 - sec-vrf | PASS | - |
| 2532 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2127 - sec-vrf | PASS | - |
| 2533 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2128 - sec-vrf | PASS | - |
| 2534 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2129 - sec-vrf | PASS | - |
| 2535 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2130 - sec-vrf | PASS | - |
| 2536 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2131 - sec-vrf | PASS | - |
| 2537 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2132 - sec-vrf | PASS | - |
| 2538 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2133 - sec-vrf | PASS | - |
| 2539 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2134 - sec-vrf | PASS | - |
| 2540 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2135 - sec-vrf | PASS | - |
| 2541 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2136 - sec-vrf | PASS | - |
| 2542 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2137 - sec-vrf | PASS | - |
| 2543 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2138 - sec-vrf | PASS | - |
| 2544 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2139 - sec-vrf | PASS | - |
| 2545 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2140 - sec-vrf | PASS | - |
| 2546 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2141 - sec-vrf | PASS | - |
| 2547 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2142 - sec-vrf | PASS | - |
| 2548 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2143 - sec-vrf | PASS | - |
| 2549 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2144 - sec-vrf | PASS | - |
| 2550 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2145 - sec-vrf | PASS | - |
| 2551 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2146 - sec-vrf | PASS | - |
| 2552 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2147 - sec-vrf | PASS | - |
| 2553 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2148 - sec-vrf | PASS | - |
| 2554 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2149 - sec-vrf | PASS | - |
| 2555 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2150 - sec-vrf | PASS | - |
| 2556 | dc1p1_leaf2b_cal422 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4051 - MLAG_PEER_L3_iBGP: vrf sec | PASS | - |
| 2557 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 2558 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 2559 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan101 - com-vrf | PASS | - |
| 2560 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan102 - com-vrf | PASS | - |
| 2561 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan103 - com-vrf | PASS | - |
| 2562 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan104 - com-vrf | PASS | - |
| 2563 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan105 - com-vrf | PASS | - |
| 2564 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan106 - com-vrf | PASS | - |
| 2565 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan107 - com-vrf | PASS | - |
| 2566 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan108 - com-vrf | PASS | - |
| 2567 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan109 - com-vrf | PASS | - |
| 2568 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - com-vrf | PASS | - |
| 2569 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan111 - com-vrf | PASS | - |
| 2570 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan112 - com-vrf | PASS | - |
| 2571 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan113 - com-vrf | PASS | - |
| 2572 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan114 - com-vrf | PASS | - |
| 2573 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan115 - com-vrf | PASS | - |
| 2574 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan116 - com-vrf | PASS | - |
| 2575 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan117 - com-vrf | PASS | - |
| 2576 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan118 - com-vrf | PASS | - |
| 2577 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan119 - com-vrf | PASS | - |
| 2578 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - com-vrf | PASS | - |
| 2579 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan121 - com-vrf | PASS | - |
| 2580 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan122 - com-vrf | PASS | - |
| 2581 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan123 - com-vrf | PASS | - |
| 2582 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan124 - com-vrf | PASS | - |
| 2583 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan125 - com-vrf | PASS | - |
| 2584 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan126 - com-vrf | PASS | - |
| 2585 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan127 - com-vrf | PASS | - |
| 2586 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan128 - com-vrf | PASS | - |
| 2587 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan129 - com-vrf | PASS | - |
| 2588 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan130 - com-vrf | PASS | - |
| 2589 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan131 - com-vrf | PASS | - |
| 2590 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan132 - com-vrf | PASS | - |
| 2591 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan133 - com-vrf | PASS | - |
| 2592 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan134 - com-vrf | PASS | - |
| 2593 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan135 - com-vrf | PASS | - |
| 2594 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan136 - com-vrf | PASS | - |
| 2595 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan137 - com-vrf | PASS | - |
| 2596 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan138 - com-vrf | PASS | - |
| 2597 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan139 - com-vrf | PASS | - |
| 2598 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan140 - com-vrf | PASS | - |
| 2599 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan141 - com-vrf | PASS | - |
| 2600 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan142 - com-vrf | PASS | - |
| 2601 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan143 - com-vrf | PASS | - |
| 2602 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan144 - com-vrf | PASS | - |
| 2603 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan145 - com-vrf | PASS | - |
| 2604 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan146 - com-vrf | PASS | - |
| 2605 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan147 - com-vrf | PASS | - |
| 2606 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan148 - com-vrf | PASS | - |
| 2607 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan149 - com-vrf | PASS | - |
| 2608 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan150 - com-vrf | PASS | - |
| 2609 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan151 - com-vrf | PASS | - |
| 2610 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan152 - com-vrf | PASS | - |
| 2611 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan153 - com-vrf | PASS | - |
| 2612 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan154 - com-vrf | PASS | - |
| 2613 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan155 - com-vrf | PASS | - |
| 2614 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan156 - com-vrf | PASS | - |
| 2615 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan157 - com-vrf | PASS | - |
| 2616 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan158 - com-vrf | PASS | - |
| 2617 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan159 - com-vrf | PASS | - |
| 2618 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan160 - com-vrf | PASS | - |
| 2619 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan161 - com-vrf | PASS | - |
| 2620 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan162 - com-vrf | PASS | - |
| 2621 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan163 - com-vrf | PASS | - |
| 2622 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan164 - com-vrf | PASS | - |
| 2623 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan165 - com-vrf | PASS | - |
| 2624 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan166 - com-vrf | PASS | - |
| 2625 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan167 - com-vrf | PASS | - |
| 2626 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan168 - com-vrf | PASS | - |
| 2627 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan169 - com-vrf | PASS | - |
| 2628 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan170 - com-vrf | PASS | - |
| 2629 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan171 - com-vrf | PASS | - |
| 2630 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan172 - com-vrf | PASS | - |
| 2631 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan173 - com-vrf | PASS | - |
| 2632 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan174 - com-vrf | PASS | - |
| 2633 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan175 - com-vrf | PASS | - |
| 2634 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan176 - com-vrf | PASS | - |
| 2635 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan177 - com-vrf | PASS | - |
| 2636 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan178 - com-vrf | PASS | - |
| 2637 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan179 - com-vrf | PASS | - |
| 2638 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan180 - com-vrf | PASS | - |
| 2639 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan181 - com-vrf | PASS | - |
| 2640 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan182 - com-vrf | PASS | - |
| 2641 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan183 - com-vrf | PASS | - |
| 2642 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan184 - com-vrf | PASS | - |
| 2643 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan185 - com-vrf | PASS | - |
| 2644 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan186 - com-vrf | PASS | - |
| 2645 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan187 - com-vrf | PASS | - |
| 2646 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan188 - com-vrf | PASS | - |
| 2647 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan189 - com-vrf | PASS | - |
| 2648 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan190 - com-vrf | PASS | - |
| 2649 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan191 - com-vrf | PASS | - |
| 2650 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan192 - com-vrf | PASS | - |
| 2651 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan193 - com-vrf | PASS | - |
| 2652 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan194 - com-vrf | PASS | - |
| 2653 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan195 - com-vrf | PASS | - |
| 2654 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan196 - com-vrf | PASS | - |
| 2655 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan197 - com-vrf | PASS | - |
| 2656 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan198 - com-vrf | PASS | - |
| 2657 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan199 - com-vrf | PASS | - |
| 2658 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan200 - com-vrf | PASS | - |
| 2659 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan201 - com-vrf | PASS | - |
| 2660 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan202 - com-vrf | PASS | - |
| 2661 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan203 - com-vrf | PASS | - |
| 2662 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan204 - com-vrf | PASS | - |
| 2663 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan205 - com-vrf | PASS | - |
| 2664 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan206 - com-vrf | PASS | - |
| 2665 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan207 - com-vrf | PASS | - |
| 2666 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan208 - com-vrf | PASS | - |
| 2667 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan209 - com-vrf | PASS | - |
| 2668 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan210 - com-vrf | PASS | - |
| 2669 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan211 - com-vrf | PASS | - |
| 2670 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan212 - com-vrf | PASS | - |
| 2671 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan213 - com-vrf | PASS | - |
| 2672 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan214 - com-vrf | PASS | - |
| 2673 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan215 - com-vrf | PASS | - |
| 2674 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan216 - com-vrf | PASS | - |
| 2675 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan217 - com-vrf | PASS | - |
| 2676 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan218 - com-vrf | PASS | - |
| 2677 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan219 - com-vrf | PASS | - |
| 2678 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan220 - com-vrf | PASS | - |
| 2679 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan221 - com-vrf | PASS | - |
| 2680 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan222 - com-vrf | PASS | - |
| 2681 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan223 - com-vrf | PASS | - |
| 2682 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan224 - com-vrf | PASS | - |
| 2683 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan225 - com-vrf | PASS | - |
| 2684 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan226 - com-vrf | PASS | - |
| 2685 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan227 - com-vrf | PASS | - |
| 2686 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan228 - com-vrf | PASS | - |
| 2687 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan229 - com-vrf | PASS | - |
| 2688 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan230 - com-vrf | PASS | - |
| 2689 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan231 - com-vrf | PASS | - |
| 2690 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan232 - com-vrf | PASS | - |
| 2691 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan233 - com-vrf | PASS | - |
| 2692 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan234 - com-vrf | PASS | - |
| 2693 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan235 - com-vrf | PASS | - |
| 2694 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan236 - com-vrf | PASS | - |
| 2695 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan237 - com-vrf | PASS | - |
| 2696 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan238 - com-vrf | PASS | - |
| 2697 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan239 - com-vrf | PASS | - |
| 2698 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan240 - com-vrf | PASS | - |
| 2699 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan241 - com-vrf | PASS | - |
| 2700 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan242 - com-vrf | PASS | - |
| 2701 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan243 - com-vrf | PASS | - |
| 2702 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan244 - com-vrf | PASS | - |
| 2703 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan245 - com-vrf | PASS | - |
| 2704 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan246 - com-vrf | PASS | - |
| 2705 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan247 - com-vrf | PASS | - |
| 2706 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan248 - com-vrf | PASS | - |
| 2707 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan249 - com-vrf | PASS | - |
| 2708 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan250 - com-vrf | PASS | - |
| 2709 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan251 - com-vrf | PASS | - |
| 2710 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan252 - com-vrf | PASS | - |
| 2711 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan253 - com-vrf | PASS | - |
| 2712 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan254 - com-vrf | PASS | - |
| 2713 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan255 - com-vrf | PASS | - |
| 2714 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan256 - com-vrf | PASS | - |
| 2715 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan257 - com-vrf | PASS | - |
| 2716 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan258 - com-vrf | PASS | - |
| 2717 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan259 - com-vrf | PASS | - |
| 2718 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan260 - com-vrf | PASS | - |
| 2719 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan261 - com-vrf | PASS | - |
| 2720 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan262 - com-vrf | PASS | - |
| 2721 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan263 - com-vrf | PASS | - |
| 2722 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan264 - com-vrf | PASS | - |
| 2723 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan265 - com-vrf | PASS | - |
| 2724 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan266 - com-vrf | PASS | - |
| 2725 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan267 - com-vrf | PASS | - |
| 2726 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan268 - com-vrf | PASS | - |
| 2727 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan269 - com-vrf | PASS | - |
| 2728 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan270 - com-vrf | PASS | - |
| 2729 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan271 - com-vrf | PASS | - |
| 2730 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan272 - com-vrf | PASS | - |
| 2731 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan273 - com-vrf | PASS | - |
| 2732 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan274 - com-vrf | PASS | - |
| 2733 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan275 - com-vrf | PASS | - |
| 2734 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan276 - com-vrf | PASS | - |
| 2735 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan277 - com-vrf | PASS | - |
| 2736 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan278 - com-vrf | PASS | - |
| 2737 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan279 - com-vrf | PASS | - |
| 2738 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan280 - com-vrf | PASS | - |
| 2739 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan281 - com-vrf | PASS | - |
| 2740 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan282 - com-vrf | PASS | - |
| 2741 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan283 - com-vrf | PASS | - |
| 2742 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan284 - com-vrf | PASS | - |
| 2743 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan285 - com-vrf | PASS | - |
| 2744 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan286 - com-vrf | PASS | - |
| 2745 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan287 - com-vrf | PASS | - |
| 2746 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan288 - com-vrf | PASS | - |
| 2747 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan289 - com-vrf | PASS | - |
| 2748 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan290 - com-vrf | PASS | - |
| 2749 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan291 - com-vrf | PASS | - |
| 2750 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan292 - com-vrf | PASS | - |
| 2751 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan293 - com-vrf | PASS | - |
| 2752 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan294 - com-vrf | PASS | - |
| 2753 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan295 - com-vrf | PASS | - |
| 2754 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan296 - com-vrf | PASS | - |
| 2755 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan297 - com-vrf | PASS | - |
| 2756 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan298 - com-vrf | PASS | - |
| 2757 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan299 - com-vrf | PASS | - |
| 2758 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan300 - com-vrf | PASS | - |
| 2759 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan301 - com-vrf | PASS | - |
| 2760 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan302 - com-vrf | PASS | - |
| 2761 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan303 - com-vrf | PASS | - |
| 2762 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan304 - com-vrf | PASS | - |
| 2763 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan305 - com-vrf | PASS | - |
| 2764 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan306 - com-vrf | PASS | - |
| 2765 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan307 - com-vrf | PASS | - |
| 2766 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan308 - com-vrf | PASS | - |
| 2767 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan309 - com-vrf | PASS | - |
| 2768 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan310 - com-vrf | PASS | - |
| 2769 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan311 - com-vrf | PASS | - |
| 2770 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan312 - com-vrf | PASS | - |
| 2771 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan313 - com-vrf | PASS | - |
| 2772 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan314 - com-vrf | PASS | - |
| 2773 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan315 - com-vrf | PASS | - |
| 2774 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan316 - com-vrf | PASS | - |
| 2775 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan317 - com-vrf | PASS | - |
| 2776 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan318 - com-vrf | PASS | - |
| 2777 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan319 - com-vrf | PASS | - |
| 2778 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan320 - com-vrf | PASS | - |
| 2779 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan321 - com-vrf | PASS | - |
| 2780 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan322 - com-vrf | PASS | - |
| 2781 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan323 - com-vrf | PASS | - |
| 2782 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan324 - com-vrf | PASS | - |
| 2783 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan325 - com-vrf | PASS | - |
| 2784 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan326 - com-vrf | PASS | - |
| 2785 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan327 - com-vrf | PASS | - |
| 2786 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan328 - com-vrf | PASS | - |
| 2787 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan329 - com-vrf | PASS | - |
| 2788 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan330 - com-vrf | PASS | - |
| 2789 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan331 - com-vrf | PASS | - |
| 2790 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan332 - com-vrf | PASS | - |
| 2791 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan333 - com-vrf | PASS | - |
| 2792 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan334 - com-vrf | PASS | - |
| 2793 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan335 - com-vrf | PASS | - |
| 2794 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan336 - com-vrf | PASS | - |
| 2795 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan337 - com-vrf | PASS | - |
| 2796 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan338 - com-vrf | PASS | - |
| 2797 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan339 - com-vrf | PASS | - |
| 2798 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan340 - com-vrf | PASS | - |
| 2799 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan341 - com-vrf | PASS | - |
| 2800 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan342 - com-vrf | PASS | - |
| 2801 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan343 - com-vrf | PASS | - |
| 2802 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan344 - com-vrf | PASS | - |
| 2803 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan345 - com-vrf | PASS | - |
| 2804 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan346 - com-vrf | PASS | - |
| 2805 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan347 - com-vrf | PASS | - |
| 2806 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan348 - com-vrf | PASS | - |
| 2807 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan349 - com-vrf | PASS | - |
| 2808 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan350 - com-vrf | PASS | - |
| 2809 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan351 - com-vrf | PASS | - |
| 2810 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan352 - com-vrf | PASS | - |
| 2811 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan353 - com-vrf | PASS | - |
| 2812 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan354 - com-vrf | PASS | - |
| 2813 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan355 - com-vrf | PASS | - |
| 2814 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan356 - com-vrf | PASS | - |
| 2815 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan357 - com-vrf | PASS | - |
| 2816 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan358 - com-vrf | PASS | - |
| 2817 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan359 - com-vrf | PASS | - |
| 2818 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan360 - com-vrf | PASS | - |
| 2819 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan361 - com-vrf | PASS | - |
| 2820 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan362 - com-vrf | PASS | - |
| 2821 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan363 - com-vrf | PASS | - |
| 2822 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan364 - com-vrf | PASS | - |
| 2823 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan365 - com-vrf | PASS | - |
| 2824 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan366 - com-vrf | PASS | - |
| 2825 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan367 - com-vrf | PASS | - |
| 2826 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan368 - com-vrf | PASS | - |
| 2827 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan369 - com-vrf | PASS | - |
| 2828 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan370 - com-vrf | PASS | - |
| 2829 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan371 - com-vrf | PASS | - |
| 2830 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan372 - com-vrf | PASS | - |
| 2831 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan373 - com-vrf | PASS | - |
| 2832 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan374 - com-vrf | PASS | - |
| 2833 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan375 - com-vrf | PASS | - |
| 2834 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan376 - com-vrf | PASS | - |
| 2835 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan377 - com-vrf | PASS | - |
| 2836 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan378 - com-vrf | PASS | - |
| 2837 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan379 - com-vrf | PASS | - |
| 2838 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan380 - com-vrf | PASS | - |
| 2839 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan381 - com-vrf | PASS | - |
| 2840 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan382 - com-vrf | PASS | - |
| 2841 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan383 - com-vrf | PASS | - |
| 2842 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan384 - com-vrf | PASS | - |
| 2843 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan385 - com-vrf | PASS | - |
| 2844 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan386 - com-vrf | PASS | - |
| 2845 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan387 - com-vrf | PASS | - |
| 2846 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan388 - com-vrf | PASS | - |
| 2847 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan389 - com-vrf | PASS | - |
| 2848 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan390 - com-vrf | PASS | - |
| 2849 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan391 - com-vrf | PASS | - |
| 2850 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan392 - com-vrf | PASS | - |
| 2851 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan393 - com-vrf | PASS | - |
| 2852 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan394 - com-vrf | PASS | - |
| 2853 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan395 - com-vrf | PASS | - |
| 2854 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan396 - com-vrf | PASS | - |
| 2855 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan397 - com-vrf | PASS | - |
| 2856 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan398 - com-vrf | PASS | - |
| 2857 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan399 - com-vrf | PASS | - |
| 2858 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan400 - com-vrf | PASS | - |
| 2859 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan401 - com-vrf | PASS | - |
| 2860 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan402 - com-vrf | PASS | - |
| 2861 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan403 - com-vrf | PASS | - |
| 2862 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan404 - com-vrf | PASS | - |
| 2863 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan405 - com-vrf | PASS | - |
| 2864 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan406 - com-vrf | PASS | - |
| 2865 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan407 - com-vrf | PASS | - |
| 2866 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan408 - com-vrf | PASS | - |
| 2867 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan409 - com-vrf | PASS | - |
| 2868 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan410 - com-vrf | PASS | - |
| 2869 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan411 - com-vrf | PASS | - |
| 2870 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan412 - com-vrf | PASS | - |
| 2871 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan413 - com-vrf | PASS | - |
| 2872 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan414 - com-vrf | PASS | - |
| 2873 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan415 - com-vrf | PASS | - |
| 2874 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan416 - com-vrf | PASS | - |
| 2875 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan417 - com-vrf | PASS | - |
| 2876 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan418 - com-vrf | PASS | - |
| 2877 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan419 - com-vrf | PASS | - |
| 2878 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan420 - com-vrf | PASS | - |
| 2879 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan421 - com-vrf | PASS | - |
| 2880 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan422 - com-vrf | PASS | - |
| 2881 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan423 - com-vrf | PASS | - |
| 2882 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan424 - com-vrf | PASS | - |
| 2883 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan425 - com-vrf | PASS | - |
| 2884 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan426 - com-vrf | PASS | - |
| 2885 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan427 - com-vrf | PASS | - |
| 2886 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan428 - com-vrf | PASS | - |
| 2887 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan429 - com-vrf | PASS | - |
| 2888 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan430 - com-vrf | PASS | - |
| 2889 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan431 - com-vrf | PASS | - |
| 2890 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan432 - com-vrf | PASS | - |
| 2891 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan433 - com-vrf | PASS | - |
| 2892 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan434 - com-vrf | PASS | - |
| 2893 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan435 - com-vrf | PASS | - |
| 2894 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan436 - com-vrf | PASS | - |
| 2895 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan437 - com-vrf | PASS | - |
| 2896 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan438 - com-vrf | PASS | - |
| 2897 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan439 - com-vrf | PASS | - |
| 2898 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan440 - com-vrf | PASS | - |
| 2899 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan441 - com-vrf | PASS | - |
| 2900 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan442 - com-vrf | PASS | - |
| 2901 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan443 - com-vrf | PASS | - |
| 2902 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan444 - com-vrf | PASS | - |
| 2903 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan445 - com-vrf | PASS | - |
| 2904 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan446 - com-vrf | PASS | - |
| 2905 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan447 - com-vrf | PASS | - |
| 2906 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan448 - com-vrf | PASS | - |
| 2907 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan449 - com-vrf | PASS | - |
| 2908 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan450 - com-vrf | PASS | - |
| 2909 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4050 - MLAG_PEER_L3_iBGP: vrf com | PASS | - |
| 2910 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2001 - sec-vrf | PASS | - |
| 2911 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2002 - sec-vrf | PASS | - |
| 2912 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2003 - sec-vrf | PASS | - |
| 2913 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2004 - sec-vrf | PASS | - |
| 2914 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2005 - sec-vrf | PASS | - |
| 2915 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2006 - sec-vrf | PASS | - |
| 2916 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2007 - sec-vrf | PASS | - |
| 2917 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2008 - sec-vrf | PASS | - |
| 2918 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2009 - sec-vrf | PASS | - |
| 2919 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2010 - sec-vrf | PASS | - |
| 2920 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2011 - sec-vrf | PASS | - |
| 2921 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2012 - sec-vrf | PASS | - |
| 2922 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2013 - sec-vrf | PASS | - |
| 2923 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2014 - sec-vrf | PASS | - |
| 2924 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2015 - sec-vrf | PASS | - |
| 2925 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2016 - sec-vrf | PASS | - |
| 2926 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2017 - sec-vrf | PASS | - |
| 2927 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2018 - sec-vrf | PASS | - |
| 2928 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2019 - sec-vrf | PASS | - |
| 2929 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2020 - sec-vrf | PASS | - |
| 2930 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2021 - sec-vrf | PASS | - |
| 2931 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2022 - sec-vrf | PASS | - |
| 2932 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2023 - sec-vrf | PASS | - |
| 2933 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2024 - sec-vrf | PASS | - |
| 2934 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2025 - sec-vrf | PASS | - |
| 2935 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2026 - sec-vrf | PASS | - |
| 2936 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2027 - sec-vrf | PASS | - |
| 2937 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2028 - sec-vrf | PASS | - |
| 2938 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2029 - sec-vrf | PASS | - |
| 2939 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2030 - sec-vrf | PASS | - |
| 2940 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2031 - sec-vrf | PASS | - |
| 2941 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2032 - sec-vrf | PASS | - |
| 2942 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2033 - sec-vrf | PASS | - |
| 2943 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2034 - sec-vrf | PASS | - |
| 2944 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2035 - sec-vrf | PASS | - |
| 2945 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2036 - sec-vrf | PASS | - |
| 2946 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2037 - sec-vrf | PASS | - |
| 2947 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2038 - sec-vrf | PASS | - |
| 2948 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2039 - sec-vrf | PASS | - |
| 2949 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2040 - sec-vrf | PASS | - |
| 2950 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2041 - sec-vrf | PASS | - |
| 2951 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2042 - sec-vrf | PASS | - |
| 2952 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2043 - sec-vrf | PASS | - |
| 2953 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2044 - sec-vrf | PASS | - |
| 2954 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2045 - sec-vrf | PASS | - |
| 2955 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2046 - sec-vrf | PASS | - |
| 2956 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2047 - sec-vrf | PASS | - |
| 2957 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2048 - sec-vrf | PASS | - |
| 2958 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2049 - sec-vrf | PASS | - |
| 2959 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2050 - sec-vrf | PASS | - |
| 2960 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2051 - sec-vrf | PASS | - |
| 2961 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2052 - sec-vrf | PASS | - |
| 2962 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2053 - sec-vrf | PASS | - |
| 2963 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2054 - sec-vrf | PASS | - |
| 2964 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2055 - sec-vrf | PASS | - |
| 2965 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2056 - sec-vrf | PASS | - |
| 2966 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2057 - sec-vrf | PASS | - |
| 2967 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2058 - sec-vrf | PASS | - |
| 2968 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2059 - sec-vrf | PASS | - |
| 2969 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2060 - sec-vrf | PASS | - |
| 2970 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2061 - sec-vrf | PASS | - |
| 2971 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2062 - sec-vrf | PASS | - |
| 2972 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2063 - sec-vrf | PASS | - |
| 2973 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2064 - sec-vrf | PASS | - |
| 2974 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2065 - sec-vrf | PASS | - |
| 2975 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2066 - sec-vrf | PASS | - |
| 2976 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2067 - sec-vrf | PASS | - |
| 2977 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2068 - sec-vrf | PASS | - |
| 2978 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2069 - sec-vrf | PASS | - |
| 2979 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2070 - sec-vrf | PASS | - |
| 2980 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2071 - sec-vrf | PASS | - |
| 2981 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2072 - sec-vrf | PASS | - |
| 2982 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2073 - sec-vrf | PASS | - |
| 2983 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2074 - sec-vrf | PASS | - |
| 2984 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2075 - sec-vrf | PASS | - |
| 2985 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2076 - sec-vrf | PASS | - |
| 2986 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2077 - sec-vrf | PASS | - |
| 2987 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2078 - sec-vrf | PASS | - |
| 2988 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2079 - sec-vrf | PASS | - |
| 2989 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2080 - sec-vrf | PASS | - |
| 2990 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2081 - sec-vrf | PASS | - |
| 2991 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2082 - sec-vrf | PASS | - |
| 2992 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2083 - sec-vrf | PASS | - |
| 2993 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2084 - sec-vrf | PASS | - |
| 2994 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2085 - sec-vrf | PASS | - |
| 2995 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2086 - sec-vrf | PASS | - |
| 2996 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2087 - sec-vrf | PASS | - |
| 2997 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2088 - sec-vrf | PASS | - |
| 2998 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2089 - sec-vrf | PASS | - |
| 2999 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2090 - sec-vrf | PASS | - |
| 3000 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2091 - sec-vrf | PASS | - |
| 3001 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2092 - sec-vrf | PASS | - |
| 3002 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2093 - sec-vrf | PASS | - |
| 3003 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2094 - sec-vrf | PASS | - |
| 3004 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2095 - sec-vrf | PASS | - |
| 3005 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2096 - sec-vrf | PASS | - |
| 3006 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2097 - sec-vrf | PASS | - |
| 3007 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2098 - sec-vrf | PASS | - |
| 3008 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2099 - sec-vrf | PASS | - |
| 3009 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2100 - sec-vrf | PASS | - |
| 3010 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2101 - sec-vrf | PASS | - |
| 3011 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2102 - sec-vrf | PASS | - |
| 3012 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2103 - sec-vrf | PASS | - |
| 3013 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2104 - sec-vrf | PASS | - |
| 3014 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2105 - sec-vrf | PASS | - |
| 3015 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2106 - sec-vrf | PASS | - |
| 3016 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2107 - sec-vrf | PASS | - |
| 3017 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2108 - sec-vrf | PASS | - |
| 3018 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2109 - sec-vrf | PASS | - |
| 3019 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2110 - sec-vrf | PASS | - |
| 3020 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2111 - sec-vrf | PASS | - |
| 3021 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2112 - sec-vrf | PASS | - |
| 3022 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2113 - sec-vrf | PASS | - |
| 3023 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2114 - sec-vrf | PASS | - |
| 3024 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2115 - sec-vrf | PASS | - |
| 3025 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2116 - sec-vrf | PASS | - |
| 3026 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2117 - sec-vrf | PASS | - |
| 3027 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2118 - sec-vrf | PASS | - |
| 3028 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2119 - sec-vrf | PASS | - |
| 3029 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2120 - sec-vrf | PASS | - |
| 3030 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2121 - sec-vrf | PASS | - |
| 3031 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2122 - sec-vrf | PASS | - |
| 3032 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2123 - sec-vrf | PASS | - |
| 3033 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2124 - sec-vrf | PASS | - |
| 3034 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2125 - sec-vrf | PASS | - |
| 3035 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2126 - sec-vrf | PASS | - |
| 3036 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2127 - sec-vrf | PASS | - |
| 3037 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2128 - sec-vrf | PASS | - |
| 3038 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2129 - sec-vrf | PASS | - |
| 3039 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2130 - sec-vrf | PASS | - |
| 3040 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2131 - sec-vrf | PASS | - |
| 3041 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2132 - sec-vrf | PASS | - |
| 3042 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2133 - sec-vrf | PASS | - |
| 3043 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2134 - sec-vrf | PASS | - |
| 3044 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2135 - sec-vrf | PASS | - |
| 3045 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2136 - sec-vrf | PASS | - |
| 3046 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2137 - sec-vrf | PASS | - |
| 3047 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2138 - sec-vrf | PASS | - |
| 3048 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2139 - sec-vrf | PASS | - |
| 3049 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2140 - sec-vrf | PASS | - |
| 3050 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2141 - sec-vrf | PASS | - |
| 3051 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2142 - sec-vrf | PASS | - |
| 3052 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2143 - sec-vrf | PASS | - |
| 3053 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2144 - sec-vrf | PASS | - |
| 3054 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2145 - sec-vrf | PASS | - |
| 3055 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2146 - sec-vrf | PASS | - |
| 3056 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2147 - sec-vrf | PASS | - |
| 3057 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2148 - sec-vrf | PASS | - |
| 3058 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2149 - sec-vrf | PASS | - |
| 3059 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2150 - sec-vrf | PASS | - |
| 3060 | dc1p1_leaf3a_smd554 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4051 - MLAG_PEER_L3_iBGP: vrf sec | PASS | - |
| 3061 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 3062 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 3063 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan101 - com-vrf | PASS | - |
| 3064 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan102 - com-vrf | PASS | - |
| 3065 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan103 - com-vrf | PASS | - |
| 3066 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan104 - com-vrf | PASS | - |
| 3067 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan105 - com-vrf | PASS | - |
| 3068 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan106 - com-vrf | PASS | - |
| 3069 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan107 - com-vrf | PASS | - |
| 3070 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan108 - com-vrf | PASS | - |
| 3071 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan109 - com-vrf | PASS | - |
| 3072 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - com-vrf | PASS | - |
| 3073 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan111 - com-vrf | PASS | - |
| 3074 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan112 - com-vrf | PASS | - |
| 3075 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan113 - com-vrf | PASS | - |
| 3076 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan114 - com-vrf | PASS | - |
| 3077 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan115 - com-vrf | PASS | - |
| 3078 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan116 - com-vrf | PASS | - |
| 3079 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan117 - com-vrf | PASS | - |
| 3080 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan118 - com-vrf | PASS | - |
| 3081 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan119 - com-vrf | PASS | - |
| 3082 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - com-vrf | PASS | - |
| 3083 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan121 - com-vrf | PASS | - |
| 3084 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan122 - com-vrf | PASS | - |
| 3085 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan123 - com-vrf | PASS | - |
| 3086 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan124 - com-vrf | PASS | - |
| 3087 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan125 - com-vrf | PASS | - |
| 3088 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan126 - com-vrf | PASS | - |
| 3089 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan127 - com-vrf | PASS | - |
| 3090 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan128 - com-vrf | PASS | - |
| 3091 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan129 - com-vrf | PASS | - |
| 3092 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan130 - com-vrf | PASS | - |
| 3093 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan131 - com-vrf | PASS | - |
| 3094 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan132 - com-vrf | PASS | - |
| 3095 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan133 - com-vrf | PASS | - |
| 3096 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan134 - com-vrf | PASS | - |
| 3097 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan135 - com-vrf | PASS | - |
| 3098 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan136 - com-vrf | PASS | - |
| 3099 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan137 - com-vrf | PASS | - |
| 3100 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan138 - com-vrf | PASS | - |
| 3101 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan139 - com-vrf | PASS | - |
| 3102 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan140 - com-vrf | PASS | - |
| 3103 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan141 - com-vrf | PASS | - |
| 3104 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan142 - com-vrf | PASS | - |
| 3105 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan143 - com-vrf | PASS | - |
| 3106 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan144 - com-vrf | PASS | - |
| 3107 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan145 - com-vrf | PASS | - |
| 3108 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan146 - com-vrf | PASS | - |
| 3109 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan147 - com-vrf | PASS | - |
| 3110 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan148 - com-vrf | PASS | - |
| 3111 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan149 - com-vrf | PASS | - |
| 3112 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan150 - com-vrf | PASS | - |
| 3113 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan151 - com-vrf | PASS | - |
| 3114 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan152 - com-vrf | PASS | - |
| 3115 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan153 - com-vrf | PASS | - |
| 3116 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan154 - com-vrf | PASS | - |
| 3117 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan155 - com-vrf | PASS | - |
| 3118 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan156 - com-vrf | PASS | - |
| 3119 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan157 - com-vrf | PASS | - |
| 3120 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan158 - com-vrf | PASS | - |
| 3121 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan159 - com-vrf | PASS | - |
| 3122 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan160 - com-vrf | PASS | - |
| 3123 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan161 - com-vrf | PASS | - |
| 3124 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan162 - com-vrf | PASS | - |
| 3125 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan163 - com-vrf | PASS | - |
| 3126 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan164 - com-vrf | PASS | - |
| 3127 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan165 - com-vrf | PASS | - |
| 3128 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan166 - com-vrf | PASS | - |
| 3129 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan167 - com-vrf | PASS | - |
| 3130 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan168 - com-vrf | PASS | - |
| 3131 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan169 - com-vrf | PASS | - |
| 3132 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan170 - com-vrf | PASS | - |
| 3133 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan171 - com-vrf | PASS | - |
| 3134 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan172 - com-vrf | PASS | - |
| 3135 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan173 - com-vrf | PASS | - |
| 3136 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan174 - com-vrf | PASS | - |
| 3137 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan175 - com-vrf | PASS | - |
| 3138 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan176 - com-vrf | PASS | - |
| 3139 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan177 - com-vrf | PASS | - |
| 3140 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan178 - com-vrf | PASS | - |
| 3141 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan179 - com-vrf | PASS | - |
| 3142 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan180 - com-vrf | PASS | - |
| 3143 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan181 - com-vrf | PASS | - |
| 3144 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan182 - com-vrf | PASS | - |
| 3145 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan183 - com-vrf | PASS | - |
| 3146 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan184 - com-vrf | PASS | - |
| 3147 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan185 - com-vrf | PASS | - |
| 3148 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan186 - com-vrf | PASS | - |
| 3149 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan187 - com-vrf | PASS | - |
| 3150 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan188 - com-vrf | PASS | - |
| 3151 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan189 - com-vrf | PASS | - |
| 3152 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan190 - com-vrf | PASS | - |
| 3153 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan191 - com-vrf | PASS | - |
| 3154 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan192 - com-vrf | PASS | - |
| 3155 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan193 - com-vrf | PASS | - |
| 3156 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan194 - com-vrf | PASS | - |
| 3157 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan195 - com-vrf | PASS | - |
| 3158 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan196 - com-vrf | PASS | - |
| 3159 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan197 - com-vrf | PASS | - |
| 3160 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan198 - com-vrf | PASS | - |
| 3161 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan199 - com-vrf | PASS | - |
| 3162 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan200 - com-vrf | PASS | - |
| 3163 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan201 - com-vrf | PASS | - |
| 3164 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan202 - com-vrf | PASS | - |
| 3165 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan203 - com-vrf | PASS | - |
| 3166 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan204 - com-vrf | PASS | - |
| 3167 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan205 - com-vrf | PASS | - |
| 3168 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan206 - com-vrf | PASS | - |
| 3169 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan207 - com-vrf | PASS | - |
| 3170 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan208 - com-vrf | PASS | - |
| 3171 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan209 - com-vrf | PASS | - |
| 3172 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan210 - com-vrf | PASS | - |
| 3173 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan211 - com-vrf | PASS | - |
| 3174 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan212 - com-vrf | PASS | - |
| 3175 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan213 - com-vrf | PASS | - |
| 3176 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan214 - com-vrf | PASS | - |
| 3177 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan215 - com-vrf | PASS | - |
| 3178 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan216 - com-vrf | PASS | - |
| 3179 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan217 - com-vrf | PASS | - |
| 3180 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan218 - com-vrf | PASS | - |
| 3181 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan219 - com-vrf | PASS | - |
| 3182 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan220 - com-vrf | PASS | - |
| 3183 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan221 - com-vrf | PASS | - |
| 3184 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan222 - com-vrf | PASS | - |
| 3185 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan223 - com-vrf | PASS | - |
| 3186 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan224 - com-vrf | PASS | - |
| 3187 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan225 - com-vrf | PASS | - |
| 3188 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan226 - com-vrf | PASS | - |
| 3189 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan227 - com-vrf | PASS | - |
| 3190 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan228 - com-vrf | PASS | - |
| 3191 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan229 - com-vrf | PASS | - |
| 3192 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan230 - com-vrf | PASS | - |
| 3193 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan231 - com-vrf | PASS | - |
| 3194 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan232 - com-vrf | PASS | - |
| 3195 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan233 - com-vrf | PASS | - |
| 3196 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan234 - com-vrf | PASS | - |
| 3197 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan235 - com-vrf | PASS | - |
| 3198 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan236 - com-vrf | PASS | - |
| 3199 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan237 - com-vrf | PASS | - |
| 3200 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan238 - com-vrf | PASS | - |
| 3201 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan239 - com-vrf | PASS | - |
| 3202 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan240 - com-vrf | PASS | - |
| 3203 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan241 - com-vrf | PASS | - |
| 3204 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan242 - com-vrf | PASS | - |
| 3205 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan243 - com-vrf | PASS | - |
| 3206 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan244 - com-vrf | PASS | - |
| 3207 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan245 - com-vrf | PASS | - |
| 3208 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan246 - com-vrf | PASS | - |
| 3209 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan247 - com-vrf | PASS | - |
| 3210 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan248 - com-vrf | PASS | - |
| 3211 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan249 - com-vrf | PASS | - |
| 3212 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan250 - com-vrf | PASS | - |
| 3213 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan251 - com-vrf | PASS | - |
| 3214 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan252 - com-vrf | PASS | - |
| 3215 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan253 - com-vrf | PASS | - |
| 3216 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan254 - com-vrf | PASS | - |
| 3217 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan255 - com-vrf | PASS | - |
| 3218 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan256 - com-vrf | PASS | - |
| 3219 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan257 - com-vrf | PASS | - |
| 3220 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan258 - com-vrf | PASS | - |
| 3221 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan259 - com-vrf | PASS | - |
| 3222 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan260 - com-vrf | PASS | - |
| 3223 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan261 - com-vrf | PASS | - |
| 3224 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan262 - com-vrf | PASS | - |
| 3225 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan263 - com-vrf | PASS | - |
| 3226 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan264 - com-vrf | PASS | - |
| 3227 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan265 - com-vrf | PASS | - |
| 3228 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan266 - com-vrf | PASS | - |
| 3229 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan267 - com-vrf | PASS | - |
| 3230 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan268 - com-vrf | PASS | - |
| 3231 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan269 - com-vrf | PASS | - |
| 3232 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan270 - com-vrf | PASS | - |
| 3233 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan271 - com-vrf | PASS | - |
| 3234 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan272 - com-vrf | PASS | - |
| 3235 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan273 - com-vrf | PASS | - |
| 3236 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan274 - com-vrf | PASS | - |
| 3237 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan275 - com-vrf | PASS | - |
| 3238 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan276 - com-vrf | PASS | - |
| 3239 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan277 - com-vrf | PASS | - |
| 3240 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan278 - com-vrf | PASS | - |
| 3241 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan279 - com-vrf | PASS | - |
| 3242 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan280 - com-vrf | PASS | - |
| 3243 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan281 - com-vrf | PASS | - |
| 3244 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan282 - com-vrf | PASS | - |
| 3245 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan283 - com-vrf | PASS | - |
| 3246 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan284 - com-vrf | PASS | - |
| 3247 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan285 - com-vrf | PASS | - |
| 3248 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan286 - com-vrf | PASS | - |
| 3249 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan287 - com-vrf | PASS | - |
| 3250 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan288 - com-vrf | PASS | - |
| 3251 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan289 - com-vrf | PASS | - |
| 3252 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan290 - com-vrf | PASS | - |
| 3253 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan291 - com-vrf | PASS | - |
| 3254 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan292 - com-vrf | PASS | - |
| 3255 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan293 - com-vrf | PASS | - |
| 3256 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan294 - com-vrf | PASS | - |
| 3257 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan295 - com-vrf | PASS | - |
| 3258 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan296 - com-vrf | PASS | - |
| 3259 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan297 - com-vrf | PASS | - |
| 3260 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan298 - com-vrf | PASS | - |
| 3261 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan299 - com-vrf | PASS | - |
| 3262 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan300 - com-vrf | PASS | - |
| 3263 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan301 - com-vrf | PASS | - |
| 3264 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan302 - com-vrf | PASS | - |
| 3265 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan303 - com-vrf | PASS | - |
| 3266 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan304 - com-vrf | PASS | - |
| 3267 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan305 - com-vrf | PASS | - |
| 3268 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan306 - com-vrf | PASS | - |
| 3269 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan307 - com-vrf | PASS | - |
| 3270 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan308 - com-vrf | PASS | - |
| 3271 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan309 - com-vrf | PASS | - |
| 3272 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan310 - com-vrf | PASS | - |
| 3273 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan311 - com-vrf | PASS | - |
| 3274 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan312 - com-vrf | PASS | - |
| 3275 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan313 - com-vrf | PASS | - |
| 3276 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan314 - com-vrf | PASS | - |
| 3277 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan315 - com-vrf | PASS | - |
| 3278 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan316 - com-vrf | PASS | - |
| 3279 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan317 - com-vrf | PASS | - |
| 3280 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan318 - com-vrf | PASS | - |
| 3281 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan319 - com-vrf | PASS | - |
| 3282 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan320 - com-vrf | PASS | - |
| 3283 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan321 - com-vrf | PASS | - |
| 3284 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan322 - com-vrf | PASS | - |
| 3285 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan323 - com-vrf | PASS | - |
| 3286 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan324 - com-vrf | PASS | - |
| 3287 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan325 - com-vrf | PASS | - |
| 3288 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan326 - com-vrf | PASS | - |
| 3289 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan327 - com-vrf | PASS | - |
| 3290 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan328 - com-vrf | PASS | - |
| 3291 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan329 - com-vrf | PASS | - |
| 3292 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan330 - com-vrf | PASS | - |
| 3293 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan331 - com-vrf | PASS | - |
| 3294 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan332 - com-vrf | PASS | - |
| 3295 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan333 - com-vrf | PASS | - |
| 3296 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan334 - com-vrf | PASS | - |
| 3297 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan335 - com-vrf | PASS | - |
| 3298 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan336 - com-vrf | PASS | - |
| 3299 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan337 - com-vrf | PASS | - |
| 3300 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan338 - com-vrf | PASS | - |
| 3301 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan339 - com-vrf | PASS | - |
| 3302 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan340 - com-vrf | PASS | - |
| 3303 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan341 - com-vrf | PASS | - |
| 3304 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan342 - com-vrf | PASS | - |
| 3305 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan343 - com-vrf | PASS | - |
| 3306 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan344 - com-vrf | PASS | - |
| 3307 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan345 - com-vrf | PASS | - |
| 3308 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan346 - com-vrf | PASS | - |
| 3309 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan347 - com-vrf | PASS | - |
| 3310 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan348 - com-vrf | PASS | - |
| 3311 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan349 - com-vrf | PASS | - |
| 3312 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan350 - com-vrf | PASS | - |
| 3313 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan351 - com-vrf | PASS | - |
| 3314 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan352 - com-vrf | PASS | - |
| 3315 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan353 - com-vrf | PASS | - |
| 3316 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan354 - com-vrf | PASS | - |
| 3317 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan355 - com-vrf | PASS | - |
| 3318 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan356 - com-vrf | PASS | - |
| 3319 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan357 - com-vrf | PASS | - |
| 3320 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan358 - com-vrf | PASS | - |
| 3321 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan359 - com-vrf | PASS | - |
| 3322 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan360 - com-vrf | PASS | - |
| 3323 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan361 - com-vrf | PASS | - |
| 3324 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan362 - com-vrf | PASS | - |
| 3325 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan363 - com-vrf | PASS | - |
| 3326 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan364 - com-vrf | PASS | - |
| 3327 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan365 - com-vrf | PASS | - |
| 3328 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan366 - com-vrf | PASS | - |
| 3329 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan367 - com-vrf | PASS | - |
| 3330 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan368 - com-vrf | PASS | - |
| 3331 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan369 - com-vrf | PASS | - |
| 3332 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan370 - com-vrf | PASS | - |
| 3333 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan371 - com-vrf | PASS | - |
| 3334 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan372 - com-vrf | PASS | - |
| 3335 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan373 - com-vrf | PASS | - |
| 3336 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan374 - com-vrf | PASS | - |
| 3337 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan375 - com-vrf | PASS | - |
| 3338 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan376 - com-vrf | PASS | - |
| 3339 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan377 - com-vrf | PASS | - |
| 3340 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan378 - com-vrf | PASS | - |
| 3341 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan379 - com-vrf | PASS | - |
| 3342 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan380 - com-vrf | PASS | - |
| 3343 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan381 - com-vrf | PASS | - |
| 3344 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan382 - com-vrf | PASS | - |
| 3345 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan383 - com-vrf | PASS | - |
| 3346 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan384 - com-vrf | PASS | - |
| 3347 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan385 - com-vrf | PASS | - |
| 3348 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan386 - com-vrf | PASS | - |
| 3349 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan387 - com-vrf | PASS | - |
| 3350 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan388 - com-vrf | PASS | - |
| 3351 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan389 - com-vrf | PASS | - |
| 3352 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan390 - com-vrf | PASS | - |
| 3353 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan391 - com-vrf | PASS | - |
| 3354 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan392 - com-vrf | PASS | - |
| 3355 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan393 - com-vrf | PASS | - |
| 3356 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan394 - com-vrf | PASS | - |
| 3357 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan395 - com-vrf | PASS | - |
| 3358 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan396 - com-vrf | PASS | - |
| 3359 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan397 - com-vrf | PASS | - |
| 3360 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan398 - com-vrf | PASS | - |
| 3361 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan399 - com-vrf | PASS | - |
| 3362 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan400 - com-vrf | PASS | - |
| 3363 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan401 - com-vrf | PASS | - |
| 3364 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan402 - com-vrf | PASS | - |
| 3365 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan403 - com-vrf | PASS | - |
| 3366 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan404 - com-vrf | PASS | - |
| 3367 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan405 - com-vrf | PASS | - |
| 3368 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan406 - com-vrf | PASS | - |
| 3369 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan407 - com-vrf | PASS | - |
| 3370 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan408 - com-vrf | PASS | - |
| 3371 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan409 - com-vrf | PASS | - |
| 3372 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan410 - com-vrf | PASS | - |
| 3373 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan411 - com-vrf | PASS | - |
| 3374 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan412 - com-vrf | PASS | - |
| 3375 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan413 - com-vrf | PASS | - |
| 3376 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan414 - com-vrf | PASS | - |
| 3377 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan415 - com-vrf | PASS | - |
| 3378 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan416 - com-vrf | PASS | - |
| 3379 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan417 - com-vrf | PASS | - |
| 3380 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan418 - com-vrf | PASS | - |
| 3381 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan419 - com-vrf | PASS | - |
| 3382 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan420 - com-vrf | PASS | - |
| 3383 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan421 - com-vrf | PASS | - |
| 3384 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan422 - com-vrf | PASS | - |
| 3385 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan423 - com-vrf | PASS | - |
| 3386 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan424 - com-vrf | PASS | - |
| 3387 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan425 - com-vrf | PASS | - |
| 3388 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan426 - com-vrf | PASS | - |
| 3389 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan427 - com-vrf | PASS | - |
| 3390 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan428 - com-vrf | PASS | - |
| 3391 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan429 - com-vrf | PASS | - |
| 3392 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan430 - com-vrf | PASS | - |
| 3393 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan431 - com-vrf | PASS | - |
| 3394 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan432 - com-vrf | PASS | - |
| 3395 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan433 - com-vrf | PASS | - |
| 3396 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan434 - com-vrf | PASS | - |
| 3397 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan435 - com-vrf | PASS | - |
| 3398 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan436 - com-vrf | PASS | - |
| 3399 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan437 - com-vrf | PASS | - |
| 3400 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan438 - com-vrf | PASS | - |
| 3401 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan439 - com-vrf | PASS | - |
| 3402 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan440 - com-vrf | PASS | - |
| 3403 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan441 - com-vrf | PASS | - |
| 3404 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan442 - com-vrf | PASS | - |
| 3405 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan443 - com-vrf | PASS | - |
| 3406 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan444 - com-vrf | PASS | - |
| 3407 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan445 - com-vrf | PASS | - |
| 3408 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan446 - com-vrf | PASS | - |
| 3409 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan447 - com-vrf | PASS | - |
| 3410 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan448 - com-vrf | PASS | - |
| 3411 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan449 - com-vrf | PASS | - |
| 3412 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan450 - com-vrf | PASS | - |
| 3413 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4050 - MLAG_PEER_L3_iBGP: vrf com | PASS | - |
| 3414 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2001 - sec-vrf | PASS | - |
| 3415 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2002 - sec-vrf | PASS | - |
| 3416 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2003 - sec-vrf | PASS | - |
| 3417 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2004 - sec-vrf | PASS | - |
| 3418 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2005 - sec-vrf | PASS | - |
| 3419 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2006 - sec-vrf | PASS | - |
| 3420 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2007 - sec-vrf | PASS | - |
| 3421 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2008 - sec-vrf | PASS | - |
| 3422 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2009 - sec-vrf | PASS | - |
| 3423 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2010 - sec-vrf | PASS | - |
| 3424 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2011 - sec-vrf | PASS | - |
| 3425 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2012 - sec-vrf | PASS | - |
| 3426 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2013 - sec-vrf | PASS | - |
| 3427 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2014 - sec-vrf | PASS | - |
| 3428 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2015 - sec-vrf | PASS | - |
| 3429 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2016 - sec-vrf | PASS | - |
| 3430 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2017 - sec-vrf | PASS | - |
| 3431 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2018 - sec-vrf | PASS | - |
| 3432 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2019 - sec-vrf | PASS | - |
| 3433 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2020 - sec-vrf | PASS | - |
| 3434 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2021 - sec-vrf | PASS | - |
| 3435 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2022 - sec-vrf | PASS | - |
| 3436 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2023 - sec-vrf | PASS | - |
| 3437 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2024 - sec-vrf | PASS | - |
| 3438 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2025 - sec-vrf | PASS | - |
| 3439 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2026 - sec-vrf | PASS | - |
| 3440 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2027 - sec-vrf | PASS | - |
| 3441 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2028 - sec-vrf | PASS | - |
| 3442 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2029 - sec-vrf | PASS | - |
| 3443 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2030 - sec-vrf | PASS | - |
| 3444 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2031 - sec-vrf | PASS | - |
| 3445 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2032 - sec-vrf | PASS | - |
| 3446 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2033 - sec-vrf | PASS | - |
| 3447 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2034 - sec-vrf | PASS | - |
| 3448 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2035 - sec-vrf | PASS | - |
| 3449 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2036 - sec-vrf | PASS | - |
| 3450 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2037 - sec-vrf | PASS | - |
| 3451 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2038 - sec-vrf | PASS | - |
| 3452 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2039 - sec-vrf | PASS | - |
| 3453 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2040 - sec-vrf | PASS | - |
| 3454 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2041 - sec-vrf | PASS | - |
| 3455 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2042 - sec-vrf | PASS | - |
| 3456 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2043 - sec-vrf | PASS | - |
| 3457 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2044 - sec-vrf | PASS | - |
| 3458 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2045 - sec-vrf | PASS | - |
| 3459 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2046 - sec-vrf | PASS | - |
| 3460 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2047 - sec-vrf | PASS | - |
| 3461 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2048 - sec-vrf | PASS | - |
| 3462 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2049 - sec-vrf | PASS | - |
| 3463 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2050 - sec-vrf | PASS | - |
| 3464 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2051 - sec-vrf | PASS | - |
| 3465 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2052 - sec-vrf | PASS | - |
| 3466 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2053 - sec-vrf | PASS | - |
| 3467 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2054 - sec-vrf | PASS | - |
| 3468 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2055 - sec-vrf | PASS | - |
| 3469 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2056 - sec-vrf | PASS | - |
| 3470 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2057 - sec-vrf | PASS | - |
| 3471 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2058 - sec-vrf | PASS | - |
| 3472 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2059 - sec-vrf | PASS | - |
| 3473 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2060 - sec-vrf | PASS | - |
| 3474 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2061 - sec-vrf | PASS | - |
| 3475 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2062 - sec-vrf | PASS | - |
| 3476 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2063 - sec-vrf | PASS | - |
| 3477 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2064 - sec-vrf | PASS | - |
| 3478 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2065 - sec-vrf | PASS | - |
| 3479 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2066 - sec-vrf | PASS | - |
| 3480 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2067 - sec-vrf | PASS | - |
| 3481 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2068 - sec-vrf | PASS | - |
| 3482 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2069 - sec-vrf | PASS | - |
| 3483 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2070 - sec-vrf | PASS | - |
| 3484 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2071 - sec-vrf | PASS | - |
| 3485 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2072 - sec-vrf | PASS | - |
| 3486 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2073 - sec-vrf | PASS | - |
| 3487 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2074 - sec-vrf | PASS | - |
| 3488 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2075 - sec-vrf | PASS | - |
| 3489 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2076 - sec-vrf | PASS | - |
| 3490 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2077 - sec-vrf | PASS | - |
| 3491 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2078 - sec-vrf | PASS | - |
| 3492 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2079 - sec-vrf | PASS | - |
| 3493 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2080 - sec-vrf | PASS | - |
| 3494 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2081 - sec-vrf | PASS | - |
| 3495 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2082 - sec-vrf | PASS | - |
| 3496 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2083 - sec-vrf | PASS | - |
| 3497 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2084 - sec-vrf | PASS | - |
| 3498 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2085 - sec-vrf | PASS | - |
| 3499 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2086 - sec-vrf | PASS | - |
| 3500 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2087 - sec-vrf | PASS | - |
| 3501 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2088 - sec-vrf | PASS | - |
| 3502 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2089 - sec-vrf | PASS | - |
| 3503 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2090 - sec-vrf | PASS | - |
| 3504 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2091 - sec-vrf | PASS | - |
| 3505 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2092 - sec-vrf | PASS | - |
| 3506 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2093 - sec-vrf | PASS | - |
| 3507 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2094 - sec-vrf | PASS | - |
| 3508 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2095 - sec-vrf | PASS | - |
| 3509 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2096 - sec-vrf | PASS | - |
| 3510 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2097 - sec-vrf | PASS | - |
| 3511 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2098 - sec-vrf | PASS | - |
| 3512 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2099 - sec-vrf | PASS | - |
| 3513 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2100 - sec-vrf | PASS | - |
| 3514 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2101 - sec-vrf | PASS | - |
| 3515 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2102 - sec-vrf | PASS | - |
| 3516 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2103 - sec-vrf | PASS | - |
| 3517 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2104 - sec-vrf | PASS | - |
| 3518 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2105 - sec-vrf | PASS | - |
| 3519 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2106 - sec-vrf | PASS | - |
| 3520 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2107 - sec-vrf | PASS | - |
| 3521 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2108 - sec-vrf | PASS | - |
| 3522 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2109 - sec-vrf | PASS | - |
| 3523 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2110 - sec-vrf | PASS | - |
| 3524 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2111 - sec-vrf | PASS | - |
| 3525 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2112 - sec-vrf | PASS | - |
| 3526 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2113 - sec-vrf | PASS | - |
| 3527 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2114 - sec-vrf | PASS | - |
| 3528 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2115 - sec-vrf | PASS | - |
| 3529 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2116 - sec-vrf | PASS | - |
| 3530 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2117 - sec-vrf | PASS | - |
| 3531 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2118 - sec-vrf | PASS | - |
| 3532 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2119 - sec-vrf | PASS | - |
| 3533 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2120 - sec-vrf | PASS | - |
| 3534 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2121 - sec-vrf | PASS | - |
| 3535 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2122 - sec-vrf | PASS | - |
| 3536 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2123 - sec-vrf | PASS | - |
| 3537 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2124 - sec-vrf | PASS | - |
| 3538 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2125 - sec-vrf | PASS | - |
| 3539 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2126 - sec-vrf | PASS | - |
| 3540 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2127 - sec-vrf | PASS | - |
| 3541 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2128 - sec-vrf | PASS | - |
| 3542 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2129 - sec-vrf | PASS | - |
| 3543 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2130 - sec-vrf | PASS | - |
| 3544 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2131 - sec-vrf | PASS | - |
| 3545 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2132 - sec-vrf | PASS | - |
| 3546 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2133 - sec-vrf | PASS | - |
| 3547 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2134 - sec-vrf | PASS | - |
| 3548 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2135 - sec-vrf | PASS | - |
| 3549 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2136 - sec-vrf | PASS | - |
| 3550 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2137 - sec-vrf | PASS | - |
| 3551 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2138 - sec-vrf | PASS | - |
| 3552 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2139 - sec-vrf | PASS | - |
| 3553 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2140 - sec-vrf | PASS | - |
| 3554 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2141 - sec-vrf | PASS | - |
| 3555 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2142 - sec-vrf | PASS | - |
| 3556 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2143 - sec-vrf | PASS | - |
| 3557 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2144 - sec-vrf | PASS | - |
| 3558 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2145 - sec-vrf | PASS | - |
| 3559 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2146 - sec-vrf | PASS | - |
| 3560 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2147 - sec-vrf | PASS | - |
| 3561 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2148 - sec-vrf | PASS | - |
| 3562 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2149 - sec-vrf | PASS | - |
| 3563 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2150 - sec-vrf | PASS | - |
| 3564 | dc1p1_leaf3b_smd555 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4051 - MLAG_PEER_L3_iBGP: vrf sec | PASS | - |
| 3565 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan101 - com-vrf | PASS | - |
| 3566 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan102 - com-vrf | PASS | - |
| 3567 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan103 - com-vrf | PASS | - |
| 3568 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan104 - com-vrf | PASS | - |
| 3569 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan105 - com-vrf | PASS | - |
| 3570 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan106 - com-vrf | PASS | - |
| 3571 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan107 - com-vrf | PASS | - |
| 3572 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan108 - com-vrf | PASS | - |
| 3573 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan109 - com-vrf | PASS | - |
| 3574 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - com-vrf | PASS | - |
| 3575 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan111 - com-vrf | PASS | - |
| 3576 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan112 - com-vrf | PASS | - |
| 3577 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan113 - com-vrf | PASS | - |
| 3578 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan114 - com-vrf | PASS | - |
| 3579 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan115 - com-vrf | PASS | - |
| 3580 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan116 - com-vrf | PASS | - |
| 3581 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan117 - com-vrf | PASS | - |
| 3582 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan118 - com-vrf | PASS | - |
| 3583 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan119 - com-vrf | PASS | - |
| 3584 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - com-vrf | PASS | - |
| 3585 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan121 - com-vrf | PASS | - |
| 3586 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan122 - com-vrf | PASS | - |
| 3587 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan123 - com-vrf | PASS | - |
| 3588 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan124 - com-vrf | PASS | - |
| 3589 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan125 - com-vrf | PASS | - |
| 3590 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan126 - com-vrf | PASS | - |
| 3591 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan127 - com-vrf | PASS | - |
| 3592 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan128 - com-vrf | PASS | - |
| 3593 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan129 - com-vrf | PASS | - |
| 3594 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan130 - com-vrf | PASS | - |
| 3595 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan131 - com-vrf | PASS | - |
| 3596 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan132 - com-vrf | PASS | - |
| 3597 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan133 - com-vrf | PASS | - |
| 3598 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan134 - com-vrf | PASS | - |
| 3599 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan135 - com-vrf | PASS | - |
| 3600 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan136 - com-vrf | PASS | - |
| 3601 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan137 - com-vrf | PASS | - |
| 3602 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan138 - com-vrf | PASS | - |
| 3603 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan139 - com-vrf | PASS | - |
| 3604 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan140 - com-vrf | PASS | - |
| 3605 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan141 - com-vrf | PASS | - |
| 3606 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan142 - com-vrf | PASS | - |
| 3607 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan143 - com-vrf | PASS | - |
| 3608 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan144 - com-vrf | PASS | - |
| 3609 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan145 - com-vrf | PASS | - |
| 3610 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan146 - com-vrf | PASS | - |
| 3611 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan147 - com-vrf | PASS | - |
| 3612 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan148 - com-vrf | PASS | - |
| 3613 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan149 - com-vrf | PASS | - |
| 3614 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan150 - com-vrf | PASS | - |
| 3615 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan151 - com-vrf | PASS | - |
| 3616 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan152 - com-vrf | PASS | - |
| 3617 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan153 - com-vrf | PASS | - |
| 3618 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan154 - com-vrf | PASS | - |
| 3619 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan155 - com-vrf | PASS | - |
| 3620 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan156 - com-vrf | PASS | - |
| 3621 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan157 - com-vrf | PASS | - |
| 3622 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan158 - com-vrf | PASS | - |
| 3623 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan159 - com-vrf | PASS | - |
| 3624 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan160 - com-vrf | PASS | - |
| 3625 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan161 - com-vrf | PASS | - |
| 3626 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan162 - com-vrf | PASS | - |
| 3627 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan163 - com-vrf | PASS | - |
| 3628 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan164 - com-vrf | PASS | - |
| 3629 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan165 - com-vrf | PASS | - |
| 3630 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan166 - com-vrf | PASS | - |
| 3631 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan167 - com-vrf | PASS | - |
| 3632 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan168 - com-vrf | PASS | - |
| 3633 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan169 - com-vrf | PASS | - |
| 3634 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan170 - com-vrf | PASS | - |
| 3635 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan171 - com-vrf | PASS | - |
| 3636 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan172 - com-vrf | PASS | - |
| 3637 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan173 - com-vrf | PASS | - |
| 3638 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan174 - com-vrf | PASS | - |
| 3639 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan175 - com-vrf | PASS | - |
| 3640 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan176 - com-vrf | PASS | - |
| 3641 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan177 - com-vrf | PASS | - |
| 3642 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan178 - com-vrf | PASS | - |
| 3643 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan179 - com-vrf | PASS | - |
| 3644 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan180 - com-vrf | PASS | - |
| 3645 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan181 - com-vrf | PASS | - |
| 3646 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan182 - com-vrf | PASS | - |
| 3647 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan183 - com-vrf | PASS | - |
| 3648 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan184 - com-vrf | PASS | - |
| 3649 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan185 - com-vrf | PASS | - |
| 3650 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan186 - com-vrf | PASS | - |
| 3651 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan187 - com-vrf | PASS | - |
| 3652 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan188 - com-vrf | PASS | - |
| 3653 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan189 - com-vrf | PASS | - |
| 3654 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan190 - com-vrf | PASS | - |
| 3655 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan191 - com-vrf | PASS | - |
| 3656 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan192 - com-vrf | PASS | - |
| 3657 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan193 - com-vrf | PASS | - |
| 3658 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan194 - com-vrf | PASS | - |
| 3659 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan195 - com-vrf | PASS | - |
| 3660 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan196 - com-vrf | PASS | - |
| 3661 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan197 - com-vrf | PASS | - |
| 3662 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan198 - com-vrf | PASS | - |
| 3663 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan199 - com-vrf | PASS | - |
| 3664 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan200 - com-vrf | PASS | - |
| 3665 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan201 - com-vrf | PASS | - |
| 3666 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan202 - com-vrf | PASS | - |
| 3667 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan203 - com-vrf | PASS | - |
| 3668 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan204 - com-vrf | PASS | - |
| 3669 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan205 - com-vrf | PASS | - |
| 3670 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan206 - com-vrf | PASS | - |
| 3671 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan207 - com-vrf | PASS | - |
| 3672 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan208 - com-vrf | PASS | - |
| 3673 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan209 - com-vrf | PASS | - |
| 3674 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan210 - com-vrf | PASS | - |
| 3675 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan211 - com-vrf | PASS | - |
| 3676 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan212 - com-vrf | PASS | - |
| 3677 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan213 - com-vrf | PASS | - |
| 3678 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan214 - com-vrf | PASS | - |
| 3679 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan215 - com-vrf | PASS | - |
| 3680 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan216 - com-vrf | PASS | - |
| 3681 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan217 - com-vrf | PASS | - |
| 3682 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan218 - com-vrf | PASS | - |
| 3683 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan219 - com-vrf | PASS | - |
| 3684 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan220 - com-vrf | PASS | - |
| 3685 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan221 - com-vrf | PASS | - |
| 3686 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan222 - com-vrf | PASS | - |
| 3687 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan223 - com-vrf | PASS | - |
| 3688 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan224 - com-vrf | PASS | - |
| 3689 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan225 - com-vrf | PASS | - |
| 3690 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan226 - com-vrf | PASS | - |
| 3691 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan227 - com-vrf | PASS | - |
| 3692 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan228 - com-vrf | PASS | - |
| 3693 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan229 - com-vrf | PASS | - |
| 3694 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan230 - com-vrf | PASS | - |
| 3695 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan231 - com-vrf | PASS | - |
| 3696 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan232 - com-vrf | PASS | - |
| 3697 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan233 - com-vrf | PASS | - |
| 3698 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan234 - com-vrf | PASS | - |
| 3699 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan235 - com-vrf | PASS | - |
| 3700 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan236 - com-vrf | PASS | - |
| 3701 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan237 - com-vrf | PASS | - |
| 3702 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan238 - com-vrf | PASS | - |
| 3703 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan239 - com-vrf | PASS | - |
| 3704 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan240 - com-vrf | PASS | - |
| 3705 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan241 - com-vrf | PASS | - |
| 3706 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan242 - com-vrf | PASS | - |
| 3707 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan243 - com-vrf | PASS | - |
| 3708 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan244 - com-vrf | PASS | - |
| 3709 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan245 - com-vrf | PASS | - |
| 3710 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan246 - com-vrf | PASS | - |
| 3711 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan247 - com-vrf | PASS | - |
| 3712 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan248 - com-vrf | PASS | - |
| 3713 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan249 - com-vrf | PASS | - |
| 3714 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan250 - com-vrf | PASS | - |
| 3715 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan251 - com-vrf | PASS | - |
| 3716 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan252 - com-vrf | PASS | - |
| 3717 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan253 - com-vrf | PASS | - |
| 3718 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan254 - com-vrf | PASS | - |
| 3719 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan255 - com-vrf | PASS | - |
| 3720 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan256 - com-vrf | PASS | - |
| 3721 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan257 - com-vrf | PASS | - |
| 3722 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan258 - com-vrf | PASS | - |
| 3723 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan259 - com-vrf | PASS | - |
| 3724 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan260 - com-vrf | PASS | - |
| 3725 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan261 - com-vrf | PASS | - |
| 3726 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan262 - com-vrf | PASS | - |
| 3727 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan263 - com-vrf | PASS | - |
| 3728 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan264 - com-vrf | PASS | - |
| 3729 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan265 - com-vrf | PASS | - |
| 3730 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan266 - com-vrf | PASS | - |
| 3731 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan267 - com-vrf | PASS | - |
| 3732 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan268 - com-vrf | PASS | - |
| 3733 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan269 - com-vrf | PASS | - |
| 3734 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan270 - com-vrf | PASS | - |
| 3735 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan271 - com-vrf | PASS | - |
| 3736 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan272 - com-vrf | PASS | - |
| 3737 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan273 - com-vrf | PASS | - |
| 3738 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan274 - com-vrf | PASS | - |
| 3739 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan275 - com-vrf | PASS | - |
| 3740 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan276 - com-vrf | PASS | - |
| 3741 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan277 - com-vrf | PASS | - |
| 3742 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan278 - com-vrf | PASS | - |
| 3743 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan279 - com-vrf | PASS | - |
| 3744 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan280 - com-vrf | PASS | - |
| 3745 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan281 - com-vrf | PASS | - |
| 3746 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan282 - com-vrf | PASS | - |
| 3747 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan283 - com-vrf | PASS | - |
| 3748 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan284 - com-vrf | PASS | - |
| 3749 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan285 - com-vrf | PASS | - |
| 3750 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan286 - com-vrf | PASS | - |
| 3751 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan287 - com-vrf | PASS | - |
| 3752 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan288 - com-vrf | PASS | - |
| 3753 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan289 - com-vrf | PASS | - |
| 3754 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan290 - com-vrf | PASS | - |
| 3755 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan291 - com-vrf | PASS | - |
| 3756 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan292 - com-vrf | PASS | - |
| 3757 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan293 - com-vrf | PASS | - |
| 3758 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan294 - com-vrf | PASS | - |
| 3759 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan295 - com-vrf | PASS | - |
| 3760 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan296 - com-vrf | PASS | - |
| 3761 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan297 - com-vrf | PASS | - |
| 3762 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan298 - com-vrf | PASS | - |
| 3763 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan299 - com-vrf | PASS | - |
| 3764 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan300 - com-vrf | PASS | - |
| 3765 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan301 - com-vrf | PASS | - |
| 3766 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan302 - com-vrf | PASS | - |
| 3767 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan303 - com-vrf | PASS | - |
| 3768 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan304 - com-vrf | PASS | - |
| 3769 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan305 - com-vrf | PASS | - |
| 3770 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan306 - com-vrf | PASS | - |
| 3771 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan307 - com-vrf | PASS | - |
| 3772 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan308 - com-vrf | PASS | - |
| 3773 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan309 - com-vrf | PASS | - |
| 3774 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan310 - com-vrf | PASS | - |
| 3775 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan311 - com-vrf | PASS | - |
| 3776 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan312 - com-vrf | PASS | - |
| 3777 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan313 - com-vrf | PASS | - |
| 3778 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan314 - com-vrf | PASS | - |
| 3779 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan315 - com-vrf | PASS | - |
| 3780 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan316 - com-vrf | PASS | - |
| 3781 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan317 - com-vrf | PASS | - |
| 3782 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan318 - com-vrf | PASS | - |
| 3783 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan319 - com-vrf | PASS | - |
| 3784 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan320 - com-vrf | PASS | - |
| 3785 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan321 - com-vrf | PASS | - |
| 3786 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan322 - com-vrf | PASS | - |
| 3787 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan323 - com-vrf | PASS | - |
| 3788 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan324 - com-vrf | PASS | - |
| 3789 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan325 - com-vrf | PASS | - |
| 3790 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan326 - com-vrf | PASS | - |
| 3791 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan327 - com-vrf | PASS | - |
| 3792 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan328 - com-vrf | PASS | - |
| 3793 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan329 - com-vrf | PASS | - |
| 3794 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan330 - com-vrf | PASS | - |
| 3795 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan331 - com-vrf | PASS | - |
| 3796 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan332 - com-vrf | PASS | - |
| 3797 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan333 - com-vrf | PASS | - |
| 3798 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan334 - com-vrf | PASS | - |
| 3799 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan335 - com-vrf | PASS | - |
| 3800 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan336 - com-vrf | PASS | - |
| 3801 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan337 - com-vrf | PASS | - |
| 3802 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan338 - com-vrf | PASS | - |
| 3803 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan339 - com-vrf | PASS | - |
| 3804 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan340 - com-vrf | PASS | - |
| 3805 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan341 - com-vrf | PASS | - |
| 3806 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan342 - com-vrf | PASS | - |
| 3807 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan343 - com-vrf | PASS | - |
| 3808 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan344 - com-vrf | PASS | - |
| 3809 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan345 - com-vrf | PASS | - |
| 3810 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan346 - com-vrf | PASS | - |
| 3811 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan347 - com-vrf | PASS | - |
| 3812 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan348 - com-vrf | PASS | - |
| 3813 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan349 - com-vrf | PASS | - |
| 3814 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan350 - com-vrf | PASS | - |
| 3815 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan351 - com-vrf | PASS | - |
| 3816 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan352 - com-vrf | PASS | - |
| 3817 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan353 - com-vrf | PASS | - |
| 3818 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan354 - com-vrf | PASS | - |
| 3819 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan355 - com-vrf | PASS | - |
| 3820 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan356 - com-vrf | PASS | - |
| 3821 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan357 - com-vrf | PASS | - |
| 3822 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan358 - com-vrf | PASS | - |
| 3823 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan359 - com-vrf | PASS | - |
| 3824 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan360 - com-vrf | PASS | - |
| 3825 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan361 - com-vrf | PASS | - |
| 3826 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan362 - com-vrf | PASS | - |
| 3827 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan363 - com-vrf | PASS | - |
| 3828 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan364 - com-vrf | PASS | - |
| 3829 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan365 - com-vrf | PASS | - |
| 3830 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan366 - com-vrf | PASS | - |
| 3831 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan367 - com-vrf | PASS | - |
| 3832 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan368 - com-vrf | PASS | - |
| 3833 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan369 - com-vrf | PASS | - |
| 3834 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan370 - com-vrf | PASS | - |
| 3835 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan371 - com-vrf | PASS | - |
| 3836 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan372 - com-vrf | PASS | - |
| 3837 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan373 - com-vrf | PASS | - |
| 3838 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan374 - com-vrf | PASS | - |
| 3839 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan375 - com-vrf | PASS | - |
| 3840 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan376 - com-vrf | PASS | - |
| 3841 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan377 - com-vrf | PASS | - |
| 3842 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan378 - com-vrf | PASS | - |
| 3843 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan379 - com-vrf | PASS | - |
| 3844 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan380 - com-vrf | PASS | - |
| 3845 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan381 - com-vrf | PASS | - |
| 3846 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan382 - com-vrf | PASS | - |
| 3847 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan383 - com-vrf | PASS | - |
| 3848 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan384 - com-vrf | PASS | - |
| 3849 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan385 - com-vrf | PASS | - |
| 3850 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan386 - com-vrf | PASS | - |
| 3851 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan387 - com-vrf | PASS | - |
| 3852 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan388 - com-vrf | PASS | - |
| 3853 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan389 - com-vrf | PASS | - |
| 3854 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan390 - com-vrf | PASS | - |
| 3855 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan391 - com-vrf | PASS | - |
| 3856 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan392 - com-vrf | PASS | - |
| 3857 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan393 - com-vrf | PASS | - |
| 3858 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan394 - com-vrf | PASS | - |
| 3859 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan395 - com-vrf | PASS | - |
| 3860 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan396 - com-vrf | PASS | - |
| 3861 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan397 - com-vrf | PASS | - |
| 3862 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan398 - com-vrf | PASS | - |
| 3863 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan399 - com-vrf | PASS | - |
| 3864 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan400 - com-vrf | PASS | - |
| 3865 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan401 - com-vrf | PASS | - |
| 3866 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan402 - com-vrf | PASS | - |
| 3867 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan403 - com-vrf | PASS | - |
| 3868 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan404 - com-vrf | PASS | - |
| 3869 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan405 - com-vrf | PASS | - |
| 3870 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan406 - com-vrf | PASS | - |
| 3871 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan407 - com-vrf | PASS | - |
| 3872 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan408 - com-vrf | PASS | - |
| 3873 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan409 - com-vrf | PASS | - |
| 3874 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan410 - com-vrf | PASS | - |
| 3875 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan411 - com-vrf | PASS | - |
| 3876 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan412 - com-vrf | PASS | - |
| 3877 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan413 - com-vrf | PASS | - |
| 3878 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan414 - com-vrf | PASS | - |
| 3879 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan415 - com-vrf | PASS | - |
| 3880 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan416 - com-vrf | PASS | - |
| 3881 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan417 - com-vrf | PASS | - |
| 3882 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan418 - com-vrf | PASS | - |
| 3883 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan419 - com-vrf | PASS | - |
| 3884 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan420 - com-vrf | PASS | - |
| 3885 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan421 - com-vrf | PASS | - |
| 3886 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan422 - com-vrf | PASS | - |
| 3887 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan423 - com-vrf | PASS | - |
| 3888 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan424 - com-vrf | PASS | - |
| 3889 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan425 - com-vrf | PASS | - |
| 3890 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan426 - com-vrf | PASS | - |
| 3891 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan427 - com-vrf | PASS | - |
| 3892 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan428 - com-vrf | PASS | - |
| 3893 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan429 - com-vrf | PASS | - |
| 3894 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan430 - com-vrf | PASS | - |
| 3895 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan431 - com-vrf | PASS | - |
| 3896 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan432 - com-vrf | PASS | - |
| 3897 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan433 - com-vrf | PASS | - |
| 3898 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan434 - com-vrf | PASS | - |
| 3899 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan435 - com-vrf | PASS | - |
| 3900 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan436 - com-vrf | PASS | - |
| 3901 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan437 - com-vrf | PASS | - |
| 3902 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan438 - com-vrf | PASS | - |
| 3903 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan439 - com-vrf | PASS | - |
| 3904 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan440 - com-vrf | PASS | - |
| 3905 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan441 - com-vrf | PASS | - |
| 3906 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan442 - com-vrf | PASS | - |
| 3907 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan443 - com-vrf | PASS | - |
| 3908 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan444 - com-vrf | PASS | - |
| 3909 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan445 - com-vrf | PASS | - |
| 3910 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan446 - com-vrf | PASS | - |
| 3911 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan447 - com-vrf | PASS | - |
| 3912 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan448 - com-vrf | PASS | - |
| 3913 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan449 - com-vrf | PASS | - |
| 3914 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan450 - com-vrf | PASS | - |
| 3915 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2001 - sec-vrf | PASS | - |
| 3916 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2002 - sec-vrf | PASS | - |
| 3917 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2003 - sec-vrf | PASS | - |
| 3918 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2004 - sec-vrf | PASS | - |
| 3919 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2005 - sec-vrf | PASS | - |
| 3920 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2006 - sec-vrf | PASS | - |
| 3921 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2007 - sec-vrf | PASS | - |
| 3922 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2008 - sec-vrf | PASS | - |
| 3923 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2009 - sec-vrf | PASS | - |
| 3924 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2010 - sec-vrf | PASS | - |
| 3925 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2011 - sec-vrf | PASS | - |
| 3926 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2012 - sec-vrf | PASS | - |
| 3927 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2013 - sec-vrf | PASS | - |
| 3928 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2014 - sec-vrf | PASS | - |
| 3929 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2015 - sec-vrf | PASS | - |
| 3930 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2016 - sec-vrf | PASS | - |
| 3931 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2017 - sec-vrf | PASS | - |
| 3932 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2018 - sec-vrf | PASS | - |
| 3933 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2019 - sec-vrf | PASS | - |
| 3934 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2020 - sec-vrf | PASS | - |
| 3935 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2021 - sec-vrf | PASS | - |
| 3936 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2022 - sec-vrf | PASS | - |
| 3937 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2023 - sec-vrf | PASS | - |
| 3938 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2024 - sec-vrf | PASS | - |
| 3939 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2025 - sec-vrf | PASS | - |
| 3940 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2026 - sec-vrf | PASS | - |
| 3941 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2027 - sec-vrf | PASS | - |
| 3942 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2028 - sec-vrf | PASS | - |
| 3943 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2029 - sec-vrf | PASS | - |
| 3944 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2030 - sec-vrf | PASS | - |
| 3945 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2031 - sec-vrf | PASS | - |
| 3946 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2032 - sec-vrf | PASS | - |
| 3947 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2033 - sec-vrf | PASS | - |
| 3948 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2034 - sec-vrf | PASS | - |
| 3949 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2035 - sec-vrf | PASS | - |
| 3950 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2036 - sec-vrf | PASS | - |
| 3951 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2037 - sec-vrf | PASS | - |
| 3952 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2038 - sec-vrf | PASS | - |
| 3953 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2039 - sec-vrf | PASS | - |
| 3954 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2040 - sec-vrf | PASS | - |
| 3955 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2041 - sec-vrf | PASS | - |
| 3956 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2042 - sec-vrf | PASS | - |
| 3957 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2043 - sec-vrf | PASS | - |
| 3958 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2044 - sec-vrf | PASS | - |
| 3959 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2045 - sec-vrf | PASS | - |
| 3960 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2046 - sec-vrf | PASS | - |
| 3961 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2047 - sec-vrf | PASS | - |
| 3962 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2048 - sec-vrf | PASS | - |
| 3963 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2049 - sec-vrf | PASS | - |
| 3964 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2050 - sec-vrf | PASS | - |
| 3965 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2051 - sec-vrf | PASS | - |
| 3966 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2052 - sec-vrf | PASS | - |
| 3967 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2053 - sec-vrf | PASS | - |
| 3968 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2054 - sec-vrf | PASS | - |
| 3969 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2055 - sec-vrf | PASS | - |
| 3970 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2056 - sec-vrf | PASS | - |
| 3971 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2057 - sec-vrf | PASS | - |
| 3972 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2058 - sec-vrf | PASS | - |
| 3973 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2059 - sec-vrf | PASS | - |
| 3974 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2060 - sec-vrf | PASS | - |
| 3975 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2061 - sec-vrf | PASS | - |
| 3976 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2062 - sec-vrf | PASS | - |
| 3977 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2063 - sec-vrf | PASS | - |
| 3978 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2064 - sec-vrf | PASS | - |
| 3979 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2065 - sec-vrf | PASS | - |
| 3980 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2066 - sec-vrf | PASS | - |
| 3981 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2067 - sec-vrf | PASS | - |
| 3982 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2068 - sec-vrf | PASS | - |
| 3983 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2069 - sec-vrf | PASS | - |
| 3984 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2070 - sec-vrf | PASS | - |
| 3985 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2071 - sec-vrf | PASS | - |
| 3986 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2072 - sec-vrf | PASS | - |
| 3987 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2073 - sec-vrf | PASS | - |
| 3988 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2074 - sec-vrf | PASS | - |
| 3989 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2075 - sec-vrf | PASS | - |
| 3990 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2076 - sec-vrf | PASS | - |
| 3991 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2077 - sec-vrf | PASS | - |
| 3992 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2078 - sec-vrf | PASS | - |
| 3993 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2079 - sec-vrf | PASS | - |
| 3994 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2080 - sec-vrf | PASS | - |
| 3995 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2081 - sec-vrf | PASS | - |
| 3996 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2082 - sec-vrf | PASS | - |
| 3997 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2083 - sec-vrf | PASS | - |
| 3998 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2084 - sec-vrf | PASS | - |
| 3999 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2085 - sec-vrf | PASS | - |
| 4000 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2086 - sec-vrf | PASS | - |
| 4001 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2087 - sec-vrf | PASS | - |
| 4002 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2088 - sec-vrf | PASS | - |
| 4003 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2089 - sec-vrf | PASS | - |
| 4004 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2090 - sec-vrf | PASS | - |
| 4005 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2091 - sec-vrf | PASS | - |
| 4006 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2092 - sec-vrf | PASS | - |
| 4007 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2093 - sec-vrf | PASS | - |
| 4008 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2094 - sec-vrf | PASS | - |
| 4009 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2095 - sec-vrf | PASS | - |
| 4010 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2096 - sec-vrf | PASS | - |
| 4011 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2097 - sec-vrf | PASS | - |
| 4012 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2098 - sec-vrf | PASS | - |
| 4013 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2099 - sec-vrf | PASS | - |
| 4014 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2100 - sec-vrf | PASS | - |
| 4015 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2101 - sec-vrf | PASS | - |
| 4016 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2102 - sec-vrf | PASS | - |
| 4017 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2103 - sec-vrf | PASS | - |
| 4018 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2104 - sec-vrf | PASS | - |
| 4019 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2105 - sec-vrf | PASS | - |
| 4020 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2106 - sec-vrf | PASS | - |
| 4021 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2107 - sec-vrf | PASS | - |
| 4022 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2108 - sec-vrf | PASS | - |
| 4023 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2109 - sec-vrf | PASS | - |
| 4024 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2110 - sec-vrf | PASS | - |
| 4025 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2111 - sec-vrf | PASS | - |
| 4026 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2112 - sec-vrf | PASS | - |
| 4027 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2113 - sec-vrf | PASS | - |
| 4028 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2114 - sec-vrf | PASS | - |
| 4029 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2115 - sec-vrf | PASS | - |
| 4030 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2116 - sec-vrf | PASS | - |
| 4031 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2117 - sec-vrf | PASS | - |
| 4032 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2118 - sec-vrf | PASS | - |
| 4033 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2119 - sec-vrf | PASS | - |
| 4034 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2120 - sec-vrf | PASS | - |
| 4035 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2121 - sec-vrf | PASS | - |
| 4036 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2122 - sec-vrf | PASS | - |
| 4037 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2123 - sec-vrf | PASS | - |
| 4038 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2124 - sec-vrf | PASS | - |
| 4039 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2125 - sec-vrf | PASS | - |
| 4040 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2126 - sec-vrf | PASS | - |
| 4041 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2127 - sec-vrf | PASS | - |
| 4042 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2128 - sec-vrf | PASS | - |
| 4043 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2129 - sec-vrf | PASS | - |
| 4044 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2130 - sec-vrf | PASS | - |
| 4045 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2131 - sec-vrf | PASS | - |
| 4046 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2132 - sec-vrf | PASS | - |
| 4047 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2133 - sec-vrf | PASS | - |
| 4048 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2134 - sec-vrf | PASS | - |
| 4049 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2135 - sec-vrf | PASS | - |
| 4050 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2136 - sec-vrf | PASS | - |
| 4051 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2137 - sec-vrf | PASS | - |
| 4052 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2138 - sec-vrf | PASS | - |
| 4053 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2139 - sec-vrf | PASS | - |
| 4054 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2140 - sec-vrf | PASS | - |
| 4055 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2141 - sec-vrf | PASS | - |
| 4056 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2142 - sec-vrf | PASS | - |
| 4057 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2143 - sec-vrf | PASS | - |
| 4058 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2144 - sec-vrf | PASS | - |
| 4059 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2145 - sec-vrf | PASS | - |
| 4060 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2146 - sec-vrf | PASS | - |
| 4061 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2147 - sec-vrf | PASS | - |
| 4062 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2148 - sec-vrf | PASS | - |
| 4063 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2149 - sec-vrf | PASS | - |
| 4064 | dc1p2_leaf1_mrv453 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2150 - sec-vrf | PASS | - |
| 4065 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan101 - com-vrf | PASS | - |
| 4066 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan102 - com-vrf | PASS | - |
| 4067 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan103 - com-vrf | PASS | - |
| 4068 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan104 - com-vrf | PASS | - |
| 4069 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan105 - com-vrf | PASS | - |
| 4070 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan106 - com-vrf | PASS | - |
| 4071 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan107 - com-vrf | PASS | - |
| 4072 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan108 - com-vrf | PASS | - |
| 4073 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan109 - com-vrf | PASS | - |
| 4074 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - com-vrf | PASS | - |
| 4075 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan111 - com-vrf | PASS | - |
| 4076 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan112 - com-vrf | PASS | - |
| 4077 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan113 - com-vrf | PASS | - |
| 4078 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan114 - com-vrf | PASS | - |
| 4079 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan115 - com-vrf | PASS | - |
| 4080 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan116 - com-vrf | PASS | - |
| 4081 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan117 - com-vrf | PASS | - |
| 4082 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan118 - com-vrf | PASS | - |
| 4083 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan119 - com-vrf | PASS | - |
| 4084 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - com-vrf | PASS | - |
| 4085 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan121 - com-vrf | PASS | - |
| 4086 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan122 - com-vrf | PASS | - |
| 4087 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan123 - com-vrf | PASS | - |
| 4088 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan124 - com-vrf | PASS | - |
| 4089 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan125 - com-vrf | PASS | - |
| 4090 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan126 - com-vrf | PASS | - |
| 4091 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan127 - com-vrf | PASS | - |
| 4092 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan128 - com-vrf | PASS | - |
| 4093 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan129 - com-vrf | PASS | - |
| 4094 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan130 - com-vrf | PASS | - |
| 4095 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan131 - com-vrf | PASS | - |
| 4096 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan132 - com-vrf | PASS | - |
| 4097 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan133 - com-vrf | PASS | - |
| 4098 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan134 - com-vrf | PASS | - |
| 4099 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan135 - com-vrf | PASS | - |
| 4100 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan136 - com-vrf | PASS | - |
| 4101 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan137 - com-vrf | PASS | - |
| 4102 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan138 - com-vrf | PASS | - |
| 4103 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan139 - com-vrf | PASS | - |
| 4104 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan140 - com-vrf | PASS | - |
| 4105 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan141 - com-vrf | PASS | - |
| 4106 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan142 - com-vrf | PASS | - |
| 4107 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan143 - com-vrf | PASS | - |
| 4108 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan144 - com-vrf | PASS | - |
| 4109 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan145 - com-vrf | PASS | - |
| 4110 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan146 - com-vrf | PASS | - |
| 4111 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan147 - com-vrf | PASS | - |
| 4112 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan148 - com-vrf | PASS | - |
| 4113 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan149 - com-vrf | PASS | - |
| 4114 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan150 - com-vrf | PASS | - |
| 4115 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan151 - com-vrf | PASS | - |
| 4116 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan152 - com-vrf | PASS | - |
| 4117 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan153 - com-vrf | PASS | - |
| 4118 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan154 - com-vrf | PASS | - |
| 4119 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan155 - com-vrf | PASS | - |
| 4120 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan156 - com-vrf | PASS | - |
| 4121 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan157 - com-vrf | PASS | - |
| 4122 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan158 - com-vrf | PASS | - |
| 4123 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan159 - com-vrf | PASS | - |
| 4124 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan160 - com-vrf | PASS | - |
| 4125 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan161 - com-vrf | PASS | - |
| 4126 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan162 - com-vrf | PASS | - |
| 4127 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan163 - com-vrf | PASS | - |
| 4128 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan164 - com-vrf | PASS | - |
| 4129 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan165 - com-vrf | PASS | - |
| 4130 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan166 - com-vrf | PASS | - |
| 4131 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan167 - com-vrf | PASS | - |
| 4132 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan168 - com-vrf | PASS | - |
| 4133 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan169 - com-vrf | PASS | - |
| 4134 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan170 - com-vrf | PASS | - |
| 4135 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan171 - com-vrf | PASS | - |
| 4136 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan172 - com-vrf | PASS | - |
| 4137 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan173 - com-vrf | PASS | - |
| 4138 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan174 - com-vrf | PASS | - |
| 4139 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan175 - com-vrf | PASS | - |
| 4140 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan176 - com-vrf | PASS | - |
| 4141 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan177 - com-vrf | PASS | - |
| 4142 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan178 - com-vrf | PASS | - |
| 4143 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan179 - com-vrf | PASS | - |
| 4144 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan180 - com-vrf | PASS | - |
| 4145 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan181 - com-vrf | PASS | - |
| 4146 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan182 - com-vrf | PASS | - |
| 4147 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan183 - com-vrf | PASS | - |
| 4148 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan184 - com-vrf | PASS | - |
| 4149 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan185 - com-vrf | PASS | - |
| 4150 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan186 - com-vrf | PASS | - |
| 4151 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan187 - com-vrf | PASS | - |
| 4152 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan188 - com-vrf | PASS | - |
| 4153 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan189 - com-vrf | PASS | - |
| 4154 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan190 - com-vrf | PASS | - |
| 4155 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan191 - com-vrf | PASS | - |
| 4156 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan192 - com-vrf | PASS | - |
| 4157 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan193 - com-vrf | PASS | - |
| 4158 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan194 - com-vrf | PASS | - |
| 4159 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan195 - com-vrf | PASS | - |
| 4160 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan196 - com-vrf | PASS | - |
| 4161 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan197 - com-vrf | PASS | - |
| 4162 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan198 - com-vrf | PASS | - |
| 4163 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan199 - com-vrf | PASS | - |
| 4164 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan200 - com-vrf | PASS | - |
| 4165 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan201 - com-vrf | PASS | - |
| 4166 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan202 - com-vrf | PASS | - |
| 4167 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan203 - com-vrf | PASS | - |
| 4168 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan204 - com-vrf | PASS | - |
| 4169 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan205 - com-vrf | PASS | - |
| 4170 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan206 - com-vrf | PASS | - |
| 4171 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan207 - com-vrf | PASS | - |
| 4172 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan208 - com-vrf | PASS | - |
| 4173 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan209 - com-vrf | PASS | - |
| 4174 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan210 - com-vrf | PASS | - |
| 4175 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan211 - com-vrf | PASS | - |
| 4176 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan212 - com-vrf | PASS | - |
| 4177 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan213 - com-vrf | PASS | - |
| 4178 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan214 - com-vrf | PASS | - |
| 4179 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan215 - com-vrf | PASS | - |
| 4180 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan216 - com-vrf | PASS | - |
| 4181 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan217 - com-vrf | PASS | - |
| 4182 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan218 - com-vrf | PASS | - |
| 4183 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan219 - com-vrf | PASS | - |
| 4184 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan220 - com-vrf | PASS | - |
| 4185 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan221 - com-vrf | PASS | - |
| 4186 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan222 - com-vrf | PASS | - |
| 4187 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan223 - com-vrf | PASS | - |
| 4188 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan224 - com-vrf | PASS | - |
| 4189 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan225 - com-vrf | PASS | - |
| 4190 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan226 - com-vrf | PASS | - |
| 4191 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan227 - com-vrf | PASS | - |
| 4192 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan228 - com-vrf | PASS | - |
| 4193 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan229 - com-vrf | PASS | - |
| 4194 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan230 - com-vrf | PASS | - |
| 4195 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan231 - com-vrf | PASS | - |
| 4196 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan232 - com-vrf | PASS | - |
| 4197 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan233 - com-vrf | PASS | - |
| 4198 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan234 - com-vrf | PASS | - |
| 4199 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan235 - com-vrf | PASS | - |
| 4200 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan236 - com-vrf | PASS | - |
| 4201 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan237 - com-vrf | PASS | - |
| 4202 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan238 - com-vrf | PASS | - |
| 4203 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan239 - com-vrf | PASS | - |
| 4204 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan240 - com-vrf | PASS | - |
| 4205 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan241 - com-vrf | PASS | - |
| 4206 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan242 - com-vrf | PASS | - |
| 4207 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan243 - com-vrf | PASS | - |
| 4208 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan244 - com-vrf | PASS | - |
| 4209 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan245 - com-vrf | PASS | - |
| 4210 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan246 - com-vrf | PASS | - |
| 4211 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan247 - com-vrf | PASS | - |
| 4212 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan248 - com-vrf | PASS | - |
| 4213 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan249 - com-vrf | PASS | - |
| 4214 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan250 - com-vrf | PASS | - |
| 4215 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan251 - com-vrf | PASS | - |
| 4216 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan252 - com-vrf | PASS | - |
| 4217 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan253 - com-vrf | PASS | - |
| 4218 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan254 - com-vrf | PASS | - |
| 4219 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan255 - com-vrf | PASS | - |
| 4220 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan256 - com-vrf | PASS | - |
| 4221 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan257 - com-vrf | PASS | - |
| 4222 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan258 - com-vrf | PASS | - |
| 4223 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan259 - com-vrf | PASS | - |
| 4224 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan260 - com-vrf | PASS | - |
| 4225 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan261 - com-vrf | PASS | - |
| 4226 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan262 - com-vrf | PASS | - |
| 4227 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan263 - com-vrf | PASS | - |
| 4228 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan264 - com-vrf | PASS | - |
| 4229 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan265 - com-vrf | PASS | - |
| 4230 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan266 - com-vrf | PASS | - |
| 4231 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan267 - com-vrf | PASS | - |
| 4232 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan268 - com-vrf | PASS | - |
| 4233 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan269 - com-vrf | PASS | - |
| 4234 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan270 - com-vrf | PASS | - |
| 4235 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan271 - com-vrf | PASS | - |
| 4236 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan272 - com-vrf | PASS | - |
| 4237 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan273 - com-vrf | PASS | - |
| 4238 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan274 - com-vrf | PASS | - |
| 4239 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan275 - com-vrf | PASS | - |
| 4240 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan276 - com-vrf | PASS | - |
| 4241 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan277 - com-vrf | PASS | - |
| 4242 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan278 - com-vrf | PASS | - |
| 4243 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan279 - com-vrf | PASS | - |
| 4244 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan280 - com-vrf | PASS | - |
| 4245 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan281 - com-vrf | PASS | - |
| 4246 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan282 - com-vrf | PASS | - |
| 4247 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan283 - com-vrf | PASS | - |
| 4248 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan284 - com-vrf | PASS | - |
| 4249 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan285 - com-vrf | PASS | - |
| 4250 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan286 - com-vrf | PASS | - |
| 4251 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan287 - com-vrf | PASS | - |
| 4252 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan288 - com-vrf | PASS | - |
| 4253 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan289 - com-vrf | PASS | - |
| 4254 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan290 - com-vrf | PASS | - |
| 4255 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan291 - com-vrf | PASS | - |
| 4256 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan292 - com-vrf | PASS | - |
| 4257 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan293 - com-vrf | PASS | - |
| 4258 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan294 - com-vrf | PASS | - |
| 4259 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan295 - com-vrf | PASS | - |
| 4260 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan296 - com-vrf | PASS | - |
| 4261 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan297 - com-vrf | PASS | - |
| 4262 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan298 - com-vrf | PASS | - |
| 4263 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan299 - com-vrf | PASS | - |
| 4264 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan300 - com-vrf | PASS | - |
| 4265 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan301 - com-vrf | PASS | - |
| 4266 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan302 - com-vrf | PASS | - |
| 4267 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan303 - com-vrf | PASS | - |
| 4268 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan304 - com-vrf | PASS | - |
| 4269 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan305 - com-vrf | PASS | - |
| 4270 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan306 - com-vrf | PASS | - |
| 4271 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan307 - com-vrf | PASS | - |
| 4272 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan308 - com-vrf | PASS | - |
| 4273 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan309 - com-vrf | PASS | - |
| 4274 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan310 - com-vrf | PASS | - |
| 4275 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan311 - com-vrf | PASS | - |
| 4276 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan312 - com-vrf | PASS | - |
| 4277 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan313 - com-vrf | PASS | - |
| 4278 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan314 - com-vrf | PASS | - |
| 4279 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan315 - com-vrf | PASS | - |
| 4280 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan316 - com-vrf | PASS | - |
| 4281 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan317 - com-vrf | PASS | - |
| 4282 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan318 - com-vrf | PASS | - |
| 4283 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan319 - com-vrf | PASS | - |
| 4284 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan320 - com-vrf | PASS | - |
| 4285 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan321 - com-vrf | PASS | - |
| 4286 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan322 - com-vrf | PASS | - |
| 4287 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan323 - com-vrf | PASS | - |
| 4288 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan324 - com-vrf | PASS | - |
| 4289 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan325 - com-vrf | PASS | - |
| 4290 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan326 - com-vrf | PASS | - |
| 4291 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan327 - com-vrf | PASS | - |
| 4292 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan328 - com-vrf | PASS | - |
| 4293 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan329 - com-vrf | PASS | - |
| 4294 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan330 - com-vrf | PASS | - |
| 4295 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan331 - com-vrf | PASS | - |
| 4296 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan332 - com-vrf | PASS | - |
| 4297 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan333 - com-vrf | PASS | - |
| 4298 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan334 - com-vrf | PASS | - |
| 4299 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan335 - com-vrf | PASS | - |
| 4300 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan336 - com-vrf | PASS | - |
| 4301 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan337 - com-vrf | PASS | - |
| 4302 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan338 - com-vrf | PASS | - |
| 4303 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan339 - com-vrf | PASS | - |
| 4304 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan340 - com-vrf | PASS | - |
| 4305 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan341 - com-vrf | PASS | - |
| 4306 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan342 - com-vrf | PASS | - |
| 4307 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan343 - com-vrf | PASS | - |
| 4308 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan344 - com-vrf | PASS | - |
| 4309 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan345 - com-vrf | PASS | - |
| 4310 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan346 - com-vrf | PASS | - |
| 4311 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan347 - com-vrf | PASS | - |
| 4312 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan348 - com-vrf | PASS | - |
| 4313 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan349 - com-vrf | PASS | - |
| 4314 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan350 - com-vrf | PASS | - |
| 4315 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan351 - com-vrf | PASS | - |
| 4316 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan352 - com-vrf | PASS | - |
| 4317 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan353 - com-vrf | PASS | - |
| 4318 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan354 - com-vrf | PASS | - |
| 4319 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan355 - com-vrf | PASS | - |
| 4320 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan356 - com-vrf | PASS | - |
| 4321 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan357 - com-vrf | PASS | - |
| 4322 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan358 - com-vrf | PASS | - |
| 4323 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan359 - com-vrf | PASS | - |
| 4324 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan360 - com-vrf | PASS | - |
| 4325 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan361 - com-vrf | PASS | - |
| 4326 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan362 - com-vrf | PASS | - |
| 4327 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan363 - com-vrf | PASS | - |
| 4328 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan364 - com-vrf | PASS | - |
| 4329 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan365 - com-vrf | PASS | - |
| 4330 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan366 - com-vrf | PASS | - |
| 4331 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan367 - com-vrf | PASS | - |
| 4332 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan368 - com-vrf | PASS | - |
| 4333 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan369 - com-vrf | PASS | - |
| 4334 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan370 - com-vrf | PASS | - |
| 4335 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan371 - com-vrf | PASS | - |
| 4336 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan372 - com-vrf | PASS | - |
| 4337 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan373 - com-vrf | PASS | - |
| 4338 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan374 - com-vrf | PASS | - |
| 4339 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan375 - com-vrf | PASS | - |
| 4340 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan376 - com-vrf | PASS | - |
| 4341 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan377 - com-vrf | PASS | - |
| 4342 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan378 - com-vrf | PASS | - |
| 4343 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan379 - com-vrf | PASS | - |
| 4344 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan380 - com-vrf | PASS | - |
| 4345 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan381 - com-vrf | PASS | - |
| 4346 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan382 - com-vrf | PASS | - |
| 4347 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan383 - com-vrf | PASS | - |
| 4348 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan384 - com-vrf | PASS | - |
| 4349 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan385 - com-vrf | PASS | - |
| 4350 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan386 - com-vrf | PASS | - |
| 4351 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan387 - com-vrf | PASS | - |
| 4352 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan388 - com-vrf | PASS | - |
| 4353 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan389 - com-vrf | PASS | - |
| 4354 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan390 - com-vrf | PASS | - |
| 4355 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan391 - com-vrf | PASS | - |
| 4356 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan392 - com-vrf | PASS | - |
| 4357 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan393 - com-vrf | PASS | - |
| 4358 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan394 - com-vrf | PASS | - |
| 4359 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan395 - com-vrf | PASS | - |
| 4360 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan396 - com-vrf | PASS | - |
| 4361 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan397 - com-vrf | PASS | - |
| 4362 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan398 - com-vrf | PASS | - |
| 4363 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan399 - com-vrf | PASS | - |
| 4364 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan400 - com-vrf | PASS | - |
| 4365 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan401 - com-vrf | PASS | - |
| 4366 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan402 - com-vrf | PASS | - |
| 4367 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan403 - com-vrf | PASS | - |
| 4368 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan404 - com-vrf | PASS | - |
| 4369 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan405 - com-vrf | PASS | - |
| 4370 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan406 - com-vrf | PASS | - |
| 4371 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan407 - com-vrf | PASS | - |
| 4372 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan408 - com-vrf | PASS | - |
| 4373 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan409 - com-vrf | PASS | - |
| 4374 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan410 - com-vrf | PASS | - |
| 4375 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan411 - com-vrf | PASS | - |
| 4376 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan412 - com-vrf | PASS | - |
| 4377 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan413 - com-vrf | PASS | - |
| 4378 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan414 - com-vrf | PASS | - |
| 4379 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan415 - com-vrf | PASS | - |
| 4380 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan416 - com-vrf | PASS | - |
| 4381 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan417 - com-vrf | PASS | - |
| 4382 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan418 - com-vrf | PASS | - |
| 4383 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan419 - com-vrf | PASS | - |
| 4384 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan420 - com-vrf | PASS | - |
| 4385 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan421 - com-vrf | PASS | - |
| 4386 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan422 - com-vrf | PASS | - |
| 4387 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan423 - com-vrf | PASS | - |
| 4388 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan424 - com-vrf | PASS | - |
| 4389 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan425 - com-vrf | PASS | - |
| 4390 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan426 - com-vrf | PASS | - |
| 4391 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan427 - com-vrf | PASS | - |
| 4392 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan428 - com-vrf | PASS | - |
| 4393 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan429 - com-vrf | PASS | - |
| 4394 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan430 - com-vrf | PASS | - |
| 4395 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan431 - com-vrf | PASS | - |
| 4396 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan432 - com-vrf | PASS | - |
| 4397 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan433 - com-vrf | PASS | - |
| 4398 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan434 - com-vrf | PASS | - |
| 4399 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan435 - com-vrf | PASS | - |
| 4400 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan436 - com-vrf | PASS | - |
| 4401 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan437 - com-vrf | PASS | - |
| 4402 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan438 - com-vrf | PASS | - |
| 4403 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan439 - com-vrf | PASS | - |
| 4404 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan440 - com-vrf | PASS | - |
| 4405 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan441 - com-vrf | PASS | - |
| 4406 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan442 - com-vrf | PASS | - |
| 4407 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan443 - com-vrf | PASS | - |
| 4408 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan444 - com-vrf | PASS | - |
| 4409 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan445 - com-vrf | PASS | - |
| 4410 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan446 - com-vrf | PASS | - |
| 4411 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan447 - com-vrf | PASS | - |
| 4412 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan448 - com-vrf | PASS | - |
| 4413 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan449 - com-vrf | PASS | - |
| 4414 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan450 - com-vrf | PASS | - |
| 4415 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2001 - sec-vrf | PASS | - |
| 4416 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2002 - sec-vrf | PASS | - |
| 4417 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2003 - sec-vrf | PASS | - |
| 4418 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2004 - sec-vrf | PASS | - |
| 4419 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2005 - sec-vrf | PASS | - |
| 4420 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2006 - sec-vrf | PASS | - |
| 4421 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2007 - sec-vrf | PASS | - |
| 4422 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2008 - sec-vrf | PASS | - |
| 4423 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2009 - sec-vrf | PASS | - |
| 4424 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2010 - sec-vrf | PASS | - |
| 4425 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2011 - sec-vrf | PASS | - |
| 4426 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2012 - sec-vrf | PASS | - |
| 4427 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2013 - sec-vrf | PASS | - |
| 4428 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2014 - sec-vrf | PASS | - |
| 4429 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2015 - sec-vrf | PASS | - |
| 4430 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2016 - sec-vrf | PASS | - |
| 4431 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2017 - sec-vrf | PASS | - |
| 4432 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2018 - sec-vrf | PASS | - |
| 4433 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2019 - sec-vrf | PASS | - |
| 4434 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2020 - sec-vrf | PASS | - |
| 4435 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2021 - sec-vrf | PASS | - |
| 4436 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2022 - sec-vrf | PASS | - |
| 4437 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2023 - sec-vrf | PASS | - |
| 4438 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2024 - sec-vrf | PASS | - |
| 4439 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2025 - sec-vrf | PASS | - |
| 4440 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2026 - sec-vrf | PASS | - |
| 4441 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2027 - sec-vrf | PASS | - |
| 4442 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2028 - sec-vrf | PASS | - |
| 4443 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2029 - sec-vrf | PASS | - |
| 4444 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2030 - sec-vrf | PASS | - |
| 4445 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2031 - sec-vrf | PASS | - |
| 4446 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2032 - sec-vrf | PASS | - |
| 4447 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2033 - sec-vrf | PASS | - |
| 4448 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2034 - sec-vrf | PASS | - |
| 4449 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2035 - sec-vrf | PASS | - |
| 4450 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2036 - sec-vrf | PASS | - |
| 4451 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2037 - sec-vrf | PASS | - |
| 4452 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2038 - sec-vrf | PASS | - |
| 4453 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2039 - sec-vrf | PASS | - |
| 4454 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2040 - sec-vrf | PASS | - |
| 4455 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2041 - sec-vrf | PASS | - |
| 4456 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2042 - sec-vrf | PASS | - |
| 4457 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2043 - sec-vrf | PASS | - |
| 4458 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2044 - sec-vrf | PASS | - |
| 4459 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2045 - sec-vrf | PASS | - |
| 4460 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2046 - sec-vrf | PASS | - |
| 4461 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2047 - sec-vrf | PASS | - |
| 4462 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2048 - sec-vrf | PASS | - |
| 4463 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2049 - sec-vrf | PASS | - |
| 4464 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2050 - sec-vrf | PASS | - |
| 4465 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2051 - sec-vrf | PASS | - |
| 4466 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2052 - sec-vrf | PASS | - |
| 4467 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2053 - sec-vrf | PASS | - |
| 4468 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2054 - sec-vrf | PASS | - |
| 4469 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2055 - sec-vrf | PASS | - |
| 4470 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2056 - sec-vrf | PASS | - |
| 4471 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2057 - sec-vrf | PASS | - |
| 4472 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2058 - sec-vrf | PASS | - |
| 4473 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2059 - sec-vrf | PASS | - |
| 4474 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2060 - sec-vrf | PASS | - |
| 4475 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2061 - sec-vrf | PASS | - |
| 4476 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2062 - sec-vrf | PASS | - |
| 4477 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2063 - sec-vrf | PASS | - |
| 4478 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2064 - sec-vrf | PASS | - |
| 4479 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2065 - sec-vrf | PASS | - |
| 4480 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2066 - sec-vrf | PASS | - |
| 4481 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2067 - sec-vrf | PASS | - |
| 4482 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2068 - sec-vrf | PASS | - |
| 4483 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2069 - sec-vrf | PASS | - |
| 4484 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2070 - sec-vrf | PASS | - |
| 4485 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2071 - sec-vrf | PASS | - |
| 4486 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2072 - sec-vrf | PASS | - |
| 4487 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2073 - sec-vrf | PASS | - |
| 4488 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2074 - sec-vrf | PASS | - |
| 4489 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2075 - sec-vrf | PASS | - |
| 4490 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2076 - sec-vrf | PASS | - |
| 4491 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2077 - sec-vrf | PASS | - |
| 4492 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2078 - sec-vrf | PASS | - |
| 4493 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2079 - sec-vrf | PASS | - |
| 4494 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2080 - sec-vrf | PASS | - |
| 4495 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2081 - sec-vrf | PASS | - |
| 4496 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2082 - sec-vrf | PASS | - |
| 4497 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2083 - sec-vrf | PASS | - |
| 4498 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2084 - sec-vrf | PASS | - |
| 4499 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2085 - sec-vrf | PASS | - |
| 4500 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2086 - sec-vrf | PASS | - |
| 4501 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2087 - sec-vrf | PASS | - |
| 4502 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2088 - sec-vrf | PASS | - |
| 4503 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2089 - sec-vrf | PASS | - |
| 4504 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2090 - sec-vrf | PASS | - |
| 4505 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2091 - sec-vrf | PASS | - |
| 4506 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2092 - sec-vrf | PASS | - |
| 4507 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2093 - sec-vrf | PASS | - |
| 4508 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2094 - sec-vrf | PASS | - |
| 4509 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2095 - sec-vrf | PASS | - |
| 4510 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2096 - sec-vrf | PASS | - |
| 4511 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2097 - sec-vrf | PASS | - |
| 4512 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2098 - sec-vrf | PASS | - |
| 4513 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2099 - sec-vrf | PASS | - |
| 4514 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2100 - sec-vrf | PASS | - |
| 4515 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2101 - sec-vrf | PASS | - |
| 4516 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2102 - sec-vrf | PASS | - |
| 4517 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2103 - sec-vrf | PASS | - |
| 4518 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2104 - sec-vrf | PASS | - |
| 4519 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2105 - sec-vrf | PASS | - |
| 4520 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2106 - sec-vrf | PASS | - |
| 4521 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2107 - sec-vrf | PASS | - |
| 4522 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2108 - sec-vrf | PASS | - |
| 4523 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2109 - sec-vrf | PASS | - |
| 4524 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2110 - sec-vrf | PASS | - |
| 4525 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2111 - sec-vrf | PASS | - |
| 4526 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2112 - sec-vrf | PASS | - |
| 4527 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2113 - sec-vrf | PASS | - |
| 4528 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2114 - sec-vrf | PASS | - |
| 4529 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2115 - sec-vrf | PASS | - |
| 4530 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2116 - sec-vrf | PASS | - |
| 4531 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2117 - sec-vrf | PASS | - |
| 4532 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2118 - sec-vrf | PASS | - |
| 4533 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2119 - sec-vrf | PASS | - |
| 4534 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2120 - sec-vrf | PASS | - |
| 4535 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2121 - sec-vrf | PASS | - |
| 4536 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2122 - sec-vrf | PASS | - |
| 4537 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2123 - sec-vrf | PASS | - |
| 4538 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2124 - sec-vrf | PASS | - |
| 4539 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2125 - sec-vrf | PASS | - |
| 4540 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2126 - sec-vrf | PASS | - |
| 4541 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2127 - sec-vrf | PASS | - |
| 4542 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2128 - sec-vrf | PASS | - |
| 4543 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2129 - sec-vrf | PASS | - |
| 4544 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2130 - sec-vrf | PASS | - |
| 4545 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2131 - sec-vrf | PASS | - |
| 4546 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2132 - sec-vrf | PASS | - |
| 4547 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2133 - sec-vrf | PASS | - |
| 4548 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2134 - sec-vrf | PASS | - |
| 4549 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2135 - sec-vrf | PASS | - |
| 4550 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2136 - sec-vrf | PASS | - |
| 4551 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2137 - sec-vrf | PASS | - |
| 4552 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2138 - sec-vrf | PASS | - |
| 4553 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2139 - sec-vrf | PASS | - |
| 4554 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2140 - sec-vrf | PASS | - |
| 4555 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2141 - sec-vrf | PASS | - |
| 4556 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2142 - sec-vrf | PASS | - |
| 4557 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2143 - sec-vrf | PASS | - |
| 4558 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2144 - sec-vrf | PASS | - |
| 4559 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2145 - sec-vrf | PASS | - |
| 4560 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2146 - sec-vrf | PASS | - |
| 4561 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2147 - sec-vrf | PASS | - |
| 4562 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2148 - sec-vrf | PASS | - |
| 4563 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2149 - sec-vrf | PASS | - |
| 4564 | dc1p2_leaf2_gt272 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2150 - sec-vrf | PASS | - |
| 4565 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 4566 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 4567 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan101 - com-vrf | PASS | - |
| 4568 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan102 - com-vrf | PASS | - |
| 4569 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan103 - com-vrf | PASS | - |
| 4570 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan104 - com-vrf | PASS | - |
| 4571 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan105 - com-vrf | PASS | - |
| 4572 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan106 - com-vrf | PASS | - |
| 4573 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan107 - com-vrf | PASS | - |
| 4574 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan108 - com-vrf | PASS | - |
| 4575 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan109 - com-vrf | PASS | - |
| 4576 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - com-vrf | PASS | - |
| 4577 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan111 - com-vrf | PASS | - |
| 4578 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan112 - com-vrf | PASS | - |
| 4579 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan113 - com-vrf | PASS | - |
| 4580 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan114 - com-vrf | PASS | - |
| 4581 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan115 - com-vrf | PASS | - |
| 4582 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan116 - com-vrf | PASS | - |
| 4583 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan117 - com-vrf | PASS | - |
| 4584 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan118 - com-vrf | PASS | - |
| 4585 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan119 - com-vrf | PASS | - |
| 4586 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - com-vrf | PASS | - |
| 4587 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan121 - com-vrf | PASS | - |
| 4588 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan122 - com-vrf | PASS | - |
| 4589 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan123 - com-vrf | PASS | - |
| 4590 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan124 - com-vrf | PASS | - |
| 4591 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan125 - com-vrf | PASS | - |
| 4592 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan126 - com-vrf | PASS | - |
| 4593 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan127 - com-vrf | PASS | - |
| 4594 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan128 - com-vrf | PASS | - |
| 4595 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan129 - com-vrf | PASS | - |
| 4596 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan130 - com-vrf | PASS | - |
| 4597 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan131 - com-vrf | PASS | - |
| 4598 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan132 - com-vrf | PASS | - |
| 4599 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan133 - com-vrf | PASS | - |
| 4600 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan134 - com-vrf | PASS | - |
| 4601 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan135 - com-vrf | PASS | - |
| 4602 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan136 - com-vrf | PASS | - |
| 4603 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan137 - com-vrf | PASS | - |
| 4604 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan138 - com-vrf | PASS | - |
| 4605 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan139 - com-vrf | PASS | - |
| 4606 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan140 - com-vrf | PASS | - |
| 4607 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan141 - com-vrf | PASS | - |
| 4608 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan142 - com-vrf | PASS | - |
| 4609 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan143 - com-vrf | PASS | - |
| 4610 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan144 - com-vrf | PASS | - |
| 4611 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan145 - com-vrf | PASS | - |
| 4612 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan146 - com-vrf | PASS | - |
| 4613 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan147 - com-vrf | PASS | - |
| 4614 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan148 - com-vrf | PASS | - |
| 4615 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan149 - com-vrf | PASS | - |
| 4616 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan150 - com-vrf | PASS | - |
| 4617 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan151 - com-vrf | PASS | - |
| 4618 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan152 - com-vrf | PASS | - |
| 4619 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan153 - com-vrf | PASS | - |
| 4620 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan154 - com-vrf | PASS | - |
| 4621 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan155 - com-vrf | PASS | - |
| 4622 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan156 - com-vrf | PASS | - |
| 4623 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan157 - com-vrf | PASS | - |
| 4624 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan158 - com-vrf | PASS | - |
| 4625 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan159 - com-vrf | PASS | - |
| 4626 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan160 - com-vrf | PASS | - |
| 4627 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan161 - com-vrf | PASS | - |
| 4628 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan162 - com-vrf | PASS | - |
| 4629 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan163 - com-vrf | PASS | - |
| 4630 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan164 - com-vrf | PASS | - |
| 4631 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan165 - com-vrf | PASS | - |
| 4632 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan166 - com-vrf | PASS | - |
| 4633 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan167 - com-vrf | PASS | - |
| 4634 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan168 - com-vrf | PASS | - |
| 4635 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan169 - com-vrf | PASS | - |
| 4636 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan170 - com-vrf | PASS | - |
| 4637 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan171 - com-vrf | PASS | - |
| 4638 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan172 - com-vrf | PASS | - |
| 4639 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan173 - com-vrf | PASS | - |
| 4640 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan174 - com-vrf | PASS | - |
| 4641 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan175 - com-vrf | PASS | - |
| 4642 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan176 - com-vrf | PASS | - |
| 4643 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan177 - com-vrf | PASS | - |
| 4644 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan178 - com-vrf | PASS | - |
| 4645 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan179 - com-vrf | PASS | - |
| 4646 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan180 - com-vrf | PASS | - |
| 4647 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan181 - com-vrf | PASS | - |
| 4648 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan182 - com-vrf | PASS | - |
| 4649 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan183 - com-vrf | PASS | - |
| 4650 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan184 - com-vrf | PASS | - |
| 4651 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan185 - com-vrf | PASS | - |
| 4652 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan186 - com-vrf | PASS | - |
| 4653 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan187 - com-vrf | PASS | - |
| 4654 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan188 - com-vrf | PASS | - |
| 4655 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan189 - com-vrf | PASS | - |
| 4656 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan190 - com-vrf | PASS | - |
| 4657 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan191 - com-vrf | PASS | - |
| 4658 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan192 - com-vrf | PASS | - |
| 4659 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan193 - com-vrf | PASS | - |
| 4660 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan194 - com-vrf | PASS | - |
| 4661 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan195 - com-vrf | PASS | - |
| 4662 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan196 - com-vrf | PASS | - |
| 4663 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan197 - com-vrf | PASS | - |
| 4664 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan198 - com-vrf | PASS | - |
| 4665 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan199 - com-vrf | PASS | - |
| 4666 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan200 - com-vrf | PASS | - |
| 4667 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan201 - com-vrf | PASS | - |
| 4668 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan202 - com-vrf | PASS | - |
| 4669 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan203 - com-vrf | PASS | - |
| 4670 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan204 - com-vrf | PASS | - |
| 4671 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan205 - com-vrf | PASS | - |
| 4672 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan206 - com-vrf | PASS | - |
| 4673 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan207 - com-vrf | PASS | - |
| 4674 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan208 - com-vrf | PASS | - |
| 4675 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan209 - com-vrf | PASS | - |
| 4676 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan210 - com-vrf | PASS | - |
| 4677 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan211 - com-vrf | PASS | - |
| 4678 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan212 - com-vrf | PASS | - |
| 4679 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan213 - com-vrf | PASS | - |
| 4680 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan214 - com-vrf | PASS | - |
| 4681 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan215 - com-vrf | PASS | - |
| 4682 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan216 - com-vrf | PASS | - |
| 4683 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan217 - com-vrf | PASS | - |
| 4684 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan218 - com-vrf | PASS | - |
| 4685 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan219 - com-vrf | PASS | - |
| 4686 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan220 - com-vrf | PASS | - |
| 4687 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan221 - com-vrf | PASS | - |
| 4688 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan222 - com-vrf | PASS | - |
| 4689 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan223 - com-vrf | PASS | - |
| 4690 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan224 - com-vrf | PASS | - |
| 4691 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan225 - com-vrf | PASS | - |
| 4692 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan226 - com-vrf | PASS | - |
| 4693 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan227 - com-vrf | PASS | - |
| 4694 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan228 - com-vrf | PASS | - |
| 4695 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan229 - com-vrf | PASS | - |
| 4696 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan230 - com-vrf | PASS | - |
| 4697 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan231 - com-vrf | PASS | - |
| 4698 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan232 - com-vrf | PASS | - |
| 4699 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan233 - com-vrf | PASS | - |
| 4700 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan234 - com-vrf | PASS | - |
| 4701 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan235 - com-vrf | PASS | - |
| 4702 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan236 - com-vrf | PASS | - |
| 4703 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan237 - com-vrf | PASS | - |
| 4704 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan238 - com-vrf | PASS | - |
| 4705 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan239 - com-vrf | PASS | - |
| 4706 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan240 - com-vrf | PASS | - |
| 4707 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan241 - com-vrf | PASS | - |
| 4708 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan242 - com-vrf | PASS | - |
| 4709 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan243 - com-vrf | PASS | - |
| 4710 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan244 - com-vrf | PASS | - |
| 4711 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan245 - com-vrf | PASS | - |
| 4712 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan246 - com-vrf | PASS | - |
| 4713 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan247 - com-vrf | PASS | - |
| 4714 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan248 - com-vrf | PASS | - |
| 4715 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan249 - com-vrf | PASS | - |
| 4716 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan250 - com-vrf | PASS | - |
| 4717 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan251 - com-vrf | PASS | - |
| 4718 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan252 - com-vrf | PASS | - |
| 4719 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan253 - com-vrf | PASS | - |
| 4720 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan254 - com-vrf | PASS | - |
| 4721 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan255 - com-vrf | PASS | - |
| 4722 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan256 - com-vrf | PASS | - |
| 4723 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan257 - com-vrf | PASS | - |
| 4724 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan258 - com-vrf | PASS | - |
| 4725 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan259 - com-vrf | PASS | - |
| 4726 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan260 - com-vrf | PASS | - |
| 4727 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan261 - com-vrf | PASS | - |
| 4728 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan262 - com-vrf | PASS | - |
| 4729 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan263 - com-vrf | PASS | - |
| 4730 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan264 - com-vrf | PASS | - |
| 4731 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan265 - com-vrf | PASS | - |
| 4732 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan266 - com-vrf | PASS | - |
| 4733 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan267 - com-vrf | PASS | - |
| 4734 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan268 - com-vrf | PASS | - |
| 4735 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan269 - com-vrf | PASS | - |
| 4736 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan270 - com-vrf | PASS | - |
| 4737 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan271 - com-vrf | PASS | - |
| 4738 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan272 - com-vrf | PASS | - |
| 4739 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan273 - com-vrf | PASS | - |
| 4740 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan274 - com-vrf | PASS | - |
| 4741 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan275 - com-vrf | PASS | - |
| 4742 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan276 - com-vrf | PASS | - |
| 4743 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan277 - com-vrf | PASS | - |
| 4744 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan278 - com-vrf | PASS | - |
| 4745 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan279 - com-vrf | PASS | - |
| 4746 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan280 - com-vrf | PASS | - |
| 4747 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan281 - com-vrf | PASS | - |
| 4748 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan282 - com-vrf | PASS | - |
| 4749 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan283 - com-vrf | PASS | - |
| 4750 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan284 - com-vrf | PASS | - |
| 4751 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan285 - com-vrf | PASS | - |
| 4752 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan286 - com-vrf | PASS | - |
| 4753 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan287 - com-vrf | PASS | - |
| 4754 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan288 - com-vrf | PASS | - |
| 4755 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan289 - com-vrf | PASS | - |
| 4756 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan290 - com-vrf | PASS | - |
| 4757 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan291 - com-vrf | PASS | - |
| 4758 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan292 - com-vrf | PASS | - |
| 4759 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan293 - com-vrf | PASS | - |
| 4760 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan294 - com-vrf | PASS | - |
| 4761 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan295 - com-vrf | PASS | - |
| 4762 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan296 - com-vrf | PASS | - |
| 4763 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan297 - com-vrf | PASS | - |
| 4764 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan298 - com-vrf | PASS | - |
| 4765 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan299 - com-vrf | PASS | - |
| 4766 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan300 - com-vrf | PASS | - |
| 4767 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan301 - com-vrf | PASS | - |
| 4768 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan302 - com-vrf | PASS | - |
| 4769 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan303 - com-vrf | PASS | - |
| 4770 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan304 - com-vrf | PASS | - |
| 4771 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan305 - com-vrf | PASS | - |
| 4772 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan306 - com-vrf | PASS | - |
| 4773 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan307 - com-vrf | PASS | - |
| 4774 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan308 - com-vrf | PASS | - |
| 4775 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan309 - com-vrf | PASS | - |
| 4776 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan310 - com-vrf | PASS | - |
| 4777 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan311 - com-vrf | PASS | - |
| 4778 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan312 - com-vrf | PASS | - |
| 4779 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan313 - com-vrf | PASS | - |
| 4780 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan314 - com-vrf | PASS | - |
| 4781 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan315 - com-vrf | PASS | - |
| 4782 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan316 - com-vrf | PASS | - |
| 4783 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan317 - com-vrf | PASS | - |
| 4784 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan318 - com-vrf | PASS | - |
| 4785 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan319 - com-vrf | PASS | - |
| 4786 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan320 - com-vrf | PASS | - |
| 4787 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan321 - com-vrf | PASS | - |
| 4788 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan322 - com-vrf | PASS | - |
| 4789 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan323 - com-vrf | PASS | - |
| 4790 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan324 - com-vrf | PASS | - |
| 4791 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan325 - com-vrf | PASS | - |
| 4792 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan326 - com-vrf | PASS | - |
| 4793 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan327 - com-vrf | PASS | - |
| 4794 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan328 - com-vrf | PASS | - |
| 4795 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan329 - com-vrf | PASS | - |
| 4796 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan330 - com-vrf | PASS | - |
| 4797 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan331 - com-vrf | PASS | - |
| 4798 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan332 - com-vrf | PASS | - |
| 4799 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan333 - com-vrf | PASS | - |
| 4800 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan334 - com-vrf | PASS | - |
| 4801 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan335 - com-vrf | PASS | - |
| 4802 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan336 - com-vrf | PASS | - |
| 4803 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan337 - com-vrf | PASS | - |
| 4804 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan338 - com-vrf | PASS | - |
| 4805 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan339 - com-vrf | PASS | - |
| 4806 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan340 - com-vrf | PASS | - |
| 4807 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan341 - com-vrf | PASS | - |
| 4808 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan342 - com-vrf | PASS | - |
| 4809 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan343 - com-vrf | PASS | - |
| 4810 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan344 - com-vrf | PASS | - |
| 4811 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan345 - com-vrf | PASS | - |
| 4812 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan346 - com-vrf | PASS | - |
| 4813 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan347 - com-vrf | PASS | - |
| 4814 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan348 - com-vrf | PASS | - |
| 4815 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan349 - com-vrf | PASS | - |
| 4816 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan350 - com-vrf | PASS | - |
| 4817 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan351 - com-vrf | PASS | - |
| 4818 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan352 - com-vrf | PASS | - |
| 4819 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan353 - com-vrf | PASS | - |
| 4820 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan354 - com-vrf | PASS | - |
| 4821 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan355 - com-vrf | PASS | - |
| 4822 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan356 - com-vrf | PASS | - |
| 4823 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan357 - com-vrf | PASS | - |
| 4824 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan358 - com-vrf | PASS | - |
| 4825 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan359 - com-vrf | PASS | - |
| 4826 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan360 - com-vrf | PASS | - |
| 4827 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan361 - com-vrf | PASS | - |
| 4828 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan362 - com-vrf | PASS | - |
| 4829 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan363 - com-vrf | PASS | - |
| 4830 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan364 - com-vrf | PASS | - |
| 4831 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan365 - com-vrf | PASS | - |
| 4832 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan366 - com-vrf | PASS | - |
| 4833 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan367 - com-vrf | PASS | - |
| 4834 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan368 - com-vrf | PASS | - |
| 4835 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan369 - com-vrf | PASS | - |
| 4836 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan370 - com-vrf | PASS | - |
| 4837 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan371 - com-vrf | PASS | - |
| 4838 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan372 - com-vrf | PASS | - |
| 4839 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan373 - com-vrf | PASS | - |
| 4840 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan374 - com-vrf | PASS | - |
| 4841 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan375 - com-vrf | PASS | - |
| 4842 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan376 - com-vrf | PASS | - |
| 4843 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan377 - com-vrf | PASS | - |
| 4844 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan378 - com-vrf | PASS | - |
| 4845 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan379 - com-vrf | PASS | - |
| 4846 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan380 - com-vrf | PASS | - |
| 4847 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan381 - com-vrf | PASS | - |
| 4848 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan382 - com-vrf | PASS | - |
| 4849 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan383 - com-vrf | PASS | - |
| 4850 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan384 - com-vrf | PASS | - |
| 4851 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan385 - com-vrf | PASS | - |
| 4852 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan386 - com-vrf | PASS | - |
| 4853 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan387 - com-vrf | PASS | - |
| 4854 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan388 - com-vrf | PASS | - |
| 4855 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan389 - com-vrf | PASS | - |
| 4856 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan390 - com-vrf | PASS | - |
| 4857 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan391 - com-vrf | PASS | - |
| 4858 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan392 - com-vrf | PASS | - |
| 4859 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan393 - com-vrf | PASS | - |
| 4860 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan394 - com-vrf | PASS | - |
| 4861 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan395 - com-vrf | PASS | - |
| 4862 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan396 - com-vrf | PASS | - |
| 4863 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan397 - com-vrf | PASS | - |
| 4864 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan398 - com-vrf | PASS | - |
| 4865 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan399 - com-vrf | PASS | - |
| 4866 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan400 - com-vrf | PASS | - |
| 4867 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan401 - com-vrf | PASS | - |
| 4868 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan402 - com-vrf | PASS | - |
| 4869 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan403 - com-vrf | PASS | - |
| 4870 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan404 - com-vrf | PASS | - |
| 4871 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan405 - com-vrf | PASS | - |
| 4872 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan406 - com-vrf | PASS | - |
| 4873 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan407 - com-vrf | PASS | - |
| 4874 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan408 - com-vrf | PASS | - |
| 4875 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan409 - com-vrf | PASS | - |
| 4876 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan410 - com-vrf | PASS | - |
| 4877 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan411 - com-vrf | PASS | - |
| 4878 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan412 - com-vrf | PASS | - |
| 4879 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan413 - com-vrf | PASS | - |
| 4880 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan414 - com-vrf | PASS | - |
| 4881 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan415 - com-vrf | PASS | - |
| 4882 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan416 - com-vrf | PASS | - |
| 4883 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan417 - com-vrf | PASS | - |
| 4884 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan418 - com-vrf | PASS | - |
| 4885 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan419 - com-vrf | PASS | - |
| 4886 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan420 - com-vrf | PASS | - |
| 4887 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan421 - com-vrf | PASS | - |
| 4888 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan422 - com-vrf | PASS | - |
| 4889 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan423 - com-vrf | PASS | - |
| 4890 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan424 - com-vrf | PASS | - |
| 4891 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan425 - com-vrf | PASS | - |
| 4892 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan426 - com-vrf | PASS | - |
| 4893 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan427 - com-vrf | PASS | - |
| 4894 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan428 - com-vrf | PASS | - |
| 4895 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan429 - com-vrf | PASS | - |
| 4896 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan430 - com-vrf | PASS | - |
| 4897 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan431 - com-vrf | PASS | - |
| 4898 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan432 - com-vrf | PASS | - |
| 4899 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan433 - com-vrf | PASS | - |
| 4900 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan434 - com-vrf | PASS | - |
| 4901 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan435 - com-vrf | PASS | - |
| 4902 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan436 - com-vrf | PASS | - |
| 4903 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan437 - com-vrf | PASS | - |
| 4904 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan438 - com-vrf | PASS | - |
| 4905 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan439 - com-vrf | PASS | - |
| 4906 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan440 - com-vrf | PASS | - |
| 4907 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan441 - com-vrf | PASS | - |
| 4908 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan442 - com-vrf | PASS | - |
| 4909 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan443 - com-vrf | PASS | - |
| 4910 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan444 - com-vrf | PASS | - |
| 4911 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan445 - com-vrf | PASS | - |
| 4912 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan446 - com-vrf | PASS | - |
| 4913 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan447 - com-vrf | PASS | - |
| 4914 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan448 - com-vrf | PASS | - |
| 4915 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan449 - com-vrf | PASS | - |
| 4916 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan450 - com-vrf | PASS | - |
| 4917 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4050 - MLAG_PEER_L3_iBGP: vrf com | PASS | - |
| 4918 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2001 - sec-vrf | PASS | - |
| 4919 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2002 - sec-vrf | PASS | - |
| 4920 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2003 - sec-vrf | PASS | - |
| 4921 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2004 - sec-vrf | PASS | - |
| 4922 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2005 - sec-vrf | PASS | - |
| 4923 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2006 - sec-vrf | PASS | - |
| 4924 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2007 - sec-vrf | PASS | - |
| 4925 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2008 - sec-vrf | PASS | - |
| 4926 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2009 - sec-vrf | PASS | - |
| 4927 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2010 - sec-vrf | PASS | - |
| 4928 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2011 - sec-vrf | PASS | - |
| 4929 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2012 - sec-vrf | PASS | - |
| 4930 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2013 - sec-vrf | PASS | - |
| 4931 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2014 - sec-vrf | PASS | - |
| 4932 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2015 - sec-vrf | PASS | - |
| 4933 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2016 - sec-vrf | PASS | - |
| 4934 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2017 - sec-vrf | PASS | - |
| 4935 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2018 - sec-vrf | PASS | - |
| 4936 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2019 - sec-vrf | PASS | - |
| 4937 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2020 - sec-vrf | PASS | - |
| 4938 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2021 - sec-vrf | PASS | - |
| 4939 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2022 - sec-vrf | PASS | - |
| 4940 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2023 - sec-vrf | PASS | - |
| 4941 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2024 - sec-vrf | PASS | - |
| 4942 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2025 - sec-vrf | PASS | - |
| 4943 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2026 - sec-vrf | PASS | - |
| 4944 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2027 - sec-vrf | PASS | - |
| 4945 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2028 - sec-vrf | PASS | - |
| 4946 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2029 - sec-vrf | PASS | - |
| 4947 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2030 - sec-vrf | PASS | - |
| 4948 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2031 - sec-vrf | PASS | - |
| 4949 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2032 - sec-vrf | PASS | - |
| 4950 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2033 - sec-vrf | PASS | - |
| 4951 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2034 - sec-vrf | PASS | - |
| 4952 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2035 - sec-vrf | PASS | - |
| 4953 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2036 - sec-vrf | PASS | - |
| 4954 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2037 - sec-vrf | PASS | - |
| 4955 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2038 - sec-vrf | PASS | - |
| 4956 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2039 - sec-vrf | PASS | - |
| 4957 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2040 - sec-vrf | PASS | - |
| 4958 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2041 - sec-vrf | PASS | - |
| 4959 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2042 - sec-vrf | PASS | - |
| 4960 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2043 - sec-vrf | PASS | - |
| 4961 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2044 - sec-vrf | PASS | - |
| 4962 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2045 - sec-vrf | PASS | - |
| 4963 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2046 - sec-vrf | PASS | - |
| 4964 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2047 - sec-vrf | PASS | - |
| 4965 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2048 - sec-vrf | PASS | - |
| 4966 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2049 - sec-vrf | PASS | - |
| 4967 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2050 - sec-vrf | PASS | - |
| 4968 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2051 - sec-vrf | PASS | - |
| 4969 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2052 - sec-vrf | PASS | - |
| 4970 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2053 - sec-vrf | PASS | - |
| 4971 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2054 - sec-vrf | PASS | - |
| 4972 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2055 - sec-vrf | PASS | - |
| 4973 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2056 - sec-vrf | PASS | - |
| 4974 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2057 - sec-vrf | PASS | - |
| 4975 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2058 - sec-vrf | PASS | - |
| 4976 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2059 - sec-vrf | PASS | - |
| 4977 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2060 - sec-vrf | PASS | - |
| 4978 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2061 - sec-vrf | PASS | - |
| 4979 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2062 - sec-vrf | PASS | - |
| 4980 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2063 - sec-vrf | PASS | - |
| 4981 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2064 - sec-vrf | PASS | - |
| 4982 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2065 - sec-vrf | PASS | - |
| 4983 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2066 - sec-vrf | PASS | - |
| 4984 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2067 - sec-vrf | PASS | - |
| 4985 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2068 - sec-vrf | PASS | - |
| 4986 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2069 - sec-vrf | PASS | - |
| 4987 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2070 - sec-vrf | PASS | - |
| 4988 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2071 - sec-vrf | PASS | - |
| 4989 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2072 - sec-vrf | PASS | - |
| 4990 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2073 - sec-vrf | PASS | - |
| 4991 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2074 - sec-vrf | PASS | - |
| 4992 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2075 - sec-vrf | PASS | - |
| 4993 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2076 - sec-vrf | PASS | - |
| 4994 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2077 - sec-vrf | PASS | - |
| 4995 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2078 - sec-vrf | PASS | - |
| 4996 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2079 - sec-vrf | PASS | - |
| 4997 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2080 - sec-vrf | PASS | - |
| 4998 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2081 - sec-vrf | PASS | - |
| 4999 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2082 - sec-vrf | PASS | - |
| 5000 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2083 - sec-vrf | PASS | - |
| 5001 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2084 - sec-vrf | PASS | - |
| 5002 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2085 - sec-vrf | PASS | - |
| 5003 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2086 - sec-vrf | PASS | - |
| 5004 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2087 - sec-vrf | PASS | - |
| 5005 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2088 - sec-vrf | PASS | - |
| 5006 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2089 - sec-vrf | PASS | - |
| 5007 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2090 - sec-vrf | PASS | - |
| 5008 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2091 - sec-vrf | PASS | - |
| 5009 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2092 - sec-vrf | PASS | - |
| 5010 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2093 - sec-vrf | PASS | - |
| 5011 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2094 - sec-vrf | PASS | - |
| 5012 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2095 - sec-vrf | PASS | - |
| 5013 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2096 - sec-vrf | PASS | - |
| 5014 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2097 - sec-vrf | PASS | - |
| 5015 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2098 - sec-vrf | PASS | - |
| 5016 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2099 - sec-vrf | PASS | - |
| 5017 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2100 - sec-vrf | PASS | - |
| 5018 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2101 - sec-vrf | PASS | - |
| 5019 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2102 - sec-vrf | PASS | - |
| 5020 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2103 - sec-vrf | PASS | - |
| 5021 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2104 - sec-vrf | PASS | - |
| 5022 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2105 - sec-vrf | PASS | - |
| 5023 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2106 - sec-vrf | PASS | - |
| 5024 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2107 - sec-vrf | PASS | - |
| 5025 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2108 - sec-vrf | PASS | - |
| 5026 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2109 - sec-vrf | PASS | - |
| 5027 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2110 - sec-vrf | PASS | - |
| 5028 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2111 - sec-vrf | PASS | - |
| 5029 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2112 - sec-vrf | PASS | - |
| 5030 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2113 - sec-vrf | PASS | - |
| 5031 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2114 - sec-vrf | PASS | - |
| 5032 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2115 - sec-vrf | PASS | - |
| 5033 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2116 - sec-vrf | PASS | - |
| 5034 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2117 - sec-vrf | PASS | - |
| 5035 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2118 - sec-vrf | PASS | - |
| 5036 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2119 - sec-vrf | PASS | - |
| 5037 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2120 - sec-vrf | PASS | - |
| 5038 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2121 - sec-vrf | PASS | - |
| 5039 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2122 - sec-vrf | PASS | - |
| 5040 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2123 - sec-vrf | PASS | - |
| 5041 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2124 - sec-vrf | PASS | - |
| 5042 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2125 - sec-vrf | PASS | - |
| 5043 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2126 - sec-vrf | PASS | - |
| 5044 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2127 - sec-vrf | PASS | - |
| 5045 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2128 - sec-vrf | PASS | - |
| 5046 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2129 - sec-vrf | PASS | - |
| 5047 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2130 - sec-vrf | PASS | - |
| 5048 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2131 - sec-vrf | PASS | - |
| 5049 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2132 - sec-vrf | PASS | - |
| 5050 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2133 - sec-vrf | PASS | - |
| 5051 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2134 - sec-vrf | PASS | - |
| 5052 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2135 - sec-vrf | PASS | - |
| 5053 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2136 - sec-vrf | PASS | - |
| 5054 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2137 - sec-vrf | PASS | - |
| 5055 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2138 - sec-vrf | PASS | - |
| 5056 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2139 - sec-vrf | PASS | - |
| 5057 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2140 - sec-vrf | PASS | - |
| 5058 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2141 - sec-vrf | PASS | - |
| 5059 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2142 - sec-vrf | PASS | - |
| 5060 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2143 - sec-vrf | PASS | - |
| 5061 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2144 - sec-vrf | PASS | - |
| 5062 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2145 - sec-vrf | PASS | - |
| 5063 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2146 - sec-vrf | PASS | - |
| 5064 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2147 - sec-vrf | PASS | - |
| 5065 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2148 - sec-vrf | PASS | - |
| 5066 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2149 - sec-vrf | PASS | - |
| 5067 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2150 - sec-vrf | PASS | - |
| 5068 | dc2p1_leaf1a_mrv305 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4051 - MLAG_PEER_L3_iBGP: vrf sec | PASS | - |
| 5069 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 5070 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 5071 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan101 - com-vrf | PASS | - |
| 5072 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan102 - com-vrf | PASS | - |
| 5073 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan103 - com-vrf | PASS | - |
| 5074 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan104 - com-vrf | PASS | - |
| 5075 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan105 - com-vrf | PASS | - |
| 5076 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan106 - com-vrf | PASS | - |
| 5077 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan107 - com-vrf | PASS | - |
| 5078 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan108 - com-vrf | PASS | - |
| 5079 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan109 - com-vrf | PASS | - |
| 5080 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan110 - com-vrf | PASS | - |
| 5081 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan111 - com-vrf | PASS | - |
| 5082 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan112 - com-vrf | PASS | - |
| 5083 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan113 - com-vrf | PASS | - |
| 5084 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan114 - com-vrf | PASS | - |
| 5085 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan115 - com-vrf | PASS | - |
| 5086 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan116 - com-vrf | PASS | - |
| 5087 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan117 - com-vrf | PASS | - |
| 5088 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan118 - com-vrf | PASS | - |
| 5089 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan119 - com-vrf | PASS | - |
| 5090 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan120 - com-vrf | PASS | - |
| 5091 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan121 - com-vrf | PASS | - |
| 5092 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan122 - com-vrf | PASS | - |
| 5093 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan123 - com-vrf | PASS | - |
| 5094 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan124 - com-vrf | PASS | - |
| 5095 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan125 - com-vrf | PASS | - |
| 5096 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan126 - com-vrf | PASS | - |
| 5097 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan127 - com-vrf | PASS | - |
| 5098 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan128 - com-vrf | PASS | - |
| 5099 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan129 - com-vrf | PASS | - |
| 5100 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan130 - com-vrf | PASS | - |
| 5101 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan131 - com-vrf | PASS | - |
| 5102 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan132 - com-vrf | PASS | - |
| 5103 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan133 - com-vrf | PASS | - |
| 5104 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan134 - com-vrf | PASS | - |
| 5105 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan135 - com-vrf | PASS | - |
| 5106 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan136 - com-vrf | PASS | - |
| 5107 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan137 - com-vrf | PASS | - |
| 5108 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan138 - com-vrf | PASS | - |
| 5109 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan139 - com-vrf | PASS | - |
| 5110 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan140 - com-vrf | PASS | - |
| 5111 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan141 - com-vrf | PASS | - |
| 5112 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan142 - com-vrf | PASS | - |
| 5113 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan143 - com-vrf | PASS | - |
| 5114 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan144 - com-vrf | PASS | - |
| 5115 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan145 - com-vrf | PASS | - |
| 5116 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan146 - com-vrf | PASS | - |
| 5117 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan147 - com-vrf | PASS | - |
| 5118 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan148 - com-vrf | PASS | - |
| 5119 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan149 - com-vrf | PASS | - |
| 5120 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan150 - com-vrf | PASS | - |
| 5121 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan151 - com-vrf | PASS | - |
| 5122 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan152 - com-vrf | PASS | - |
| 5123 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan153 - com-vrf | PASS | - |
| 5124 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan154 - com-vrf | PASS | - |
| 5125 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan155 - com-vrf | PASS | - |
| 5126 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan156 - com-vrf | PASS | - |
| 5127 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan157 - com-vrf | PASS | - |
| 5128 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan158 - com-vrf | PASS | - |
| 5129 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan159 - com-vrf | PASS | - |
| 5130 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan160 - com-vrf | PASS | - |
| 5131 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan161 - com-vrf | PASS | - |
| 5132 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan162 - com-vrf | PASS | - |
| 5133 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan163 - com-vrf | PASS | - |
| 5134 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan164 - com-vrf | PASS | - |
| 5135 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan165 - com-vrf | PASS | - |
| 5136 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan166 - com-vrf | PASS | - |
| 5137 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan167 - com-vrf | PASS | - |
| 5138 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan168 - com-vrf | PASS | - |
| 5139 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan169 - com-vrf | PASS | - |
| 5140 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan170 - com-vrf | PASS | - |
| 5141 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan171 - com-vrf | PASS | - |
| 5142 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan172 - com-vrf | PASS | - |
| 5143 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan173 - com-vrf | PASS | - |
| 5144 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan174 - com-vrf | PASS | - |
| 5145 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan175 - com-vrf | PASS | - |
| 5146 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan176 - com-vrf | PASS | - |
| 5147 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan177 - com-vrf | PASS | - |
| 5148 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan178 - com-vrf | PASS | - |
| 5149 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan179 - com-vrf | PASS | - |
| 5150 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan180 - com-vrf | PASS | - |
| 5151 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan181 - com-vrf | PASS | - |
| 5152 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan182 - com-vrf | PASS | - |
| 5153 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan183 - com-vrf | PASS | - |
| 5154 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan184 - com-vrf | PASS | - |
| 5155 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan185 - com-vrf | PASS | - |
| 5156 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan186 - com-vrf | PASS | - |
| 5157 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan187 - com-vrf | PASS | - |
| 5158 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan188 - com-vrf | PASS | - |
| 5159 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan189 - com-vrf | PASS | - |
| 5160 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan190 - com-vrf | PASS | - |
| 5161 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan191 - com-vrf | PASS | - |
| 5162 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan192 - com-vrf | PASS | - |
| 5163 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan193 - com-vrf | PASS | - |
| 5164 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan194 - com-vrf | PASS | - |
| 5165 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan195 - com-vrf | PASS | - |
| 5166 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan196 - com-vrf | PASS | - |
| 5167 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan197 - com-vrf | PASS | - |
| 5168 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan198 - com-vrf | PASS | - |
| 5169 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan199 - com-vrf | PASS | - |
| 5170 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan200 - com-vrf | PASS | - |
| 5171 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan201 - com-vrf | PASS | - |
| 5172 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan202 - com-vrf | PASS | - |
| 5173 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan203 - com-vrf | PASS | - |
| 5174 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan204 - com-vrf | PASS | - |
| 5175 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan205 - com-vrf | PASS | - |
| 5176 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan206 - com-vrf | PASS | - |
| 5177 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan207 - com-vrf | PASS | - |
| 5178 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan208 - com-vrf | PASS | - |
| 5179 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan209 - com-vrf | PASS | - |
| 5180 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan210 - com-vrf | PASS | - |
| 5181 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan211 - com-vrf | PASS | - |
| 5182 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan212 - com-vrf | PASS | - |
| 5183 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan213 - com-vrf | PASS | - |
| 5184 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan214 - com-vrf | PASS | - |
| 5185 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan215 - com-vrf | PASS | - |
| 5186 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan216 - com-vrf | PASS | - |
| 5187 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan217 - com-vrf | PASS | - |
| 5188 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan218 - com-vrf | PASS | - |
| 5189 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan219 - com-vrf | PASS | - |
| 5190 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan220 - com-vrf | PASS | - |
| 5191 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan221 - com-vrf | PASS | - |
| 5192 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan222 - com-vrf | PASS | - |
| 5193 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan223 - com-vrf | PASS | - |
| 5194 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan224 - com-vrf | PASS | - |
| 5195 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan225 - com-vrf | PASS | - |
| 5196 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan226 - com-vrf | PASS | - |
| 5197 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan227 - com-vrf | PASS | - |
| 5198 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan228 - com-vrf | PASS | - |
| 5199 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan229 - com-vrf | PASS | - |
| 5200 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan230 - com-vrf | PASS | - |
| 5201 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan231 - com-vrf | PASS | - |
| 5202 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan232 - com-vrf | PASS | - |
| 5203 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan233 - com-vrf | PASS | - |
| 5204 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan234 - com-vrf | PASS | - |
| 5205 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan235 - com-vrf | PASS | - |
| 5206 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan236 - com-vrf | PASS | - |
| 5207 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan237 - com-vrf | PASS | - |
| 5208 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan238 - com-vrf | PASS | - |
| 5209 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan239 - com-vrf | PASS | - |
| 5210 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan240 - com-vrf | PASS | - |
| 5211 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan241 - com-vrf | PASS | - |
| 5212 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan242 - com-vrf | PASS | - |
| 5213 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan243 - com-vrf | PASS | - |
| 5214 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan244 - com-vrf | PASS | - |
| 5215 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan245 - com-vrf | PASS | - |
| 5216 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan246 - com-vrf | PASS | - |
| 5217 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan247 - com-vrf | PASS | - |
| 5218 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan248 - com-vrf | PASS | - |
| 5219 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan249 - com-vrf | PASS | - |
| 5220 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan250 - com-vrf | PASS | - |
| 5221 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan251 - com-vrf | PASS | - |
| 5222 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan252 - com-vrf | PASS | - |
| 5223 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan253 - com-vrf | PASS | - |
| 5224 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan254 - com-vrf | PASS | - |
| 5225 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan255 - com-vrf | PASS | - |
| 5226 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan256 - com-vrf | PASS | - |
| 5227 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan257 - com-vrf | PASS | - |
| 5228 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan258 - com-vrf | PASS | - |
| 5229 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan259 - com-vrf | PASS | - |
| 5230 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan260 - com-vrf | PASS | - |
| 5231 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan261 - com-vrf | PASS | - |
| 5232 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan262 - com-vrf | PASS | - |
| 5233 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan263 - com-vrf | PASS | - |
| 5234 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan264 - com-vrf | PASS | - |
| 5235 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan265 - com-vrf | PASS | - |
| 5236 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan266 - com-vrf | PASS | - |
| 5237 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan267 - com-vrf | PASS | - |
| 5238 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan268 - com-vrf | PASS | - |
| 5239 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan269 - com-vrf | PASS | - |
| 5240 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan270 - com-vrf | PASS | - |
| 5241 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan271 - com-vrf | PASS | - |
| 5242 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan272 - com-vrf | PASS | - |
| 5243 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan273 - com-vrf | PASS | - |
| 5244 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan274 - com-vrf | PASS | - |
| 5245 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan275 - com-vrf | PASS | - |
| 5246 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan276 - com-vrf | PASS | - |
| 5247 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan277 - com-vrf | PASS | - |
| 5248 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan278 - com-vrf | PASS | - |
| 5249 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan279 - com-vrf | PASS | - |
| 5250 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan280 - com-vrf | PASS | - |
| 5251 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan281 - com-vrf | PASS | - |
| 5252 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan282 - com-vrf | PASS | - |
| 5253 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan283 - com-vrf | PASS | - |
| 5254 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan284 - com-vrf | PASS | - |
| 5255 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan285 - com-vrf | PASS | - |
| 5256 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan286 - com-vrf | PASS | - |
| 5257 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan287 - com-vrf | PASS | - |
| 5258 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan288 - com-vrf | PASS | - |
| 5259 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan289 - com-vrf | PASS | - |
| 5260 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan290 - com-vrf | PASS | - |
| 5261 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan291 - com-vrf | PASS | - |
| 5262 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan292 - com-vrf | PASS | - |
| 5263 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan293 - com-vrf | PASS | - |
| 5264 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan294 - com-vrf | PASS | - |
| 5265 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan295 - com-vrf | PASS | - |
| 5266 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan296 - com-vrf | PASS | - |
| 5267 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan297 - com-vrf | PASS | - |
| 5268 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan298 - com-vrf | PASS | - |
| 5269 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan299 - com-vrf | PASS | - |
| 5270 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan300 - com-vrf | PASS | - |
| 5271 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan301 - com-vrf | PASS | - |
| 5272 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan302 - com-vrf | PASS | - |
| 5273 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan303 - com-vrf | PASS | - |
| 5274 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan304 - com-vrf | PASS | - |
| 5275 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan305 - com-vrf | PASS | - |
| 5276 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan306 - com-vrf | PASS | - |
| 5277 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan307 - com-vrf | PASS | - |
| 5278 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan308 - com-vrf | PASS | - |
| 5279 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan309 - com-vrf | PASS | - |
| 5280 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan310 - com-vrf | PASS | - |
| 5281 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan311 - com-vrf | PASS | - |
| 5282 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan312 - com-vrf | PASS | - |
| 5283 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan313 - com-vrf | PASS | - |
| 5284 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan314 - com-vrf | PASS | - |
| 5285 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan315 - com-vrf | PASS | - |
| 5286 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan316 - com-vrf | PASS | - |
| 5287 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan317 - com-vrf | PASS | - |
| 5288 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan318 - com-vrf | PASS | - |
| 5289 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan319 - com-vrf | PASS | - |
| 5290 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan320 - com-vrf | PASS | - |
| 5291 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan321 - com-vrf | PASS | - |
| 5292 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan322 - com-vrf | PASS | - |
| 5293 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan323 - com-vrf | PASS | - |
| 5294 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan324 - com-vrf | PASS | - |
| 5295 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan325 - com-vrf | PASS | - |
| 5296 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan326 - com-vrf | PASS | - |
| 5297 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan327 - com-vrf | PASS | - |
| 5298 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan328 - com-vrf | PASS | - |
| 5299 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan329 - com-vrf | PASS | - |
| 5300 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan330 - com-vrf | PASS | - |
| 5301 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan331 - com-vrf | PASS | - |
| 5302 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan332 - com-vrf | PASS | - |
| 5303 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan333 - com-vrf | PASS | - |
| 5304 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan334 - com-vrf | PASS | - |
| 5305 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan335 - com-vrf | PASS | - |
| 5306 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan336 - com-vrf | PASS | - |
| 5307 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan337 - com-vrf | PASS | - |
| 5308 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan338 - com-vrf | PASS | - |
| 5309 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan339 - com-vrf | PASS | - |
| 5310 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan340 - com-vrf | PASS | - |
| 5311 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan341 - com-vrf | PASS | - |
| 5312 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan342 - com-vrf | PASS | - |
| 5313 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan343 - com-vrf | PASS | - |
| 5314 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan344 - com-vrf | PASS | - |
| 5315 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan345 - com-vrf | PASS | - |
| 5316 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan346 - com-vrf | PASS | - |
| 5317 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan347 - com-vrf | PASS | - |
| 5318 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan348 - com-vrf | PASS | - |
| 5319 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan349 - com-vrf | PASS | - |
| 5320 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan350 - com-vrf | PASS | - |
| 5321 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan351 - com-vrf | PASS | - |
| 5322 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan352 - com-vrf | PASS | - |
| 5323 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan353 - com-vrf | PASS | - |
| 5324 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan354 - com-vrf | PASS | - |
| 5325 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan355 - com-vrf | PASS | - |
| 5326 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan356 - com-vrf | PASS | - |
| 5327 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan357 - com-vrf | PASS | - |
| 5328 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan358 - com-vrf | PASS | - |
| 5329 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan359 - com-vrf | PASS | - |
| 5330 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan360 - com-vrf | PASS | - |
| 5331 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan361 - com-vrf | PASS | - |
| 5332 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan362 - com-vrf | PASS | - |
| 5333 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan363 - com-vrf | PASS | - |
| 5334 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan364 - com-vrf | PASS | - |
| 5335 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan365 - com-vrf | PASS | - |
| 5336 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan366 - com-vrf | PASS | - |
| 5337 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan367 - com-vrf | PASS | - |
| 5338 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan368 - com-vrf | PASS | - |
| 5339 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan369 - com-vrf | PASS | - |
| 5340 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan370 - com-vrf | PASS | - |
| 5341 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan371 - com-vrf | PASS | - |
| 5342 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan372 - com-vrf | PASS | - |
| 5343 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan373 - com-vrf | PASS | - |
| 5344 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan374 - com-vrf | PASS | - |
| 5345 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan375 - com-vrf | PASS | - |
| 5346 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan376 - com-vrf | PASS | - |
| 5347 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan377 - com-vrf | PASS | - |
| 5348 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan378 - com-vrf | PASS | - |
| 5349 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan379 - com-vrf | PASS | - |
| 5350 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan380 - com-vrf | PASS | - |
| 5351 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan381 - com-vrf | PASS | - |
| 5352 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan382 - com-vrf | PASS | - |
| 5353 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan383 - com-vrf | PASS | - |
| 5354 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan384 - com-vrf | PASS | - |
| 5355 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan385 - com-vrf | PASS | - |
| 5356 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan386 - com-vrf | PASS | - |
| 5357 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan387 - com-vrf | PASS | - |
| 5358 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan388 - com-vrf | PASS | - |
| 5359 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan389 - com-vrf | PASS | - |
| 5360 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan390 - com-vrf | PASS | - |
| 5361 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan391 - com-vrf | PASS | - |
| 5362 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan392 - com-vrf | PASS | - |
| 5363 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan393 - com-vrf | PASS | - |
| 5364 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan394 - com-vrf | PASS | - |
| 5365 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan395 - com-vrf | PASS | - |
| 5366 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan396 - com-vrf | PASS | - |
| 5367 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan397 - com-vrf | PASS | - |
| 5368 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan398 - com-vrf | PASS | - |
| 5369 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan399 - com-vrf | PASS | - |
| 5370 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan400 - com-vrf | PASS | - |
| 5371 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan401 - com-vrf | PASS | - |
| 5372 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan402 - com-vrf | PASS | - |
| 5373 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan403 - com-vrf | PASS | - |
| 5374 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan404 - com-vrf | PASS | - |
| 5375 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan405 - com-vrf | PASS | - |
| 5376 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan406 - com-vrf | PASS | - |
| 5377 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan407 - com-vrf | PASS | - |
| 5378 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan408 - com-vrf | PASS | - |
| 5379 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan409 - com-vrf | PASS | - |
| 5380 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan410 - com-vrf | PASS | - |
| 5381 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan411 - com-vrf | PASS | - |
| 5382 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan412 - com-vrf | PASS | - |
| 5383 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan413 - com-vrf | PASS | - |
| 5384 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan414 - com-vrf | PASS | - |
| 5385 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan415 - com-vrf | PASS | - |
| 5386 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan416 - com-vrf | PASS | - |
| 5387 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan417 - com-vrf | PASS | - |
| 5388 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan418 - com-vrf | PASS | - |
| 5389 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan419 - com-vrf | PASS | - |
| 5390 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan420 - com-vrf | PASS | - |
| 5391 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan421 - com-vrf | PASS | - |
| 5392 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan422 - com-vrf | PASS | - |
| 5393 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan423 - com-vrf | PASS | - |
| 5394 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan424 - com-vrf | PASS | - |
| 5395 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan425 - com-vrf | PASS | - |
| 5396 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan426 - com-vrf | PASS | - |
| 5397 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan427 - com-vrf | PASS | - |
| 5398 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan428 - com-vrf | PASS | - |
| 5399 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan429 - com-vrf | PASS | - |
| 5400 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan430 - com-vrf | PASS | - |
| 5401 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan431 - com-vrf | PASS | - |
| 5402 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan432 - com-vrf | PASS | - |
| 5403 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan433 - com-vrf | PASS | - |
| 5404 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan434 - com-vrf | PASS | - |
| 5405 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan435 - com-vrf | PASS | - |
| 5406 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan436 - com-vrf | PASS | - |
| 5407 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan437 - com-vrf | PASS | - |
| 5408 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan438 - com-vrf | PASS | - |
| 5409 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan439 - com-vrf | PASS | - |
| 5410 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan440 - com-vrf | PASS | - |
| 5411 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan441 - com-vrf | PASS | - |
| 5412 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan442 - com-vrf | PASS | - |
| 5413 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan443 - com-vrf | PASS | - |
| 5414 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan444 - com-vrf | PASS | - |
| 5415 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan445 - com-vrf | PASS | - |
| 5416 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan446 - com-vrf | PASS | - |
| 5417 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan447 - com-vrf | PASS | - |
| 5418 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan448 - com-vrf | PASS | - |
| 5419 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan449 - com-vrf | PASS | - |
| 5420 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan450 - com-vrf | PASS | - |
| 5421 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4050 - MLAG_PEER_L3_iBGP: vrf com | PASS | - |
| 5422 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2001 - sec-vrf | PASS | - |
| 5423 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2002 - sec-vrf | PASS | - |
| 5424 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2003 - sec-vrf | PASS | - |
| 5425 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2004 - sec-vrf | PASS | - |
| 5426 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2005 - sec-vrf | PASS | - |
| 5427 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2006 - sec-vrf | PASS | - |
| 5428 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2007 - sec-vrf | PASS | - |
| 5429 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2008 - sec-vrf | PASS | - |
| 5430 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2009 - sec-vrf | PASS | - |
| 5431 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2010 - sec-vrf | PASS | - |
| 5432 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2011 - sec-vrf | PASS | - |
| 5433 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2012 - sec-vrf | PASS | - |
| 5434 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2013 - sec-vrf | PASS | - |
| 5435 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2014 - sec-vrf | PASS | - |
| 5436 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2015 - sec-vrf | PASS | - |
| 5437 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2016 - sec-vrf | PASS | - |
| 5438 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2017 - sec-vrf | PASS | - |
| 5439 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2018 - sec-vrf | PASS | - |
| 5440 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2019 - sec-vrf | PASS | - |
| 5441 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2020 - sec-vrf | PASS | - |
| 5442 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2021 - sec-vrf | PASS | - |
| 5443 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2022 - sec-vrf | PASS | - |
| 5444 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2023 - sec-vrf | PASS | - |
| 5445 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2024 - sec-vrf | PASS | - |
| 5446 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2025 - sec-vrf | PASS | - |
| 5447 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2026 - sec-vrf | PASS | - |
| 5448 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2027 - sec-vrf | PASS | - |
| 5449 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2028 - sec-vrf | PASS | - |
| 5450 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2029 - sec-vrf | PASS | - |
| 5451 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2030 - sec-vrf | PASS | - |
| 5452 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2031 - sec-vrf | PASS | - |
| 5453 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2032 - sec-vrf | PASS | - |
| 5454 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2033 - sec-vrf | PASS | - |
| 5455 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2034 - sec-vrf | PASS | - |
| 5456 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2035 - sec-vrf | PASS | - |
| 5457 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2036 - sec-vrf | PASS | - |
| 5458 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2037 - sec-vrf | PASS | - |
| 5459 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2038 - sec-vrf | PASS | - |
| 5460 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2039 - sec-vrf | PASS | - |
| 5461 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2040 - sec-vrf | PASS | - |
| 5462 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2041 - sec-vrf | PASS | - |
| 5463 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2042 - sec-vrf | PASS | - |
| 5464 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2043 - sec-vrf | PASS | - |
| 5465 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2044 - sec-vrf | PASS | - |
| 5466 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2045 - sec-vrf | PASS | - |
| 5467 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2046 - sec-vrf | PASS | - |
| 5468 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2047 - sec-vrf | PASS | - |
| 5469 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2048 - sec-vrf | PASS | - |
| 5470 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2049 - sec-vrf | PASS | - |
| 5471 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2050 - sec-vrf | PASS | - |
| 5472 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2051 - sec-vrf | PASS | - |
| 5473 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2052 - sec-vrf | PASS | - |
| 5474 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2053 - sec-vrf | PASS | - |
| 5475 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2054 - sec-vrf | PASS | - |
| 5476 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2055 - sec-vrf | PASS | - |
| 5477 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2056 - sec-vrf | PASS | - |
| 5478 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2057 - sec-vrf | PASS | - |
| 5479 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2058 - sec-vrf | PASS | - |
| 5480 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2059 - sec-vrf | PASS | - |
| 5481 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2060 - sec-vrf | PASS | - |
| 5482 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2061 - sec-vrf | PASS | - |
| 5483 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2062 - sec-vrf | PASS | - |
| 5484 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2063 - sec-vrf | PASS | - |
| 5485 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2064 - sec-vrf | PASS | - |
| 5486 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2065 - sec-vrf | PASS | - |
| 5487 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2066 - sec-vrf | PASS | - |
| 5488 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2067 - sec-vrf | PASS | - |
| 5489 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2068 - sec-vrf | PASS | - |
| 5490 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2069 - sec-vrf | PASS | - |
| 5491 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2070 - sec-vrf | PASS | - |
| 5492 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2071 - sec-vrf | PASS | - |
| 5493 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2072 - sec-vrf | PASS | - |
| 5494 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2073 - sec-vrf | PASS | - |
| 5495 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2074 - sec-vrf | PASS | - |
| 5496 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2075 - sec-vrf | PASS | - |
| 5497 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2076 - sec-vrf | PASS | - |
| 5498 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2077 - sec-vrf | PASS | - |
| 5499 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2078 - sec-vrf | PASS | - |
| 5500 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2079 - sec-vrf | PASS | - |
| 5501 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2080 - sec-vrf | PASS | - |
| 5502 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2081 - sec-vrf | PASS | - |
| 5503 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2082 - sec-vrf | PASS | - |
| 5504 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2083 - sec-vrf | PASS | - |
| 5505 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2084 - sec-vrf | PASS | - |
| 5506 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2085 - sec-vrf | PASS | - |
| 5507 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2086 - sec-vrf | PASS | - |
| 5508 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2087 - sec-vrf | PASS | - |
| 5509 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2088 - sec-vrf | PASS | - |
| 5510 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2089 - sec-vrf | PASS | - |
| 5511 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2090 - sec-vrf | PASS | - |
| 5512 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2091 - sec-vrf | PASS | - |
| 5513 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2092 - sec-vrf | PASS | - |
| 5514 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2093 - sec-vrf | PASS | - |
| 5515 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2094 - sec-vrf | PASS | - |
| 5516 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2095 - sec-vrf | PASS | - |
| 5517 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2096 - sec-vrf | PASS | - |
| 5518 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2097 - sec-vrf | PASS | - |
| 5519 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2098 - sec-vrf | PASS | - |
| 5520 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2099 - sec-vrf | PASS | - |
| 5521 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2100 - sec-vrf | PASS | - |
| 5522 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2101 - sec-vrf | PASS | - |
| 5523 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2102 - sec-vrf | PASS | - |
| 5524 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2103 - sec-vrf | PASS | - |
| 5525 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2104 - sec-vrf | PASS | - |
| 5526 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2105 - sec-vrf | PASS | - |
| 5527 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2106 - sec-vrf | PASS | - |
| 5528 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2107 - sec-vrf | PASS | - |
| 5529 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2108 - sec-vrf | PASS | - |
| 5530 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2109 - sec-vrf | PASS | - |
| 5531 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2110 - sec-vrf | PASS | - |
| 5532 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2111 - sec-vrf | PASS | - |
| 5533 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2112 - sec-vrf | PASS | - |
| 5534 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2113 - sec-vrf | PASS | - |
| 5535 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2114 - sec-vrf | PASS | - |
| 5536 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2115 - sec-vrf | PASS | - |
| 5537 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2116 - sec-vrf | PASS | - |
| 5538 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2117 - sec-vrf | PASS | - |
| 5539 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2118 - sec-vrf | PASS | - |
| 5540 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2119 - sec-vrf | PASS | - |
| 5541 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2120 - sec-vrf | PASS | - |
| 5542 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2121 - sec-vrf | PASS | - |
| 5543 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2122 - sec-vrf | PASS | - |
| 5544 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2123 - sec-vrf | PASS | - |
| 5545 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2124 - sec-vrf | PASS | - |
| 5546 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2125 - sec-vrf | PASS | - |
| 5547 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2126 - sec-vrf | PASS | - |
| 5548 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2127 - sec-vrf | PASS | - |
| 5549 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2128 - sec-vrf | PASS | - |
| 5550 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2129 - sec-vrf | PASS | - |
| 5551 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2130 - sec-vrf | PASS | - |
| 5552 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2131 - sec-vrf | PASS | - |
| 5553 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2132 - sec-vrf | PASS | - |
| 5554 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2133 - sec-vrf | PASS | - |
| 5555 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2134 - sec-vrf | PASS | - |
| 5556 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2135 - sec-vrf | PASS | - |
| 5557 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2136 - sec-vrf | PASS | - |
| 5558 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2137 - sec-vrf | PASS | - |
| 5559 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2138 - sec-vrf | PASS | - |
| 5560 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2139 - sec-vrf | PASS | - |
| 5561 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2140 - sec-vrf | PASS | - |
| 5562 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2141 - sec-vrf | PASS | - |
| 5563 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2142 - sec-vrf | PASS | - |
| 5564 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2143 - sec-vrf | PASS | - |
| 5565 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2144 - sec-vrf | PASS | - |
| 5566 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2145 - sec-vrf | PASS | - |
| 5567 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2146 - sec-vrf | PASS | - |
| 5568 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2147 - sec-vrf | PASS | - |
| 5569 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2148 - sec-vrf | PASS | - |
| 5570 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2149 - sec-vrf | PASS | - |
| 5571 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan2150 - sec-vrf | PASS | - |
| 5572 | dc2p1_leaf1b_mrv306 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4051 - MLAG_PEER_L3_iBGP: vrf sec | PASS | - |
| 5573 | oob_spine1_pm362 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 5574 | oob_spine2_pm363 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 5575 | dc1p1_leaf1a_cal418 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 5576 | dc1p1_leaf1b_cal419 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 5577 | dc1p1_leaf2a_cal421 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 5578 | dc1p1_leaf2b_cal422 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 5579 | dc1p1_leaf3a_smd554 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 5580 | dc1p1_leaf3b_smd555 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 5581 | dc1p1_sleaf_smv541 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 5582 | dc1p2_leaf1_mrv453 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 5583 | dc1p2_leaf2_gt272 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 5584 | dc2p1_leaf1a_mrv305 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 5585 | dc2p1_leaf1b_mrv306 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 5586 | dc2p1_sleaf_gt407 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 5587 | dc1p1_leaf1a_cal418 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5588 | dc1p1_leaf1a_cal418 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 5589 | dc1p1_leaf1a_cal418 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback101 - com_VTEP_DIAGNOSTICS | PASS | - |
| 5590 | dc1p1_leaf1a_cal418 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback102 - sec_VTEP_DIAGNOSTICS | PASS | - |
| 5591 | dc1p1_leaf1b_cal419 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5592 | dc1p1_leaf1b_cal419 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 5593 | dc1p1_leaf1b_cal419 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback101 - com_VTEP_DIAGNOSTICS | PASS | - |
| 5594 | dc1p1_leaf1b_cal419 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback102 - sec_VTEP_DIAGNOSTICS | PASS | - |
| 5595 | dc1p1_leaf2a_cal421 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5596 | dc1p1_leaf2a_cal421 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 5597 | dc1p1_leaf2a_cal421 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback101 - com_VTEP_DIAGNOSTICS | PASS | - |
| 5598 | dc1p1_leaf2a_cal421 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback102 - sec_VTEP_DIAGNOSTICS | PASS | - |
| 5599 | dc1p1_leaf2b_cal422 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5600 | dc1p1_leaf2b_cal422 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 5601 | dc1p1_leaf2b_cal422 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback101 - com_VTEP_DIAGNOSTICS | PASS | - |
| 5602 | dc1p1_leaf2b_cal422 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback102 - sec_VTEP_DIAGNOSTICS | PASS | - |
| 5603 | dc1p1_leaf3a_smd554 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5604 | dc1p1_leaf3a_smd554 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 5605 | dc1p1_leaf3a_smd554 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback101 - com_VTEP_DIAGNOSTICS | PASS | - |
| 5606 | dc1p1_leaf3a_smd554 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback102 - sec_VTEP_DIAGNOSTICS | PASS | - |
| 5607 | dc1p1_leaf3b_smd555 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5608 | dc1p1_leaf3b_smd555 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 5609 | dc1p1_leaf3b_smd555 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback101 - com_VTEP_DIAGNOSTICS | PASS | - |
| 5610 | dc1p1_leaf3b_smd555 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback102 - sec_VTEP_DIAGNOSTICS | PASS | - |
| 5611 | dc1p1_sleaf_smv541 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5612 | dc1p1_sleaf_smv541 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 5613 | dc1p1_sleaf_smv541 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback101 - com_VTEP_DIAGNOSTICS | PASS | - |
| 5614 | dc1p1_sleaf_smv541 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback102 - sec_VTEP_DIAGNOSTICS | PASS | - |
| 5615 | dc1p1_spine1_glf437 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5616 | dc1p1_spine2_btp454 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5617 | dc1p1_spine3_btd452 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5618 | dc1p2_leaf1_mrv453 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5619 | dc1p2_leaf1_mrv453 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 5620 | dc1p2_leaf1_mrv453 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback101 - com_VTEP_DIAGNOSTICS | PASS | - |
| 5621 | dc1p2_leaf1_mrv453 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback102 - sec_VTEP_DIAGNOSTICS | PASS | - |
| 5622 | dc1p2_leaf2_gt272 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5623 | dc1p2_leaf2_gt272 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 5624 | dc1p2_leaf2_gt272 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback101 - com_VTEP_DIAGNOSTICS | PASS | - |
| 5625 | dc1p2_leaf2_gt272 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback102 - sec_VTEP_DIAGNOSTICS | PASS | - |
| 5626 | dc1p2_spine1_ghs253 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5627 | dc1p2_spine2_ghs278 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5628 | dc1p2_spine3_ghs281 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5629 | dc2p1_leaf1a_mrv305 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5630 | dc2p1_leaf1a_mrv305 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 5631 | dc2p1_leaf1a_mrv305 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback101 - com_VTEP_DIAGNOSTICS | PASS | - |
| 5632 | dc2p1_leaf1a_mrv305 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback102 - sec_VTEP_DIAGNOSTICS | PASS | - |
| 5633 | dc2p1_leaf1b_mrv306 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5634 | dc2p1_leaf1b_mrv306 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 5635 | dc2p1_leaf1b_mrv306 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback101 - com_VTEP_DIAGNOSTICS | PASS | - |
| 5636 | dc2p1_leaf1b_mrv306 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback102 - sec_VTEP_DIAGNOSTICS | PASS | - |
| 5637 | dc2p1_sleaf_gt407 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5638 | dc2p1_sleaf_gt407 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 5639 | dc2p1_sleaf_gt407 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback101 - com_VTEP_DIAGNOSTICS | PASS | - |
| 5640 | dc2p1_sleaf_gt407 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback102 - sec_VTEP_DIAGNOSTICS | PASS | - |
| 5641 | dc2p1_spine1_ghs282 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5642 | dc2p1_spine2_ghs283 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5643 | dc2p1_spine3_ghs284 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 5644 | dc1p1_leaf1a_cal418 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet53/1 - remote: dc1p1_leaf1b_cal419_Ethernet53/1 | PASS | - |
| 5645 | dc1p1_leaf1a_cal418 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet54/1 - remote: dc1p1_leaf1b_cal419_Ethernet54/1 | PASS | - |
| 5646 | dc1p1_leaf1a_cal418 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet49/1 - remote: dc1p1_spine1_glf437_Ethernet3/1/1 | PASS | - |
| 5647 | dc1p1_leaf1a_cal418 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet50/1 - remote: dc1p1_spine2_btp454_Ethernet3/1 | PASS | - |
| 5648 | dc1p1_leaf1a_cal418 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet51/1 - remote: dc1p1_spine3_btd452_Ethernet3/1 | PASS | - |
| 5649 | dc1p1_leaf1b_cal419 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet53/1 - remote: dc1p1_leaf1a_cal418_Ethernet53/1 | PASS | - |
| 5650 | dc1p1_leaf1b_cal419 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet54/1 - remote: dc1p1_leaf1a_cal418_Ethernet54/1 | PASS | - |
| 5651 | dc1p1_leaf1b_cal419 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet49/1 - remote: dc1p1_spine1_glf437_Ethernet3/2/1 | PASS | - |
| 5652 | dc1p1_leaf1b_cal419 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet50/1 - remote: dc1p1_spine2_btp454_Ethernet4/1 | PASS | - |
| 5653 | dc1p1_leaf1b_cal419 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet51/1 - remote: dc1p1_spine3_btd452_Ethernet4/1 | PASS | - |
| 5654 | dc1p1_leaf2a_cal421 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet53/1 - remote: dc1p1_leaf2b_cal422_Ethernet53/1 | PASS | - |
| 5655 | dc1p1_leaf2a_cal421 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet54/1 - remote: dc1p1_leaf2b_cal422_Ethernet54/1 | PASS | - |
| 5656 | dc1p1_leaf2a_cal421 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet50/1 - remote: dc1p1_spine1_glf437_Ethernet3/3/1 | PASS | - |
| 5657 | dc1p1_leaf2a_cal421 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet51/1 - remote: dc1p1_spine2_btp454_Ethernet5/1 | PASS | - |
| 5658 | dc1p1_leaf2a_cal421 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet52/1 - remote: dc1p1_spine3_btd452_Ethernet5/1 | PASS | - |
| 5659 | dc1p1_leaf2b_cal422 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet53/1 - remote: dc1p1_leaf2a_cal421_Ethernet53/1 | PASS | - |
| 5660 | dc1p1_leaf2b_cal422 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet54/1 - remote: dc1p1_leaf2a_cal421_Ethernet54/1 | PASS | - |
| 5661 | dc1p1_leaf2b_cal422 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet49/1 - remote: dc1p1_spine1_glf437_Ethernet3/4/1 | PASS | - |
| 5662 | dc1p1_leaf2b_cal422 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet50/1 - remote: dc1p1_spine2_btp454_Ethernet6/1 | PASS | - |
| 5663 | dc1p1_leaf2b_cal422 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet51/1 - remote: dc1p1_spine3_btd452_Ethernet6/1 | PASS | - |
| 5664 | dc1p1_leaf3a_smd554 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1/1 - remote: dc1p1_leaf3b_smd555_Ethernet1/1 | PASS | - |
| 5665 | dc1p1_leaf3a_smd554 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2/1 - remote: dc1p1_leaf3b_smd555_Ethernet2/1 | PASS | - |
| 5666 | dc1p1_leaf3a_smd554 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/1 - remote: dc1p1_leaf3b_smd555_Ethernet3/1 | PASS | - |
| 5667 | dc1p1_leaf3a_smd554 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4/1 - remote: dc1p1_leaf3b_smd555_Ethernet4/1 | PASS | - |
| 5668 | dc1p1_leaf3a_smd554 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet33/1 - remote: dc1p1_spine1_glf437_Ethernet4/1/1 | PASS | - |
| 5669 | dc1p1_leaf3a_smd554 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet34/1 - remote: dc1p1_spine2_btp454_Ethernet31/1 | PASS | - |
| 5670 | dc1p1_leaf3a_smd554 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet35/1 - remote: dc1p1_spine3_btd452_Ethernet31/1 | PASS | - |
| 5671 | dc1p1_leaf3b_smd555 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1/1 - remote: dc1p1_leaf3a_smd554_Ethernet1/1 | PASS | - |
| 5672 | dc1p1_leaf3b_smd555 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2/1 - remote: dc1p1_leaf3a_smd554_Ethernet2/1 | PASS | - |
| 5673 | dc1p1_leaf3b_smd555 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/1 - remote: dc1p1_leaf3a_smd554_Ethernet3/1 | PASS | - |
| 5674 | dc1p1_leaf3b_smd555 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4/1 - remote: dc1p1_leaf3a_smd554_Ethernet4/1 | PASS | - |
| 5675 | dc1p1_leaf3b_smd555 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet33/1 - remote: dc1p1_spine1_glf437_Ethernet4/2/1 | PASS | - |
| 5676 | dc1p1_leaf3b_smd555 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet34/1 - remote: dc1p1_spine2_btp454_Ethernet32/1 | PASS | - |
| 5677 | dc1p1_leaf3b_smd555 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet35/1 - remote: dc1p1_spine3_btd452_Ethernet32/1 | PASS | - |
| 5678 | dc1p1_sleaf_smv541 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1/1 - remote: dc1p1_spine1_glf437_Ethernet3/5/1 | PASS | - |
| 5679 | dc1p1_sleaf_smv541 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2/1 - remote: dc1p1_spine2_btp454_Ethernet7/1 | PASS | - |
| 5680 | dc1p1_sleaf_smv541 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/1 - remote: dc1p1_spine3_btd452_Ethernet7/1 | PASS | - |
| 5681 | dc1p1_spine1_glf437 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/1/1 - remote: dc1p1_leaf1a_cal418_Ethernet49/1 | PASS | - |
| 5682 | dc1p1_spine1_glf437 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/2/1 - remote: dc1p1_leaf1b_cal419_Ethernet49/1 | PASS | - |
| 5683 | dc1p1_spine1_glf437 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/3/1 - remote: dc1p1_leaf2a_cal421_Ethernet50/1 | PASS | - |
| 5684 | dc1p1_spine1_glf437 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/4/1 - remote: dc1p1_leaf2b_cal422_Ethernet49/1 | PASS | - |
| 5685 | dc1p1_spine1_glf437 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/5/1 - remote: dc1p1_sleaf_smv541_Ethernet1/1 | PASS | - |
| 5686 | dc1p1_spine1_glf437 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4/1/1 - remote: dc1p1_leaf3a_smd554_Ethernet33/1 | PASS | - |
| 5687 | dc1p1_spine1_glf437 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4/2/1 - remote: dc1p1_leaf3b_smd555_Ethernet33/1 | PASS | - |
| 5688 | dc1p1_spine1_glf437 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2/1/1 - remote: dc1p2_spine1_ghs253_Ethernet1/1 | PASS | - |
| 5689 | dc1p1_spine1_glf437 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2/2/1 - remote: dc2p1_spine1_ghs282_Ethernet1/1 | PASS | - |
| 5690 | dc1p1_spine2_btp454 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/1 - remote: dc1p1_leaf1a_cal418_Ethernet50/1 | PASS | - |
| 5691 | dc1p1_spine2_btp454 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4/1 - remote: dc1p1_leaf1b_cal419_Ethernet50/1 | PASS | - |
| 5692 | dc1p1_spine2_btp454 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5/1 - remote: dc1p1_leaf2a_cal421_Ethernet51/1 | PASS | - |
| 5693 | dc1p1_spine2_btp454 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6/1 - remote: dc1p1_leaf2b_cal422_Ethernet50/1 | PASS | - |
| 5694 | dc1p1_spine2_btp454 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7/1 - remote: dc1p1_sleaf_smv541_Ethernet2/1 | PASS | - |
| 5695 | dc1p1_spine2_btp454 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet31/1 - remote: dc1p1_leaf3a_smd554_Ethernet34/1 | PASS | - |
| 5696 | dc1p1_spine2_btp454 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet32/1 - remote: dc1p1_leaf3b_smd555_Ethernet34/1 | PASS | - |
| 5697 | dc1p1_spine2_btp454 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1/1 - remote: dc1p2_spine2_ghs278_Ethernet1/1 | PASS | - |
| 5698 | dc1p1_spine2_btp454 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2/1 - remote: dc2p1_spine2_ghs283_Ethernet1/1 | PASS | - |
| 5699 | dc1p1_spine3_btd452 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/1 - remote: dc1p1_leaf1a_cal418_Ethernet51/1 | PASS | - |
| 5700 | dc1p1_spine3_btd452 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4/1 - remote: dc1p1_leaf1b_cal419_Ethernet51/1 | PASS | - |
| 5701 | dc1p1_spine3_btd452 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5/1 - remote: dc1p1_leaf2a_cal421_Ethernet52/1 | PASS | - |
| 5702 | dc1p1_spine3_btd452 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6/1 - remote: dc1p1_leaf2b_cal422_Ethernet51/1 | PASS | - |
| 5703 | dc1p1_spine3_btd452 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7/1 - remote: dc1p1_sleaf_smv541_Ethernet3/1 | PASS | - |
| 5704 | dc1p1_spine3_btd452 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet31/1 - remote: dc1p1_leaf3a_smd554_Ethernet35/1 | PASS | - |
| 5705 | dc1p1_spine3_btd452 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet32/1 - remote: dc1p1_leaf3b_smd555_Ethernet35/1 | PASS | - |
| 5706 | dc1p1_spine3_btd452 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1/1 - remote: dc1p2_spine3_ghs281_Ethernet1/1 | PASS | - |
| 5707 | dc1p1_spine3_btd452 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2/1 - remote: dc2p1_spine3_ghs284_Ethernet1/1 | PASS | - |
| 5708 | dc1p2_leaf1_mrv453 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet49/1 - remote: dc1p2_spine1_ghs253_Ethernet3/1 | PASS | - |
| 5709 | dc1p2_leaf1_mrv453 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet50/1 - remote: dc1p2_spine2_ghs278_Ethernet3/1 | PASS | - |
| 5710 | dc1p2_leaf1_mrv453 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet51/1 - remote: dc1p2_spine3_ghs281_Ethernet3/1 | PASS | - |
| 5711 | dc1p2_leaf2_gt272 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet49/1 - remote: dc1p2_spine1_ghs253_Ethernet4/1 | PASS | - |
| 5712 | dc1p2_leaf2_gt272 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet50/1 - remote: dc1p2_spine2_ghs278_Ethernet4/1 | PASS | - |
| 5713 | dc1p2_leaf2_gt272 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet51/1 - remote: dc1p2_spine3_ghs281_Ethernet4/1 | PASS | - |
| 5714 | dc1p2_spine1_ghs253 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/1 - remote: dc1p2_leaf1_mrv453_Ethernet49/1 | PASS | - |
| 5715 | dc1p2_spine1_ghs253 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4/1 - remote: dc1p2_leaf2_gt272_Ethernet49/1 | PASS | - |
| 5716 | dc1p2_spine1_ghs253 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1/1 - remote: dc1p1_spine1_glf437_Ethernet2/1/1 | PASS | - |
| 5717 | dc1p2_spine1_ghs253 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2/1 - remote: dc2p1_spine1_ghs282_Ethernet2/1 | PASS | - |
| 5718 | dc1p2_spine2_ghs278 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/1 - remote: dc1p2_leaf1_mrv453_Ethernet50/1 | PASS | - |
| 5719 | dc1p2_spine2_ghs278 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4/1 - remote: dc1p2_leaf2_gt272_Ethernet50/1 | PASS | - |
| 5720 | dc1p2_spine2_ghs278 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1/1 - remote: dc1p1_spine2_btp454_Ethernet1/1 | PASS | - |
| 5721 | dc1p2_spine2_ghs278 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2/1 - remote: dc2p1_spine2_ghs283_Ethernet2/1 | PASS | - |
| 5722 | dc1p2_spine3_ghs281 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/1 - remote: dc1p2_leaf1_mrv453_Ethernet51/1 | PASS | - |
| 5723 | dc1p2_spine3_ghs281 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4/1 - remote: dc1p2_leaf2_gt272_Ethernet51/1 | PASS | - |
| 5724 | dc1p2_spine3_ghs281 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1/1 - remote: dc1p1_spine3_btd452_Ethernet1/1 | PASS | - |
| 5725 | dc1p2_spine3_ghs281 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2/1 - remote: dc2p1_spine3_ghs284_Ethernet2/1 | PASS | - |
| 5726 | dc2p1_leaf1a_mrv305 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet53/1 - remote: dc2p1_leaf1b_mrv306_Ethernet53/1 | PASS | - |
| 5727 | dc2p1_leaf1a_mrv305 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet54/1 - remote: dc2p1_leaf1b_mrv306_Ethernet54/1 | PASS | - |
| 5728 | dc2p1_leaf1a_mrv305 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet49/1 - remote: dc2p1_spine1_ghs282_Ethernet3/1 | PASS | - |
| 5729 | dc2p1_leaf1a_mrv305 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet50/1 - remote: dc2p1_spine2_ghs283_Ethernet3/1 | PASS | - |
| 5730 | dc2p1_leaf1a_mrv305 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet51/1 - remote: dc2p1_spine3_ghs284_Ethernet3/1 | PASS | - |
| 5731 | dc2p1_leaf1b_mrv306 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet53/1 - remote: dc2p1_leaf1a_mrv305_Ethernet53/1 | PASS | - |
| 5732 | dc2p1_leaf1b_mrv306 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet54/1 - remote: dc2p1_leaf1a_mrv305_Ethernet54/1 | PASS | - |
| 5733 | dc2p1_leaf1b_mrv306 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet49/1 - remote: dc2p1_spine1_ghs282_Ethernet4/1 | PASS | - |
| 5734 | dc2p1_leaf1b_mrv306 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet50/1 - remote: dc2p1_spine2_ghs283_Ethernet4/1 | PASS | - |
| 5735 | dc2p1_leaf1b_mrv306 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet51/1 - remote: dc2p1_spine3_ghs284_Ethernet4/1 | PASS | - |
| 5736 | dc2p1_sleaf_gt407 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet49/1 - remote: dc2p1_spine1_ghs282_Ethernet6/1 | PASS | - |
| 5737 | dc2p1_sleaf_gt407 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet50/1 - remote: dc2p1_spine2_ghs283_Ethernet6/1 | PASS | - |
| 5738 | dc2p1_sleaf_gt407 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet51/1 - remote: dc2p1_spine3_ghs284_Ethernet6/1 | PASS | - |
| 5739 | dc2p1_spine1_ghs282 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/1 - remote: dc2p1_leaf1a_mrv305_Ethernet49/1 | PASS | - |
| 5740 | dc2p1_spine1_ghs282 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4/1 - remote: dc2p1_leaf1b_mrv306_Ethernet49/1 | PASS | - |
| 5741 | dc2p1_spine1_ghs282 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6/1 - remote: dc2p1_sleaf_gt407_Ethernet49/1 | PASS | - |
| 5742 | dc2p1_spine1_ghs282 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1/1 - remote: dc1p1_spine1_glf437_Ethernet2/2/1 | PASS | - |
| 5743 | dc2p1_spine1_ghs282 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2/1 - remote: dc1p2_spine1_ghs253_Ethernet2/1 | PASS | - |
| 5744 | dc2p1_spine2_ghs283 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/1 - remote: dc2p1_leaf1a_mrv305_Ethernet50/1 | PASS | - |
| 5745 | dc2p1_spine2_ghs283 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4/1 - remote: dc2p1_leaf1b_mrv306_Ethernet50/1 | PASS | - |
| 5746 | dc2p1_spine2_ghs283 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6/1 - remote: dc2p1_sleaf_gt407_Ethernet50/1 | PASS | - |
| 5747 | dc2p1_spine2_ghs283 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1/1 - remote: dc1p1_spine2_btp454_Ethernet2/1 | PASS | - |
| 5748 | dc2p1_spine2_ghs283 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2/1 - remote: dc1p2_spine2_ghs278_Ethernet2/1 | PASS | - |
| 5749 | dc2p1_spine3_ghs284 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3/1 - remote: dc2p1_leaf1a_mrv305_Ethernet51/1 | PASS | - |
| 5750 | dc2p1_spine3_ghs284 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4/1 - remote: dc2p1_leaf1b_mrv306_Ethernet51/1 | PASS | - |
| 5751 | dc2p1_spine3_ghs284 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6/1 - remote: dc2p1_sleaf_gt407_Ethernet51/1 | PASS | - |
| 5752 | dc2p1_spine3_ghs284 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1/1 - remote: dc1p1_spine3_btd452_Ethernet2/1 | PASS | - |
| 5753 | dc2p1_spine3_ghs284 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2/1 - remote: dc1p2_spine3_ghs281_Ethernet2/1 | PASS | - |
| 5754 | oob_spine1_pm362 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: oob_spine2_pm363_Ethernet2 | PASS | - |
| 5755 | oob_spine1_pm362 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: oob_spine2_pm363_Ethernet3 | PASS | - |
| 5756 | oob_spine2_pm363 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: oob_spine1_pm362_Ethernet2 | PASS | - |
| 5757 | oob_spine2_pm363 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: oob_spine1_pm362_Ethernet3 | PASS | - |
| 5758 | dc1p1_leaf1a_cal418 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 5759 | dc1p1_leaf1b_cal419 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 5760 | dc1p1_leaf2a_cal421 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 5761 | dc1p1_leaf2b_cal422 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 5762 | dc1p1_leaf3a_smd554 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 5763 | dc1p1_leaf3b_smd555 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 5764 | dc2p1_leaf1a_mrv305 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 5765 | dc2p1_leaf1b_mrv306 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 5766 | oob_spine1_pm362 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 5767 | oob_spine2_pm363 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 5768 | dc1p1_leaf1a_cal418 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf1a_cal418_Ethernet49/1 - Destination: dc1p1_spine1_glf437_Ethernet3/1/1 | FAIL | 100% packet loss |
| 5769 | dc1p1_leaf1a_cal418 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf1a_cal418_Ethernet50/1 - Destination: dc1p1_spine2_btp454_Ethernet3/1 | PASS | - |
| 5770 | dc1p1_leaf1a_cal418 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf1a_cal418_Ethernet51/1 - Destination: dc1p1_spine3_btd452_Ethernet3/1 | PASS | - |
| 5771 | dc1p1_leaf1b_cal419 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf1b_cal419_Ethernet49/1 - Destination: dc1p1_spine1_glf437_Ethernet3/2/1 | FAIL | 100% packet loss |
| 5772 | dc1p1_leaf1b_cal419 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf1b_cal419_Ethernet50/1 - Destination: dc1p1_spine2_btp454_Ethernet4/1 | PASS | - |
| 5773 | dc1p1_leaf1b_cal419 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf1b_cal419_Ethernet51/1 - Destination: dc1p1_spine3_btd452_Ethernet4/1 | PASS | - |
| 5774 | dc1p1_leaf2a_cal421 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf2a_cal421_Ethernet50/1 - Destination: dc1p1_spine1_glf437_Ethernet3/3/1 | FAIL | 100% packet loss |
| 5775 | dc1p1_leaf2a_cal421 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf2a_cal421_Ethernet51/1 - Destination: dc1p1_spine2_btp454_Ethernet5/1 | PASS | - |
| 5776 | dc1p1_leaf2a_cal421 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf2a_cal421_Ethernet52/1 - Destination: dc1p1_spine3_btd452_Ethernet5/1 | PASS | - |
| 5777 | dc1p1_leaf2b_cal422 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf2b_cal422_Ethernet49/1 - Destination: dc1p1_spine1_glf437_Ethernet3/4/1 | FAIL | 100% packet loss |
| 5778 | dc1p1_leaf2b_cal422 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf2b_cal422_Ethernet50/1 - Destination: dc1p1_spine2_btp454_Ethernet6/1 | PASS | - |
| 5779 | dc1p1_leaf2b_cal422 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf2b_cal422_Ethernet51/1 - Destination: dc1p1_spine3_btd452_Ethernet6/1 | PASS | - |
| 5780 | dc1p1_leaf3a_smd554 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf3a_smd554_Ethernet33/1 - Destination: dc1p1_spine1_glf437_Ethernet4/1/1 | FAIL | 100% packet loss |
| 5781 | dc1p1_leaf3a_smd554 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf3a_smd554_Ethernet34/1 - Destination: dc1p1_spine2_btp454_Ethernet31/1 | PASS | - |
| 5782 | dc1p1_leaf3a_smd554 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf3a_smd554_Ethernet35/1 - Destination: dc1p1_spine3_btd452_Ethernet31/1 | PASS | - |
| 5783 | dc1p1_leaf3b_smd555 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf3b_smd555_Ethernet33/1 - Destination: dc1p1_spine1_glf437_Ethernet4/2/1 | FAIL | 100% packet loss |
| 5784 | dc1p1_leaf3b_smd555 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf3b_smd555_Ethernet34/1 - Destination: dc1p1_spine2_btp454_Ethernet32/1 | PASS | - |
| 5785 | dc1p1_leaf3b_smd555 | IP Reachability | ip reachability test p2p links | Source: dc1p1_leaf3b_smd555_Ethernet35/1 - Destination: dc1p1_spine3_btd452_Ethernet32/1 | PASS | - |
| 5786 | dc1p1_sleaf_smv541 | IP Reachability | ip reachability test p2p links | Source: dc1p1_sleaf_smv541_Ethernet1/1 - Destination: dc1p1_spine1_glf437_Ethernet3/5/1 | PASS | - |
| 5787 | dc1p1_sleaf_smv541 | IP Reachability | ip reachability test p2p links | Source: dc1p1_sleaf_smv541_Ethernet2/1 - Destination: dc1p1_spine2_btp454_Ethernet7/1 | PASS | - |
| 5788 | dc1p1_sleaf_smv541 | IP Reachability | ip reachability test p2p links | Source: dc1p1_sleaf_smv541_Ethernet3/1 - Destination: dc1p1_spine3_btd452_Ethernet7/1 | PASS | - |
| 5789 | dc1p1_spine1_glf437 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine1_glf437_Ethernet3/1/1 - Destination: dc1p1_leaf1a_cal418_Ethernet49/1 | FAIL | 100% packet loss |
| 5790 | dc1p1_spine1_glf437 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine1_glf437_Ethernet3/2/1 - Destination: dc1p1_leaf1b_cal419_Ethernet49/1 | FAIL | 100% packet loss |
| 5791 | dc1p1_spine1_glf437 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine1_glf437_Ethernet3/3/1 - Destination: dc1p1_leaf2a_cal421_Ethernet50/1 | FAIL | 100% packet loss |
| 5792 | dc1p1_spine1_glf437 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine1_glf437_Ethernet3/4/1 - Destination: dc1p1_leaf2b_cal422_Ethernet49/1 | FAIL | 100% packet loss |
| 5793 | dc1p1_spine1_glf437 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine1_glf437_Ethernet3/5/1 - Destination: dc1p1_sleaf_smv541_Ethernet1/1 | PASS | - |
| 5794 | dc1p1_spine1_glf437 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine1_glf437_Ethernet4/1/1 - Destination: dc1p1_leaf3a_smd554_Ethernet33/1 | FAIL | 100% packet loss |
| 5795 | dc1p1_spine1_glf437 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine1_glf437_Ethernet4/2/1 - Destination: dc1p1_leaf3b_smd555_Ethernet33/1 | FAIL | 100% packet loss |
| 5796 | dc1p1_spine1_glf437 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine1_glf437_Ethernet2/1/1 - Destination: dc1p2_spine1_ghs253_Ethernet1/1 | PASS | - |
| 5797 | dc1p1_spine1_glf437 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine1_glf437_Ethernet2/2/1 - Destination: dc2p1_spine1_ghs282_Ethernet1/1 | PASS | - |
| 5798 | dc1p1_spine2_btp454 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine2_btp454_Ethernet3/1 - Destination: dc1p1_leaf1a_cal418_Ethernet50/1 | PASS | - |
| 5799 | dc1p1_spine2_btp454 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine2_btp454_Ethernet4/1 - Destination: dc1p1_leaf1b_cal419_Ethernet50/1 | PASS | - |
| 5800 | dc1p1_spine2_btp454 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine2_btp454_Ethernet5/1 - Destination: dc1p1_leaf2a_cal421_Ethernet51/1 | PASS | - |
| 5801 | dc1p1_spine2_btp454 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine2_btp454_Ethernet6/1 - Destination: dc1p1_leaf2b_cal422_Ethernet50/1 | PASS | - |
| 5802 | dc1p1_spine2_btp454 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine2_btp454_Ethernet7/1 - Destination: dc1p1_sleaf_smv541_Ethernet2/1 | PASS | - |
| 5803 | dc1p1_spine2_btp454 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine2_btp454_Ethernet31/1 - Destination: dc1p1_leaf3a_smd554_Ethernet34/1 | PASS | - |
| 5804 | dc1p1_spine2_btp454 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine2_btp454_Ethernet32/1 - Destination: dc1p1_leaf3b_smd555_Ethernet34/1 | PASS | - |
| 5805 | dc1p1_spine2_btp454 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine2_btp454_Ethernet1/1 - Destination: dc1p2_spine2_ghs278_Ethernet1/1 | PASS | - |
| 5806 | dc1p1_spine2_btp454 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine2_btp454_Ethernet2/1 - Destination: dc2p1_spine2_ghs283_Ethernet1/1 | PASS | - |
| 5807 | dc1p1_spine3_btd452 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine3_btd452_Ethernet3/1 - Destination: dc1p1_leaf1a_cal418_Ethernet51/1 | PASS | - |
| 5808 | dc1p1_spine3_btd452 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine3_btd452_Ethernet4/1 - Destination: dc1p1_leaf1b_cal419_Ethernet51/1 | PASS | - |
| 5809 | dc1p1_spine3_btd452 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine3_btd452_Ethernet5/1 - Destination: dc1p1_leaf2a_cal421_Ethernet52/1 | PASS | - |
| 5810 | dc1p1_spine3_btd452 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine3_btd452_Ethernet6/1 - Destination: dc1p1_leaf2b_cal422_Ethernet51/1 | PASS | - |
| 5811 | dc1p1_spine3_btd452 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine3_btd452_Ethernet7/1 - Destination: dc1p1_sleaf_smv541_Ethernet3/1 | PASS | - |
| 5812 | dc1p1_spine3_btd452 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine3_btd452_Ethernet31/1 - Destination: dc1p1_leaf3a_smd554_Ethernet35/1 | PASS | - |
| 5813 | dc1p1_spine3_btd452 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine3_btd452_Ethernet32/1 - Destination: dc1p1_leaf3b_smd555_Ethernet35/1 | PASS | - |
| 5814 | dc1p1_spine3_btd452 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine3_btd452_Ethernet1/1 - Destination: dc1p2_spine3_ghs281_Ethernet1/1 | PASS | - |
| 5815 | dc1p1_spine3_btd452 | IP Reachability | ip reachability test p2p links | Source: dc1p1_spine3_btd452_Ethernet2/1 - Destination: dc2p1_spine3_ghs284_Ethernet1/1 | PASS | - |
| 5816 | dc1p2_leaf1_mrv453 | IP Reachability | ip reachability test p2p links | Source: dc1p2_leaf1_mrv453_Ethernet49/1 - Destination: dc1p2_spine1_ghs253_Ethernet3/1 | PASS | - |
| 5817 | dc1p2_leaf1_mrv453 | IP Reachability | ip reachability test p2p links | Source: dc1p2_leaf1_mrv453_Ethernet50/1 - Destination: dc1p2_spine2_ghs278_Ethernet3/1 | PASS | - |
| 5818 | dc1p2_leaf1_mrv453 | IP Reachability | ip reachability test p2p links | Source: dc1p2_leaf1_mrv453_Ethernet51/1 - Destination: dc1p2_spine3_ghs281_Ethernet3/1 | PASS | - |
| 5819 | dc1p2_leaf2_gt272 | IP Reachability | ip reachability test p2p links | Source: dc1p2_leaf2_gt272_Ethernet49/1 - Destination: dc1p2_spine1_ghs253_Ethernet4/1 | PASS | - |
| 5820 | dc1p2_leaf2_gt272 | IP Reachability | ip reachability test p2p links | Source: dc1p2_leaf2_gt272_Ethernet50/1 - Destination: dc1p2_spine2_ghs278_Ethernet4/1 | PASS | - |
| 5821 | dc1p2_leaf2_gt272 | IP Reachability | ip reachability test p2p links | Source: dc1p2_leaf2_gt272_Ethernet51/1 - Destination: dc1p2_spine3_ghs281_Ethernet4/1 | PASS | - |
| 5822 | dc1p2_spine1_ghs253 | IP Reachability | ip reachability test p2p links | Source: dc1p2_spine1_ghs253_Ethernet3/1 - Destination: dc1p2_leaf1_mrv453_Ethernet49/1 | PASS | - |
| 5823 | dc1p2_spine1_ghs253 | IP Reachability | ip reachability test p2p links | Source: dc1p2_spine1_ghs253_Ethernet4/1 - Destination: dc1p2_leaf2_gt272_Ethernet49/1 | PASS | - |
| 5824 | dc1p2_spine1_ghs253 | IP Reachability | ip reachability test p2p links | Source: dc1p2_spine1_ghs253_Ethernet1/1 - Destination: dc1p1_spine1_glf437_Ethernet2/1/1 | PASS | - |
| 5825 | dc1p2_spine1_ghs253 | IP Reachability | ip reachability test p2p links | Source: dc1p2_spine1_ghs253_Ethernet2/1 - Destination: dc2p1_spine1_ghs282_Ethernet2/1 | PASS | - |
| 5826 | dc1p2_spine2_ghs278 | IP Reachability | ip reachability test p2p links | Source: dc1p2_spine2_ghs278_Ethernet3/1 - Destination: dc1p2_leaf1_mrv453_Ethernet50/1 | PASS | - |
| 5827 | dc1p2_spine2_ghs278 | IP Reachability | ip reachability test p2p links | Source: dc1p2_spine2_ghs278_Ethernet4/1 - Destination: dc1p2_leaf2_gt272_Ethernet50/1 | PASS | - |
| 5828 | dc1p2_spine2_ghs278 | IP Reachability | ip reachability test p2p links | Source: dc1p2_spine2_ghs278_Ethernet1/1 - Destination: dc1p1_spine2_btp454_Ethernet1/1 | PASS | - |
| 5829 | dc1p2_spine2_ghs278 | IP Reachability | ip reachability test p2p links | Source: dc1p2_spine2_ghs278_Ethernet2/1 - Destination: dc2p1_spine2_ghs283_Ethernet2/1 | PASS | - |
| 5830 | dc1p2_spine3_ghs281 | IP Reachability | ip reachability test p2p links | Source: dc1p2_spine3_ghs281_Ethernet3/1 - Destination: dc1p2_leaf1_mrv453_Ethernet51/1 | PASS | - |
| 5831 | dc1p2_spine3_ghs281 | IP Reachability | ip reachability test p2p links | Source: dc1p2_spine3_ghs281_Ethernet4/1 - Destination: dc1p2_leaf2_gt272_Ethernet51/1 | PASS | - |
| 5832 | dc1p2_spine3_ghs281 | IP Reachability | ip reachability test p2p links | Source: dc1p2_spine3_ghs281_Ethernet1/1 - Destination: dc1p1_spine3_btd452_Ethernet1/1 | PASS | - |
| 5833 | dc1p2_spine3_ghs281 | IP Reachability | ip reachability test p2p links | Source: dc1p2_spine3_ghs281_Ethernet2/1 - Destination: dc2p1_spine3_ghs284_Ethernet2/1 | PASS | - |
| 5834 | dc2p1_leaf1a_mrv305 | IP Reachability | ip reachability test p2p links | Source: dc2p1_leaf1a_mrv305_Ethernet49/1 - Destination: dc2p1_spine1_ghs282_Ethernet3/1 | PASS | - |
| 5835 | dc2p1_leaf1a_mrv305 | IP Reachability | ip reachability test p2p links | Source: dc2p1_leaf1a_mrv305_Ethernet50/1 - Destination: dc2p1_spine2_ghs283_Ethernet3/1 | PASS | - |
| 5836 | dc2p1_leaf1a_mrv305 | IP Reachability | ip reachability test p2p links | Source: dc2p1_leaf1a_mrv305_Ethernet51/1 - Destination: dc2p1_spine3_ghs284_Ethernet3/1 | PASS | - |
| 5837 | dc2p1_leaf1b_mrv306 | IP Reachability | ip reachability test p2p links | Source: dc2p1_leaf1b_mrv306_Ethernet49/1 - Destination: dc2p1_spine1_ghs282_Ethernet4/1 | PASS | - |
| 5838 | dc2p1_leaf1b_mrv306 | IP Reachability | ip reachability test p2p links | Source: dc2p1_leaf1b_mrv306_Ethernet50/1 - Destination: dc2p1_spine2_ghs283_Ethernet4/1 | PASS | - |
| 5839 | dc2p1_leaf1b_mrv306 | IP Reachability | ip reachability test p2p links | Source: dc2p1_leaf1b_mrv306_Ethernet51/1 - Destination: dc2p1_spine3_ghs284_Ethernet4/1 | PASS | - |
| 5840 | dc2p1_sleaf_gt407 | IP Reachability | ip reachability test p2p links | Source: dc2p1_sleaf_gt407_Ethernet49/1 - Destination: dc2p1_spine1_ghs282_Ethernet6/1 | PASS | - |
| 5841 | dc2p1_sleaf_gt407 | IP Reachability | ip reachability test p2p links | Source: dc2p1_sleaf_gt407_Ethernet50/1 - Destination: dc2p1_spine2_ghs283_Ethernet6/1 | PASS | - |
| 5842 | dc2p1_sleaf_gt407 | IP Reachability | ip reachability test p2p links | Source: dc2p1_sleaf_gt407_Ethernet51/1 - Destination: dc2p1_spine3_ghs284_Ethernet6/1 | PASS | - |
| 5843 | dc2p1_spine1_ghs282 | IP Reachability | ip reachability test p2p links | Source: dc2p1_spine1_ghs282_Ethernet3/1 - Destination: dc2p1_leaf1a_mrv305_Ethernet49/1 | PASS | - |
| 5844 | dc2p1_spine1_ghs282 | IP Reachability | ip reachability test p2p links | Source: dc2p1_spine1_ghs282_Ethernet4/1 - Destination: dc2p1_leaf1b_mrv306_Ethernet49/1 | PASS | - |
| 5845 | dc2p1_spine1_ghs282 | IP Reachability | ip reachability test p2p links | Source: dc2p1_spine1_ghs282_Ethernet6/1 - Destination: dc2p1_sleaf_gt407_Ethernet49/1 | PASS | - |
| 5846 | dc2p1_spine1_ghs282 | IP Reachability | ip reachability test p2p links | Source: dc2p1_spine1_ghs282_Ethernet1/1 - Destination: dc1p1_spine1_glf437_Ethernet2/2/1 | PASS | - |
| 5847 | dc2p1_spine1_ghs282 | IP Reachability | ip reachability test p2p links | Source: dc2p1_spine1_ghs282_Ethernet2/1 - Destination: dc1p2_spine1_ghs253_Ethernet2/1 | PASS | - |
| 5848 | dc2p1_spine2_ghs283 | IP Reachability | ip reachability test p2p links | Source: dc2p1_spine2_ghs283_Ethernet3/1 - Destination: dc2p1_leaf1a_mrv305_Ethernet50/1 | PASS | - |
| 5849 | dc2p1_spine2_ghs283 | IP Reachability | ip reachability test p2p links | Source: dc2p1_spine2_ghs283_Ethernet4/1 - Destination: dc2p1_leaf1b_mrv306_Ethernet50/1 | PASS | - |
| 5850 | dc2p1_spine2_ghs283 | IP Reachability | ip reachability test p2p links | Source: dc2p1_spine2_ghs283_Ethernet6/1 - Destination: dc2p1_sleaf_gt407_Ethernet50/1 | PASS | - |
| 5851 | dc2p1_spine2_ghs283 | IP Reachability | ip reachability test p2p links | Source: dc2p1_spine2_ghs283_Ethernet1/1 - Destination: dc1p1_spine2_btp454_Ethernet2/1 | PASS | - |
| 5852 | dc2p1_spine2_ghs283 | IP Reachability | ip reachability test p2p links | Source: dc2p1_spine2_ghs283_Ethernet2/1 - Destination: dc1p2_spine2_ghs278_Ethernet2/1 | PASS | - |
| 5853 | dc2p1_spine3_ghs284 | IP Reachability | ip reachability test p2p links | Source: dc2p1_spine3_ghs284_Ethernet3/1 - Destination: dc2p1_leaf1a_mrv305_Ethernet51/1 | PASS | - |
| 5854 | dc2p1_spine3_ghs284 | IP Reachability | ip reachability test p2p links | Source: dc2p1_spine3_ghs284_Ethernet4/1 - Destination: dc2p1_leaf1b_mrv306_Ethernet51/1 | PASS | - |
| 5855 | dc2p1_spine3_ghs284 | IP Reachability | ip reachability test p2p links | Source: dc2p1_spine3_ghs284_Ethernet6/1 - Destination: dc2p1_sleaf_gt407_Ethernet51/1 | PASS | - |
| 5856 | dc2p1_spine3_ghs284 | IP Reachability | ip reachability test p2p links | Source: dc2p1_spine3_ghs284_Ethernet1/1 - Destination: dc1p1_spine3_btd452_Ethernet2/1 | PASS | - |
| 5857 | dc2p1_spine3_ghs284 | IP Reachability | ip reachability test p2p links | Source: dc2p1_spine3_ghs284_Ethernet2/1 - Destination: dc1p2_spine3_ghs281_Ethernet2/1 | PASS | - |
| 5858 | dc1p1_leaf1a_cal418 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5859 | dc1p1_leaf1b_cal419 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5860 | dc1p1_leaf2a_cal421 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5861 | dc1p1_leaf2b_cal422 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5862 | dc1p1_leaf3a_smd554 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5863 | dc1p1_leaf3b_smd555 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5864 | dc1p1_sleaf_smv541 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5865 | dc1p1_spine1_glf437 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5866 | dc1p1_spine2_btp454 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5867 | dc1p1_spine3_btd452 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5868 | dc1p2_leaf1_mrv453 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5869 | dc1p2_leaf2_gt272 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5870 | dc1p2_spine1_ghs253 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5871 | dc1p2_spine2_ghs278 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5872 | dc1p2_spine3_ghs281 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5873 | dc2p1_leaf1a_mrv305 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5874 | dc2p1_leaf1b_mrv306 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5875 | dc2p1_sleaf_gt407 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5876 | dc2p1_spine1_ghs282 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5877 | dc2p1_spine2_ghs283 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5878 | dc2p1_spine3_ghs284 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 5879 | dc1p1_leaf1a_cal418 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.2.5.1 | PASS | - |
| 5880 | dc1p1_leaf1a_cal418 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.0 | FAIL | Session state Active |
| 5881 | dc1p1_leaf1a_cal418 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.2 | PASS | - |
| 5882 | dc1p1_leaf1a_cal418 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.4 | PASS | - |
| 5883 | dc1p1_leaf1b_cal419 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.2.5.0 | PASS | - |
| 5884 | dc1p1_leaf1b_cal419 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.6 | FAIL | Session state Active |
| 5885 | dc1p1_leaf1b_cal419 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.8 | PASS | - |
| 5886 | dc1p1_leaf1b_cal419 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.10 | PASS | - |
| 5887 | dc1p1_leaf2a_cal421 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.2.5.5 | PASS | - |
| 5888 | dc1p1_leaf2a_cal421 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.12 | FAIL | Session state Active |
| 5889 | dc1p1_leaf2a_cal421 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.14 | PASS | - |
| 5890 | dc1p1_leaf2a_cal421 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.16 | PASS | - |
| 5891 | dc1p1_leaf2b_cal422 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.2.5.4 | PASS | - |
| 5892 | dc1p1_leaf2b_cal422 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.18 | FAIL | Session state Active |
| 5893 | dc1p1_leaf2b_cal422 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.20 | PASS | - |
| 5894 | dc1p1_leaf2b_cal422 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.22 | PASS | - |
| 5895 | dc1p1_leaf3a_smd554 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.2.5.9 | PASS | - |
| 5896 | dc1p1_leaf3a_smd554 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.24 | FAIL | Session state Active |
| 5897 | dc1p1_leaf3a_smd554 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.26 | PASS | - |
| 5898 | dc1p1_leaf3a_smd554 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.28 | PASS | - |
| 5899 | dc1p1_leaf3b_smd555 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.2.5.8 | PASS | - |
| 5900 | dc1p1_leaf3b_smd555 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.30 | FAIL | Session state Active |
| 5901 | dc1p1_leaf3b_smd555 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.32 | PASS | - |
| 5902 | dc1p1_leaf3b_smd555 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.34 | PASS | - |
| 5903 | dc1p1_sleaf_smv541 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.36 | PASS | - |
| 5904 | dc1p1_sleaf_smv541 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.38 | PASS | - |
| 5905 | dc1p1_sleaf_smv541 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.40 | PASS | - |
| 5906 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.1 | FAIL | Session state Idle |
| 5907 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.7 | FAIL | Session state Idle |
| 5908 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.13 | FAIL | Session state Idle |
| 5909 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.19 | FAIL | Session state Idle |
| 5910 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.37 | PASS | - |
| 5911 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.25 | FAIL | Session state Idle |
| 5912 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.31 | FAIL | Session state Idle |
| 5913 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.1 | PASS | - |
| 5914 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.3 | PASS | - |
| 5915 | dc1p1_spine1_glf437 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 163.1.0.1 | PASS | - |
| 5916 | dc1p1_spine2_btp454 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.3 | PASS | - |
| 5917 | dc1p1_spine2_btp454 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.9 | PASS | - |
| 5918 | dc1p1_spine2_btp454 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.15 | PASS | - |
| 5919 | dc1p1_spine2_btp454 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.21 | PASS | - |
| 5920 | dc1p1_spine2_btp454 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.39 | PASS | - |
| 5921 | dc1p1_spine2_btp454 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.27 | PASS | - |
| 5922 | dc1p1_spine2_btp454 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.33 | PASS | - |
| 5923 | dc1p1_spine2_btp454 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.5 | PASS | - |
| 5924 | dc1p1_spine2_btp454 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.7 | PASS | - |
| 5925 | dc1p1_spine3_btd452 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.5 | PASS | - |
| 5926 | dc1p1_spine3_btd452 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.11 | PASS | - |
| 5927 | dc1p1_spine3_btd452 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.17 | PASS | - |
| 5928 | dc1p1_spine3_btd452 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.23 | PASS | - |
| 5929 | dc1p1_spine3_btd452 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.41 | PASS | - |
| 5930 | dc1p1_spine3_btd452 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.29 | PASS | - |
| 5931 | dc1p1_spine3_btd452 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.35 | PASS | - |
| 5932 | dc1p1_spine3_btd452 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.9 | PASS | - |
| 5933 | dc1p1_spine3_btd452 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.11 | PASS | - |
| 5934 | dc1p2_leaf1_mrv453 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.42 | PASS | - |
| 5935 | dc1p2_leaf1_mrv453 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.44 | PASS | - |
| 5936 | dc1p2_leaf1_mrv453 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.46 | PASS | - |
| 5937 | dc1p2_leaf2_gt272 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.48 | PASS | - |
| 5938 | dc1p2_leaf2_gt272 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.50 | PASS | - |
| 5939 | dc1p2_leaf2_gt272 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.52 | PASS | - |
| 5940 | dc1p2_spine1_ghs253 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.43 | PASS | - |
| 5941 | dc1p2_spine1_ghs253 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.49 | PASS | - |
| 5942 | dc1p2_spine1_ghs253 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.0 | PASS | - |
| 5943 | dc1p2_spine1_ghs253 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.13 | PASS | - |
| 5944 | dc1p2_spine1_ghs253 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 163.1.1.1 | PASS | - |
| 5945 | dc1p2_spine2_ghs278 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.45 | PASS | - |
| 5946 | dc1p2_spine2_ghs278 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.51 | PASS | - |
| 5947 | dc1p2_spine2_ghs278 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.4 | PASS | - |
| 5948 | dc1p2_spine2_ghs278 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.15 | PASS | - |
| 5949 | dc1p2_spine3_ghs281 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.47 | PASS | - |
| 5950 | dc1p2_spine3_ghs281 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.53 | PASS | - |
| 5951 | dc1p2_spine3_ghs281 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.8 | PASS | - |
| 5952 | dc1p2_spine3_ghs281 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.17 | PASS | - |
| 5953 | dc2p1_leaf1a_mrv305 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.2.5.19 | PASS | - |
| 5954 | dc2p1_leaf1a_mrv305 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.54 | PASS | - |
| 5955 | dc2p1_leaf1a_mrv305 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.56 | PASS | - |
| 5956 | dc2p1_leaf1a_mrv305 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.58 | PASS | - |
| 5957 | dc2p1_leaf1b_mrv306 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.2.5.18 | PASS | - |
| 5958 | dc2p1_leaf1b_mrv306 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.60 | PASS | - |
| 5959 | dc2p1_leaf1b_mrv306 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.62 | PASS | - |
| 5960 | dc2p1_leaf1b_mrv306 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.64 | PASS | - |
| 5961 | dc2p1_sleaf_gt407 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.66 | PASS | - |
| 5962 | dc2p1_sleaf_gt407 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.68 | PASS | - |
| 5963 | dc2p1_sleaf_gt407 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.70 | PASS | - |
| 5964 | dc2p1_spine1_ghs282 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.55 | PASS | - |
| 5965 | dc2p1_spine1_ghs282 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.61 | PASS | - |
| 5966 | dc2p1_spine1_ghs282 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.67 | PASS | - |
| 5967 | dc2p1_spine1_ghs282 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.2 | PASS | - |
| 5968 | dc2p1_spine1_ghs282 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.12 | PASS | - |
| 5969 | dc2p1_spine1_ghs282 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 163.1.2.1 | PASS | - |
| 5970 | dc2p1_spine2_ghs283 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.57 | PASS | - |
| 5971 | dc2p1_spine2_ghs283 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.63 | PASS | - |
| 5972 | dc2p1_spine2_ghs283 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.69 | PASS | - |
| 5973 | dc2p1_spine2_ghs283 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.6 | PASS | - |
| 5974 | dc2p1_spine2_ghs283 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.14 | PASS | - |
| 5975 | dc2p1_spine3_ghs284 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.59 | PASS | - |
| 5976 | dc2p1_spine3_ghs284 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.65 | PASS | - |
| 5977 | dc2p1_spine3_ghs284 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 161.1.0.71 | PASS | - |
| 5978 | dc2p1_spine3_ghs284 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.10 | PASS | - |
| 5979 | dc2p1_spine3_ghs284 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 162.5.1.16 | PASS | - |
| 5980 | dc1p1_leaf1a_cal418 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.1 | FAIL | Session state: Active |
| 5981 | dc1p1_leaf1a_cal418 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.2 | PASS | - |
| 5982 | dc1p1_leaf1a_cal418 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.3 | PASS | - |
| 5983 | dc1p1_leaf1b_cal419 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.1 | FAIL | Session state: Active |
| 5984 | dc1p1_leaf1b_cal419 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.2 | PASS | - |
| 5985 | dc1p1_leaf1b_cal419 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.3 | PASS | - |
| 5986 | dc1p1_leaf2a_cal421 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.1 | FAIL | Session state: Active |
| 5987 | dc1p1_leaf2a_cal421 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.2 | PASS | - |
| 5988 | dc1p1_leaf2a_cal421 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.3 | PASS | - |
| 5989 | dc1p1_leaf2b_cal422 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.1 | FAIL | Session state: Active |
| 5990 | dc1p1_leaf2b_cal422 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.2 | PASS | - |
| 5991 | dc1p1_leaf2b_cal422 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.3 | PASS | - |
| 5992 | dc1p1_leaf3a_smd554 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.1 | FAIL | Session state: Active |
| 5993 | dc1p1_leaf3a_smd554 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.2 | PASS | - |
| 5994 | dc1p1_leaf3a_smd554 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.3 | PASS | - |
| 5995 | dc1p1_leaf3b_smd555 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.1 | FAIL | Session state: Active |
| 5996 | dc1p1_leaf3b_smd555 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.2 | PASS | - |
| 5997 | dc1p1_leaf3b_smd555 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.3 | PASS | - |
| 5998 | dc1p1_sleaf_smv541 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.1 | PASS | - |
| 5999 | dc1p1_sleaf_smv541 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.2 | PASS | - |
| 6000 | dc1p1_sleaf_smv541 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.3 | PASS | - |
| 6001 | dc1p1_spine1_glf437 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.1.3 | FAIL | Session state: Active |
| 6002 | dc1p1_spine1_glf437 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.1.4 | FAIL | Session state: Active |
| 6003 | dc1p1_spine1_glf437 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.2.5 | FAIL | Session state: Active |
| 6004 | dc1p1_spine1_glf437 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.2.6 | FAIL | Session state: Active |
| 6005 | dc1p1_spine1_glf437 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.3.7 | FAIL | Session state: Active |
| 6006 | dc1p1_spine1_glf437 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.3.8 | FAIL | Session state: Active |
| 6007 | dc1p1_spine1_glf437 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.4.9 | PASS | - |
| 6008 | dc1p1_spine1_glf437 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.2.4 | PASS | - |
| 6009 | dc1p1_spine1_glf437 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.3.7 | PASS | - |
| 6010 | dc1p1_spine2_btp454 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.1.3 | PASS | - |
| 6011 | dc1p1_spine2_btp454 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.1.4 | PASS | - |
| 6012 | dc1p1_spine2_btp454 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.2.5 | PASS | - |
| 6013 | dc1p1_spine2_btp454 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.2.6 | PASS | - |
| 6014 | dc1p1_spine2_btp454 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.3.7 | PASS | - |
| 6015 | dc1p1_spine2_btp454 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.3.8 | PASS | - |
| 6016 | dc1p1_spine2_btp454 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.4.9 | PASS | - |
| 6017 | dc1p1_spine2_btp454 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.2.5 | PASS | - |
| 6018 | dc1p1_spine2_btp454 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.3.8 | PASS | - |
| 6019 | dc1p1_spine3_btd452 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.1.3 | PASS | - |
| 6020 | dc1p1_spine3_btd452 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.1.4 | PASS | - |
| 6021 | dc1p1_spine3_btd452 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.2.5 | PASS | - |
| 6022 | dc1p1_spine3_btd452 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.2.6 | PASS | - |
| 6023 | dc1p1_spine3_btd452 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.3.7 | PASS | - |
| 6024 | dc1p1_spine3_btd452 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.3.8 | PASS | - |
| 6025 | dc1p1_spine3_btd452 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.1.4.9 | PASS | - |
| 6026 | dc1p1_spine3_btd452 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.2.6 | PASS | - |
| 6027 | dc1p1_spine3_btd452 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.3.9 | PASS | - |
| 6028 | dc1p2_leaf1_mrv453 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.2.4 | PASS | - |
| 6029 | dc1p2_leaf1_mrv453 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.2.5 | PASS | - |
| 6030 | dc1p2_leaf1_mrv453 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.2.6 | PASS | - |
| 6031 | dc1p2_leaf2_gt272 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.2.4 | PASS | - |
| 6032 | dc1p2_leaf2_gt272 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.2.5 | PASS | - |
| 6033 | dc1p2_leaf2_gt272 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.2.6 | PASS | - |
| 6034 | dc1p2_spine1_ghs253 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.2.1.10 | PASS | - |
| 6035 | dc1p2_spine1_ghs253 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.2.2.11 | PASS | - |
| 6036 | dc1p2_spine1_ghs253 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.1 | PASS | - |
| 6037 | dc1p2_spine1_ghs253 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.3.7 | PASS | - |
| 6038 | dc1p2_spine2_ghs278 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.2.1.10 | PASS | - |
| 6039 | dc1p2_spine2_ghs278 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.2.2.11 | PASS | - |
| 6040 | dc1p2_spine2_ghs278 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.2 | PASS | - |
| 6041 | dc1p2_spine2_ghs278 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.3.8 | PASS | - |
| 6042 | dc1p2_spine3_ghs281 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.2.1.10 | PASS | - |
| 6043 | dc1p2_spine3_ghs281 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.2.2.11 | PASS | - |
| 6044 | dc1p2_spine3_ghs281 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.3 | PASS | - |
| 6045 | dc1p2_spine3_ghs281 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.3.9 | PASS | - |
| 6046 | dc2p1_leaf1a_mrv305 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.3.7 | PASS | - |
| 6047 | dc2p1_leaf1a_mrv305 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.3.8 | PASS | - |
| 6048 | dc2p1_leaf1a_mrv305 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.3.9 | PASS | - |
| 6049 | dc2p1_leaf1b_mrv306 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.3.7 | PASS | - |
| 6050 | dc2p1_leaf1b_mrv306 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.3.8 | PASS | - |
| 6051 | dc2p1_leaf1b_mrv306 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.3.9 | PASS | - |
| 6052 | dc2p1_sleaf_gt407 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.3.7 | PASS | - |
| 6053 | dc2p1_sleaf_gt407 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.3.8 | PASS | - |
| 6054 | dc2p1_sleaf_gt407 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.3.9 | PASS | - |
| 6055 | dc2p1_spine1_ghs282 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.3.1.12 | PASS | - |
| 6056 | dc2p1_spine1_ghs282 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.3.1.13 | PASS | - |
| 6057 | dc2p1_spine1_ghs282 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.3.2.14 | PASS | - |
| 6058 | dc2p1_spine1_ghs282 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.1 | PASS | - |
| 6059 | dc2p1_spine1_ghs282 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.2.4 | PASS | - |
| 6060 | dc2p1_spine2_ghs283 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.3.1.12 | PASS | - |
| 6061 | dc2p1_spine2_ghs283 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.3.1.13 | PASS | - |
| 6062 | dc2p1_spine2_ghs283 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.3.2.14 | PASS | - |
| 6063 | dc2p1_spine2_ghs283 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.2 | PASS | - |
| 6064 | dc2p1_spine2_ghs283 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.2.5 | PASS | - |
| 6065 | dc2p1_spine3_ghs284 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.3.1.12 | PASS | - |
| 6066 | dc2p1_spine3_ghs284 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.3.1.13 | PASS | - |
| 6067 | dc2p1_spine3_ghs284 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.3.2.14 | PASS | - |
| 6068 | dc2p1_spine3_ghs284 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.1.3 | PASS | - |
| 6069 | dc2p1_spine3_ghs284 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 150.9.2.6 | PASS | - |
| 6070 | dc1p1_leaf1a_cal418 | Routing Table | Remote VTEP address | 150.1.1.3 | PASS | - |
| 6071 | dc1p1_leaf1a_cal418 | Routing Table | Remote VTEP address | 150.1.1.4 | PASS | - |
| 6072 | dc1p1_leaf1a_cal418 | Routing Table | Remote VTEP address | 150.1.2.5 | PASS | - |
| 6073 | dc1p1_leaf1a_cal418 | Routing Table | Remote VTEP address | 150.1.2.6 | PASS | - |
| 6074 | dc1p1_leaf1a_cal418 | Routing Table | Remote VTEP address | 150.1.3.7 | PASS | - |
| 6075 | dc1p1_leaf1a_cal418 | Routing Table | Remote VTEP address | 150.1.3.8 | PASS | - |
| 6076 | dc1p1_leaf1a_cal418 | Routing Table | Remote VTEP address | 9.1.1.9 | PASS | - |
| 6077 | dc1p1_leaf1a_cal418 | Routing Table | Remote VTEP address | 3.2.1.10 | PASS | - |
| 6078 | dc1p1_leaf1a_cal418 | Routing Table | Remote VTEP address | 3.2.2.11 | PASS | - |
| 6079 | dc1p1_leaf1a_cal418 | Routing Table | Remote VTEP address | 150.3.1.12 | PASS | - |
| 6080 | dc1p1_leaf1a_cal418 | Routing Table | Remote VTEP address | 150.3.1.13 | PASS | - |
| 6081 | dc1p1_leaf1a_cal418 | Routing Table | Remote VTEP address | 9.3.1.14 | PASS | - |
| 6082 | dc1p1_leaf1b_cal419 | Routing Table | Remote VTEP address | 150.1.1.3 | PASS | - |
| 6083 | dc1p1_leaf1b_cal419 | Routing Table | Remote VTEP address | 150.1.1.4 | PASS | - |
| 6084 | dc1p1_leaf1b_cal419 | Routing Table | Remote VTEP address | 150.1.2.5 | PASS | - |
| 6085 | dc1p1_leaf1b_cal419 | Routing Table | Remote VTEP address | 150.1.2.6 | PASS | - |
| 6086 | dc1p1_leaf1b_cal419 | Routing Table | Remote VTEP address | 150.1.3.7 | PASS | - |
| 6087 | dc1p1_leaf1b_cal419 | Routing Table | Remote VTEP address | 150.1.3.8 | PASS | - |
| 6088 | dc1p1_leaf1b_cal419 | Routing Table | Remote VTEP address | 9.1.1.9 | PASS | - |
| 6089 | dc1p1_leaf1b_cal419 | Routing Table | Remote VTEP address | 3.2.1.10 | PASS | - |
| 6090 | dc1p1_leaf1b_cal419 | Routing Table | Remote VTEP address | 3.2.2.11 | PASS | - |
| 6091 | dc1p1_leaf1b_cal419 | Routing Table | Remote VTEP address | 150.3.1.12 | PASS | - |
| 6092 | dc1p1_leaf1b_cal419 | Routing Table | Remote VTEP address | 150.3.1.13 | PASS | - |
| 6093 | dc1p1_leaf1b_cal419 | Routing Table | Remote VTEP address | 9.3.1.14 | PASS | - |
| 6094 | dc1p1_leaf2a_cal421 | Routing Table | Remote VTEP address | 150.1.1.3 | PASS | - |
| 6095 | dc1p1_leaf2a_cal421 | Routing Table | Remote VTEP address | 150.1.1.4 | PASS | - |
| 6096 | dc1p1_leaf2a_cal421 | Routing Table | Remote VTEP address | 150.1.2.5 | PASS | - |
| 6097 | dc1p1_leaf2a_cal421 | Routing Table | Remote VTEP address | 150.1.2.6 | PASS | - |
| 6098 | dc1p1_leaf2a_cal421 | Routing Table | Remote VTEP address | 150.1.3.7 | PASS | - |
| 6099 | dc1p1_leaf2a_cal421 | Routing Table | Remote VTEP address | 150.1.3.8 | PASS | - |
| 6100 | dc1p1_leaf2a_cal421 | Routing Table | Remote VTEP address | 9.1.1.9 | PASS | - |
| 6101 | dc1p1_leaf2a_cal421 | Routing Table | Remote VTEP address | 3.2.1.10 | PASS | - |
| 6102 | dc1p1_leaf2a_cal421 | Routing Table | Remote VTEP address | 3.2.2.11 | PASS | - |
| 6103 | dc1p1_leaf2a_cal421 | Routing Table | Remote VTEP address | 150.3.1.12 | PASS | - |
| 6104 | dc1p1_leaf2a_cal421 | Routing Table | Remote VTEP address | 150.3.1.13 | PASS | - |
| 6105 | dc1p1_leaf2a_cal421 | Routing Table | Remote VTEP address | 9.3.1.14 | PASS | - |
| 6106 | dc1p1_leaf2b_cal422 | Routing Table | Remote VTEP address | 150.1.1.3 | PASS | - |
| 6107 | dc1p1_leaf2b_cal422 | Routing Table | Remote VTEP address | 150.1.1.4 | PASS | - |
| 6108 | dc1p1_leaf2b_cal422 | Routing Table | Remote VTEP address | 150.1.2.5 | PASS | - |
| 6109 | dc1p1_leaf2b_cal422 | Routing Table | Remote VTEP address | 150.1.2.6 | PASS | - |
| 6110 | dc1p1_leaf2b_cal422 | Routing Table | Remote VTEP address | 150.1.3.7 | PASS | - |
| 6111 | dc1p1_leaf2b_cal422 | Routing Table | Remote VTEP address | 150.1.3.8 | PASS | - |
| 6112 | dc1p1_leaf2b_cal422 | Routing Table | Remote VTEP address | 9.1.1.9 | PASS | - |
| 6113 | dc1p1_leaf2b_cal422 | Routing Table | Remote VTEP address | 3.2.1.10 | PASS | - |
| 6114 | dc1p1_leaf2b_cal422 | Routing Table | Remote VTEP address | 3.2.2.11 | PASS | - |
| 6115 | dc1p1_leaf2b_cal422 | Routing Table | Remote VTEP address | 150.3.1.12 | PASS | - |
| 6116 | dc1p1_leaf2b_cal422 | Routing Table | Remote VTEP address | 150.3.1.13 | PASS | - |
| 6117 | dc1p1_leaf2b_cal422 | Routing Table | Remote VTEP address | 9.3.1.14 | PASS | - |
| 6118 | dc1p1_leaf3a_smd554 | Routing Table | Remote VTEP address | 150.1.1.3 | PASS | - |
| 6119 | dc1p1_leaf3a_smd554 | Routing Table | Remote VTEP address | 150.1.1.4 | PASS | - |
| 6120 | dc1p1_leaf3a_smd554 | Routing Table | Remote VTEP address | 150.1.2.5 | PASS | - |
| 6121 | dc1p1_leaf3a_smd554 | Routing Table | Remote VTEP address | 150.1.2.6 | PASS | - |
| 6122 | dc1p1_leaf3a_smd554 | Routing Table | Remote VTEP address | 150.1.3.7 | PASS | - |
| 6123 | dc1p1_leaf3a_smd554 | Routing Table | Remote VTEP address | 150.1.3.8 | PASS | - |
| 6124 | dc1p1_leaf3a_smd554 | Routing Table | Remote VTEP address | 9.1.1.9 | PASS | - |
| 6125 | dc1p1_leaf3a_smd554 | Routing Table | Remote VTEP address | 3.2.1.10 | PASS | - |
| 6126 | dc1p1_leaf3a_smd554 | Routing Table | Remote VTEP address | 3.2.2.11 | PASS | - |
| 6127 | dc1p1_leaf3a_smd554 | Routing Table | Remote VTEP address | 150.3.1.12 | PASS | - |
| 6128 | dc1p1_leaf3a_smd554 | Routing Table | Remote VTEP address | 150.3.1.13 | PASS | - |
| 6129 | dc1p1_leaf3a_smd554 | Routing Table | Remote VTEP address | 9.3.1.14 | PASS | - |
| 6130 | dc1p1_leaf3b_smd555 | Routing Table | Remote VTEP address | 150.1.1.3 | PASS | - |
| 6131 | dc1p1_leaf3b_smd555 | Routing Table | Remote VTEP address | 150.1.1.4 | PASS | - |
| 6132 | dc1p1_leaf3b_smd555 | Routing Table | Remote VTEP address | 150.1.2.5 | PASS | - |
| 6133 | dc1p1_leaf3b_smd555 | Routing Table | Remote VTEP address | 150.1.2.6 | PASS | - |
| 6134 | dc1p1_leaf3b_smd555 | Routing Table | Remote VTEP address | 150.1.3.7 | PASS | - |
| 6135 | dc1p1_leaf3b_smd555 | Routing Table | Remote VTEP address | 150.1.3.8 | PASS | - |
| 6136 | dc1p1_leaf3b_smd555 | Routing Table | Remote VTEP address | 9.1.1.9 | PASS | - |
| 6137 | dc1p1_leaf3b_smd555 | Routing Table | Remote VTEP address | 3.2.1.10 | PASS | - |
| 6138 | dc1p1_leaf3b_smd555 | Routing Table | Remote VTEP address | 3.2.2.11 | PASS | - |
| 6139 | dc1p1_leaf3b_smd555 | Routing Table | Remote VTEP address | 150.3.1.12 | PASS | - |
| 6140 | dc1p1_leaf3b_smd555 | Routing Table | Remote VTEP address | 150.3.1.13 | PASS | - |
| 6141 | dc1p1_leaf3b_smd555 | Routing Table | Remote VTEP address | 9.3.1.14 | PASS | - |
| 6142 | dc1p1_sleaf_smv541 | Routing Table | Remote VTEP address | 150.1.1.3 | PASS | - |
| 6143 | dc1p1_sleaf_smv541 | Routing Table | Remote VTEP address | 150.1.1.4 | PASS | - |
| 6144 | dc1p1_sleaf_smv541 | Routing Table | Remote VTEP address | 150.1.2.5 | PASS | - |
| 6145 | dc1p1_sleaf_smv541 | Routing Table | Remote VTEP address | 150.1.2.6 | PASS | - |
| 6146 | dc1p1_sleaf_smv541 | Routing Table | Remote VTEP address | 150.1.3.7 | PASS | - |
| 6147 | dc1p1_sleaf_smv541 | Routing Table | Remote VTEP address | 150.1.3.8 | PASS | - |
| 6148 | dc1p1_sleaf_smv541 | Routing Table | Remote VTEP address | 9.1.1.9 | PASS | - |
| 6149 | dc1p1_sleaf_smv541 | Routing Table | Remote VTEP address | 3.2.1.10 | PASS | - |
| 6150 | dc1p1_sleaf_smv541 | Routing Table | Remote VTEP address | 3.2.2.11 | PASS | - |
| 6151 | dc1p1_sleaf_smv541 | Routing Table | Remote VTEP address | 150.3.1.12 | PASS | - |
| 6152 | dc1p1_sleaf_smv541 | Routing Table | Remote VTEP address | 150.3.1.13 | PASS | - |
| 6153 | dc1p1_sleaf_smv541 | Routing Table | Remote VTEP address | 9.3.1.14 | PASS | - |
| 6154 | dc1p2_leaf1_mrv453 | Routing Table | Remote VTEP address | 150.1.1.3 | PASS | - |
| 6155 | dc1p2_leaf1_mrv453 | Routing Table | Remote VTEP address | 150.1.1.4 | PASS | - |
| 6156 | dc1p2_leaf1_mrv453 | Routing Table | Remote VTEP address | 150.1.2.5 | PASS | - |
| 6157 | dc1p2_leaf1_mrv453 | Routing Table | Remote VTEP address | 150.1.2.6 | PASS | - |
| 6158 | dc1p2_leaf1_mrv453 | Routing Table | Remote VTEP address | 150.1.3.7 | PASS | - |
| 6159 | dc1p2_leaf1_mrv453 | Routing Table | Remote VTEP address | 150.1.3.8 | PASS | - |
| 6160 | dc1p2_leaf1_mrv453 | Routing Table | Remote VTEP address | 9.1.1.9 | PASS | - |
| 6161 | dc1p2_leaf1_mrv453 | Routing Table | Remote VTEP address | 3.2.1.10 | PASS | - |
| 6162 | dc1p2_leaf1_mrv453 | Routing Table | Remote VTEP address | 3.2.2.11 | PASS | - |
| 6163 | dc1p2_leaf1_mrv453 | Routing Table | Remote VTEP address | 150.3.1.12 | PASS | - |
| 6164 | dc1p2_leaf1_mrv453 | Routing Table | Remote VTEP address | 150.3.1.13 | PASS | - |
| 6165 | dc1p2_leaf1_mrv453 | Routing Table | Remote VTEP address | 9.3.1.14 | PASS | - |
| 6166 | dc1p2_leaf2_gt272 | Routing Table | Remote VTEP address | 150.1.1.3 | PASS | - |
| 6167 | dc1p2_leaf2_gt272 | Routing Table | Remote VTEP address | 150.1.1.4 | PASS | - |
| 6168 | dc1p2_leaf2_gt272 | Routing Table | Remote VTEP address | 150.1.2.5 | PASS | - |
| 6169 | dc1p2_leaf2_gt272 | Routing Table | Remote VTEP address | 150.1.2.6 | PASS | - |
| 6170 | dc1p2_leaf2_gt272 | Routing Table | Remote VTEP address | 150.1.3.7 | PASS | - |
| 6171 | dc1p2_leaf2_gt272 | Routing Table | Remote VTEP address | 150.1.3.8 | PASS | - |
| 6172 | dc1p2_leaf2_gt272 | Routing Table | Remote VTEP address | 9.1.1.9 | PASS | - |
| 6173 | dc1p2_leaf2_gt272 | Routing Table | Remote VTEP address | 3.2.1.10 | PASS | - |
| 6174 | dc1p2_leaf2_gt272 | Routing Table | Remote VTEP address | 3.2.2.11 | PASS | - |
| 6175 | dc1p2_leaf2_gt272 | Routing Table | Remote VTEP address | 150.3.1.12 | PASS | - |
| 6176 | dc1p2_leaf2_gt272 | Routing Table | Remote VTEP address | 150.3.1.13 | PASS | - |
| 6177 | dc1p2_leaf2_gt272 | Routing Table | Remote VTEP address | 9.3.1.14 | PASS | - |
| 6178 | dc2p1_leaf1a_mrv305 | Routing Table | Remote VTEP address | 150.1.1.3 | PASS | - |
| 6179 | dc2p1_leaf1a_mrv305 | Routing Table | Remote VTEP address | 150.1.1.4 | PASS | - |
| 6180 | dc2p1_leaf1a_mrv305 | Routing Table | Remote VTEP address | 150.1.2.5 | PASS | - |
| 6181 | dc2p1_leaf1a_mrv305 | Routing Table | Remote VTEP address | 150.1.2.6 | PASS | - |
| 6182 | dc2p1_leaf1a_mrv305 | Routing Table | Remote VTEP address | 150.1.3.7 | PASS | - |
| 6183 | dc2p1_leaf1a_mrv305 | Routing Table | Remote VTEP address | 150.1.3.8 | PASS | - |
| 6184 | dc2p1_leaf1a_mrv305 | Routing Table | Remote VTEP address | 9.1.1.9 | PASS | - |
| 6185 | dc2p1_leaf1a_mrv305 | Routing Table | Remote VTEP address | 3.2.1.10 | PASS | - |
| 6186 | dc2p1_leaf1a_mrv305 | Routing Table | Remote VTEP address | 3.2.2.11 | PASS | - |
| 6187 | dc2p1_leaf1a_mrv305 | Routing Table | Remote VTEP address | 150.3.1.12 | PASS | - |
| 6188 | dc2p1_leaf1a_mrv305 | Routing Table | Remote VTEP address | 150.3.1.13 | PASS | - |
| 6189 | dc2p1_leaf1a_mrv305 | Routing Table | Remote VTEP address | 9.3.1.14 | PASS | - |
| 6190 | dc2p1_leaf1b_mrv306 | Routing Table | Remote VTEP address | 150.1.1.3 | PASS | - |
| 6191 | dc2p1_leaf1b_mrv306 | Routing Table | Remote VTEP address | 150.1.1.4 | PASS | - |
| 6192 | dc2p1_leaf1b_mrv306 | Routing Table | Remote VTEP address | 150.1.2.5 | PASS | - |
| 6193 | dc2p1_leaf1b_mrv306 | Routing Table | Remote VTEP address | 150.1.2.6 | PASS | - |
| 6194 | dc2p1_leaf1b_mrv306 | Routing Table | Remote VTEP address | 150.1.3.7 | PASS | - |
| 6195 | dc2p1_leaf1b_mrv306 | Routing Table | Remote VTEP address | 150.1.3.8 | PASS | - |
| 6196 | dc2p1_leaf1b_mrv306 | Routing Table | Remote VTEP address | 9.1.1.9 | PASS | - |
| 6197 | dc2p1_leaf1b_mrv306 | Routing Table | Remote VTEP address | 3.2.1.10 | PASS | - |
| 6198 | dc2p1_leaf1b_mrv306 | Routing Table | Remote VTEP address | 3.2.2.11 | PASS | - |
| 6199 | dc2p1_leaf1b_mrv306 | Routing Table | Remote VTEP address | 150.3.1.12 | PASS | - |
| 6200 | dc2p1_leaf1b_mrv306 | Routing Table | Remote VTEP address | 150.3.1.13 | PASS | - |
| 6201 | dc2p1_leaf1b_mrv306 | Routing Table | Remote VTEP address | 9.3.1.14 | PASS | - |
| 6202 | dc2p1_sleaf_gt407 | Routing Table | Remote VTEP address | 150.1.1.3 | PASS | - |
| 6203 | dc2p1_sleaf_gt407 | Routing Table | Remote VTEP address | 150.1.1.4 | PASS | - |
| 6204 | dc2p1_sleaf_gt407 | Routing Table | Remote VTEP address | 150.1.2.5 | PASS | - |
| 6205 | dc2p1_sleaf_gt407 | Routing Table | Remote VTEP address | 150.1.2.6 | PASS | - |
| 6206 | dc2p1_sleaf_gt407 | Routing Table | Remote VTEP address | 150.1.3.7 | PASS | - |
| 6207 | dc2p1_sleaf_gt407 | Routing Table | Remote VTEP address | 150.1.3.8 | PASS | - |
| 6208 | dc2p1_sleaf_gt407 | Routing Table | Remote VTEP address | 9.1.1.9 | PASS | - |
| 6209 | dc2p1_sleaf_gt407 | Routing Table | Remote VTEP address | 3.2.1.10 | PASS | - |
| 6210 | dc2p1_sleaf_gt407 | Routing Table | Remote VTEP address | 3.2.2.11 | PASS | - |
| 6211 | dc2p1_sleaf_gt407 | Routing Table | Remote VTEP address | 150.3.1.12 | PASS | - |
| 6212 | dc2p1_sleaf_gt407 | Routing Table | Remote VTEP address | 150.3.1.13 | PASS | - |
| 6213 | dc2p1_sleaf_gt407 | Routing Table | Remote VTEP address | 9.3.1.14 | PASS | - |
| 6214 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.1.1.3 | PASS | - |
| 6215 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.1.1.4 | PASS | - |
| 6216 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.1.2.5 | PASS | - |
| 6217 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.1.2.6 | PASS | - |
| 6218 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.1.3.7 | PASS | - |
| 6219 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.1.3.8 | PASS | - |
| 6220 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.1.4.9 | PASS | - |
| 6221 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.9.1.1 | FAIL | Lo0 150.9.1.1 is not in the routing table |
| 6222 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.9.1.2 | PASS | - |
| 6223 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.9.1.3 | PASS | - |
| 6224 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.2.1.10 | PASS | - |
| 6225 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.2.2.11 | PASS | - |
| 6226 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.9.2.4 | FAIL | Lo0 150.9.2.4 is not in the routing table |
| 6227 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.9.2.5 | PASS | - |
| 6228 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.9.2.6 | PASS | - |
| 6229 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.3.1.12 | PASS | - |
| 6230 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.3.1.13 | PASS | - |
| 6231 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.3.2.14 | PASS | - |
| 6232 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.9.3.7 | FAIL | Lo0 150.9.3.7 is not in the routing table |
| 6233 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.9.3.8 | PASS | - |
| 6234 | dc1p1_leaf1a_cal418 | Routing Table | Remote Lo0 address | 150.9.3.9 | PASS | - |
| 6235 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.1.1.3 | PASS | - |
| 6236 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.1.1.4 | PASS | - |
| 6237 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.1.2.5 | PASS | - |
| 6238 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.1.2.6 | PASS | - |
| 6239 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.1.3.7 | PASS | - |
| 6240 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.1.3.8 | PASS | - |
| 6241 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.1.4.9 | PASS | - |
| 6242 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.9.1.1 | FAIL | Lo0 150.9.1.1 is not in the routing table |
| 6243 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.9.1.2 | PASS | - |
| 6244 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.9.1.3 | PASS | - |
| 6245 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.2.1.10 | PASS | - |
| 6246 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.2.2.11 | PASS | - |
| 6247 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.9.2.4 | FAIL | Lo0 150.9.2.4 is not in the routing table |
| 6248 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.9.2.5 | PASS | - |
| 6249 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.9.2.6 | PASS | - |
| 6250 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.3.1.12 | PASS | - |
| 6251 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.3.1.13 | PASS | - |
| 6252 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.3.2.14 | PASS | - |
| 6253 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.9.3.7 | FAIL | Lo0 150.9.3.7 is not in the routing table |
| 6254 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.9.3.8 | PASS | - |
| 6255 | dc1p1_leaf1b_cal419 | Routing Table | Remote Lo0 address | 150.9.3.9 | PASS | - |
| 6256 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.1.1.3 | PASS | - |
| 6257 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.1.1.4 | PASS | - |
| 6258 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.1.2.5 | PASS | - |
| 6259 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.1.2.6 | PASS | - |
| 6260 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.1.3.7 | PASS | - |
| 6261 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.1.3.8 | PASS | - |
| 6262 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.1.4.9 | PASS | - |
| 6263 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.9.1.1 | FAIL | Lo0 150.9.1.1 is not in the routing table |
| 6264 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.9.1.2 | PASS | - |
| 6265 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.9.1.3 | PASS | - |
| 6266 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.2.1.10 | PASS | - |
| 6267 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.2.2.11 | PASS | - |
| 6268 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.9.2.4 | FAIL | Lo0 150.9.2.4 is not in the routing table |
| 6269 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.9.2.5 | PASS | - |
| 6270 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.9.2.6 | PASS | - |
| 6271 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.3.1.12 | PASS | - |
| 6272 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.3.1.13 | PASS | - |
| 6273 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.3.2.14 | PASS | - |
| 6274 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.9.3.7 | FAIL | Lo0 150.9.3.7 is not in the routing table |
| 6275 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.9.3.8 | PASS | - |
| 6276 | dc1p1_leaf2a_cal421 | Routing Table | Remote Lo0 address | 150.9.3.9 | PASS | - |
| 6277 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.1.1.3 | PASS | - |
| 6278 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.1.1.4 | PASS | - |
| 6279 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.1.2.5 | PASS | - |
| 6280 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.1.2.6 | PASS | - |
| 6281 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.1.3.7 | PASS | - |
| 6282 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.1.3.8 | PASS | - |
| 6283 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.1.4.9 | PASS | - |
| 6284 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.9.1.1 | FAIL | Lo0 150.9.1.1 is not in the routing table |
| 6285 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.9.1.2 | PASS | - |
| 6286 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.9.1.3 | PASS | - |
| 6287 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.2.1.10 | PASS | - |
| 6288 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.2.2.11 | PASS | - |
| 6289 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.9.2.4 | FAIL | Lo0 150.9.2.4 is not in the routing table |
| 6290 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.9.2.5 | PASS | - |
| 6291 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.9.2.6 | PASS | - |
| 6292 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.3.1.12 | PASS | - |
| 6293 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.3.1.13 | PASS | - |
| 6294 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.3.2.14 | PASS | - |
| 6295 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.9.3.7 | FAIL | Lo0 150.9.3.7 is not in the routing table |
| 6296 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.9.3.8 | PASS | - |
| 6297 | dc1p1_leaf2b_cal422 | Routing Table | Remote Lo0 address | 150.9.3.9 | PASS | - |
| 6298 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.1.1.3 | PASS | - |
| 6299 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.1.1.4 | PASS | - |
| 6300 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.1.2.5 | PASS | - |
| 6301 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.1.2.6 | PASS | - |
| 6302 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.1.3.7 | PASS | - |
| 6303 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.1.3.8 | PASS | - |
| 6304 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.1.4.9 | PASS | - |
| 6305 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.9.1.1 | FAIL | Lo0 150.9.1.1 is not in the routing table |
| 6306 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.9.1.2 | PASS | - |
| 6307 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.9.1.3 | PASS | - |
| 6308 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.2.1.10 | PASS | - |
| 6309 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.2.2.11 | PASS | - |
| 6310 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.9.2.4 | FAIL | Lo0 150.9.2.4 is not in the routing table |
| 6311 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.9.2.5 | PASS | - |
| 6312 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.9.2.6 | PASS | - |
| 6313 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.3.1.12 | PASS | - |
| 6314 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.3.1.13 | PASS | - |
| 6315 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.3.2.14 | PASS | - |
| 6316 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.9.3.7 | FAIL | Lo0 150.9.3.7 is not in the routing table |
| 6317 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.9.3.8 | PASS | - |
| 6318 | dc1p1_leaf3a_smd554 | Routing Table | Remote Lo0 address | 150.9.3.9 | PASS | - |
| 6319 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.1.1.3 | PASS | - |
| 6320 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.1.1.4 | PASS | - |
| 6321 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.1.2.5 | PASS | - |
| 6322 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.1.2.6 | PASS | - |
| 6323 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.1.3.7 | PASS | - |
| 6324 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.1.3.8 | PASS | - |
| 6325 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.1.4.9 | PASS | - |
| 6326 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.9.1.1 | FAIL | Lo0 150.9.1.1 is not in the routing table |
| 6327 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.9.1.2 | PASS | - |
| 6328 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.9.1.3 | PASS | - |
| 6329 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.2.1.10 | PASS | - |
| 6330 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.2.2.11 | PASS | - |
| 6331 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.9.2.4 | FAIL | Lo0 150.9.2.4 is not in the routing table |
| 6332 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.9.2.5 | PASS | - |
| 6333 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.9.2.6 | PASS | - |
| 6334 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.3.1.12 | PASS | - |
| 6335 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.3.1.13 | PASS | - |
| 6336 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.3.2.14 | PASS | - |
| 6337 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.9.3.7 | FAIL | Lo0 150.9.3.7 is not in the routing table |
| 6338 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.9.3.8 | PASS | - |
| 6339 | dc1p1_leaf3b_smd555 | Routing Table | Remote Lo0 address | 150.9.3.9 | PASS | - |
| 6340 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.1.1.3 | PASS | - |
| 6341 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.1.1.4 | PASS | - |
| 6342 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.1.2.5 | PASS | - |
| 6343 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.1.2.6 | PASS | - |
| 6344 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.1.3.7 | PASS | - |
| 6345 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.1.3.8 | PASS | - |
| 6346 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.1.4.9 | PASS | - |
| 6347 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.9.1.1 | PASS | - |
| 6348 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.9.1.2 | PASS | - |
| 6349 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.9.1.3 | PASS | - |
| 6350 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.2.1.10 | PASS | - |
| 6351 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.2.2.11 | PASS | - |
| 6352 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.9.2.4 | PASS | - |
| 6353 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.9.2.5 | PASS | - |
| 6354 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.9.2.6 | PASS | - |
| 6355 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.3.1.12 | PASS | - |
| 6356 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.3.1.13 | PASS | - |
| 6357 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.3.2.14 | PASS | - |
| 6358 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.9.3.7 | PASS | - |
| 6359 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.9.3.8 | PASS | - |
| 6360 | dc1p1_sleaf_smv541 | Routing Table | Remote Lo0 address | 150.9.3.9 | PASS | - |
| 6361 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.1.1.3 | PASS | - |
| 6362 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.1.1.4 | PASS | - |
| 6363 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.1.2.5 | PASS | - |
| 6364 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.1.2.6 | PASS | - |
| 6365 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.1.3.7 | PASS | - |
| 6366 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.1.3.8 | PASS | - |
| 6367 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.1.4.9 | PASS | - |
| 6368 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.9.1.1 | PASS | - |
| 6369 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.9.1.2 | PASS | - |
| 6370 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.9.1.3 | PASS | - |
| 6371 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.2.1.10 | PASS | - |
| 6372 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.2.2.11 | PASS | - |
| 6373 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.9.2.4 | PASS | - |
| 6374 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.9.2.5 | PASS | - |
| 6375 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.9.2.6 | PASS | - |
| 6376 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.3.1.12 | PASS | - |
| 6377 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.3.1.13 | PASS | - |
| 6378 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.3.2.14 | PASS | - |
| 6379 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.9.3.7 | PASS | - |
| 6380 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.9.3.8 | PASS | - |
| 6381 | dc1p2_leaf1_mrv453 | Routing Table | Remote Lo0 address | 150.9.3.9 | PASS | - |
| 6382 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.1.1.3 | PASS | - |
| 6383 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.1.1.4 | PASS | - |
| 6384 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.1.2.5 | PASS | - |
| 6385 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.1.2.6 | PASS | - |
| 6386 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.1.3.7 | PASS | - |
| 6387 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.1.3.8 | PASS | - |
| 6388 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.1.4.9 | PASS | - |
| 6389 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.9.1.1 | PASS | - |
| 6390 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.9.1.2 | PASS | - |
| 6391 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.9.1.3 | PASS | - |
| 6392 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.2.1.10 | PASS | - |
| 6393 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.2.2.11 | PASS | - |
| 6394 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.9.2.4 | PASS | - |
| 6395 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.9.2.5 | PASS | - |
| 6396 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.9.2.6 | PASS | - |
| 6397 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.3.1.12 | PASS | - |
| 6398 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.3.1.13 | PASS | - |
| 6399 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.3.2.14 | PASS | - |
| 6400 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.9.3.7 | PASS | - |
| 6401 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.9.3.8 | PASS | - |
| 6402 | dc1p2_leaf2_gt272 | Routing Table | Remote Lo0 address | 150.9.3.9 | PASS | - |
| 6403 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.1.1.3 | PASS | - |
| 6404 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.1.1.4 | PASS | - |
| 6405 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.1.2.5 | PASS | - |
| 6406 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.1.2.6 | PASS | - |
| 6407 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.1.3.7 | PASS | - |
| 6408 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.1.3.8 | PASS | - |
| 6409 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.1.4.9 | PASS | - |
| 6410 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.9.1.1 | PASS | - |
| 6411 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.9.1.2 | PASS | - |
| 6412 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.9.1.3 | PASS | - |
| 6413 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.2.1.10 | PASS | - |
| 6414 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.2.2.11 | PASS | - |
| 6415 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.9.2.4 | PASS | - |
| 6416 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.9.2.5 | PASS | - |
| 6417 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.9.2.6 | PASS | - |
| 6418 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.3.1.12 | PASS | - |
| 6419 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.3.1.13 | PASS | - |
| 6420 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.3.2.14 | PASS | - |
| 6421 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.9.3.7 | PASS | - |
| 6422 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.9.3.8 | PASS | - |
| 6423 | dc2p1_leaf1a_mrv305 | Routing Table | Remote Lo0 address | 150.9.3.9 | PASS | - |
| 6424 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.1.1.3 | PASS | - |
| 6425 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.1.1.4 | PASS | - |
| 6426 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.1.2.5 | PASS | - |
| 6427 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.1.2.6 | PASS | - |
| 6428 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.1.3.7 | PASS | - |
| 6429 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.1.3.8 | PASS | - |
| 6430 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.1.4.9 | PASS | - |
| 6431 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.9.1.1 | PASS | - |
| 6432 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.9.1.2 | PASS | - |
| 6433 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.9.1.3 | PASS | - |
| 6434 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.2.1.10 | PASS | - |
| 6435 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.2.2.11 | PASS | - |
| 6436 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.9.2.4 | PASS | - |
| 6437 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.9.2.5 | PASS | - |
| 6438 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.9.2.6 | PASS | - |
| 6439 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.3.1.12 | PASS | - |
| 6440 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.3.1.13 | PASS | - |
| 6441 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.3.2.14 | PASS | - |
| 6442 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.9.3.7 | PASS | - |
| 6443 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.9.3.8 | PASS | - |
| 6444 | dc2p1_leaf1b_mrv306 | Routing Table | Remote Lo0 address | 150.9.3.9 | PASS | - |
| 6445 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.1.1.3 | PASS | - |
| 6446 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.1.1.4 | PASS | - |
| 6447 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.1.2.5 | PASS | - |
| 6448 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.1.2.6 | PASS | - |
| 6449 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.1.3.7 | PASS | - |
| 6450 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.1.3.8 | PASS | - |
| 6451 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.1.4.9 | PASS | - |
| 6452 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.9.1.1 | PASS | - |
| 6453 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.9.1.2 | PASS | - |
| 6454 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.9.1.3 | PASS | - |
| 6455 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.2.1.10 | PASS | - |
| 6456 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.2.2.11 | PASS | - |
| 6457 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.9.2.4 | PASS | - |
| 6458 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.9.2.5 | PASS | - |
| 6459 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.9.2.6 | PASS | - |
| 6460 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.3.1.12 | PASS | - |
| 6461 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.3.1.13 | PASS | - |
| 6462 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.3.2.14 | PASS | - |
| 6463 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.9.3.7 | PASS | - |
| 6464 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.9.3.8 | PASS | - |
| 6465 | dc2p1_sleaf_gt407 | Routing Table | Remote Lo0 address | 150.9.3.9 | PASS | - |
| 6466 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.1.1.3 | PASS | - |
| 6467 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.1.1.4 | PASS | - |
| 6468 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.1.2.5 | PASS | - |
| 6469 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.1.2.6 | PASS | - |
| 6470 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.1.3.7 | PASS | - |
| 6471 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.1.3.8 | PASS | - |
| 6472 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.1.4.9 | PASS | - |
| 6473 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.9.1.1 | FAIL | 100% packet loss |
| 6474 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.9.1.2 | PASS | - |
| 6475 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.9.1.3 | PASS | - |
| 6476 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.2.1.10 | PASS | - |
| 6477 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.2.2.11 | PASS | - |
| 6478 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.9.2.4 | FAIL | 100% packet loss |
| 6479 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.9.2.5 | PASS | - |
| 6480 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.9.2.6 | PASS | - |
| 6481 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.3.1.12 | PASS | - |
| 6482 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.3.1.13 | PASS | - |
| 6483 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.3.2.14 | PASS | - |
| 6484 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.9.3.7 | FAIL | 100% packet loss |
| 6485 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.9.3.8 | PASS | - |
| 6486 | dc1p1_leaf1a_cal418 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1a_cal418 - 150.1.1.3 Destination: 150.9.3.9 | PASS | - |
| 6487 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.1.1.3 | PASS | - |
| 6488 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.1.1.4 | PASS | - |
| 6489 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.1.2.5 | PASS | - |
| 6490 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.1.2.6 | PASS | - |
| 6491 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.1.3.7 | PASS | - |
| 6492 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.1.3.8 | PASS | - |
| 6493 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.1.4.9 | PASS | - |
| 6494 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.9.1.1 | FAIL | 100% packet loss |
| 6495 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.9.1.2 | PASS | - |
| 6496 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.9.1.3 | PASS | - |
| 6497 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.2.1.10 | PASS | - |
| 6498 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.2.2.11 | PASS | - |
| 6499 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.9.2.4 | FAIL | 100% packet loss |
| 6500 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.9.2.5 | PASS | - |
| 6501 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.9.2.6 | PASS | - |
| 6502 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.3.1.12 | PASS | - |
| 6503 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.3.1.13 | PASS | - |
| 6504 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.3.2.14 | PASS | - |
| 6505 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.9.3.7 | FAIL | 100% packet loss |
| 6506 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.9.3.8 | PASS | - |
| 6507 | dc1p1_leaf1b_cal419 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf1b_cal419 - 150.1.1.4 Destination: 150.9.3.9 | PASS | - |
| 6508 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.1.1.3 | PASS | - |
| 6509 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.1.1.4 | PASS | - |
| 6510 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.1.2.5 | PASS | - |
| 6511 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.1.2.6 | PASS | - |
| 6512 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.1.3.7 | PASS | - |
| 6513 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.1.3.8 | PASS | - |
| 6514 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.1.4.9 | PASS | - |
| 6515 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.9.1.1 | FAIL | 100% packet loss |
| 6516 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.9.1.2 | PASS | - |
| 6517 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.9.1.3 | PASS | - |
| 6518 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.2.1.10 | PASS | - |
| 6519 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.2.2.11 | PASS | - |
| 6520 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.9.2.4 | FAIL | 100% packet loss |
| 6521 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.9.2.5 | PASS | - |
| 6522 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.9.2.6 | PASS | - |
| 6523 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.3.1.12 | PASS | - |
| 6524 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.3.1.13 | PASS | - |
| 6525 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.3.2.14 | PASS | - |
| 6526 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.9.3.7 | FAIL | 100% packet loss |
| 6527 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.9.3.8 | PASS | - |
| 6528 | dc1p1_leaf2a_cal421 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2a_cal421 - 150.1.2.5 Destination: 150.9.3.9 | PASS | - |
| 6529 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.1.1.3 | PASS | - |
| 6530 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.1.1.4 | PASS | - |
| 6531 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.1.2.5 | PASS | - |
| 6532 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.1.2.6 | PASS | - |
| 6533 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.1.3.7 | PASS | - |
| 6534 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.1.3.8 | PASS | - |
| 6535 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.1.4.9 | PASS | - |
| 6536 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.9.1.1 | FAIL | 100% packet loss |
| 6537 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.9.1.2 | PASS | - |
| 6538 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.9.1.3 | PASS | - |
| 6539 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.2.1.10 | PASS | - |
| 6540 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.2.2.11 | PASS | - |
| 6541 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.9.2.4 | FAIL | 100% packet loss |
| 6542 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.9.2.5 | PASS | - |
| 6543 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.9.2.6 | PASS | - |
| 6544 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.3.1.12 | PASS | - |
| 6545 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.3.1.13 | PASS | - |
| 6546 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.3.2.14 | PASS | - |
| 6547 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.9.3.7 | FAIL | 100% packet loss |
| 6548 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.9.3.8 | PASS | - |
| 6549 | dc1p1_leaf2b_cal422 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf2b_cal422 - 150.1.2.6 Destination: 150.9.3.9 | PASS | - |
| 6550 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.1.1.3 | PASS | - |
| 6551 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.1.1.4 | PASS | - |
| 6552 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.1.2.5 | PASS | - |
| 6553 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.1.2.6 | PASS | - |
| 6554 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.1.3.7 | PASS | - |
| 6555 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.1.3.8 | PASS | - |
| 6556 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.1.4.9 | PASS | - |
| 6557 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.9.1.1 | FAIL | 100% packet loss |
| 6558 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.9.1.2 | PASS | - |
| 6559 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.9.1.3 | PASS | - |
| 6560 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.2.1.10 | PASS | - |
| 6561 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.2.2.11 | PASS | - |
| 6562 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.9.2.4 | FAIL | 100% packet loss |
| 6563 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.9.2.5 | PASS | - |
| 6564 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.9.2.6 | PASS | - |
| 6565 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.3.1.12 | PASS | - |
| 6566 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.3.1.13 | PASS | - |
| 6567 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.3.2.14 | PASS | - |
| 6568 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.9.3.7 | FAIL | 100% packet loss |
| 6569 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.9.3.8 | PASS | - |
| 6570 | dc1p1_leaf3a_smd554 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3a_smd554 - 150.1.3.7 Destination: 150.9.3.9 | PASS | - |
| 6571 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.1.1.3 | PASS | - |
| 6572 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.1.1.4 | PASS | - |
| 6573 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.1.2.5 | PASS | - |
| 6574 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.1.2.6 | PASS | - |
| 6575 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.1.3.7 | PASS | - |
| 6576 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.1.3.8 | PASS | - |
| 6577 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.1.4.9 | PASS | - |
| 6578 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.9.1.1 | FAIL | 100% packet loss |
| 6579 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.9.1.2 | PASS | - |
| 6580 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.9.1.3 | PASS | - |
| 6581 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.2.1.10 | PASS | - |
| 6582 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.2.2.11 | PASS | - |
| 6583 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.9.2.4 | FAIL | 100% packet loss |
| 6584 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.9.2.5 | PASS | - |
| 6585 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.9.2.6 | PASS | - |
| 6586 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.3.1.12 | PASS | - |
| 6587 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.3.1.13 | PASS | - |
| 6588 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.3.2.14 | PASS | - |
| 6589 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.9.3.7 | FAIL | 100% packet loss |
| 6590 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.9.3.8 | PASS | - |
| 6591 | dc1p1_leaf3b_smd555 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_leaf3b_smd555 - 150.1.3.8 Destination: 150.9.3.9 | PASS | - |
| 6592 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.1.1.3 | PASS | - |
| 6593 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.1.1.4 | PASS | - |
| 6594 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.1.2.5 | PASS | - |
| 6595 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.1.2.6 | PASS | - |
| 6596 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.1.3.7 | PASS | - |
| 6597 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.1.3.8 | PASS | - |
| 6598 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.1.4.9 | PASS | - |
| 6599 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.9.1.1 | PASS | - |
| 6600 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.9.1.2 | PASS | - |
| 6601 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.9.1.3 | PASS | - |
| 6602 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.2.1.10 | PASS | - |
| 6603 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.2.2.11 | PASS | - |
| 6604 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.9.2.4 | PASS | - |
| 6605 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.9.2.5 | PASS | - |
| 6606 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.9.2.6 | PASS | - |
| 6607 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.3.1.12 | PASS | - |
| 6608 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.3.1.13 | PASS | - |
| 6609 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.3.2.14 | PASS | - |
| 6610 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.9.3.7 | PASS | - |
| 6611 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.9.3.8 | PASS | - |
| 6612 | dc1p1_sleaf_smv541 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p1_sleaf_smv541 - 150.1.4.9 Destination: 150.9.3.9 | PASS | - |
| 6613 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.1.1.3 | PASS | - |
| 6614 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.1.1.4 | PASS | - |
| 6615 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.1.2.5 | PASS | - |
| 6616 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.1.2.6 | PASS | - |
| 6617 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.1.3.7 | PASS | - |
| 6618 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.1.3.8 | PASS | - |
| 6619 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.1.4.9 | PASS | - |
| 6620 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.9.1.1 | PASS | - |
| 6621 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.9.1.2 | PASS | - |
| 6622 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.9.1.3 | PASS | - |
| 6623 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.2.1.10 | PASS | - |
| 6624 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.2.2.11 | PASS | - |
| 6625 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.9.2.4 | PASS | - |
| 6626 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.9.2.5 | PASS | - |
| 6627 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.9.2.6 | PASS | - |
| 6628 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.3.1.12 | PASS | - |
| 6629 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.3.1.13 | PASS | - |
| 6630 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.3.2.14 | PASS | - |
| 6631 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.9.3.7 | PASS | - |
| 6632 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.9.3.8 | PASS | - |
| 6633 | dc1p2_leaf1_mrv453 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf1_mrv453 - 150.2.1.10 Destination: 150.9.3.9 | PASS | - |
| 6634 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.1.1.3 | PASS | - |
| 6635 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.1.1.4 | PASS | - |
| 6636 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.1.2.5 | PASS | - |
| 6637 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.1.2.6 | PASS | - |
| 6638 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.1.3.7 | PASS | - |
| 6639 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.1.3.8 | PASS | - |
| 6640 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.1.4.9 | PASS | - |
| 6641 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.9.1.1 | PASS | - |
| 6642 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.9.1.2 | PASS | - |
| 6643 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.9.1.3 | PASS | - |
| 6644 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.2.1.10 | PASS | - |
| 6645 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.2.2.11 | PASS | - |
| 6646 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.9.2.4 | PASS | - |
| 6647 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.9.2.5 | PASS | - |
| 6648 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.9.2.6 | PASS | - |
| 6649 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.3.1.12 | PASS | - |
| 6650 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.3.1.13 | PASS | - |
| 6651 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.3.2.14 | PASS | - |
| 6652 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.9.3.7 | PASS | - |
| 6653 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.9.3.8 | PASS | - |
| 6654 | dc1p2_leaf2_gt272 | Loopback0 Reachability | Loopback0 Reachability | Source: dc1p2_leaf2_gt272 - 150.2.2.11 Destination: 150.9.3.9 | PASS | - |
| 6655 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.1.1.3 | PASS | - |
| 6656 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.1.1.4 | PASS | - |
| 6657 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.1.2.5 | PASS | - |
| 6658 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.1.2.6 | PASS | - |
| 6659 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.1.3.7 | PASS | - |
| 6660 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.1.3.8 | PASS | - |
| 6661 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.1.4.9 | PASS | - |
| 6662 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.9.1.1 | PASS | - |
| 6663 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.9.1.2 | PASS | - |
| 6664 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.9.1.3 | PASS | - |
| 6665 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.2.1.10 | PASS | - |
| 6666 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.2.2.11 | PASS | - |
| 6667 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.9.2.4 | PASS | - |
| 6668 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.9.2.5 | PASS | - |
| 6669 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.9.2.6 | PASS | - |
| 6670 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.3.1.12 | PASS | - |
| 6671 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.3.1.13 | PASS | - |
| 6672 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.3.2.14 | PASS | - |
| 6673 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.9.3.7 | PASS | - |
| 6674 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.9.3.8 | PASS | - |
| 6675 | dc2p1_leaf1a_mrv305 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1a_mrv305 - 150.3.1.12 Destination: 150.9.3.9 | PASS | - |
| 6676 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.1.1.3 | PASS | - |
| 6677 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.1.1.4 | PASS | - |
| 6678 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.1.2.5 | PASS | - |
| 6679 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.1.2.6 | PASS | - |
| 6680 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.1.3.7 | PASS | - |
| 6681 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.1.3.8 | PASS | - |
| 6682 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.1.4.9 | PASS | - |
| 6683 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.9.1.1 | PASS | - |
| 6684 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.9.1.2 | PASS | - |
| 6685 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.9.1.3 | PASS | - |
| 6686 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.2.1.10 | PASS | - |
| 6687 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.2.2.11 | PASS | - |
| 6688 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.9.2.4 | PASS | - |
| 6689 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.9.2.5 | PASS | - |
| 6690 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.9.2.6 | PASS | - |
| 6691 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.3.1.12 | PASS | - |
| 6692 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.3.1.13 | PASS | - |
| 6693 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.3.2.14 | PASS | - |
| 6694 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.9.3.7 | PASS | - |
| 6695 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.9.3.8 | PASS | - |
| 6696 | dc2p1_leaf1b_mrv306 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_leaf1b_mrv306 - 150.3.1.13 Destination: 150.9.3.9 | PASS | - |
| 6697 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.1.1.3 | PASS | - |
| 6698 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.1.1.4 | PASS | - |
| 6699 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.1.2.5 | PASS | - |
| 6700 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.1.2.6 | PASS | - |
| 6701 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.1.3.7 | PASS | - |
| 6702 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.1.3.8 | PASS | - |
| 6703 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.1.4.9 | PASS | - |
| 6704 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.9.1.1 | PASS | - |
| 6705 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.9.1.2 | PASS | - |
| 6706 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.9.1.3 | PASS | - |
| 6707 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.2.1.10 | PASS | - |
| 6708 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.2.2.11 | PASS | - |
| 6709 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.9.2.4 | PASS | - |
| 6710 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.9.2.5 | PASS | - |
| 6711 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.9.2.6 | PASS | - |
| 6712 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.3.1.12 | PASS | - |
| 6713 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.3.1.13 | PASS | - |
| 6714 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.3.2.14 | PASS | - |
| 6715 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.9.3.7 | PASS | - |
| 6716 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.9.3.8 | PASS | - |
| 6717 | dc2p1_sleaf_gt407 | Loopback0 Reachability | Loopback0 Reachability | Source: dc2p1_sleaf_gt407 - 150.3.2.14 Destination: 150.9.3.9 | PASS | - |
