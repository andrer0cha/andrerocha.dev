# andrerocha.dev

Plain HTML and CSS, no build step. GitHub Pages serves it as is.

- `index.html`: home
- `pilot/`: First Agent Pilot
- `agents/cleaning/`: page for cleaning-business software (copy this folder for the next vertical)
- `writing/`: add one `<div class="post">` per article
- `about/`
- `assets/site.css`: all styles

Publish: push to GitHub, Settings → Pages → Deploy from branch `main` / root.
Custom domain: `CNAME` already says `andrerocha.dev`. At your DNS provider add four A records for `@`
(185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) and a CNAME `www` → `<user>.github.io`.
Then tick "Enforce HTTPS" in Settings → Pages.
