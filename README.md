# WNARaven Windows downloads

This repository hosts public release downloads and update metadata for WNARaven.
The application source is maintained separately in a private repository.

## Download

Version 1.6.3 moves **Star Domain** out of Beta and gives **Run Once** a
full-width section above Info. The Star Domain settings show each Lord's debuff,
availability, and respawn countdown. The leader can opt to exit and skip a
boss when another party is detected after entry.

Open [Releases](https://github.com/NostawMul/WNARaven-Releases/releases) and download
the `WNARaven-…-windows-x64.zip` asset. Extract the complete ZIP into its own folder
and run `WNARaven.exe`. Keep the DLLs and `data` folder together with the executable.
No GitHub account is required. [Latest release](https://github.com/NostawMul/WNARaven-Releases/releases/latest)
includes the Windows ZIP, full changelog, SHA-256 checksum and updater metadata.

## In-app updates

Updater-enabled builds check once a day while open. Use **Extra → Check for
updates** to check sooner. When a newer version is found, the label changes to
**Update WNARaven** with an indicator. The app downloads and verifies the full
Windows bundle, then offers a restart to install it. **Prompt to restart after
future updates** shows a confirmation when a verified update is ready. Choose
**Later** to keep sessions running. To downgrade, select a dated release under
**Roll back to a previous version**, verify the download, then confirm the restart.

Saved accounts, settings and Gallery plans stay in the separate application data
directory. Normal Auto launch settings apply after restart. Existing older builds
need one manual installation of version 0.6.0 or later first. Version 1.6.3 is available through the in-app updater for users on 0.6.0 or later.

Release assets contain the Windows bundle and `update.json`; this repository does
not require or distribute GitHub credentials or WNARaven account data.
