# Fadal Store

A static HTML website for Fadal Store — a financial freedom and online business resource hub written in Somali.

## Structure

- `index.html` — Main landing page
- `article1.html` through `article30.html` — Individual article pages
- `about.html`, `contact.html`, `privacy-policy.html`, `terms-of-service.html` — Static pages
- `ai-tools.html`, `apps.html`, `freelancing.html`, `make-money-online.html` — Topic pages
- `sitemap.xml`, `robots.txt` — SEO files
- `sw.js` — Service worker for PWA support
- `generate_articles.js` — Script for generating article pages

## Running

The site is served via Python's built-in HTTP server on port 5000.

**Workflow:** `Start application` runs `python3 -m http.server 5000 --bind 0.0.0.0`

## Deployment

Configured as a static deployment with `publicDir = "."`.
