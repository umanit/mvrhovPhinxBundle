# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [v1.1] - 2019-11-08
### Fixed
- Cannot migrate due to wrong requirement of a name in configuration.

## [v1.0] - 2019-11-02
### Added
- Add a new `umanit_phinx.environment.connection.dsn` parameter.

### Changed
- Add support for phinx 0.11.

### Removed
- Remove all old parameters from `umanit_phinx.environment.connection`.
- Drop support for old PHP version; ^7.1 is now required.

## v0.10 - 2019-02-06
### Added
- Add support for phinx 0.10.

### Changed
- Change namespace in the code.

### Fixed
- Fix BC break with Symfony < 4.

[v1.0]: https://github.com/umanit/phinx-bundle/compare/v0.10...v1.0
[v1.1]: https://github.com/umanit/phinx-bundle/compare/v1.0...v1.1
[Unreleased]: https://github.com/umanit/phinx-bundle/compare/v1.1...master
