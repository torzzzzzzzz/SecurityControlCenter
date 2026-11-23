# Security Control Center — Downloads

Installer downloads for **Security Control Center**, a Windows 11 security dashboard with a safe, fully reversible Gaming Mode.

## Download

**[⬇ SecurityControlCenter-Setup-2.0.0.exe](https://github.com/torzzzzzzzz/SecurityControlCenter/raw/main/SecurityControlCenter-Setup-2.0.0.exe)** — Windows 11 installer (428 KB)

Direct link: `https://github.com/torzzzzzzzz/SecurityControlCenter/raw/main/SecurityControlCenter-Setup-2.0.0.exe`

## Install

1. Run `SecurityControlCenter-Setup-2.0.0.exe`.
2. The installer is not code-signed, so Windows may show **"Windows protected your PC"**. Click **More info → Run anyway**.
3. Approve the administrator prompt (installing to Program Files needs it), then open **Security Control Center** from the Start menu.

Requires Windows 11 (x64 or ARM64). Uses the .NET Framework 4.8 built into Windows 11.

## Verify the download (optional)

```powershell
Get-FileHash .\SecurityControlCenter-Setup-2.0.0.exe -Algorithm SHA256
```

Expected SHA-256: `98ba6b28e449e3c7e4029945a4073a31c3392a768bfe669e76ebfdc31b63681e`

## Note

Version 2.0.0 has been tested with automated tests on Linux and under Wine, but not yet on a real Windows 11 PC.
