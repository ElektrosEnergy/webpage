# Elektros — GitHub Pages site

This repository contains a simple, responsive GitHub Pages site for "Elektros" — a clean-energy technology brand, including an Investor Relations page.

Quick checklist before publishing
1. Replace `assets/logo.svg` (or `assets/logo.png`) with your provided logo if you want the exact branding mark.
2. Replace `assets/lithium.svg`, `assets/investors.svg`, and `assets/favicon.svg` if you want custom images. (Optional)
3. Replace `assets/elektros-deck.pdf` with your investor deck if you want the download link live.
4. Set your custom domain in the `CNAME` file (replace `yourdomain.com`).
5. Update contact emails inside the site (hello@elektros.com and investors@elektros.com) to real addresses.

Publishing options
- Project site (current): push files to any repo (this one). Pages URL will be:
  `https://elektrosenergy.github.io/webpage/` (replace `webpage` by the repo name if different)

- Org root site (optional): If you'd like the site at `https://elektrosenergy.github.io/`, create a repo named `ElektrosEnergy.github.io` and push these files there instead.

DNS notes
- For apex domains (example.com) use the GitHub Pages A records:
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153
- For subdomains (www.example.com) create a CNAME to `elektrosenergy.github.io` (or the repo Pages hostname).

If you want me to make additional edits (copy changes, SEO tags, analytics, contact form wiring) tell me which changes.
