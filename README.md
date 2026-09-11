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
  SHA-256: `6b126d17fb743ae497b4b05d070e0933a89b6114bb6d056f266909663d2fb970`
- File: `assets/webcraft_wasm.e8a9a99859111bb56a9ec2c3644ab7acde9608975e094b727ef072495e9898bd.wasm`
  SHA-256: `e8a9a99859111bb56a9ec2c3644ab7acde9608975e094b727ef072495e9898bd`
