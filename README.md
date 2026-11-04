# Ketamine – Drug Profile Dashboard

Static, self-contained website (no build step). Educational use only; not medical advice.

## Before deploying
1. Edit `index.html`: replace `YOURDOMAIN.com` (3 places) and the footer placeholders `[Your name]` and `[Module]`.
2. Edit `CNAME` to your real sub-domain, or delete the file if you use a free host address.

## GitHub Pages
1. Create a repo, upload all files in this folder.
2. Settings > Pages > deploy from `main` branch, root.
3. DNS: add CNAME record, host `ketamine`, value `<github-username>.github.io`.
4. Tick "Enforce HTTPS" once the certificate is issued.

## Netlify / Cloudflare Pages
Drag and drop this folder, add the custom domain, create the CNAME record they show.

## Still to add
Yearly trend, serious vs non-serious split and age distribution from openFDA (see the placeholder on the page).
