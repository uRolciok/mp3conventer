# yt2mp3

Simple YouTube to MP3 converter with a graphical interface.

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## Features

- Download audio from YouTube and convert to MP3
- Quality selection (128 / 192 / 256 / 320 kbps)
- Custom save folder
- Download progress bar
- Dark Gruvbox-style interface

## Requirements

- **Python 3.8+** — [download here](https://www.python.org/downloads/)
- **FFmpeg** — required for audio conversion

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/uRolciok/mp3conventer.git
cd mp3conventer
```

### 2. Install Python dependencies

```bash
pip install -r requirements.txt
```

### 3. Install FFmpeg

**Windows (winget):**
```bash
winget install Gyan.FFmpeg
```

**Windows (manual):**
1. Download from [ffmpeg.org](https://ffmpeg.org/download.html)
2. Extract and add the `bin` folder to your PATH

**Linux:**
```bash
sudo apt install ffmpeg
```

**macOS:**
```bash
brew install ffmpeg
```

## Usage

```bash
python conventer.py
```

1. Paste a YouTube video link
2. Select audio quality (default: 192 kbps)
3. Optionally change the save folder
4. Click **"pobierz mp3"**
5. The MP3 file will appear in the selected folder

## License

MIT
