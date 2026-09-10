# Ben Clayton — Portfolio

A responsive single-page software engineering portfolio built with semantic
HTML and modern CSS. It introduces selected public projects across automation,
full-stack development, building-management integrations, media systems, and
Rust game development.

## Run locally

No build step is required. Open `index.html` directly or serve the directory:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Design goals

- fast static delivery with no client-side framework;
- keyboard-accessible navigation and visible focus behaviour;
- responsive layouts from mobile to wide screens;
- readable typography and contrast; and
- reduced-motion support.

## Structure

- `index.html` — content and document metadata
- `global.css` — layout, theme, typography, and responsive states
- `assets/img/me.jpg` — profile image
