# SI ($SI) — Stupid Intelligence

Not Super. Just Stupid.

Static meme-token site for **Stupid Intelligence** — one brain cell, maximum confidence, purple-hoodie ape.

## Live site

After deploy: [https://aaaa-web-deploy.github.io/SI/](https://aaaa-web-deploy.github.io/SI/)

## Edit before launch

Open `index.html` and set `window.SI_CONFIG`:

```js
window.SI_CONFIG = {
  CA: '',        // Solana contract address
  X: '',         // https://x.com/...
  TELEGRAM: '',  // https://t.me/...
  DEX: '',       // chart URL (auto from CA if empty)
  BUY: ''        // buy URL (auto from CA if empty)
}
```

Leave fields blank until the CA and official links exist. The page shows “Coming soon” and safe placeholder toasts.

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
npx --yes serve .
```

## Deploy

Push to `main`. GitHub Actions publishes the folder to GitHub Pages.

## Assets

| Path | Use |
| --- | --- |
| `media/*.webp` | Character scenes used by the page |
| `assets/logo*.png` | Favicon / avatar |
| `assets/social-preview.jpg` | Open Graph / Twitter card |
| `assets/characters/*.png` | High-res source art |
