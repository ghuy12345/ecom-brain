---
title: "Performance Max Setup - Asset Groups and Brand Exclusions"
topic: "08 Google Ads"
stage: intermediate
tags: [google-ads, performance-max, asset-groups, brand-exclusions, feed-only-pmax]
summary: "Configure Performance Max so it can learn: size asset groups to your budget, give each a real reason to exist, and exclude your brand so PMax has to find new customers."
---
# Performance Max Setup - Asset Groups and Brand Exclusions

## What it is
Performance Max is not the problem; default-settings PMax is. Left alone, it lumps every product into one asset group, sweeps up your branded searches, and drifts into cheap placements. This note covers the setup that keeps it honest: how many asset groups to run, what goes in each, how to exclude your brand, and when to strip it back to a feed-only campaign.

## When to use it
- Launching PMax, or inheriting one with a single asset group.
- When PMax reports a strong ROAS that falls apart once you look at brand vs non-brand.
- When you add a new product line that should not inherit the old line's audience.

## How (steps)
**1. Decide whether PMax should run at all.** At around $50/day, standard Shopping or a single asset group is usually better, unless PMax clearly wins on new customers ([[Performance Max vs Standard Shopping]]).

**2. Size asset groups to budget.** A handy rule of thumb: allow one asset group for each $50 you spend per day. Spread $100/day across ten groups and each gets $10; at a $40 CPA that is one conversion every four days, far too little to learn from. Keep a sensible range: at least three groups once budget allows, rarely more than about twenty, and simpler beats sprawling.

**3. Only split for two reasons.**
- *Signals*: different customer lists, in-market audiences or search themes. These are hints that point the model somewhere, not hard targeting. They matter most on new launches and matter little once a mature account has data; you can remove them after about a month of conversions. Use terms and lists that actually converted.
- *Assets*: images, headlines, landing pages and value propositions specific to a product type. A bottle brand adding food containers should not show container shoppers bottle messaging.

**4. Build groups by product type.** List categories with their conversion volume. Fold low-volume categories together; keep a hero category separate only if it can feed its own data. Split similar categories (shirts vs tops) only when both have volume. Customise the listing group in each asset group so every product is not in every group, and give each group at least around 15 products; a one-product group tends to get no spend.

**5. Plan restructures in advance.** Decide restructure points on a budget roadmap (for example at $100, $200 and $300 per day). Changes at asset-group level can depress results for about a month, so do not restructure as a reaction to a dip.

**6. Exclude your brand.** Brand exclusions push branded traffic into your brand campaign and point PMax at cold audiences. Without them, PMax is largely retargeting.
1. Open the campaign settings, then additional settings, then brand exclusions.
2. Create a new brand list and name it.
3. Type your brand and pick your own site from the suggestions; add every variant offered.
4. Save the list and the campaign, then attach the same list to every PMax campaign.
5. Add brand negative keywords to PMax as a second safeguard.
6. Run a dedicated brand search campaign (and branded Shopping if volume allows) to catch that traffic ([[Brand Search and Branded Shopping Campaigns]]).
7. Check later that brand queries now show up in the brand campaign.

Expect PMax's reported ROAS to fall after exclusion while total revenue barely moves. That lower number is the honest non-brand ROAS you can now scale against.

**7. Know the priority order of levers.** Feed quality first, then brand exclusions, then asset and listing-group structure and creative quality, then bidding, and last the signals and search themes.

**8. Use feed-only PMax when it drifts.** If PMax pushes spend into video or inbox placements (where an opened email counts as a click), delete the asset groups but keep the listing groups, and turn off URL expansion and auto-created assets. This forces spend into Shopping.

## Example
Say an apparel brand runs PMax at $200/day. That supports up to four asset groups: tops, bottoms, outerwear (the hero) and accessories folded into bottoms because they sell too little alone. At $300/day it adds a fifth group. If PMax shows about 6x before the exclusion and about 3x afterward, with total revenue flat, scale against the 3x.

## Common mistakes
- One asset group holding the whole catalogue.
- More asset groups than the budget can feed.
- Treating audience signals like Meta interest targeting.
- Excluding brand from one PMax campaign and forgetting the others.
- Restructuring every time results dip.

## Related
- [[Performance Max vs Standard Shopping]] — whether PMax should run, and how big
- [[Is Performance Max Incremental]] — judging PMax after it is set up
- [[Brand Search and Branded Shopping Campaigns]] — where excluded brand traffic should go
- [[Shopping Feed Optimisation]] — the top lever for PMax performance
- [[Google Ads Account Structure for Ecommerce]] — the learning layers behind asset-group sizing
