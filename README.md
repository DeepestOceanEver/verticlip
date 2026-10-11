# 📼 verticlip - Turn Long Videos Into Viral Clips

[![Download verticlip](https://img.shields.io/badge/Download-verticlip-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DeepestOceanEver/verticlip/releases)

## 👋 Welcome to verticlip

verticlip takes your long videos and turns them into short, vertical, 9:16 clips ready for TikTok, YouTube Shorts, and Instagram Reels. It automatically detects who's speaking, adds captions, and crops the video to keep the speaker in frame. Everything runs on your own computer—no internet connection needed, no API keys, no monthly fees.

## 🎯 What Does verticlip Do?

Imagine you have a 30-minute podcast, lecture, or gameplay video. You want to share the best moments on social media, but editing takes hours. verticlip does the heavy lifting for you:

- **Upload or select a video** – Any long video file works
- **Automatic speaker detection** – Finds who's talking and tracks them
- **Smart cropping** – Converts to vertical 9:16 format, keeping the speaker centered
- **Automatic captions** – Adds word-by-word captions using Whisper (runs locally)
- **Export ready-to-post clips** – Get multiple short clips you can upload immediately

## 🚀 Getting Started

Follow these simple steps to get verticlip running on your Windows computer.

### 📥 Step 1: Download verticlip

Visit this link to download the application: [https://github.com/DeepestOceanEver/verticlip/releases](https://github.com/DeepestOceanEver/verticlip/releases)

Click the download button for the latest release. Save the file to your computer.

### 💻 Step 2: Run the Application

Once the download is complete, locate the downloaded file and double-click it to open. The application will start.

### ⚙️ Step 3: First-Time Setup

When you first launch verticlip, it will ask you to install two free components automatically:
- **Whisper** – Handles speech recognition and caption generation
- **Ollama** – Powers the smart speaker tracking and clip selection

These install automatically in the background. You don't need to do anything except wait a few minutes.

### 🎬 Step 4: Start Clipping

Once setup is complete, you'll see the main screen. Click **"Select Video"** to choose your long video file. verticlip will analyze the video, find the best moments, and generate your vertical clips.

## 🛠️ System Requirements

To run verticlip smoothly, your computer should have:

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| Operating System | Windows 10 (64-bit) | Windows 11 |
| Processor | Intel Core i5 / AMD Ryzen 5 | Intel Core i7 / AMD Ryzen 7 |
| RAM | 8 GB | 16 GB |
| Storage | 5 GB free space | 20 GB free space |
| Graphics | Any GPU | NVIDIA GTX 1060 or better |

Note: verticlip works on Mac and Linux too, but Windows is fully supported with automatic installers.

## ✨ Key Features

### 🤖 Local-First Privacy
All processing happens on your computer. Your videos never leave your hard drive. No cloud uploads, no tracking, no data collection.

### 🧠 Smart Speaker Tracking
Using Ollama's AI models, verticlip identifies who is speaking in the video and dynamically crops the frame to keep them centered. Even if they move around, the clip follows them.

### 📝 Accurate Captions
Whisper generates precise, timestamped captions for every word spoken. Subtitles are burned directly into the video, making clips accessible and engaging.

### ⚡ Batch Processing
Feed verticlip a full-length video and get multiple clips in one go. Choose the length (15, 30, or 60 seconds) and let the AI pick the most engaging segments.

### 🎛️ Customization Options
- Choose output resolution (1080x1920, 720x1280, or 480x854)
- Select clip duration
- Toggle captions on/off
- Adjust caption style and position
- Preview clips before exporting

### 🔄 Regular Updates
The verticlip team regularly releases updates to improve accuracy, add new features, and support more video formats.

## ❓ Frequently Asked Questions

### Do I need an API key or internet connection?
No! verticlip is fully local. It works offline and requires no API keys.

### What video formats are supported?
verticlip supports MP4, MOV, AVI, MKV, and most common video formats. It uses FFmpeg under the hood for maximum compatibility.

### How long does processing take?
Processing time depends on your video length and computer speed. A 10-minute video typically takes 5-10 minutes to analyze and export on a mid-range PC.

### Can I use verticlip for commercial content?
Yes, verticlip is free to use for personal and commercial purposes. It's open-source software (GPL license).

### What if I run into an error?
Check the **"Help"** menu in the application. You can also visit the GitHub repository and search for your issue in the Issues tab.

## 📖 Step-by-Step Tutorial

### Creating Your First Clip

1. **Launch verticlip** – Double-click the app icon to start
2. **Click "Select Video"** – Browse to your long video file and select it
3. **Wait for analysis** – A progress bar shows AI analysis (speaker detection, speech transcription)
4. **Review suggested clips** – verticlip shows a list of recommended segments with previews
5. **Choose your clips** – Check the boxes next to the clips you want, or adjust the length slider
6. **Click "Export Clips"** – Your vertical videos are saved to the **"Output"** folder
7. **Upload to social media** – Share your new clips directly to TikTok, YouTube Shorts, or Instagram

### Tips for Best Results

- Use videos with clear, single-speaker segments for most accurate speaker tracking
- Higher resolution source videos produce crisper vertical crops
- Reduce clip length if the speaker moves a lot
- Ensure good audio quality for accurate captions

## 🆘 Getting Help

If you need assistance:

1. **In-app Help** – Press F1 or click the "?" icon
2. **GitHub Issues** – [Report bugs or ask questions](https://github.com/DeepestOceanEver/verticlip/issues)
3. **Documentation** – Check the `docs` folder in the repository

## 📊 Version History

| Version | Date | Highlights |
|---------|------|------------|
| 1.2.0 | 2025-06-01 | Added batch export, improved caption styling |
| 1.1.0 | 2025-04-15 | Faster processing, better speaker tracking |
| 1.0.0 | 2025-02-10 | Initial public release |

## 🙏 Acknowledgements

verticlip builds on amazing open-source tools:
- [OpenAI Whisper](https://github.com/openai/whisper) – Speech recognition
- [Ollama](https://ollama.ai) – Local AI model runner
- [FFmpeg](https://ffmpeg.org) – Video processing

## 📜 License

verticlip is released under the MIT License. See the `LICENSE` file for details.

---

**Ready to start creating?** [Download verticlip now](https://github.com/DeepestOceanEver/verticlip/releases) and turn your boring vertical videos into engagement gold.

Keywords: ffmpeg, local-first, ollama, python, shorts, tiktok, video, video-editing, whisper, youtube-shorts