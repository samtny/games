# games

Small, self-contained browser games. Open `index.html` (or the GitHub Pages site) for the menu.

| Game | Path | Notes |
| --- | --- | --- |
| Superformula Squadron | [`superformula-squadron/`](superformula-squadron/) | Mobile-friendly vertical shooter. Enemy ships and bosses are generated from the Gielis superformula, deterministically from a sector seed. Drag to fly; firing is automatic. |

## Superformula Squadron

- **Seeds** — each sector seed deterministically generates 8 enemy families (silhouette, colours, movement pattern, weapon, stats), every wave's composition, and an endless series of bosses. Share a sector with `superformula-squadron/?seed=YOURSEED`, or use the *Daily* button for the seed of the day.
- **Controls** — drag anywhere on the screen to move (relative, so your finger never covers the ship); guns fire automatically. Desktop: arrow keys / WASD, `P` or `Esc` to pause.
- **Bosses** — every 5th wave. Bosses morph between two superformula shapes and have three phases; some attacks fire "bloom" bullet clouds whose shape follows the boss's current silhouette.
- No build step and no external dependencies: each game is a single HTML file.

## GitHub Pages

Serve from the repository root (Settings → Pages → Deploy from branch → `/ (root)`). The root `index.html` links to each game.
