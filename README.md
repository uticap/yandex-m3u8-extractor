cat > README.md << 'EOF'
# Yandex m3u8 Extractor

[![Python Version](https://img.shields.io/badge/python-3.6%2B-blue)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

Extract video streams from public Yandex.Disk links and save as m3u8 playlist.

## 🚀 Features

- Extract video files (mp4, mkv, avi, mov, webm) from public Yandex.Disk folders
- Generate m3u8 playlists compatible with VLC, MPV, and other video players
- Simple command-line interface
- Shows file sizes and counts

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/uticap/yandex-m3u8-extractor.git
cd yandex-m3u8-extractor

# Install dependencies
pip install -r requirements.txt
