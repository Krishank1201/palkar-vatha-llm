# palkar-vatha-llm
### *Palkar Vatha ~ The First-Ever Interactive Spoken Corpus for the Sourashtra Language*

---

## 📌 Official Declaration of Origin

**This repository marks the official commencement of the "Sourashtra Voice LLM" project.**  

- **Project Initiation Date:** July 11, 2026  
- **Core Claim:** This is the **first-ever interactive, voice-first, subtitle-enabled conversational AI** built for the Sourashtra language.  
- **Design Philosophy:** 100% **Oral-First**. We do not use the native Sourashtra script. All transliteration is done using Romanized Latin characters (ISO 15919 standard) to ensure accessibility for the global diaspora.  
- **Prior Art Protection:** The project architecture, data strategy, and interactive workflow are documented here with cryptographic timestamps via Git. This serves as prior art against any future claims of "first interactive corpus" for Sourashtra.

---

## 🚀 The Vision

Sourashtra is a 1,000-year-old Indo-Aryan language spoken by ~250,000 people, primarily in Tamil Nadu and Karnataka. Despite its rich heritage, it is classified as **"definitely endangered"** by UNESCO. 

While static linguistic datasets exist, **no one has built a bridge for the younger generation**—a bot that allows a diaspora child to speak English and *hear* their ancestral tongue spoken back with real-time subtitles. 

This project is that bridge.

---

## 🏗️ Architecture (The Modular Pipeline)

| Module | Name | Tech Stack | Purpose |
| :--- | :--- | :--- | :--- |
| **A** | The Interpreter (Brain) | Llama 3.1 70B / Gemini Flash (via Groq free tier) | Translates user prompt into Romanized Sourashtra using RAG. |
| **B** | The Voice Clone (TTS) | Coqui XTTS-v2 (Fine-tuned) | Speaks the translated text in a native speaker's voice. |
| **C** | The Ears (STT) | OpenAI Whisper (Multi-lingual) | Transcribes user speech (English/Tamil/Kannada) into text. |
| **D** | The Memory (RAG) | ChromaDB + Golden Phrasebook | Retrieves 300+ pre-validated sentences to ensure grammar accuracy. |
| **E** | The Flywheel (Crowdsource) | Supabase (Free Tier) | Collects user corrections to continuously improve the corpus. |

---

## 🗂️ Data Strategy (The Moat)

**To prevent academic "scooping" while building in the open, we strictly separate public code from private data.**

| Data Type | Status | Access |
| :--- | :--- | :--- |
| **Golden RAG Phrasebook** (300+ sentences) | ✅ Will be uploaded (Public) | Included in `/data/golden_phrases.csv` |
| **Sample Audio Clips** (10 demonstration files) | ✅ Will be uploaded (Public) | Included in `/data/sample_audio/` |
| **Full Voice Clone Dataset** (1.5 Hours / 1,800 Files) | 🔒 Private | Stored securely. Available upon reasonable request **ONLY after** the accompanying research paper is published. |

---

## ⚖️ License

- **Code:** GNU General Public License v3.0 – You may use, modify, and distribute the code, but any derivative work must also be open-source.
- **Audio Data (Samples & Full Dataset):** Creative Commons Attribution-NonCommercial (CC BY-NC). Commercial use of the voice data is strictly prohibited without explicit written consent.

---

## 🗓️ Project Timeline (Quality over Speed)

| Phase | Milestone | Target Completion |
| :--- | :--- | :--- |
| **0** | Public Repository Launch & Prior Art Claim | ✅ **Completed** (July 2026) |
| **1** | Record 1.5-Hour High-Fidelity Voice Dataset | Q4 2026 |
| **2** | Fine-tune XTTS-v2 Voice Clone | Q1 2027 |
| **3** | Launch Gradio MVP (Interactive Demo) | Q2 2027 |
| **4** | Add Crowdsource "Correct This" Feature | Q3 2027 |
| **5** | Submit Research Paper & Secure Grants | Q4 2027 / Q1 2028 |

---

## 👥 How to Contribute (For the Sourashtra Community)

If you are a native Sourashtra speaker:
1.  **Star** this repo to show your support.
2.  **Review** the `golden_phrases.csv` for accuracy.
3.  **Reach out** via the Issues tab if you want to volunteer your voice for recording or help with grammar validation.

---

## 📧 Contact & Community

- **Maintainer:** Krishank D Boswan, reach me at [Krishank](https://www.linkedin.com/in/krishank-d-boswan-343894226/)
- **Community Support:** Please open a GitHub Issue for technical discussions.
- **Serious Inquiries:** Contact krishankboswan@gmail.com for grant/partnership inquiries.

---

*"A language is not just words; it is the soul of a culture. Let's keep ours alive."*
