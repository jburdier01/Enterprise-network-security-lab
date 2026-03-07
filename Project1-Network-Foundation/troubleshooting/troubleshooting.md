# Troubleshooting Notes

## Issue: FortiGate GUI unreachable

Cause:
Laptop received APIPA address.

Resolution:
Assigned correct static IP address.

---

## Issue: VLAN interface not created

Cause:
Missing VDOM parameter in FortiGate interface configuration.

Resolution:
Added:

set vdom root
