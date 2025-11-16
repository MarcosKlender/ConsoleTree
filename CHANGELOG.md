# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.2] - 2025-11-16

### Added

- CHANGELOG.md for tracking project version history and notable changes

### Changed

- Lowered minimum VSCode engine requirement from `^1.106.0` to `^1.96.0` for better compatibility
- Added Open VSX Registry installation instructions
- Improved README documentation and styling
- Optimized Demo GIF file size

### Fixed

- Compatibility issues with VSCode-based editors (Cursor, Windsurf)

## [1.0.1] - 2025-11-15

### Added

- Demo GIF in README showcasing extension functionality

### Changed

- Improved README documentation

## [1.0.0] - 2025-11-15

### Added

- Initial release of Console Tree
- Tree view interface in Activity Bar
- Detection of console.log, console.warn, console.error, console.info, and console.debug
- Click-to-navigate functionality
- Individual console statement removal
- Bulk removal of all console statements
- Auto-refresh on file changes
- Configurable file patterns and search patterns
- Support for JavaScript, TypeScript, JSX, TSX, Vue, Svelte, and more
