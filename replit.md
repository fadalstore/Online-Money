# Fadal Store

A static HTML website for Fadal Store — a financial freedom and online business resource hub written in Somali.

## Structure

- `index.html` — Main landing page
- `article1.html` through `article30.html` — Individual article pages (30 articles)
- `about.html`, `contact.html`, `privacy-policy.html`, `terms-of-service.html` — Static pages
- `ai-tools.html`, `apps.html`, `freelancing.html`, `make-money-online.html` — Topic pages
- `admin.html` — Private admin panel for creating new posts (password: fadal2024)
- `sitemap.xml` — SEO sitemap with image entries, correct canonical URLs, and all 30 articles
- `robots.txt` — Search engine crawling rules
- `sw.js` — Service worker for PWA support
- `generate_articles.js` — Script for generating article pages

## Admin Panel

Access at `/admin.html` — password protected (password: `fadal2024`).
Features:
- Create new articles with a visual builder form
- Select from curated Unsplash images
- Add multiple sections with text and images
- Generate ready-to-save HTML code
- View all 30 existing articles
- Sitemap information and Google Search Console instructions

## SEO

- Sitemap URL: `https://fadalstore.github.io/Online-Money/sitemap.xml`
- All articles include proper OG image meta tags, Twitter card meta, and canonical URLs
- All 30 articles now use real Unsplash images (no more placeholders)
- Sitemap includes image namespace entries for all articles

## Running

The site is served via Python's built-in HTTP server on port 5000.

**Workflow:** `Start application` runs `python3 -m http.server 5000 --bind 0.0.0.0`

## Deployment

Configured as a static deployment with `publicDir = "."`.
Deploy and submit sitemap to Google Search Console:
`https://fadalstore.github.io/Online-Money/sitemap.xml`
