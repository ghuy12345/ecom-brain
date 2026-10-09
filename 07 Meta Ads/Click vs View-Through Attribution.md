---
title: "Click vs View-Through Attribution"
topic: "07 Meta Ads"
stage: scaling
tags: [meta-ads, attribution, view-through, incrementality, scaling-gate]
summary: "How click and view-through credit change both what Meta reports and whom it optimises toward, how to check your click share, and how to tell whether a top ad really finds new customers."
---
# Click vs View-Through Attribution

## What it is
Your attribution setting plays two roles. It decides which purchases Meta reports, and it tells the system whom to optimise toward. Click-based credit counts a purchase if it happens within the window after someone clicks the ad (seven days for 7-day click). View-through credit counts purchases from people who saw the ad, did not click, and bought later. View-through is useful for very small accounts that need every data point, but it is not incremental. If reporting is inflated by view-through, delivery slides toward buyers who were going to purchase regardless.

## When to use it
- Before every scale-up.
- When reported ROAS and store revenue disagree.
- When results swing wildly day to day.
- When your "best" top-of-funnel ad seems too good to be true.

## How (steps)
1. **Compare settings.** In Ads Manager, use Columns, Compare attribution settings, and place 7-day click beside your default, plus 1-day click where that helps.
2. **Calculate click share** per campaign and for the account: click-based purchases divided by total purchases.
3. **Read the result.** When view-through supplies over half of purchases, your reporting is inflated. Ads that show purchases but zero click purchases are only collecting credit.
4. **Find the cause.** The usual three: email or SMS sends that spike purchases, a high share of returning customers, and strong organic or influencer presence.
5. **Fix it.** Run 7-day click only. Ideally test it side by side: same ads, two campaigns, one on click plus view and one on click only; compare click-based ROAS and spend.
6. **Pick a default by spend.**
   - Under about $1,000/day: 7-day click plus 1-day view is acceptable, because you need the data.
   - Above about $1,000/day, or with heavy view-through: 7-day click only.
   - 1-day click as an optimisation setting is rarely needed below very large budgets, but it is a useful column for seeing how quickly people buy.
7. **Use it as the scaling gate.** Only scale when at least about 60% of purchases are click-based, or when click-based results alone hit KPI. See [[Meta Scaling Decision Tree]].

## Checking a top-of-funnel ad
The top spender in an automated campaign can show a dazzling headline ROAS and, once broken down, deliver a fraction of it on new customers.
1. Look at frequency first; even a modestly elevated number is an early warning sign.
2. Break down by audience segment (new, engaged, existing). When existing customers soak up roughly half the budget and new-customer ROAS sits far below the headline, the ad mostly serves people who already buy from you.
3. Within the new-customer segment, set 7-day click against incremental attribution.
4. Fix: optimise to 7-day click, keep existing customers out of cold campaigns (customers lapsed for around two years form their own separate group), and measure top-line impact at product level when you scale.
After months of scaling where CAC keeps climbing but new-customer counts stay flat, assume your "winner" is retargeting or over-attributing.

Meta's incremental attribution applies a pooled estimate rather than your own experiment, so treat it as a column to inspect, not the truth. Holdout lift tests are the rigorous version.

## Example
Say a brand duplicates its ads into two otherwise identical campaigns. The click-plus-view campaign spends about $8,000 at a reported 8x but under 3x on click data. The click-only campaign spends three times as much at about 3x click-based. The reported number was flattering; the click-only campaign was finding more real buyers.

## Common mistakes
- Sorting ads by ROAS under the default setting.
- Allowing existing customers to absorb budget in "cold" campaigns.
- Expecting an attribution switch alone to multiply spend; it improves incrementality, not reach.
- Scaling on a day when an email blast inflated results.

## Related
- [[Meta Scaling Decision Tree]] — where the click-share gate sits
- [[Using a Third-Party Attribution Dashboard]] — cross-checking Meta with outside data
- [[Isolating Winners in a Dedicated ABO]] — attribution test ad sets
- [[Auditing an Ad Account]] — data integrity checks that use these comparisons
- [[Is Performance Max Incremental]] — the same question on Google
