# Troubleshooting Notes

Problems encountered during lab build and how they were resolved.

## Issue: FortiGate GUI Not Accessible

Cause:
Laptop received APIPA address due to DHCP failure.

Resolution:
Configured static IPv4 address in the correct subnet.

---

## Issue: VLAN Interface Not Created

Cause:
FortiGate required the VDOM attribute during interface creation.

Resolution:
Added:

set vdom root

during VLAN interface configuration.

---

## Issue: Trunk Not Passing Traffic

Cause:
Ethernet cable connected to incorrect FortiGate port.

Resolution:
Moved trunk cable to internal2 interface.
