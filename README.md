# Maktura design mockups · public CDN

Screenshots of the Maktura design mockups referenced in [mrdombie/social-hub](https://github.com/mrdombie/social-hub) GitHub issues.

This repo exists so the dev-AIs claiming UI tickets see the visual targets inline in issue bodies — not as file paths they'd have to open separately. Per the rule [`feedback_no_orphan_features.md`](../social-hub/blob/develop/...), every Maktura ticket with a mockup gets PNG screenshots embedded.

PNGs render via `https://raw.githubusercontent.com/mrdombie/maktura-mockups/main/<path>` URLs.

## Folders

- `persona-update-2026-05-24/` — mockups for [#2458 EPIC: Persona Update](https://github.com/mrdombie/social-hub/issues/2458)
- `imprint-2026-05-24/` — mockups for [#2458 Phase 3 Voice DNA](https://github.com/mrdombie/social-hub/issues/2458) + [#2478 Imprint marketing tool](https://github.com/mrdombie/social-hub/issues/2478)

## How mockups land here (BD-mode workflow)

1. Mockup HTML designed at `~/Documents/maktura-design/<feature>/<file>.html`
2. Chrome headless renders each HTML to PNG at 1440×2400
3. PNG committed to this repo at `<feature>/<file>.png`
4. Raw URL embedded in the GH issue body as inline `![Caption](https://raw.githubusercontent.com/...)`

Automation: see [INTERVENTION A · #2488](https://github.com/mrdombie/social-hub/issues/2488).
