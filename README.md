# Browser Games

Two self-contained HTML5 games — no build step or dependencies. Open `index.html` (or either game's `index.html`) in any modern browser.

## Snakes & Ladders — `snakes-and-ladders/`
- 2–4 players, each human or computer
- Animated step-by-step movement, snake slides and ladder climbs
- Optional rules: roll a 6 for an extra turn; exact roll to finish (overshoot bounces back)
- Controls: click **Roll Dice** or press Space/Enter

## Space Invaders — `space-invaders/`
- Classic 5×11 invader formation that speeds up as it thins out
- Destructible shields, mystery UFO, increasing levels, extra life at 1500 points
- High score saved in `localStorage`, retro WebAudio sound effects
- Controls: ←/→ or A/D to move, Space to fire, P to pause, M to mute; on-screen buttons on touch devices

## Run locally
```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
