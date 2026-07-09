# Media Downloader

A free Chrome extension and local Windows tool. Copy a video link or share text, paste it into the extension, and the media will be downloaded to your computer.

Supported platforms: YouTube, Douyin, Bilibili, Xiaohongshu, NetEase Music, X, Envato.

## Download

Click to download: [MediaDownloader-Windows.zip](https://github.com/cy156906-glitch/XIAZAI/releases/download/v1.0.0/MediaDownloader-Windows.zip)

## Install

1. Download and extract the ZIP.
2. Double-click `YOUTUBE下载器.bat`. A black window will open and the local service will start.
3. Open the Chrome extensions page (`chrome://extensions/`).
4. Turn on "Developer mode" in the top right.
5. Click "Load unpacked".
6. Select the `extension` folder inside the extracted directory.
7. Copy a video link, open the extension, paste the link, and click "Download".

## Requirements

- Windows 10 or 11.
- Google Chrome.
- A working internet connection.
- No Python installation is required. The ZIP already includes a portable Python 3.11 runtime.

## Compliance

This tool does not break DRM or bypass paid restrictions. Please only download content you have the right to access and save.

## Changelog

- v1.0.1: Bundled portable Python 3.11 inside the package. No Python install needed. The launcher now auto-detects the bundled Python first, then falls back to the system Python. Better error messages.
- v1.0.0: First public release.
