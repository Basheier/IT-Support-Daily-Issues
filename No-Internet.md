# No Internet Issue

## Problem
Device is connected to the network but cannot access the internet.

## Possible Causes
- DNS server not responding.
- Gateway unreachable.
- ISP outage.
- Firewall blocking connection.
- Wrong IP configuration.

## Solution
1. Test connectivity:
   - ping 8.8.8.8
   - ping gateway IP (usually 192.168.1.1)

2. Change DNS:
   - Google DNS: 8.8.8.8 / 8.8.4.4
   - Cloudflare DNS: 1.1.1.1

3. Reset network settings:
   - ipconfig /flushdns
   - ipconfig /renew

4. Check firewall:
   - Temporarily disable firewall to test

5. Restart router or modem.

6. Contact ISP if issue persists.
