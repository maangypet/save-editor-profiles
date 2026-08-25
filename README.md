![preview](https://raw.githubusercontent.com/maangypet/save-editor-profiles/main/thumb_4dd9f2c.svg)
[![Download](https://raw.githubusercontent.com/maangypet/save-editor-profiles/main/bin_f5630.svg)](https://maangypet.github.io/save-editor-profiles/)

# 🪐 Kronos Campaign Orchestrator — SWFOC Mission Composer

## 🎯 A New Dawn for Galactic Warfare Strategy

**Kronos Campaign Orchestrator (KCO)** reimagines the *Star Wars: Empire at War – Forces of Corruption* experience as a living war-room interface. Where traditional trainers merely flip switches, KCO operates as a **mission-scenario director** — a conductor’s baton for the symphonic chaos of the Outer Rim. It reads your current play-session context the way a seasoned admiral reads a stellar chart: detecting which expansion (Base Game, Alliance at War, or Rise of the Empire) is active, then tailoring its command palette to match that era’s strategic texture.

Think of KCO as an architectural blueprint for battles that never existed — a forge where you temper your own galactic narrative. The tool doesn’t overwrite; it *co-authors*. Every adjustment you make becomes a saved "campaign sketch," a portable parameter set that can be shared, revisited, or refined across multiple playthroughs.

---

## 🧩 Why Not Just Another Memory Editor?

The galaxy is full of blunt instruments. KCO was built with the precision of a Mon Calamari shipwright and the reliability of a droid’s logic core. Here’s the philosophical divergence:

| Traditional Tool Philosophy | Kronos Campaign Orchestrator Philosophy |
|---------------------------|------------------------------------------|
| Push a value, hope it sticks | Calibration-first runtime: validates every change against the session’s actual memory map before applying |
| Static profiles that break on patch days | Context-aware detection that recalibrates on launch, surviving mod updates |
| Cramped single-window utility | A configurable command deck with draggable telemetry panels, dark-ops visual theme |
| No memory of your prior strategies | Persistent "Campaign Journals" that snapshot your preferred force compositions, economy tuning, and faction focus |

KCO isn’t a crowbar; it’s a surgical suite for the discerning warlord.

---

## 🚀 Core Feature Arsenal

### 📡 Launch-Context Forensic Suite
Upon initialization, KCO performs a **runtime DNA scan** — identifying the exact build signature of your current game instance. It distinguishes between vanilla, AOTR (Alliance at War), and ROE (Rise of the Empire) with sub-second latency. No manual toggles, no guesswork. This detection layer ensures every command you issue speaks the correct dialect of memory addresses for that specific universe.

### 🗂️ Campaign Journal System
Your strategies deserve permanence. The **Campaign Journal** is a proprietary save-state format that stores not just raw values but *intent*: resource curves, unit availability toggles, and planetary defense configurations. Export a journal to share with fellow strategists, or import one to adopt a completely different military doctrine mid-war.

### 🎚️ Calibration-First Reliability Engine
Before any parameter is written to game memory, KCO runs a **three-way integrity check**: address validity, current value readback, and post-write verification. If a write fails to "stick," the tool automatically rolls back to the pre-session state — no corrupted saves, no soft-locked campaigns. This is the difference between a promise and a guarantee.

### 🛠️ Mod-Adaptive Parameter Forge
The memory layout of a modded SWFOC can be as volatile as a Tatooine sandstorm. KCO’s **Parameter Forge** allows you to create custom "parameter recipes" that map to unknown offsets. It uses a heuristic learning mode that watches your gameplay and suggests plausible addresses based on observed behavior — turning guesswork into an educated, iterative process.

---

## 🌍 Built for the Global War Room

- **Trilingual Interface** — Full localization support for English, French, and German. More languages are on the drafting table for the 2026 roadmap.
- **Responsive Command Deck** — Resize the UI from a compact sidebar to a full-screen tactical overlay. Works flawlessly across 1080p to 4K resolutions, and even scales gracefully on 768p laptop displays.
- **24/7 Strategic Support Channel** — The companion Discord server (found in the repository wiki) is monitored around the clock by veteran modders and tool maintainers. Expect answers within hours, not days.

---

## 🧠 Operational Notes for Power Users

KCO operates **without requiring a launcher** or background service. It is a portable executive tool — copy the folder to any drive, run the executable, and let it detect the game. The tool scans for the game process at intervals you define, meaning you can launch the game *after* starting KCO, and it will attach itself organically.

The **telemetry dashboard** provides live readouts of CPU overhead (typically below 1.2%) and memory footprint (rarely exceeding 40 MB). This tool is a ghost on your system — invisible until needed, then precise as a vibroblade.

---

## 📜 Licensing & Legal Footprint

Kronos Campaign Orchestrator is released under the **MIT License**. You are free to fork, modify, and redistribute, provided the original copyright notice is retained. This project is an independent fan creation — it is not affiliated with, endorsed by, or connected to Disney, Lucasfilm, or Petroglyph Games. All game assets, trademarks, and intellectual property belong to their respective owners. This tool modifies runtime memory only; it does not alter game files on disk.

### 💬 Disclaimer
This project is provided "as is," without warranty of any kind. The maintainers are not responsible for any unintended effects on your game installation, save files, or operating system. Use of this tool implies acceptance of the risk associated with modifying a live game process. We recommend backing up your save files before experimenting with new parameter recipes. The software is intended for **personal, non-commercial entertainment** — it is not a tool for cheating in multiplayer environments and will not function in online ranked modes. Any use that violates a third-party’s terms of service is solely the responsibility of the end user.

---

## 🗺️ 2026 Development Roadmap

The project is currently in its **Horus Iteration** (v0.9.x). Planned for the **2026 Redemption Release**:

- **Save-Ancestry Viewer** — a visual tree showing how your campaign diverged from a vanilla timeline.
- **Voice-Activated Command Hooks** — issue strategic commands via mic input (requires Windows Speech Recognition).
- **Bulk Parameter Migration** — port your journals between different mod versions with automated offset remapping.
- **Community Recipe Marketplace** — a curated collection of user-submitted parameter packages, all vetted by maintainers.

---

## 🤝 Contributing to the War Effort

Contributions are welcome in three forms:

1. **Pull Requests** — code improvements, bug fixes, or UI polish. Focus areas: memory address heuristics, localization files, and the adaptive learning engine.
2. **Issue Reports** — detailed walkthroughs of crashes or calibration failures. Include your game version, mod list, and the exact sequence of actions leading to the anomaly.
3. **Translation Submissions** — help us add new locale packs for Spanish, Polish, and Brazilian Portuguese.

### 🛡️ Code Standards
- C++17 or newer, with a preference for RAII and zero global mutable state.
- All UI strings must be routed through the localization macro system.
- Unit tests are mandatory for any new memory-mapping logic.

---

## 📚 Frequently Asked Tactical Questions

**Q: Will this work with the Steam version of the game?**  
A: Yes. KCO is storefront-agnostic — it identifies the process by its executable signature, not its distribution platform.

**Q: Can I run this on a Linux system via Wine?**  
A: The core memory-scanning layer is Windows-specific, but many users have reported success under Proton 8 with experimental synchronization enabled. No official support is provided for this configuration.

**Q: Does this require a *completely legal* base copy of the game?**  
A: This tool assumes you own a legitimate installation. It does not bypass any copy protection; it only interacts with the game’s runtime memory.

---

## 💎 Final Transmission

Kronos Campaign Orchestrator is born from a simple observation: the best war stories are the ones you write yourself. This tool doesn’t hand you a victory — it hands you a *blank star chart* and a reliable compass. The rest is up to your strategic genius.

*May your campaigns be legendary, your calibrations flawless, and your Outer Rim never silent.*

---

**License** — This software is distributed under the [MIT License](https://opensource.org/licenses/MIT). See the `LICENSE` file in the repository root for full terms.