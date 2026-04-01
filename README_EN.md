<div align="center">

# Telegram Video Downloader

Chrome Extension for Downloading Videos and Images from Telegram Web

[📥 Download](https://github.com/hOvannes7/telegram-video-downloader/archive/refs/heads/main.zip) • [📖 Usage Guide](USAGE.md)

[Русский](README.md) | [English](README_EN.md)

</div>

## 🚀 Quick Start

### Installation

1. Open Chrome → `chrome://extensions/`
2. Enable **Developer Mode** (toggle in the top right)
3. Click **Load unpacked**
4. Select the extension folder
5. Done!

### Usage

1. Open [Telegram Web](https://web.telegram.org/)
2. Find a video or image to download
3. Click the **⬇ Download** button on the media
4. File will be saved to your Downloads folder

## 🔥 Features

- **Unlimited downloads** — no restrictions or limits
- **2 versions support** — works with `/a/` and `/k/` Telegram Web
- **Privacy** — no telemetry, no analytics, no external requests
- **Modern design** — buttons styled like Telegram
- **Fast loading** — uses Range API for efficient downloads

## 📁 Project Structure

```
├── manifest.json         # Extension config (Manifest V3)
├── background.js         # Service Worker
├── content_tg.js         # Content Script (download buttons)
├── inject.js             # Inject Script (file download logic)
├── popup.html            # Popup interface
├── popup.js              # Popup logic
└── icons/
    ├── 16.png            # Toolbar icon
    ├── 48.png            # Extensions page icon
    └── 128.png           # Details/Store icon
```

## 🎨 Design

### Download Buttons
- Semi-transparent blue background (`rgba(51,144,236,0.8)`)
- SVG download icon
- Hover effects
- Adaptive sizing for different screens

### Progress Bar
- Dark semi-transparent background
- Smooth animation
- Auto-hide after completion
- Dark theme support

## 🔒 Security & Privacy

- ✅ Direct download from Telegram CDN
- ✅ No external requests (except file downloads)
- ✅ No telemetry or analytics
- ✅ Minimal data storage (clientId only)
- ✅ No redirects on install/uninstall

## 🛠 Development

### Requirements
- Google Chrome or Chromium-based browser
- Developer mode for extensions

### Testing
1. Install extension in developer mode
2. Open Telegram Web
3. Test video and image downloads
4. Check both versions (`/a/` and `/k/`)

## ❓ FAQ

**Q: Are there any download limits?**  
A: No. The extension is completely unlimited.

**Q: Do I need to register?**  
A: No. Works immediately after installation.

**Q: Is it safe?**  
A: Yes. No data is sent to third parties. Files are downloaded directly from Telegram servers.

**Q: Where are files saved?**  
A: To your browser's default Downloads folder.

## 🔧 Troubleshooting

### Download button not appearing
1. Refresh Telegram Web page (F5)
2. Check that extension is enabled in `chrome://extensions/`
3. Make sure you're using `/a/` or `/k/` version

### Download stuck
1. Check your internet connection
2. Refresh page and try again

### Download failed error
1. File may be unavailable or deleted
2. Check that you're logged in to Telegram

## 📄 License

MIT License — free to use, modify, and distribute.

## ⚠️ Disclaimer

This extension is provided "as is", without any warranties. Use at your own risk. Authors are not responsible for any misuse.

---

<div align="center">

**[USAGE.md](USAGE.md)** — Detailed user guide  
**[README.md](README.md)** — Русская версия

</div>
