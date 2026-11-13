# MiniSlice

A free, browser-based slicer for small desktop printers, with a pen-drawing mode.
Everything runs in the browser. Models are not uploaded anywhere.

## Disclaimer

MiniSlice is an independent, unofficial project. It is not made by, endorsed by,
sponsored by, or affiliated with Toybox or its owners. Toybox is named only to say
which build size the plate profile matches (75 × 80 × 90 mm). Heated parts and moving
machines can cause harm: watch every print and check the first layers.

## Put it on the web (free)

Option A, Netlify Drop (no account needed to try):
1. Open https://app.netlify.com/drop
2. Drag the whole `release` folder onto the page.
3. Netlify gives you a public address. Share that address.

Option B, GitHub Pages:
1. Create a repository and upload `index.html`.
2. In Settings → Pages, choose the main branch and save.
3. Your site appears at https://YOUR-NAME.github.io/REPO-NAME/

## Before you publish

- Keep the disclaimer on the site and in the app (it is already in both).
- Do not use Toybox logos, product photos, or the Toybox name in the site title,
  domain name, or social media handles.
- If you plan to sell it or make money from it, have a lawyer review the name, the
  disclaimer, and the look of the app.
- Choose a license (for example MIT) and add a LICENSE file if you want others to reuse the code.

## Files

- `index.html`: the whole app in one file. It loads Three.js from cdnjs.cloudflare.com.
