# WNARaven Windows downloads

This repository hosts public release downloads and update metadata for WNARaven.
The application source is maintained separately in a private repository.

## Download

Version 1.5.3 fixes **false reconnect restarts during Refining or other crowded
game screens**. Recent server packets and current engine ticks preserve active
gameplay when a bounded UI scan is incomplete. Copy reconnect status now includes
scan limits and the evidence behind the last automatic restart. **Reset Demon
attempts** target 15, 25, 45, 55, 65 and 75 seconds after midnight, stopping on
confirmed entry and allowing farming between confirmed refusals. Phone-login
waits, real failure recovery and normal-wave limits remain. Native overnight and
reset feedback are welcome. Ghost mode and existing features remain available.

Open [Releases](https://github.com/NostawMul/WNARaven-Releases/releases) and download
the `WNARaven-…-windows-x64.zip` asset. Extract the complete ZIP into its own folder
and run `WNARaven.exe`. Keep the DLLs and `data` folder together with the executable.
No GitHub account is required. [Latest release](https://github.com/NostawMul/WNARaven-Releases/releases/latest)
includes the Windows ZIP, full changelog, SHA-256 checksum and updater metadata.

## In-app updates

Updater-enabled builds check once a day while open. Use **Extra → Check for
updates** to check sooner. When a newer version is found, the label changes to
**Update WNARaven** with an indicator. The app downloads and verifies the full
Windows bundle, then offers a restart to install it. The saved automatic-restart
option applies to future updates and closes active game sessions before updating.

Saved accounts, settings and Gallery plans stay in the separate application data
directory. Normal Auto launch settings apply after restart. Existing older builds
need one manual installation of version 0.6.0 or later first. Version 1.5.3 is available through the in-app updater for users on 0.6.0 or later.

Release assets contain the Windows bundle and `update.json`; this repository does
not require or distribute GitHub credentials or WNARaven account data.
