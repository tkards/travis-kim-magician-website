# Travis Kim — Magician Website

Simple static site for Travis Kim (close-up magician) with homepage, booking page, and assets.

Quick start

1. Open the site locally: double-click [index.html](index.html) or serve with a simple static server.

   Python 3 (quick local server):

```bash
python -m http.server 8000
# then open http://localhost:8000
```

SEO & Local visibility tips

- Keep the title and meta description focused on "Seattle" and "close-up magician" (already added).
- Claim or create a Google Business Profile for "Travis Kim — Magician" with Seattle address and photos.
- Ensure images have descriptive `alt` text (already included in the HTML).
- Keep page fast: compress images, serve via CDN/Netlify for best results.
- Add backlinks (Gigsalad profile, local event listings) and list the business on relevant directories.
- The site includes JSON-LD structured data (Person) to help search engines understand the service.

Deployment options

- GitHub Pages: push this repo and enable Pages on the `main` branch.
- Netlify / Vercel: drag-and-drop or connect the repo for automatic deploys.

Files

- [index.html](index.html) — main homepage
- [booking.html](booking.html) — booking form that opens an email
- [css/styles.css](css/styles.css) — styles
- `assets/` — your photos (already present)

Next steps I can help with

- Configure a contact form that sends emails via an SMTP/Form endpoint.
- Optimize images (automated compression) and add a favicon.
- Create social preview meta tags (Open Graph / Twitter cards).
