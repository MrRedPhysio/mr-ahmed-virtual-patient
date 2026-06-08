# Mr Ahmed – OSCE-Style Virtual Patient Website

This folder is ready to upload to GitHub Pages, Netlify, Vercel, Moodle, or another web host.

## Files included

- `index.html` – the full interactive virtual patient simulation
- `assets/mr-ahmed-portrait.png` – Mr Ahmed portrait used in the welcome pop-up
- `.nojekyll` – helps GitHub Pages serve the site without processing issues

## Quick local test

1. Open this folder.
2. Double-click `index.html`.
3. The virtual patient should open in your browser.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `mr-ahmed-virtual-patient`.
2. Upload all files and folders from this package.
3. Go to **Settings** → **Pages**.
4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Click **Save**.
6. GitHub will give you a public link. Share that link with lecturers, students and assessors.

## Publish with Netlify

1. Go to Netlify.
2. Choose **Add new site** → **Deploy manually**.
3. Drag the whole extracted folder into Netlify.
4. Netlify will create a public link automatically.

## Important

Do not upload only `index.html` by itself unless you also upload the `assets` folder. The portrait image is stored separately so browsers load it more reliably.
