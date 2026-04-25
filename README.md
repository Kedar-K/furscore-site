# furscore-site

Marketing landing page + Privacy Policy for [FurScore](https://furscore.app), a dog wellness iOS app.

## Pages

- `index.html` — landing page
- `privacy.html` — privacy policy (linked from the App Store listing and the in-app Settings)
- `styles.css` — shared styles, brand-aligned dark theme with emerald teal accents

## Hosting

Deploy as a static site on Netlify:

1. Connect this repo in Netlify
2. Build command: *(none)*
3. Publish directory: `/` (repo root)

After deploy, the URLs become:
- `https://<netlify-subdomain>.netlify.app/` → landing
- `https://<netlify-subdomain>.netlify.app/privacy` → privacy policy

Update the canonical privacy URL in `app-store-metadata.md` (in the FurScore main repo) once Netlify is live.

## Updating the privacy policy

Edit `privacy.html` directly. Bump the **Last updated** date at the top whenever you change it. Material changes should also be communicated in-app before taking effect.
