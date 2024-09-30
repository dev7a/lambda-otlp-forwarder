# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.1] - 2024-09-29
### Fixed
- Corrected documentation references to use the correct crate name `otlp-stdout-client`

## [0.1.0] - 2024-03-29
### Added
- Initial release of `otlp-stdout-client`
- Support for exporting OpenTelemetry data to stdout in JSON format
- Compatibility with AWS Lambda environments
- Configurable through standard OpenTelemetry environment variables
- Support for both tracing and metrics (as optional features)
- Local implementation of `LambdaResourceDetector` (temporary solution)

[0.1.1]: https://github.com/dev7a/lambda-otlp-forwarder/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/dev7a/lambda-otlp-forwarder/releases/tag/v0.1.0