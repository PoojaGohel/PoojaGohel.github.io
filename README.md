# VelvetJS

Landing site for the VelvetJS ecosystem, hosted via GitHub Pages at [velvetjs.github.io](https://velvetjs.github.io).

## Packages

- [velvet-writer](https://www.npmjs.com/package/velvet-writer) — Notion-style rich text editor for React and Tailwind CSS
- [velvet-image-dropzone](https://www.npmjs.com/package/velvet-image-dropzone) — Drag-and-drop image uploader with preview support
- [velvet-qr](https://www.npmjs.com/package/velvet-qr) — Customizable QR code generator for React

## Local preview

Open `index.html` directly in a browser, or serve the directory:

```bash
npx serve .
```

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which publishes this repo to GitHub Pages.

Before going live, replace the placeholders in this repo:

- `YOURNAME` — your Buy Me a Coffee handle
- `assets/writer-demo.png`, `assets/dropzone-demo.png`, `assets/qr-demo.png` — actual screenshots
