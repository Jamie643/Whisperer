# 🎙️ WHISPERER

WHISPERER is a streamlined transcription pipeline built on [OpenAI's Whisper](https://github.com/openai/whisper) speech recognition model. Designed for both short and long-form audio files, it supports MP3 input, timestamped transcriptions, and Word/Text file exports — all in an intuitive Colab notebook.

---

![banner](https://i.imgur.com/zYzUOZ5.png) <!-- Replace with your own banner if needed -->

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Jamie643/Whisperer/blob/main/notebooks/LibriSpeech.ipynb)
![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Whisper](https://img.shields.io/badge/powered%20by-Whisper-8A2BE2?logo=openai)
![License](https://img.shields.io/github/license/Jamie643/Whisperer)

---

## ✨ Features

- 🎧 Supports **MP3** audio files (auto-converted to 16kHz WAV)
- 🧠 Powered by **Whisper base.en** model
- ⏱️ Generates **timestamped transcriptions**
- 📜 Output in **clean text format** or downloadable Word documents
- 🧪 Built for experimentation on Google Colab (no setup required!)

---

## 🚀 Getting Started

Open the project in Google Colab and follow the cells step-by-step:

🔗 [Launch WHISPERER in Colab](https://colab.research.google.com/github/Jamie643/Whisperer/blob/main/notebooks/LibriSpeech.ipynb)

### 1. Upload Your MP3
Use the upload prompt to add your audio file.

### 2. Automatic Conversion
MP3 is converted to WAV and resampled to 16kHz mono.

### 3. Transcription
Whisper processes the file and outputs timestamped text.

### 4. Export Results
Download your transcript as a `.txt` or `.docx` file.

---

## 📂 Output Example

```text
[0.0 - 5.3] Welcome to the latest episode of the tech chronicles...
[5.4 - 10.1] Today, we're diving into the rise of artificial intelligence...

📦 Dependencies
Python 3.8+
OpenAI Whisper
torchaudio
pydub
ffmpeg
docx (optional for .docx export)
Google Colab

🙋 Author
Spkymnk
📍 GitHub: Spkymnk
🧠 Project: WHISPERER
