# Bibhuti Bhusan Mohapatra — Artist Portfolio

A responsive, single-page artist portfolio built from the 106 photographs supplied in the `ArtbyBibhuti` Google Drive folder. The public archive is intentionally curated to 38 non-redundant views.

## Preview

```bash
cd site
python3 -m http.server 8080
```

Open http://localhost:8080.

## Structure

- `site/index.html` — complete responsive site
- `site/images/` — optimized WebP versions of the 106 source HEIC photographs (38 curated views appear in the public archive)
- `site/staticwebapp.config.json` — Azure Static Web Apps routing/security headers
- `source/` — original Drive download (not required for deployment)
- `analysis/` — contact sheets and signature inspection images (not required for deployment)

## Content notes

- **Artist name:** Confirmed by the owner as **Bibhuti Bhusan Mohapatra** on 2026-08-15.
- **Biography/contact:** intentionally marked as forthcoming; no biography, location, exhibition history, pricing, or contact details were invented.
- **Dates:** the two archive descriptions use visible dates on the works (1990 and 1992).

## Deployment

The `site/` folder is deployment-ready for any static host, including Azure Static Web Apps, Netlify, Vercel, GitHub Pages, or Cloudflare Pages. No build command is required.
