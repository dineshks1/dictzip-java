# Change Log
All notable changes to this project will be documented in this file.

## [Unreleased]
### Add
- gradle.properties.template
  You need to copy to gradle.properties and edit its configuration.

### Changed
- Now this is a Gradle project.
- Reorganize file structures on Maven rules.
- We have now dictzip-lib and dictzip-cli subprojects.
- Command script by Gradle.
- Delete external libraries. Now gradle will download it.
- README: add build procedure, contribution and copyright.
- Coding style checks by checkstyle 6.16.1

## [0.5.0] - 2016-03-21
### Added
- Command line tool subproject.
- CHANGELOG.md file.

### Changed
- DictZipHeader interface.
- DictZipOutputStream constructor interface.

### Fixed
- Broken output features in previous releases.

## 0.0.2 - 2016-03-06
### Added
- Readme document.

## 0.0.1 - 2016-02-28
### Added
- Start project.

[Unreleased]: https://github.com/miurahr/dictzip-java/compare/v0.5.0...HEAD
[0.5.0]: https://github.com/miurahr/dictzip-java/compare/v0.0.2...v0.5.0