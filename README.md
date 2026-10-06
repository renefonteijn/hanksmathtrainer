# Hank's Multiplication Speed Trainer

A small, dependency-free website for iPad Safari and desktop browsers.

## What it does
- 30 random multiplication questions from 1×1 through 15×15
- Measures the time for every answer
- Green: 0–3 seconds
- Orange: 4–7 seconds
- Red: 8+ seconds
- Question-by-question speed graph
- 15×15 multiplication matrix with response times
- Saves the last 20 round summaries locally in the browser
- No login, server, database, or external libraries required

## Put it online
Upload the contents of this folder to any static website host. The important file is `index.html`.

### GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` and `manifest.webmanifest`.
3. Enable GitHub Pages in the repository settings.
4. Open the generated HTTPS URL on the iPad.

### Netlify / Cloudflare Pages
Create a new static site and upload this folder. No build command is needed.

## Add to an iPad Home Screen
1. Open the website URL in Safari.
2. Tap Share.
3. Choose **Add to Home Screen**.
4. Open the new **Hank Math** icon like an app.

The site works without external dependencies. The round-history feature uses the browser's local storage, so history is kept on that device/browser.
