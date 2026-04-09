# Janine Standish Wellness Site

Static marketing site for Janine Standish Wellness. The repo is intentionally simple: one HTML file, one stylesheet, one small script, and local image assets.

## Stack
- HTML
- CSS
- Vanilla JavaScript
- Static hosting on Vercel or any basic file host

## Local development
```bash
cd "/Users/josephstewart/Documents/Janine"
python3 -m http.server 8000
```
Open `http://localhost:8000`.

## SEO improvements included
- Optimized `<title>` and `<meta name="description">`.
- Canonical URL.
- Open Graph + Twitter metadata.
- Structured data (`LocalBusiness` JSON-LD).
- `robots.txt` and `sitemap.xml`.

## Critical post-launch visibility steps
1. Verify domain in Google Search Console.
2. Submit sitemap: `https://www.janinestandish.com/sitemap.xml`.
3. Create/verify Google Business Profile and keep NAP details consistent:
   - Name: Janine Standish Wellness, LLC
   - Address: 700 Godwin Avenue, Suite 230, Midland Park, NJ 07432
   - Phone: (201) 282-6720
4. Add backlinks from trusted local directories/professional listings.
5. Add social profile links in JSON-LD (`sameAs`) once available.

## Files
- `index.html`: Content + structure + SEO metadata + structured data
- `styles.css`: Visual system and responsive styles
- `script.js`: Mobile nav + section reveal behavior
- `logo-3.avif`: Primary logo asset used in the hero
- `headshot.avif`: Local headshot used in the hero
- `robots.txt`: Crawler directives
- `sitemap.xml`: Indexable URL list

## Maintenance notes
- Time-sensitive event copy should stay evergreen unless someone is actively updating dates.
- Canonical and Open Graph URLs in `index.html` should match the live domain.
- `robots.txt` and `sitemap.xml` should be updated if the domain changes.
