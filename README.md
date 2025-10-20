
---

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python" alt="Python Badge">
  <img src="https://img.shields.io/badge/Platform-Termux%20%7C%20Windows%20%7C%20Linux-orange" alt="Platform Badge">
  <img src="https://img.shields.io/badge/License-Open--Source-green" alt="License Badge">
</p>

<h1 align="center">🧰 YT-Downloader (CLI Tool)</h1>
<p align="center">
  🎬 A fast & powerful Python-based terminal tool to <b>download YouTube videos or movies in HD</b> and save them directly to your 📱 phone or 💻 system storage.  
  <br>Lightweight • Cross-Platform • Termux Supported ⚡
</p>

---

## 🚀 Features

- 🎥 Download any YouTube video or full movie using a link  
- ⚙️ Choose your preferred quality (360p, 720p, 1080p, etc.)  
- 💾 Automatically saves videos in your device storage  
- 🐍 Built using Python & the `pytube` library  
- 💻 Works on **Windows**, **Linux**, **macOS**, and **Termux (Android)**  

---

## 🛠️ Tech Stack
| Component | Description |
|------------|--------------|
| 🐍 **Language** | Python |
| 📦 **Library** | pytube |
| 💻 **Interface** | Command Line (CLI) |

---

## 📦 Installation & Setup

### 📱 **For Termux (Android):**

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
1️⃣ Paste your YouTube video link when asked.
2️⃣ Choose your preferred video quality.
3️⃣ The video will download automatically to your storage.

📂 Default Termux Download Path:
```
/storage/emulated/0/Download/YT-Downloads/
```

---

📁 Folder Structure
```
YT-Downloader/
│
├── downloader.py       # Main Python script
├── README.md           # Project documentation
└── requirements.txt    # Python dependencies (optional)
```

---

💡 Notes

🌐 Works best with a stable internet connection.

📹 Supports HD & Full HD resolutions (if available).

⚙️ Termux users must run:
```
termux-setup-storage
```


---

✅ Example (Termux)
```
python downloader.py
```
🎬 Enter YouTube video link: https://youtu.be/abcd1234
Available qualities:
1. 360p - 15.3 MB
2. 720p - 45.6 MB
3. 1080p - 95.2 MB
🔽 Enter the number of your preferred quality: 2
📥 Downloading...
✅ Download complete!
📂 Saved to: /storage/emulated/0/Download/YT-Downloads/


---

📜 License

This project is open-source and free for educational or personal use.
You’re welcome to modify, improve, or share it!


---

🧑‍💻 Author

Amos Anand
🌍 Garhwa → Bangalore | 💼 Developer, Designer & YouTuber
📫 GitHub • 🎥 YouTube • 🌐 Portfolio


---

<p align="center">
  ⭐ If you like this project, give it a star on GitHub! ⭐
</p>
```
---

💡 What’s special about this version:

✅ Uses emojis + centered headings
✅ Includes badges (Python, platform, license)
✅ Perfect spacing for readability
✅ Looks professional on both mobile & desktop GitHub view
✅ Copy button auto-enables for all code blocks


---

Would you like me to add an image banner or animated GIF demo section (to make it look like premium GitHub repos)?
Example: a preview of YT-Downloader running in Termux or terminal.


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

