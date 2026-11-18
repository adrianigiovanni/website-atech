# A/TECH — Company website

Showcase website for **A/TECH**, a commercial and office fit-out company based in Roubaix,
France (shops, branches, offices, renovation). The site itself is in French.

**Live site:** <https://adrianigiovanni.github.io/website-atech/>

## Stack

- Static HTML, no framework and no build step
- Tailwind CSS (CDN)
- Fonts: Manrope and Work Sans (Google Fonts)
- Icons: Material Symbols Outlined
- Hosting: GitHub Pages

## Pages

| Page | File | Content |
|---|---|---|
| Home | `index.html` | One-page landing: hero, expertise, projects, approach, commitments, about, key figures, contact |
| Projects | `projets.html` | Portfolio filterable by category (shop, branch, office, renovation) |
| Legal | `mentions-legales.html` | Legal notice and GDPR privacy policy |

## Deployment

Hosted on GitHub Pages from the `main` branch: every push updates the live site within a minute
or two. All links and asset paths are relative, so the site works under a sub-path.

## Local development

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8080
# or
npx serve .
```

## Licence

© 2025 A/TECH. All rights reserved.
