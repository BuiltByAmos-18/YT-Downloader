# YT-Downloader
# 🧰 YT-Downloader (CLI Tool)

### 📖 Project Description
**YT-Downloader** is a Python-based command-line tool that allows users to **download YouTube videos or movies directly from a link** and **save them to their device storage**.  
It is simple, fast, and works perfectly in terminal environments, including **Termux on Android**.

---

### 🚀 Features
- 🎥 Download any YouTube video or full movie using a link  
- 💾 Save videos directly to your phone or system storage  
- ⚡ Lightweight and easy-to-use command-line interface  
- 🐍 Built with Python and the `pytube` library  
- 💻 Works on **Windows, Linux, macOS**, and **Termux (Android)**  

---

### 🛠️ Tech Stack
- **Language:** Python  
- **Library:** pytube  
- **Interface:** Command Line (Terminal)

---

### 📦 Installation & Setup

#### **For Termux Users (Android):**
1. Update Termux packages:
   ```bash
   pkg update && pkg upgrade

2. Install Python:

   pkg install python


3. Install Git:

   pkg install git


4. Clone the repository:

   git clone https://github.com/your-username/YT-Downloader.git


5. Navigate to the project folder:

   cd YT-Downloader


6. Install dependencies:

   pip install pytube




---

▶️ How to Use

1. Run the downloader script:

   python downloader.py


2. Paste the YouTube video link when prompted.


3. The video will download automatically to your device storage (default download folder).




---

📁 Folder Structure

YT-Downloader/
│
├─ downloader.py      # Main Python script
├─ README.md          # Project documentation
└─ requirements.txt   # Python dependencies (optional)


---

📜 License

This project is open-source and free for educational and personal use.


---

💡 Notes

Works best with stable internet connection.

Supports downloading videos in different resolutions (if supported by YouTube).

Termux users may need to grant storage permissions:

   termux-setup-storage
