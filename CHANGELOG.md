# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.1.5] - 2025-05-XX

### Changed
- Improved issue matching regex to accurately detect closes/fixes and bare GitHub links.
- Generalized the ZAP auto-labeling feature into a more robust `Auto-labeling Issues and PRs` feature using JSON configurations.
- Action inputs changed: `enable-zap-labeling` -> `enable-auto-labeling`, `zap-labels` -> `auto-label-rules`.

## [1.0.0] - 2025-01-XX

### Added
- Initial release of Issue & PR Automation Suite
- Project board automation for GitHub Projects V2
  - Automatically add new issues to project backlog
  - Update issue status based on PR lifecycle (In Progress, In Review)
- Label and milestone synchronization between issues and PRs
  - Bidirectional label sync
  - Smart milestone sync
- ZAP security scan issue auto-labeling
- Configurable inputs for all features
- Comprehensive documentation with examples

### Features
- Support for composite GitHub Action
- Integration with GitHub Projects V2 GraphQL API
- Automatic issue linking detection (multiple patterns supported)
- Modular feature enablement (can enable/disable individual features)

[Unreleased]: https://github.com/SillyLittleTech/AutomationSuite/compare/v2.1.5...HEAD
[2.1.5]: https://github.com/SillyLittleTech/AutomationSuite/compare/v1.0.0...v2.1.5
[1.0.0]: https://github.com/SillyLittleTech/AutomationSuite/releases/tag/v1.0.0
