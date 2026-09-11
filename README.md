<div align="center">

# 🌀 Debian for WSL

### Debian 13 & Debian 14 for Windows Subsystem for Linux

Run a clean Debian base inside **WSL2**, then build the desktop environment you want — GNOME, KDE Plasma, XFCE, Cinnamon and more.

[![Debian](https://img.shields.io/badge/Debian-WSL-A81D33?logo=debian&logoColor=white)](https://www.debian.org/)
[![WSL2](https://img.shields.io/badge/WSL2-Ready-0078D4?logo=windows&logoColor=white)](https://learn.microsoft.com/windows/wsl/)
[![Release](https://img.shields.io/github/v/release/vinberg88/debian?label=Release)](https://github.com/vinberg88/debian/releases/latest)
[![GitHub](https://img.shields.io/badge/GitHub-vinberg88-181717?logo=github)](https://github.com/vinberg88)

</div>

---

## 🐧 About the project

This project provides ready-to-install Debian base distributions for **Windows Subsystem for Linux (WSL2)**.

The goal is to keep the base installation clean and let you decide which desktop environment and applications you want to install.

| Distribution | Release | WSL Base |
|---|---|---|
| **Debian 13 — Trixie** | Stable | ✅ Ready |
| **Debian 14 — Forky** | Testing | ✅ Ready |

Both distributions are designed for WSL2 with **systemd**, Windows interoperability and support for graphical Linux applications.

---

## 📥 Download

### ➜ [Download Debian for WSL](https://github.com/vinberg88/debian/releases/latest)

Current images:

```text
Debian13-WSL-Base-0.1.0-x86_64.wsl
Debian14-WSL-Base-0.1.2-x86_64.wsl
```

Download the `.wsl` file and open it from Windows to begin the installation.

Keep Debian updated with:

```bash
sudo apt update
sudo apt dist-upgrade
```

---

# 🖥️ Desktop Environments

One of the main goals of this project is experimenting with complete Linux desktop environments running on Debian under WSL.

Each desktop section can include:

- 🖼️ Screenshot
- 📖 Installation guide
- ⚙️ WSL configuration
- 🔊 Audio setup
- 🪟 X410 / WSLg information
- ▶️ YouTube demonstration

---

## GNOME

GNOME provides a modern and clean Linux desktop with excellent integration and a large ecosystem of applications.

📖 **Installation guide — coming soon**  
▶️ **YouTube video — coming soon**

---

## KDE Plasma

KDE Plasma is a powerful and highly customizable desktop environment and works especially well when experimenting with full Linux desktops under WSL.

📖 **Installation guide — coming soon**  
▶️ **YouTube video — coming soon**

---

## XFCE

XFCE is lightweight, fast and a good choice if you want a traditional Linux desktop without using too many resources.

📖 **Installation guide — coming soon**  
▶️ **YouTube video — coming soon**

---

## Cinnamon

Cinnamon offers a familiar desktop layout with a traditional panel, application menu and highly configurable desktop.

📖 **Installation guide — coming soon**  
▶️ **YouTube video — coming soon**

---

## 🚧 More desktops coming

More desktop environments will be tested and documented here.

**Deepin · Budgie · MATE · LXQt · LXDE · COSMIC · Enlightenment**

---

## 📂 Planned repository structure

```text
debian/
├── README.md
│
├── docs/
│   ├── gnome.md
│   ├── kde-plasma.md
│   ├── xfce.md
│   └── cinnamon.md
│
└── images/
    └── desktops/
        ├── gnome.png
        ├── kde-plasma.png
        ├── xfce.png
        └── cinnamon.png
```

This keeps the main README clean while detailed installation instructions can live in separate guides.

---

## 🐧 About Debian

Debian is one of the oldest and most influential Linux distributions.

First released in **1993**, Debian is known for stability, security, its huge software repository and its strong commitment to free and open-source software.

Debian is also the foundation for many other Linux distributions including Ubuntu, Linux Mint, MX Linux, Kali Linux and many others.

Learn more at **[debian.org](https://www.debian.org/)**.

---

## ⭐ Project goal

> **Take Debian + WSL2 and see how far we can push the Linux desktop experience on Windows.**

More desktops, installation guides, screenshots and videos will be added as the project develops.

---

<div align="center">

### Debian + WSL2 + Linux Desktop 🐧 ❤️ 🪟

Created and maintained by **[vinberg88](https://github.com/vinberg88)**

*Community project — not affiliated with Debian or Microsoft.*

</div>
