# MoveDay: Spec

**The moving-house checklist that runs itself** · #33 of 33 · Wave 3: Seasonal and episodic · Used: Once per move · Very easy · Revenue potential: Medium · Home & Household · Source: New (Claude)

## One-liner

Enter your moving date and MoveDay gives you a week-by-week timeline (book removals, give notice, pack room by room), a UK change-of-address checklist (council tax, DVLA, GP, bank, TV licence, utilities) and a box tracker.

## Problem / audience

- **Who it's for:** Renters and buyers moving home, especially first-time movers.
- **The problem it solves:** Moving has dozens of deadlines and admin tasks, and things get forgotten: redirecting post, council tax, meter readings.
- **Example:** A renter moving in six weeks follows the timeline, ticks off giving notice and booking a van, and on the day gets prompted to take meter readings.

## MVP features (ship with only these)

1. Countdown to moving day with a week-by-week task timeline
2. UK change-of-address checklist
3. Room-by-room packing checklist
4. Box tracker: what's in which box and which room it goes to
5. Moving-day prompts: meter readings, keys, photos

## Not in MVP

- Share the move with a partner
- Removals, broadband and energy comparisons (affiliate), clearly labelled
- First-week-in-your-new-home checklist

## Monetisation

| Model | Detail |
|---|---|
| Free | Timeline and checklists, with ads |
| Premium | £3.99 one-off per move: box tracker, sharing, no ads |
| Affiliate | Removals, broadband, energy and insurance comparisons |

Prices are starting points; test before committing.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | This week's timeline tasks |
| Tiny win | Tick a task |
| Progress | Countdown and % of the move done |
| Share | 'Moved in!' card |
| Next step | After the move: new-home setup, then hand over to Reset and SubSpot |
| Cadence | Daily for the 6–8 weeks of a move |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app; the checklist also works as an SEO web page.
- **Data:** On the device only.
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Moving checklists; Renting tips; Packing hacks; First home
- **Shareable output:** 'Moved in!' card

## Risks

Disposable by nature: people delete it after the move, which is why it's last in the build order. Worth building only as a cheap ad and affiliate earner (many people move every year). The UK checklist must be kept accurate.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to growth-engine as an app config
