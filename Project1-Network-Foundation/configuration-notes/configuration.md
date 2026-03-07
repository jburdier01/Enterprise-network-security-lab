# Configuration Notes

## Cisco Catalyst 9300

Configured VLANs:

- VLAN10 – Management
- VLAN20 – Users
- VLAN30 – Servers
- VLAN40 – Security Lab
- VLAN50 – DMZ

Configured trunk port:

Switch Port: Te2/0/24  
Encapsulation: 802.1Q  
Allowed VLANs: 10,20,30,40,50

## FortiGate 60E

Configured VLAN interfaces:

VLAN10 – 10.10.10.1  
VLAN20 – 10.20.20.1  
VLAN30 – 10.30.30.1  

Firewall handles inter-VLAN routing.
