# wsidicom-data changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.4.0] - 2026-11-27

### Added

- Encoded files for JPEG Lossless SV1, which settings with predictor 1 give from wsidicom 0.38.

### Changed

- The encoded files for JPEG Lossless are encoded with predictor 7. They were encoded with predictor 1, as the settings for both predictors wrote the same files.

### Removed

- Settings and encoded file for JPEG Lossless with YBR, which stored the samples as RGB. wsidicom 0.38 does not allow such settings.

## [0.3.0] - 2023-12-06

### Added

- RGB images for Jpeg-LS.

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

[Unreleased]: https://github.com/imi-bigpicture/wsidicom-data/compare/v0.4.0..HEAD
[0.4.0]: https://github.com/imi-bigpicture/wsidicom-data/compare/v0.3.0..v0.4.0
[0.3.0]: https://github.com/imi-bigpicture/wsidicom-data/compare/v0.2.0..v0.3.0
[0.2.0]: https://github.com/imi-bigpicture/wsidicom-data/compare/v0.1.0..v0.2.0
[0.1.0]: https://github.com/imi-bigpicture/wsidicom-data/tree/refs/tags/v0.1.0
