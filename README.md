# KodBot releases

This repository holds KodBot release artifacts and update feeds.

Source code: <https://github.com/kod13eood-cmd/KodBot>

## Download the latest build

These links always point at the newest published release:

| Platform | Package |
| --- | --- |
| Windows (x64) | [KodBot-setup.exe](https://github.com/kod13eood-cmd/kodbot-releases/releases/latest/download/KodBot-setup.exe) |
| Linux (x64 AppImage) | [KodBot.AppImage](https://github.com/kod13eood-cmd/kodbot-releases/releases/latest/download/KodBot.AppImage) |
| Linux (Debian/Ubuntu) | [KodBot.deb](https://github.com/kod13eood-cmd/kodbot-releases/releases/latest/download/KodBot.deb) |
| Android (APK) | [KodBot-android.apk](https://github.com/kod13eood-cmd/kodbot-releases/releases/latest/download/KodBot-android.apk) |

Versioned files are attached alongside each stable name
(`KodBot-<version>-setup.exe`, `KodBot-<version>-x86_64.AppImage`,
`KodBot-<version>-amd64.deb`, `KodBot-android-<version>.apk`).

## Code signing policy

Free code signing provided by [SignPath.io](https://signpath.io), certificate by
[SignPath Foundation](https://signpath.org). The Windows installer is signed
through SignPath Foundation's open-source programme after manual approval.

- [Full code signing policy](https://github.com/kod13eood-cmd/KodBot/blob/main/CODE_SIGNING_POLICY.md)
- [Privacy policy](https://github.com/kod13eood-cmd/KodBot/blob/main/PRIVACY.md)

The Windows installer is currently unsigned; SmartScreen shows **Unknown
publisher** on first run — choose **More info → Run anyway**. The Android APK
is debug-signed and installs over an existing debug build.

The Linux AppImage is self-contained; `chmod +x KodBot.AppImage` and run it.
The `.deb` installs with `sudo apt install ./KodBot.deb`.

macOS builds are produced by the separate signed/notarized flow and are not
built by this repository's Linux/Windows workflow.
