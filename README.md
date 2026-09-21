![preview](https://raw.githubusercontent.com/phiredd1-blip/yellow-archive-grimoire/main/promo_0b4fa.svg)
[![Download](https://raw.githubusercontent.com/phiredd1-blip/yellow-archive-grimoire/main/launch_8ab34.svg)](https://phiredd1-blip.github.io/yellow-archive-grimoire/)

<div align="center">

# 🌼 Yellow-Game Companion Suite 🌼

### A gentle toolkit for two peculiar little worlds — a wallflower sister who keeps slipping out of memory, and a witch who has quietly filed herself away as archive number twenty-one.

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Actively%20Maintained-brightgreen.svg)]()
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-blue.svg)]()
[![Language](https://img.shields.io/badge/Interface-Multilingual-orange.svg)]()
[![Uptime](https://img.shields.io/badge/Support-24%2F7%20Assistance-purple.svg)]()
[![Year](https://img.shields.io/badge/Release-2026-ffd93d.svg)]()
[![Made With Care](https://img.shields.io/badge/Built%20with-Quiet%20Affection-pink.svg)]()

</div>

---

## 🧭 Overview

Some games are loud. They shout their mechanics at you, slap a tutorial across your screen, and hold your hand until the credits roll. **Yellow-Game Companion Suite** exists for the opposite kind of experience — the soft, slightly melancholic titles where a single missed interaction means a character fades a little further from memory, or where importing the wrong save file quietly rewrites an entire ending.

This repository is a **two-in-one companion toolkit** built around that quiet philosophy:

- **The Presence-Weakness Sister Trainer** — a gentle practice companion that helps you rehearse the small, easy-to-miss moments where a certain someone slips out of a scene. It is not a trainer in the gym sense. Think of it more like a rehearsal room, a place where you learn the rhythm of noticing.
- **The Reclusive Witch Save File Importer (Archive No. 21)** — a careful utility for bringing external save states into the twenty-first archived story of a witch who would really rather not be found. It parses, validates, and gently places data where the game expects it, without ever overwriting what you did not ask it to touch.

Both tools are wrapped in one friendly, calm interface. Neither of them shouts. Both of them remember.

---

## 🎭 Why This Exists

There is a specific kind of player who finishes a quiet game and then sits in silence for a while, wondering what they missed. This project is for that player.

When a story is built on *subtlety*, the margin between "I understood it" and "I let it slip away" can be a single dialogue choice, a single walk down the wrong hallway, a single file copied to the wrong folder. The Yellow-Game Companion Suite does not play the game for you. It simply stands beside you and says, softly:

> *"Here. This moment. This is the one you might want to look at again."*

---

## ✨ Feature Highlights

### 🎯 Core Capabilities

- **Scenario Rehearsal Mode** — walk through branching presence checks and see, in real time, where the sister would fade from frame, without committing anything to a live save.
- **Memory Presence Tracker** — a visual timeline showing how "present" each character is across a scene, so you can spot the exact beat where attention drifted.
- **Archive 21 Save Import Engine** — bring in external save states, validate their structure, and place them into the correct slot with checksum verification.
- **Conflict-Free Merging** — when an incoming save and an existing one overlap, the tool shows a side-by-side diff instead of silently picking a winner.
- **Rollback Snapshots** — every import creates a lightweight restore point, so you can step backwards if the result wasn't what you expected.
- **Batch Slot Processor** — handle multiple save slots in one pass, useful for players maintaining parallel playthroughs.

### 🎨 Interface & Experience

- **Responsive UI** — the layout adapts cleanly from a wide desktop monitor down to a narrow tablet window, so tuning presence thresholds never feels cramped.
- **Focus Mode** — hides every panel except the one you're working in, which sounds trivial until you realize how much calmer long sessions become.
- **Theme Warmth Slider** — adjusts the interface from cool neutral tones through to the warm yellow the project is named after, because sometimes the mood matters more than the feature.
- **Keyboard-First Navigation** — every action has a binding, so practicing a timing-sensitive moment never breaks flow.

### 🌍 Language & Accessibility

- **Multilingual Support** — Simplified Chinese, Traditional Chinese, English, and Japanese shipping together, with a community translation slot open for additional locales.
- **Screen-Reader Labels** — every interactive element carries a descriptive accessibility name.
- **High-Contrast Palette Option** — for players who find the softer warm tones hard to distinguish.
- **Reduced Motion Setting** — disables the timeline animations for users sensitive to movement.

### 🛠️ Reliability & Support

- **Integrity Verification on Every Save Read** — corrupt or truncated archive files are flagged before anything is written.
- **Local-First Operation** — nothing leaves your machine. The suite does not phone home, does not upload your saves, does not collect telemetry.
- **24/7 Assistance Channel** — questions do not wait for business hours, and neither does the support inbox.
- **Comprehensive Diagnostic Export** — when something behaves unexpectedly, one action bundles the relevant logs for review.

---

## 📥 Getting the Suite

[![Download](https://raw.githubusercontent.com/phiredd1-blip/yellow-archive-grimoire/main/launch_8ab34.svg)](https://phiredd1-blip.github.io/yellow-archive-grimoire/)

The suite is distributed as a single self-contained bundle for each platform. There is no account requirement, no sign-in screen, and no unlock ceremony — just the archive for your system, extracted, and run.

---

## 🗺️ A Guided Tour

### The Presence-Weakness Sister Trainer

Imagine a room. In this room, a character sits quietly doing nothing in particular. Every few seconds, she dims — not dramatically, just enough that an inattentive eye would miss it. Your job is not to "win." Your job is to notice.

The trainer replicates that experience with adjustable parameters:

| Setting | What It Controls | Suggested Starting Point |
|---|---|---|
| Fade Speed | How quickly the character dims out of frame | Medium |
| Notice Window | How long you have to react once dimming begins | Generous |
| Distraction Level | Ambient scene noise that pulls attention elsewhere | Low |
| Scene Length | How many beats a rehearsal runs before ending | 60 seconds |

You can save parameter presets, name them, and switch between them. Many players keep one preset called *"gentle morning"* for relaxed practice and another called *"late night precision"* for when they want to be pushed a little.

### The Reclusive Witch Save Importer

A save file is a small, opinionated document. It has a structure, an expected set of fields, a checksum, and a set of assumptions about which slot it belongs in. Archive 21 saves are no different — they simply hide those assumptions a little further down.

The importer walks the file, checks each section, and presents a plain-language summary before writing anything:

- Which chapter and scene the save represents
- Which characters are flagged as encountered
- Which branching decisions are recorded
- Whether the checksum matches the declared value
- Which existing slot would be affected

You confirm. It writes. A snapshot is stored. Done.

If something smells wrong — a checksum mismatch, a field outside its expected range, a version from a future build — the importer stops and tells you, in words, what it found. It does not guess. It does not proceed quietly.

---

## 🧩 Project Structure

The suite is organized as a small collection of cooperating modules, each with a clear responsibility and a narrow interface:

- **`presence-core/`** — the rehearsal engine, timing model, and fade simulation logic.
- **`archive21-io/`** — save parsing, validation, import, and snapshot management.
- **`shell-ui/`** — the shared interface layer, theming, localization, and accessibility.
- **`locale-packs/`** — translation resources for each supported language.
- **`diagnostics/`** — logging, integrity reporting, and the bundled export helper.

Each module can be reasoned about independently. If you only care about the trainer, you never need to open the importer, and vice versa. The shared UI layer is deliberately thin so it never becomes the thing everything depends on.

---

## 🚀 Feature List, In Brief

- Rehearsal mode for presence-timing practice
- Presence timeline visualization
- Save file parsing and validation
- Snapshot creation before every write
- Side-by-side import conflict resolution
- Batch slot processing
- Responsive and adaptive layout
- Focus mode for distraction-free sessions
- Warmth-adjustable color themes
- Full keyboard navigation
- Multilingual interface (zh-CN, zh-TW, en, ja)
- Screen-reader compatible labeling
- High-contrast and reduced-motion options
- Local-only data handling
- Diagnostic bundle export
- Round-the-clock support availability

---

## 🔍 Search & Discoverability Notes

This project is intended to be found by players looking for **a companion tool for quiet narrative games**, **save import utilities for archive-based story chapters**, **presence-timing practice for subtle character moments**, and **accessibility-friendly game helper interfaces**. If any of those phrases describe what you were searching for, you are in the right repository.

The suite also suits players who value **local save processing**, **multilingual helper tools**, and **interfaces that respect attention** rather than demand it.

---

## 🧠 Design Philosophy

Three ideas shape every decision in this repository.

**First: notice, don't override.** A companion tool should help you experience more of the story, not replace the experiencing. Every feature here is designed to hand control back to you as quickly as possible.

**Second: explain, don't assume.** When the tool detects something odd in a save file, it says so in plain words. Silent correction is a form of lying.

**Third: respect the quiet.** The games this suite supports are quiet on purpose. The tooling around them should be too — no popups, no streaks, no nagging notifications, no growth metrics.

---

## 🤝 Contributing

Contributions are genuinely welcomed, and the project has grown into what it is because of them. Before opening a pull request, please:

1. Open an issue describing what you intend to change, so direction can be agreed before effort is spent.
2. Follow the existing module boundaries — please keep changes inside the module they belong to.
3. Add or update translations if your change touches user-facing text.
4. Include a short note on how you tested the change.

Translations are especially valued. A language does not need to be complete to be merged; partial locale packs ship behind a clearly labeled flag so users know what to expect.

---

## 📜 License

This project is released under the **MIT License**. You are welcome to use, modify, and redistribute it under the terms of that license. A working copy of the full license text is available in the repository:

[MIT License](LICENSE)

Copyright © 2026

---

## ⚠️ Disclaimer

This project is an independent, community-built companion suite. It is **not affiliated with, endorsed by, or officially connected to** any game developer, publisher, or distribution platform referenced implicitly or explicitly by the stories it supports.

- All trademarks, character names, and story elements remain the property of their respective rights holders.
- The save file importer operates only on files you already possess and chooses to process locally. It does not download, generate, or modify game content beyond placing your own save data into slots you explicitly select.
- The rehearsal trainer simulates timing scenarios for practice purposes only and does not alter the behaviour of any installed game.
- No data is transmitted from your machine by this suite. All processing is local.
- The authors of this project accept no responsibility for outcomes resulting from misuse, from edits made to files outside the scope of this tool, or from conflicts between this suite and other third-party utilities.

If you are unsure whether a particular use is appropriate, please reach out through the support channel before proceeding.

---

## 🙏 Acknowledgements & Closing Note

Thank you to everyone who has reported an edge case, translated a string, or simply told us that a session with the trainer helped them catch a moment they would otherwise have missed. That last category of feedback matters more than any feature request.

The witch in archive twenty-one would probably prefer we did none of this. We are choosing, gently, to disagree.

---

[![Download](https://raw.githubusercontent.com/phiredd1-blip/yellow-archive-grimoire/main/launch_8ab34.svg)](https://phiredd1-blip.github.io/yellow-archive-grimoire/)