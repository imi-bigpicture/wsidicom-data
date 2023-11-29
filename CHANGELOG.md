# wsidicom-data changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2023-11-29

### Added

- Methods for getting rgb and grayscale (8, 12, and 16 bits) Pillow images.

### Changed

- Scale samples to number of bits in output.
- RLE segment are even number of bytes.
- MCT used for jpeg2000 lossless YBR.

## [0.1.0] - 2023-11-22

### Added

- Initial release of wsidicom-data

[Unreleased]: https://github.com/imi-bigpicture/wsidicom-data/compare/0.1.0..HEAD
[0.1.0]: https://github.com/imi-bigpicture/wsidicom-data/tree/refs/tags/v0.1.0
