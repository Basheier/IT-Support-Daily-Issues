# Gateway Unreachable Issue

## Problem
Device cannot reach the network gateway (e.g., 192.168.1.1), causing loss of internet or LAN access.

## Possible Causes
- Wrong IP configuration.
- Faulty switch port.
- Router not responding.
- Network adapter issue.
- VLAN misconfiguration.
- Firewall blocking ICMP.

## Solution
1. Test gateway reachability:
   - ping 192.168.1.1

2. Check IP configuration:
   - ipconfig
   - Ensure correct IP, subnet, and gateway

3. Reset network adapter:
   - Disable → Enable adapter

4. Try another switch port or cable.

5. Restart router or switch.

6. Clear ARP cache:
   - arp -d *

7. Check VLAN settings (if applicable).

8. Temporarily disable firewall to test ICMP.
