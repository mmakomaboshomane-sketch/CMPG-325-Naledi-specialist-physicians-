# Milestone 2 – Network Topologies

**Client:** Naledi Specialist Physicians  
**Client ID:** CLI-006  
**Project Code:** CMPG325-2026-006

## Physical Topology

The network was implemented in Cisco Packet Tracer using one Cisco 2911 router, one Cisco 3560-24PS Core Switch and two Cisco 2960 Access Switches.

## Logical Topology

The network uses separate VLANs for Administration, Doctors, Reception, Records, CCTV and Management.

The core switch connects to the router and access switches. Redundant links between the switches provide alternative paths.

## Spanning Tree Protocol

STP was used to prevent Layer 2 switching loops caused by redundant switch connections. The configuration was checked using the `show spanning-tree` command.
