# BannChecker APK

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

Lightweight Flutter app for checking banned phone numbers with automated GitHub-based update system.

## Features

 Banned number checker  
 Multiple number list support  
 Automated in-app updates via GitHub Releases  
 SHA-256 integrity verification  
 Changelog display  
 Direct APK download + Browser fallback  

## Quick Start

### Download Latest APK

**Latest Version: 1.0.0** ([Release Notes](CHANGELOG.md))

-  [Download APK](https://github.com/7ucg/bannchecker-apk/releases/download/v1.0.0/bannchecker-1.0.0.apk)
-  Check [releases page](../../releases) for all versions

### Installation

1. Enable unknown sources: `Settings > Security > Unknown Sources`
2. Download APK above
3. Tap file → Install

## Update System

The app automatically checks for updates on startup:
- Fetches version info from [`releases/latest.json`](releases/latest.json)
- Compares with current version
- Shows dialog with changelog + download options
- Supports direct APK download or browser install


## Development

```bash
flutter pub get
flutter run
flutter build apk --release

## Release Process

1. Update version in `pubspec.yaml` and `releases/latest.json`

2. Build: `flutter build apk --release`



## License

MIT - See [LICENSE](LICENSE) file

---

**Author:** Baron  
**Last Updated:** 24. Januar 2026
