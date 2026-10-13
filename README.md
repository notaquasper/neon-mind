# 🧠 NEON MIND

A fast, neon-soaked memory game. Watch the sequence, repeat it, survive.

![Made with](https://img.shields.io/badge/made%20with-HTML%20%2B%20CSS%20%2B%20JS-00e5ff)
![No dependencies](https://img.shields.io/badge/dependencies-0-7cff3d)
![License](https://img.shields.io/badge/license-MIT-ff2d95)

## 🎮 Play

👉 **https://YOUR-USERNAME.github.io/neon-mind/**

## ✨ Features

- 🎨 Neon glassmorphism UI with animated ambient background
- 🔊 Procedural sound via Web Audio API — zero audio files
- 💥 Particle bursts + screen shake + haptic feedback on mobile
- ❤️ Lives system — mistakes replay the sequence instead of ending instantly
- 🎚️ 4 difficulties: Easy / Normal / Hard / Insane
- ⚡ Speed scales up as your level climbs
- 🏆 Per-difficulty high scores saved to `localStorage`
- ⌨️ Full keyboard support (`1` `2` `3` `4`, `Enter`, `Esc`, `M` to mute)
- 📱 Fully responsive, mobile-first, no scroll
- 🚫 Zero dependencies, one file, works offline

## 🕹️ How to Play

1. Pick a difficulty and hit **START**
2. Watch the pads light up in a sequence
3. Repeat the sequence by clicking pads (or pressing `1`–`4`)
4. Each round adds one more step
5. Make a mistake → lose a life, the sequence replays
6. Run out of lives → game over

## ⌨️ Controls

| Key | Action |
|-----|--------|
| `1` `2` `3` `4` | Hit pad top-left, top-right, bottom-left, bottom-right |
| `Enter` / `Space` | Start / play again |
| `Esc` | Back to menu |
| `M` | Mute / unmute |

## 🚀 Run Locally

Just open `index.html` in a browser. That's it.

Or serve it:

```bash
python3 -m http.server 8000
# → http://localhost:8000