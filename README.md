# CitRunner

> This application is built by AI. I made this for myself and I'm uploading it to GitHub for backup and to share in case anyone can get any use out of it. It's pretty specific to my setup and my needs, but if you can get any use out of it, then enjoy.
>
> Use at your own risk. I offer no warranty or guarantees for this software.

## Download

**Latest version: v1.2** (Oct 8, 2026)

- [CitRunner_v1.2_no-install.zip](https://github.com/codenomics/CitRunner/releases/download/v1.2/CitRunner_v1.2_no-install.zip) - 71 KB
- [CitRunner_v1.2_Setup.exe](https://github.com/codenomics/CitRunner/releases/download/v1.2/CitRunner_v1.2_Setup.exe) - 151 KB
- [CitRunner_v1.2_source.zip](https://github.com/codenomics/CitRunner/releases/download/v1.2/CitRunner_v1.2_source.zip) - 61 KB

What's new in v1.2:

- updater versioning fix**

Older versions are on the [Releases page](https://github.com/codenomics/CitRunner/releases).

## Getting started

### Installer (recommended)

1. Download the file ending in `_Setup.exe` above.
2. Double-click it and click Install. It installs just for you - no admin password needed - and adds Start menu and Desktop shortcuts.
3. To remove it later: Windows Settings > Apps, find CitRunner and click Uninstall.

### No install (portable zip)

1. Download the file ending in `_no-install.zip` above.
2. Right-click it > Extract All, and pick a folder. Don't run it from inside the zip.
3. Open the folder and double-click the app's .exe. Nothing is installed; delete the folder to remove it.

Windows says "Windows protected your PC"? Click More info > Run anyway. It shows that for apps without a paid signing certificate.

## Source code

Want to see how it works, or build it yourself? Download the file ending in `_source.zip` above, extract it and double-click `Build.bat`. It only uses the C# compiler that already comes with Windows, so there is nothing to install.

## More details

```
CITRUNNER
=========

Looks up a Star Citizen player by their handle and shows their public RSI
profile: avatar, citizen record number, enlisted date, location, fluency,
badge, organizations (with their rank) and bio. Keeps a list of your recent lookups.


GETTING STARTED
---------------
Pick one. Both give you the same app.

OPTION 1 - INSTALLER (recommended)
  Download the file ending in _Setup.exe, double-click it and click Install.
  It installs just for you (no admin password) and adds Start menu and
  Desktop shortcuts. Needs Windows 10 or 11 (64-bit).
  To remove it later: Windows Settings > Apps > CitRunner > Uninstall.

OPTION 2 - NO INSTALL (zip)
  1. Download the file ending in _no-install.zip. Right-click it -> Extract
  All... and put the CitRunner folder somewhere it can stay (for example
  Documents). Don't run it from inside the zip.
  2. Double-click CitRunner.exe. Nothing is installed; to remove it, delete
  the folder.

"Windows protected your PC"? Click "More info" -> "Run anyway".
Windows shows that for apps downloaded from the internet that aren't
signed with a paid certificate.


USING IT
--------
- Type a player's handle (the name in the address of their RSI profile)
  and press Enter or click Look up.
- Click any name in the Recent list to look that player up again.
- Their organizations are listed with the player's rank in each. Click one
  to see its Overview, History, Manifesto, Charter and a Members list.
- "Open on RSI website" opens their page in your browser.


GOOD TO KNOW
------------
- CitRunner only reads public pages on robertsspaceindustries.com. Nothing
  about you is sent anywhere. Parts a player keeps private show as "-".
- RSI has no official lookup service, so if RSI changes its web page some
  details may come up blank.
- Your recent lookups are kept in %APPDATA%\CitRunner.
- Updates: a few seconds after it starts, CitRunner checks GitHub for a newer
  version (it only reads the public release page; nothing is sent). If there
  is one, "Update available" shows at the top right; click it to update. With
  the installer, it downloads and runs the new installer for you; with the
  no-install zip, it opens the download page. Right-click "Check for updates"
  to turn the startup check on or off.
- If something goes wrong, CitRunner-log.txt next to CitRunner.exe says what.
- To remove CitRunner: delete its folder and %APPDATA%\CitRunner.
```

