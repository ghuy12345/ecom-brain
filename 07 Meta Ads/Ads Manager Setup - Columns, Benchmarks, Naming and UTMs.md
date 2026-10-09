---
title: "Ads Manager Setup - Columns, Benchmarks, Naming and UTMs"
topic: "07 Meta Ads"
stage: beginner
tags: [meta-ads, ads-manager, custom-columns, hook-rate, utm, naming]
summary: "Build an Ads Manager view that shows money first, the custom creative metrics second, names that double as a setup check, and UTMs so you can read Meta independently."
---
# Ads Manager Setup - Columns, Benchmarks, Naming and UTMs

## What it is
Ads Manager's default columns hide most of what you need to judge creative. A good setup has three parts: a saved column preset with the hard money metrics first and the creative diagnostics after; a naming template that fills itself from your real settings; and UTM parameters on every ad so your store and analytics can count Meta traffic without trusting Meta's own reporting.

## When to use it
- Once, when you set up a new ad account, then save it as a preset.
- Whenever you onboard someone new, so everyone reads the same view.
- Before any review of winners and losers.

## How (steps)
1. **Order columns by importance.** Money first: amount spent, purchases, cost per purchase, purchase value, ROAS. Then context: delivery, budget, attribution setting, date created, impressions, reach, frequency, CPM. Then creative diagnostics: average play time, hold rate, hook rate, link CTR, cost per link click and link clicks, followed by adds to cart and checkouts with their costs, and finally URL parameters (to confirm UTMs are set).
2. **Create custom metrics** (Customize columns, Create custom metric):
   - AOV = purchase conversion value / purchases
   - Conversion rate = purchases divided by landing page views (link clicks works as a fallback)
   - Hook rate = impressions-based share of 3-second video plays (3-second plays divided by impressions)
   - Hold rate = ThruPlays / 3-second plays (a ThruPlay is 15 seconds watched, or the whole video if shorter)
   - Delivery efficiency = ThruPlays / impressions (hook rate multiplied by hold rate)
   Save the whole set as a column preset.
3. **Add a spend-share view.** For reviews, note each ad's share of total account spend over seven days. Share of spend tells you more than ROAS on a tiny budget (see [[Learnings From Losing Ads]]).
4. **Use rough benchmarks, then your own baseline.**
   - Hook rate: under 25% is a warning sign, 25% acceptable, 40%+ a good target.
   - Hold rate: aim for 30% or more; compare like-length videos.
   - Link CTR: above 1% is the floor, above 1.5% good. If an ad is profitable, its CPC does not matter.
   - CPM around $10 is very cheap; $60-70 is hard to make work.
   - 30-day frequency drifting toward 6 suggests the ad is mostly re-serving people who already know you.
   Conversion rate and AOV have no universal benchmark; compare to your own account.
5. **Set name templates** (Ad account settings, Name templates). Let campaign and ad-set names fill dynamically from country, gender, age, custom audiences and budget type. The value is verification: if you add a second country by mistake or forget to switch on campaign budget, the name changes and exposes it. At ad level, name manually: product or concept, creative variant, destination page, copy and headline numbers, and batch number.
6. **Add UTM parameters at ad level.** In the ad's URL parameters field, set a fixed source (for example facebook_ads), a fixed medium (for example paid_social), and dynamic placeholders for campaign, ad set, ad name and ad ID. Pick one spelling and never vary it; two spellings of the same source split your reports.
7. **Test and reconcile.** Click one live ad and confirm the parameters reach the landing URL and your store's session report. Weekly, compare orders by UTM source in your store against what Meta reports. That difference tells you how much Meta is over-attributing.

## Example
Say Meta reports 60 purchases this week and Google reports 42, but your store's UTM breakdown shows 29 orders from Meta and 38 from Google. Neither platform is lying about its own model, but the store view shows Meta is crediting itself with roughly twice the orders it can prove. You keep using Meta's numbers to compare ads inside Meta, and the store view to decide how much budget Meta deserves overall.

## Common mistakes
- Sorting by ROAS instead of spend, and getting excited about a high-ROAS ad that spent almost nothing.
- Optimising for cheap clicks or high CTR rather than profit.
- Reading hook and hold on static ads, where they do not apply.
- Treating add-to-cart and checkout columns as decision metrics; they mostly diagnose a brand-new account (hundreds of clicks with no add to cart is a funnel problem).
- Typing targeting into names by hand so names drift away from the real settings.
- Setting UTMs at campaign level, or using inconsistent source names.

## Related
- [[Meta Ad Metrics Framework - Part 1]] — a deeper framework for reading these metrics
- [[Meta Ad Metrics Framework - Part 2]] — continued metric framework
- [[Click vs View-Through Attribution]] — the attribution column that changes what these numbers mean
- [[Learnings From Losing Ads]] — how to use the columns in a review
- [[Glossary - Metrics & Media Buying]] — definitions of each metric
- [[Diagnosing a Store With Conversion Benchmarks]] — on-site benchmarks that complement these
