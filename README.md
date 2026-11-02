# Tumble Forge

A brutal five-level platformer for iPhone (played in landscape). You are **Ember**, a spark loose in a foundry, and you are cooling down. Light braziers and grab coal to keep your heat up, then reach the furnace at the end.

**Play:** https://drfillmore.github.io/Tumble-Forge/

## Put it on your iPhone like an app

1. Open the link above in **Safari** on your iPhone.
2. Tap the **Share** button, then **Add to Home Screen**, then **Add**.
3. Launch Tumble Forge from the new icon. It opens full screen, with no Safari bars.
4. Turn the phone sideways.

If you hear no music, check the ring/silent switch: iOS mutes web audio while the phone is on silent.

## Controls

- **Move:** put your left thumb anywhere on the left half of the screen and slide it left or right.
- **Jump:** the JUMP button. Hold it longer to jump higher.
- **Keyboard:** ← → to move, Space to jump, Esc to pause, R to restart.

## Worlds and levels

| World | Levels | Tuned for |
|-------|--------|-----------|
| 1 · Slag Run | 1-1 Cinder Path, 1-2 Slag Bridges, 1-3 The Chimney, 1-4 Cog Run, 1-5 Slag Run (finale) | Top 5% of players |
| 2 · Bellows | 2-1 Steam Vents, 2-2 Vent Ceiling, 2-3 Rail Cogs, 2-4 Saw Chimney, 2-5 First Beat, 2-6 High Ledges, 2-7 Bellows (finale) | Top 4% of players |
| 3 · Trip Hammer | 3-1 Trip Hammer | Top 3% |
| 4 · Quench | 4-1 Quench | Top 2% |
| 5 · Crucible | 5-1 Crucible | Top 1% |

New hazards by world (every one warns before it can hurt you, and behaves the same on every run):

| World | Hazards |
|-------|---------|
| 1 | Beat jets (flame columns in the gaps on the hammer beat), trap jets (fire when you come close) |
| 2 | Side jets, the ladle (pours slag on a rhythm), hanging anvils (drop, rest, get hauled back up) |
| 3 | Fire-biters (chomping heads that leap from the lava), the slag balloon (drops cinders from its basket) |
| 1 onward | Flame balls that shoot up out of gaps and fall back (single, or two taking turns) |
| 2 onward | Piston pillars that rise and sink out of the lava in a wave; ride them across |
| 4–5 | The hunter drone (follows you and drops when it is overhead), mixed with everything above |

Each world's finale ends with its own celebration and music.

## Medals

- **Iron:** clear the level.
- **Steel:** collect every piece of coal in a single run.
- **Gold:** finish within 10% of the Forgemaster's time.

The Forgemaster has cleared every level, and a solver running the game's own physics has proven every level can be cleared, including a route that collects all the coal. Once you clear a level yourself, **Watch the Forgemaster** shows his run.

## Files

- `index.html`: the whole game in one file (graphics, physics, generated music, levels).
- `manifest.webmanifest`, `icon-180.png`, `icon-512.png`: Home Screen icon and app settings.
