# Physics-Aware Representation Learning for Physical Systems &mdash; Project Page

Project page for our NYU CSCI-GA 2572 (Spring 2026) final project. Built on the
[Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template).

## Local preview

Just open `index.html` in a browser, or:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy on GitHub Pages

The repo is already configured for the simplest setup (no Jekyll &mdash; `.nojekyll` is present).

1. Push to `main`:
   ```bash
   git add .
   git commit -m "Initial project page"
   git push -u origin main
   ```
2. On GitHub: **Settings &rarr; Pages &rarr; Source = Deploy from a branch &rarr; Branch: `main` / `/ (root)`**.
3. The site will be served at
   `https://saltfish-len.github.io/Physics-Aware-Project-Page/`.

## TODO before publishing

- Replace the four author `<a href="#">` placeholders in `index.html` with personal pages.
- Replace the `#` placeholder URLs in the "Code" and "Checkpoints" buttons.
- (Optional) Update the social-preview OG image at `static/images/main_diagram.png`
  if you'd like a dedicated 1200x630 image.

## Layout

```
index.html                       # the page itself
static/
  css/, js/                      # Bulma + carousel + slider (unchanged from template)
  images/                        # paper figures used in the page
  pdfs/paper.pdf                 # downloadable copy of the report
```

## License

Page content &copy; the authors. Page template under
[CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/), per the upstream template.
