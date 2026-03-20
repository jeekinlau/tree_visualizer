# Changelog

All notable changes to the Orchard Tree Visualizer project will be documented in this file.

## [Unreleased] - 2026-02-19

### Added
- **Responsive Design**: Full mobile support with media queries for tablets, phones, and landscape mode
- **Progressive Web App**: Manifest file for installable app on iOS and Android devices
- **Keyboard Shortcuts**: Desktop shortcuts for common actions (G, L, T, S, arrows, [], ?)
- **Settings Persistence**: Automatic saving of user preferences to localStorage
- **Input Validation**: Comprehensive validation with user-friendly error messages
- **Better Error Handling**: Improved GPS error messages with setup instructions
- **Documentation**: Comprehensive README updates with platform compatibility
- **Accessibility**: ARIA labels, improved touch targets, keyboard navigation
- **Help System**: Keyboard shortcut help dialog (press ? key)

### Changed
- Extracted CSS to external stylesheet (styles.css) for better organization
- Improved mobile responsiveness with larger touch targets (44-48px)
- Enhanced GPS error messages with platform-specific instructions
- Updated README to reflect iOS and Android support
- Removed iOS-only limitation in documentation
- Optimized tile layer configuration (removed duplication)

### Technical Improvements
- Separated concerns (HTML structure, CSS styling)
- Added JSDoc comments for better code documentation
- Reduced code duplication using spread operator
- Improved code organization and readability
- Added proper meta tags for mobile devices
- Implemented PWA best practices

### Fixed
- Mobile input auto-zoom issue (increased font size to 16px)
- Sidebar visibility on small screens
- Touch target sizes for mobile accessibility
- Landscape mode layout issues

## Previous Versions

The application was previously a single HTML file with inline CSS and JavaScript, 
primarily tested on iOS devices.
