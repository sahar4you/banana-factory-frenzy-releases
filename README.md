# Banana Factory Frenzy — beta releases

Catch fresh bananas with Bobo, avoid the rotten ones, sell by the dozen and grow your stall.

This repository publishes official Android beta builds of Banana Factory Frenzy and collects bug reports. It contains release files and documentation only; the application source code is not published here.

## Download

Get the latest APK from the [Releases](https://github.com/sahar4you/banana-factory-frenzy-releases/releases) page.

| | |
|---|---|
| Current beta | 0.1.0-beta.1 (versionCode 2) |
| File | `banana-factory-frenzy-0.1.0-beta.1.apk` (45,953,850 bytes) |
| Package | `com.sahar4you.bananafactoryfrenzy` |
| Requires | Android 7.0 or newer on an ARM phone (arm64-v8a or armeabi-v7a) |

x86 devices and emulators are not supported.

## Install

1. Download the APK on your Android phone.
2. Open it and allow installing apps from this source when Android asks.
3. If an earlier test build of the game is installed and Android refuses the update, uninstall that build first (this removes its saved progress).

## Verify your download

Official builds have these values:

- APK SHA-256: `A3E34875D9AC6C66974528A15F457D9A9F7293108626BA5508724A096347927A`
- Signing certificate SHA-256: `7516D9406E9B582E59C383FDF5D9AD2C6986935082CF739B8E2B5C642854FD58` (`CN=Banana Factory Frenzy`)

Check the file hash:

- Windows: `certutil -hashfile banana-factory-frenzy-0.1.0-beta.1.apk SHA256`
- macOS: `shasum -a 256 banana-factory-frenzy-0.1.0-beta.1.apk`
- Linux: `sha256sum -c SHA256SUMS.txt` (with `SHA256SUMS.txt` from the release in the same folder)

Advanced: with the Android SDK build tools, `apksigner verify --print-certs banana-factory-frenzy-0.1.0-beta.1.apk` shows the signing certificate.

Every future update is signed with the same certificate, so it installs over the previous version and keeps your progress. An APK with a different signing certificate is not an official build.

## Report a bug

Open a [bug report](https://github.com/sahar4you/banana-factory-frenzy-releases/issues/new/choose). The game has no crash reporting, so reports are only received this way. Please do not include personal information, save files or other sensitive data.

## Privacy

This beta works offline and collects no data. See [PRIVACY.md](PRIVACY.md).

## About the source archives

GitHub automatically adds "Source code (zip)" and "Source code (tar.gz)" to every release. In this repository they contain only these documentation files, not the application source code.
