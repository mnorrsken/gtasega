# 🚗 GTA MEGADRIVE 🌴

A tiny paint-style arcade driving game. Steer left/right, dodge pedestrians,
and lure the chasing police into rocks and palm trees.

The whole game is a single self-contained file: [`index.html`](index.html).
No build step, no dependencies.

## How to play

- **Steer:** `◀` / `▶` arrow keys, `A` / `D`, or the on-screen buttons.
- Hitting people doesn't kill you — it raises your **WANTED** level, summons
  the police, and makes every cop faster.
- Cops chase from behind. Shake them by **luring them into rocks 🪨 and
  palm trees 🌴** (or outlast them until they give up).
- Crashing into an obstacle yourself ends the run.
- **Mute:** `M` key or the 🔊 button. Start/restart with `Space` or a tap.

## Ways to run it

### 1. Click the file directly
Download/clone the repo and double-click `index.html` — it opens in your
browser and runs entirely offline (`file://`).

### 2. GitHub Pages (hosted link)
This repo deploys to GitHub Pages automatically via
[`.github/workflows/pages.yml`](.github/workflows/pages.yml).

**One-time setup** (repo owner): go to
**Settings → Pages → Build and deployment → Source** and select
**GitHub Actions**. After that, every push runs the workflow and publishes
the game.

The live URL will be:

```
https://mnorrsken.github.io/gtasega/
```
