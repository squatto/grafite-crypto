# Change Log - Crypto
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).
----

## [v1.2.1] - 2020-05-25

### Changed
- Upgrade `ramsey/uuid` from v3 to v4
- Updated dependencies

## [v1.2.0] - 2020-08-08

### Changed
- Require PHP 7.3+, Laravel 7.0+
- Updated dependencies

## [v1.1.4] - 2020-05-25

### Changed
- Updated dependencies

## [v1.1.3] - 2020-02-18

### Changed
- Require PHP 7.2+, Laravel 6.0+
- Updated dev dependencies

## [v1.1.2] - 2020-02-17

### Changed
- Forked package to [squatto/grafite-crypto](https://github.com/squatto/grafite-crypto)
  because [GrafiteInc/Crypto](https://github.com/GrafiteInc/Crypto) is abandoned
- Changed composer package name to `squatto/grafite-crypto`
- Moved `Blade::directive()` calls in `CryptoProvider.php` from `register()` to `boot()` to fix
  a compatibility bug with Laravel 5.8

## [v1.1.1] - 2018-10-20

### Changed
- Switched UUID to Ramsey rather than rely on uniqid which may be deprecated in the future

## [v1.1.0] - 2018-03-19

### Changed
- Rebranding

## [v1.0.6] - 2017-01-27

### Changed
- Updated composer for easier maintenance

## [v1.0.5] - 2017-01-08

### Changed
- Minor improvements for lacking env variables

## [v1.0.4] - 2016-08-26

### Fixed
- Composer fixes

## [v1.0.3] - 2016-08-24

### Added
- Support for Laravel 5.3

## [v1.0.2] - 2016-07-24

### Fixed
- Issue with encrypt

## [v1.0.1] - 2016-07-24

### Fixed
- General fixes for Lumen support

## [v1.0.0] - 2016-07-18

### Changed
- Initial build separating from Laracogs
