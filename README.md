# MusicLyrics

A modern overlay application that displays synchronized lyrics for songs playing on YouTube Music.

---

## Features
- Real-time lyrics overlay for YouTube Music
- Minimal, distraction-free design
- Works best with English songs
- Easy setup: just run and play

## Installation
1. **Download** the latest release from [Releases](https://github.com/Peaxmoon/MusicLyrics/releases).
2. **Run** the executable to launch the overlay window.
3. **Install** the [MusicLyrics Chrome Extension](https://chromewebstore.google.com/detail/legffijegmnbcphbcjkgmooadpjiaikg) in your Chromium-based browser.
4. Play your favorite song on YouTube Music—lyrics will appear automatically!

> **Tip:** If you had YouTube Music open before installing the extension, refresh the tab after installation.

## Requirements
- Python 3.8+
- kivy
- websockets
- pyautogui
- unidecode

## How to Run
```sh
# 1. (Optional) Create a virtual environment
python -m venv env
# Activate the environment (Windows)
env\Scripts\activate

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the application
python main.py
```

## Inspiration
This project is inspired by and builds upon the excellent work of [Music-LAW-Lyrics-AnyWhere by iamdevdiv](https://github.com/iamdevdiv/Music-LAW-Lyrics-AnyWhere). Special thanks to the original author for the concept and foundation.

## Contributing
Pull requests and suggestions are welcome! Feel free to fork the repository and submit your improvements.

## Credits
- App and extension logo: Royyan Wijaya ([Flaticon](https://www.flaticon.com/free-icon/list_9376376))
- Drag button: SeyfDesigner ([Flaticon](https://www.flaticon.com/free-icon/drag_8379640))
- Exit button: hqrloveq ([Flaticon](https://www.flaticon.com/free-icon/cross_14035689))

---

© 2025 Peaxmoon. All rights reserved.
