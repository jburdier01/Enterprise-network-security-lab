# Configuration Notes

This document records the major configuration steps performed during Project 1.

## Cisco Catalyst Switch

Configured VLANs:

- VLAN10 – Management
- VLAN20 – Users
- VLAN30 – Servers
- VLAN40 – Security Lab
- VLAN50 – DMZ

Configured trunk:

Switch Port: Te2/0/24  
Connected Device: FortiGate Firewall  
Encapsulation: 802.1Q

Allowed VLANs:

10,20,30,40,50

## FortiGate Firewall

Configured VLAN interfaces:

VLAN10 – 10.10.10.1  
VLAN20 – 10.20.20.1  
VLAN30 – 10.30.30.1  

Firewall performs inter-VLAN routing.

Management access enabled via:

- HTTPS
- SSH
- Ping
