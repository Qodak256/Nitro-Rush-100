# Nitro Rush 100 - playable prototype

A mobile-first, browser-playable 3D endless car runner built with Three.js.

## Run locally

Because the game uses ES modules and a service worker, serve this folder over HTTP rather than opening `index.html` directly.

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish to GitHub Pages

1. Create a GitHub repository and upload the contents of this folder (not just the ZIP).
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. Open the published HTTPS URL on your phone. The first load needs an internet connection for the Three.js CDN; the shell is cached by the service worker for later visits.

## Controls
- Swipe left/right or use the on-screen arrows to change lanes.
- Swipe up or tap the jump control to jump.
- Swipe down or tap slide to duck.
- Use nitro to boost score and speed.
- Keyboard: arrows or A/D, Space to jump, S/Down to slide, Shift for nitro, Esc to pause.

## Prototype scope
Includes third-person 3D driving, scrolling road, roadside scenery, traffic, barriers, cones, ramps, coins, XP, shield pickups, near-miss bonuses, nitro, score, local progress, four-car garage foundation, and level progression. The first pass uses procedural low-poly car models and scenery to keep the prototype lightweight. Production-grade art, audio, richer collision tuning, 100 individually authored missions, and device testing are follow-up polish.
