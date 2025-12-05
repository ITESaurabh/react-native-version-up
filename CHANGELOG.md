# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

> **Note:** Version 1.1.3 is the first version of this fork. For older versions (1.1.2 and below), please refer to the original repositories:
> - [gdulik/react-native-version-up](https://github.com/gdulik/react-native-version-up)
> - [gustarus/react-native-version-up](https://github.com/gustarus/react-native-version-up)

## [1.1.3] - 2025-12-05

### Changed

- Migrated from `.eslintignore` to `ignores` property in `eslint.config.mts`

### Fixed

- Fixed iOS build number always resetting to 1 instead of incrementing like Android
- Changed `--build` flag from boolean to number type to accept custom build values
- Build numbers now auto-increment by default, or can be set to a specific value using `--build <number>`

## [1.1.1] - 2022-11-25

### Added

- Add CHANGELOG

### Changed

- Update chalk dependency

### Fixed

- Fix incorrect path to index file in README
- Fix incorrect repository url in README

## [1.1.0] - 2022-11-18

### Added

- New option to increase only build number
- Separate versioning logic of Android and iOS

### Changed

- iOS version file from .plist to .pbxproj

[1.1.3]: https://github.com/ITESaurabh/react-native-version-up/tree/v1.1.3
[1.1.1]: https://github.com/gdulik/react-native-version-up/tree/v1.1.1
[1.1.0]: https://github.com/gdulik/react-native-version-up/tree/v1.1.0
