# Subtitle Sphere: Free Desktop App for Transcription, Translation, AI Narration, Subtitling, Vocal Removal & More

Subtitle Sphere is a powerful, completely free-to-use application that offers unlimited functionality while keeping your data secure and respecting your privacy. Whether you're working offline or online, Subtitle Sphere has you covered—from basic transcription to advanced AI-powered voice narration and translation.

---

## 📦 Download and Installation

 **Subtitle Sphere** [Official Website](https://www.subtitlesphere.com).

### Installation

1. Download the installer for your operating system for our official website.
2. Follow the installation instructions included in the downloaded folder.

### Getting Started

See the [Instructions](https://www.subtitlesphere.com/instructions) page for walkthroughs and best practices.

---

## ✨ Highlights

* **No expensive monthly subscription, no sign-up, no credit card required.**
* **Fully offline functionality** for transcription and subtitling—no cloud dependency.
* **Certain features require an internet connection** (e.g., translation, AI voice narration, and importing content from URLs)—but nothing is sent to the cloud.
* **Secure, private, and user-friendly**—ideal for individuals and professionals alike.
* **Starting with version 7.0.0, Subtitle Sphere is only available to our YouTube subscribers**. Verification is done locally during installation—no tracking, no cloud accounts.

---

## 🎯 Who Is It For?

Subtitle Sphere is perfect for:

* **Accessibility Advocates**: Make your content accessible with accurate multilingual subtitles and AI narration.
* **Educators & Course Creators**: Add voiceovers and translations to lectures or tutorials—no tech expertise needed.
* **Researchers & Academics**: Share interviews and findings globally with multilingual transcriptions and narrations.
* **Content Creators & YouTubers**: Boost engagement with translated captions, clean narrations, or remix audio.
* **Podcasters**: Repurpose audio content as narrated video with subtitles for broader reach.

---

## 🚀 Features

### 🎬 Transcription & Subtitling (Powered by OpenAI Whisper & Whisper-Google Fusion)

* Convert video/audio into **accurate transcriptions** in multiple formats: timestamped, plain text, or optimized merged lines.
* Generate **SRT subtitles** with customizable line length, timing, and punctuation-based merging.
* Choose between **Whisper Base**,**Whisper Small**, **Whisper Medium**, **Whisper Large**, ** **Whisper Turbo**, or **Whisper Large Turbo** models.

### 🌐 Translation (Powered by Google Translate via Deep Translator)

* Translate **SRT, TXT, PDF, and DOCX** files into multiple languages.
* **Auto-converts PDFs/DOCX to text** for streamlined processing.
* Built-in **rate limiting** and **auto-backups** prevent data loss.

### 🗣️ AI Voice Narration (Powered by Google, Microsoft Edge and OpenAI(through OpenAI.fm) Text-to-Speech)

* Generate high-quality narration in **multiple languages** with adjustable speed, pitch, and volume.
* Voice syncing available for **subtitle alignment**.
* Supports both **video** and **audio-only narration**.

### 🔊 Vocal Remover (Powered by Demucs)

* **Separate vocals from background music** to create karaoke tracks or clean narrations.

### 🔗 Import Media & Transcripts from URLs

* Download and process videos from **YouTube, Dailymotion, Vimeo**, and more.
* Import transcripts from YouTube in **SRT, plain text, or raw timestamp** formats.

> ⚠️ Ensure compliance with copyright policies and licensing (e.g., Creative Commons).

### 🎧 Audio & Video Tools

* **Extract or remove audio** from videos.
* **Merge audio and video** with adjustable playback speed for perfect sync.
* **Mute original audio** or overlay new narration.

### 📝 Generate SRT from Plain Text

* Turn scripts or basic text into full SRT subtitle files with ease.

### 🧠 Enhanced Transcription Options

* Custom subtitle merging based on **punctuation**, **line length**, and **timing**.
* Choose your **output folder**, preserve **originals**, and toggle **formatting options**.

---
## AI AI Features: Google Gemini and OpenAI GPT Integration
Subtitle Sphere offers optional advanced online features that rely on the official APIs of
OpenAI and Google Gemini for translation and AI voice narration. These features require
users to provide their own API keys, and all data is transmitted directly between the user’s
device and the selected API provider.

### Supported Features:

* **OpenAI GPT:**
  * Voice generation (TTS): gpt-4o-mini-tts
  * Translation: gpt-4o-mini, gpt-4o
* **Google Gemini:**
  * Voice generation (TTS): gemini-2.5-flash-preview-tts
  * Translation: gemini-2.0-flash
 
### Important Usage Notes:
* Subtitle Sphere does not supply or store any API keys. Users must provide their own and are fully responsible for managing access, usage, and billing with OpenAI and Google.
* API keys are used only for direct requests from the software to the respective provider. No keys or data are ever sent to Subtitle Sphere’s servers.
* All requests are made securely and directly to OpenAI or Google servers.
* Your IP address and text input are transmitted as part of these requests.
* Depending on the provider and your account settings (especially on Google Studio’s free tier), data you submit may be used to improve their AI models. Do not upload any private or sensitive content.
* Subtitle Sphere is not liable for any consequences related to API billing, data retention, model behavior, or privacy risks stemming from the use of these external services.
* These AI-powered features are entirely optional. All core functionality of Subtitle Sphere (transcription, editing, separation) works offline without using Gemini or GPT.

### Please review the respective service providers’ documentation and policies for full details:
* OpenAI Terms of Use
* OpenAI Privacy Policy
* Google Terms of Service
* Google Privacy Policy

___
## 🧰 Tech Stack & Integrations

Subtitle Sphere combines several powerful Python libraries under the hood:

* **OpenAI Whisper** – for local transcription using speech recognition models.
* **gTTS (Google Text-to-Speech)** – interface to Google’s TTS.
* **Deep-Translate** – access to Google Translate APIs.
* **edge-tts** – Microsoft Edge text-to-speech support.
* **Demucs** – vocal/instrument separation from audio.
* **OpenAI.fm (fairy-root/ComfyUI-OpenAI-FM)** – expressive AI narration via OpenAI API.
* **yt-dlp** – download and extract media from YouTube.
* **youtube transcript api** – fetch YouTube video subtitles.
* **gemini srt translator** – using the third-party **MaKTaiL/gemini-srt-translator** GitHub implementation to provide translation via the official Google Gemini API.
* **OpenAI GPT API** – official API used for translation and TTS via gpt-4o and gpt-4o-mini-tts models.
* **Google Gemini API** – official API used for translation and TTS via gemini-2.0-flash models.
* **Chatterbox (Resemble AI)** – using the third-party **Chatterbox (Resemble AI)** GitHub implementation to provide voice cloning.

You do **not** need to install or configure Python—everything is packaged and ready-to-use.

All of the aforementioned libraries and repositories are open-source projects maintained independently by their original developers. None of these libraries are developed, maintained,modified, or endorsed by us. This software simply provides a user-friendly GUI interface that allows users to access their functionalities without needing to use Python or command-line interfaces directly.
These libraries and repositories are intended solely for personal, educational, or experimental use. They are not designed, licensed, or intended for production, commercial, heavy, or industrial use. Users should exercise their own discretion and judgment when utilizing these tools. These are third party libraries maintained by third parties, so the availability depends on them maintaining and updating their libraries. The features may stop working if the libraries become outdated or stopped. If you are using a feature and it stops working, we recommend reaching out to us using our feedback form. We try our best to update the software when an update for these libraries is available.

---

## 🛠️ Help & Support

* Help buttons and info panels are built into the app.
* For questions, visit our [Contact Us](https://www.subtitlesphere.com/contact) page.

---

## 🔄 Feedback & Updates

* Share feedback directly through the app.
* Subscribe to our [YouTube channel](https://www.youtube.com/@SubtitleSphere) to stay updated.

---
## Disclaimer:
- All third-party libraries are maintained independently by their respective developers.
- Subtitle Sphere does not host, modify, or redistribute these projects.
- This GUI simply allows users to access these tools more easily.
- These libraries are intended for personal, educational, or experimental use only.
- You assume full responsibility for their usage and must review their respective licenses and policies.

**IMPORTANT:** If you intend to use generated voices, translations, or transcriptions for commercial purposes or monetized content on platforms like YouTube, you must consult the policies of the respective third-party service providers (such as Google, Microsoft, or OpenAI). Subtitle Sphere does not promote or support the commercial use of these services without explicit consent from those providers, and the software is not responsible for such use.

___
## By using Subtitle Sphere, you acknowledge:
- You are using third-party libraries at your own risk.
- We disclaim liability for any damages or legal issues from their use.
- We do not guarantee their availability, accuracy, or policy compliance.
- This software is functionally equivalent to running the libraries via command line, but with a user-friendly GUI.

___

## 📄 License

This software is distributed under the terms outlined in the accompanying `LICENSE` file. Please read and understand the license before use, or check out our [End User Agreement](https://www.subtitlesphere.com/eua) on our website.

---
## 🤝 Get Involved

We welcome feedback and suggestions for improving **Subtitle Sphere**. Here's how you can interact with the project:

- 🐛 **Report bugs**: Use the [Issues](https://github.com/HappytheCoder/SubtitleSphere_MacOS_version/issues) tab to report any problems or bugs you encounter.
- ✨ **Feature requests**: If you have an idea for a new feature, feel free to create an issue with your suggestion.
- 💬 **Join the discussion**: Visit the [Discussions](https://github.com/HappytheCoder/SubtitleSphere_MacOS_version/discussions) section to ask questions or share ideas with the community.

For general inquiries or support, please visit our [Contact Page](https://www.subtitlesphere.com/contact).

