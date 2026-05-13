# Glücksrad

A minimalist, weighted wheel of names that lives in a single HTML file.

**Live app:** [gluecksrad.arnesano.xyz](https://gluecksrad.arnesano.xyz)

## Features

- **Weighted entries** — give each name a bias so favourites (or unlucky ones) come up more often.
- **Hold-to-spin** — press and hold `Space` or the spin button; the longer you hold, the stronger the spin.
- **Saved groups** — manage recurring rosters without re-entering names every time.
- **JSON import / export** — round-trip your groups as JSON.
- **AuD-Platform integration** — paste a JSON array exported from the AuD platform to spin up an exercise group in one click. Names are taken from `_firstname` / `_lastname`, and the `presented` counter can optionally be carried over as the entry weight so students who have already presented less often come up more often.
- **Bilingual UI** — toggle between German and English.
- **Zero dependencies** — one `index.html`, no build step, no tracking, no backend. State lives in `localStorage`.

## Running locally

```sh
# any static server will do
python3 -m http.server 8000
# then open http://localhost:8000
```

Or just open `index.html` directly in a browser.

## Tech

Vanilla HTML, CSS, and JavaScript. No frameworks, no bundler, no `package.json` — the whole app is a single file.

## Status

Vibe-coded, quick and dirty — a weekend afternoon, one HTML file, no roadmap. Issues and PRs welcome, but don't expect production polish.

## License

MIT
