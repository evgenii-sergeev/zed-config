# Zed Editor Configuration

This repository contains a customized configuration for the [Zed](https://zed.dev) code editor, designed for an enhanced developer experience with a focus on JavaScript/TypeScript and modern web development.

## ✨ Features

- **Assistant Integration**  
  Uses the latest Claude 3.7 Sonnet model from `zed.dev` for AI assistance.

- **UI & Theme Customization**  
  - Dark mode enabled by default (`One Dark` / `One Light` themes).
  - JetBrains Mono font with adjusted font sizes for better readability.
  - Comfortable line height for code buffers.

- **Editing Enhancements**  
  - Subtle edit predictions.
  - Enabled indent guides with smart coloring.
  - Auto-formatting for TSX files using Prettier.
  - Inlay hints for improved code comprehension.
  - Live diffs for real-time file comparison.

- **Project & Workspace Behavior**  
  - Automatically restores the last workspace on startup.
  - Custom tab behavior and Git integration in tabs.
  - Standard spacing in the project panel with custom indentation.

- **Language Support & LSP Settings**  
  - Auto-installation of common web dev extensions (HTML, CSS, JS, TS, React, JSON, Markdown, Emmet).
  - Rich inlay hints for both JavaScript and TypeScript (parameter names/types, return types, enum values, etc.).
  - Integrated LSP support with `vtsls`.

- **Terminal Configuration**  
  - System shell with 12pt font.
  - Automatic detection of Python virtual environments via `.env` directories.

## 🔧 Setup Instructions

To use this configuration:

1. Open Zed.
2. Run the command: `Zed: Open User Settings`.
3. Replace the contents with the `zed-config.json` from this repo.
4. Save and restart Zed.

## 🧠 Notes

- You can tweak font sizes, themes, and tab behavior further to match your personal preferences.
- For more documentation on configuring Zed, visit the [official docs](https://zed.dev/docs/configuring-zed).

---

Enjoy a faster, cleaner, and more productive coding experience with Zed! 🚀
