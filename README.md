# BVLOS Dashboard - installers

Published installers for the **Airborne Robotics Flight Monitor** desktop app (Windows NSIS + Linux
AppImage/deb) plus the `electron-updater` metadata that installed apps read to self-update.

Grab the latest build from the [Releases](../../releases) page. Installed apps also check here on launch
and every 4h and apply updates on operator click (never forced).

Built automatically from the private `BVLOS_Dashboard` repo by pushing a `v*` tag; this repo holds only the
release artifacts, no source. The Ground Comms Android APK releases separately in `ground-comms-releases`.
