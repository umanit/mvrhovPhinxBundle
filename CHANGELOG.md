# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres
to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.0.5] - 2022-07-19

### Added

- Allow several migrations directories

## [2.0.4] - 2022-03-22

### Added

- Allow several seeder directories (thanks @GErpeldinger)
- Add a confirmation before executing rollback command (thanks @GErpeldinger)

## [2.0.3] - 2021-12-11

Thanks to @GErpeldinger for all his work!

### Added

- Add `phinx:seed:create` command
- Add `phinx:seed:run` command
- Add aliases on all commands

## [2.0.2] - 2021-11-21

### Fixed

- Resolve env placeholders when processing configuration

## [2.0.1] - 2021-11-20

### Fixed

- Remove deprecated usage of `%kernel.root_dir%`
- Fix the documentation about how to configure the bundle

## [2.0.0] - 2021-10-20

### Changed

- Add support for PHP version `^8.0`.
- Add support for Symfony version `^5.0`.
- Default value of `umanit_phinx.paths.migrations` and `umanit_phinx.paths.seeds`.
- Type of declaration and return value for :
    - `Command/BreakpointCommand.php`
    - `Command/CreateCommand.php`
    - `Command/MigrateCommand.php`
    - `Command/RollbackCommand.php`
    - `Command/StatusCommand.php`

### Removed

- Drop support for old symfony version; `^4.4` is now required.

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

[2.0.0]: https://github.com/umanit/phinx-bundle/compare/v1.1...2.0.0

[2.0.1]: https://github.com/umanit/phinx-bundle/compare/2.0.0...2.0.1

[2.0.2]: https://github.com/umanit/phinx-bundle/compare/2.0.1...2.0.2

[2.0.3]: https://github.com/umanit/phinx-bundle/compare/2.0.2...2.0.3

[2.0.4]: https://github.com/umanit/phinx-bundle/compare/2.0.3...2.0.4

[Unreleased]: https://github.com/umanit/phinx-bundle/compare/2.0.4...master
