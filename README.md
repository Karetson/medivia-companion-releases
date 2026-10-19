# Medivia Companion

Companion app for [Medivia Online](https://medivia.online): timers with an in-game overlay that count down
next to the game window. More features (game log import, statistics and charts) are on the way.

This repository holds the Windows releases of the app. It contains no source code.

## Download and install

1. Open the [latest release](https://github.com/Karetson/medivia-companion-releases/releases/latest).
2. Under **Assets**, download `medivia-companion_X.Y.Z_x64-setup.exe` (X.Y.Z is the version).
3. Run the file. The installer suggests the folder `C:\Medivia Companion`; you can choose another one. No
   administrator rights are needed.

**Windows SmartScreen** may show "Windows protected your PC" the first time you run the installer, because
the installer is not yet signed with a code signing certificate. Click **More info → Run anyway** to continue.

<img width="1099" height="747" alt="image" src="https://github.com/user-attachments/assets/44511f79-57fe-462d-9514-8556b4e24b4f" />

Other files of a release:

- `latest.json` is a technical file used by the app's automatic updates. You do not need to download it.
- "Source code (zip)" and "Source code (tar.gz)" are added by GitHub to every release. They contain only
  the files of this repository (this README and `SECURITY.md`), not the app.

## Requirements

- Windows 10 or Windows 11, 64-bit.
- Microsoft Edge WebView2 Runtime (included in Windows 11; the installer downloads it when it is missing).
- The in-game overlay works with the desktop version of the game.

## Updates

The app updates itself on request: **Settings → Check for updates**. Every update is
verified with a signature before it is installed.

## Security

See [`SECURITY.md`](SECURITY.md).

## License

All rights reserved © 2026 Karetson. You may install and use the official releases for personal,
non-commercial purposes; the full licence text is installed with the app as `LICENSE.txt`.
