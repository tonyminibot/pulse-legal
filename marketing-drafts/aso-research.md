# Pulse — ASO research + keyword proposals

**Status:** research doc, not applied yet
**When to apply:** next App Store version after 1.0.2 (the localization
 release) lands. Realistic window: when shipping v1.0.3.

---

## Current en-US ASO state (as of 2026-05-23)

- **App name:** "Pulse: Paddle Revenue" (21/30 chars) — strong, brand + niche
- **Subtitle:** "Combined revenue analytics" (26/30 chars) — solid
- **Keywords field (93/100 chars):**
  ```
  paddle,revenue,analytics,saas,mrr,sales,transactions,dashboard,income,merchant,finance,widget
  ```
- **Promotional text:** ok, no changes needed

## Issues / opportunities

1. **No "billing" or "stripe"** — but those are wrong-intent
   (Stripe-buyer ≠ Paddle-buyer). Don't add.
2. **No "subscription"** — Paddle is heavily used by SaaS folks who
   think in subscription terms. "subscription" + "MRR" pair well.
3. **"finance"** is broad and dilutive — probably not driving qualified
   installs. Could repurpose those 8 chars.
4. **"widget"** is good. Pulse has real iOS widgets; ranking for this
   pulls Home-Screen-buyers.
5. **"sales"** is generic but high-volume. Probably worth keeping.
6. **"merchant"** is okay but redundant with "paddle". Could drop.
7. **Missing**: "ARR" (annual recurring rev), "ecommerce", "kpi",
   "metrics", "indie".

## Proposed keyword field (97/100 chars)

```
paddle,revenue,analytics,mrr,arr,subscription,sales,transactions,dashboard,kpi,metrics,widget,indie
```

Char-count: 97. Leaves 3 chars headroom.

Changes:
- Dropped: `saas` (redundant with arr/mrr/subscription), `income`,
  `merchant`, `finance` (low intent)
- Added: `arr`, `subscription`, `kpi`, `metrics`, `indie`

## Subtitle

Current "Combined revenue analytics" is good but could be sharper.

Alternative options (all ≤30 chars):

A. **"Combined revenue analytics"** (26 — current)
B. **"All your Paddle revenue, live"** (29)
C. **"Paddle revenue on your phone"** (28)
D. **"MRR & sales — every account"** (27)

Recommendation: **B — "All your Paddle revenue, live"**. Pairs better
with the marketing screenshot caption ("All your Paddle revenue").
Tighter, more concrete.

## Promo text

Current promo "See your Paddle revenue the moment you open your phone."
is good. Keep.

## Action items for next version (v1.0.3)

- [ ] Bump version
- [ ] Update en-US keywords + subtitle via ASC REST
- [ ] Re-translate keywords + subtitle for the 14 new locales
- [ ] Ship a new build (no functional changes; metadata-only). Or
      piggyback on next feature work.
- [ ] Submit for review
