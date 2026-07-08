# DNS Errors Issue

## Problem
Device has internet connection but websites do not load or show DNS-related errors.

## Possible Causes
- DNS server not responding.
- Corrupted DNS cache.
- Wrong DNS configuration.
- ISP DNS outage.
- Firewall blocking DNS requests.

## Solution
1. Flush DNS cache:
   - ipconfig /flushdns

2. Change DNS server:
   - Google DNS: 8.8.8.8 / 8.8.4.4
   - Cloudflare DNS: 1.1.1.1

3. Reset network adapter:
   - ipconfig /release
   - ipconfig /renew

4. Check firewall:
   - Temporarily disable firewall to test

5. Test DNS resolution:
   - nslookup google.com

6. Restart router or modem.
