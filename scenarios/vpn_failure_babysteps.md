# Scenario: VPN Connection Failure — Baby Steps

**Symptom:** User can't connect to corporate VPN from home.

## Guided steps
1. **Identify**  
   - Action: Ask user "Can you open https://www.google.com?"  
   - Click: User opens browser and tests URL.  
   - Why: Confirms base internet works.

2. **Collect error**  
   - Action: Ask user to open VPN client and attempt connect. Copy exact error text and paste into chat/ticket.
   - Why: The exact message guides the troubleshooting path.

3. **Quick tests**  
   - Action: Ask user to click Start → type cmd → Enter → type `ping vpn.company.com` → Enter.  
   - What to expect: Replies or timeouts.

4. **Credential check**  
   - Action: Instruct user to re-enter username/password slowly (click username field → highlight → type) and try other known-good account if available.

5. **Recreate VPN profile**
   - Action: Click VPN client → settings → delete profile → add new profile (enter server address, username).
   - Why: Removes corrupt configs.

6. **Verify**
   - Action: Once connected, ask user to open a company resource (SharePoint, intranet).
   - Why: Confirms functional access.

7. **Document & prevent**
   - Action: Write final ticket notes and email short steps to user.
