---
title: "Breakeven ROAS and KPI Tiers"
topic: "11 Finance & Unit Economics"
stage: intermediate
tags: [breakeven-roas, gross-margin, kpi, blended-roas, cpa, unit-economics]
summary: "How to derive breakeven ROAS from your gross margin, which KPI tier to judge ads by at each stage, and how to reset the number when a discount changes your margin."
---
# Breakeven ROAS and KPI Tiers

## What it is
**Breakeven ROAS** is the return on ad spend at which a sale covers its product, delivery and processing costs and the ad that bought it, with nothing left over:

**Breakeven ROAS = 1 / gross margin**

A 70% margin gives a breakeven of about 1.43; a 50% margin gives 2.0. It is the floor under every other target. **Scaling ROAS** is the higher return at which you are comfortable raising budgets (see [[Setting a Target ROAS - Breakeven Plus One]]).

A **KPI tier** is the measurement you judge performance by. Which one is right depends on your size, how much organic revenue you have and what tracking you can afford.

## When to use it
- Before your first campaign, so you know what "working" means.
- Every time price, product cost, shipping or the offer changes.
- When you move from one platform to several, or when organic sales grow, and need a more honest KPI.

## How (steps)
1. **Compute gross margin on the revenue you actually collect.** Revenue = product price plus any shipping you charge. Costs = product cost, shipping (to you and to the customer), payment processing and a small padding allowance for handling. Use gross margin, never net margin, and leave fixed costs such as salaries, editors, software and the store subscription out of it.
2. **Convert to breakeven.** Divide 1 by the margin, or enter the margin into a profit calculator with service fees, ad spend and multiplier set to zero. Always round up (1.37 becomes 1.4); at true breakeven, small hidden costs usually mean you are still slightly negative.
3. **Record it somewhere permanent** and recompute whenever an input changes. If a spreadsheet calculator breaks, check for blank fields and enter zero instead.
4. **Choose your KPI tier.**
   - *Beginner: blended ROAS* = total store revenue / total ad spend. No tools needed. Best when sales volume is low, organic presence is small or several platforms run at once.
   - *Intermediate: in-platform ROAS plus blended.* Once organic revenue is meaningful, blended alone flatters paid ads, so read both.
   - *Advanced: new-customer CPA against LTV at 3, 6 and 12 months.* Usually worth it from roughly $50k a month in spend with a third-party attribution tool. Breakeven CPA is the most you can pay for a customer; scaling CPA is what you would like to pay (see [[LTGP to CAC Ratio and the CAC Death Spiral]]).
5. **Compare daily against the tier.** Above your scaling target, keep pushing budget; below it, pull back or fix creative. Platform attribution windows are short and many products have longer buying journeys, so do not scale off the platform figure alone (see [[Click vs View-Through Attribution]]).
6. **Reset after any offer change.** A discount lowers margin, so breakeven rises. Two ways to set the new target:
   - *Gap method:* keep the same distance above breakeven you were scaling at before.
   - *Default method:* new breakeven plus one.

## Example
Say you sell a $50 phone accessory and it costs $15 delivered (hypothetical). Margin is 70% and breakeven about 1.43, rounded to 1.5. If you also charge $5 shipping, revenue per order is $55 and margin rises to about 73%.

You had been scaling at a 2.0 target, 0.57 above the old breakeven. Now you launch a discount that cuts margin to 55%, so breakeven becomes about 1.82. Using the gap method, the new target is about 2.4. Scaling the discounted offer at the old 2.0 target would quietly lose money (full worked numbers in [[Checking Whether a Discount Is Profitable]]).

**Margin as a lever.** Price points and shipping costs move the return you can achieve. As a rough guide, gross margin around 55% is a bare minimum for paid acquisition and above 60% is more comfortable. Higher-AOV products can live with a lower percentage margin; products under about $60 AOV usually need a higher one.

**Check against reality.** Re-run the numbers weekly rather than daily, and confirm them against actual profit in the bank account, not a calculator or a dashboard that is not connected to your books.

## Common mistakes
- Using net margin or product-only margin instead of gross margin.
- Folding fixed costs into the margin.
- Forgetting to add charged shipping to revenue.
- Not resetting breakeven after a price, cost or offer change.
- Judging only on platform ROAS when organic revenue is mixed in.
- Assuming every brand needs a 3x ROAS.

## Related
- [[Setting a Target ROAS - Breakeven Plus One]] - turning breakeven into a scaling target
- [[Checking Whether a Discount Is Profitable]] - the full discount math
- [[Contribution Margin and Variable Costs]] - the cost stack behind gross margin
- [[Click vs View-Through Attribution]] - why platform ROAS needs a sanity check
- [[Glossary - Metrics & Media Buying]] - definitions of ROAS, MER, CPA and related terms
