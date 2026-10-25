# Figora — Professional Mobile IDE

![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)
![Version](https://img.shields.io/badge/Version-2.0-5B8DEF)
![License](https://img.shields.io/badge/License-Proprietary-lightgrey)
![Status](https://img.shields.io/badge/Status-Stable-4ADE80)

> A complete, on-device Integrated Development Environment for Android. Build, edit, run, debug, and export Android & web projects directly from your phone or tablet — no PC required.

---

line 10

## ✨ Overview

**Figora** is a powerful, portable, and fully offline-capable mobile IDE designed for developers who want to code anywhere. It combines a modern code editor, a built-in web server, a visual GUI designer, an API tester, and a complete Android build toolchain into a single application.

Whether you are a beginner learning to code or a professional shipping production apps, Figora puts a full development workflow in your pocket.

---

## 🚀 Key Features

### 📱 Portable & Free
Designed to be simple, lightweight, and portable. Code and manage your projects anytime, anywhere — completely free.

### 🧠 Smart Code Editor
- Syntax highlighting for **HTML, CSS, JavaScript, Java, Kotlin, XML, JSON**, and more
- Code completion, bracket matching, and auto-indentation
- Multiple tabs, word-wrap, line numbers, and pin-line support
- Dark & light themes with customizable font size
- Find & replace across files

### 🌐 Built-in Web Server
- Localhost HTTP server to preview websites instantly
- Share your site over Wi-Fi / internet via IP interfaces
- Access from any device on the same network

### 🐞 Debug Console
- Built-in terminal/console to run commands
- Quick troubleshooting and log inspection
- Crash reports captured automatically and viewable in-app

### 🐙 GitHub Integration
- Clone repositories directly into the IDE
- Download files and resources from GitHub and other sources
- Import existing projects seamlessly

### 🧪 API Testing
- Test REST endpoints with **GET, POST, PUT, DELETE** and more
- Add headers, query params, and request bodies
- View detailed response logs, status codes, and headers

### 🖥️ Responsive Design Emulator
- Test website responsiveness across multiple screen sizes
- Emulate different devices and resolutions
- Ensure a seamless experience on every screen

### 🎨 GUI Editor
- Visual, drag-and-drop interface editor
- Build layouts without writing code
- Export generated code into your project

### 📦 Android Build & Export
- Compile Android projects on-device (ECJ + D8)
- Sign APKs with keystore support
- Export signed/unsigned APKs ready to install or share
- Project backup and restore

### 🗂️ Project Management
- Create, open, rename, and delete projects
- File & folder explorer with search
- Recent projects and quick-open
- Store & browse community projects

### 🌍 Additional Tools
- IP interfaces manager
- Documentation browser
- WebView browser with dev-tools
- Screen size emulator
- Request/API playground

---

## 📥 Download & Installation

Figora is distributed as an **APK** file. Source code is not included in this repository.

### Requirements
- Android **7.0 (API 24)** or higher
- ~100 MB free storage
- Internet connection for cloning/downloading (optional for offline coding)

### Install
1. Download the latest `Figora.apk` from the **Releases** section.
2. Enable **"Install from unknown sources"** in your Android settings (if prompted).
3. Open the APK and tap **Install**.
4. Launch **Figora** and grant storage permissions.

> ⚠️ Only install APKs from trusted sources. Verify the file checksum published with each release.

---

## 🏁 Getting Started

1. **Launch the app** — you will land on the Home screen.
2. Tap **New Project** to create a project, or **Open Existing Project** to browse your files.
3. Use the file explorer to navigate and edit files in the Code Editor.
4. Tap **Run / Build** to compile and preview your app or website.
5. Use **Export** to generate a signed APK.

### Quick Tips
- Long-press files for rename / delete / new file options.
- Use the **Debug Console** for quick commands and logs.
- Test APIs in the **Request** screen before integrating them.
- Preview responsive layouts with the **Screen Emulator**.

---

## 🛠️ Supported Languages & Tools

| Category | Support |
|---|---|
| Web | HTML, CSS, JavaScript, JSON |
| Android | Java, Kotlin, XML, Gradle (basic) |
| Editor | Syntax highlighting, completion, themes |
| Server | Localhost HTTP, IP sharing |
| Build | On-device compile, D8 dexing, APK signing |

---

## 📸 Screenshots

> _Screenshots will be added in upcoming releases._

| Home | Editor | Web Server |
|---|---|---|
| ![Home](docs/screenshots/home.png) | ![Editor](docs/screenshots/editor.png) | ![Server](docs/screenshots/server.png) |

---

## ❓ FAQ

**Q: Is an internet connection required?**
A: No. Coding, editing, and building work fully offline. Internet is only needed for cloning repos, downloading resources, or API testing.

**Q: Can I build real Android apps?**
A: Yes. Figora includes an on-device Java compiler and D8 dexer to produce installable APKs.

**Q: Where are my projects stored?**
A: Projects are stored in the app's private storage under `Projects/`. You can export or back them up manually.

**Q: The app crashed — what do I do?**
A: Open the **Debug Report** screen to view the stack trace, or use the in-app "Send Bug Report" button to email it to support.

---

## 📞 Contact & Support

- **Website:** https://websiteide.web.app
- **Email:** hrprojects38@gmail.com
- **Issues / Feedback:** Use the in-app **Debug Report → Send Bug Report** feature.

---

## 📝 Changelog

### v2.0
- Complete UI/UX overhaul with professional dark enterprise theme
- Added project search & filtering
- Added About dialog with version/device info
- Improved download service (progress, error handling, cleanup)
- Improved input validation across screens
- Stability and performance improvements

---

## ⚖️ License

This software is distributed as a compiled APK. **Source code is not provided.** All rights reserved by the author.

Redistribution of the APK is permitted only via the official release channels. Reverse engineering, decompilation, or modification is not allowed.

---

## 🙏 Acknowledgements

Built with love for developers who code on the go. Special thanks to the open-source libraries that power Figora's editor and tooling.

---

*Happy Coding! — The Figora Team*
