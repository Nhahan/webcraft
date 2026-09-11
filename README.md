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
  SHA-256: `d878bb84f026b5c8aa1ac3df0ce63b93fbe35e77a04f41d4d3217c86fb45676d`
- File: `assets/webcraft_wasm.4e2aa95af732ffd584e7a81c8ee0aeeb7590090b9b6cd4186c4b3396671893da.wasm`
  SHA-256: `4e2aa95af732ffd584e7a81c8ee0aeeb7590090b9b6cd4186c4b3396671893da`
