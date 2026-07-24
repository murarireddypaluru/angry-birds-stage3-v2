# ABC33 — Angry Birds (Stage 3: Introducing Constraint)

A browser "Angry Birds" style slingshot game. Drag the bird back in the
slingshot and release to launch it into a tower of boxes and logs to hit the
pigs.

This is a **Stage 3** build from the Angry Birds curriculum — *Introducing
Constraint* — where the bird is held to the slingshot by a matter.js
constraint that releases when you let go, flinging the bird toward the tower.

## Built with

- [p5.js](https://p5js.org/) — canvas rendering, input, and sprites
- [matter.js](https://brm.io/matter-js/) — 2D physics (gravity, collisions, constraints)

## How to run

- **Simplest:** open `index.html` directly in a web browser.
- **Via a static server** (recommended, avoids image-loading quirks):
  ```
  python3 -m http.server 8000
  ```
  then visit <http://localhost:8000>.
- **GitHub Pages:** enable Pages for this repo and open the published URL.

## Controls

- **Mouse drag** — pull the bird back in the slingshot.
- **Release the mouse** — launch the bird toward the tower.
