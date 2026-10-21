# Lean-Cut for Windows

This repository contains Windows installers and update metadata. The application
source is maintained separately.

Download the latest installer from [Releases](https://github.com/siemenvgemert/lean-cut-releases/releases/latest).
Requires Windows 10/11 x64 and a Vulkan-capable graphics driver.

Install once, then open **Lean-Cut** using the desktop or Start menu shortcut.
The shortcut checks for stable updates and installs a newer version before
opening the app. If the app is already open, updates wait until a later launch.
The installed app continues to work offline. No GitHub login is required.

Projects and settings are kept outside the program directory and survive
updates and uninstalling. Updates are downloaded over HTTPS and checked against
the release's SHA-256 manifest. The installer is currently unsigned.

Only versioned installers, checksums, update metadata and release automation
belong in this repository. Application sources and credentials must not be copied here.
