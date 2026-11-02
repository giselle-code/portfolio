# Giselle — Portfolio

A minimal, black portfolio with grass-green typography, a pointer-driven image trail, and a closely spaced masonry project gallery.

## Website

Static HTML, CSS, and JavaScript live in `site/`. No dependency installation or build step is needed. All images are local to the repository.

- `site/index.html`: page layout and content
- `site/style.css`: styling and responsive layouts
- `site/script.js`: image trail, project viewer, and mobile navigation
- `site/assets/trails/`: the 16 supplied portfolio images optimized for the pointer animation

The masonry gallery currently contains illustrative concept projects. The pointer animation uses Giselle's supplied artwork.

## Deployment

In repository **Settings → Pages → Build and deployment**, select **GitHub Actions** as the source. The included workflow publishes `site/` when changes are pushed to `main`, or when started manually in Actions.

Expected address after deployment: https://giselle-code.github.io/portfolio/

## Preview locally

Open `site/index.html` in a browser, or serve the `site/` folder with any static HTTP server.
