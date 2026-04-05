# Fadal Store — Jekyll Website

## Overview
Fadal Store is a Somali-language blog and educational platform about online business, remote work, and programming. Built with Jekyll (Ruby static site generator) using the Mediumish theme.

## Tech Stack
- **Framework:** Jekyll 4.x (Ruby)
- **Theme:** Mediumish (Bootstrap 4)
- **Search:** Lunr.js (client-side)
- **Server:** Jekyll serve on port 5000

## Running the App
```bash
JEKYLL_NO_BUNDLER_REQUIRE=true jekyll serve --host 0.0.0.0 --port 5000
```
Note: The local bundler (2.0.1) is incompatible with Ruby 3.2 — use `JEKYLL_NO_BUNDLER_REQUIRE=true` to bypass it.

## Project Structure
```
_posts/          # 52 blog posts (article1-52) as Markdown files
_pages/          # Static pages (about, categories, tags + 12 restored legacy pages)
_layouts/        # Jekyll layout templates
_includes/       # Reusable HTML components
_sass/           # SCSS stylesheets
assets/          # CSS, JS, images
courses/         # Programming and security course lessons (HTML)
```

## Content
- **52 blog posts** in `_posts/` covering: freelancing, affiliate marketing, dropshipping, YouTube, programming, etc.
- **12 legacy content pages** restored from old website zip:
  - amazon-kdp-2026.html
  - building-a-global-personal-brand.html
  - cash-giraffe-app.html
  - essential-tools-for-remote-workers.html
  - finding-high-paying-remote-jobs-2026.html
  - fiverr-seller-levels-2026.html
  - managing-productivity-mental-health.html
  - partnerstack-somali.html
  - partnerstack.html
  - sir-cusub.html (Somali language)
  - tech-news-april-2026.html
  - youtube-monetization-2026.html
- **Google verification files** at root: google250c51e5fea180e9.html, googled378bcbdc246f969.html

## Key Notes
- Old website was plain HTML. Theme was migrated to Jekyll.
- Restored old pages preserve original URLs so Google-indexed links still work.
- Articles are tagged with categories: make-money-online, remote-work, programming, cybersecurity
- Author: "fadal" with avatar, bio, and social links in _config.yml
