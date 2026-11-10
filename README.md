# Jensen Lover 🕶️

Interactive video grid sticker experience inspired by [vercel.vercel.vercel.app](https://vercel.vercel.vercel.app/).

## Features
- **Dynamic Mouse Scaling (Y-axis)**: Moving the cursor from top to bottom dynamically scales the video grid from tiny stickers to full size (`clamp(8px, mouseY, 100vmin)`).
- **Position Tracking (X-axis)**: Moving the cursor horizontally shifts the repeating tile pattern smoothly.
- **Audio Experience**: Plays *Wasted (Nightcore)* starting directly at the 20-second drop, looping seamlessly.
- **Hardware-Accelerated Canvas**: 60fps canvas pattern rendering for smooth continuous video decoding.

## Running Locally
Simply serve the directory with any static server:
```bash
python3 -m http.server 8123
```
Then open `http://localhost:8123/` in your browser.
