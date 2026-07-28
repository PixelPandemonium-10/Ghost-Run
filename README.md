# 👻 GHOST RUN

[![Live Demo]( https://pixelpandemonium-10.github.io/Ghost-Run/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

GHOST RUN is a browser-based infinite runner that evolves the genre from pure reaction-time testing into tactical prediction gameplay. Set in a rain-slicked cyberpunk city, the player controls a neon-lit silhouette sprinting across three lanes, reading telegraphed threats, and making split-second decisions that compound over time.

Unlike traditional runners where obstacles appear without warning, GHOST RUN gives the player a predictive window—a flashing telegraph that reveals the required action before the threat materializes. Correct predictions build Focus, which extends future reaction windows and creates positive feedback loops for skilled play.

The game was developed through an iterative design process involving four major revisions, each addressing deeper layers of game design: game feel, meaningful choice, predictive depth, emergent complexity, and production polish.

[Play it now →]( https://pixelpandemonium-10.github.io/Ghost-Run/)


---

## 🎮 How to Play

| Control | Action |
|---------|--------|
| **Space** | Jump |
| **↑ Arrow** | Jump |
| **Tap (Mobile)** | Jump |

- Avoid obstacles to stay alive.
- The longer you survive, the higher your score.
- Game speed gradually increases as you progress.

---

## ✨ Features

### Visual Atmosphere
- **Parallax city background** — Multi-layered scrolling skyline
- **Dynamic rain system** — Rain leans and intensifies based on motion
- **Neon signs** — Glowing urban signage scrolling past
- **Graffiti walls** — Street art at varying speeds
- **Ghost eye pulse** — The ghost's eyes beat with an eerie glow

### Character Mechanics
- **Snappy jump** — High, responsive jump arc with smooth gravity
- **Fast run animation** — Legs cycle quickly for that urgent dash feel
- **Body lean** — Ghost tilts into the run for dynamic motion

### Difficulty Scaling
- Obstacles spawn faster as your score climbs
- Speed ramps up gradually every 40 points
- Maximum speed is capped to keep the game fair

---

## ⚙️ Technical Parameters

| Parameter | Value | Description |
|-----------|-------|-------------|
| Background parallax | 0.25× / 0.7× | Normal city scroll speed |
| Rain lean | up to 8px | Subtle wind effect |
| Rain intensity | 0.25× | Light, atmospheric rain |
| Neon sign speed | 0.7× | Normal signage drift |
| Graffiti speed | 0.9× | Near-normal wall art scroll |
| Jump force | -15.5 | High, snappy leap |
| Gravity | 0.48 | Smooth arc with hang time |
| Leg animation | 0.55× | Fast running cycle |
| Body lean | 0.15 | Aggressive forward tilt |
| Ghost eye pulse | 0.25 | Alive, breathing glow |
| Obstacle speed | 6× / 25px cap | Reasonable dodge difficulty |
| Game speed ramp | +0.18 every 40 pts | Gradual difficulty curve |
| Max speed | 3.5× | Sane upper limit |

---

## 🚀 Getting Started

1. Open `ghostrun_final.html` in any modern web browser.
2. No installation or dependencies required — everything runs client-side.
3. Works on desktop (keyboard) and mobile (touch).

---

## 💻 System Requirements

- Any modern browser with HTML5 Canvas support (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Recommended: 60 FPS capable display for smoothest experience

---

## 📝 Changelog

### Balanced Edition
- Background speed normalized for a calmer experience
- Ghost jump made higher, snappier, and smoother
- Run animation feels more responsive
- Difficulty curve tuned for better pacing
- Visual effects toned down to avoid overwhelming the player

---

*Game refined and balanced based on player feedback for a smooth, responsive, and visually atmospheric endless runner experience.*
