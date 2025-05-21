# Discord Video Downloader Bot

A Discord bot that:
- Detects video links from **Instagram, YouTube, Reddit, Facebook, TikTok**
- Downloads and compresses videos using `yt-dlp` and `ffmpeg`
- Uploads videos under 10MB directly to Discord
- Uploads larger videos to [transfer.sh](https://transfer.sh)

## 🚀 Features

- Smart domain detection
- Automatic video downloading
- Compression with FFmpeg if needed
- External upload fallback for large files

## 🛠️ Requirements

- Python 3.8+
- FFmpeg installed and available in your system PATH

## 🔧 Setup

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/discord-video-downloader-bot.git
   cd discord-video-downloader-bot
