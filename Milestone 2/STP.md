# Milestone 2 – STP: Loop Prevention and Root Design

**Client:** Naledi Specialist Physicians  
**Client ID:** CLI-006  
**Project Code:** CMPG325-2026-006

## Introduction

Spanning Tree Protocol (STP) was used to prevent Layer 2 switching loops caused by redundant connections between switches.

## Implementation

The network contains a Core Switch and two Access Switches connected using redundant links. STP manages these links to prevent switching loops.

One path can forward traffic while a redundant path is placed in a blocking state.

## Verification

The following command was used to inspect STP operation:

`show spanning-tree`

The output was checked to identify forwarding and blocking ports.

## Result

STP provides loop prevention while allowing redundant connections to remain available as alternative paths.
