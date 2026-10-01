# landing-cleanroll

Landing page for [CleanRoll](https://github.com/roypm/cleanroll), published at [cleanroll.roypm.es](https://cleanroll.roypm.es).

One page: `index.html`, Tailwind, and a little JavaScript. The copy is in English, Spanish, and Catalan. English is the default. If the browser is set to Spanish or Catalan, the page uses that language.

## Folders

- `assets/` is what the page loads: logo, video, and walkthrough shots.
- `source/` holds the original materials. It is not published.
- `DESIGN.md` is the style reference.

## Preview locally

```bash
python3 -m http.server 8765
```

Open `http://127.0.0.1:8765`.

## Publishing

Each push to `main` deploys the page with GitHub Pages. The domain is set in `CNAME`.
