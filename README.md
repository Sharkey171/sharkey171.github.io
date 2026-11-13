# sharkey171.github.io

The top-level address for Seylumi (the app itself lives in the `cadence` repository, at https://sharkey171.github.io/cadence/).

- `index.html` sends visitors to the Seylumi welcome page, so https://sharkey171.github.io/ works as a short address.
- `.well-known/assetlinks.json` proves to Android that the Google Play app and this website belong together, so the app opens without a browser address bar. It gets the app's signing fingerprints once the Play Console app exists.
- `.nojekyll` makes GitHub publish the `.well-known` folder (it skips folders starting with a dot otherwise).
