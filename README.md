# KON Board — Konverto Hackathon 2026

Interactive dashboard built from the fictional Konverto Labs hackathon dataset.

## Demo

 https://crissilva1901.github.io/kon-board-hackathon-2026/


## Files

- `index.html`: page markup and interactive controls
- `style.css`: styles and responsive layout
- `app.js`: interactive charts, filters and Who Pays simulator
- `data.json`: original fictional hackathon dataset

## Local usage

Run a static web server in the repository folder, for example:

```bash
python -m http.server 8000
```

Open `http://localhost:8000`. Opening `index.html` as a `file://` URL will not load `data.json` in browsers that block local fetches.

## Notes

This is a browser-only interactive prototype. Finance scenario changes are saved in that browser's local storage; they are not written back to the JSON or shared across devices. The supplied dataset is fictional and May and November are partial months. Missing reports are not equivalent to zero usage.

## Data permissions

Sample records originate from hackathon materials provided by Konverto Labs. 
