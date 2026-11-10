# TradePilot Releases

Android releases for the standalone TradePilot mobile app. The source project remains in its separate repository. The app runs its Python engine and SQLite database on-device; it does not require a PC server.

## Current Android release: 0.14.1

- Android APK: [TradePilot-0.14.1-android.apk](https://github.com/HeesungYang1/auto-trading-system-releases/releases/download/v0.14.1/TradePilot-0.14.1-android.apk)
- SHA-256 file: [SHA256SUMS.txt](https://github.com/HeesungYang1/auto-trading-system-releases/releases/download/v0.14.1/SHA256SUMS.txt)
- Release notes: [GitHub release v0.14.1](https://github.com/HeesungYang1/auto-trading-system-releases/releases/tag/v0.14.1)

The Android app checks anonymous public release metadata, automatically downloads a newer APK, and verifies its checksum, package, version, and signing certificate before marking it ready. The user starts installation through Android's standard installer. Installation remains gated while a trading engine is running or unresolved orders exist; the app does not force-stop trading. Windows PC 0.3.0 is a retired legacy build and is not an Android update source.

iOS has no installable release in this version. No source archive, SDK, QA material, or user data is published here. Release assets contain the Android APK and SHA256SUMS.txt only.
