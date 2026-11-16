<div align="center">
  <img src="assets/logo.png" alt="Pawse" width="140" />
  <h1>Pawse</h1>
  <p><strong>A cozy Pomodoro timer with pixel-art cat companions.</strong><br/>Focus with Tux, Ginger, or Void. Free for Windows, macOS, and Linux.</p>
  <p>
    <a href="https://github.com/educ-jkescritor/Pawse-Releases/releases/latest"><strong>Download the latest version</strong></a> •
    <a href="https://trypawse.vercel.app">Website</a>
  </p>
</div>

---

## What is Pawse?

Pawse is a desktop Pomodoro timer: work in focused sessions, take short breaks, and earn a long break after four sessions. A pixel-art cat keeps you company, reacts to how your sessions go, and can be petted during breaks.

- **Three companions, three rhythms:** Tux (25 / 5 / 20 min), Ginger (15 / 3 / 12 min), and Void (50 / 10 / 40 min): work / short break / long break.
- **Never lose your progress:** if the app or your computer shuts down unexpectedly, your focus time is kept and you can pick up where you left off.
- **Strict Mode:** optionally lock pausing and skipping once a session starts.
- **Stats and streaks:** daily focus time, weekly activity, streaks, and personal bests.
- **Widgets:** a small floating timer or a cat-only desk companion that stays on top.
- **Auto-start:** optionally start breaks and focus sessions automatically.
- **Private by design:** works offline, no account, your data stays on your computer.

---

## Download

Get the files from the **[latest release](https://github.com/educ-jkescritor/Pawse-Releases/releases/latest)** (under **Assets**). Pick the one for your computer:

| Your computer | Download | Notes |
| :--- | :--- | :--- |
| **Windows 10 / 11** (64-bit) | `Pawse-Setup-<version>.exe` | Installer. Updates itself from inside the app |
| **Mac with Apple Silicon** (M1, M2, M3…) | `Pawse-<version>-arm64.dmg` | *Preview* (see below) |
| **Mac with an Intel processor** | `Pawse-<version>.dmg` (no `arm64` in the name) | *Preview* |
| **Linux, any distribution** (64-bit) | `Pawse-<version>.AppImage` | *Preview*. Runs without installing; updates itself from inside the app |
| **Linux: Ubuntu, Debian, Mint** (64-bit) | `pawse_<version>_amd64.deb` | *Preview*. Installs like a normal app |

Not sure which Mac you have? Apple menu  → **About This Mac**: "Chip: Apple M…" means Apple Silicon; "Processor: Intel…" means Intel.

The other files in each release (`latest*.yml`, `.blockmap`, `.zip`) are used by the in-app updater; you don't need to download them.

> **Preview builds:** Windows is the tested platform for this release. The macOS and Linux builds work the same way but have not yet been tested on real machines; please report anything that looks wrong.

---

## Install

### Windows
1. Run `Pawse-Setup-<version>.exe`.
2. Windows may show **"Windows protected your PC"**. This appears because the installer isn't code-signed yet; it is not a virus warning. Click **More info → Run anyway**.

### macOS (13 Ventura or newer)
1. Open the `.dmg` and drag **Pawse** into **Applications**.
2. The first time you open it, macOS may say **"Pawse can't be opened"** or **"is damaged"**. This is because the app isn't signed with an Apple Developer ID yet. Go to **System Settings → Privacy & Security**, scroll down, and click **Open Anyway**.
3. Closing the window keeps Pawse in the Dock; quit with **Cmd+Q**.

### Linux
- **AppImage:** make it executable and run it: `chmod +x Pawse-<version>.AppImage && ./Pawse-<version>.AppImage`. On Ubuntu 22.04 and newer you may need `libfuse2` (`sudo apt install libfuse2`, or `libfuse2t64` on 24.04). If it fails with a sandbox error on Ubuntu 24.04+, use the `.deb` instead.
- **.deb:** `sudo apt install ./pawse_<version>_amd64.deb`, then open **Pawse** from your app menu.
- On Wayland desktops, "always on top" and the floating widgets may not stay above other windows.

---

## Updates

Open **Settings → Check for Updates**:
- **Windows and Linux AppImage:** the update downloads inside the app; click **Restart & Update**.
- **macOS and Linux `.deb`:** a **Download** button takes you to the newest release; install it over the old version. Your stats are kept.

---

## Your data and privacy

- Pawse needs **no account** and works **offline**.
- Your sessions and stats are stored **only on your computer**, in Pawse's app-data folder (`%APPDATA%\pawse` on Windows, `~/Library/Application Support/pawse` on macOS, `~/.config/pawse` on Linux).
- Pawse only goes online when **you** ask it to: when you click **Check for Updates** (it reads this GitHub page), or open a link. There is no tracking or analytics.
- Uninstalling the app does not delete that folder; delete it yourself if you want your stats gone.

---

## Help and feedback

- Found a bug or have an idea? [Open an issue](https://github.com/educ-jkescritor/Pawse-Releases/issues) and include your operating system and Pawse version (**Settings → About**).
- Email: pawseapp.team@gmail.com
- Website: https://trypawse.vercel.app

---

## License

© 2026 Pawse. All rights reserved. Pawse is free to download and use; its code, characters, and artwork may not be copied, modified, or redistributed without permission. See **[LICENSE](LICENSE)**.

Pawse includes fonts, sounds, and open-source software made by others, used under their own licenses: see **[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)**.
