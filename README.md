# Html-PPT-Editor

> **Version**: v2.0.3 (2026-06-05)
> **Platforms**: Windows 10/11 · macOS 12.0+ · Linux
> **Last updated**: 2026-06-05

[中文文档 (README.zh-CN.md)](./README.zh-CN.md)

**Edit HTML like editing PPTX.** A desktop HTML presentation editor for the AI era. WYSIWYG editing, fully offline security, one-click sharing — just open and view.

***

## Overview

Built for users who generate HTML presentations with AI tools. Powered by Rust + WebView2, it lets you fix, polish, and enhance AI-generated content — making every presentation professional, secure, and smooth.

> **Core Positioning**: The best editing companion for AI-generated HTML presentations

***

## Features

### Compatibility Matrix

| Feature                | Reveal.js | Marp   | Slidev | Generic HTML |
| ---------------------- | :-------: | :----: | :----: | :----------: |
| **Slide Counting**     |     ⚠️    |   ✅    |   ⚠️    |       ✅      |
| **Slide Navigation**   |     ⚠️    |   ✅    |   ⚠️    |       ✅      |
| **Fullscreen**         |     ⚠️    |   ✅    |   ⚠️    |       ✅      |
| **Presentation Mode**  |     ⚠️    |   ✅    |   ⚠️    |       ✅      |
| **PDF Export**         |     ⚠️    |   ✅    |   ⚠️    |       ✅      |
| **HTML Export**        |     ⚠️    |   ✅    |   ⚠️    |       ✅      |
| **Text Editing**       |     ✅     |   ✅    |   ✅    |       ✅      |
| **Style Settings**     |     ✅     |   ✅    |   ✅    |       ✅      |
| **Image Editing**      |     ✅     |   ✅    |   ✅    |       ✅      |
| **Video Editing**      |     ✅     |   ✅    |   ✅    |       ✅      |
| **URL Embedding**      |     ✅     |   ✅    |   ✅    |       ✅      |
| **Animations**         |     ❌     |  N/A   |   ❌    |      ⚠️      |
| **Framework-specific** |     ❌     |   ⚠️    |   ❌    |      N/A     |
| **Portrait Slides**    |     ❌     |  N/A   |  N/A   |      N/A     |
| **Interactivity**      |     ❌     |  N/A   |   ❌    |      N/A     |
| **Header/Footer Mgmt** |     ⚠️    |   ✅    |   ⚠️    |       ✅      |
| **Runtime Friction**   |     ⚠️    | ✅ None |   ❌    |   ✅ None    |

### ✏️ Visual Editing

A true WYSIWYG experience with no coding required. Select text to adjust styles (bold, italic, underline, strikethrough), switch heading levels (H1/H2/H3), and change alignment. Insert images, local videos, online videos, and hyperlinks directly.

> ⚠️ **Note**: After opening an HTML file, click the **"Edit" button** in the sidebar to activate editing mode and show the toolbar. Click it again to exit editing mode and return to read-only preview.

### 📄 Source Code Editing

A 420px code editing panel with monospace font and real-time preview updates. Gives technical users fine-grained control over every line of code.

### 🔍 Preview & Zoom

Smooth CSS transform-based zoom (25% — 300%, ±10% per step). One-click 1:1 reset. Does not interfere with editing.

### 📊 Slide Navigation

Automatically detects slide markers in your HTML. Supports **8 marker types**: `.slide`, `.slide-page`, `.page`, `<section>`, `<article>`, `data-slide`, `data-page`, `hr.separator`. The top bar shows your current position in real time. Free edition supports up to 20 slides per day.

### 🎬 Fullscreen Presentation

An immersive presentation mode that hides all UI. Pure black background with floating controls. Keyboard navigation (← → ↑ ↓ Space Home End) and smooth CSS animations throughout. Sidebar state restores automatically on exit.

### 📥 File Operations

- Open via button click or Ctrl+O shortcut
- Click the center button in blank state
- **Pro**: Load from URL (with SSRF protection, anti-scraping detection, rate limiting)
- One-click save (Ctrl+S) — preview watermarks are automatically removed

### 🎨 Theme Management

5 built-in beautiful themes: DeepLogiX Dark, Nordic Light, Midnight Blue, Forest, and Monochrome. Switch the entire look with one click. Pro edition supports theme persistence; Free edition is session-only.

### 📋 Header & Footer Management

Auto-detects header/footer elements with `position: fixed/absolute`. Supports show/hide toggling, HTML content editing, and image replacement. **Note**: Elements with `sticky` / `relative` positioning are not detected.

### 🖼️ Media Management

Insert and manage images (PNG/JPG/GIF/WebP/SVG/BMP/ICO), local videos (MP4/WebM/MOV/AVI/MKV/M4V/OGG, ≤ 100 MB per file), online videos (auto-detect YouTube/Bilibili/Vimeo embeds), and hyperlinks. Free edition supports 25%/50%/100% preset sizes; Pro edition supports drag-to-resize and image replacement.

### 📤 Export

- **Export HTML** (Free): One-click generates `presentation.html` + `asset/` directory. Media paths auto-rewritten as relative paths, watermarks and editor attributes removed.
- **Export PDF** (Pro): Powered by `pdf-lib`. Each slide becomes one PDF page (1920×1080). Videos rendered as poster image placeholders.

***

## Free Edition (Forever Free)

| Feature             | Description                                       |
| :------------------ | :------------------------------------------------ |
| HTML Editor         | ✅ Full WYSIWYG editing                            |
| Live Preview        | ✅                                                 |
| Source Code Editing | ✅                                                 |
| File Save           | ✅                                                 |
| Export HTML         | ✅                                                 |
| Daily Page Limit    | **20 pages/day** (auto-reset at 0:00)              |
| Built-in Themes     | ✅ 5 themes (session-only; default on restart)     |
| Media Preset Sizes  | ✅ 25% / 50% / 100%                                |
| License Activation  | None required — works out of the box              |

The Free edition covers most everyday editing scenarios. Download and use immediately — no registration, no internet, no activation needed.

## Pro Edition (Activation Required)

| Feature                | Description                                                |
| :--------------------- | :--------------------------------------------------------- |
| Unlimited Pages        | Remove the 20-page/day limit                                |
| Load from URL          | Enter a URL to fetch HTML (with SSRF protection & rate limit) |
| Theme Persistence      | Auto-save theme selection                                   |
| Custom Theme Import    | Import JSON themes from `themes/` directory                |
| Media Drag & Drop      | Drag to customize media dimensions (CSS resize)             |
| Media Replacement      | Right-click to replace images (keep size / auto-fit)        |
| Font Color & Highlight | Text color and highlight background                         |
| **PDF Export**         | **One-click PDF export (powered by pdf-lib)**               |

***

## Download & Install

### Windows

1. Download the `.msi` or `.exe` installer from the release page
2. Double-click to run the installer
3. **Security notice**: Windows SmartScreen may show "Windows protected your PC" warning, as the software does not yet have a digital signature certificate. Click **"More info"** → select **"Run anyway"** to proceed with installation
4. Launch from the desktop shortcut or Start menu after installation

### macOS

1. Download the `.dmg` package from the release page
2. Double-click to open the DMG file and drag the app icon into the Applications folder
3. **First launch notice**: macOS Gatekeeper will block unsigned apps from running, showing "cannot verify the developer". To bypass:
   - Go to **System Settings → Privacy & Security**
   - Scroll down to the security section and click the **"Open Anyway"** button
   - Click **"Open Anyway"** again in the confirmation dialog
   - Alternatively, right-click the app in Finder → select **"Open"**, then choose **"Open"** in the warning dialog
4. Subsequent launches will not be blocked

### Linux

1. Download the `.AppImage` or `.deb` package from the release page
2. **AppImage method**:
   - Set executable permission: `chmod +x Html-PPT-Editor*.AppImage`
   - Double-click or run from terminal
   - If blocked, right-click the file → Properties → Permissions → check "Allow executing file as program"
3. **Deb method**: Double-click the `.deb` file or install with `sudo dpkg -i *.deb`
4. Launch from the application menu or terminal

***

## Quick Start

1. Launch the software and import an HTML presentation file
2. Click the **"Edit"** button in the sidebar to enter visual editing mode
3. Select and modify text content directly in the preview area
4. Click **"Save"** (Ctrl+S) — preview watermarks are automatically removed
5. Click **"Fullscreen Presentation"** or export HTML to share with others

***

## Platform Support

| OS       | Support                                                |
| :------- | :----------------------------------------------------- |
| Windows  | ✅ Native installer (NSIS / MSI / portable)              |
| macOS    | ✅ Native installer (DMG)                               |
| Linux    | ✅ Native installer (AppImage / deb)                    |

### System Requirements

| Item         | Windows                            | macOS                  | Linux                                                |
| :----------- | :--------------------------------- | :--------------------- | :--------------------------------------------------- |
| OS           | 10 21H2+ / 11                      | 12.0 Monterey+         | Ubuntu 20.04+                                        |
| Runtime      | WebView2 Runtime (built-in on 21H2+) | Built-in WKWebView   | `libwebkit2gtk-4.1-dev` + `libgtk-3-dev`              |
| Binary Size  | ~5.4 MB                            | ~10 MB                 | ~8 MB                                                |
| Resolution   | Min 1024×720, recommended 1920×1080+ | Same                | Same                                                 |

***

## Security & License

- **Offline License**: No internet required for activation. License stored locally in `license.dat`
- **Encrypted Storage**: AES-256-GCM + HKDF-SHA256
- **Signature Verification**: RSA-2048 + PKCS#1 v1.5 + SHA-256, verified at every startup
- **Device Binding**: SHA-256 fingerprint based on system UUID / machine-id
- **Anti-Debug**: 7 layers (IsDebuggerPresent, CheckRemoteDebuggerPresent, NtQueryInformationProcess, TracerPid, stack canary, binary self-check, time anomaly)
- **Audit Log**: All license operations recorded in `audit.log`
- **Time Rollback Detection**: 60-second threshold

License format: `DPLX-v2.<base64url payload>.<base64url signature>`

***

## Keyboard Shortcuts

| Shortcut                  | Action                                |
| :------------------------ | :------------------------------------ |
| `Ctrl + O`                | Open HTML file                        |
| `Ctrl + S`                | Save current file                     |
| `Ctrl + B`                | Toggle sidebar                        |
| `Esc`                     | Collapse sidebar / Exit presentation  |
| `Ctrl + Z` / `Ctrl + Y`   | Undo / Redo (8\~20 steps)             |
| `←` `→` `↑` `↓`           | Navigate slides in presentation       |
| `Space`                   | Next slide                            |
| `Home` / `End`            | Jump to first / last slide            |

> **Note**: On macOS, `Ctrl` corresponds to `Cmd`.

***

## Contact

- Email: <D-LogiX@outlook.com>
- Project: <https://github.com/DeepLogiX/htmleditor-v2>
- GitHub: github.com/FYLS9527

***

*Html-PPT-Editor v2.0.2 by FYLS9527 — Making AI-generated presentations simple, secure, and professional*
