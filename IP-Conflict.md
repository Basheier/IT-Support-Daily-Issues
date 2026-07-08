# IP Conflict Issue

## Problem
Device shows "IP address conflict" or loses network connection.

## Possible Causes
- Two devices using the same IP.
- Static IP assigned incorrectly.
- DHCP server not assigning new IPs.
- Router or switch cache issue.

## Solution
1. Release and renew IP:
   - ipconfig /release
   - ipconfig /renew

2. Set IP to automatic:
   - Network Adapter → Properties → IPv4 → Obtain IP automatically

3. Restart DHCP service:
   - services.msc → DHCP Client → Restart

4. Restart router or switch to clear IP cache.

5. Assign a unique static IP if required:
   - Example: 192.168.1.50 → change to 192.168.1.60
