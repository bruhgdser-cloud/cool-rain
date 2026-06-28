
# Cool-Rain 🌧️

Very cool and fun ASCII rain animation for Arch / Arch-based Linux distributions.

## Features
- Dynamic terminal resizing support.
- Low resource consumption.
- Authentic digital rain drops (`.`, `│`, `║`).
- Clean exit without breaking terminal cursor settings.

## Installation for Arch Linux

Choose **one** of the two convenient methods below to install the package on your system.

### Method 1: Instant Installation (Recommended)
Install using the precompiled binary package without needing to build from source:

```bash
git clone https://github.com/bruhgdser-cloud/cool-rain.git
cd cool-rain
sudo pacman -U cool-rain-1-1.0.0-1-any.pkg.tar.zst
```

### Method 2: Build from Source (Using makepkg)
If you prefer to package it yourself using the Arch Linux build system:

```bash
git clone https://github.com/bruhgdser-cloud/cool-rain.git
cd cool-rain
makepkg -si
```

## How to Run

Once installed, simply open any terminal emulator and type:

```bash
cool-rain
```

To stop the animation and restore your terminal cursor, press `Ctrl + C`.

## Dependencies
- `bash`
- `ncurses` (for terminal manipulation tools like `tput`)

