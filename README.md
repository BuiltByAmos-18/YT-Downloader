Perfect, Amos 🔥
Main tumhe complete GitHub-ready project de raha hoon —
✅ README.md (copy-friendly, GitHub format)
✅ downloader.py (Termux + desktop dono ke liye ready)


---

🧰 YT-Downloader (CLI Tool)

📖 Project Description

YT-Downloader is a Python-based command-line tool that lets you download YouTube videos in HD and save them directly to your device storage.
It’s lightweight, fast, and works perfectly in Termux on Android as well as on Windows, macOS, and Linux.


---

🚀 Features

🎥 Download any YouTube video using a direct link

⚙️ Choose your preferred quality (360p, 720p, 1080p, etc.)

💾 Automatically saves in your storage folder

🐍 Built using Python & pytube

💻 Works across all platforms (Windows / Linux / macOS / Termux)



---

🛠️ Tech Stack

Language: Python

Library: pytube

Interface: Command Line



---

📦 Installation & Setup

For Termux (Android):
```
pkg update && pkg upgrade
```
```
pkg install python
```
```
pkg install git
```
```
git clone https://github.com/your-username/YT-Downloader.git
```
```
cd YT-Downloader
```
```
pip install pytube
```

Grant Termux access to your storage (first time only):
```
termux-setup-storage
```

---

▶️ How to Use
```
python downloader.py
```
1. Paste your YouTube video link when asked.


2. Choose your preferred video quality.


3. The video will be downloaded to your device storage automatically.



Default download location for Termux:
```
/storage/emulated/0/Download/YT-Downloads/
```

---

📁 Folder Structure
```
YT-Downloader/
│
├── downloader.py       # Main Python script
├── README.md           # Documentation
└── requirements.txt    # Python dependencies (optional)
```

---

📜 License

This project is open-source and free for educational or personal use.


---

💡 Notes

Works best with a stable internet connection.

Supports HD video downloads (if available).

Termux users may need to allow storage permission using termux-setup-storage.

✅ Usage Example (Termux)
```
python downloader.py
```
🎬 Enter YouTube video link: https://youtu.be/abcd1234
Available qualities:
1. 360p - 15.3 MB
2. 720p - 45.6 MB
3. 1080p - 95.2 MB
<br>
🔽 Enter the number of your preferred quality: 2
<br>
📥 Downloading...
<br>
✅ Download complete!
<br>
📂 Saved to: /storage/emulated/0/Download/YT-Downloads/

