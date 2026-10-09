---
title: "Meta Ad Metrics Framework - Part 1"
topic: "07 Meta Ads"
stage: beginner
tags: [meta-ads, ad-metrics, hook-rate, hold-rate, cpm, frequency, seba-framework]
summary: "Part 1 of a Meta ad metrics framework: the funnel map, all formulas and benchmarks, and how to read frequency, CPM, hook rate and hold rate."
---
# Meta Ad Metrics Framework - Part 1

Framework by Josh Omosebi, Seba Agency.

Part 2 covers delivery efficiency, clicks, CTR, landing page views, add-to-cart and diagnostics: [[Meta Ad Metrics Framework - Part 2]].

## The funnel in one picture

Each metric marks one step of a viewer's path from seeing the ad to adding to cart, and shows where people fall away.

```
SEEN ──► STOPPED ──► STAYED ──► CLICKED ──► LANDED ──► CARTED
Impr./     Hook rate   Hold rate  Clicks/CTR  LPV rate    ATC rate
Reach/        └─ Delivery efficiency ─┘
Frequency
CPM = the price of being seen
```

**Core principles**
- Optimise for conversions, not vanity. A metric only matters for what it says about reaching buyers.
- Always use the strictest version: unique over total, outbound over any click. Inflated figures hide problems.
- Better ads that talk to your customer are the main lever on CPM and everything downstream.

## Cheat sheet

### Formulas

Source column: "Built-in" means Meta reports it by default, "Custom" means you create it as a custom metric.

- **Frequency** (built-in): impressions divided by reach.
- **CPM** (built-in): what you pay for every 1,000 impressions.
- **Hook rate** (custom): impressions as the denominator, 3-second video plays as the numerator.
- **Hold rate** (custom): ThruPlays over 3-second video plays.
- **Delivery efficiency** (custom): ThruPlays over impressions, which equals hook × hold.
- **CTR** (built-in): all clicks over impressions.
- **Unique CTR** (built-in): unique clicks over reach.
- **Outbound CTR** (built-in): outbound clicks over impressions.
- **Unique outbound CTR** (built-in): unique outbound clicks over reach.
- **Landing page view rate** (available in Meta): landing page views over link clicks, or over outbound clicks.
- **Add-to-cart rate** (custom): adds to cart over landing page views.

### Benchmarks

- **Frequency at the top of the funnel:** aim for roughly 1.0 to 1.4.
- **Frequency at the bottom of the funnel:** around 2 to 4, or more, is normal.
- **Hook rate:** under 25% is a warning sign, 25% and up is acceptable, 40% and up is the target.
- **Hold rate:** target 30% or more.
- **Landing page view rate:** under 70% is cause for worry and under 60% means real trouble; 70 to 80% is acceptable; aim for 90% or more.
- **Add-to-cart rate:** under 5% is a warning sign (it varies by industry); 5 to 10% is acceptable; aim for 10% or more.

### Which version to use

- **Counting clicks:** go with unique outbound clicks.
- **Campaigns aimed at followers, awareness or on-platform actions:** use unique CTR.
- **Ecommerce, or anything sending people off Meta:** use unique outbound CTR.
- **Plain CTR:** skip it, because it overstates performance.

## Impressions, reach and frequency

Impressions count showings, reach counts people, frequency is showings per person.

**Frequency reveals two things:**
1. **Funnel position.** Prospecting ads usually hover around 1 to 1.4, while retargeting-style ads land near 2 to 4 or higher, with the middle in between. Meta assigns each ad its position without your input, typically within the first week, depending on spend.
2. **Fatigue.** Give a new ad a few days to a week; leave a good one running a week or more. If, after a couple of steady weeks (say 1.3 to 1.5), CPA and frequency start rising together, the creative is fatiguing.

## CPM

CPM is what you pay per thousand impressions, the cost of reaching your audience.

**CPM rises with:** a competitive market, a high price point, the audience chosen, creative fatigue, and audience overlap at higher spend.

**Meta's three rankings**

| Ranking | What it judges |
|---|---|
| Quality | Is this relevant and good compared with competitors' ads? |
| Engagement rate | Does it stop attention and earn clicks, comments, shares? |
| Conversion rate | Do your page, offer and price suit this audience? |

The more relevant the ad, the higher its quality ranking and the lower the CPM.

**Reading the rankings:** a low conversion ranking means ad and page don't connect; high quality with low conversion looks like clickbait; a generally low conversion ranking points at page, offer or price. High-ticket products naturally carry higher CPMs, but still check page and offer.

## Hook rate

Build it as a custom metric: 3-second video plays ÷ impressions, formatted as a percentage.

**A hook is three things:** the words, the visuals and the on-screen text.

**Relevance over volume.** A good hook filters out the wrong people. A high hook rate that attracts the wrong audience brings weak traffic, a disconnect with the page and lower conversion.

**Benchmarks:** 25% minimum, 40%+ target.

## Hold rate

This is the portion of viewers who keep watching once the hook ends. It tells you whether the video stays relevant to the person the hook addressed and interesting enough to hold them.

**Setup:** custom metric of ThruPlays ÷ 3-second plays. A ThruPlay is a view reaching 15 seconds or the end, whichever is first.

**What it measures:** everything after the hook, usually the bridge and the pain section. **Target:** above 30%.

## Related

- [[Meta Ad Metrics Framework - Part 2]] — covers clicks, the landing page step, carting and troubleshooting
- [[Simplifying Meta Ads Structure Framework]] — the structure these metrics read
- [[Breakthrough Advertising Ch 2 - The Five Levels of Awareness - Part 1]] — why a hook should filter
