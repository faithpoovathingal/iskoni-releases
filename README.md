<div align="center">

  <img src="https://raw.githubusercontent.com/faithpoovathingal/iskoni-releases/main/assets/logo.png" alt="ISKONI Logo" width="280" height="150" style="border-radius: 45px; box-shadow: 0 10px 30px rgba(229, 9, 20, 0.1);" onerror="this.src='https://images.unsplash.com/photo-1536440136628-849c177e76a1?w=200&auto=format&fit=crop&q=80'" />

  # ISKONI for macOS
  
  **A high-performance, lightweight cinema & TV streaming desktop client.**

  [![Latest Release](https://img.shields.io/github/v/release/faithpoovathingal/iskoni-releases?color=E50914&label=Version&style=for-the-badge)](https://github.com/faithpoovathingal/iskoni-releases/releases/latest)
  [![Platform](https://img.shields.io/badge/Platform-macOS%20Apple%20Silicon%20(M1%2FM2%2FM3%2FM4)-black?style=for-the-badge&logo=apple)](https://github.com/faithpoovathingal/iskoni-releases/releases/latest)
  [![License](https://img.shields.io/badge/Status-Active%20v1.0.5-red?style=for-the-badge)](https://github.com/faithpoovathingal/iskoni-releases)

  <br />

  <a href="https://github.com/faithpoovathingal/iskoni-releases/releases/latest">
    <img src="https://img.shields.io/badge/Download_Installer_(.pkg)-E50914?style=for-the-badge&logo=apple&logoColor=white" height="40" alt="Download PKG" />
  </a>

</div>

---

## 📽️ About ISKONI

**ISKONI** is an Electron and React-powered desktop streaming hub engineered for fast, clean, bufferless entertainment. Built with a unified dark UI, seamless TMDB discovery, in-player episode switching, local subtitle integration, intelligent duration telemetry filtering, native settings management, and background over-the-air updates.

---

## ✨ Key Features

- ⚙️ **Native Settings & Preferences Panel:** Configure default streaming engines, manage aspect ratio behaviors, clear watch history bookmarks, and purge webview cache directly from the navigation bar.
- 📐 **Retina Viewport Aspect Ratio Control:** Toggle between standard Letterboxed Contain (16:9) and dynamic Smart Zoom / Fill (16:10) tailored for MacBook Retina screens.
- ⚡ **Multi-Engine Failover Scraper:** Switch between top streaming CDNs on the fly—**VidLink Core** (Multi-Sub / 4K), **EmbedSU** (Fast Buffer), **SuperEmbed** (Adaptive CDN), and **AutoEmbed**.
- 🛡️ **Anti-Ad Duration Filter:** Built-in telemetry firewall ignores bogus pre-roll ad durations (22s, 3m) and locks to real TMDB metadata runtimes for accurate progress tracking.
- ⏭️ **Smart Up Next Prompt:** Displays an automated card with episode artwork and a 15-second countdown during the final 45 seconds of a TV show.
- ✨ **Instant Up Next Preview:** Dedicated preview control in the player header to inspect and toggle the Up Next card on demand.
- 🛑 **"Stay" Credit Mode:** Dismiss auto-advance prompts with one click to finish watching post-credit scenes uninterrupted.
- 📺 **In-Player Episode Drawer & Quick Nav:** Browse seasons and full episode lists with rich artwork without exiting active playback.
- 🖥️ **Integrated Top-Bar Fullscreen:** Fast one-click toggle control embedded directly into the player navigation bar.
- 💬 **Custom Subtitle Loader:** Load external `.srt` or `.vtt` subtitle files directly over active video streams.
- 🔖 **My List & Watchlist:** Bookmark movies and TV shows for instant access from local offline storage.
- 🕒 **Resume & History Tracking:** Automatically saves playback state to pick up right where you left off.
- 🔄 **Over-The-Air (OTA) Updates:** Automatic startup check with strict semantic version checking and one-click package download.
- 🔍 **Genre & Language Discovery:** Filter content across Malayalam, Hindi, Tamil, Telugu, English, Korean, and Japanese.

---

## ⌨️ Media Shortcuts

| Key | Action |
| :--- | :--- |
| <kbd>F</kbd> | Toggle Fullscreen |
| <kbd>T</kbd> | Toggle / Preview Up Next Card |
| <kbd>N</kbd> | Jump to Next Episode |
| <kbd>P</kbd> | Jump to Previous Episode |
| <kbd>Esc</kbd> | Close Episode Drawer / Exit Fullscreen / Close Player |

---

## 📥 Installation Guide (macOS)

1. Open the **[Latest Release](https://github.com/faithpoovathingal/iskoni-releases/releases/latest)** page.
2. Download the latest **`ISKONI-v1.0.5-macOS-arm64.pkg`** installer.
3. **Right-Click (or Control + Click)** the downloaded `.pkg` file and select **Open**.
4. Follow the macOS installer prompts to install ISKONI into your `/Applications` directory.
5. Launch **ISKONI** from Spotlight or Launchpad.

---

## 👨‍💻 Developer & Credits

Designed and engineered with precision by **Faith Poovathingal**.

- **GitHub:** [@faithpoovathingal](https://github.com/faithpoovathingal)
- **Architecture:** Electron, React, TypeScript, Tailwind CSS, TMDB API

---

<div align="center">
  <sub>Disclaimer: ISKONI is built purely as an educational media aggregator and client. All media metadata is provided via the TMDB API and third-party scrapers.</sub>
</div>
EOF

echo "README.md updated successfully."
