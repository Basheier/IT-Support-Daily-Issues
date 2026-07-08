# Network Reset Issue

## Problem
Device cannot connect to the network or shows "No Internet".

## Possible Causes
- Corrupted network adapter settings.
- Wrong IP configuration.
- DNS server not responding.
- Router or switch issue.

## Solution
1. Run the following command in CMD (Admin):
   - ipconfig /release
   - ipconfig /renew
   - ipconfig /flushdns

2. Reset network adapter:
   - Settings → Network & Internet → Advanced network settings → Network reset

3. Restart router or switch.

4. Test connection using:
   - ping 8.8.8.8
   - ping gateway IP

