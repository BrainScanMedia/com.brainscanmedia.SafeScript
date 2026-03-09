# SafeScript

A clean, fast code snippet manager for Linux built with Qt6.

![SafeScript Dark Mode](https://raw.githubusercontent.com/BrainScanMedia/SafeScript/main/screenshot-dark.png)
![SafeScript Light Mode](https://raw.githubusercontent.com/BrainScanMedia/SafeScript/main/screenshot-light.png)

## Features
- Organize snippets into folders
- Syntax-aware code editor with line numbers
- Notes field for each snippet
- Dark and light mode
- Search snippets instantly
- Data stored locally in SQLite

## Installation

### Flatpak (recommended)
```bash
flatpak install flathub com.brainscanmedia.SafeScript
```

### Build from source
Requires Qt6 with Widgets and SQL modules.
```bash
git clone https://github.com/BrainScanMedia/SafeScript.git
cd SafeScript
qmake6 SafeScript.pro
make
./SafeScript
```

## Data Storage
All snippets and folders are saved locally on your machine at:
```
~/Documents/SafeScript/storage.sqlite3
```
No data is sent to the internet. Everything stays on your device.

## Source Code
Full source code is available at:
[https://github.com/BrainScanMedia/SafeScript](https://github.com/BrainScanMedia/SafeScript)

## Flatpak Manifest
This repository contains the Flatpak manifest used to build and distribute SafeScript on Flathub. The manifest pulls directly from the source code repository above and compiles inside the KDE 6.10 SDK.

## Developer
BrainScanMedia.com, Inc.
[https://brainscanmedia.com](https://brainscanmedia.com)

## License
MIT — © BrainScanMedia.com, Inc.
