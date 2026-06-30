# mahmoudkhaled.dev

Personal portfolio site for Mahmoud Khaled — a minimal, single-page static site.

- **Stack:** plain HTML + CSS (no build step)
- **Theme:** gruvbox dark hard
- **Hosting:** GitHub Pages with custom domain `mahmoudkhaled.dev`

## Local preview

Just open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

The site is served by GitHub Pages from the `main` branch (root). The `CNAME`
file binds it to `mahmoudkhaled.dev`. Pushing to `main` publishes changes.

## Structure

```
index.html   # all markup
styles.css   # gruvbox dark hard styling
CNAME        # custom domain
```
