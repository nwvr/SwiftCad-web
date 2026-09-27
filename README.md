# SwiftCad web (GitHub Pages)

This public repository holds **only compiled** SwiftCad WebAssembly assets
(`index.html`, `Package/*.wasm`, `Package/*.js`, sample CIF files). It does
**not** contain the private Swift sources.

## Enable Pages

1. **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / root (`/`)

Site URL (project Pages):

`https://<owner>.github.io/SwiftCad-web/`

## How it is updated

A GitHub Actions workflow in the private source repo builds the WASM client and
force-pushes an orphan `main` commit here (no history of sources).
