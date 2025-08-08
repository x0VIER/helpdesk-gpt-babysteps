# Operating Systems — Baby Steps

## Windows (common tasks)
- **Reset network adapter**
  1. Click Start → type "Network reset" → Enter.
  2. Click "Network reset" → Click "Reset now" → Confirm.
  - *Why:* Rebuilds all network adapters; good for stubborn connectivity issues.
  - *Look for:* Reboot required message; test connectivity after restart.

- **Run SFC (System File Checker)**
  1. Click Start → type cmd → Right click → Run as administrator.
  2. In the black window type `sfc /scannow` → Enter.
  - *Why:* Detects and repairs corrupted Windows system files.
  - *Look for:* "Windows Resource Protection found corrupt files" message.

## macOS basics
- **Reset PRAM/NVRAM**
  - Action and why explained with click-by-click for relevant Mac models.

## Linux basics
- **Check disk usage**
  - Action: Open terminal, run `df -h`
  - Why: Identifies full disks that can cause system problems.
