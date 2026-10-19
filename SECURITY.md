# Security policy

## Supported versions

Only the latest release receives security fixes. The app can update itself to the latest release
(**Settings → Check for updates**).

## Reporting a vulnerability

Please **do not open a public issue** for security problems. Report them privately through GitHub:
**Security → Report a vulnerability** on this repository (private vulnerability reporting).

Include what you found, how to reproduce it and which version you used. You will get an answer within
14 days. Please give us a reasonable time to release a fix before you disclose the issue publicly.

## Scope

- The desktop app, its installer and its automatic updates.
- The release files in this repository (`medivia-companion_X.Y.Z_x64-setup.exe`, `latest.json`).

Out of scope: the game Medivia Online itself and its website.

## How releases are made

Releases are built by an automated release pipeline and published here only with their complete set of
files. Every installer carries an updater signature that installed copies verify before they update.
