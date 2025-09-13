# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a VSCode theme extension called "Sonder" - a dark theme for Visual Studio Code. The project is a VSCode extension that provides a single dark color theme inspired by Jon Blow's Emacs theme and the Witness theme for Sublime Editor.

## Architecture

- **Theme Definition**: The main theme configuration is in `themes/Sonder-color-theme.json`, which contains all color mappings for VSCode UI elements and syntax highlighting
- **Extension Manifest**: `package.json` defines the VSCode extension metadata, dependencies, and contribution points
- **Static Assets**: Logo and screenshots are in `static/` directory
- **Documentation**: Sample code and documentation in `docs/` and `samples/` directories

## Common Commands

### Development and Publishing
- `npm run package` - Package the extension into a .vsix file using vsce
- `npm run login` - Login to Visual Studio Code Marketplace
- `npm run publish` - Publish to marketplace and push git changes with tags
- `npm run patch` - Increment patch version and create release commit
- `npm run minor` - Increment minor version and create release commit  
- `npm run major` - Increment major version and create release commit

### Dependencies
The project uses `@vscode/vsce` for packaging and publishing VSCode extensions.

## Key Files
- `themes/Sonder-color-theme.json`: Main theme definition with color mappings
- `package.json`: VSCode extension manifest and npm scripts
- `static/logo/logo.png`: Extension icon displayed in VSCode marketplace