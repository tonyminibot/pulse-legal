# Indie Hackers — milestone / launch post

**Status:** draft, not posted
**Posting account:** Tony's IH account
**Best section to post in:** Launchpad (now, pre-sales) OR Milestones
(once cumulative source-bundle revenue clears $100)
**When to post:** Tuesday morning ET

---

## Title

```
A BYOK iOS app for Paddle revenue — selling the source for $19
```

---

## Body

```
Hey indie hackers 👋

I just launched **Pulse** — a private iOS dashboard for Paddle
revenue. Native SwiftUI app, BYOK, lives entirely on your phone (no
proxy server, your API key stays in the iOS Keychain).

App Store: https://apps.apple.com/app/id6770415388

What I'm doing differently for monetization:

The App Store version is free (no IAP, no subscription). The actual
revenue model is **selling the full Xcode source** as a one-time $19
bundle on the landing page.

Reasoning (which is the same as my Skyline app, separately):

- The kind of person who installs a niche Paddle dashboard is rarely
  going to pay $5/mo for one. Subscription friction kills installs.
- But the kind of developer who sells on Paddle and wants a known-
  working Paddle API client to fork from — that person will trade
  $19 for ~6 hours of integration work without thinking.
- "Free app, paid source" inverts the usual "freemium" trap where
  the free tier permanently undercuts paid. Here the free tier is
  the marketing channel for the paid tier.

What's in the source bundle:
- Full Xcode project (xcodegen-managed Swift source)
- The Paddle Billing API client (rate-limited, retries, decoded models)
- Cross-period comparison logic (today vs same-time-7d-prior, not just
  raw totals — what makes a dashboard actually useful)
- WidgetKit home-screen widget with background refresh
- AGENTS.md so an AI agent can orient itself in seconds
- Personal + commercial license — fork + rebrand + ship your own
- 7-day money-back guarantee via Polar

Landing: https://pulserevenue.app

Open to feedback on:
- Should I A/B the price between $19 and $29? The bundle is built
  to a quality where $29 feels defensible, but I haven't tested.
- Are there other "private dashboard" niches you'd buy a source
  bundle for? (Stripe seems obvious; what else?)

Happy to compare notes on Paddle's API quirks, the BYOK + Keychain
pattern, or how the cross-period math works.
```

---

## Notes / playbook

- The IH framing emphasizes monetization model > technical depth
  (opposite of HN). The audience here is "what should I build" /
  "what should I charge" makers, not "how did you implement X" devs.
- Constrained question at the end ("should I A/B $19 vs $29?") drives
  more replies than open-ended "what do you think?".
- DON'T cross-link Skyline. One product per post.
- DON'T mention the current revenue ($38 / $1,000). The IH crowd
  reads bare numbers as the floor, not the ceiling — $38 reads
  "didn't work" even if it's day 3. Wait for the milestone post.
