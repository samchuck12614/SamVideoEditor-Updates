# 🎬 Sam Video Editor

**AI Automation Studio for Windows** — turn a script or a set of images into a finished video with AI voiceover, stock footage and automatic captions.

[![Download](https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge)](https://github.com/samchuck12614/SamVideoEditor-Updates/releases/latest)
![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-lightgrey?style=for-the-badge)

---

## ⬇️ Download

1. Go to the **[Releases page](https://github.com/samchuck12614/SamVideoEditor-Updates/releases/latest)**
2. Download the ZIP file
3. Extract it completely, then run **`SamVideoEditor.exe`**

> Keep `SamVideoEditor.exe` together with the `_internal` folder. Do not move the exe alone.

---

## ✨ Features

**🎞️ Editor**
- Build videos from your own images + audio (MP3 / WAV / M4A)
- Smooth zoom effect on images
- Transitions: Crossfade, Fade to Black
- Auto-fit image length to your audio
- 1080p Landscape and Portrait (YouTube, Shorts, Reels, TikTok)

**🤖 AI Studio**
- Write scripts with local AI models through Ollama
- Ready presets: YouTube Script Writer, Scene Breakdown, Image Prompts, Titles & SEO
- Fast Mode for quicker answers
- Send the finished script straight to the AI Builder

**🎥 AI Builder**
- Script → full video in one click
- AI voiceover (English, Hindi, Urdu and more voices)
- Stock video or images from Pexels, Pixabay and Coverr
- Automatic scene detection from your script

**💬 Captions**
- Auto captions from audio using Whisper (word-level timing)
- Or load your own `.srt` file
- Caption styles: Bold Yellow, Standard White, Neon Blue
- Position and animation control (fade, slide)

**⚙️ Tools**
- Render queue with live progress and cancel
- Multiple videos rendering at the same time
- CPU or NVIDIA GPU rendering
- Light and Dark theme
- Built-in update checker

---

## 📸 Screenshots

<!-- Upload screenshots to the repo (e.g. /screenshots) and link them here -->
![Editor](screenshots/editor.png)
![AI Studio](screenshots/ai-studio.png)
![AI Builder](screenshots/ai-builder.png)

---

## 💻 System Requirements

| | |
|---|---|
| OS | Windows 10 / 11 (64-bit) |
| RAM | 8 GB minimum, 16 GB recommended |
| Disk | 10 GB free space |
| Internet | Needed for AI voiceover, stock media and first-time captions |
| GPU | Optional (NVIDIA, for faster rendering) |

---

## 🚀 Quick Start

**Make a video from a script**
1. Open the **AI Builder** tab
2. Paste your script (or generate one in **AI Studio**)
3. Add your free Pexels / Pixabay key and click **Save Keys**
4. Choose voice, captions and resolution
5. Click **Build AI Video**

**Make a video from your own images**
1. Open the **Editor** tab
2. Add images and select your audio
3. Choose captions and transitions
4. Click **Add to Render Queue**

Finished videos are saved in the `output` folder.

---

## 🔑 Activation

The app asks for an activation password on first launch. Send your **Machine ID** (shown in the window) to get your key.

📧 Contact: **[your-email@example.com]**

---

## 🔧 Optional Setup

- **Free stock media keys:** [Pexels](https://www.pexels.com/api/new/) · [Pixabay](https://pixabay.com/api/docs/) · [Coverr](https://coverr.co/developers)
- **AI script writing:** install [Ollama](https://ollama.com), then run `ollama pull qwen3`
- **Captions:** the first run downloads a small Whisper model (~140 MB). After that it works offline.

---

## ❓ FAQ

**Windows shows a SmartScreen warning.**
The app is not code-signed yet. Click *More info → Run anyway*.

**Captions do not work.**
Check your internet on the first run. If you see an ffmpeg error, run `winget install ffmpeg` in PowerShell and restart the app.

**Ollama is not detected.**
Start Ollama, then click *Refresh Ollama Connection* in the AI Studio tab.

**GPU rendering fails.**
Switch *Rendering* to **CPU (libx264)**.

---

## 🔄 Updates

The app checks this repository for new versions automatically. See the [Releases](https://github.com/samchuck12614/SamVideoEditor-Updates/releases) page for the changelog.

---

## 📬 Support

Found a bug or have an idea? Open an [Issue](https://github.com/samchuck12614/SamVideoEditor-Updates/issues) or email **mazadiqbal85@gmail.com**.

---

⭐ If this tool helps you, please star the repository!
