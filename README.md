# OpenTorrent Android releases

This repository hosts signed APK releases and the wireless update feed. It does not contain private app data or signing keys.

Install the latest APK over your existing OpenTorrent installation. Do not uninstall; your downloads and settings stay. OpenTorrent 0.4.1 and later include automatic update checks, notifications and an in-app installer. Android asks you to approve installation and allow OpenTorrent to install updates once.

Checks run when the app opens and periodically in the background, subject to Android battery scheduling. This provides wireless update delivery, not immediate push or forced silent installs.

The app verifies HTTPS, SHA-256, the package name, a newer version code and the existing signing certificate. Releases contain an APK and latest.json. Future builds are staged as drafts, then published after validation.
