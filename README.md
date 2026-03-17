# Bad Sector 👾

[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
[![Flame](https://img.shields.io/badge/Flame-Engine-FF6600?style=for-the-badge)](https://flame-engine.org)
[![iOS](https://img.shields.io/badge/iOS-13%2B-000000?style=for-the-badge&logo=apple&logoColor=white)](https://apps.apple.com/mx/app/bad-sector/id6758281840)
[![App Store](https://img.shields.io/badge/App_Store-Descargar-0D96F6?style=for-the-badge&logo=app-store&logoColor=white)](https://apps.apple.com/mx/app/bad-sector/id6758281840)

> A retro pixel-art arcade game where you pilot a digital core through a corrupted CRT system — collecting hertz frequencies while surviving deadly scanlines and glitch entities.

---

## 🎮 About the Game

**Bad Sector** is an arcade survival game set inside a corrupted cathode-ray monitor. You control **CORE.EXE**, a white pixel navigating a black screen filled with hostile system errors.

The main threat is the **REFRESH scanline** — a green beam that sweeps the screen at increasing speed with every hertz you collect. Touch it and it's game over. Your only tools are movement, a **stealth phase mechanic** (hold to become invisible and pass through the scanline), and power-ups that appear as you progress.

As your score climbs, the system degrades further: glitch entities spawn, a magnetic field pulls you off course, and the scanline accelerates relentlessly. How many hertz can you collect before the system crashes?

---

## ✨ Features

### 🕹️ Core Mechanics
- **Drag to move** — fluid touch controls using pan gestures
- **Hold to phase** — tap and hold to enter stealth mode and avoid the scanline
- **Progressive speed** — the scanline accelerates with every hertz collected

### ⚡ Power-Ups
- **FIREWALL (Shield)** — absorbs one fatal scanline hit before breaking, with particle explosion effect
- **LAG_SWITCH (Time Dilation)** — slows the entire game world for 5 seconds, giving you breathing room

### 👾 Enemy Types
- **REFRESH** — the main scanline, sweeps vertically at increasing speed
- **BURN-IN (Dead Pixel)** — solid cyan block that physically repels the player
- **WHITE NOISE (Static)** — vibrating interference circle with soft push
- **MAGNET** — pulls the player toward it with increasing force the closer you get

### 🎯 Difficulty System
- Score-based enemy spawning: glitches appear every 2 hertz collected
- Enemy variety unlocks progressively (Burn-In → White Noise → Magnet)
- Alert messages warn the player at key difficulty thresholds

### 📺 Visual & Audio Design
- Custom **CRT effect** with scanline overlay, vignette, and phosphor green tint
- Pixel particle system for hertz collection, shield breaks, and game over
- Retro **BIOS boot sequence** on startup with animated diagnostic screens
- Photosensitivity warning screen before gameplay
- Chiptune audio with toggle mute support

### 📱 Platform & Monetization
- Portrait mode, optimized for iPhone
- **Google AdMob** — banner ads and interstitial ads (shown every 4 games)
- **App Tracking Transparency** — iOS 14+ compliant
- High score persistence via SharedPreferences
- Haptic feedback on collection, shield break, and game over

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| **Flutter** | UI framework |
| **Dart** | Programming language |
| **Flame Engine** | 2D game engine |
| **flame_audio** | Sound effects & background music |
| **google_mobile_ads** | AdMob integration |
| **shared_preferences** | High score persistence |
| **app_tracking_transparency** | iOS ATT compliance |
| **url_launcher** | Privacy policy & EULA links |

---

## 📱 Download

<a href="https://apps.apple.com/mx/app/bad-sector/id6758281840">
  <img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on App Store" height="50"/>
</a>

---


## 👨‍💻 Developer

**regioc3pi0**
- GitHub: [@regioc3pi0](https://github.com/regioc3pi0)

---

## 📄 License

This project is proprietary software. The source code is private.  
All rights reserved © 2025
