# Lyrics Visualizer

View Apple Music–inspired word- and line-synchronized LRC/ELRC lyrics in your browser with MP3 playback, queue management, ID3 metadata parsing, and dynamic artwork-reactive ambient backgrounds.

## Live Demo

Open the app here: **[https://mytf49.github.io/Lyrics-Visualizer/](https://mytf49.github.io/Lyrics-Visualizer/)**

## Features

- **Apple Music–Inspired Lyrics Stage:** Smooth auto-scrolling lyrics with active-line focus, word-by-word glow progression, optional `||` secondary/translation sub-lines, click-to-seek lines, and a responsive mobile layout with expandable album artwork.
- **Dynamic Ambient Mesh Background:** Extracts colors directly from embedded MP3 cover art (`APIC`) to animate a multi-orb blurred gradient backdrop, falling back cleanly when no artwork is present.
- **LRC & Enhanced LRC (ELRC) Support:** Load `.lrc`, `.elrc`, or `.txt` files via drag-and-drop or paste lyrics directly, auto-pair lyrics with matching MP3 filenames, assign lyrics per track, and fine-tune sync timing with a `±2.00s` offset slider.
- **MP3 Queue, ID3 Parser & Playback Controls:** Drag-and-drop multiple `.mp3` files to build and reorder a playback queue, read ID3v1/ID3v2 tags (`TIT2`, `TPE1`, `TALB`, year, `COMM`, `USLT`, and cover art), toggle shuffle and repeat modes (`Off`, `All`, `One`), adjust playback speed (`0.75x–1.50x`), and set A–B section loops.
- **Customization & Keyboard Shortcuts:** Adjust lyric font scale and word glow intensity, toggle auto-scroll lock, auto-hide controls and cursor in fullscreen (`F`), and control playback with `Space`, `0–9`, `Left/Right`, `Up/Down`, and `M`.

## How to Run Locally

1. Download or clone this repository.
2. Open `index.html` in any web browser.

## Privacy & Data

Your MP3 files, cover art, lyrics, and playback settings are processed locally in your browser on your device — no audio files or lyrics are uploaded to any server. Lyrics text and visualizer settings are saved locally in `localStorage` across sessions.
