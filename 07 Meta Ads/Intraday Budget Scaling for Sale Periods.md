---
title: "Intraday Budget Scaling for Sale Periods"
topic: "07 Meta Ads"
stage: scaling
tags: [meta-ads, intraday-scaling, promotions, bfcm, blended-roas, budgets]
summary: "During a sale, check results every few hours and raise or hold budgets on blended ROAS, account for reporting lag, and reset the next morning from what you actually spent."
---
# Intraday Budget Scaling for Sale Periods

## What it is
During a real promotion, conversion rates and intent spike for a few days. Adjusting budget once a day is too slow to capture that. Intraday incremental scaling means checking performance every one to six hours, logging each period in a shared sheet, and raising, holding or cutting budget by fixed rules. The sheet exists so everyone on the team decides the same way from the data instead of scaling on gut feel.

## When to use it
- Sale periods: Black Friday and Cyber Monday, seasonal holidays, launch sales.
- On evergreen campaigns only when one campaign is already spending several thousand dollars daily.
- Not at around $1k/day: each period has too few purchases to judge.

## How (steps)
1. **Finish all testing beforehand.** On peak sale days scaling is the only job; tests and site changes must be done and switched off.
2. **Note both time zones.** Budgets roll over at midnight in the ad account's time zone, not your own. Raising budget just before that reset can blow out the next day. Put a time-zone converter in the sheet and arrange cover across time zones on peak days.
3. **Choose a check interval by spend,** so each period has enough purchases to read:
   - A few hundred dollars a day: every 6 hours at most.
   - About $5-20k/day: about every 4 hours.
   - About $30k/day and up (roughly $1M a month): every 2 hours.
   - Near $100k/day: hourly, never more often. Hourly is justified at roughly 50 purchases per hour.
4. **Log each period:** store revenue, platform revenue, Meta spend and other-channel spend. Compute blended ROAS (store revenue / total ad spend) for the period.
5. **Decide using blended ROAS first.** Platform data lags and can look good when the store does not. If blended is below target, do not scale, whatever the campaigns show.
6. **Apply step rules against target** (the 20%, 50% and 100% steps are rough estimates, not benchmarks):
   - 50-100% above target: double (triple only if very aggressive).
   - 20-50% above: +20%.
   - At target: hold.
   - Below target or a dead hour: hold or cut about 20%.
   Shifting budget from evergreen to the sale campaign can work better than adding more overall.
7. **Watch 1-day-click ROAS.** Launch-day and email-blast spikes inflate platform numbers. A revenue spike caused by email does not justify scaling paid media; wait for the click signal.
8. **Scale ahead of known rushes.** Meta reacts one to two hours late. If you wait to see the evening peak before raising budget, delivery arrives after the buyers have gone.
9. **Reset the next morning.** Set the new day's budget to about half of what you actually spent yesterday, not half of the figure you set. With repeated doubling through the day, delivery often cannot spend it all; an unreset inflated budget will spend in full from midnight. Example: budget raised to $500, spent $300, start tomorrow at $150. After an exceptional day you can keep it. Prefer underspending to overspending.
10. **Cost-cap campaigns:** lift the budget during the day and leave the bid alone.

## Why sale steps differ from evergreen steps
Evergreen scaling uses small steps every one to three days because there is no deadline and each step pushes into colder audiences. A sale compresses demand into hours, so doubling or several 20-50% steps a day is justified. Using sale-sized steps in normal weeks, or evergreen steps during a sale, are both mistakes. Aggressive scaling also needs a team in sync: media buyer, creative and whoever watches the store.

## Example
Say an account at about $40,000/day checks every two hours on Black Friday. Successive periods come in at 5.1x, 4.8x, 3.6x and 3.1x against a 2x target on blended data, so budget doubles twice, then rises 20% twice. Mid-afternoon reads 1.7x for one period, so budget holds. The next morning the account spent $62,000 of a $110,000 budget; it resets to about $31,000 and climbs again.

## Common mistakes
- Scaling on feel or on platform ROAS alone.
- Forgetting the ad account's time zone.
- Not resetting, so the inflated budget spends in full.
- Checking too often at low spend.

## Related
- [[Black Friday Week - Day-by-Day Curve]] — when the hot windows arrive
- [[Sale-Period Campaign Structure]] — the campaign this routine scales
- [[Budget Increase Rules for Evergreen Scaling]] — the slower evergreen rules
- [[Setting a Target ROAS - Breakeven Plus One]] — recalculating targets at sale prices
- [[Black Friday Pre-Season Spend Pacing]] — reading lagged returns around the peak
