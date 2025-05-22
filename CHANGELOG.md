# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0] - 2025-05-22

### Added
- **Light Mode:** Full support for a light color scheme, complementing the existing dark mode.
- **Multilingual Support:** Enhanced for easier setup and use with pre-configured English, Spanish, and French.
- **Region in Experience:** `country` field added to experience entries, displayed in the experience section.
- **Carousel Animations:** Implemented new criss-cross transition animations for carousels.
- **Hyperlink SVGs:** Visual indicators (SVGs) added to hyperlinks for better affordance.
- **SVG Reorganization:** Internal SVG assets have been restructured for better maintainability.
- **Enhanced Mobile Navigation:** Improved mobile menu and navigation bars for better usability on small screens.
- **`hugo.example.toml`:** Added a comprehensive example configuration file for users.
- **GitHub Release Badge:** Added to `README.md`.

### Changed
- **Theme Name:** Standardized to "Hugo Noir" across all files.
- **Documentation:** Updated `README.md` extensively to reflect new features and configurations.

### Fixed
- **SVG Optimization:** Replaced long data URI strings for SVGs with minimal, optimized versions.
- **Customization Enhancement:** Removed hardcoded titles and footers from `index.html` to allow for complete user customization via configuration files and i18n.

## [1.0.0] - YYYY-03-12
- Initial release 