# DisplayDirect

A lightweight Windows tray app for switching monitor settings per game: resolution, refresh rate,
brightness, contrast, gamma and NVIDIA digital vibrance, saved as profiles.

This repository only hosts the Windows installer. The source code is private.

## Download

**[Download the latest installer](https://github.com/miguelc2001/displaydirect-releases/releases/latest/download/DisplayDirect-setup.exe)** (Windows 10/11, x64)

Or see all versions on the [Releases page](https://github.com/miguelc2001/displaydirect-releases/releases).

## Installing

The installer isn't code-signed yet, so Windows SmartScreen may show "Windows protected your PC".
Click **More info**, then **Run anyway**.

It installs for your user only (no admin needed) and lets you choose a desktop shortcut and whether
DisplayDirect starts with Windows. The app checks for updates on launch (you can turn this off in Settings)
and only installs updates that pass a signature check.

## Features

- Profiles with per-monitor settings: resolution + refresh rate, brightness, contrast, gamma, digital vibrance
- Apply a profile from the app, the tray menu or a global hotkey
- Link games to a profile: it applies when the game starts and your previous settings come back when it closes
- Live preview while adjusting colors

## Notes

- Digital vibrance needs an NVIDIA GPU. Everything else works on any GPU.
- Brightness, contrast and gamma don't apply while Windows HDR is on.
- Windows limits extreme gamma values by default; Settings has a button to unlock the full range.
