<div align="center">

# 🛰️ HeeSA Everwatch Signal System

### Free Network Intelligence System for Windows

<br>

<a href="README.md"><img src="https://img.shields.io/badge/🇬🇧_English-0A84FF?style=for-the-badge&labelColor=0B1220" alt="English"></a>
&nbsp;
<a href="README.fa.md"><img src="https://img.shields.io/badge/🇮🇷_فارسی-1F2937?style=for-the-badge&labelColor=0B1220" alt="Persian"></a>

<br><br>

![Platform](https://img.shields.io/badge/Platform-Windows-0078D4?style=flat-square&logo=windows&logoColor=white)
![C#](https://img.shields.io/badge/C%23-WPF-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![WebView2](https://img.shields.io/badge/UI-WebView2-00B7C3?style=flat-square&logo=microsoftedge&logoColor=white)
![Themes](https://img.shields.io/badge/Themes-Dark_·_Light_·_Glass-8B5CF6?style=flat-square)
![Languages](https://img.shields.io/badge/Docs-EN_·_FA-F59E0B?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-22C55E?style=flat-square)

<br>

[✨ Features](#-features) · [🧭 How it works](#-how-it-works) · [🚀 Getting started](#-getting-started) · [🗂️ Folder layout](#️-folder-layout) · [🛡️ Reliability](#️-reliability) · [📬 Contact](#-contact)

</div>

---

## 🌌 What is ESS?

**HeeSA Everwatch Signal System (ESS)** is a premium Windows network monitor built for people who need the *truth* about their connection, not a guess.

It measures ping, jitter, packet loss and speed on the **real physical adapter** (before any VPN), tells you instantly when the internet drops, shows exactly **which apps and destinations** use your data, and keeps a clean overlay on your screen, **even above fullscreen games**.

> 💡 One app. One glance. Complete awareness.

---

## ✨ Features

### 📡 Live Monitoring
| | Feature | Details |
|---|---|---|
| ⚡ | **Ping** | Measured on the real physical adapter, matching `cmd ping`, with no false timeouts |
| 📉 | **Packet Loss** | Fine decimal precision, not just rounded steps |
| 🌊 | **Jitter** | Stable, calm readings |
| ⬇️⬆️ | **DL / UL** | Always in Mbps, max 3 digits, updating smoothly |
| 🌐 | **Internet header** | Clean `Internet <IP>` status, or `Internet timeout` when the link is cut |

### 🖥️ ESS Overlay
- 📌 Always on top, **even above fullscreen apps**
- 🔄 Appears automatically at app start
- 🎛️ Live settings with **auto-persist**, no Save / Apply / Discard buttons
- 🎮 Game-server latency without false disconnects (UDP / TCP fallback)

### 🔔 Smart Alerts
- 🚨 **Instant disconnect detection** for the internal (domestic) internet
- 🧠 Losing `8.8.8.8` alone does **not** trigger a false alarm
- 🔁 Fast **IP change** alerts
- 🎉 Decorated startup notification: *iHeeSA+ · Network Intelligence System · is working*
- 🎨 Available in all alert themes

### 📊 Data Usage
- 🧩 **By application**, **By destination**, **By country**
- ✅ Real traffic only, even when a VPN is active (no duplicated services)
- 🗓️ Up to **5 years** of history using compact monthly files
- 🛰️ **ESS Service** records in the background, even when the app is closed

### 🗺️ Global Traffic Map
- 🌍 *Global Traffic Map By HeeSA* with an offline **Net DataBase**
- 🏷️ Adapter labels (LAN) / (USB) for physical adapters only

### 🕵️ IP · ISP · Location
- 🎯 Stable detection with few, ordered providers
- ☁️ Cloudflare trace + offline Net DataBase
- 🔒 No unreliable third-party flip-flopping

### 🧱 VPN / Proxy & Filter-Breaker Detection
- 🛡️ Detects VPN and proxy tools (e.g. Lantern, v2ray-type clients)
- ⏳ Hold and grace timers so the badge doesn't flicker
- 🧾 Detailed trace lines in the Crash Log for diagnosis

### 🧰 Tools
- 🚀 **Speed Test**: Cloudflare and Speedtest by Ookla (no installs per run)
- 🧭 **Ping & Trace**: full traceroute with real hop results

### 🎨 Themes
- 🌑 **Dark** · ☀️ **Light** · 🪟 **Glass** (real Windows Acrylic / Mica)

---

## 🧭 How it works

```
 ┌──────────────┐     ┌────────────────┐     ┌─────────────────┐
 │  Physical    │ ──▶ │   ESS Engine   │ ──▶ │  Overlay · Alerts│
 │  Adapter     │     │ ping·loss·DL/UL│     │  Monitoring · UI │
 └──────────────┘     └───────┬────────┘     └─────────────────┘
                              │
                      ┌───────▼────────┐
                      │  ESS Service   │  background recorder
                      │  Data Usage DB │  monthly files · 5 years
                      └────────────────┘
```

---

## 🚀 Getting started

1. 📥 Download the latest release and extract the **`HeeSA Everwatch Signal System`** folder.
2. ▶️ Run **`HeeSA Everwatch Signal System.exe`**.
3. 🪄 The overlay appears automatically. Open Settings to choose your theme and options.
4. 🟢 Enable **Start with Windows** and **Keep running in the tray** to let ESS quietly watch your network from boot.

**Requirements**
- 🪟 Windows
- 🌐 Microsoft Edge **WebView2 Runtime** (Evergreen)

> 📦 The program folder is **portable**: copy it to another PC and run it. It does not depend on files outside its folder.

---

## 🗂️ Folder layout

```
HeeSA Everwatch Signal System/
├── 🚀 HeeSA Everwatch Signal System.exe
├── 🗑️ Uninstall ESS.exe
└── …clean, grouped support folders
```

Only the main executable and the uninstaller are visible; runtime files are neatly grouped into a few clearly named folders.

---

## 🛡️ Reliability

- 🪵 One unified **Crash Log** (`ESS Crash Log.log`) with a **Crash Log.exe** viewer, built-in **Run diagnosis** and exportable crash reports
- 🧹 Clean **Uninstall ESS.exe**
- 🧊 Calm UI: no jumpy numbers, no false alarms

---

## 📬 Contact

| | |
|---|---|
| 💬 Telegram channel | [@HeeSA_Software](https://t.me/HeeSA_Software) |
| 👤 Telegram (private) | [@abolfazlhessari](https://t.me/abolfazlhessari) |
| 🐙 GitHub | [@HeeSA_Software](https://github.com/HeeSA_Software) |

---

<div align="center">

**Made with 💙 by HeeSA**

⭐ If ESS is useful to you, give the project a star!

<a href="README.fa.md">🇮🇷 مشاهده به فارسی</a>

</div>
