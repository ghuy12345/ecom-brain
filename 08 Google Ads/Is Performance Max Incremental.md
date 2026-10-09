---
title: "Is Performance Max Incremental"
topic: "08 Google Ads"
stage: scaling
tags: [google-ads, performance-max, demand-gen, incrementality, geo-lift-test]
summary: "Performance Max and Demand Gen often claim sales your other marketing created; check whether their revenue follows the rest of the business and run a regional lift test before scaling them."
---
# Is Performance Max Incremental

## What it is
Incrementality is the revenue that would not have happened without a campaign. For brands with several traffic sources, Performance Max's attributed revenue often tracks total store revenue rather than driving it. PMax retargets people who already know you through YouTube, Display, Gmail and brand search, and then claims their purchase. Its real influence on those sales may be a fraction of what it reports.

Demand Gen shows the same pattern. Regional tests can show lift among returning customers but little among new ones, so it can behave like a retargeting channel rather than a demand creator. That does not prove it never works, but it is a reason to measure before you scale.

## When to use it
- Before raising PMax or Demand Gen budgets on the strength of in-platform ROAS.
- When you run significant spend on Meta, email, PR or influencers alongside Google.
- When reported Google ROAS is high but total revenue does not respond to more Google spend.

## How (steps)
**1. Apply a working discount.** As planning rules of thumb, not facts:
- Meta on 7-day click with healthy tracking: take 10-20% off reported ROAS.
- Standard Shopping: a reported 10 might be roughly 8-9 incremental.
- PMax: a reported 10 may be only 3-5 incremental. Discounting PMax ROAS by 30-70% for scale planning is reasonable, even with brand exclusions on.

**2. Run the mirror check.** Overlay 90 days of PMax-attributed revenue on total store revenue. If peaks and dips line up, PMax is following, not leading.

**3. Log outside events.** Note email sends, PR hits, influencer pushes and Meta budget changes. If PMax ROAS spikes on email days and drops when Meta traffic falls, it depends on traffic created elsewhere.

**4. Run a regional lift test** for any channel you are unsure about.
1. Export at least 12 months of orders by region, daily if possible. Find regions that move closely together and have enough volume; pick test regions and control regions.
2. Build a baseline of expected daily orders in the test regions with 90% and 95% confidence bounds, and work out the lift needed to be significant.
3. Budget = incremental orders needed x the CAC you assume. Accepting 90% confidence lets you spend less.
4. Run for about three weeks with nothing else changing; longer runs risk mixing in unrelated business changes.
5. Split results into new and returning customers. Always report the two separately.

**5. Decide.**
- A meaningful lift in new customers: scale it up.
- A lift among returning customers only: shrink the budget, reclassify the campaign as retargeting, and later test removing it.
- No lift: switch it off.

**6. Restructure around the answer.** Use standard Shopping for cold acquisition and keep PMax as a smaller retargeting layer ([[Performance Max vs Standard Shopping]]). Track new-customer revenue and acquisition MER next to platform ROAS, and never scale PMax on its own reported number.

## Example
Say a store sends an email to its full list and store revenue jumps by a large amount that day. PMax reports an 8x ROAS that week. The next week, with no email and no campaign changes, PMax drops to 4x. Nothing inside Google changed; PMax was claiming the people the email brought back.

Now a hypothetical regional test: two closely correlated metro areas, three weeks, a few thousand dollars on Demand Gen. Total orders rise about 5% against forecast, returning-customer orders rise about 14%, and new-customer orders stay inside the noise band. The implied new-customer CAC is unprofitable on a first order. The decision is to cut the campaign to a small daily budget as a returning-customer tool and test switching it off later.

## Common mistakes
- Treating a reported ROAS of 5 as meaning an extra $1,000 will return $5,000.
- Reading platform ROAS without splitting new vs returning revenue.
- Running a lift test while also changing offers, prices or other channels.
- Concluding from one test that a channel can never work, or from one good week that it always does.
- Making PMax the primary acquisition campaign when it is mostly re-capturing existing demand.

## Related
- [[Performance Max vs Standard Shopping]] — where to move budget once you know PMax's true return
- [[Click vs View-Through Attribution]] — why platforms over-credit themselves
- [[Using a Third-Party Attribution Dashboard]] — tracking new-customer revenue across channels
- [[Brand Search and Branded Shopping Campaigns]] — the same incrementality question for brand terms
- [[Reading Split-Test Results - Sample Size and Power]] — significance thinking behind lift tests
