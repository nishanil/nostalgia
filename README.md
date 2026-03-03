# 🎮 Nostalgia Games

A collection of retro browser games — no installs, no dependencies, just pure HTML fun.

**Play now: [nishanil.github.io/nostalgia](https://nishanil.github.io/nostalgia/)**

## Games

| Game | Description |
|------|-------------|
| 🧱 **Brick Breaker** | Classic breakout action with 10 levels and power-ups |
| 🟩 **Tetris** | The original classic in retro Game Boy style |
| 🔤 **Word Trail** | Find hidden words by tracing paths through letters |
| ⚔️ **Blade of the Lost Prince** | Side-scrolling action — fight guards, dodge traps, escape the dungeon |

## Features

- 🔊 Retro synthesized sound effects (Web Audio API — no audio files)
- 📱 Mobile-friendly with touch controls
- 🎨 Each game has its own visual style
- 💾 High scores saved locally
- 📦 Zero dependencies — every game is a single HTML file

## Tech

Each game is a standalone HTML file using Canvas 2D and vanilla JavaScript. Sound effects are generated in real-time using `OscillatorNode` — no external assets required.

## Running Locally

Just open any `.html` file in a browser, or serve the directory:

```sh
npx serve .
```

---

Built with ❤️ for Ami & Pree from Nish & Copilot
