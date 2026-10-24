# Melek Keuangan — Update Feed

This repository hosts **only** signed Android APK builds and the
`update.json` manifest consumed by the in-app updater.

The application source code is private.

## Endpoints

- Latest manifest: `https://github.com/jerremi/melek-keuangan-updates/releases/latest/download/update.json`
- Releases: `https://github.com/jerremi/melek-keuangan-updates/releases`

Every APK is signed with the stable Melek Keuangan release key and is
verified by the installed app (SHA-256 + signing certificate) before
Android shows its installer.
