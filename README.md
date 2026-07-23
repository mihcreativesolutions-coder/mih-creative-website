# MIH Creative Solutions — Site

A single scrolling page for MIH Creative Solutions, styled to the brand's look-and-feel spec (cream canvas, dark-ink CTAs, the 6-color saturated feature card cycle, rounded display type).

## Structure

- `index.html` — page content and layout
- `styles.css` — design tokens + component styles
- `script.js` — mobile nav toggle, scroll-reveal animation, footer year

No build step or dependencies — it's plain HTML/CSS/JS.

## Preview locally

```
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploying

This is a static site, so it can be hosted as-is on GitHub Pages, Netlify, Vercel, or similar. It is **not** a Squarespace template — Squarespace doesn't accept raw HTML/CSS files as a full site. To use this content on Squarespace, either:

- Host it separately (GitHub Pages/Netlify) and point a custom domain at it, or
- Rebuild the sections inside Squarespace's editor by hand, using this file as the copy/design reference, or
- Paste individual sections into Squarespace **Code Blocks** (limited — no full-page control).

## Content notes

- Contact CTA is a single `mailto:mihcreativesolutions@gmail.com` link (per request — no contact form).
- No testimonials are included since none were provided; add real client quotes to the "Why MIH" or a new testimonials section once available.
