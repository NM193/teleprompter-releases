# Teleprompter for Mac

A teleprompter that sits right under your MacBook's notch, next to the camera, so you keep eye contact while you read. It can follow your voice, and it stays hidden when you share your screen.

Requires a Mac with Apple Silicon (M1 or newer) and macOS 14 or later.

## Install

1. Open [the latest release](../../releases/latest) and download `Teleprompter-<version>.zip`.
2. Double-click the zip, then drag **Teleprompter** into your **Applications** folder.
3. Open Teleprompter. macOS will say it can't verify the developer. Click **Done**.
4. Go to **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to Teleprompter. Confirm with **Open**.

You only need to do step 4 once. Teleprompter lives in the menu bar (top right), not in the Dock.

If macOS says the app is "damaged", run this once in Terminal and open it again:

```bash
xattr -dr com.apple.quarantine /Applications/Teleprompter.app
```

## Updates

Teleprompter checks for updates once a day and asks before installing. You can also check at any time from the menu bar icon → **Check for Updates…**

## Quick start

- **Scripts…** (⌘E): write or paste your script. Use `---` on its own line to split it into slides.
- **⌃⌥P** shows or hides the prompter, **⌃⌥→** plays, **⌃⌥←** pauses, and **⌃⌥↑ / ⌃⌥↓** change the speed.
- **⌃⌥V** makes the text follow your voice. For English you can choose word by word; any language works in "Any voice" mode.
- Settings has ghost mode (hidden from screen sharing), floating and follow-cursor modes, rehearsal, memorize mode, and more.
