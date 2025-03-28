# AGNT Downloads

This repository contains the latest versions of AGNT for Windows and macOS.

## Download Links

- [AGNT for Windows](https://agnt.gg/downloads/AGNT-0.2.2.exe)
- [AGNT for macOS](https://agnt.gg/downloads/AGNT-0.2.2-arm64.dmg)

## Installation Instructions

### Windows
1. Download the AGNT.exe file.
2. Double-click the downloaded file to run the installer.
3. Follow the on-screen instructions to complete the installation.

### macOS
1. Download the AGNT.dmg file.
2. Drag the AGNT.dmg file to your Applications folder.
3. Open Terminal (cmd + space, type terminal, enter) and run the following command:
   ```
   sudo xattr -cr /Applications/AGNT.app
   ```
   This removes quarantine attributes which may prevent the app from running.
4. Double-click the AGNT app icon to launch the application.

## System Requirements

### Windows
- Windows 10 or later
- 4 GB RAM (8 GB recommended)
- 500 MB free disk space

### macOS
- macOS 10.15 (Catalina) or later
- 4 GB RAM (8 GB recommended)
- 500 MB free disk space

## Changelog

### Version 0.2.2 (Latest)
- Updated and reordered tool names for better organization
- Fixed several minor bugs
- General performance improvements

### Version 0.2.1
- Added new SLOP tool node (runs any SLOP server)
- Added Notion integration
- Updated Twitter tool with improved features
- Implemented various UX / UI bug fixes for a smoother user experience

### Version 0.2.0
- Implemented MCP client node (runs any SSE based MCP server)
- Fixed for-loop tool counter issue
- Enhanced workflow engine stability
- Improved error handling and reporting
- Optimized performance across all platforms
- General bug fixes and performance improvements

### Version 0.1.9
- Added support for Claude 3.7 Sonnet model
- Improved X.com API error handling for rate limits
- Enhanced workflow engine stability
- General bug fixes and performance improvements

### Version 0.1.8
- Updated server to better catch and handle errors
- Added feature: Copy execution details and execution log to clipboard button in execution history
- Added new LLM models: gemini-pro-2, grok-2, and sonnet 3.5 20241022
- General bug fixes and performance improvements

### Version 0.1.7
- Updated dependencies for improved performance and security.
- Added support for resizing images in Google Slides presentations.
- Enhanced error handling for image loading in Google Slides integration.
- General bug fixes and performance improvements.

### Version 0.1.6
- Enhanced stability and reliability of custom code execution
- Implemented robust error reporting for unresolved templates and null values
- Optimized performance of the JavaScript sandbox environment
- Added timeout mechanism to prevent hanging of long-running scripts
- Improved logging and debugging capabilities for custom scripts

### Version 0.1.5
- Implemented persistent database storage across updates
- Enhanced cross-platform compatibility for database location
- Improved error handling and logging for database operations
- General performance improvements and bug fixes

### Version 0.1.4
- Improved email trigger handling for workflows
- Enhanced error logging and reporting
- Fixed issues with repeated trigger processing
- General performance improvements and bug fixes

## Support

If you encounter any issues during download or installation, please reach out to our discord: https://discord.com/invite/nwXJMnHmXP

## Version Information

Current version: 0.2.2

Last updated: [3-28-2025]

For full release notes and version history, please visit our [official website](https://agnt.gg/).

---

AGNT © 2025. All rights reserved.
