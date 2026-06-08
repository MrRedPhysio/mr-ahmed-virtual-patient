# Mr Ahmed Virtual Patient – PWA App Version

This package turns Mr Ahmed into an installable Progressive Web App (PWA).

## What is included

- `index.html` – the interactive virtual patient
- `manifest.json` – app name, icons and install settings
- `service-worker.js` – offline support after first load
- `assets/` – portrait and app icons
- `.nojekyll` – GitHub Pages compatibility

## How to test locally

You can open `index.html` directly to view it, but PWA install/offline features work best when hosted online.

## How to publish

### GitHub Pages
1. Create a GitHub repository.
2. Upload all files from this folder.
3. Go to Settings → Pages.
4. Choose Deploy from branch → main → root.
5. Open the GitHub Pages URL.
6. On phone/tablet/desktop, choose Add to Home Screen or Install App.

### Netlify
1. Go to Netlify.
2. Drag and drop the whole extracted folder.
3. Open the Netlify link.
4. Install it from the browser.

## Important

PWA installation only works reliably from a web link using HTTPS. GitHub Pages and Netlify both provide HTTPS automatically.

For iPhone/iPad:
- Open the site in Safari.
- Tap Share.
- Tap Add to Home Screen.

For Android:
- Open the site in Chrome.
- Tap the install prompt or three-dot menu.
- Tap Add to Home Screen / Install App.
