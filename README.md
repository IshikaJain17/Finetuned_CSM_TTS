# Fine-Tuned CSM (Contextual Speech Model) — Emotion-Aware Text-to-Speech (TTS)

This repository contains an implementation and light fine-tuning workflow for **CSM-1B (Contextual Speech Model)**, designed to produce natural, expressive speech directly from text.  
CSM goes beyond traditional TTS by using *semantic understanding* instead of rigid emotion tokens. The model automatically infers tone, emotion, and conversational flow from the text itself.

---

## 🚀 Features
- 🎤 **Text-to-Speech with contextual emotion**
- 🤖 **No emotion tags needed** — emotions come from semantics
- 🧠 Natural prosody, pauses, and speaking style
- 📄 Google-Colab-ready notebook (`Sesame_CSM_(1B)-TTS.ipynb`)
- 🔧 Supports fine-tuning of:
  - Prompt style
  - Speaker embeddings
  - Conversational structure
- 🔊 Outputs high-quality WAV audio

---

## 📂 Repository Contents


📁 project/
├── Sesam e_CSM_(1B)-TTS.ipynb # Main notebook
├── README.md # Documentation
└── /audio_outputs # Generated samples (optional)


---

## 🛠️ Installation

This project is built to run easily in **Google Colab**.

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/<repo-name>
cd <repo-name>

2. Install dependencies (in Colab or locally)
pip install transformers accelerate soundfile torch numpy scipy
