# 👻 Ghost Hunter Game (HTML5 + SVG + RxJS)

A fun and interactive browser game built using **Snap.svg** and **RxJS**. In this game, you control a player who zaps ghosts using a lightning stream. Inspired by arcade-style ghost-catching mechanics and enhanced with dynamic animations and SVG graphics.

## 🎮 Gameplay

- Move the player left and right using **Arrow Keys** or **A/D**.
- Click or tap and hold anywhere on the screen to launch an **electric stream**.
- Aim the stream to hit and catch floating ghosts.
- Ghosts get zapped and follow your stream while being caught.
- Ghosts react with animated "shock" eyes and lightning effects.

## ⚙️ Features

- 🔌 SVG-based animations via [Snap.svg](http://snapsvg.io/)
- ⚡️ Smooth lightning effects and particle movement
- 🎯 Reactive input with [RxJS](https://rxjs.dev/)
- 📱 Mouse and touch support
- 🎨 Randomized ghost shapes, sizes, and movement patterns
- 🎮 Real-time collision detection and ghost grabbing

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **Snap.svg** – for SVG manipulation
- **RxJS** – for handling mouse, touch, and keyboard events reactively

## 📁 Project Structure

All game logic, visuals, and interactions are contained in a single HTML file:

- `index.html`: Contains game logic, styles, and embedded scripts
- `<svg>`: Used to render all game entities and animations

## 🧠 Concepts Demonstrated

- Procedural shape generation using SVG paths
- Stream-based user input via RxJS
- Object-oriented design using ES6 classes (`Game`, `Ghost`, `Player`, `Stream`)
- Real-time animation using `requestAnimationFrame`
- Collision detection via Snap.svg’s `isPointInside()`
- Tweening and path-based animation

## 🚀 Getting Started

To run the game:

1. Download or clone the repo.
2. Open `index.html` in any modern web browser.
3. Start hunting ghosts!

## 🔧 Possible Enhancements

- Score system & game timer
- Multiple levels or increasing difficulty
- Sound effects and background music
- Ghost types with different behaviors
- Leaderboard with localStorage

## 📄 License

MIT License – feel free to use, modify, and distribute.
