# xsf-site

Landing page for [**xsf**](https://github.com/CyVenom/Reflective_XSS), an async-first reflected XSS detection framework. This repo is just the marketing/demo site. The actual scanner lives in [Reflective_XSS](https://github.com/CyVenom/Reflective_XSS).

## What's here

- A single static page (`index.html`) with real content pulled from the tool's own README: its console output, its 10 reflection contexts, its 5-stage pipeline, its CLI commands, its test numbers.
- An in-page "run it" demo that replays a canned scan output on click, it does **not** make network requests or scan anything live.
- No build step, no framework, no dependencies. Plain HTML/CSS/JS.

## Running locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Design

Dark terminal theme: Geist for text, JetBrains Mono for code, OKLCH colour scale. All styles live in `styles.css`.

## License

MIT, see [LICENSE](LICENSE).
