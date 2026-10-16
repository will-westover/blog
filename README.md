# STAT 386 Tutorial Blog

Quarto website published with GitHub Pages at
<https://will-westover.github.io/blog/>.

- Tutorial post: [`posts/yolo-detections-to-dataframe/index.qmd`](posts/yolo-detections-to-dataframe/index.qmd)
- Rendered site: `docs/` (served by GitHub Pages from `main` → `/docs`)

## Work on it

```bash
uv sync
uv run quarto preview
```

## Publish

```bash
uv run quarto render
git add .
git commit -m "..."
git push
```

Always run a full `quarto render` before pushing, otherwise `docs/` (the live site) won't update.
