# Harbour Light Café brand

Direction: **Harbour Pulse**. A sleek, modern identity that captures the energetic rhythm of Whitby harbour through clean lines and vibrant coastal accents.

Tagline: Whitby's Modern Coffee Stop

## Colour

Use only these tokens, from `tokens.css`:

| Token | Value |
| --- | --- |
| `--ink` | `#1a1a1a` |
| `--paper` | `#f5f5f5` |
| `--accent` | `#d43500` |
| `--accent-ink` | `#ffffff` |
| `--muted` | `#555555` |

Measured contrast (WCAG 2.x), each with headroom over the 4.5:1 minimum:

| Pair | Contrast | Required |
| --- | --- | --- |
| ink on paper | 15.96:1 | 7.0:1 |
| accent-ink on accent | 4.87:1 | 4.8:1 |
| muted on paper | 6.84:1 | 4.8:1 |

## Type

- Display: `"Helvetica Neue", Arial, system-ui, sans-serif`
- Body: `"Segoe UI", "Gill Sans", "Trebuchet MS", system-ui, sans-serif`

System font stacks only: the site loads no external fonts.

## Voice

Sleek, energetic, modern, inviting.

- Use: Grab a flat white; Catch the light; Harbour vibes
- Avoid: Rustic; Timeless; Traditional

## Logo

| File | Use |
| --- | --- |
| `logo/mark.svg` | the mark on paper; also the site's favicon |
| `logo/mark-on-dark.svg` | the mark on an ink background |
| `logo/mark-mono.svg` | one colour, for stamps and small sizes |
| `logo/lockup.svg` | the mark with the name |
| `social/og-card.svg` | the 1200×630 social card |

Keep clear space of a quarter of the mark's width around it. Do not recolour,
stretch or add effects to the mark.

## Contrast adjustments

Trusted code moved these colours in lightness only, to the
nearest shade that meets its contrast target:

- accent #e63900 → #d43500 (accent-ink on accent, 4.8:1)
