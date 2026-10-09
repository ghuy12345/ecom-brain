---
title: "Contribution Margin and Variable Costs"
topic: "11 Finance & Unit Economics"
stage: beginner
tags: [contribution-margin, variable-costs, unit-economics, first-order-economics, payback]
summary: "How to build a true per-order contribution margin from every cost that moves with revenue, and why first orders and repeat orders need separate cost stacks."
---
# Contribution Margin and Variable Costs

## What it is
Contribution margin is the money left from an order after you subtract every cost that rises and falls with sales. Profit is a different number: it is what remains after overhead such as salaries, rent and software as well. You make scaling decisions on contribution margin, because it tells you how much each extra order actually adds to the pot that pays for overhead.

- Contribution margin ($) = revenue minus variable costs
- Contribution margin (%) = (revenue minus variable costs) / revenue

Without an honest version of this number you cannot say how much you can afford to pay for a customer, whether more ad spend will make you richer or poorer, or why a record revenue month left the bank account thin.

## When to use it
- Before you set any ROAS or CPA target (see [[Breakeven ROAS and KPI Tiers]]).
- When you build a cohort model and need per-order margin inputs.
- Whenever a cost line changes: a new supplier price, a new fulfilment partner, a fee that scales with ad spend.
- When you are deciding whether losing money on the first order is acceptable.

## How (steps)
1. **List every variable cost per order.** Use delivered cost, not factory cost:
   - Product cost including packaging, inbound freight and duties.
   - Pick, pack and shipping to the customer.
   - Payment processing. Card fees on a standard store plan usually land a little under 3% plus a small fixed fee per transaction; round to about 3% for quick models.
   - App and subscription-platform fees charged as a share of revenue (often around 0.5-1%).
   - Any team, freelancer or agency fee that is billed as a share of what you spend on ads. Because it moves with spend it is a variable cost, not overhead.
   - Optionally, an allowance for refunds and returns, so the model errs on the safe side.
2. **Split the stack into first-order and repeat-order versions.** Customer acquisition cost and any fee tied to ad spend belong only to the first order. A repeat order carries product, delivery and processing costs but no acquisition cost, so its margin is much higher.
3. **Calculate both margins.** Next, work out how many repeat orders, or how many days, are needed to recover any loss on the first order.
4. **Set a payback window and treat it as an operating rule.** Around 90 days is a common choice, picked for cash reasons rather than accounting purity. A negative first order is only rational if the modelled contribution inside that window clearly exceeds the loss, with a safety buffer.
5. **Keep the cost list in one place** and update it whenever a supplier, carrier or fee changes.

## Example
Say you sell a skincare kit for $100 (all numbers hypothetical):

| Line | First order | Repeat order |
|---|---|---|
| Delivered product cost | $35.00 | $35.00 |
| Processing (~3% + fixed fee) | $3.30 | $3.30 |
| App/subscription fee (1%) | $1.00 | $1.00 |
| Acquisition cost | $40.00 | - |
| Spend-linked fee (5% of $40) | $2.00 | - |
| **Variable costs** | **$81.30** | **$39.30** |
| **Contribution margin** | **$18.70 (18.7%)** | **$60.70 (60.7%)** |

Now suppose acquisition cost climbs to $70, which also lifts the spend-linked fee to $3.50. The first order loses $12.80. If that customer buys once more within 90 days, the 90-day contribution is roughly $47.90, so the business is still healthy. If they never return, every new customer is a loss.

At scale the "small" lines matter. Missing processing fees, platform fees and spend-linked fees can hide tens of thousands of dollars a month in a brand doing seven figures monthly.

## Common mistakes
- **Treating profit and contribution margin as one number.** Overhead belongs below contribution margin; mixing them distorts every target built on top.
- **Using raw product cost.** The landed, delivered cost is the real one.
- **Forgetting the hidden lines:** processing, subscription-platform fees and percentage-of-spend fees.
- **Averaging first and repeat orders together.** The blend hides that acquisition orders and repeat orders behave like two different businesses.
- **Double-counting.** If processing fees are already inside your cost-of-goods figure, do not subtract them again elsewhere in the model.
- **Calling a cost "fixed" because the invoice is monthly.** If the amount scales with sales or spend, it is variable.

## Related
- [[Reading an Ecommerce P&L]] - where contribution margin sits in the full profit waterfall
- [[Cohort LTV Modelling]] - uses first-order and repeat-order margins as its core inputs
- [[Breakeven ROAS and KPI Tiers]] - turns margin into the minimum return your ads must hit
- [[Stress-Testing Unit Economics]] - checks how fragile the margin is when costs move
- [[Glossary - Ops, Finance & Sourcing]] - definitions of COGS, contribution margin and related terms
