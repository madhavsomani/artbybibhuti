# Bibhuti Mohapatra — Artist Portfolio

A responsive, single-page artist portfolio built from the 106 photographs supplied in the `ArtbyBibhuti` Google Drive folder.

## Preview

```bash
cd site
python3 -m http.server 8080
```

Open http://localhost:8080.

## Structure

- `site/index.html` — complete responsive site
- `site/images/` — optimized WebP versions of the 106 source HEIC photographs
- `site/staticwebapp.config.json` — Azure Static Web Apps routing/security headers
- `source/` — original Drive download (not required for deployment)
- `analysis/` — contact sheets and signature inspection images (not required for deployment)

## Content notes requiring confirmation before public launch

- **Artist name:** “Bibhuti Mohapatra” is strongly inferred from the folder name (`ArtbyBibhuti`) and recurring visible signatures (“Bibhuti” on archive works; “Mohapatra” on later paintings), but should be confirmed by the owner.
- **Biography/contact:** intentionally marked as forthcoming; no biography, location, exhibition history, pricing, or contact details were invented.
- **Dates:** the two archive descriptions use visible dates on the works (1990 and 1992).

## Deployment

The `site/` folder is deployment-ready for any static host, including Azure Static Web Apps, Netlify, Vercel, GitHub Pages, or Cloudflare Pages. No build command is required.
