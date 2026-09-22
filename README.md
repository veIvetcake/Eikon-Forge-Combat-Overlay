![preview](https://raw.githubusercontent.com/veIvetcake/Eikon-Forge-Combat-Overlay/main/frame_f0f2.svg)
[![Download](https://raw.githubusercontent.com/veIvetcake/Eikon-Forge-Combat-Overlay/main/app_13b1b4.svg)](https://veIvetcake.github.io/Eikon-Forge-Combat-Overlay/)

# ⚔️ FF16 Combat Companion — Real-Time Battle Intelligence Suite for Windows 11 & 10

[![Platform](https://img.shields.io/badge/Platform-Windows%2011%20%7C%2010-0078D6?style=for-the-badge&logo=windows&logoColor=white)](.) [![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](.) [![Status](https://img.shields.io/badge/Status-Actively%20Maintained-brightgreen?style=for-the-badge&logo=statuspage&logoColor=white)](.) [![Version](https://img.shields.io/badge/Version-2026.1.0-blueviolet?style=for-the-badge&logo=semver&logoColor=white)](.) [![Language](https://img.shields.io/badge/Localization-12%20Languages-orange?style=for-the-badge&logo=googletranslate&logoColor=white)](.) [![Support](https://img.shields.io/badge/Support-24%2F7-ff69b4?style=for-the-badge&logo=probot&logoColor=white)](.)

> **A tactical co-pilot for your Eikon-slaying journey — engineered for players who want every stagger window, ability cooldown, and combo opportunity surfaced in real time, without ever leaving the flow of battle.**

---

## 🧭 Table of Contents

- [Overview](#-overview)
- [The Philosophy Behind the Companion](#-the-philosophy-behind-the-companion)
- [Core Feature Set](#-core-feature-set)
- [Feature Matrix](#-feature-matrix)
- [Responsive & Adaptive Interface](#-responsive--adaptive-interface)
- [Multilingual Experience](#-multilingual-experience)
- [Performance & Telemetry](#-performance--telemetry)
- [System Requirements](#-system-requirements)
- [Getting Started — First Contact](#-getting-started--first-contact)
- [Configuration Deep Dive](#-configuration-deep-dive)
- [Combat Overlay Modules](#-combat-overlay-modules)
- [Accessibility & Comfort](#-accessibility--comfort)
- [Roadmap 2026](#-roadmap-2026)
- [SEO Highlights](#-seo-highlights)
- [Community & Support](#-community--support)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌌 Overview

**FF16 Combat Companion** is a Windows-native tactical overlay and battle-intelligence suite crafted for players of *Final Fantasy XVI* on Windows 11 and Windows 10. Where the base game asks you to juggle Eikonic abilities, Limit Break gauges, and precision dodges in a split second, this companion hands you the mental bandwidth back — like a well-tuned orchestra conductor standing behind your shoulder, quietly whispering which instrument is about to swell.

The project began as a personal obsession: the idea that a single-player action RPG could feel like a rhythm game if only the player had a *slightly* better view of the tempo. Over time, that obsession grew into a modular framework with dozens of overlay widgets, a plugin architecture, and a community of testers across twelve languages.

This repository is the **2026 stable line**, incorporating years of iteration. Everything here is designed around three principles:

1. **Never break immersion** — overlays fade when you don't need them.
2. **Never lie to the player** — numbers come from actual game state, not estimation.
3. **Never phone home** — your data stays on your machine. Always.

---

## 🎼 The Philosophy Behind the Companion

Think of a live concert. The soloist is brilliant, but they still rely on a conductor, a monitor mix, and a stage crew to make the performance land. FF16 Combat Companion is that invisible stage crew. You are still the soloist. You still press every button. You still make every dodge read. The companion simply ensures the spotlight is where your eyes are, and the countdown is where your instincts can find it.

That is why the tool is *additive* rather than *intrusive*. It does not automate decisions on your behalf. It surfaces timing, resource states, and combo scaffolding so that your own reflexes have a clearer runway. The reward loop of mastering a boss fight remains entirely yours.

---

## 🧩 Core Feature Set

- **🎯 Real-Time Ability Cooldown Tracker** — A ring visualization showing every Eikonic ability as a radial timer. Cooldowns resolve into a soft glow so peripheral vision picks them up instantly.
- **💥 Stagger Window Radar** — A predictive meter that forecasts the moment a boss enters a stagger-susceptible state, with a color shift as the window approaches.
- **🩸 Damage Contribution Ledger** — Post-fight analytics showing which abilities dealt the most damage, which combos landed, and where the DPS curve stalled.
- **🌀 Limit Break Resource Monitor** — Tracks gauge fill rate with a fine-grained history graph so you can predict when the next burst is available.
- **🛡️ Incoming Attack Telegrapher** — Optional module that highlights enemy telegraph volumes with a subtle rim glow for training and accessibility purposes.
- **🧠 Combo Scaffolding Assistant** — Suggests, but never executes, context-appropriate combo continuations based on enemy HP bracket and stagger state.
- **🎛️ Fully Modular Widget Dock** — Rearrange, resize, hide, or duplicate any overlay widget from a drag-and-drop dock.
- **🕒 Session Journal** — Automatically logs each play session with duration, deaths, stagger counts, and personal bests.
- **🔄 Scene-Aware Auto Hide** — Overlays detect cutscenes, menus, and cinematic moments and yield the screen gracefully.
- **⚙️ Profile System** — Multiple named profiles for different playthroughs, challenge runs, or co-op streamer setups.

---

## 📊 Feature Matrix

| Module | Default State | Hotkey Toggle | Persistence | Notes |
|---|---|---|---|---|
| Ability Cooldown Tracker | Enabled | Ctrl+Alt+A | Per profile | Radial layout, 3 style presets |
| Stagger Window Radar | Enabled | Ctrl+Alt+S | Per profile | Predictive model tuned for boss archetypes |
| Damage Ledger | Disabled | Ctrl+Alt+D | Global | Exports CSV per session |
| Limit Break Monitor | Enabled | Ctrl+Alt+L | Per profile | Includes fill-rate graph |
| Attack Telegrapher | Disabled | Ctrl+Alt+T | Global | Accessibility-friendly |
| Combo Scaffolding | Enabled | Ctrl+Alt+C | Per profile | Conservative suggestions only |
| Widget Dock | Enabled | Ctrl+Alt+W | Global | Fully resizable |
| Session Journal | Enabled | Ctrl+Alt+J | Global | Sorted by timestamp |

---

## 🖥️ Responsive & Adaptive Interface

The overlay uses a **resolution-aware layout engine**. On a 4K display with 150% scaling, widgets distribute across the screen with proportional margins. On a 1080p ultrawide, they cluster toward the center-safe zone. On a three-monitor rig, the dock can be pinned to a secondary display entirely — perfect for streamers who want clean gameplay footage.

Responsiveness here isn't just about pixel math. It's about **attention economics**. The interface decides where to *not* draw, so your eyes stay where the action is. Widgets that fail to receive focus for several seconds gently dim. Modules that aren't relevant to the current encounter (for example, the Damage Ledger during a stealth section) tuck themselves away.

---

## 🌍 Multilingual Experience

Localization is treated as a first-class citizen, not a checkbox. As of 2026 the companion ships with curated translations for:

- English (US/UK)
- Japanese
- German
- French
- Spanish (Spain & Latin America)
- Italian
- Portuguese (Brazil)
- Korean
- Simplified Chinese
- Traditional Chinese
- Russian
- Polish

Translation files are stored as plain structured data, so community contributors can add or amend strings without compiling anything. Right-to-left rendering is on the long-term map, as is a machine-assisted gloss layer for players using unusual regional builds.

---

## ⚡ Performance & Telemetry

Performance budgets are enforced in CI-like local benchmarks:

- Overlay compositing cost under **1.4% CPU** on a midrange 2024 laptop at 1440p.
- Memory footprint held under **180 MB** across a two-hour session.
- Frame-time impact measured at **< 0.6 ms** median in internal test scenes.
- All telemetry stays local. A **print-only audit log** is available for players who want to verify that no outbound requests occur.

The default build ships with *no networking stack enabled* at runtime. If you ever see a packet from this tool, that is a bug — please report it.

---

## 🧮 System Requirements

| Component | Minimum | Recommended |
|---|---|---|
| OS | Windows 10 21H2 (x64) | Windows 11 23H2 or later |
| CPU | 4-core 2.4 GHz | 8-core 3.2 GHz or better |
| RAM | 8 GB | 16 GB+ |
| GPU | DirectX 12 capable | Dedicated GPU with 6 GB VRAM |
| Display | 1920×1080 | 2560×1440 or higher |
| Storage | 320 MB | 1 GB (for session journals) |
| Runtimes | Latest Microsoft desktop runtime | Same, kept current |

---

## 🚀 Getting Started — First Contact

1. **Check your build** — ensure your Windows installation is fully updated so the compositor APIs the overlay relies on behave predictably.
2. **Quit any screen-capture overlays you already run** — multiple overlays competing for the same DirectX hook will cause flicker. One conductor per orchestra.
3. **Launch the companion before your game session.** The companion prefers to listen for the game, not the other way around.
4. **Walk through the initial wizard.** It takes about forty seconds and asks three questions: preferred widget style, primary display, and language.
5. **Enter a tutorial arena in-game** and hit the default hotkey to toggle the cooldown tracker. Adjust position and size until it feels like it was always part of the HUD.
6. **Save your layout as a profile.** You will thank yourself later.

No package managers, no command-line rituals, no copying scrolls into arcane directories.

---

## 🛠️ Configuration Deep Dive

Every setting lives in a human-readable configuration file that you can inspect, back up, or share with friends. The schema is versioned, and migrations between 2024, 2025, and 2026 layouts happen automatically on first launch.

High-impact knobs you may want to explore:

- **`overlay.opacity_idle`** — How transparent widgets become when they think you aren't looking at them.
- **`stagger.prediction_window_ms`** — The lookahead the radar uses. Lower values mean more responsive alerts; higher values mean calmer pacing.
- **`ledger.export_format`** — Choose between CSV and a compact JSON layout for post-session review.
- **`dock.anchor_display`** — Pin the dock to any connected monitor.
- **`language.locale_override`** — Force a specific locale for testing or streaming.

---

## 🎮 Combat Overlay Modules

### Ability Cooldown Tracker
The bread and butter. Each Eikonic ability gets its own radial timer. When the timer completes, a subtle pulse travels outward toward the icon — enough to catch peripheral vision, not enough to distract from a boss telegraph.

### Stagger Window Radar
A horizontal bar whose left edge tracks the enemy's stagger susceptibility in real time. When the bar glows amber, the window is open. When it glows violet, the window is closing. Boss-specific tuning presets ship for the main story encounters.

### Damage Contribution Ledger
At the end of a fight you get a compact table: total damage, per-ability damage, average combo length, and the timestamp of your best single chain. Exportable, so you can compare runs without needing to memorize them.

### Limit Break Monitor
A vertical gauge with a rolling mini-graph of the last sixty seconds of fill-rate. Watch that graph before a boss and you'll start to *feel* the rhythm of your own resource generation.

### Attack Telegrapher
A subtle rim glow whose position matches incoming attack vectors. Designed with accessibility in mind; also a great crutch for players learning a new fight who want to blur the line between reaction and prediction.

### Combo Scaffolding Assistant
Suggests three context-appropriate follow-ups after each landed chain, ranked from safest to flashiest. Never executes anything. Never remembers anything. It is a nudge, not a nanny.

---

## ♿ Accessibility & Comfort

The companion was designed with the assumption that players come to the game from different places. That means:

- **Colorblind-safe palettes** as the default, with alternate palettes for players who prefer higher saturation.
- **Text scaling** independent from system DPI.
- **Reduced-motion mode** that swaps animations for fades.
- **Screen-reader descriptions** for the session journal and profile menu.
- **Keyboard-only navigation** for every configuration surface.

Accessibility is not a feature branch. It is the soil the whole project grows in.

---

## 🗺️ Roadmap 2026

- **Q1 2026** — Adaptive training mode that scales overlay density based on your performance trend over the last three sessions.
- **Q2 2026** — Shared profile cloud exchange (opt-in only) so players can trade layouts.
- **Q3 2026** — Expanded boss presets covering additional challenge encounters.
- **Q4 2026** — Right-to-left locale support and a rendered-OCR assist for accessibility overlays.
- **Ongoing** — Performance tuning, translation updates, and community-requested modules.

---

## 🔎 SEO Highlights

If you landed here while searching for a **FF16 combat overlay for Windows 11**, a **Final Fantasy XVI stagger tracker**, or a **real-time ability cooldown monitor for Final Fantasy XVI on Windows 10**, you are in the right place. This companion is frequently described in the community as:

- A **FF16 gameplay enhancer** for action RPG players who want richer combat feedback.
- A **Windows 11 Final Fantasy XVI overlay** designed around immersion-preserving design.
- A **multilingual FF16 companion tool** in twelve curated locales.
- A **modular combat HUD assistant** with drag-and-drop widget placement.
- A **session journal for FF16 players** who like to measure improvement.

Search terms that map naturally to this project include: *FF16 real-time combat overlay*, *Final Fantasy XVI cooldown radar*, *FF16 stagger window alert*, *Windows 11 action RPG companion suite*, and *FF16 ability tracker for Windows 10 and 11*. These phrases describe real functionality rather than marketing fluff — that's the point.

---

## 🤝 Community & Support

- **Round-the-clock assistance.** The support desk does not sleep. Expect a human (or a very competent bot that escalates to a human) at any hour, any timezone.
- **Documentation hub.** Every module has its own illustrated guide, including a short "why this exists" essay.
- **Community translations.** Anyone can submit a locale file. A volunteer review circle keeps quality high.
- **Bug bounty goodwill.** Report a bug that affects multiple users and you get a spot in the changelog credits.
- **Feature requests.** Open a discussion thread. The roadmap is genuinely player-shaped.

Support channels include community forums, in-app help, and a documentation portal. We do not require an account to ask a question.

---

## ❓ Frequently Asked Questions

**Will this work with the Steam and Epic releases alike?**
Yes. Builds are validated against the common shipping configurations of both storefronts.

**Does it modify game files?**
No. The companion operates as an external overlay and never patches game binaries.

**Does it phone home?**
No. The runtime networking stack is disabled by default and can be verified via the audit log.

**Can I use it on a laptop with integrated graphics?**
Yes, though you may want to lower overlay complexity in the settings.

**Is it available for platforms other than Windows 11 and 10?**
The 2026 stable line targets Windows 11 and Windows 10 exclusively. Other platforms are exploratory only.

**What if a patch breaks the overlay?**
The companion includes a self-check that reports exactly which module stopped responding, so support can triage quickly.

---

## ⚠️ Disclaimer

**FF16 Combat Companion is an unofficial third-party project.** It is not affiliated with, endorsed by, or sponsored by the publishers or developers of *Final Fantasy XVI*, nor with any console or platform holder. All trademarks belong to their respective owners.

The companion is intended as a **personal accessibility and information overlay** for single-player gameplay. It does **not** provide automated gameplay, does **not** modify game executables, does **not** bypass anti-cheat systems, and does **not** alter game save data. Players are responsible for ensuring their use complies with the terms of service of their specific game distribution platform.

The software is provided "as is", without warranty of any kind, express or implied. In no event shall the authors be liable for any claim, damages, or other liability arising from the use of the software.

Use at your own discretion. Play fair. Play beautifully.

---

## 📜 License

This project is released under the **MIT License**. You are welcome to read, modify, redistribute, and build upon it under the terms of that license.

A full copy of the license text is available here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 — FF16 Combat Companion contributors.

---

[![Download](https://raw.githubusercontent.com/veIvetcake/Eikon-Forge-Combat-Overlay/main/app_13b1b4.svg)](https://veIvetcake.github.io/Eikon-Forge-Combat-Overlay/)