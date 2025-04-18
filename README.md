# 🎧 Whisper Audio Transcription Tool

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

A powerful transcription tool using OpenAI's Whisper model to convert MP3 audio files into accurate, timestamped text - perfect for podcasts, interviews, and lectures.

## 🌟 Features

- 🎵 **MP3 Support** - Directly upload and process `.mp3` files
- ⏱️ **Timestamps** - Word-level and segment-level timing markers
- 🕒 **Long Audio Handling** - Automatically splits large files
- 🌍 **Multilingual** - Supports 100+ languages (optional)
- 📊 **Accuracy Metrics** - Optional Word Error Rate (WER) calculation
- ☁️ **Cloud-Based** - Runs entirely in Google Colab

## 🛠️ Tech Stack

| Component       | Technology |
|-----------------|------------|
| Core Engine     | OpenAI Whisper |
| Environment     | Google Colab |
| Audio Processing| PyDub |
| Metrics         | jiwer |
| Data Handling   | Pandas |

## 🚀 Quick Start

### Prerequisites
- Google account (for Colab)
- MP3 audio file (<2GB recommended)

### Installation
1. **Open the [Colab Notebook](https://colab.research.google.com/)**
2. **Run setup cell**:
   ```python
   !pip install git+https://github.com/openai/whisper.git
   !pip install pydub jiwer pandas
