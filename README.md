# Media Downloader

A free Chrome extension and local Windows tool. Copy a video link or share text, paste it into the extension, and the media will be downloaded to your computer.

Supported platforms: YouTube, Douyin, Bilibili, Xiaohongshu, NetEase Music, X, Envato.

## Download

Click to download: [MediaDownloader-Windows.zip](https://github.com/cy156906-glitch/XIAZAI/releases/download/v1.0.0/MediaDownloader-Windows.zip)

## Install

1. Download and extract the ZIP.
2. Double-click `安装开机自启.bat` once. This registers the local service to Windows auto-start, and starts it now. **After this, you never need to double-click anything else to start the service.**
3. Open Chrome extensions page (`chrome://extensions/`).
4. Turn on "Developer mode" in the top right.
5. Click "Load unpacked".
6. Select the `extension` folder inside the extracted directory.
7. Copy a video link, open the extension, paste the link, and click "Download".

## Requirements

- Windows 10 or 11.
- Google Chrome.
- A working internet connection.
- No Python installation is required. The ZIP already includes a portable Python 3.11 runtime.

## What each file does

- `安装开机自启.bat` — double-click once. Registers the service to start automatically on every Windows login, and starts it now. Silent (no window).
- `YOUTUBE下载器.bat` — manual start. A black window flashes briefly and closes. Use this if auto-start is disabled or the service was killed by antivirus.
- `卸载开机自启.bat` — removes the auto-start registration and stops the running service.
- `server.py` — the local HTTP service that handles downloads.
- `python\` — portable Python 3.11 runtime with all required packages pre-installed.
- `yt-dlp.exe` / `ffmpeg.exe` — used by the service to download media.
- `extension\` — the Chrome extension files.

## Compliance

This tool does not break DRM or bypass paid restrictions. Please only download content you have the right to access and save.

## Changelog

- v1.0.2: Launcher now silent (no black window). Added one-time auto-start installer and uninstaller. The extension always works after `安装开机自启.bat` is run once.
- v1.0.1: Bundled portable Python 3.11 inside the package. No Python install needed.
- v1.0.0: First public release.
