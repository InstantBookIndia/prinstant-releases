# Prinstant Releases

Official release builds of the Prinstant apps. This repository contains **only signed installers and update
manifests**; the source code is private.

## Download

**Prinstant Desktop (Windows):**
[Download the latest version](https://github.com/InstantBookIndia/prinstant-releases/releases/download/desktop-prod-channel/Prinstant-Desktop-Setup.exe)

## How updates work

Installed apps check this repository for updates when they open. Every installer is signed, and the app verifies the
signature before installing, so an unsigned or modified file is never installed.

| Release | Purpose |
|---|---|
| `desktop-vX.Y.Z` | A desktop app version (pre-releases are test builds) |
| `desktop-prod-channel` | What shop PCs update to. Do not delete. |
| `desktop-dev-channel` | What test PCs update to. Do not delete. |

## Notes

- Releases are published automatically by CI. Do not upload or edit files here by hand.
- Support: contact Prinstant support.
