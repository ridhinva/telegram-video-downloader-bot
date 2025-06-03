Telegram Multi-Platform Video Downloader Bot

A Telegram bot that allows users to download videos or audio from multiple social platforms (YouTube, TikTok, Instagram, Facebook, Twitter/X, Vimeo). Supports MP4 and MP3, quality selection, and multiple users concurrently.

✅ Features

Download videos from YouTube, Instagram, TikTok, Facebook, Twitter/X, Vimeo

YouTube MP4 (video) or MP3 (audio) selection

Choose video quality for YouTube downloads

Multi-user mode (isolated downloads per user)

No file size or duration restrictions

Automatic file cleanup


📦 Setup Instructions

1. Clone the repository

git clone https://github.com/yourusername/telegram-video-downloader-bot.git
cd telegram-video-downloader-bot

2. Install dependencies

Ensure you have Python 3.9+ and ffmpeg installed.

pip install -r requirements.txt

Install ffmpeg (if not already installed):

# On Ubuntu/Debian:
sudo apt install ffmpeg

# On macOS (via Homebrew):
brew install ffmpeg

3. Set environment variable

Create a .env file or set the environment variable directly:

export TELEGRAM_BOT_TOKEN=your_bot_token_here

Alternatively, use a .env file:

TELEGRAM_BOT_TOKEN=your_bot_token_here

4. Run the bot

python bot.py

📁 Project Structure

.
├── bot.py          # Main Telegram bot logic
├── config.py       # Configuration (token, formats, logging)
├── downloader.py   # Video/audio downloader logic
├── utils.py        # Utility helpers (URL parsing, cleaning)
├── README.md       # This file

💡 Usage

1. Send a supported video URL to the bot.


2. For YouTube:

Choose between MP4 (video) or MP3 (audio).

Select available quality.



3. Bot downloads and sends the file to your chat.



🛠 Built With

python-telegram-bot

yt-dlp

Python 3.9+


🔒 Privacy

No personal user data is stored.

All downloads are temporary and auto-deleted.


🧹 Cleanup

The bot automatically removes files after sending to keep the server clean.

📬 Contact / Issues

Create an issue on the GitHub repo or contact the bot owner.


---

License: MIT



✅ The README.md file is complete and includes:

📌 Feature list

⚙️ Setup and installation instructions

🧪 Usage guide

📁 File structure

🔒 Privacy details


Let me know if you want a version for deployment to platforms like Heroku, Docker, or Railway as well.

