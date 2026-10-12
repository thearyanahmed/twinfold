# Twinfold — Content & Social Plan (Brief / Instructions)

_Last updated 2026-07-26. This is the master brief for the journal + Facebook content project. Read this first._

## Goal
Build two streams of content for twinfold.co.uk:
1. **SEO journals** — 6 pillar articles (one per collection + cross-cutting guides) that rank and pull traffic to products, then get repackaged as Facebook posts.
2. **45 top-of-funnel Facebook posts** — 3/day for 15 days. Non-sales. Brand-building, inspiration/aesthetic-led, about notes, desk objects and analog living.

## Decisions locked (2026-07-26)
- **Journals:** ~6 pillar articles, organised by collection.
- **Facebook images:** minimal text-on-colour cards (no photos) on Twinfold's palette.
- **Scheduling:** Claude schedules via the browser (Meta Business Suite / Claude in Chrome).
- **45 posts lean:** mostly inspiration / aesthetic.

## Brand voice (non-negotiable)
Calm, warm minimalism. Few words, more space. Considered, tactile, quietly premium — the copy should feel like a well-made object. Founder-led, independent. Never novelty, never hype, never cute-for-cute's-sake.

## Marketing guardrails
- **Market Twinfold, never the supplier.** Never name Coffeenotes, Ogo Living, Girls Who Grind's wholesaler, Faire, "Minimum Design", etc. Use "our UK maker / a Dorset workshop / milled in Cumbria / pressed in France" style provenance only where true.
- **No "plastic-free" claims** anywhere.
- Material facts are fine ("recycled coffee-cup paper", "bio-composite wood", "made in France").
- The 45 posts are **not** sales posts — no discount codes, no "buy now". Product may appear as a quiet prop, not a pitch.

## Folder structure (this folder, sibling to theme-001)
```
content/
  01-instructions.md      <- this file
  02-findings.md          <- trend + influencer research
  03-journals/            <- the 6 pillar SEO articles (original posts)
  04-facebook/            <- FB post copy + a posting calendar
    images/               <- generated text-on-colour cards (PNG)
```

## The 6 pillar journals (working titles)
1. **Desk & Paper** — "Why we think better on paper" (notebooks, layflat, stitched, organiser pads).
2. **Objects** — "A calm desk, built from a few good objects" (pen holders, desk organisers).
3. **Brew & Sip** — "The slow cup: tea, coffee and the ritual of a pause" (infusers, teapots, coffee).
4. **The Calm Corner** — "Making a corner that helps you focus" (planters, candle holders, calm setup).
5. **Cross-cutting guide** — "The analog morning: a screen-free first hour."
6. **Cross-cutting guide** — "Buy less, keep longer: a small guide to considered stationery & sustainability."

Each journal: SEO title (<60 chars) + meta description (<155) + ~800–1200 words, keyword-led opening, H2 structure, natural internal links to relevant products/collections, one clear soft CTA at the end. No supplier names.

## Facebook image spec (text-on-colour cards)
- Square **1080×1080** (primary) for feed.
- Palette: cream `#FCFBF7` bg / ink `#2b2c33` text / muted green accent `#3f7a50`. Alternate a few cards on ink bg with cream text for variety.
- Type: **Hanken Grotesk** (headings/labels) + **Newsreader** (serif quotes/body).
- Layout: generous margins, one idea per card, small "twinfold" wordmark bottom. No clutter.
- Built as HTML/CSS rendered to PNG (headless Chromium) so they're consistent and re-generatable.

## The 45 posts (3/day × 15 days)
- Lean: inspiration/aesthetic, with a light thread of the analog-revival + "quiet intellectual" mood (see findings).
- Rough daily rhythm: 1 quiet quote/mantra, 1 gentle tip or "glimmer" prompt, 1 mood/aesthetic or community prompt.
- Each post = short caption (calm voice) + a text-on-colour card + 3–6 on-brand hashtags.
- Dated calendar in `04-facebook/` mapping post → day → time.

## Order of work
1. Instructions (this) → 2. Findings → 3. Journals → 4. FB posts + images → 5. Schedule via browser.

## Scheduling notes
- Post via Meta Business Suite's native scheduler, driven in-browser.
- Suggested slots (UK): ~08:30, ~13:00, ~19:30 (revisit against page insights once live).
