# Project 1 – Network Foundation

## Objective
Build a segmented enterprise-style cybersecurity lab using real networking hardware.

## Hardware Used

- Cisco Catalyst 9300 Switch
- FortiGate 60E Firewall
- Dell PowerEdge R630 Server
- Verizon ONT Router

## Network Architecture

Internet
   │
Verizon Router / ONT
   │
FortiGate Firewall
   │
802.1Q Trunk
   │
Cisco Catalyst Switch
   │
Lab VLANs

## VLAN Design

VLAN 10 – Management  
VLAN 20 – User Network  
VLAN 30 – Server Network  
VLAN 40 – Security Lab  
VLAN 50 – DMZ  

## Skills Demonstrated

- VLAN segmentation
- 802.1Q trunk configuration
- Cisco IOS CLI administration
- FortiGate firewall routing
- Network troubleshooting
- Secure management network design
