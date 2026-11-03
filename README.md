# creasegame.com

The Crease website, served by GitHub Pages.

- `index.html` the home page
- `play/` where shared links land (`https://creasegame.com/play#w2-4&t=127&f=1`).
  With Crease installed, iOS opens these straight in the app (universal links).
- `.well-known/apple-app-site-association` tells iOS which links belong to Crease.
- `.nojekyll` lets GitHub Pages serve the `.well-known` folder.
