# InfraNeuro HDD Check — Releases

Official builds of **InfraNeuro HDD Check**, a disk health and management tool for Windows and Linux
(SMART health, surface scan, RAID & surveillance suitability, performance test, disk editor, partition tools).

➡️ **[Download the latest release](../../releases/latest)**

| File | System |
|---|---|
| `InfraNeuro-HDDCheck-windows-amd64.exe` | Windows 10 / 11 (x64) — run as administrator |
| `InfraNeuro-HDDCheck-linux-amd64` | Linux x64 — needs GTK3 + WebKitGTK; run as root |
| `SHA256SUMS.txt` | SHA-256 checksums of the files above |

The app checks this repository for updates (menu **Updates**) and verifies every download
against `SHA256SUMS.txt` before installing it.

### Verify a download yourself
Windows (PowerShell):
```powershell
Get-FileHash .\InfraNeuro-HDDCheck-windows-amd64.exe -Algorithm SHA256
```
Linux:
```bash
sha256sum -c SHA256SUMS.txt --ignore-missing
```

© InfraNeuro
