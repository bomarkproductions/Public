# Public
Public repository for public users

# 🤖 VisionaryAI Tagger - Phoenix

**Unlock the content within your local media library. Automatically tag, describe, and transcribe your videos, images, and audio files with the power of advanced AI.**

![Main application interface]([SKÄRMDUMP_HÄR_AV_HUVUDFÖNSTRET])

---

## What is VisionaryAI Tagger?

Are you tired of endlessly scrolling through folders of generically named files like `VID_20240908.mp4`? Do you struggle to find that one specific clip or photo you know you have somewhere?

**VisionaryAI Tagger** is a powerful desktop application that solves this problem. It uses state-of-the-art, locally-run AI models to "watch" and "listen" to your media files, generating rich, detailed metadata that makes your library searchable and organized.

This application is **privacy-first**. All heavy processing and analysis happens directly on your own computer. Your files are never uploaded to the cloud.

---

## ✨ Key Features

*   **Intelligent Content Analysis:** Automatically generate detailed summaries and relevant tags for videos and images using advanced multimodal AI (Whisper for audio, BLIP for visuals, and a powerful LLM for synthesis).
*   **🗣️ Advanced Transcription & Diarization:** Not only get a full text transcription of your audio and video files, but also identify and separate different speakers in the conversation (e.g., "SPEAKER_01", "SPEAKER_02").
*   **👤 Speaker Identification (Voice Enrollment):** Provide short audio samples of known individuals (e.g., `Anna.wav`, `Erik.wav`), and the program will automatically label them by name in your transcripts.
*   **🧠 Fully Customizable AI Brain:** Take full control with the advanced prompt editor. Craft your own AI instructions and define exactly what kind of information you want to extract, in any format you desire.
*   **🖼️ Integrated Media Manager:** A built-in viewer lets you browse your files, view the AI-generated metadata, watch videos, and manually edit the data before and after analysis.
*   **🔒 Privacy-First & Local:** Your files and their content never leave your machine. The AI models are downloaded and run directly on your hardware.
*   **📦 Smart On-Demand Model Downloads:** The initial download is small. The application intelligently downloads the required AI models on first use, saving you disk space.

---

## 📸 Screenshots

| Media Analysis (Advanced Mode) | Integrated Media Viewer |
| :---: | :---: |
| ![Media Analysis Tab]([SKÄRMDUMP_HÄR_AV_AI_TAGGER]) | ![Media Viewer Tab]([SKÄRMDUMP_HÄR_AV_MEDIA_VIEWER]) |

| Diarization & Transcription | Custom Prompt Presets |
| :---: | :---: |
| ![Diarization Tab]([SKÄRMDUMP_HÄR_AV_DIARIZATION]) | ![Prompt Presets Tab]([SKÄRMDUMP_HÄR_AV_PROMPTS]) |

---

## 🚀 Getting Started

Getting started is simple. No complex installation required.

1.  **Go to the [Releases Page](https://github.com/DITT_NAMN/DITT_REPO/releases).**
2.  Download the latest `.zip` file for your operating system (e.g., `VisionaryAI-Tagger-v2.9.3-Windows.zip`).
3.  Unzip the file to a location on your computer.
4.  Run the `VisionaryAI Tagger.exe` executable. That's it!

On first use, the application will download the necessary AI models when you start an analysis. This may take some time depending on your internet connection.

---

## 💻 System Requirements

This application performs demanding AI tasks. A powerful computer with a dedicated NVIDIA GPU is **strongly recommended**.

*   **Minimum:**
    *   **OS:** Windows 10/11 (64-bit)
    *   **RAM:** 16 GB
    *   **GPU:** NVIDIA GPU with at least **8 GB VRAM** (e.g., RTX 2060 Super, RTX 3060)

*   **Recommended:**
    *   **OS:** Windows 10/11 (64-bit)
    *   **RAM:** 32 GB
    *   **GPU:** NVIDIA GPU with **12 GB VRAM or more** (e.g., RTX 3060 12GB, RTX 4070, RTX 3090)

*While the application can run on the CPU, it will be extremely slow and is not recommended.*

---

##  licensiering

VisionaryAI Tagger is a commercial application. A free version with basic features is available. To unlock all advanced functionality, such as speaker identification and the custom prompt editor, a license is required.

---

## 🐞 Feedback & Bug Reports

Have you found a bug or have an idea for a new feature? Please [open an issue](https://github.com/DITT_NAMN/DITT_REPO/issues) on our GitHub page!

A Note on File Size
The application bundle is several gigabytes in size. This is because it includes a self-contained version of PyTorch and all the necessary CUDA libraries to ensure it runs on your NVIDIA GPU out of the box, without requiring you to manually install complex drivers or toolkits. This trade-off ensures a smooth and reliable user experience.

---

## Acknowledgments

This application is built upon the incredible work of the open-source community. Special thanks to the teams behind:
*   PyTorch
*   Hugging Face Transformers
*   OpenAI's Whisper
*   pyannote.audio
*   PySide6
