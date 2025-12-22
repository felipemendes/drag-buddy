# Changelog

All notable changes to Drag Buddy will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2024-12-22

### Added

- Initial release
- Drag any window from anywhere by holding modifier keys
- Customizable key combinations:
  - Two-key combinations: Option+Control, Option+Command, Control+Command
  - Single-key options: Option, Control, Command
  - Custom combinations with up to 4 modifier keys
- Preferences window with General and Update tabs
- Display icon options (Menu Bar only, Dock only, or both)
- Enable/disable dragging toggle
- Activate window on drag option
- Launch at login support
- Show preferences at launch option
- Check for updates functionality
- Menu bar icon grays out when dragging is disabled
- Accessibility permission management with clear instructions
- Privacy-focused design (no data collection, no network access)

### Technical

- Built with AppKit (no SwiftUI)
- Menu bar-only app by default
- Distributed outside the Mac App Store
- Requires macOS 11.5 or later
