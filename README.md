<p align="center">
  <img src="assets/logo-with-background-large.png" alt="AlphaOS Logo" height="200">
</p>

<h1 align="center">AlphaOS</h1>
<h3 align="center">Your Custom Ubuntu-Based Linux Distro with a Sleek Purple Theme</h3>

<div align="center">
  
[![GPL-3.0 License](https://img.shields.io/badge/License-GPLv3-purple.svg)](LICENSE)
[![GitHub Release](https://img.shields.io/github/v/release/ax10mdev/AlphaOS?color=%236A1B9A)](https://github.com/ax10mdev/AlphaOS/releases)
[![Discord](https://img.shields.io/discord/1234567890?label=Community&logo=discord&color=7289DA)](https://discord.gg/alphaos)
[![ISO Size](https://img.shields.io/badge/ISO_Size-2.4GB-purple)](https://alphaos.org/download)
[![Website](https://img.shields.io/website?url=https%3A%2F%2Fsites.google.com%2Fview%2Falpha-os%2Fmain)](https://sites.google.com/view/alpha-os/main)

</div>

![AlphaOS Desktop Showcase](assets/showcase.png)

## 🚀 Features

### 🎨 Stunning Visual Design
- AlphaPurple theme (#6A1B9A) across all UI elements
- Custom icon pack with purple accents
- Dynamic light/dark mode switching
- Animated application launcher
- Custom GRUB and Plymouth boot screens

### ⚡️ Performance Optimizations
- Streamlined kernel (6.5.x) with custom scheduler
- Reduced background services (30% fewer than stock Ubuntu)
- Faster boot times (under 15s on SSD)
- Memory efficiency (uses 30% less RAM than Ubuntu)

### 🛠 Pre-Installed Tools
| Tool | Description | Usage Example |
|------|-------------|---------------|
| Timeshift | System restore/snapshot tool | sudo timeshift --create |
| Stacer | System optimizer and monitor | stacer |
| Neofetch | Custom terminal system info | neofetch --ascii_distro AlphaOS |
| Cubic | ISO customization tool | sudo cubic |

## 📥 Download

Latest Stable Release: AlphaOS 24.4 "Infinity"  
*Released: April 2024*

🔗 [Download ISO (2.4GB)](https://alphaos.org/download)  
🔗 [Torrent Mirror](magnet:?xt=urn:btih:...)  
🔗 [Alternative Mirrors](docs/MIRRORS.md)

Verification:
echo "a1b2c3d4e5f6... AlphaOS-24.4.iso" | sha256sum --check
### System Requirements
| Component | Minimum | Recommended |
|-----------|---------|-------------|
| CPU | 64-bit dual-core | Quad-core or better |
| RAM | 4GB | 8GB+ |
| Storage | 25GB | 50GB SSD |
| GPU | OpenGL 3.3+ | Vulkan compatible |

## 🖥 Screenshots

<div align="center">
  <img src="assets/screenshots/desktop.png" alt="Desktop" width="45%">
  <img src="assets/screenshots/menu.png" alt="App Menu" width="45%">
  <img src="assets/screenshots/terminal.png" alt="Terminal" width="45%">
  <img src="assets/screenshots/settings.png" alt="Settings" width="45%">
</div>

## 📦 Installation Guide

# Create bootable USB (Linux/macOS)
dd if=AlphaOS-24.4.iso of=/dev/sdX bs=4M status=progress && sync

# Windows users can use Rufus or BalenaEtcher
1. Boot from USB/DVD
2. Select "Install AlphaOS"
3. Follow the graphical installer
4. Reboot and enjoy!

[📚 Full Installation Guide](docs/INSTALL.md) | [🛠 Troubleshooting](docs/TROUBLESHOOTING.md)

## 🤝 Contributing

# Development setup
git clone https://github.com/ax10mdev/AlphaOS.git
cd AlphaOS
./configure --prefix=/usr
make
Ways to contribute:
- 🐛 [Report Bugs](https://github.com/ax10mdev/AlphaOS/issues)
- 💡 [Suggest Features](https://github.com/ax10mdev/AlphaOS/discussions)
- 📝 Improve [Documentation](docs/)
- 🌍 Help with [Translations](https://github.com/ax10mdev/AlphaOS/tree/main/po)

[📜 Contribution Guidelines](docs/CONTRIBUTING.md)

## 🌐 Community

<div align="center">
  
[![Discord](https://img.shields.io/discord/1234567890?label=Chat%20on%20Discord&logo=discord&style=for-the-badge&color=7289DA)](https://discord.gg/alphaos)
[![Forum](https://img.shields.io/badge/Official_Forum-alphaos.org-blue?style=for-the-badge)](https://forum.alphaos.org)

</div>

- 🐦 [Twitter @alphaos_dev](https://twitter.com/alphaos_dev)
- 📺 [YouTube Tutorials](https://youtube.com/alphaos)
- 📰 [Blog Updates](https://alphaos.org/blog)

## 📜 License

AlphaOS is licensed under the GNU General Public License v3.0.  
See [LICENSE](LICENSE) for full details.

---

<div align="center">
  
💜 Made with passion by AXIOMDEV  
📆 Last Updated: October 2024  
🌍 [https://alphaos.org](https://alphaos.org)

</div>
