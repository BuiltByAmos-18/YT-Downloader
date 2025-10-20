
---

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python" alt="Python Badge">
  <img src="https://img.shields.io/badge/Platform-Termux%20%7C%20Linux%20%7C%20Windows-orange" alt="Platform Badge">
  <img src="https://img.shields.io/badge/License-Open--Source-green" alt="License Badge">
</p>

<h1 align="center">🧰 YT-Downloader (CLI Tool)</h1>

<p align="center">
  🎬 <b>YT-Downloader</b> is a fast, lightweight, and powerful Python-based terminal tool to <b>download YouTube videos, audio, and playlists</b> directly to your device storage.  
  Works on <b>Termux (Android)</b>, <b>Linux</b>, <b>Windows</b>, and <b>macOS</b>.  
  Download videos in HD, extract audio, download subtitles, and save thumbnails easily! ⚡
</p>

---

## 📖 Project Description

**YT-Downloader** is designed for anyone who wants to quickly save YouTube content to their device.  
It supports:

- High-quality video downloads (360p / 720p / 1080p / 4K)  
- Audio-only downloads (MP3/M4A)  
- Playlist downloads  
- Automatic thumbnail and subtitle downloads  
- Colored terminal output for easy navigation  
- Custom download folders and automatic file name cleaning  
- Download history log  

This tool is perfect for Termux users on Android and also works on Linux, Windows, and macOS terminals.

---

## 🚀 Features

- 🎥 Download YouTube videos in HD/Full HD/4K  
- 🎵 Download audio-only (MP3/M4A)  
- 📝 Download subtitles (if available)  
- 📂 Save videos/audio to a custom folder  
- 🖼 Automatically download video thumbnails  
- 📑 Download full playlists  
- ⚡ Colored CLI output & progress bar with ETA  
- 📝 Maintains a download history log  
- ✅ Avoid duplicate downloads  
- 🐍 Built with Python & pytube library  

---

## 🛠 Tech Stack

| Component | Description |
|-----------|-------------|
| 🐍 Language | Python |
| 📦 Libraries | pytube, moviepy, colorama, requests |
| 💻 Interface | Command Line (Terminal/CLI) |

---

## 📦 Installation & Setup

### **1️⃣ Termux (Android)**

1. Update packages:

```
pkg update && pkg upgrade -y
```
2. Install Python & Git:


```
pkg install python git -y
```
3. Clone the repository:


```
git clone https://github.com/your-username/YT-Downloader.git
cd YT-Downloader
```
4. Install dependencies:

```
pip install -r requirements.txt
```
5. Allow Termux storage access (required first time):


```
termux-setup-storage
```

---
### **2️⃣ Linux / Windows / macOS**

1. Ensure Python 3.10+ is installed.


2. Clone the repository:


```
git clone https://github.com/your-username/YT-Downloader.git
cd YT-Downloader
```
3. Install dependencies:


```
pip install -r requirements.txt
```

---

### *▶️ How to Use*

Run the Python script:
```
python downloader.py
```
### Menu Options

<h1>
========== YT-Downloader ==========<br>
1️⃣ Download Video<br>
2️⃣ Download Audio<br>
3️⃣ Download Playlist<br>
4️⃣ Exit<br>
==================================
  <br>
</h1>
Download Video → Enter YouTube link, choose resolution or auto-highest quality.

Download Audio → Extract audio from video, save as MP3/M4A.

Download Playlist → Download all videos in the playlist automatically.

Exit → Close the program.


### Example (Termux/Linux)
```
python downloader.py
```
🎬 Enter YouTube video link: https://youtu.be/abcd1234
Available qualities:
1. 360p - 15.3 MB
2. 720p - 45.6 MB
3. 1080p - 95.2 MB<br>
🔽 Enter the number of your preferred quality: 2 <br>
📥 Downloading...<br>
✅ Download complete!<br>
📂 Saved to: ```/storage/emulated/0/Download/YT-Downloads/```


---

### 📁 Folder Structure
```
YT-Downloader/
│
├── downloader.py       # Main Python script
├── requirements.txt    # Python dependencies
├── downloads.log       # Download history (auto-generated)
└── thumbnails/         # Downloaded video thumbnails
```

---

<h3 align="center">💡 Notes & Tips</h3><br>

✨ <b>Stable Internet:</b> Works best with a stable internet connection for smooth downloads.<br>
📁 <b>Default Download Folder:</b><br>
&nbsp;&nbsp;• Termux: <code>/storage/emulated/0/Download/YT-Downloads/</code><br>
&nbsp;&nbsp;• Linux/Desktop: <code>YT-Downloads</code> folder in project directory<br>
🔐 <b>Storage Permission (Termux only):</b> Run <code>termux-setup-storage</code> once to allow access.<br>
🎥 <b>Video Quality:</b> Supports HD, Full HD, and 4K downloads if available.<br>
🎵 <b>Audio Download:</b> Converts video to MP3/M4A automatically when selected.<br>
📝 <b>Filename Cleaning:</b> Automatically removes illegal characters for safe storage.<br>
📂 <b>Custom Folders:</b> You can set your own download folder inside the script if needed.<br>
📑 <b>Playlist Downloads:</b> Automatically skips already downloaded videos to avoid duplicates.<br>
🌟 <b>Pro Tip:</b> Always check your internet connection and storage space before downloading large videos.<br>

<h3 align="center">
  🧑‍💻 Amos Anand <br>
  🌍 Garhwa → Bangalore | 💼 Developer, Designer & YouTuber<br>
  📫 
  
  <a href="https://github.com/BuiltByAmos-18" target="_blank">
    GitHub
    ---
  </a> • 
  🎥 <a href="https://instagram.com/@builtbyamos.0" target="_blank">
    Instagram
    ---
  </a> • 
  🌐 <a href="https://builtbyamos.great-site.net" target="_blank">
    Portfolio
  ---
  </a>
</h3>

<p align="center">
  ⭐ If you like this project, give it a star on GitHub! ⭐
</p>
---

<h3 align="center">✨ Highlights of This README ✨</h3><br>

🌟 <b>Centered Title & Badges:</b> Gives a professional and visually appealing look.<br>
🎨 <b>Colorful Emojis:</b> Makes each section lively and easy to scan.<br>
📦 <b>Clear Installation Instructions:</b> Step-by-step guide for Termux, Linux, and Desktop users.<br>
🎬 <b>Detailed Usage Examples:</b> Shows how to run the script and download videos/audio/playlists.<br>
🗂 <b>Professional Folder Structure:</b> Clearly explains all project files and directories.<br>
💡 <b>Tips & Notes:</b> Beginner-friendly tips to avoid errors and optimize downloads.<br>
🧑‍💻 <b>Clickable Author Section:</b> Social media links are interactive and center-aligned.<br>
⭐ <b>GitHub Star Encouragement:</b> Encourages users to star the project for support.<br>
