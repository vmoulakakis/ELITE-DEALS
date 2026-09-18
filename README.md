# ELITE-DEALS

> **Architecture status (2026-09-18):** Front-end campaign/deal surface only. It must consume validated affiliate offers from `vmoulakakis/Socialmarket`; it must not become an independent product database, merchant authority, demand engine or tracking-link generator.

## Canonical contract

- Product / merchant / demand / AI-ranking truth: `vmoulakakis/Socialmarket`
- Only validated, active offers may be rendered.
- Preserve the exact canonical `tracking_url`.
- Do not expose affiliate credentials in browser code.
- Keep campaign presentation, animation and conversion UX local to this repository.
