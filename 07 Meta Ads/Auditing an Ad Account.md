---
title: "Auditing an Ad Account"
topic: "07 Meta Ads"
stage: scaling
tags: [meta-ads, audit, data-integrity, account-structure, creative-velocity, inherited-account]
summary: "Audit a Meta account in order of data integrity, structure and creative velocity and diversity, and mine an inherited account for previous winners before testing anything new."
---
# Auditing an Ad Account

## What it is
Treat an audit as a hunt for the one constraint holding the business back, with fixes ranked by commercial impact into a plan of about 90 days. A pile of settings mistakes is not an audit. There is only ever one main bottleneck; when the numbers themselves are unreliable, that is it, since every other call depends on them. Audit three pillars in this order: data integrity (fastest, validates everything else), structure (fast), creative (highest impact, slowest to change). Google audits are covered in [[Google Ads Self-Audit and Bottleneck Diagnosis]].

## When to use it
- Taking over an account from another team or agency.
- Growth has stalled and nobody agrees why.
- Quarterly, as a health check on a scaling brand.

## How (steps)
**Pillar 1: data integrity (start in the store, not the ad platform)**
1. Build a monthly cohort view over about two years: CAC (total ad spend / new customers), new-customer count, gross profit on first purchase (real margins and AOV), and first-purchase gross profit to CAC. CAC climbing alongside customer volume is healthy; CAC climbing while volume stays flat means you are paying extra for the same buyers.
2. Build a normalised P&L for the same period down to contribution profit, plus a second one for first-time orders only. New-customer revenue divided by ad spend gives an acquisition efficiency ratio you can trust.
3. Compare that ratio with platform ROAS. If the platform claims several times more, suspect spend on existing customers and view-through credit. Compare attribution settings; stricter ones usually correlate far better with the store.
4. If a channel's incrementality is still unclear, run a geo holdout test.
5. Check retention at 90, 180 and 365 days. Strong retention tolerates higher CAC; weak retention needs first-purchase profit.

**Pillar 2: structure**
1. List every campaign with a purpose column. Anything without a defensible job gets cut or merged. Let structure grow with the business's own complexity (markets, sub-brands, catalog size) rather than with spend.
2. Check the new / engaged / existing split by frequency, not percentage. Very high 30-day frequency on existing customers means overspend.
3. Check attribution settings are consistent and restrictive.
4. Scan for errors: cold campaigns that still reach existing customers, legacy interest or lookalike targeting on purchase objectives, low-quality placements leaking in, and names that do not match what campaigns do.
5. Check catalog ads are not taking most of the spend.

**Pillar 3: creative velocity and diversity**
1. Volume: a rough guide is one fresh ad for every $1,000 spent per month, with diminishing returns at very high spend. Better: estimate how many winners churn out each month and divide by your hit rate.
2. Diversity is counted in concepts (angle, offer, persona) rather than formats. A rough guide: under $100k/month, one to three concepts; $100-500k/month, about two winning concepts with more in test; above that, three or more winners and several in test.
3. Quality: judge scripts against direct-response fundamentals, and check that someone can explain why each winner won.

**Inherited accounts: find previous winners first**
1. List top prospecting and top retargeting creatives over 30 days and over six months, sorted by spend, then CPA or ROAS. Save share links.
2. Confirm "prospecting" campaigns really are broad; if there is no retargeting campaign, sort by frequency to find ads acting as retargeting.
3. Remove duplicates (the same creative frequently appears as multiple ads).
4. Add hook, hold, play time and CTR, and set your own thresholds before calling anything great.
5. Seed proven winners into a champions ad set that new tests must beat. In a brand-new ad account, previous winners may not win again; reuse pages and pixel and make fresh creative.

## Example
Say a beauty brand at $150k/month shows 6x platform ROAS but first-order revenue over ad spend of 2.1x. Half of "prospecting" spend reaches existing customers. The audit's first fix is excluding customers and switching to 7-day click, the second is merging six campaigns into two, the third is lifting output from four to about twelve concepts a month.

## Common mistakes
- Auditing from platform data alone.
- Settings checklists with no commercial priority.
- Counting format variety as creative diversity.
- Ranking inherited ads without removing duplicates.

## Related
- [[Click vs View-Through Attribution]] — the attribution checks in pillar one
- [[Reading an Ecommerce P&L]] — building the P&L view
- [[LTGP to CAC Ratio and the CAC Death Spiral]] — interpreting cohort ratios
- [[Campaign Types - An Account Map]] — what a defensible structure looks like
- [[Hit Rate vs Creative Volume]] — sizing creative output
