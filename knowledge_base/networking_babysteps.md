# Networking — Baby Steps

## Check IP configuration (Windows)
1. Click Start → type `cmd` → Enter.
2. Type `ipconfig /all` → Enter.
- *Why:* Shows current IP address, gateway, DNS servers.
- *Look for:* APIPA address (169.254.x.x) indicates DHCP failure.

## Ping test
1. In the same Command Prompt type `ping 8.8.8.8` → Enter.
- *Why:* Tests raw IP connectivity independent of DNS.
- *Look for:* Packets lost or successful replies.

## DNS test
1. `nslookup www.google.com` → Enter.
- *Why:* Verifies DNS resolution.
- *Look for:* Server address and returned IP.

## Wi-Fi troubleshooting (Windows)
1. Click Wi-Fi icon in taskbar → Click "Network & Internet settings" → Click "Network troubleshooter".
- *Why:* Windows automated troubleshooting can auto-fix adapter and profile issues.
