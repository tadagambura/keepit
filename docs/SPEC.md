# KeepIt: Spec

**Receipts, returns and warranties, never lost** · #22 of 33 · Wave 2: Recurring keepers · Used: Whenever you buy something · Harder · Revenue potential: Medium · Home & Household · Source: New (Claude)

## One-liner

Snap a receipt and KeepIt remembers the return window and warranty expiry, reminds you before they run out, and keeps everything searchable for when something breaks.

## Problem / audience

- **Who it's for:** Anyone who buys electronics, appliances or clothes and loses receipts.
- **The problem it solves:** Receipts fade and go missing, and return windows close before people act.
- **Example:** A user's headphones break at 11 months; KeepIt finds the receipt and shows a month of warranty left.

## MVP features (ship with only these)

1. Photo receipts with item, shop, price and date
2. Return-window and warranty-expiry reminders
3. Search by item or shop
4. Categories
5. Manual entry for online orders

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

Prices are starting points; test before committing.

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

## Animation and tone

**Calm.** Smooth, reassuring motion only: gentle ticks, numbers easing into place. No characters, jokes or drama.

- The receipt files itself into a folder


## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app (camera); backup needs storage.
- **Data:** On the device first; receipt photos are compressed. Cloud backup is a premium feature so storage costs are covered by the people who use it.
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
- [ ] Added to growth-engine as an app config
