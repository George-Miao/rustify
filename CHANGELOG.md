# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2021-08-18

### Added
- Query parameters can now be specified using the `query` attribute

### Changed
- Response errors try to parse content to be UTF-8 encoded strings instead of raw bytes
- Successul response codes updated to an inclusive range of 200-208

### Fixed
- The `builder` option can now be used with structs that have generics and lifetimes

## [0.1.0] - 2021-08-15

### Added
- Initial release

[unreleased]: https://github.com/jmgilman/rustify/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/jmgilman/rustify/releases/tag/v0.2.0
[0.1.0]: https://github.com/jmgilman/rustify/releases/tag/v0.1.0