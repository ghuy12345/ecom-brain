---
title: "Meta Ad Metrics Framework - Part 2"
topic: "07 Meta Ads"
stage: beginner
tags: [meta-ads, ad-metrics, ctr, landing-page-views, add-to-cart, diagnostics, seba-framework]
summary: "Part 2 of a Meta ad metrics framework: delivery efficiency, the five click types, four CTRs, landing page view rate, add-to-cart rate, a diagnostic playbook and a custom-metric setup checklist."
---
# Meta Ad Metrics Framework - Part 2

Framework by Josh Omosebi, Seba Agency.

Continues [[Meta Ad Metrics Framework - Part 1]], which covers the funnel map, formulas, benchmarks, frequency, CPM, hook rate and hold rate.

## Delivery efficiency rate

One quick sanity figure for a video's combined opening and retention strength: the two rates multiplied together.

**Formula:** (3-second plays ÷ impressions) × (ThruPlays ÷ 3-second plays). Because the 3-second plays divide out, the custom metric you enter is simply **ThruPlays ÷ Impressions**. Note that ThruPlays ÷ 3-second plays is the hold rate, which is a different thing.

| Hook | Hold | Reading |
|---|---|---|
| Low | High | Strong middle, but the opening loses people |
| High | Low | Grabs attention, then loses it |
| High | High | Strong throughout |
| Low | Low | Obvious at a glance |

## Clicks

Clicks matter more than they look. Of the five types, only one gives an honest count.

1. **Clicks (all):** any interaction with the ad, including profile taps and "see more", whether or not anyone reaches your site.
2. **Link clicks:** taps on elements that go somewhere, such as the link or profile image. Note that "see more" is counted only in clicks (all).
3. **Outbound clicks:** taps that leave Meta for your landing page, product page or other site.
4. **Unique link clicks** (each person counted once).
5. **Unique outbound clicks** (each person counted once).

**Unique versus total:** totals count every tap, so one person tapping five times is five; unique counts that person once. Totals behave like impressions, uniques like reach.

**Use unique outbound clicks** to know how many people actually reached your page.

## CTR (click-through rate)

Ordered from most generous to most demanding, the four are **CTR, Unique CTR, Outbound CTR and Unique outbound CTR** (formulas in Part 1).

- Campaigns aimed at followers, reach or staying on the platform: use unique CTR.
- Stores and anything that sends traffic away from Meta: use unique outbound CTR, since what matters is how many separate people clicked through.
- Plain CTR runs inflated, so don't rely on it if you spend daily.

Treat a headline CTR with suspicion; the number that counts is unique outbound CTR.

## Landing page view rate

Already available in Meta: the share of people who clicked and then reached your fully loaded page. Plenty drop out in between.

| Rate | Verdict |
|---|---|
| 90%+ | The goal |
| 80% | Strong |
| 70% | Acceptable |
| <70% | Worrying |
| <60% | Serious trouble |

Many accounts sit at 60 to 70%. The higher your spend, the more that gap costs you in wasted clicks.

**Causes:** broken redirects, tracking faults, the browser not opening, ad blockers, poor connections, and above all slow page loads.

**Fixes for speed:** lazy loading, compressed images and standard site-speed work.

## Add-to-cart rate

The share of visitors who landed and added to cart.

**Formula:** the number of adds to cart ÷ landing page views. Divide by page views instead of clicks, since only people who really viewed the offer had the chance to add it.

| Rate | Verdict |
|---|---|
| <5% | Slightly worrying (varies by industry) |
| 5–10% | Healthy |
| >10% | Very strong |

## Diagnosis playbook: finding the break

Start at the top and repair the earliest step that fails.

| Symptom | Likely cause | Fix |
|---|---|---|
| CPA and frequency rising together | Creative fatigue | New or refreshed concept |
| High CPMs | Competition, price, weak rankings, fatigue, overlap | Ads that talk to the customer; check rankings |
| High quality, low conversion ranking | The ad promises something the page fails to deliver | Match the page, offer and price to what the ad says |
| Hook rate under 25% | Weak opening | Rework words, visuals and on-screen text |
| High hook rate, poor conversions | Hook attracts the wrong people | Make it filter |
| Hold rate under 30% | Post-hook section loses viewers | Make it relevant to who the hook called |
| Low delivery efficiency | Weak hook, hold or both | Check the table above |
| Big CTR, few sales | Inflated CTR | Judge on unique outbound CTR |
| LPV rate under 70% | Redirects, tracking, blockers, speed | Speed up the page |
| Add-to-cart under 5% | Page or offer doesn't convince | Fix the product page ([[Product Page Essentials Framework]]) |

## Checklist for the custom metrics you need

- [ ] Hook rate: 3-second plays ÷ impressions
- [ ] Hold rate: ThruPlays ÷ 3-second plays
- [ ] Delivery efficiency: ThruPlays ÷ impressions
- [ ] Add-to-cart rate: add-to-cart events ÷ landing page views
- [ ] Columns to show: frequency, CPM, unique outbound clicks and their CTR, plus landing page views and the rate for them
- [ ] Switch on the quality ranking, engagement rate ranking and conversion rate ranking

## Worth tracking next

Conversion rate, CPA and ROAS, and checkout initiation rate follow the same logic.

## Related

- [[Meta Ad Metrics Framework - Part 1]] — funnel map, formulas and top-of-funnel metrics
- [[Product Page Essentials Framework]] — fixing a low add-to-cart rate
- [[Simplifying Meta Ads Structure Framework]] — the structure behind clean data
