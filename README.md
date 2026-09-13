# ⚡ Fast Downloader → Google Drive

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fLMNbsv0oiWxwXykzlGpjmklzjJtLG8H#scrollTo=8IhbrM-V5jVr)

A high-speed Google Colab notebook designed to download direct files, magnet/torrent links, and video URLs directly into your Google Drive using high-bandwidth cloud servers.

---

## 🌟 Key Features

- **🧲 Magnet & Torrent Support**: Fast torrent downloads using `aria2c` with automatic seed stopping timeout.
- **🎥 Video Downloader**: Download YouTube and generic video links via `yt-dlp`.
- **🚀 Multi-Threaded Direct Downloads**: Accelerated file downloads utilizing up to 16 parallel connections with `aria2c`.
- **☁️ Google Drive Integration**: Automatically mounts Google Drive and saves files straight into your designated folder (`ColabDownloads`).
- **🔗 Batch Downloading**: Process multiple links in one run (comma-separated input support).

---

## 🚀 Quick Start & Usage

1. **Open in Google Colab**: Click the [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fLMNbsv0oiWxwXykzlGpjmklzjJtLG8H#scrollTo=8IhbrM-V5jVr) badge or open [`fast_downloader.ipynb`](https://github.com/Bino369/ColabDownloads/blob/main/fast_downloader.ipynb) directly.
2. **Execute Environment Setup**:
   Run Cell 1 to install necessary dependencies (`aria2` and `yt-dlp`).
3. **Mount Google Drive**:
   Run Cell 2 and follow the prompt to grant authorization to mount `/content/drive`.
4. **Configure Destination Folder (Optional)**:
   By default, files will be saved to:
   ```text
   /content/drive/MyDrive/ColabDownloads
   ```
   You can change the `SAVE_FOLDER` variable in Cell 3 if desired.
5. **Start Downloading**:
   - Run the final cell.
   - Paste one or more links into the text prompt (separate multiple links with commas).
   - Press <kbd>Enter</kbd> to begin.

---

## 🛠️ Tools Used

- **[aria2c](https://aria2.github.io/)**: Multi-protocol & multi-source high-speed download utility.
- **[yt-dlp](https://github.com/yt-dlp/yt-dlp)**: Feature-rich command-line audio/video downloader.
- **[Google Colab](https://colab.research.google.com/)**: Cloud execution environment providing high network speeds.

---

## 📂 Project Structure

```text
.
├── fast_downloader.ipynb   # Main Google Colab Notebook
└── README.md               # Documentation
```
