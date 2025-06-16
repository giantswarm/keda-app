# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [3.0.0] - 2025-06-16

### Changed

- Upgrade app to version 2.17.1 to support kubernetes 1.30 to 1.32.
- Upgrade chart to upstream version 2.17.1.

## [2.0.0] - 2025-06-12

### Changed

- Upgrade app to version 2.15.1 to support kubernetes 1.28 to 1.30.
- Upgrade chart to upstream version 2.15.2.

## [1.0.0] - 2024-07-08

### Changed

- Upgrade app and chart to upstream version 2.11.2 to support kubernetes 1.25 to 1.27.

## [0.3.1] - 2024-02-23

### Fixed

- Fix pod disruption budget to allow disruptions when replica count is 1.

## [0.3.0] - 2024-02-22

### Added

- Allow extra egress policies to be configured in the keda-operator ciliumnetworkpolicy.

## [0.2.0] - 2023-11-08

### Added

- Add VPA CRs to both `keda-operator` and `keda-operator-metrics-apiserver`.

## [0.1.1] - 2023-11-07

### Fixed

- Fix CI configuration.

## [0.1.0] - 2023-11-07

### Added

- Create first app iteration.

[Unreleased]: https://github.com/giantswarm/keda-app/compare/v3.0.0...HEAD
[3.0.0]: https://github.com/giantswarm/keda-app/compare/v2.0.0...v3.0.0
[2.0.0]: https://github.com/giantswarm/keda-app/compare/v1.0.0...v2.0.0
[1.0.0]: https://github.com/giantswarm/keda-app/compare/v0.3.1...v1.0.0
[0.3.1]: https://github.com/giantswarm/keda-app/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/giantswarm/keda-app/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/giantswarm/keda-app/compare/v0.1.1...v0.2.0
[0.1.1]: https://github.com/giantswarm/keda-app/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/giantswarm/keda-app/releases/tag/v0.1.0
