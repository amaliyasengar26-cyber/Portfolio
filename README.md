# Portfolio
My professional portfolio website containing few of my B2B and B2C projects.

## Structure

- `site/index.html`: the whole site. The homepage and all six case studies live in this one page; each case study opens at `#cs/<name>` (for example `#cs/virtual-bundles`).
- `site/assets/style.css`: all styles.
- `site/work/assets/`: case-study images, one folder per project.

## Deploying

There is no build step. `netlify.toml` tells Netlify to serve the `site/` folder, so a Netlify site connected to this repo redeploys on every merge to `main`.

To preview locally: `python3 -m http.server -d site` and open http://localhost:8000.
