# Signal board

A tiny single-page soundboard used as an audience-feedback tool during
presentations. Scan the QR code, tap an animal, and the sound plays on your
phone as a signal to the presenter.

Live site: https://lronpaw.github.io/signal-board/

## Adding or changing sounds

1. Drop an `.mp3` / `.m4a` / `.ogg` file into `sounds/`.
2. Add an entry to `sounds/manifest.json`:
   ```json
   { "label": "Duck", "emoji": "🦆", "file": "duck.mp3" }
   ```
3. Commit and push — GitHub Pages rebuilds automatically.

See [CREDITS.md](CREDITS.md) for sound attributions.
