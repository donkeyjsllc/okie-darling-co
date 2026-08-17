# Okie Darling Co — Site

Static site, no build step. `index.html` + `styles.css` + `script.js` + `assets/logo.jpg`.

## To push to your repo
```
git add .
git commit -m "Initial site build"
git push
```

## Still needed before this goes live
1. **GoFundMe link** — currently a placeholder `href="#"` in the "Chip In Toward the Mission"
   card (`index.html`, search for `gofundme-link`). Swap in the real URL.
2. **Facebook URL** — currently set to `https://www.facebook.com/OkieDarlingCo` as a best
   guess. Confirm this matches her actual page URL/handle before launch.
3. **Photos** — no real photos are in this build yet (only the logo). Once Madison sends
   usable photos, they can be dropped into `assets/` and swapped into the hero, about, or
   angel tree sections.
4. **Angel Tree specifics** — the section currently has general copy. If she wants exact
   dates, sponsor instructions, or a sign-up link for this year's tree, add those in.

## Connecting the domain (Cloudflare Pages)
1. Workers & Pages → Create → Pages → Connect to Git → select this repo.
2. Framework preset: None (static HTML).
3. Once deployed, go to the domain's DNS settings — Cloudflare will offer to auto-connect
   okiedarlingco.com to the Pages project.
