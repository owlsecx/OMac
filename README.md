# 🦉 OMac

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-ONetwork-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OMac** — Professional MAC Address Management Suite

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OMac is a MAC address management suite for Debian-based Linux. It spoofs, restores, rotates, and analyzes MAC addresses, with ghost/burn modes, history, profiles, NetworkManager integration, live monitor, and export. CLI flags cover interface selection, vendor/OUI presets, and dry-run/permanent options.

---

## ✨ Features

- Spoof a MAC on a target interface (`--mac` or random) with optional real OUI / vendor preset
- Restore, rotate, ghost, and burn modes for temporary or aggressive MAC changes
- Analyze a MAC string; scan and live-monitor interface traffic/state
- History tracking and export to JSON or CSV; profile save/load actions
- NetworkManager-aware permanent change option and dry-run / force / no-confirm controls
- Interval and timer knobs for rotate/monitor workflows

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OMac -i eth0 -m random -r
./OMac --restore eth0
./OMac --analyze aa:bb:cc:dd:ee:ff --export json
./OMac --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
