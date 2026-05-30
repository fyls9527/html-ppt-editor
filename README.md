# Html-PPT-Editor

**中文** — 像编辑PPTX一样，编辑HTML。 一款面向 AI 时代的 HTML 演示文稿桌面编辑器 —— 所见即所得编辑、完全离线安全运行、一键分享即开即看。

**English** — Edit HTML like editing PPTX. A desktop HTML presentation editor for the AI era. WYSIWYG editing, fully offline security, one-click sharing — just open and view.

***

## 软件简介 / Overview

**中文** — Html-PPT-Editor 专为使用 AI 工具生成 HTML 演示文稿的用户打造。基于 Rust+ WebView2，赋予你修正、美化、增强 AI 生成内容的能力，让每一份演示都专业、安全、流畅。

> **核心定位**：AI 生成 HTML 演示文稿的最佳编辑伙伴

**English** — Built for users who generate HTML presentations with AI tools. Powered by Rust + WebView2, it lets you fix, polish, and enhance AI-generated content — making every presentation professional, secure, and smooth.

> **Core Positioning**: The best editing companion for AI-generated HTML presentations

***

## 功能特性 / Features

### ✏️ 可视化编辑 / Visual Editing

**中文** — 所见即所得的编辑体验，无需手写代码。选中文字即可调整样式（加粗、斜体、下划线、删除线）、切换标题级别（H1/H2/H3）、调整对齐方式。支持直接插入图片、视频、在线视频和超链接。

> ⚠️ **操作提示**：打开 HTML 文件后，需点击侧边栏的\*\*"编辑"按钮\*\*，方可激活编辑模式并显示工具栏。再次点击可退出编辑模式，预览区恢复只读状态。

**English** — A true WYSIWYG experience with no coding required. Select text to adjust styles (bold, italic, underline, strikethrough), switch heading levels (H1/H2/H3), and change alignment. Insert images, local videos, online videos, and hyperlinks directly.

> ⚠️ **Note**: After opening an HTML file, click the **"Edit" button** in the sidebar to activate editing mode and show the toolbar. Click it again to exit editing mode and return to read-only preview.

### 📄 源码编辑 / Source Code Editing

**中文** — 420px 宽的代码编辑面板，等宽字体排版，修改后预览区实时更新。满足技术用户对每一行代码的精细控制需求。

**English** — A 420px code editing panel with monospace font and real-time preview updates. Gives technical users fine-grained control over every line of code.

### 🔍 预览与缩放 / Preview & Zoom

**中文** — CSS transform 实现流畅缩放（25% — 300%，每次 ±10%），一键 1:1 复位，不影响编辑操作。

**English** — Smooth CSS transform-based zoom (25% — 300%, ±10% per step). One-click 1:1 reset. Does not interfere with editing.

### 📊 幻灯片导航 / Slide Navigation

**中文** — 自动识别 HTML 中的幻灯片标记，支持 7 种标记方式（`.slide`、`.slide-page`、`.page`、`section`、`article`、`data-slide`、`data-page`），顶栏实时显示当前位置。

**English** — Automatically detects slide markers in your HTML. Supports 7 marker types: `.slide`, `.slide-page`, `.page`, `section`, `article`, `data-slide`, `data-page`. The top bar shows your current position in real time.

### 🎬 全屏演示模式 / Fullscreen Presentation

**中文** — 隐藏所有 UI 的沉浸式演示体验，纯黑背景 + 浮动控制条，支持键盘导航（← → ↑ ↓ Space Home End），所有 CSS 动效流畅呈现。退出后自动恢复侧边栏状态。

**English** — An immersive presentation mode that hides all UI. Pure black background with floating controls. Keyboard navigation (← → ↑ ↓ Space Home End) and smooth CSS animations throughout. Sidebar state restores automatically on exit.

### 📥 文件操作 / File Operations

**中文**

- 点击按钮或快捷键 Ctrl+O 打开
- 空白状态点击中央按钮
- **Pro 版**：从 URL 加载（SSRF 防护 + 反爬检测 + 频率限制）
- 一键保存（Ctrl+S），保存时自动移除预览水印

**English**

- Open via button click or Ctrl+O shortcut
- Click the center button in blank state
- **Pro**: Load from URL (with SSRF protection, anti-scraping detection, rate limiting)
- One-click save (Ctrl+S) — preview watermarks are automatically removed

### 🎨 主题管理 / Theme Management

**中文** — 内置多套精美主题（Corporate Clean、Tokyo Night、Academic Paper、Catppuccin Latte、Minimal White 等），一键切换全局风格。

**English** — Multiple built-in beautiful themes: Corporate Clean, Tokyo Night, Academic Paper, Catppuccin Latte, Minimal White, and more. Switch the entire look with one click.

### 📋 页眉页脚管理 / Header & Footer Management

**中文** — 统一管理演示文稿的页眉页脚信息，支持编辑 HTML 源码进行精细调整。

**English** — Centrally manage header and footer content across your presentation. Supports HTML source editing for detailed customization.

### 🖼️ 媒体管理 / Media Management

**中文** — 支持插入和管理图片、视频文件、在线视频等多媒体元素。

**English** — Insert and manage images, video files, online videos, and other multimedia elements.

### 📤 导出功能 / Export

**中文** — 导出为纯净 HTML 文件，不含任何编辑器痕迹，接收方在任何浏览器中都能直接打开。

**English** — Export to a clean HTML file with no editor artifacts. Recipients can open it in any browser instantly.

***

## 免费试用 / Free Trial

### Free 版（永久免费） / Free Edition (Forever Free)

**中文**

| 功能       | 说明                      |
| :------- | :---------------------- |
| HTML 编辑器 | ✅ 完整可视化编辑               |
| 实时预览     | ✅                       |
| 源码编辑     | ✅                       |
| 文件保存     | ✅                       |
| 导出 HTML  | ✅                       |
| 每日页数限制   | 50 页/天（足以满足日常编辑需求,0点重置） |
| 许可证激活    | 无需任何操作，开箱即用             |

Free 版已覆盖大部分日常编辑场景，下载即可使用，无需注册、无需联网、无需激活。

**English**

| Feature             | Description                                       |
| :------------------ | :------------------------------------------------ |
| HTML Editor         | ✅ Full WYSIWYG editing                            |
| Live Preview        | ✅                                                 |
| Source Code Editing | ✅                                                 |
| File Save           | ✅                                                 |
| Export HTML         | ✅                                                 |
| Daily Page Limit    | 50 pages/day (sufficient for daily editing needs) |
| License Activation  | None required — works out of the box              |

The Free edition covers most everyday editing scenarios. Download and use immediately — no registration, no internet, no activation needed.

### Pro 版（激活解锁） / Pro Edition (Activation Required)

**中文**

| 功能       | 说明            |
| :------- | :------------ |
| 无限页数     | 解除 50 页/天限制   |
| 从 URL 加载 | 输入网址直接抓取 HTML |
| 主题持久化    | 主题选择自动保存      |
| 媒体拖拽     | 拖拽自定义媒体尺寸     |

**English**

| Feature           | Description                        |
| :---------------- | :--------------------------------- |
| Unlimited Pages   | Remove the 50-page/day limit       |
| Load from URL     | Enter a URL to fetch HTML directly |
| Theme Persistence | Auto-save theme selection          |
| Media Drag & Drop | Drag to customize media dimensions |

***

## 下载与安装 / Download & Install

### Windows

**中文**

1. 从发布页下载 `.msi` 或 `.exe` 安装包
2. 双击运行安装程序
3. **系统保护提示**：Windows SmartScreen 可能弹出"Windows 保护了你的电脑"警告，这是因为软件暂无数字签名证书。点击 **"更多信息"** → 选择 **"仍要运行"** 即可继续安装
4. 安装完成后，从桌面快捷方式或开始菜单启动

**English**

1. Download the `.msi` or `.exe` installer from the release page
2. Double-click to run the installer
3. **Security notice**: Windows SmartScreen may show "Windows protected your PC" warning, as the software does not yet have a digital signature certificate. Click **"More info"** → select **"Run anyway"** to proceed with installation
4. Launch from the desktop shortcut or Start menu after installation

### macOS

**中文**

1. 从发布页下载 `.dmg` 安装包
2. 双击打开 DMG 文件，将应用图标拖入 Applications（应用程序）文件夹
3. **首次运行提示**：macOS Gatekeeper 会阻止未签名的应用直接运行，可能提示"无法验证开发者"。此时请：
   - 打开 **系统设置 → 隐私与安全性**
   - 向下滚动找到安全区域，点击 **"仍要打开"** 按钮
   - 在弹出的确认对话框中再次点击 **"仍要打开"**
   - 或者直接在 Finder 中右键应用 → 选择 **"打开"**，然后在弹出的警告中选择 **"仍要打开"**
4. 后续启动时不再拦截

**English**

1. Download the `.dmg` package from the release page
2. Double-click to open the DMG file and drag the app icon into the Applications folder
3. **First launch notice**: macOS Gatekeeper will block unsigned apps from running, showing "cannot verify the developer". To bypass:
   - Go to **System Settings → Privacy & Security**
   - Scroll down to the security section and click the **"Open Anyway"** button
   - Click **"Open Anyway"** again in the confirmation dialog
   - Alternatively, right-click the app in Finder → select **"Open"**, then choose **"Open"** in the warning dialog
4. Subsequent launches will not be blocked

### Linux

**中文**

1. 从发布页下载 `.AppImage` 或 `.deb` 安装包
2. **AppImage 方式**：
   - 赋予执行权限：`chmod +x Html-PPT-Editor*.AppImage`
   - 双击运行或终端执行
   - 如果系统提示"无法执行"，请右击文件 → 属性 → 权限 → 勾选"允许作为程序执行文件"
3. **Deb 方式**：双击 `.deb` 文件或使用 `sudo dpkg -i *.deb` 安装
4. 从应用菜单或终端启动

**English**

1. Download the `.AppImage` or `.deb` package from the release page
2. **AppImage method**:
   - Set executable permission: `chmod +x Html-PPT-Editor*.AppImage`
   - Double-click or run from terminal
   - If blocked, right-click the file → Properties → Permissions → check "Allow executing file as program"
3. **Deb method**: Double-click the `.deb` file or install with `sudo dpkg -i *.deb`
4. Launch from the application menu or terminal

***

## 快速上手 / Quick Start

**中文**

1. 启动软件后，导入 HTML 演示文稿文件
2. 点击侧边栏的 **"编辑"** 按钮，进入可视化编辑模式
3. 在预览区直接选中并修改文字内容、调整样式
4. 点击 **"保存"**（Ctrl+S），文件将自动移除预览水印
5. 点击 **"全屏演示"** 或导出 HTML 分享给他人

**English**

1. Launch the software and import an HTML presentation file
2. Click the **"Edit"** button in the sidebar to enter visual editing mode
3. Select and modify text content directly in the preview area
4. Click **"Save"** (Ctrl+S) — preview watermarks are automatically removed
5. Click **"Fullscreen Presentation"** or export HTML to share with others

***

## 平台支持 / Platform Support

**中文**

| 操作系统    |           支持情况           |
| :------ | :----------------------: |
| Windows |     ✅ 原生安装（NSIS 安装器）     |
| macOS   |       ✅ 原生安装（DMG 包）      |
| Linux   | ✅ 原生安装（AppImage / deb 包） |

**English**

| OS      |               Support               |
| :------ | :---------------------------------: |
| Windows |      ✅ Native installer (NSIS)      |
| macOS   |       ✅ Native installer (DMG)      |
| Linux   | ✅ Native installer (AppImage / deb) |

***

## 联系我们 / Contact

**中文**

- 联系邮箱：<D-logix@outlook.com>
- GitHub：github.com/FYLS9527

**English**

- Email: <D-logix@outlook.com>
- GitHub: github.com/FYLS9527

***

*Html-PPT-Editor by FYLS9527 — 让 AI 生成演示文稿变得简单、安全、专业 | Making AI-generated presentations simple, secure, and professional*
