# memeWeather™

A Y2K-aesthetic meme-as-forecast iPhone web app. The forecast IS the meme — every day in the 7-day outlook is rendered as a hand-curated meme matched to the weather condition, with real attribution and a tasteful weather-stat panel underneath.

## What's in this repo

- `index.html` — single self-contained build. Just open it in a browser, or drop it on GitHub Pages / any static host.
- `Meme Weather.html` + `memeweather.jsx` + `ios-frame.jsx` + `tweaks-panel.jsx` — the source files (multi-file dev version).

## Hosting on GitHub Pages

1. Push this folder to a repo
2. Settings → Pages → Source: `main` branch, root
3. The single-file build at `dist/index.html` is the easiest target — copy it to repo root as `index.html`

## Features

- 7-day meme forecast feed (curated meme library, real attribution)
- Three formats: image macros (Drake, Distracted Boyfriend, Two Buttons, etc.), reaction images (This Is Fine, Disaster Girl, Roll Safe…), and rendered tweet cards
- Per-day weather stat panel: temp + H/L, feels-like, wind, humidity, precip%, UV
- Reactions, share, refresh, submit-meme modal, location search
- Tweaks panel: theme (teal/pink/lime), cursor sparkle trail, units (°F/°C), tone forcing

## Meme image source

Meme template images are fetched from the public Imgflip API (`api.imgflip.com/get_memes`) at runtime. No API key needed.

## License

Limited Use License — see [LICENSE](LICENSE).

Personal, educational, and non-commercial use only. The meme images themselves remain the property of their original creators (attribution shown on each card).
