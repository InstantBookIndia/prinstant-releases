# Prinstant Releases

Official release builds of the Prinstant apps. This repository contains **only signed installers and update
manifests**; the source code is private.

## Download

**Prinstant Desktop (Windows):**
[Download the latest version](https://github.com/InstantBookIndia/prinstant-releases/releases/download/desktop-prod-channel/Prinstant-Desktop-Setup.exe)

**PRINSTANT Kiosk (Ubuntu 26.04):**
[Download the latest version](https://github.com/InstantBookIndia/prinstant-releases/releases/download/kiosk-prod-channel/Prinstant-Kiosk-Setup.deb)

## How updates work

Installed apps check this repository for updates: the desktop app when it opens, kiosks at night (12 AM and 6 AM).
Every installer is signed, and the app verifies the signature before installing, so an unsigned or modified file is
never installed.

| Release | Purpose |
|---|---|
| `desktop-vX.Y.Z` | A desktop app version (pre-releases are test builds) |
| `desktop-prod-channel` | What shop PCs update to. Do not delete. |
| `desktop-dev-channel` | What test PCs update to. Do not delete. |
| `kiosk-vX.Y.Z` | A kiosk app version (pre-releases are test builds) |
| `kiosk-prod-channel` | What shop kiosks update to. Do not delete. |
| `kiosk-dev-channel` | What test kiosks update to. Do not delete. |

## Notes

- Releases are published automatically by CI. Do not upload or edit files here by hand.
- Support: contact Prinstant support.
