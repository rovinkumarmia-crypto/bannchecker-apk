# Changelog

## [2.0.1] - 2026-04-04
### Fixed
- Non-`temporarily_unavailable` API fail responses are now treated as unbanned results
- `temporarily_unavailable` responses still show as a temporary service warning
- Cleaned update-service logging behavior in the app

### Changed
- Bumped the app version to `2.0.1`

## [2.0.0] - 2026-04-04
### Added
- Flutter-native app interface replacing the previous HTML/WebView-based runtime
- Optional result dialog with separate settings for dialog colors and texts
- Crash reporting with file logging and a visible crash popup
- Four APK variants for easier installation across different Android device architectures

### Changed
- Updated the app package to the `2.0.0` release line
- Improved the result dialog design with a darker semi-transparent background and simplified styling

### Fixed
- Fixed ban-check handling for temporary  availability problems so they no longer appear as normal unbanned results
- Fixed background image handling for base64 data sources

### Performance
- Reduced app size to under 43 MB
- Reduced lag by removing the old embedded web runtime and moving to a Flutter-native interface
- Improved startup and overall stability

## [1.0.0] - 2026-01-24
### Added
- Initial release
- Core banned number checker functionality
- Support for multiple number lists
- In-app update system
- GitHub Releases integration
- Direct APK download

### Technical
- Flutter 3.x
- Dart null safety
- HTTP caching with ETag support
- SHA-256 integrity verification
