# DotStudio

A responsive, local-first companion avatar maker built with plain HTML, CSS, JavaScript, and inline SVG. It has no backend and uses no external assets or libraries.

## Run

Open `index.html` directly in a modern browser, or serve the folder over HTTP:

```bash
python3 -m http.server 4173 --bind 0.0.0.0
```

Then visit the local server address. The Arena preview is served from the same folder.

## Included

- 38 editable shape presets, organized by category
- Face controls for eyes, expressions, mouth, brows, blush, highlights, and nose details
- 16 hat styles with color, trim, scale, tilt, and position controls
- Glasses and a multi-accessory layer list
- 18 palettes, custom colors, material and pattern controls
- Mood/state previews and animation playground
- Multiple saved Dots, starter gallery, local storage, undo/redo, randomize, and shareable design links
- PNG, SVG, JSON, sticker-pack ZIP, and React-snippet exports
- Responsive layout, dark/light themes, and reduced-motion support

## Notes

All characters are generated from original inline SVG and saved locally in the browser. The state animations are visual previews only; the app does not connect to an AI agent. WebM export is available only in browsers that support `MediaRecorder` and canvas capture.
