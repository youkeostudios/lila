# Lila Studios logo library

This folder is derived from the client-supplied outlined master at `../logo.svg`. The supplied letterforms, masks, proportions and embedded play geometry remain unchanged.

## Lockup levels

### Primary lockup

Includes the Lila logo, “Studios” and “Drama, Generated”. Use for large identity moments, presentations, title cards and brand-guideline applications.

- `lila-primary-color-on-light.svg`
- `lila-primary-color-on-dark.svg`
- `lila-primary-black-on-light.svg`
- `lila-primary-white-on-dark.svg`

### Studios lockup

Includes the Lila logo and “Studios”, without the tagline. Use in credits, medium-size panels and placements where the tagline would become too small.

- `lila-studios-color-on-light.svg`
- `lila-studios-color-on-dark.svg`
- `lila-studios-black-on-light.svg`
- `lila-studios-white-on-dark.svg`

### Lila wordmark / compact logo

Includes the stylised Lila artwork only. Use in navigation, footers, video watermarks, compact branded controls and small-format placements.

- `lila-wordmark-color.svg` — preferred colour version; suitable on light or sufficiently dark neutral backgrounds.
- `lila-wordmark-black-on-light.svg`
- `lila-wordmark-white-on-dark.svg`

## Choosing a treatment

- **Colour on light:** preferred on white, off-white and very pale neutral backgrounds.
- **Colour on dark:** preferred on Lila’s cinematic black; supporting text is changed to accessible light tones.
- **Black on light:** one-colour fallback for print, embossing, stamps and restricted production.
- **White on dark:** reversed one-colour fallback for black and near-black surfaces.

The `lila-primary-lockup.svg`, `lila-studios-lockup.svg` and `lila-wordmark.svg` files remain as compatibility aliases from the first component pass. New implementation should use the explicit background-aware filenames above.

## Usage rules

- Preserve the SVG aspect ratio; never stretch, retype or redraw the artwork.
- Use each `-on-light` or `-on-dark` file only on its intended background family.
- Leave clear space around the mark and avoid borders, glow, shadows or decorative overlays.
- Prefer the primary lockup when every line remains legible, then step down to the Studios lockup or compact wordmark.
- Do not extract the play triangle as a standalone icon. It is structurally integrated into the final letterform in the approved master.
