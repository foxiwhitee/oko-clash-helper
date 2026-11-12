# oko-clash-helper

Unofficial helper app for Clash of Clans — a timer/upgrade manager with background notifications.

**This is NOT an official Supercell product.** It is an independent, free, open-source helper tool. Clash of Clans and Supercell are trademarks of Supercell Oy. This project is not affiliated with, endorsed by, or sponsored by Supercell.

## What this repo hosts
- `version.json` — version manifest used by the app's auto-update.
- Release APKs — installable Android builds.

## Auto-update
The oko app checks `<base>/version.json` on startup. If `versionCode` is newer, it offers to download and install the APK from `apkUrl`.

## Privacy
No user data is collected. The app runs locally on the device. Clash API tokens are stored only on the device.
