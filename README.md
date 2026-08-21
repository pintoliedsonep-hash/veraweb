[Uploading READ-ME.md…]()
# Vera Web — website

Four static pages: `index.html` (Home), `services.html`, `portfolio.html`, `contact.html`, plus `css/style.css`. No build step — just files.

## To preview
Open `index.html` in any browser. Keep the folder structure as-is (the pages link to `css/style.css` with a relative path).

## To publish
Any of these work, since it's plain HTML/CSS:
- **Netlify / Vercel** — drag the whole folder into their web dashboard, done in ~1 minute (free).
- **GitHub Pages** — push the folder to a repo, turn on Pages.
- Any regular web host — upload the folder via FTP.

You'll also want a domain (e.g. `veraweb.co.mz` or `.com`) — happy to help pick a registrar/host once you're ready.

## Notes
- Uses Google Fonts (Poppins) via a CDN link in `style.css` — needs internet to load, which is fine once it's live on a real host.
- The contact form uses a `mailto:` action (opens the visitor's email app) since there's no backend yet — works for now, but a form service (like Formspree) would feel more professional later if you want.
- Same brand system as the business card/poster: navy `#0B2545`, blue `#1B5FA6`, cyan `#2FA8D9`, the browser-window logomark, and the loading-bar motif.
- Portfolio page shows the project process (Discovery → Design → Build → Launch) instead of finished work, per your call — easy to swap in real projects later.
