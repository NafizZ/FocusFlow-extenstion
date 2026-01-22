# Privacy Policy

Last updated: 2025-01-22

FocusFlow is a productivity-focused browser extension designed to enhance user concentration through configurable timers, intelligent break scheduling, and selective content filtering. This document outlines our data handling practices and technical implementation.

## Data Collection Architecture

FocusFlow operates under a strict zero-data-collection principle. The extension does not:
- Collect, transmit, or process personal identifiable information
- Implement analytics, tracking mechanisms, or telemetry
- Communicate with external servers or third-party services
- Store data outside the user's local browser environment

## Local Data Storage

All application data is persisted exclusively within the browser's local storage APIs. The following data structures are maintained client-side:

- **Configuration State**: Timer preferences, session parameters, and user-defined settings
- **Filtering Rules**: Domain blocklist configurations (default templates and custom entries)
- **Usage Analytics**: Localized focus session metrics and distraction tracking statistics

This architecture ensures complete data isolation - information never leaves the user's browser instance.

## Permission Requirements

FocusFlow requests the minimal necessary permissions to implement core functionality:

- **Storage API**: Persistent configuration and state management
- **Tabs API**: Active tab URL detection for content filtering
- **Alarms API**: Background timer synchronization and session management
- **Notifications API**: Break reminder delivery system
- **Host Permissions** (http/https/*): URL pattern matching for overlay deployment

## Data Lifecycle Management

All data resides exclusively in the client's browser storage. Users maintain complete control through:
- Browser extension data clearing mechanisms
- Extension uninstallation procedures
- Built-in configuration reset options

## Policy Updates

Modifications to this privacy policy will be documented in the repository's change history. Users are encouraged to review updates during extension updates.

## Technical Support

For privacy-related inquiries or technical questions regarding data handling practices:
- **Contact**: altafhossain7227@gmail.com
- **Repository**: Issues and discussions available via project GitHub page
 +++++++ REPLACE
