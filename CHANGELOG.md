# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- Added `adapter_service` and `adapter_timeout` configuration options
### Deprecated
- Deprecated the `adapter_class` configuration option. Use `adapter_service` instead for custom adapters.
- Deprecated the `timeout` option for endpoints. Configure the timeout on the client using `adapter_timeout` or configure your custom adapter service accordingly.
### Changed
- Remove support for Symfony 3.x
- Remove support for Symfony <= 4.3
- Require Solarium ^5.2
### Fixed
- Fixed deprecations introduced in Solarium 5.2
### Security

## [v4.0.0](https://github.com/nelmio/NelmioSolariumBundle/releases/tag/v4.0.0) - 2020-05-08
### Changed
 - Add support for Symfony v5.x [#PR-98](https://github.com/nelmio/NelmioSolariumBundle/pull/98)

## [v4.0.0-rc.1](https://github.com/nelmio/NelmioSolariumBundle/releases/tag/v4.0.0-rc.1) - 2019-12-16
### Changed
 - Removed support for PHP 7.1 (require PHP >= 7.2)
 - Removed support for unmaintained Symfony versions
 - Require Solarium >= 5.x
### Fixed
- Fixed Symfony 4.4 deprecations
