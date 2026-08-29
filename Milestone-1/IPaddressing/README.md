
4. IP Addressing Plan – Summary
The network uses the 10.12.0.0/16 address block, divided into /24 subnets, with each subnet providing 254 usable host addresses.
Separate VLANs are assigned to each department/function to improve network organisation and traffic segmentation:

VLAN 10: Administration – 10.12.10.0/24
VLAN 20: Doctors – 10.12.20.0/24
VLAN 30: Reception – 10.12.30.0/24
VLAN 40: Records – 10.12.40.0/24
VLAN 50: CCTV – 10.12.50.0/24
VLAN 99: Management – 10.12.99.0/24
Each VLAN uses .1 as its default gateway and a subnet mask of 255.255.255.0.
The four CCTV cameras are placed on the dedicated CCTV VLAN 50, using IP addresses 10.12.50.10–10.12.50.13. This dedicated subnet ensures that CCTV traffic is properly separated from other network departments, meeting the required traffic segmentation for CR7.
