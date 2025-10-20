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

pkg update && pkg upgrade

pkg install python

pkg install git

git clone https://github.com/your-username/YT-Downloader.git

cd YT-Downloader

pip install pytube

Grant Termux access to your storage (first time only):

termux-setup-storage


---

▶️ How to Use

python downloader.py

1. Paste your YouTube video link when asked.


2. Choose your preferred video quality.


3. The video will be downloaded to your device storage automatically.



Default download location for Termux:

/storage/emulated/0/Download/YT-Downloads/


---

📁 Folder Structure

YT-Downloader/
│
├── downloader.py       # Main Python script
├── README.md           # Documentation
└── requirements.txt    # Python dependencies (optional)


---

📜 License

This project is open-source and free for educational or personal use.


---

💡 Notes

Works best with a stable internet connection.

Supports HD video downloads (if available).

Termux users may need to allow storage permission using termux-setup-storage.



---

🧩 downloader.py

import os
from pytube import YouTube

# Output folder for Termux / Android
DOWNLOAD_FOLDER = "/storage/emulated/0/Download/YT-Downloads/"

def create_download_folder():
    if not os.path.exists(DOWNLOAD_FOLDER):
        os.makedirs(DOWNLOAD_FOLDER)

def download_video():
    try:
        link = input("\n🎬 Enter YouTube video link: ").strip()
        yt = YouTube(link)

        print(f"\n📄 Title: {yt.title}")
        print(f"🎥 Author: {yt.author}")
        print(f"⏱ Duration: {round(yt.length / 60, 2)} minutes")

        # List available streams
        print("\nAvailable qualities:")
        streams = yt.streams.filter(progressive=True, file_extension='mp4').order_by('resolution').desc()
        for i, stream in enumerate(streams, 1):
            print(f"{i}. {stream.resolution} - {round(stream.filesize / (1024*1024), 2)} MB")

        choice = int(input("\n🔽 Enter the number of your preferred quality: "))
        selected_stream = streams[choice - 1]

        print("\n📥 Downloading...")
        create_download_folder()
        selected_stream.download(output_path=DOWNLOAD_FOLDER)
        print(f"\n✅ Download complete!\n📂 Saved to: {DOWNLOAD_FOLDER}")

    except Exception as e:
        print(f"\n❌ Error: {str(e)}")
        print("⚠️ Make sure you entered a valid YouTube link and have internet access.")

if __name__ == "__main__":
    download_video()


---

✅ Usage Example (Termux)

python downloader.py

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

Would you like me to also create the requirements.txt file (so GitHub users can just do pip install -r requirements.txt)?

