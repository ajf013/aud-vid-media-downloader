# ReClip — Premium Media Downloader

A state-of-the-art, self-hosted media downloader with a sleek web UI. Paste links from 1000+ sites and download as high-quality MP4 or MP3 with real-time feedback.

![Python](https://img.shields.io/badge/python-3.12+-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Gunicorn](https://img.shields.io/badge/server-Gunicorn-orange)

## ✨ New in Modern ReClip

- **🌓 Dual-Theme UI**: Seamlessly switch between a sophisticated Premium Dark mode and a clean, vibrant Light mode.
- **📈 Live Progress Tracking**: Watch your downloads in real-time with progress bars, speed metrics (MiB/s), and ETA estimates.
- **💎 Premium Design**: Built with glassmorphism, Outfit & Inter typography, and smooth AOS scroll animations.
- **🚀 Production Ready**: Pre-configured with Gunicorn and Docker for professional-grade deployment.
- **📱 Responsive & Social**: Mobile-first design with a custom footer for social integration.

## 🛠️ Tech Stack

- **Backend:** Python 3.12 + Flask
- **Production Server:** Gunicorn
- **Frontend:** Vanilla HTML5, CSS3 (Glassmorphism), JavaScript (ES6+)
- **Animations:** [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/)
- **Icons:** [Font Awesome 6](https://fontawesome.com/)
- **Engine:** [yt-dlp](https://github.com/yt-dlp/yt-dlp) + [ffmpeg](https://ffmpeg.org/)

## 🚀 Quick Start

### Local Setup
```bash
# Install dependencies
brew install yt-dlp ffmpeg

# Clone and run
git clone https://github.com/ajf013/aud-vid-media-downloader.git
cd aud-vid-media-downloader
./reclip.sh
```
Open **http://localhost:8899**.

### Docker Deployment
```bash
docker build -t reclip .
docker run -p 8899:8899 -e PORT=8899 reclip
```

## 🚂 Deploy to Railway

This project is optimized for [Railway](https://railway.app). 

1. Push this code to your GitHub.
2. Connect the repo to Railway.
3. Railway will automatically build the `Dockerfile` and provide a public URL.

## 🤝 Supported Platforms
Anything [yt-dlp supports](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md): YouTube, TikTok, Instagram, Twitter/X, LinkedIn, Reddit, and 1000+ more.

## ⚖️ Disclaimer
This tool is for personal use only. Please respect the copyright and TOS of the platforms you use.

## 📄 License
[MIT](LICENSE)
