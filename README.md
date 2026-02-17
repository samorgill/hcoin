# Harrison's Roblox-Style Mini Web Game

A tiny obby platformer you can run in a browser.

## Play it
1. Open `/Users/samorgill/projects/hdogg/index.html` in a web browser.
2. Desktop controls: move with `A/D` or arrow keys, jump with `W`, `Up Arrow`, or `Space`.
3. iPad touch controls: swipe left/right on the game area to move, swipe up to jump, or tap to jump.
4. You can also use the on-screen `Left`, `Right`, and `Jump` buttons on touch devices.
5. Collect all coins, then touch the green finish block.

## Let Harrison edit it
Open `/Users/samorgill/projects/hdogg/index.html` and find:
- `SETTINGS` (near the top of the `<script>`)
- `LEVEL` (right below `SETTINGS`)

Good first edits:
- Change player color: `playerColor`
- Make movement faster/slower: `playerSpeed`
- Make jumps higher/lower: `jumpPower`
- Add/remove platforms in `LEVEL.platforms`
- Add/remove coins in `LEVEL.coins`

## Quick ideas
- Make a super hard mode by removing some platforms.
- Make an easy mode by adding extra platforms over gaps.
- Change hazard locations in `LEVEL.hazards`.
