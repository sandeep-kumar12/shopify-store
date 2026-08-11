# MY SHAKE — Shopify Hero Section

Shopify section that matches the **MY SHAKE** sports-nutrition hero (split teal/lime bar, serif headline, pill CTA, slide dots).

## Files

| Path | Purpose |
|------|---------|
| `sections/myshake-hero.liquid` | Hero section (settings + slide blocks) |
| `templates/index.json` | Homepage preset using the hero |
| `layout/theme.liquid` | Minimal theme layout |

## Install in an existing theme

1. Copy `sections/myshake-hero.liquid` into your theme’s `sections/` folder.
2. In the theme editor: **Add section → MY SHAKE Hero**.
3. Add **Slide** blocks and upload a full-bleed background image (runners / athletes works best).
4. Edit headline, split-bar words, and CTA text per slide.

## Section settings

- Height (vh), overlay opacity, teal bar width
- Colors: lime accent, teal, light text
- Headline / “Live to Perform” font sizes
- Autoplay + slide dots

## Slide block fields

- Background image
- Top & bottom headline lines
- Meta lines inside the teal bar
- Words spanning the color split (`Live` / `to Perform`)
- CTA: prefix, highlight (`30% Off`), label, link, lightning badge toggle
