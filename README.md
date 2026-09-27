# Werd

Installers and updates for Werd, a local development environment for Laravel and PHP on Windows, macOS and Linux.

Download the installer for your system from the [latest release](https://github.com/JustFlavio/werd-releases/releases/latest). Werd updates itself afterwards: when a new version is out, an update button appears at the bottom of the sidebar.

| System | File |
| --- | --- |
| Windows 10/11 (x64) | `Werd_<version>_x64-setup.exe` |
| macOS (Apple Silicon) | `Werd_<version>_aarch64.dmg` |
| Ubuntu / Debian (x64) | `Werd_<version>_amd64.deb` or `Werd_<version>_amd64.AppImage` |

## First launch of an unsigned build

Werd is not code-signed yet, so the systems warn before the first start.

- **Windows:** SmartScreen shows "Windows protected your PC". Choose **More info → Run anyway**.
- **macOS:** right-click Werd in Applications and choose **Open**, then **Open** again. Or run `xattr -dr com.apple.quarantine /Applications/Werd.app` once.
- **Linux (AppImage):** `chmod +x Werd_*.AppImage` before starting it.

This repository only hosts releases; it contains no source code.
