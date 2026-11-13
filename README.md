# WNARaven Windows downloads

This repository hosts public release downloads and update metadata for WNARaven.
The application source is maintained separately in a private repository.

## Download

Version 1.2.4 adds optional per-character Idle farming teams (default off), a
default-on Demon entry check just after daily reset, and a rebuilt searchable
Guide with contextual help beside actions and settings. Farming teams never move
you to follow teammates. Unknown operation replies retain existing safeguards.
Live team admission and midnight-entry feedback is welcome; include Copy status.

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
need one manual installation of version 0.6.0 or later first. Version 1.2.4 is available through the in-app updater for users on 0.6.0 or later.

Release assets contain the Windows bundle and `update.json`; this repository does
not require or distribute GitHub credentials or WNARaven account data.
