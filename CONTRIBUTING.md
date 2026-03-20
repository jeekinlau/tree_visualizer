# Contributing to Orchard Tree Visualizer

Thank you for your interest in contributing to the Orchard Tree Visualizer!

## Development Setup

1. Clone the repository
2. Open `index.html` in a modern web browser
3. Or use a local web server:
   ```bash
   python3 -m http.server 8080
   # Then visit http://localhost:8080
   ```

## Code Structure

```
tree_visualizer/
├── index.html          # Main application file
├── styles.css          # Stylesheet with responsive design
├── manifest.json       # PWA manifest
├── README.md           # User documentation
├── CHANGELOG.md        # Version history
└── docs/               # Screenshots and images
```

## Making Changes

### Before You Start
1. Check existing issues and pull requests
2. Create an issue to discuss major changes
3. Follow the existing code style

### Code Style Guidelines
- Use consistent indentation (2 spaces)
- Add comments for complex logic
- Use JSDoc for function documentation
- Keep functions small and focused
- Test on multiple browsers and devices

### Testing
Please test your changes on:
- **Desktop**: Chrome, Firefox, Safari, Edge
- **Mobile**: iOS Safari, Android Chrome (if possible)
- **Different screen sizes**: Desktop, tablet, phone

### Mobile Development
- Ensure touch targets are at least 44x44 pixels
- Test on actual devices when possible
- Consider both portrait and landscape orientations
- Test with and without GPS/location services

## Submitting Changes

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Pull Request Guidelines
- Provide a clear description of changes
- Include screenshots for UI changes
- Reference related issues
- Update documentation as needed
- Add entry to CHANGELOG.md

## Feature Requests

Have an idea? Open an issue with:
- Clear description of the feature
- Use case / why it's needed
- Proposed implementation (if you have ideas)

## Bug Reports

Found a bug? Open an issue with:
- Steps to reproduce
- Expected vs actual behavior
- Browser/device information
- Screenshots if applicable

## Future Enhancement Ideas

Areas where contributions would be especially valuable:
- Service worker for offline capability
- Custom modal dialogs (replace alert())
- Additional measurement tools
- More tree layout patterns
- Import/export improvements
- Unit tests
- Internationalization

## Questions?

Open an issue or reach out to the maintainers.

Thank you for contributing! 🌳
