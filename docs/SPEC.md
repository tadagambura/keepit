# KeepIt: Spec

**Buy smarter, keep the receipts** · #12 of 15 · Wave 2: Recurring keepers · Used: Whenever you buy something · Harder · Revenue potential: Medium · Home & Household · Source: Perplexity + ChatGPT (absorbs BuyOrBye)

## One-liner

The purchase lifecycle in one app. Before you buy: cool-off wishlist ('still want it in 7 days?'), unit-price and cost-per-use maths. After you buy: snap the receipt, and KeepIt remembers return windows and warranty expiry (UK Consumer Rights Act: up to 6 years to claim), and tracks cost-per-use as you use things.

## Problem / audience

- **Who it's for:** Anyone who buys electronics, appliances or clothes and loses receipts.
- **The problem it solves:** Receipts fade and go missing, and return windows close before people act.
- **Example:** A user's headphones break at 11 months; KeepIt finds the receipt and shows a month of warranty left.

## MVP features (ship with only these)

1. Cool-off wishlist with 'still want it?' check-ins and a saved-by-not-buying total
2. Price-per-unit and cost-per-use calculators (also free SEO web pages)
3. Photo receipts with return-window and warranty reminders
4. Consumer-rights clock (UK): what you can still claim and for how long
5. Cost-per-use tracking for things you own

## Not in MVP

- Read receipt text automatically, on the device
- Cloud backup (premium)
- Manuals and serial numbers

## Monetisation

| Model | Detail |
|---|---|
| Free | Up to 20 receipts, with ads |
| Premium | £1.99/month: unlimited, backup, auto-read |
| Ads | Light |

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Return and warranty reminders |
| Tiny win | Snap a receipt |
| Progress | Money protected |
| Share | Low |
| Next step | Monthly 'anything to return?' check |
| Cadence | Weekly/event-driven |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone: five signature animations

**Calm.** Gentle, kind humour and smooth motion: a stickman yawning after a shift, a fly escaping an empty pocket. No drama, nothing that adds stress.

- Receipt snapped: it files itself into a folder and salutes
- Return window closing: a tiny calendar taps its watch
- Warranty saves the day: the receipt does a superhero landing
- Search: the magnifying glass sniffs around like a bloodhound
- Monthly tidy: the folder closes and takes a bow


## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app (camera); backup needs storage.
- **Data:** On the device first; receipt photos are compressed. Cloud backup is a premium feature so storage costs are covered by the people who use it.
- **Backend:** None for the free version: everything lives on the phone. Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Consumer rights (general info); Return windows; Warranty tips
- **Shareable output:** Low

## Risks

Camera, image storage and backup costs. Consumer-rights content must be general and accurate.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to the Growth & Maintenance Engine as an app config
