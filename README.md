# TaniX Chat for Mac: download

**TaniX Chat** is Connect, the TaniX chat, in a window of its own: your chats, groups and calls with other
students, without opening the whole TaniX app. You stay signed in.

## ⬇️ Download (click one)

| Your Mac | Click to download |
|---|---|
| **Apple chip** (M1, M2, M3, M4; most Macs from 2021 on) | **[Download for Apple chip Mac (.dmg, 129 MB)](https://github.com/Samsontanimawo/TaniX-Chat-macOS/releases/latest/download/TaniX-Chat-1.0.2-mac-arm64.dmg)** |
| **Intel chip** (older Macs) | **[Download for Intel Mac (.dmg, 136 MB)](https://github.com/Samsontanimawo/TaniX-Chat-macOS/releases/latest/download/TaniX-Chat-1.0.2-mac-x64.dmg)** |

Not sure which Mac you have? Apple menu  → **About This Mac**: "Chip Apple M…" = Apple chip, "Processor Intel" = Intel.
Then follow **Install** and **The first time you open it** below.

## Install

1. Open the downloaded `.dmg` file (double-click it).
2. Drag **TaniX Chat** onto the **Applications** folder.
3. Open **Applications** and double-click **TaniX Chat**.

## The first time you open it

The app is not registered with Apple yet, so macOS asks you to confirm once:

1. macOS says it can't check the app. Click **Done** (or **OK**).
2. Open the Apple menu  → **System Settings** → **Privacy & Security**.
3. Scroll down to the message about **TaniX Chat** and click **Open Anyway**, then **Open Anyway** again
   (type your Mac password if asked).

From then on it opens normally from Applications, Launchpad or the Dock.

### "TaniX Chat is damaged and can't be opened"

This means macOS blocked the download. It is not really damaged. Fix it once:

1. Open **Terminal** (Applications → Utilities → Terminal).
2. Paste this line and press Return:

   ```
   xattr -dr com.apple.quarantine "/Applications/TaniX Chat.app"
   ```
3. Open TaniX Chat again.

## Updates

The chat inside the app is the live website, so new chat features arrive by themselves. When a new version of the
app itself comes out, it tells you and offers the download; drag the new one into Applications, replacing the old.

## Help

Ask in the Telegram community group: [t.me/DrDanielFreeAIChat](https://t.me/DrDanielFreeAIChat), or email
tanimawoaiacademy@gmail.com. Windows version: [TaniX-Chat-Windows](https://github.com/Samsontanimawo/TaniX-Chat-Windows).

## Change log

Newest first. Add one line per change.

- **2026-11-04** 1.0.2: notifications you can reply to. A new direct message or @mention shows with a Reply box, and clicking it opens the chat. Installed copies are offered the download. Download links point to 1.0.2.
- **2026-11-04** 1.0.1: the new TaniX Chat logo (the robot in a graduation cap with "CHAT") is the app icon. Download links point to 1.0.1.
- **2026-11-04** First public Mac download: TaniX Chat 1.0.0 for Apple chip and Intel. Built by the private
  TaniX-Chat-desktop repo; only the installers are published here.
