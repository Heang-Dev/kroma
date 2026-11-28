<h1 align="center">
  <a href="https://heang-dev.github.io/kroma/"><img src="https://raw.githubusercontent.com/Heang-Dev/KROMA.STUDIO/main/docs/assets/readme-icon.png" alt="Kroma Studio" width="72" valign="middle" /></a> Kroma Studio
</h1>

<p align="center">
  <a href="https://github.com/Heang-Dev/kroma/releases/latest"><img src="https://img.shields.io/github/v/release/Heang-Dev/kroma?style=flat&label=release&color=7F22FE" alt="Latest release" /></a>
  <a href="https://github.com/Heang-Dev/kroma/releases"><img src="https://img.shields.io/github/downloads/Heang-Dev/kroma/total?style=flat&label=downloads&color=7F22FE" alt="Total downloads" /></a>
  <a href="https://github.com/Heang-Dev/KROMA.STUDIO/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-7F22FE?style=flat" alt="License: MIT" /></a>
  <a href="https://t.me/kromastudio_community"><img src="https://img.shields.io/badge/Telegram-26A5E4?logo=telegram&logoColor=white" alt="Telegram" /></a>
  <img src="https://img.shields.io/badge/macOS%20%7C%20Windows%20%7C%20Linux-171717?style=flat" alt="macOS, Windows and Linux" />
</p>

<h2 align="center">Turn any video into a Khmer video.</h2>

<p align="center">
  Download a video or a whole series from YouTube, Bilibili, Douyin and 1,000+ sites. Get the subtitles, translate them to Khmer, give every character their own voice, and post to YouTube, Facebook and TikTok. One free, open-source desktop app.
</p>

<h3 align="center">
  <a href="https://github.com/Heang-Dev/kroma/releases/latest"><ins>Download the latest version</ins></a> &nbsp;·&nbsp;
  <a href="https://heang-dev.github.io/kroma/"><ins>Website</ins></a> &nbsp;·&nbsp;
  <a href="https://heang-dev.github.io/kroma/docs/"><ins>Docs</ins></a> &nbsp;·&nbsp;
  <a href="https://github.com/Heang-Dev/KROMA.STUDIO"><ins>Source code →</ins></a>
</h3>

<p align="center">
  <img src="https://raw.githubusercontent.com/Heang-Dev/KROMA.STUDIO/main/docs/assets/readme-editor-dark.jpg" alt="The Kroma Studio editor: a video with Khmer subtitles, the Characters panel, the subtitle list and the timeline" width="960" />
</p>

## Download

| System | File | |
| --- | --- | --- |
| **macOS** (Apple silicon, M1 and later) | `Kroma-Studio-<version>-arm64.dmg` | [Download](https://github.com/Heang-Dev/kroma/releases/latest) |
| **Windows** 10 / 11 (x64) | `Kroma-Studio-Setup-<version>.exe` | [Download](https://github.com/Heang-Dev/kroma/releases/latest) |
| **Linux** (x64) | `.AppImage` (any distro) or `.deb` (Ubuntu, Debian) | [Download](https://github.com/Heang-Dev/kroma/releases/latest) |

Install it once: Kroma updates itself. New versions download in the background and a **Restart to update** card appears in the bottom-right corner. Every version and its notes are on the [changelog](https://heang-dev.github.io/kroma/changelog/), and in [CHANGELOG.md](CHANGELOG.md) ([ខ្មែរ](CHANGELOG.km.md)).

### The installers aren't code-signed yet

- **macOS:** if it says the app is damaged or won't open, run this once in Terminal: `xattr -cr "/Applications/Kroma Studio.app"`
- **Windows:** on "Windows protected your PC", click **More info → Run anyway**.
- **Linux:** `chmod +x Kroma-Studio-*.AppImage`, then run it.

## What it does

<table>
<tr>
<td width="50%"><img src="https://raw.githubusercontent.com/Heang-Dev/KROMA.STUDIO/main/docs/assets/readme-translate-dark.jpg" alt="Translating subtitles to Khmer" width="100%" /></td>
<td width="50%"><img src="https://raw.githubusercontent.com/Heang-Dev/KROMA.STUDIO/main/docs/assets/readme-voices-dark.jpg" alt="The Khmer voice library" width="100%" /></td>
</tr>
<tr>
<td valign="top"><b>Khmer that sounds like Khmer.</b> Gemini (free), Google Translate (free, no key) or Claude, with lines that fit their time on screen, and a series glossary so every name is spelled the same in every episode. Thai, Vietnamese, Lao, English, Indonesian and Malay too.</td>
<td valign="top"><b>A voice for every character.</b> 36 Khmer voices, your own cloned voice, or free instant voices. The original voices are removed; music and effects stay.</td>
</tr>
<tr>
<td width="50%"><img src="https://raw.githubusercontent.com/Heang-Dev/KROMA.STUDIO/main/docs/assets/readme-style-dark.jpg" alt="Styling subtitles" width="100%" /></td>
<td width="50%"><img src="https://raw.githubusercontent.com/Heang-Dev/KROMA.STUDIO/main/docs/assets/readme-post-dark.jpg" alt="Posting to YouTube, Facebook and TikTok" width="100%" /></td>
</tr>
<tr>
<td valign="top"><b>Your style.</b> 33 subtitle styles, Khmer display fonts and animated captions. The burned-in original subtitles are found and blurred automatically. 16:9, 9:16 and 1:1.</td>
<td valign="top"><b>Post in one click.</b> AI-written titles, text and hashtags for YouTube, Facebook and TikTok, the right format for each, and numbered episode covers.</td>
</tr>
</table>

## More in Kroma

- **Batch.** Add many videos at once, from the Download Center or your project files, choose the steps once (subtitles, translate, characters, voice-over, hide the original subtitles, style, export, covers, post text) and press **Process**. Each video goes through every step while you do something else, then waits in **Ready to post** so you check it first.
- **The right format for each platform.** YouTube gets 16:9; TikTok, Facebook and Reels get 9:16. Kroma exports each format it needs and uploads the right file to each platform.
- **Download Center.** Paste a whole series, a playlist or a channel, tick the episodes you want, and each video becomes its own project, numbered in a folder. The queue keeps going while you work and picks up after a restart.
- **Series glossary, my styles and episode covers.** One spelling for every name across a series, your subtitle look saved for every project, and a numbered thumbnail for every episode. [Release notes →](https://heang-dev.github.io/kroma/docs/0.2/release-notes/)
- **Story studio.** Write a story one line per speaker, give every character a voice, and Kroma reads it aloud. Save the audio with its subtitles.
- **A voice engine built in.** One button installs it on your computer, or run it on a free Google Colab GPU. [Voice engine →](https://heang-dev.github.io/kroma/docs/0.2/voice-engine/)
- **Notifications.** A bell in the title bar keeps everything that finished or failed, with **Retry** or **Open**, and your computer tells you when Kroma is in the background.

## About this repository

This repository holds the **installers** (in [Releases](https://github.com/Heang-Dev/kroma/releases)) and the **built website** (the `gh-pages` branch, served at [heang-dev.github.io/kroma](https://heang-dev.github.io/kroma/)). The app's source code, the website's source and the docs are in [Heang-Dev/KROMA.STUDIO](https://github.com/Heang-Dev/KROMA.STUDIO). Report problems [there](https://github.com/Heang-Dev/KROMA.STUDIO/issues), or ask in the [Telegram group](https://t.me/kromastudio_community).

## Use it responsibly

Only download, translate and repost videos you have the right to use, and only clone voices that are your own or that you have the speaker's permission for.

---

<p align="center"><sub>MIT License © 2026 Heang-Dev · Made for Khmer creators</sub></p>
