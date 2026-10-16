# Minnesota Sensorimotor Flyers

Static hosting for three PDF flyers.

## Netlify import

- Production branch: `main`
- Base directory: leave blank
- Build command: leave blank
- Publish directory: `public`

`netlify.toml` sets the publish directory and PDF response headers. No build step is required.

## Retaining published links

PDF filenames include their event date and a SHA-256 prefix. Keep these files and filenames unchanged. When adding a revised flyer, add it under a new versioned filename and retain earlier files so existing links remain valid. `public/manifest.json` records file sizes and SHA-256 checksums.
