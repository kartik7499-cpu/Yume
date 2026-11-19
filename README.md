
# 🌸 Yume

**Your Ultimate Anime Discovery & Streaming Experience.**

Yume is a Windows-based anime discovery and playback application featuring a clean, keyboard-driven terminal interface.

Explore a massive anime catalogue, discover currently airing shows, check episode schedules, and jump straight into playback through the Yume Player.

---

## ✨ Features

- 🔎 **Anime Search** — Discover anime from a catalogue of 26,000+ titles.
- 📚 **Anime Details** — Explore anime information, ratings, genres, and more.
- 📅 **Airing Schedule** — Browse upcoming episodes and airing times.
- 🌍 **Timezone Support** — View schedules in your preferred timezone.
- 🎬 **Episode Selection** — Browse and filter available episodes.
- 🎧 **Multiple Tracks** — Switch between SUB, HSUB, and DUB.
- ⏯️ **Continue Watching** — Save playback progress and resume watching.
- 🌐 **Yume Player** — Open episodes directly in your default browser.

---

## 🚀 Installation

1. Visit the [Yume Releases](https://github.com/kartik7499-cpu/Yume/releases) page.
2. Download the latest Windows executable from the release assets.
3. Save it somewhere accessible on your computer.
4. Run the downloaded executable.

Use only builds published through the official Yume GitHub repository.

---

## 🔑 License Activation

Yume requires a valid activation key to run.

### How to get an activation key

You can request an activation key using either method:

- **Email:** [yume@tomnix.qzz.io](mailto:yume@tomnix.qzz.io)
- **Discord:** Send a direct message to **tomn_yakuza**.

Please mention that you are requesting a Yume activation key.

### Activating Yume

1. Launch Yume for the first time.
2. The application will ask you for an activation key.
3. Enter the key you received.
4. Yume will contact the licensing server and verify your key.
5. Once activated, your license token is securely saved locally.
6. On subsequent launches, Yume automatically verifies your saved license.

**Important:** Activation keys may be restricted to a single device. Keep your key private and do not share your license token.

---

## 🎮 How to Use Yume

### 🔎 Search for Anime

1. Start typing an anime title on the home screen.
2. Use **Up** and **Down** to navigate suggestions.
3. Press **Enter** to open the selected anime.
4. If more results are available, select the See All option to browse the complete matching list.

### 📚 Anime Details

Inside the anime details screen:

- Use **Up / Down** to scroll through information.
- Press **W** to open the episode selector.
- Press **O** to open the poster URL in your browser.
- Press **Esc** or **B** to return.

### 🎬 Episode Selection & Playback

1. Open an anime's episode selector by pressing **W**.
2. Navigate episodes using **Up / Down**.
3. Select an episode and press **Enter**.
4. Yume opens the player in your default browser.

Available tracks:

| Track | Description |
|---|---|
| SUB | Subtitled version |
| HSUB | Hard-subbed version |
| DUB | Dubbed version |

Use **Left / Right** to switch tracks, or press **T** to cycle forward.

You can also press **/** to search or filter episodes.

### ⏯️ Continue Watching

Yume saves playback progress locally.

When you return to an anime's episode selector, Yume can show your saved progress so you can continue from where you stopped.

### 📅 Airing Schedule

Press **Ctrl + D** from the home screen to open the airing schedule.

Available controls:

- **Up / Down** — Navigate schedule entries.
- **Enter** — Open anime details.
- **/** or **S** — Search/filter the schedule.
- **T** — Change timezone.
- **R** — Refresh the schedule.
- **Esc / B** — Return to the home screen.

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|---|---|
| Type on Home | Search anime |
| Up / Down | Navigate lists |
| Enter | Open selection / Play episode |
| W | Open episode selector |
| O | Open poster URL |
| Left / Right | Change playback track |
| T | Cycle track / Select timezone |
| / | Search or filter |
| S | Start schedule search |
| Ctrl + D | Open airing schedule |
| R | Refresh schedule |
| Esc / B | Go back |
| F1 | Open keyboard help |
| Ctrl + Q | Quit Yume |
| Ctrl + C | Quit Yume |

---

## 💾 Local Data & Playback

Yume stores application data in:

```text
%LOCALAPPDATA%\Yume
```

This directory contains:

- `device.id` — Local device identifier.
- `license.dat` — Encrypted license token.
- `watch-history.json` — Saved playback progress.

License data is protected using Windows DPAPI.

### Local Player Service

Yume starts a local player service at:

```text
http://127.0.0.1:7499
```

Keep Yume running while using the browser player. The local service allows the browser player to communicate playback progress back to the application.

Only one Yume application instance can run at a time.

---

## ⚠️ Requirements

- Windows
- Active internet connection
- Valid Yume activation key
- Configured default web browser

---

## 🛠️ Troubleshooting

### Anime catalogue or schedule is not loading

- Check your internet connection.
- Wait for the loading operation to finish.
- Try again later if the API is temporarily unavailable.

### License activation failed

- Check that your activation key was entered correctly.
- Make sure the key is valid and has not already been activated on another device.
- Contact us if the problem continues.

### Player does not open

- Make sure Windows has a default browser configured.
- Check whether your browser blocked the page.
- Keep Yume running while using the player.

### Playback progress is not saving

- Keep the Yume application running.
- Make sure local connections to `127.0.0.1:7499` are not blocked by security software.

---

## 📬 Contact & Support

Need an activation key, have a question, or found a bug?

**Email:** [yume@tomnix.qzz.io](mailto:yume@tomnix.qzz.io)

**Discord:** DM **tomn_yakuza**

For bug reports and feature requests, visit:

[GitHub Issues](https://github.com/kartik7499-cpu/Yume/issues)

---

<p align="center">
  Made with 🌸 by the Yume project
</p>
