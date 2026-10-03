# LONGevity LOBsters · genesis MVP

The genesis MVP design package: information architecture, design system
specification, and the full product surface — a seven-screen mobile flow
plus the modular desktop dashboard. Bilingual (EN / ไทย).

## View it

- **Board** — `index.html` lays out all ten boards in review order.
- **Flow** — start at [`pages/03-1-the-gift.html`](pages/03-1-the-gift.html)
  and walk the app as a user would: the gift → the gift is yours → join →
  intake → your shell → bring your numbers → me. In-flow links are wired
  between screens.

Any static file server works (or just open the files — no build step, no
CDN calls; React, ReactDOM, the app runtime, and all webfonts are vendored
locally under `assets/`).

## Boards

| # | Board | File |
|---|-------|------|
| 1 | Information architecture & sitemap | [`pages/01-sitemap.html`](pages/01-sitemap.html) |
| 2 | Design system specification | [`pages/02-design-system.html`](pages/02-design-system.html) |
| 3.1 | The gift (ad lands here) | [`pages/03-1-the-gift.html`](pages/03-1-the-gift.html) |
| 3.2 | The gift is yours | [`pages/03-2-the-gift-is-yours.html`](pages/03-2-the-gift-is-yours.html) |
| 3.3 | Join · LINE or your own key | [`pages/03-3-join.html`](pages/03-3-join.html) |
| 3.4 | Intake · one question at a time | [`pages/03-4-intake.html`](pages/03-4-intake.html) |
| 3.5 | Your shell · your data, your keys | [`pages/03-5-your-shell.html`](pages/03-5-your-shell.html) |
| 3.6 | Bring your numbers | [`pages/03-6-bring-your-numbers.html`](pages/03-6-bring-your-numbers.html) |
| 3.7 | Me · the telemetry dashboard | [`pages/03-7-me-telemetry.html`](pages/03-7-me-telemetry.html) |
| 4 | Me on desktop · modular cards | [`pages/04-me-desktop.html`](pages/04-me-desktop.html) |
| 5 | Your hub · anti-aging, endometriosis, gym & aerobic — one home | [`pages/05-your-hub.html`](pages/05-your-hub.html) |
| 6 | The coach's morning · evaluate the roster's wearables in 5 minutes | [`pages/06-coach-console.html`](pages/06-coach-console.html) |
| 7 | The return · income & free time the stack gives back | [`pages/07-the-return.html`](pages/07-the-return.html) |

## The daily-use layer (screens 5–7)

The seven screens above the fold are the funnel; screens 5–7 are what
people **open every day** — built in the same design language, with a
working EN/ไทย toggle (persisted), local Thai fonts, and real
on-device logging:

- **Your hub** — the user's own center: the clock (anti-aging telemetry:
  bio-age, HRV, sleep debt), the cycle (endometriosis: phase strip,
  30-second symptom quick-log with pain + triggers, stored on-device,
  pattern insights, and a standing care note that logging prepares you
  for your doctor — it never replaces them), and the engine
  (recovery-adjusted gym & aerobic plan).
- **The coach's morning** — the practitioner side: the roster's wearables
  distilled into ready / watch / rest flags, per-client HRV-vs-baseline,
  sleep, cycle context and adherence dots, private notes, and
  suggested LINE nudges with one-tap copy — the 5-minute daily scan.
- **The return** — the sustainability surface: funnel numbers
  (gift → LINE → intake → roster), recurring income, hours reclaimed vs
  1:1 coaching, and the hive path (clients who molt into coaches).

## Provenance

Unpacked from the self-contained single-file artifact
(`original/longevity-lobsters-genesis-mvp.html`, kept as the record — it
renders standalone from a double-click). The pages here are the same bytes
laid out as plain static files: per-page manifests were gunzipped, assets
were content-hash deduplicated into `assets/`, and the artifact's internal
`J*.dc.html` page links were rewired to the real files so the flow is
navigable.

## Campaign — Bee's influencer launch kit

First client: **Bee** (Bangkok). Her full socials messaging package lives
in [`campaign/`](campaign/README.md) — funnel map, TikTok/IG/FB/X copy
deck (EN/ไทย), LINE Official Account flows and 14-day drip, launch
calendar, and Thailand compliance/PDPA notes. One-line strategy: give the
gift first, and let the morning after the rave do the selling.

## Estate

beeHive biomass · beehive-biomass org.
