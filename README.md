# Luzdewutts production baseline

The site is deployable as a static site using Netlify, Cloudflare Pages, or any HTTPS static host. `netlify.toml` adds security headers and publishes `src/`.

Before launch, replace `example.com` in `src/robots.txt` and `src/sitemap.xml`, replace placeholder business content/contact details, and connect `src/booking.html` and the homepage forms to an approved form/CRM provider. The current mailto fallback requires the visitor to have a configured mail application and should not be treated as reliable lead storage.

Preview locally with any static server from the repository root, serving `src/`.
