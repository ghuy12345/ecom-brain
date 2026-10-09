---
title: "Brand Search and Branded Shopping Campaigns"
topic: "08 Google Ads"
stage: intermediate
tags: [google-ads, brand-search, branded-shopping, incrementality, marketplaces]
summary: "Isolate your brand traffic in dedicated search and Shopping campaigns for clean data and defence, then test and size that spend rather than assuming it is all incremental."
---
# Brand Search and Branded Shopping Campaigns

## What it is
Brand campaigns capture people searching your brand name. They do two jobs. **Data integrity:** if brand traffic leaks into PMax or cold campaigns, those campaigns look brilliant and you cannot tell cold revenue from returning revenue. **Defence:** if you do not show up on your own name, competitors, marketplaces or resellers can sit above you.

A dedicated brand search campaign is cheap because your brand term earns a top quality score that rivals cannot match. Normal brand CPCs run around 10-15 cents and can be a few cents. Brand terms bought inside PMax or broad campaigns often cost $1-3, which signals leakage. Generic-word brand names and very competitive categories are the exception.

## When to use it
- Always, as a separate brand campaign, once you run cold Google campaigns.
- When PMax shows a high ROAS that does not hold when you add budget.
- When marketplaces, stockists or competitors appear on your brand searches.

## How (steps)
**1. Set up brand search.**
- Create one campaign for your name and its variants.
- Use Target Impression Share bidding rather than conversion bidding: you want to appear for every brand searcher. Switching often cuts brand CPCs sharply while improving share; one report saw CPCs fall about 80%.
- Exclude brand from every cold campaign: negatives on Search and Shopping, brand exclusions in PMax. Keep checking search terms for leaks.
- Review auction insights regularly; raise bids or the share target if a competitor appears, and look for regional pushes.

**2. Test whether brand search is incremental.** For many stores it is not: switch paid off and clicks move to your organic listing.
1. Export daily Search Console clicks and impressions on brand queries for the last 60-90 days, alongside the brand campaign's clicks, impressions and cost.
2. Chart stacked paid plus organic clicks, with spend and total CTR.
3. Lower brand spend in steps (bid strategy changes work better than budget cuts).
4. If total clicks stay flat, the spend was not incremental. If total clicks fall, you are losing branded clicks, possibly to competitors; restore some spend and check conversions.
Results differ if a competitor buys your name or your organic listing is not first.

**3. Decide how much to spend when marketplaces compete.** Marketplaces and resellers can bring buyers you would never reach. The risk is paying twice: you fund awareness, then a reseller intercepts the brand search and you pay acquisition cost plus their cut. Search your brand in a private window and write answers to three questions:
- What do you want from marketplaces: reach, revenue, retail presence or profit?
- How valuable is a direct customer, given repeat rate and cross-sell?
- How much stronger is the reseller's offer on returns, delivery speed and shipping cost?
High-repeat consumables with easy cross-sell justify defending hard. Low-repeat, high-ticket goods justify a modest share target and moving budget to cold acquisition. If the reseller's offer is far better, you lose the click even when you rank beside them.

**4. Add branded Shopping if volume allows.** Shopping has no keywords, so you build it indirectly: a standard Shopping campaign at HIGH priority, maximise clicks, a small budget (around $5/day), all products, plus a scheduled script that adds every non-brand search term to a shared negative list.
- Script inputs: the campaign's numeric ID (from the campaign URL), a comma-separated list of brand variants, and the negative list name. Run it hourly.
- Add your brand as a negative in every other Shopping and PMax campaign to avoid duplicates.
- Check the search terms report; a few stray terms may appear within the hourly lag.
Volume threshold: under about 10 brand clicks a day, skip it, because Shopping will spend its budget on cold terms anyway. At 10-15, run it and monitor closely. Above about 15, launch. The payoff is near-total share of your own Shopping block (which sits above text results on mobile) and CPCs well below brand clicks inside regular Shopping.

## Example
Say PMax reports 6.5x with no brand campaign. A 50% budget increase leaves store revenue flat and ROAS slides to 3x, because most of that 6.5x was brand traffic. The fix: start brand search and branded Shopping campaigns, block brand terms in PMax, and measure PMax again against non-brand revenue only. Separately, a luggage brand with a low repeat rate and a strong marketplace listing caps brand search at a modest share target and moves the savings to cold Shopping.

## Common mistakes
- No dedicated brand campaign, so brand inflates cold results.
- Defending your brand heavily when no competitor bids on it.
- Running branded Shopping with too little brand volume.
- Forgetting the brand negative on one cold campaign.

## Related
- [[Performance Max Setup - Asset Groups and Brand Exclusions]] — excluding brand from PMax
- [[Is Performance Max Incremental]] — the wider incrementality question
- [[Competing With Low-Price Marketplace Sellers]] — handling marketplace pressure on Shopping
- [[Search Terms and Negative Keywords]] — the controls that stop brand terms leaking into cold campaigns
- [[Cohort LTV Modelling]] — valuing a direct customer when deciding to defend
