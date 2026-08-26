# Personal Toolbox 1.0

Small everyday tools for personal use.

## Included

- `index.html` — Toolbox dashboard
- `price-compare.html` — multi-product unit-price comparison
- `manifest.webmanifest` — installable web app metadata
- `service-worker.js` — offline app-shell cache
- `apple-touch-icon.png` — iPhone/iPad Home Screen icon
- `icon-192.png`, `icon-512.png` — PWA icons
- `favicon-32.png` — browser favicon

## Price Compare

- Add/remove any number of products
- Automatic labels: A, B, C … Z, AA …
- Per-product currency: EUR, CNY, USD, TRY, INR, JPY
- Optional note for each product
- Output currency independently selectable from the same six currencies
- Live ranking by normalized price per 100 quantity units
- Shows how much more expensive each option is than the cheapest
- Daily FX data from Frankfurter
- Last successful FX rates cached for offline use
- Current comparison automatically saved in localStorage
- `Clear` resets the current comparison
- Decimal comma and decimal point are both accepted

### Quantity rule

All products must use the same quantity unit. The UI deliberately does not ask for a unit.

## GitHub Pages

Upload all files to the root of the repository and enable GitHub Pages for that branch/folder.

## iPhone / Safari

1. Open the GitHub Pages URL in Safari.
2. Tap Share.
3. Choose **Add to Home Screen**.
4. Launch **Toolbox** from the Home Screen.

The app uses the supplied `apple-touch-icon.png`, runs in standalone mode, respects iPhone safe areas, and caches its local app shell for offline launches.
