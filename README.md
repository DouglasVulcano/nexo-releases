<p align="center">
  <img src="assets/icon.png" width="96" alt="Nexo" />
</p>

<h1 align="center">Nexo</h1>

<p align="center">
  A desktop development environment for <a href="https://github.com/anthropics/claude-code">Claude Code</a>.
  <br/>
  Windows · Linux · macOS, with first-class support for <a href="https://learn.microsoft.com/windows/wsl/">WSL</a>.
</p>

<p align="center">
  <a href="https://github.com/DouglasVulcano/nexo-releases/releases/latest"><img src="https://img.shields.io/github/v/release/DouglasVulcano/nexo-releases?label=version&color=f2762e" alt="Latest version" /></a>
  <a href="https://github.com/DouglasVulcano/nexo-releases/releases"><img src="https://img.shields.io/github/downloads/DouglasVulcano/nexo-releases/total?label=downloads&color=47848F" alt="Downloads" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-proprietary-555.svg" alt="Proprietary License" /></a>
  <img src="https://img.shields.io/badge/platforms-Windows%20%C2%B7%20Linux%20%C2%B7%20macOS-555" alt="Platforms" />
</p>

<p align="center">
  <strong>English</strong> · <a href="README.pt-BR.md">Português</a>
</p>

---

> This is the official **distribution** channel for Nexo. It hosts only the installers and the auto-update metadata.

## About

**Nexo** is a desktop development environment built for people working with [Claude Code](https://github.com/anthropics/claude-code). It brings the AI-agent development workflow together in one place: fast, integrated and cross-platform, with first-class support for [WSL](https://learn.microsoft.com/windows/wsl/) on Windows.

## Download and install

Download the installer for your platform from the **[releases page](https://github.com/DouglasVulcano/nexo-releases/releases/latest)**.

### Windows

1. Download `Nexo-Setup-x.y.z.exe` and run it.
2. On first launch, SmartScreen may show "unknown publisher" (the app is not signed yet): click **More info → Run anyway**.

### Linux

- **AppImage** (recommended, with automatic updates):
  ```bash
  chmod +x Nexo-x.y.z.AppImage
  ./Nexo-x.y.z.AppImage
  ```
- **Debian/Ubuntu (.deb):**
  ```bash
  sudo dpkg -i nexo_x.y.z_amd64.deb
  ```

### macOS

1. Open `Nexo-x.y.z.dmg` and drag Nexo into Applications.
2. Since the app is not notarized yet, the first time right-click → **Open** and confirm.

## Automatic updates

Nexo **updates itself**: on launch it checks for new versions here in the releases repository and notifies you when one is available. You decide when to **download** and then **restart** to apply; nothing is installed silently. (Windows and Linux AppImage support automatic updates; `.deb` packages are updated by the system package manager.)

## Support

Found a problem or have a suggestion? Open an **[issue](https://github.com/DouglasVulcano/nexo-releases/issues)** in this repository.

## License

Nexo is proprietary software, licensed and not sold. Redistribution, resale,
decompilation and reverse engineering are not permitted. Use is subject to the
[End User License Agreement](LICENSE) and, for paid features, an active
subscription.

---

<sub>Nexo is an independent project and is not affiliated with Anthropic. "Claude" and "Claude Code" are trademarks of Anthropic.</sub>
