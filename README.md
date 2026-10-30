# Arduino Roulette

A fast, minimal slot machine that picks three components for an Arduino project. Built for filming Instagram Reels, with illustrated parts from the ELEGOO UNO R3 Super Starter Kit.

## Run locally

Open `dist/index.html` in a modern browser, or serve the `dist` folder with any static web server. No build step or dependencies are required. Fonts load from Google Fonts; system fonts are used as a fallback.

## Use

- Click **Spin**, or press **Space**, to draw three parts.
- The music-note button toggles sound.
- The frame button switches to a portrait layout for recording.
- The info button shows the companion hardware bundled with each part.

Each draw includes an input, an output, and a distinct extra component. Labels stay off the main screen. Companion hardware counts as part of its main component's pack. The LCD and standalone knob cannot be drawn together because the kit contains one potentiometer.

## Files

- `dist/index.html` — page structure
- `dist/style.css` — layout, styling, and animations
- `dist/app.js` — component artwork, parts catalog, pack rules, and spinning behavior

The site uses vanilla HTML, CSS, JavaScript, inline SVG artwork, and the Web Audio API. Serve `dist/` to deploy it on a static host.
