# Local implementation notes

## Status

The prior Art Déco Luxe system (gold/copper palette, Playfair Display, Inter, and decorative geometry) is **SUPERSEDED** for this institutional site.

The institutional authority is **Core & Patch Identity 2026 — V1.0** and the P03 Brand System. This repository does not duplicate those rules.

## Repository bridge

- Identity assets live in `client/public/brand/identity-v1.0`.
- Global tokens use the `--cp-` prefix in `client/src/index.css`.
- The existing Tailwind 4, Radix/shadcn components, ThemeProvider, routing, and responsive behavior remain in use.
- Legacy class names such as `.btn-gold` and `.art-deco-card` remain temporarily for component compatibility; their visual treatment is institutional and neutral.
- The existing favicon remains unchanged. `FAVICON_FINAL_PENDING`.

For canonical brand decisions, use the released identity package and P03 documentation rather than this local note.
