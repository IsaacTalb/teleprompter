# Isaac Teleprompter

Isaac Teleprompter is a lightweight frontend-only teleprompter built with HTML, Tailwind CSS, and vanilla JavaScript. It is designed for creators who want a clean camera preview, mirrored scrolling script, and quick install support on mobile devices.

## Features

- Live camera preview with an overlay for readability.
- Large teleprompter text with tap-to-play / tap-to-pause scrolling.
- Adjustable text size and scroll speed.
- Mirror mode for camera rigs and reflective setups.
- Script persistence with `localStorage`.
- Fullscreen support for distraction-free recording.
- Basic PWA setup with a manifest and service worker for installability.

## Getting started

Because camera access usually requires a secure origin, use a local server instead of opening the file directly.

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000> in your browser.

## iPhone / iOS install notes

1. Serve the app over HTTPS in production.
2. Open the app in Safari.
3. Tap **Share** → **Add to Home Screen**.
4. Grant camera permissions when prompted.

## Project structure

- `index.html` — main UI, styling hooks, and application logic.
- `manifest.json` — PWA metadata.
- `sw.js` — simple service worker for offline caching.
- `LICENSE` — open-source license for the project.

## Open source

This project is open source under the MIT License. See [`LICENSE`](./LICENSE) for details.
