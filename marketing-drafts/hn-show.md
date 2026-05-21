# Hacker News — Show HN post

**Status:** draft, not posted
**Goal:** front-page discussion → traffic → source-bundle conversion
**Posting account:** Tony's own HN
**When to post:** Tuesday or Wednesday, **08:00 UTC** — the canonical HN
prime window. NEVER Friday afternoon or weekends.
**Pre-post:** flownmap.com loads in <1s, Polar checkout works.

---

## Title (under 80 chars)

```
Show HN: Pulse – a native iOS dashboard for Paddle revenue
```

(Alt if the above feels too marketing-y: `Show HN: A BYOK iOS app for
your Paddle revenue, on-device`)

---

## URL field

```
https://pulserevenue.app
```

---

## First comment (post immediately — HN convention)

```
Author here. Why this exists instead of being a wrapper for Paddle's
web dashboard:

I sell on Paddle and was checking the web dashboard 4-5 times a day on
mobile. The web app is competent but slow on a phone, requires logging
in, and doesn't give you a glanceable view. I wanted the Stripe-Dashboard-
for-iOS equivalent for Paddle. That didn't exist.

A few things that might be interesting to the HN crowd:

1. BYOK + no servers. The Paddle Billing API key lives in the iOS
   Keychain. The app talks directly to api.paddle.com from the device.
   No proxy, no cloud function, no "sign up with an account". This is
   the architecture I want all my financial tools to have but rarely
   see anyone ship.

2. Cross-period comparison logic. Raw revenue numbers ("today: $X")
   are noise without baseline. Pulse shows "today vs same-time-
   yesterday-7d" (i.e., same elapsed minutes from this morning,
   averaged over the prior 7 weekdays). It's a 30-line function but
   it's the difference between "is this number good or bad?" and
   actually knowing.

3. The home-screen widget. This is the actual reason I built the
   whole app. Glanceable revenue without unlocking the phone is the
   workflow I wanted. WidgetKit pulls fresh data via a background
   refresh that respects the Paddle API rate limit.

4. SwiftUI + Swift Charts native — I avoided every "build a web app
   in a WebView" shortcut. The transactions list is a stock SwiftUI
   List with searchable() because that's the right primitive.

I also sell the full Xcode source as a one-time $19 bundle for folks
who want a known-working Paddle API client to fork from. Personal +
commercial license, AGENTS.md included so AI coding agents get
oriented in seconds. Bundle link is on the landing page.

Happy to answer questions about the Paddle API integration, the
cross-period math, or the widget background-refresh specifically.
```

---

## Notes / playbook

- Same as Skyline HN post — no marketing adjectives in the title,
  stay in the comments for the first 2h, acknowledge alternatives
  by name (Baremetrics, ChartMogul) without trashing them.
- If someone asks about Stripe support, say "next on the list if
  there's demand — current focus is making the Paddle version really
  good". DON'T say "yes coming next week" if it's not true.
- This post and the Skyline Show HN should NOT go up the same week.
  HN penalizes the same poster's repeated front-page attempts.
- Don't link the buy URL in the comment body. Landing page does
  the conversion.
