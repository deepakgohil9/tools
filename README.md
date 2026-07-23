# IT Tools

A small collection of single-page, browser-only utilities. No build step, no server — just static HTML/CSS/JS.

## Tools

| Tool | Description |
| --- | --- |
| [JSON Complexity](json-complexity.html) | Visualize JSON structure and complexity metrics. |
| [Markdown Preview](markdown.html) | Live Markdown editor with syntax highlighting. |

The [home page](index.html) links to every tool.

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Hosting on GitHub Pages

See the step-by-step instructions below in `DEPLOY.md`, or the short version:

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Select the `main` branch and `/ (root)` folder, then **Save**.
5. Your site goes live at `https://<username>.github.io/it-tools/` within a minute or two.
