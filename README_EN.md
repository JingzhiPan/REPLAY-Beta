# REPLAY

[简体中文](README.md) | **English**

> This repository distributes beta builds of REPLAY. The installers are provided for invited testing only — please do not redistribute without permission. All rights reserved.

> A local-first, immersive space for narrative creation and character relationship management

---

## What is REPLAY

REPLAY is a **local-first desktop app** designed for deeply immersive creators.

It is an organizing and writing space built specifically for **character-centric, long-term storytelling**.

**Core value**: bringing scattered creative material, memories, and character relationships together into one continuous, personal, and fully private local space.

---

## Who it's for

| User | Typical use |
|------|-------------|
| TRPG players | Character journeys, session logs, worldbuilding notes |
| Self-insert / OC×canon creators | Preserving interactions with AI or fictional characters, emotional continuity |
| AI roleplay communities | Multi-character management, story archives, lore upkeep |
| OC creators | Original character profiles, worldbuilding, inspiration collection |
| Novel / game-script writers | Relationship graphs, story fragments, research material |

**What they have in common**: highly immersive, character-driven, and invested in continuity. They pay for **peace of mind** — no data floating in the cloud, no creative history lost to platform changes.

**The pain REPLAY solves**: the anxiety of fragmented creation — chat logs scattered everywhere, character settings drifting over time, inspiration slipping away with nowhere to collect it.

---

## Download & install

Go to the **[Releases page](../../releases)** and download the installer for your platform from the latest release:

| Platform | File |
|----------|------|
| macOS (Apple Silicon, M1 or later) | `REPLAY-<version>-mac.dmg` |
| Windows 64-bit (installer) | `REPLAY-<version>-win.exe` |
| Windows 64-bit (portable) | `REPLAY-<version>-portable.exe` |

> No Intel Mac build for now — contact the maintainer if you need one.

### ⚠️ Back up before upgrading

If you have used any earlier version, **make a full copy of your Vault folder** (the data directory you chose at first launch) before upgrading. New versions may upgrade the on-disk data structures; the first launch migrates old Vaults automatically (with automatic backups, but an extra manual copy is always safer). Fresh users can skip this.

### macOS
1. Download the `.dmg`, open it, and drag REPLAY into **Applications**.
2. The first launch will be blocked by macOS ("cannot verify the developer" or "damaged") — **this is because beta builds are unsigned, not a problem with the app**:
   - **Option A:** In Applications, **right-click REPLAY → Open**, then click "Open" in the dialog. Only needed once.
   - **Option B:** If it says "damaged", run `xattr -cr /Applications/REPLAY.app` in Terminal, then open it again.

### Windows
1. Download the installer `.exe` or the `portable.exe`.
2. If the blue **SmartScreen** warning appears: click "More info" → "Run anyway". Also normal — beta builds have no code-signing certificate yet.

---

## First launch

1. The UI defaults to **English**; you can switch between EN / Simplified / Traditional Chinese on the welcome screen (top right) or in Settings. Your choice is remembered.
2. You'll be asked to **choose a Vault folder** — this is where all your data lives. Pick a folder you can find again (**avoid cloud-synced folders** during the beta to prevent sync conflicts).
3. AI features require your own API key (Settings → AI). Everything except AI works fine without one.
4. The version number is at the **bottom of the Settings panel** — please include it in feedback.

---

## Feedback

When reporting an issue, please include: **version + OS**, **steps to reproduce (if possible)**, **expected vs actual behavior**, and screenshots if you have them.

> ⚠️ If you ever see **data loss or corrupted display**, **stop immediately and contact the maintainer** — don't keep writing. Your Vault folder is all of your data; preserving its current state matters most.

---

## Known limitations (beta)

- **No auto-update**: new versions are downloaded and installed manually (your data lives in the Vault and is unaffected).
- Both mac and Windows builds are **unsigned** (see install notes above).
- No Intel Mac build yet.
