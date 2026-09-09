# WebCraft

WebCraft is a browser-only 3D voxel survival game distributed as HTML
and a same-origin authority WASM file.

## Links

- [Play WebCraft](https://nhahan.github.io/webcraft/)
- [Open the asset gallery](https://nhahan.github.io/webcraft/#assets)

## Standalone edition

- Runs without a backend, CDN, or third-party assets.
- Uses the shared WebCraft client with a browser-local authority runtime.
- Stores nicknames, worlds, and gameplay state locally in the browser.

## Artifacts

Host `index.html` and `assets/` together over HTTP(S), preserving their relative paths.
Opening the HTML via `file://` or copying it alone is not supported.

- File: `index.html`
  SHA-256: `dd0998d004d9660a978a2340565bdb13c2402431c582782127ee031cb0d180a8`
- File: `assets/webcraft_wasm.9da373ea655f203674b2c1d2149903032351014d28593ba568cc49bf686125c8.wasm`
  SHA-256: `9da373ea655f203674b2c1d2149903032351014d28593ba568cc49bf686125c8`
