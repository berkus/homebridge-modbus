# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0] - 2021-03-14

### Changed

- Original homebridge-modbus npm version 1.0.1 is not in github, so this 1.0.0 is based on 1.0.0 version available on github and then patched by AlekseevAV to support scaling of values.
- Support simple value adjustment via "correction" key in the map. It could only be something simple like `"correction": "/10"` but this should be enough for most cases.

[Unreleased]: https://github.com/berkus/homebridge-modbus/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/berkus/homebridge-modbus/compare/original-v1.0.0...v1.0.0
