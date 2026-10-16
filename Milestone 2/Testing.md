# Milestone 2 – Testing and Verification

**Client:** Naledi Specialist Physicians  
**Client ID:** CLI-006  
**Project Code:** CMPG325-2026-006

## Connectivity Testing

Connectivity was tested between devices in the Reception and Records VLANs.

- **VLAN 30 – Reception:** 4 packets received, 0% packet loss.
- **VLAN 40 – Records:** 4 packets received, 0% packet loss.

## Switch Verification

The following commands were used to verify the network:

- `show vlan brief` – to check VLAN assignments.
- `show spanning-tree` – to check STP operation.
- `show cdp neighbors` – to identify connected network devices.
- `show vlan id 50` – to verify the CCTV VLAN ports.

## Router Verification

The router's GigabitEthernet0/0 interface was checked and confirmed to be up/up.

## Result

The tests confirmed connectivity between the tested devices and helped verify the VLAN configuration, switch connections and STP operation.
