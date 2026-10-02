# CMPG325 Milestone 2 – Client Implementation Review

## Client Information

**Client:** Naledi Specialist Physicians  
**Client ID:** CLI-006  
**Project Code:** CMPG325-2026-006

## Milestone 2 Implementation

The network designed for Naledi Specialist Physicians was implemented in Cisco Packet Tracer using a Cisco 2911 router, one Cisco 3560-24PS Core Switch and two Cisco 2960 Access Switches.

The network includes separate VLANs for the different departments and services:

- VLAN 10 – Administration
- VLAN 20 – Doctors
- VLAN 30 – Reception
- VLAN 40 – Records
- VLAN 50 – CCTV
- VLAN 99 – Management

## Assigned Feature: STP – Loop Prevention and Root Design

Spanning Tree Protocol (STP) was implemented to prevent Layer 2 switching loops caused by the redundant connections between the switches.

STP was verified using the `show spanning-tree` command. The redundant path was controlled by STP, with one path forwarding and the alternate path placed into a blocking state.

## CCTV Implementation

Four CCTV cameras were included in the network and assigned to the dedicated CCTV VLAN.

The CCTV ports were verified using:

`show vlan id 50`

The verification confirmed that the CCTV ports are assigned to VLAN 50.

## Testing

Connectivity was tested between devices in the Reception VLAN and Records VLAN.

**Reception VLAN 30:** 4 packets received, 0% packet loss.

**Records VLAN 40:** 4 packets received, 0% packet loss.

The Core Switch was also verified using `show cdp neighbors`, which identified Access-Switch-A, Access-Switch-B and Router R1.

The router interface GigabitEthernet0/0 was verified as **up/up**.

## Result

The Milestone 2 network implementation was completed and tested in Cisco Packet Tracer. The implementation includes VLAN segmentation, trunk links, redundant switch connections, STP loop prevention and a dedicated CCTV VLAN.
