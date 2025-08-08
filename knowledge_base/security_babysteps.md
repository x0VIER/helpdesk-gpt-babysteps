# Security — Baby Steps

## Multi-Factor Authentication (MFA)
- **Action:** Ask user to open Authenticator app (Google Authenticator, Microsoft Authenticator).
- **Why:** MFA reduces risk of stolen passwords.

## Malware cleanup (Windows)
1. Click Start → Settings → Update & Security → Windows Security → Virus & threat protection → Quick scan.
2. If threat found, follow quarantine or full scan instructions.
- *Why:* Removes known malware signatures.

## Password reset (Active Directory on Admin workstation)
1. Open 'Active Directory Users and Computers' → find user → Right-click → Reset Password.
2. Check "User must change password at next logon" if required.
- *Why:* Enforces new credentials and prevents reuse.
