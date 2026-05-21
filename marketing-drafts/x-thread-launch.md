# X (Twitter) — Pulse source launch thread

**Status:** draft, not posted
**Target audience:** Paddle sellers + indie iOS devs + "I want a private
revenue dashboard" makers
**Goal:** sell the source bundle ($19) — App Store app is just legitimacy
**Posting account:** @trungdq88
**Cadence:** main tweet → wait for 30+ likes → drop the source-sale reply
**When to post:** weekday evening ICT (= morning PT, dev-Twitter prime time)

---

## Main tweet (with a 5-10s screen recording or the existing revenue.png)

```
I built a private revenue dashboard for Paddle that lives entirely on
my iPhone.

Today / 7-day / 30-day vs the prior period. Transactions searchable.
Home-screen widget showing today's revenue. Zero servers. The Paddle
API key never leaves the device.

It's on the App Store, and I sell the source.

pulserevenue.app 💰
```

**Media:** the existing `shots/revenue.png` (now 101KB after the perf
cycle) or a short screen recording showing the today→7d→30d card flip.
The widget on home screen also makes a great demo.

---

## Reply 1 (the "why I built it" thread)

```
Why I built this instead of opening Paddle's web dashboard:

1. The Paddle web app is great for ops, but I check revenue 4x a day
   and I don't want to log into a web tool every time.
2. Stripe has dozens of native iOS clients. Paddle has ~zero good ones.
   That's a hole.
3. I wanted my Paddle API key in the iOS Keychain — not in a cloud
   service's database. The whole app is BYOK with no proxy server.
4. The widget specifically. Glanceable revenue on the home screen is
   the thing I wanted and couldn't find.

The cross-period comparison ("today vs same-time-yesterday-7d", not
just "today total") is what makes it actually useful — raw numbers
without a baseline are noise.
```

---

## Reply 2 (the source pitch — the conversion ask)

```
I'm also selling the full Xcode source as a one-time $19 bundle.

- Full Swift source (SwiftUI + WidgetKit + Paddle Billing API client)
- The cross-period comparison logic (works for any one-time/sub product)
- AGENTS.md so an AI agent can orient itself instantly — fork, rebrand,
  ship your own under your branding
- 7-day money-back guarantee
- Personal + commercial license

If you sell on Paddle and want your own private revenue dashboard
on your home screen — or if you're a dev who wants a known-working
Paddle API client to start from:

pulserevenue.app (scroll to "Inside the source")
```

---

## Alt main (if first stalls)

```
Paddle's web dashboard is fine. But I check revenue 4x a day and
don't want a browser tab open.

So I built Pulse: a native iOS app + home-screen widget showing
today/7d/30d Paddle revenue, with transactions searchable. The
API key never leaves the device. Zero servers.

App Store + source code: pulserevenue.app
```

---

## Notes for future Tony

- Lead with the dashboard image (or the widget specifically — that's
  the most novel piece). "App on phone showing graph" is a saturated
  visual genre; the home-screen widget breaks pattern.
- DON'T mention the current sales count or revenue total in the post.
  $38 is "small dollar-amount" theater — better to lead on engineering
  depth.
- If someone asks "why $19", say "to weed out tire-kickers — at $5 you
  get refund requests; at $19 you get committed devs." Don't say "to
  hit my $1k goal" — that signals desperation.
- This is a Paddle-specific thread. DON'T cross-pitch Skyline in the
  replies — let each app stand alone.
