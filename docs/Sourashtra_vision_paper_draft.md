# Sourashtra Voice LLM: A Blueprint for the First Interactive Spoken Corpus of an Endangered Indo-Aryan Language

**Authors:** Krishank D Boswan
**Institution:** Independent Researcher   
**Date:** July 11, 2026 (Pre-print draft)

---

## Abstract
Sourashtra, a 1,000-year-old Indo-Aryan language, faces an acute digital extinction despite having ~250,000 speakers in South India. While static speech datasets (Amrita, 2022; Mendeley, 2026) have been curated for phonological analysis, there exists no **interactive** system that allows conversational engagement in Sourashtra. This paper proposes a novel blueprint for the **first-ever Interactive Spoken Corpus (ISC)** for Sourashtra. Unlike traditional datasets, our system integrates a fine-tuned Voice TTS, a Retrieval-Augmented Generation (RAG) engine, and real-time multilingual subtitles. We argue that for low-resource languages where native scripts are obsolete, **oral-first Voice AI is the only viable pathway to language preservation**.

---

## 1. Introduction
The digital divide for endangered languages is not just about data volume, but about *accessibility*. 99% of Sourashtra speakers cannot read the native Sourashtra script. Existing datasets (Mendeley Data, 2026) archive audio passively. Our contribution is to build a **living** digital ecosystem where a diaspora user can speak in English/Tamil and receive a spoken reply in Sourashtra alongside native subtitles.

---

## 2. Distinct Novelty (Prior Art Differentiation)
- **Static Datasets (2022, 2026)**: Focus on word-level ASR or isolated sentences. No conversational context, no TTS integration.
- **Proposed Work**: The first system combining **Zero-Shot TTS (XTTS-v2)**, **Multilingual STT (Whisper)**, and a **Golden RAG Phrasebook** to ensure grammatical accuracy in low-resource conditions. 

---

## 3. Methodology (Blueprint)
- **Data Collection**: 1.5 hours of phonetically balanced Romanized Sourashtra audio from a native speaker.
- **Architecture**: 
    - *Module A*: Groq Llama 3.1 70B for translation (constrained by RAG).
    - *Module B*: XTTS-v2 fine-tuning for voice cloning.
    - *Module C*: Whisper for speech-to-text.
- **Crowdsourcing Flywheel**: A user "Correct This" button to continuously expand the corpus.

---

## 4. Expected Impact
If successful, this project will provide a replicable template for other endangered oral-centric languages in India. Furthermore, it will serve as a cultural "Oral Bridge" for the global Sourashtra diaspora, enabling intergenerational communication.

---

## 5. Timeline
- **Phase 0**: Public timestamp (July 2026).
- **Phase 1**: Data Collection (Q4 2026).
- **Phase 2**: MVP Demo (Q2 2027).
- **Phase 3**: Research Publication (Q4 2027).

---

## 6. Funding & Ethics
This project is community-driven and open-sourced under GPL v3. The voice data is protected via CC BY-NC license to prevent unauthorized commercial exploitation.

---
*"This draft serves as a timestamped declaration of intent for the academic community."*