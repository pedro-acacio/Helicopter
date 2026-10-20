# Helicopter

Physics game built with [p5.js](https://p5js.org/) + [matter.js](https://brm.io/matter-js/): fly a helicopter carrying a package and drop it at the right moment to hit a target box on the ground.

## How to play

Open `index.html` in your browser — no installation or server required.

- Left arrow / right arrow: moves the helicopter (and the package, still attached to it) horizontally
- Down arrow: drops the package, which then falls under matter.js physics (gravity and collision)
- The goal is to drop the package at the right time so it lands inside the red box drawn on the ground

## Structure

- `sketch.js` — flight physics (matter.js) and game logic
- `index.html` — loads p5.js, matter.js, p5.play and the sketch
- `helicopter.png`, `package.png` — sprites

## Running locally

No external dependencies: the libraries are already included in the repository. Just open `index.html` directly in the browser or serve the folder with any static server (e.g. `npx serve .`).
