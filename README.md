# project-03-vlan-dhcp-dns-enterprise-network
Enterprise multi-VLAN network with centralized DHCP and DNS using DHCP relay
# Scenario
A small enterprise with HR, IT, and Finance departments requires automatic IP addressing and internal name resolution across segmented VLANs.
# Network Design
- VLAN 10 – HR (192.168.10.0/24)
- VLAN 20 – IT (192.168.20.0/24)
- VLAN 30 – Finance (192.168.30.0/24)
- Router-on-a-Stick for inter-VLAN routing
- Centralized DHCP and DNS hosted in IT VLAN
# Technologies Used
- VLANs and 802.1Q trunking
- Inter-VLAN routing
- DHCP with ip helper-address
- DNS name resolution
- IPv4 addressing
# Verification
- PCs receive correct IP configuration via DHCP
- Successful inter-VLAN communication
- Hostname resolution verified using DNS
# Key Learning Outcomes
- Configuring DHCP relay across VLANs
- Troubleshooting incorrect DHCP gateway assignments
- Understanding broadcast vs routed traffic
