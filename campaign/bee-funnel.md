# The funnel — how Bee's channels become lobsters

## 1. The shape

The product already defines seven screens. The funnel maps onto them; Bee
never has to invent a step, only feed the top and keep the middle warm.

```
            TikTok / Reels          ← reach: the night, the molt, the gift tease
                 │
IG Stories (link sticker) ─ FB post ─ X            ← curiosity: tap through
                 │
        ┌────────▼──────────────────────────┐
        │ 3.1 THE GIFT  (ad lands here)     │  ← every link lands here
        │ "no account, no email, nothing    │
        │  to buy"                          │
        └────────┬──────────────────────────┘
                 │  3.2 the gift is yours (claim)
                 │  3.3 join · LINE or your own key
        ┌────────▼──────────────────────────┐
        │ LINE OA                            │  ← the spine (Thailand)
        │ welcome → gift → intake nudges     │
        └────────┬──────────────────────────┘
                 │  3.4 intake (one question at a time)
                 │  3.5 your shell (your data, your keys)
                 │  3.6 bring your numbers (wearables)
        ┌────────▼──────────────────────────┐
        │ 3.7 ME — telemetry dashboard       │  ← habit + retention
        └───────────────────────────────────┘
```

**The rule that keeps it honest:** nothing in Bee's content asks for money
or an account. Every CTA is *take the gift*. Claiming the gift leads to
LINE; LINE walks the rest. If a piece of content can't end in the gift,
it's brand content, not funnel content — fine, but label it so.

## 2. Platform jobs (don't cross the streams)

| Platform | Job in the funnel | Metric that matters | CTA form |
|---|---|---|---|
| **TikTok** | Reach + the wedge ("the morning after") | profile visits → bio link clicks | "gift in bio" |
| **IG Reels** | Same TikTok content, recycled | saves + shares (algo fuel) | "gift in bio" |
| **IG Stories** | The actual click machine (link stickers) | link sticker taps | direct link → 3.1 |
| **IG grid + bio** | Credibility; the bio is the toll booth | bio link clicks | link-in-bio → 3.1 |
| **Facebook** | Events scene, slightly older crowd, shareability | post link clicks | link → 3.1 |
| **X** | Data-sovereignty niche, expat/EN crowd | link clicks | link → 3.1 |
| **LINE OA** | Conversion + retention spine in Thailand | friend adds → intake completes → broadcasts opened | rich menu + broadcasts |
| **Paid ads** | Only amplifying what already works organically | cost per gift claim | ad → 3.1 (it's literally the ad landing page) |

TikTok and Reels are the same content; Stories, LINE and Facebook are
Bangkok-specific leverage. X is optional but fits the "your keys" angle.

## 3. The golden window

The gift's first artifact is **After the rave** — the post-event recovery
protocol. So the calendar breathes with Bangkok's event weekends:

- **T-minus (week before):** pure night/fashion/lineup content, gift
  teased once or twice. Build the audience that will feel terrible Sunday.
- **Sunday morning after (the golden window):** the heaviest CTA push of
  the entire cycle. Everyone is scrolling in bed feeling like a wet paper
  towel. Post the molt content *then* — 09:00–11:00 ICT.
- **Molt week (+1 to +7):** the 72-hour protocol plays out; LINE carries
  the daily beats; Bee posts the "day 3 check-in" content.
- **Numbers week (+7 to +14):** wearables content, dashboard screenshots,
  "your data, your keys" — the long-game angle.

Then the cycle repeats with the next event. The funnel is a drumbeat, not
a one-shot.

## 4. Links & attribution (works today, no product changes)

The static build doesn't run analytics yet — that's fine; don't wait.

- Every placement gets a distinct `?src=` tag:
  `?src=tt-bio`, `?src=ig-story-gift01`, `?src=fb-post-rave`,
  `?src=line-welcome`, `?src=ad-a-en` …
- Use **one short link per placement** from any shortener Bee controls
  (bit.ly, self-hosted, whatever) so each has a live click counter.
- LINE tells you friend **source** (QR vs link added) — use a different
  add-friend link per surface (bio vs stories vs FB).
- The conversion events we care about, in order:
  1. link click (shortener)
  2. gift claimed (screen 3.2 reached — needs product instrumentation
     later; for now "claimed" ≈ LINE friend add)
  3. LINE friend added (measured today)
  4. intake completed (screen 3.4 done — later)
  5. numbers connected (3.6 — later)
  6. dashboard habit: weekly returning user (3.7 — later)

When the product grows real analytics, the `?src=` convention rolls
straight into UTM discipline. Until then the shorteners + LINE source
report give us 80% of the picture.

## 5. Content pillars (Bee's four lanes)

1. **The night** — event fashion, lineup hype, dancing. Pure reach; no CTA
   except "come find me at the front left of the stage."
2. **The morning after** — hydration fails, sunglasses indoors, the molt
   wedge. The funnel's favorite; always ends in the gift.
3. **The long game** — sleep debt, HRV, what your wearable is trying to
   tell you, data sovereignty. Slower, saves-and-shares content; ends in
   the gift framed as "start with the gift."
4. **The shell** — "your data, your keys" as identity, not tech. Bangkok
   angle: PDPA made data a dinner-table topic; Bee's audience already
   distrusts apps that hoard. This pillar differentiates; it never sells.

Ratio through a normal week: 4 night / 3 morning-after / 2 long-game /
1 shell. During the golden window: morning-after takes over.
