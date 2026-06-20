# Pranav Kumar — Portfolio Website

This folder is a complete, ready-to-publish website. `index.html` is fully
self-contained (photo, certificates, and resume are all embedded), so the only
thing left to do is put it online. Pick whichever option below is easiest for you.

---

## Option 1 — Netlify Drop (fastest, no account signup flow, free)

1. Go to **https://app.netlify.com/drop**
2. Drag this entire `site` folder onto the page.
3. Done. You get a live URL like `https://pranav-kumar.netlify.app` in seconds.
4. (Optional) In Site settings → Domain management, rename it or add your own
   domain (e.g. `pranavkumar.dev`).

## Option 2 — GitHub Pages (free, good if you already use GitHub)

1. Create a new public repo, e.g. `portfolio` (or name it
   `<yourusername>.github.io` to get a clean root URL).
2. Upload the contents of this `site` folder (especially `index.html`) to the repo.
3. Repo → **Settings → Pages → Build and deployment**: set Source to
   "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. Your site appears at `https://<yourusername>.github.io/portfolio/`
   (or `https://<yourusername>.github.io/` if you used the special repo name).

## Option 3 — Vercel (free)

1. Go to **https://vercel.com**, sign in with GitHub.
2. "Add New → Project", import the repo containing this folder (or use the
   Vercel CLI: `npm i -g vercel` then `vercel` inside this folder).
3. No framework / no build command needed — it's a static site. Deploy.

## Option 4 — Cloudflare Pages (free)

1. **https://pages.cloudflare.com** → Create a project.
2. Connect your repo, leave build command empty, output directory `.`. Deploy.

---

## Custom domain (optional)

Once deployed on any host above, you can buy a domain (Namecheap, Google Domains,
Cloudflare, etc.) such as `pranavkumar.dev` and point it at your site in the
host's "Domain" / "Custom domain" settings. All four hosts give free HTTPS.

## Files in this folder

- `index.html`   — the website itself (this is everything; you can rename to
                   anything, but most hosts serve `index.html` automatically)
- `404.html`     — friendly "page not found" fallback
- `og-preview.jpg` — the image shown when the link is shared on social media
- `robots.txt`   — lets search engines index the site
- `netlify.toml` — config used automatically if you deploy on Netlify

## Updating later

Whenever you want changes, edit `index.html` (or ask for an updated version),
then re-drag the folder to Netlify / push to GitHub. The site updates in seconds.
