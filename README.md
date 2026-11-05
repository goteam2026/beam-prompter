# Beam Prompter

A free teleprompter for iPad glass (beam-splitter) stands. Mirroring included.

**Open it:** https://goteam2026.github.io/beam-prompter/

## Put it on the iPad

1. Open the link above in **Safari**.
2. Tap **Share → Add to Home Screen**.
3. Always launch it from the Home Screen icon. It opens full screen and works offline after the first load.

Scripts and settings are saved on the iPad only. The Home Screen app keeps its own storage, separate from Safari, so type or paste scripts inside the Home Screen app.

## Features

- Mirror text, and flip upside down for rigs that need it
- Text size, line spacing, side margins, alignment, all caps
- Scroll speed, 3 s or 5 s countdown, movable amber reading line
- Tap to play or pause, drag to scroll by hand
- Bluetooth remotes and keyboards. Defaults: Space/Enter play/pause, ↑ ↓ page up/down, ← → text size, + − speed, Esc back to the editor
- **Remote and keyboard** panel: shows what each remote button sends, and lets you assign any button (keys, scroll, or media buttons) to any action
- **Catch media buttons**: play/pause and next/previous buttons on remotes go to the iPad's media player, not the page. With this on, the app plays a silent loop so those buttons reach the prompter (it pauses other audio)
- `[text in brackets]` shows as an amber cue
- Keeps the screen awake while prompting

## Updating

Edit the files, then change `VERSION` at the top of `sw.js` (for example `beam-prompter-v1` → `beam-prompter-v2`) before pushing. iPads pick up the new version the next time they open the app online, and show it on the launch after that.
