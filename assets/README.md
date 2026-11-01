# Assets

## Structure

- `icons/` — favicon and brand icons
  - `favicon.svg` — vector favicon (preferred, used by modern browsers)
  - `favicon.png` — 64×64 raster fallback
- `images/` — raster images used by the site
  - `og-preview.png` — **(add manually)** 1200×630 social/OG preview image. Recommended: dark product banner with the AirPod earbuds and "AirPod" title. Until added, the Open Graph image meta tag points to this path and will 404 (harmless).

## Notes

- The hero product visual is rendered in real time with Three.js, so no product photo is required.
- To add the OG preview image, drop a 1200×630 PNG named `og-preview.png` into `images/`.
- Image generation quota was exhausted during build; raster assets can be generated later and dropped in here without code changes.
