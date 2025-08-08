# Scenario: Account Lockout — Baby Steps

**Symptom:** User reports "Account locked" when logging in.

1. Verify identity: Ask three pieces of user info per company policy.
2. On admin workstation: Open Active Directory Users and Computers → find user → Right-click → Properties → Account tab → Uncheck "Account is locked out".
3. Reset password if required and advise user to change on first login.
4. Check security logs for failed attempts and source IP.
5. Document findings and recommend MFA if not enabled.
