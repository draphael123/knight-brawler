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
| `Shift` | Armored dodge-step |
| `E` | Pick up / throw a rock or pot (stuns through shields) |
| `R` | Restart level |
| `Esc` | Back to map |
| `M` | Open the Knight's Codex |

## Features

- **Combat feel:** combos, launchers, juggles, hitstun, hit-pause, screen shake, impact rings, blade flash
- **Enemy roster:** raiders, guards, ranged troops, casters, beasts, undead, and five unique chapter bosses
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
- **Final-art sprite system:** painted character sheets, 12-state hero and boss reels, directional hurt poses, recoveries, and non-graphic defeats
- **Five unique bosses:** Dire Wolf Alpha, Elder Treant, Bridge Troll, Risen Knight, and Black Knight each use bespoke art
- **Multilayer stages:** painted chapter plates, independently scrolling set pieces, combat-floor props, atmosphere, and foreground depth
- **Painted prop atlas:** chapter-specific shrines, thorn arches, bridge masonry, ruins, banners, braziers, and royal statuary
- **Living illuminated map:** animated route ink, selectable chapter seals, and persistent campaign records
- **Animation polish:** sprite blending, committed attack silhouettes, layered contact shadows, cloth, water, fog, embers, and footfall dust

Built with vanilla JavaScript + canvas. No dependencies, no build step.

🤖 Generated with [Claude Code](https://claude.com/claude-code)
