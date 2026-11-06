# ARCSET Corporate Website

Static multilingual corporate website for ARCSET Co., Ltd.

## Preview locally

Run a static server from this directory, for example:

```powershell
python -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

## Updating

- Copy lives in `script.js` (`translations.en / ja / zh`); the HTML holds English fallback text.
- News items live in `news.json` (newest first); add an entry to publish.
- Styles in `styles.css`; the color system matches the ARCSET PowerPoint theme.
- Pushing to `main` publishes to www.arcset.jp via GitHub Pages (1–2 min).

## Languages

- English
- Japanese
- Simplified Chinese

The site selects a language from the visitor's saved preference or browser language. English is used as the fallback.
