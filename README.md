# Akira Theme

![Version](https://img.shields.io/badge/version-1.0.0-blue?style=flat)
![License](https://img.shields.io/badge/license-MIT-green?style=flat)
![GitHub Stars](https://img.shields.io/github/stars/videmelo/akira-theme?style=flat)

Akira is a dark theme for Visual Studio Code, inspired by Cursor's Anysphere and the Mhammed Talhaouy theme.

![banner](https://raw.githubusercontent.com/videmelo/akira-theme/main/images/banner.png)

## Installation

Option 1 - Marketplace

-  Search for "Akira" or `videmelo.akira` in the Visual Studio Code Marketplace and install it directly.

Option 2 - Manual / Local

1. Open Visual Studio Code.
2. To test locally without packaging, copy the project folder into the VS Code extensions directory (for example: `%USERPROFILE%\.vscode\extensions\akira-theme`) and restart VS Code.

Or package it as a `.vsix` and install:

```powershell
# Install the packaging tool (if needed)
npm install -g vsce
# Package the theme (run from the project root)
vsce package
# Install the generated .vsix
code --install-extension .\\akira-0.0.1.vsix
```

## Usage

-  After installation, open the Command Palette (F1) `Preferences: Color Theme` select **Akira**.
