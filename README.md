# EdgePoint Leadership Balloon Game

Interactive single-page experience that challenges players to identify the six core traits of world business leaders by dragging virtual “balloons” into an anchor zone.

## Features
- Responsive full-screen layout with floating draggable balloons.
- Keyword whitelist limits which balloons can anchor; only six correct traits.
- Balloons animate back if incorrect, float when idle, and display strings/tails.
- Completion overlay with restart and a detailed trait carousel modal (keyboard, click, and swipe friendly).
- Easy customization in `index.html`:
  - Update `balloonConfig` for labels/colors.
  - Adjust `allowedKeywords` and `leadershipTraits`.
  - Change `maxAnchored` for anchor limit.

## Running Locally
Open `index.html` directly in a browser or host via any static server (e.g. `npx serve`, `python3 -m http.server`). No build step required.
