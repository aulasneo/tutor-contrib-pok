# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Added branding-aligned local maintenance tooling with a `Makefile`, dev requirements files, and modern build/test targets.
- Added GitHub Actions `test.yml` and `publish.yml` workflows for test and release automation.

### Changed
- Updated packaging metadata to require Python 3.11+ only and aligned the project with current build tooling expectations.
- Ignored generated Tutor local artifacts such as `config.yml` and `env/`.

## [20.0.0] - 2026-03-17

### Changed
- Upgraded Tutor compatibility to version 20.x for Open edX Teak.
- Scoped the LMS init task to the LMS app context and lowered its priority so it runs after core LMS initialization.

## [19.1.2] - 2025-12-05

* Do not allow multiple templates for the same course.
* Improve testing and code quality.

## [19.1.1] - 2025-11-06

### Changed
- Bumped `POK_PLUGIN_VERSION` default to `v1.0.2`, implementing language resolution changes.

## [19.1.0] - 2025-11-06

### Changed
- Bumped `POK_PLUGIN_VERSION` default to `v1.0.1`, implementing language resolution changes.

## [19.0.2] - 2025-10-28

### Changed
- Updated documentation to include waffle flag configuration

## [19.0.1] - 2025-07-17 - 2025-07-17

### Changed
- Added initialization script for LMS

### Fixed
- Improved documentation

## [19.0.0] - 2025-07-09

### Added
- Initial version of the POK certificates plugin for Tutor
- Version management with bump2version
- CHANGELOG.md for tracking changes

### Changed
- Updated Tutor dependency to version 19.x

## [18.0.0] - 2025-07-09

### Added
- Initial release of the POK certificates plugin
