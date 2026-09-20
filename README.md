# jainaryan.github.io

Personal academic website. Static HTML, no build step, no dependencies.

Based on [Jon Barron's template](https://github.com/jonbarron/jonbarron_website),
with a light-mode fix, a mobile breakpoint, and a typographic rework of the
section list.

## Structure

| Path | What it is |
| --- | --- |
| `index.html` | The whole site. |
| `stylesheet.css` | Template CSS plus the modifications above. |
| `images/` | Profile photo and paper figures. |
| `data/` | CV. |

## Local preview

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deployment

Served by GitHub Pages from `main`.
