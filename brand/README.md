# How Buildings Work brand files

Tagline: KNOW YOUR HOUSE. Colours: cream #F3EFE4 (ground), ink #25262A (lettering, interior), red #C4362C (the ring only).

**Rule: edit the SVG, never regenerate the mark with an image model.** The SVGs are the masters; text is outlined (Architects Daughter), no external fonts or images.

| File | Use on the site |
|---|---|
| `mark-compact.svg` | Header mark (40 px, links to `/`), SVG favicon. |
| `mark-full.svg` | Full mark with leader and tag. About/print use; not on pages yet. |
| `lockup-horizontal.svg` | Footer lockup (220 px wide, above the footer lines). Source of `og-image.png`. |
| `lockup-stacked.svg` | Home page hero mark above the tools list. |
| `favicon-16.png`, `favicon-32.png` | `<link rel="icon">` PNGs. |
| `favicon-512.png` | `apple-touch-icon`. |
| `og-image.png` | 1200x630 share card: cream, horizontal lockup centred. Used for `og:image` / `twitter:image` (absolute URL). |

Link these with root paths (`/brand/...`). To change `og-image.png`, edit `lockup-horizontal.svg` and re-render it to 1200x630 in Chromium; do not redraw it.
