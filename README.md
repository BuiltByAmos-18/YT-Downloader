#  YT-Downloader  Fast YouTube Downloader (CLI)

<p align="center">
  <img alt="YT-Downloader" src="https://www.google.com/search?client=ms-android-oppo&sca_esv=125bfe73879b54c9&sxsrf=AE3TifN3d5NTy58tqmygzgd3D5RFltvaVA:1760937631660&udm=2&fbs=AIIjpHxCtmkhHKu27CW9pNYJlh4RjL2XNN7H2eGEwe1vRehTgx2PNlKqSsUGSlpdjHDY7h70mMYCoGv1f44Oel0GP7mA6HDy9g4ljJcq3MSuaKJwRg1a_seTj-48Y8L5XapNfX-TULGM9tHeGAPiR97l8PfwcPw0IevcUQSQdHWS2LXb_0OGNw2HX5yY-i4jmMHhtT3eBYw0W3HIhW01fet1ln5K-fbEO_nag3iG0qLCSLCVbBOKgmI&q=img+tool+for+github+yt+download&sa=X&ved=2ahUKEwiD1Ybwg7KQAxWSSmwGHY_EOBgQtKgLegQIFBAB&biw=597&bih=1224&dpr=1.21#sv=CAMSxgQamQQK8wEKuQEStgEKd0FMa3RfdkdWd25TRl9wVHB0eExwcGdGdkNqeWFLeFVaUjViemNRN1p2Q1VvSV9hQVRuM3A0SXl5azN2NHlLNENJWWZhMExYMmJGWUVkLVpoaTRzYVRZN2FMb0dVVGRJMUpnMmFvbjNWNllwQ0wtQ2ZHbGdzS21nEhc2TWIxYU1iZEdlMndzZU1QX3ZIV2tBdxoiQUZNQUdHcTZJTmNsZ0ZXam1RYl92X25WRi11NklQZDRlZxIDODQ5GgEzIiQKAXESH2ltZyB0b29sIGZvciBnaXRodWIgeXQgZG93bmxvYWQiBwoDdGJzEgASjgIKzwESzAEKjAFBTGt0X3ZGdEZJTlBDaXFIMFVuRDJXb3VNZnB1U1FZX2Zsek9sSFJPZms0Z1NreVQwcEtlWjV4UkNGalFpMDRJNFBZeDZDQm8xUW9qbTJid0ZocHRzYXJkVTZBOWhkb0xqX1pmcDVzMFkxUlp3U3hzWnFEVzFWQ0h2TGtYa0dUeU4wMWtPUncya0xXcxIXNk1iMWFNYmRHZTJ3c2VNUF92SFdrQXcaIkFGTUFHR3FTMklmeGdvRGZ5YUJmdGVwUUFfY2VXaTBKTmcSBDQ2OTgaATMiGAoGaW1nZGlpEg4wSDRvck9SbUtiMDBDTSIXCgVkb2NpZBIOMEF2TzZGZUJobjNPSE0qEGUtMEg0b3JPUm1LYjAwQ00gBCokCg5Pekh4YlZYY1FhUGZJTRIQZS0wSDRvck9SbUtiMDBDTRgAMAEYByCM9uPUBzABSgoIAhACGAIgAigC" width="720"/>
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python" />
  <img alt="Platform" src="https://img.shields.io/badge/Platform-Termux%20%7C%20Linux%20%7C%20Windows%20%7C%20macOS-orange" />
  <img alt="License" src="https://img.shields.io/badge/License-Open--Source-green" />
  <img alt="Repo" src="https://img.shields.io/badge/Repo-BuiltByAmos--18/YT--Downloader-brightgreen" />
</p>

A fast, lightweight, and friendly terminal tool to download YouTube videos, audio, and playlists directly to your device. Built for Termux (Android), Linux, Windows, and macOS.

Why you'll love it
- Small, fast, and scriptable
- Download HD / 4K videos, extract audio (MP3/M4A)
- Playlist support, thumbnails, subtitles
- Clean filenames, download history, and duplicate avoidance

---

## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Requirements](#requirements)
- [Installation](#installation)
  - [Termux (Android)](#termux-android)
  - [Linux / macOS / Windows](#linux--macos--windows)
- [Quick Start](#quick-start)
- [Usage Examples](#usage-examples)
- [Folder Structure](#folder-structure)
- [Tips & Troubleshooting](#tips--troubleshooting)
- [Contributing](#contributing)
- [License & Author](#license--author)

---

## Features
-  Download videos in multiple qualities (360p / 720p / 1080p / 4K when available)
-  Extract audio and save as MP3 or M4A
-  Download full playlists automatically
-  Download thumbnails automatically
-  Download subtitles (when present)
-  Clean, colored CLI output with progress and ETA
-  Custom download folder support
-  Avoids duplicate downloads using a history log
-  Built with Python and pytube, with optional moviepy for conversions

---

## Screenshots
> Replace these placeholders with real screenshots/GIFs of the app running for best presentation.

<p align="center">
  <img alt="terminal-sample" src="https://user-images.githubusercontent.com/00000000/placeholder-screenshot-1.png" width="700"/>
</p>

---

## Requirements
- Python 3.10 or newer
- Internet access
- Recommended: 100+ MB free disk space for large downloads

Python libraries (installed via requirements.txt):
- pytube
- moviepy (optional, for audio conversions)
- colorama
- requests

---

## Installation

Important: This README uses the actual repository URL. Clone the repo from your GitHub account:

Repository:
```
https://github.com/BuiltByAmos-18/YT-Downloader.git
```

### Termux (Android)
1. Update and install essentials:
```bash
pkg update && pkg upgrade -y
pkg install python git -y
```
2. Clone the repo:
```bash
git clone https://github.com/BuiltByAmos-18/YT-Downloader.git
cd YT-Downloader
```
3. Install Python dependencies:
```bash
pip install -r requirements.txt
```
4. Allow Termux to access storage (first time only):
```bash
termux-setup-storage
```

### Linux / macOS / Windows
1. Ensure Python 3.10+ is installed.
2. Clone the repo:
```bash
git clone https://github.com/BuiltByAmos-18/YT-Downloader.git
cd YT-Downloader
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```

---

## Quick Start

Run the main script:
```bash
python downloader.py
```

You'll see an interactive menu:
- Download Video
- Download Audio
- Download Playlist
- Exit

Follow the prompts to paste a YouTube URL and choose a quality or audio format.

---

## Usage Examples

Example: Download a single video (interactive)
```
python downloader.py
```
Then paste:
```
https://youtu.be/abcd1234
```
Choose quality (e.g., 720p) and wait for the progress bar.

Example: Typical flow shown in-menu
- Available qualities will be listed with sizes
- Enter the number for preferred quality
- Script downloads video, saves thumbnail and subtitle (if available)
- Entry is written to downloads.log to avoid redownloading

Notes:
- Audio extraction to MP3/M4A uses moviepy (install moviepy if you need conversion)
- If a requested resolution is unavailable, the script will fall back to the best matching stream

---

## Folder Structure
```
YT-Downloader/

 downloader.py       # Main Python script (interactive CLI)
 requirements.txt    # Python dependencies
 downloads.log       # Download history (auto-generated)
 thumbnails/         # Downloaded video thumbnails
```

Default download folders:
- Termux: /storage/emulated/0/Download/YT-Downloads/
- Desktop: ./YT-Downloads/ (project directory)

You can change the download folder inside downloader.py (look for DOWNLOAD_DIR constant or prompt).

---

## Tips & Troubleshooting
- Stable internet yields smooth downloads â€” large files may take long on mobile networks.
- If download fails, try a different stream (audio-only vs progressive vs adaptive).
- On Windows, use `python` or `py` depending on your Python setup.
- If audio conversion fails, ensure ffmpeg is installed (moviepy uses it).
  - On Linux: sudo apt install ffmpeg
  - On Termux: pkg install ffmpeg
- To clear the log and re-download, delete downloads.log (or edit it to remove entries).

---

## Contributing
Contributions, improvements, and bug fixes are welcome!
1. Fork the repo
2. Create a feature branch: git checkout -b feat/your-feature
3. Commit your changes and push: git push origin feat/your-feature
4. Open a Pull Request with a clear description of the change

Please keep code readable and include tests or examples when applicable.

---

## License & Author
By Amos Anand (BuiltByAmos-18)

- GitHub: https://github.com/BuiltByAmos-18
- Portfolio: https://builtbyamos.great-site.net
- Instagram: https://instagram.com/@builtbyamos.0

This project is open-source feel free to use and modify under the project license.

---

If you want, I can:
- Add real screenshots or a demo GIF to this README (you can upload images to the repo or link externally).
- Add a badge for PyPI or CI if you plan to publish.
- Add a small CONTRIBUTING.md and CODE_OF_CONDUCT.md for maintainers.

Tell me which improvements you want next and I'll update the files accordingly.
