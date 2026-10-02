Project Overview

This repository contains the network design and implementation plan for Naledi Specialist Physicians, a healthcare organisation based in Rustenburg, South Africa. The network is designed and simulated using Cisco Packet Tracer to provide reliable connectivity, security, VLAN segmentation, and Spanning Tree Protocol (STP) implementation.
## Milestone 2 – Client Implementation Review

Milestone 2 focuses on the implementation and testing of the Naledi Specialist Physicians network in Cisco Packet Tracer.

The implementation includes:

- VLAN segmentation for Administration, Doctors, Reception, Records, CCTV and Management
- Trunk links between switches
- Spanning Tree Protocol (STP) for loop prevention
- Redundant switch connections
- Dedicated CCTV VLAN (VLAN 50)
- Connectivity testing for Reception and Records
- Router and switch connectivity verification

The STP implementation was verified using Cisco IOS commands, including `show spanning-tree`. Connectivity and device discovery were also tested using ping and `show cdp neighbors`.

See **Milestone-2.md** for the detailed Milestone 2 implementation and testing documentation.
