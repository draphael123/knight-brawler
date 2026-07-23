# Knight Brawler

A forest beat-’em-up — a single-file HTML5 canvas game. Play as an armored knight fighting through a campaign of waves: grunts, shield-knights, and archers, across a Castle-Crashers-style world map.

**[▶ Play it](https://knight-brawler.vercel.app)** · no install, just open in a browser.

## Controls

| Key | Action |
|-----|--------|
| `A` / `D` · `W` / `S` | Move (W/S walks into the screen) |
| `J` | Light attack (chains) |
| `K` | Heavy / launcher |
| `J, J, K` | Rising Slash (uppercut launcher) |
| `J, J, J, K` | Whirlwind (spin AoE) |
| `J, K` | Lunging Cleave (gap closer + guard break) |
| `K, K` | Earthbreaker (heavy area slam) |
| `Space` | Jump → `J`/`K` for aerials (K = dive) |
| `L` | Shield (costs stamina) |
| `Shift` | Dodge roll |
| `E` | Pick up / throw a rock or pot (stuns through shields) |
| `R` | Restart level |
| `Esc` | Back to map |
| `M` | Open the Knight's Codex |

## Features

- **Combat feel:** combos, launchers, juggles, hitstun, hit-pause, screen shake, impact rings, blade flash
- **Enemies:** shield-knights (block/bash, must be guard-broken or flanked), archers (telegraphed + fire arrows)
- **Stamina** system gating shield + roll, with guard-breaks
- **Campaign map** with 5 levels, progress saved locally
- **Persistent campaign record:** unlocked levels, best scores, attempts, and victories
- **Readable combat cues:** named enemy health plates, status labels, and attack-intent warnings
- **Readable encounters:** 2–3 active foes at once, with larger groups arriving as reinforcements
- **Ground telegraphs:** distinct arcs, lanes, circles, and ritual rings for each attack family
- **Dynamic score:** a unique procedural theme for every level, intensified during boss fights
- **Layered audio:** varied impacts, metal clashes, warning cues, projectiles, and reinforcement stingers
- **Knight's Codex:** move list plus persistent field notes for discovered enemies and bosses
- **Title screen, settings** (difficulty, screen shake, damage numbers), wave banners, score
- **Living forest:** fireflies, falling leaves, drifting mist, birds, campfire, a distant ruined castle
- **Distinct silhouettes:** enemy-specific proportions, stances, helmets, capes, robes, quivers, standards, and armor profiles
- **Five visual identities:** ancient Greenwood oaks and shrine, Thornwood arches, Old Bridge masonry, Ruined Gate, and the Keep throne hall
- **Secondary animation:** swaying foliage, cloth and banners, spectral tatters, water, fog, embers, boss breathing, creature tails, and footfall dust

Built with vanilla JavaScript + canvas. No dependencies, no build step.

🤖 Generated with [Claude Code](https://claude.com/claude-code)
