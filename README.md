# Mercedes V Class Hire — website

A single-page static site advertising the Mercedes-Benz V-Class Turo listing. Every booking CTA links out to Turo — this site has no independent booking system.

## Files

- `index.html` — the actual site. Plain HTML/CSS/JS, no build step, no dependencies.
- `images/` — the car photos used on the site. See `images/README.md` for which file is used where.
- `index-preview.html` — **not for hosting.** A version with photos embedded inline, only used for previewing in Claude/Cowork chat. Ignore this file when deploying.

## Deploying

This is a static site — no build step. Point any static host (Cloudflare Pages, Netlify, Vercel, GitHub Pages) at this repo with:
- Build command: *(none)*
- Output directory: `/` (repo root)

## Updating content

If Turo listing details change (price, reviews, trip count), those need to be updated manually in `index.html` — there's no live sync with Turo.
