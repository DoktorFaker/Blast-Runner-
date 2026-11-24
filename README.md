# Neon Blast Arena

An explosive arena survival game with a roguelite twist, built as a single HTML5 page (no engine, no build step).

Creatures warp in through glowing portals, wave after wave. Drop bombs, slide them into crowds, fire the bazooka, lob mortars and throw grenades. Quick kills chain into a combo multiplier, and crystals charge NOVA, an arena-wide shockwave. After every wave, pick 1 of 3 upgrade cards.

## Play it
Open `index.html` in a browser, or serve the folder with any static web server:

```
python3 -m http.server 8000
```

then visit http://localhost:8000. Desktop, mobile (touch D-pad) and controllers are supported.

## What's inside
| Path | Contents |
|---|---|
| `index.html` | The whole game: code, graphics (drawn in code) and built-in sound effects |
| `audio/` | Menu song, 13 gameplay songs and 4 recorded sound effects |
| `fonts/` | Press Start 2P and Chakra Petch (SIL Open Font License, licence files included) |
| `CRAZYGAMES_UPLOAD.md` | Store text and upload notes for CrazyGames |

## Controls
- Move: Arrow keys / WASD · Bomb: Space · Mortar: C · Bazooka: V · Grenade: G
- NOVA: R · Special weapon: F · Switch weapon: Q · Dance: E · Pause: P
- Pick an upgrade card: 1 / 2 / 3

## CrazyGames
This build includes the CrazyGames HTML5 SDK v3 (ads, gameplay events, cloud saves). It also runs normally anywhere else: without the SDK the game simply plays without ads.
To package it for CrazyGames, zip `index.html`, `audio/` and `fonts/` so `index.html` sits at the top of the zip.
