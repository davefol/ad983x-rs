# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

<!-- next-header -->
## [Unreleased] - ReleaseDate

### Changed
- [breaking-change] Updated `embedded-hal` to version `1.0.0-alpha.8`.
- Updated MSRV to Rust 1.62.0.
- Updated dependencies.
- [breaking-change] Protect marker types.

## [0.3.0] - 2021-09-24

### Changed
- [breaking-change] Remove `Default` implementation for `Ad989x`.
- Updated dependencies.

## [0.2.0] - 2019-11-10

### Changed
- Use `embedded_hal::digital::v2::OutputPin` traits for SPI chip-select pin.

## [0.1.1] - 2019-05-30

### Added
- Support for AD9834 and AD9838 devices.

## 0.1.0 - 2019-05-29

Initial release to crates.io. AD9833 and AD9837 devices are fully supported.
All changes will be documented in this CHANGELOG.

<!-- next-url -->
[Unreleased]: https://github.com/eldruin/ad983x-rs/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/eldruin/ad983x-rs/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/eldruin/ad983x-rs/compare/v0.1.1...v0.2.0
[0.1.1]: https://github.com/eldruin/ad983x-rs/compare/v0.1.0...v0.1.1