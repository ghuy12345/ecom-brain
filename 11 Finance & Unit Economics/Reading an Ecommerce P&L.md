---
title: "Reading an Ecommerce P&L"
topic: "11 Finance & Unit Economics"
stage: scaling
tags: [profit-and-loss, gross-margin, finance-kpis, amer, cac, scaling-margins]
summary: "How to structure an ecommerce P&L as a waterfall, which finance-grade KPIs to track instead of platform ROAS, and what margins are normal while you scale."
---
# Reading an Ecommerce P&L

## What it is
The profit and loss statement is the scoreboard your ad account has to reconcile with. If the ads look great but the business is not getting healthier, something in between is broken, and the P&L is where you find it. Two truths frame everything here: revenue growth is not profit growth (a smaller brand with a much fatter net margin can out-earn a bigger one), and profit is not cash (see [[Cash Flow Forecasting]]).

## When to use it
- Monthly, as the source of truth for whether scaling is working.
- When platform ROAS and the bank balance tell different stories.
- Before setting margin, CAC or ROAS targets.
- When preparing to hire, raise money or talk about the value of the business.

## How (steps)
1. **Build the waterfall top-down.**
   - Gross revenue, minus refunds and returns, minus discounts, adjusted for shipping collected = **net revenue**.
   - Net revenue minus the full cost of delivery = **gross margin**. Delivery cost means landed product cost, duties, freight, pick and pack, shipping to the customer, transaction fees and a refund/discount allowance. Warehouse staff who pick orders belong here, converted to a per-order cost.
   - Gross margin minus marketing (ads, influencers, variable content production) = **contribution margin**.
   - Contribution margin minus operating expenses (people, software, space) = **EBITDA**.
   - EBITDA minus interest = **net profit**. Interest never sits inside operating expenses.
2. **Track gross-to-net separately.** Accounting tools often show only net revenue, which hides whether growth came from more sales, fewer refunds or less discounting. Your three quiet revenue levers are lower refunds, less unnecessary discounting and not undercharging for shipping.
3. **Work from true gross margin rather than product margin.** Price less manufacturing cost can look like 70% while the fully loaded gross margin is closer to 25%. Targets built on product margin are wrong from the start.
4. **Back-solve your targets.** If you want 20% net profit and operating expenses run at 15% of revenue, contribution margin must reach about 35%. Always confirm which "contribution margin" a colleague means before comparing numbers.
5. **Split the P&L by customer type.** Build a first-time-customer P&L next to the returning-customer one. Repeat revenue flatters the blended view and can hide an acquisition engine that is losing money.
6. **Report finance-grade KPIs** alongside platform metrics:
   - **CAC** is total ad spend divided by new customers from your store back end (not platform-attributed CPA, and not split by channel).
   - **aMER** (acquisition marketing efficiency) = new-customer revenue / ad spend.
   - **New-customer profit contribution** is new-customer revenue minus their COGS minus ad spend.
   - **LTGP:CAC** over a fixed window (see [[LTGP to CAC Ratio and the CAC Death Spiral]]).
7. **Have an accountant own the P&L.** Attribution dashboards are built for channel attribution; they handle bundles, tiered pricing and true COGS poorly. Never let one stand in for your books (see [[Using a Third-Party Attribution Dashboard]]).
8. **Diagnose from the top.** When a line misses target, the cause sits somewhere above it in the waterfall.

## Example
Say a home-goods brand books $200k revenue on $50k ad spend: a blended 4x that looks comfortable. But $60k of that revenue came from returning customers. New-customer revenue is $140k, so aMER is 2.8x, which may be below the brand's breakeven once true gross margin is applied. The P&L split shows acquisition is barely paying for itself while repeat buyers carry the month.

**What is normal while scaling.** Front-end margins of roughly 10-13% alongside high fixed costs are common in a growth phase, and spending around 10% of revenue on team and tools is a reasonable rule of thumb. Category changes these numbers. Keep operating expenses roughly flat as revenue grows; ecommerce growth is driven by marketing, not headcount, so that is where margin expands.

**Valuation as rough context only.** Rough estimates people quote put a standard ecommerce brand at about 3x EBITDA and a subscription or high-LTV brand from about 8x EBITDA, with maturity, team structure, recurring revenue, trendiness and retail presence moving the figure. Treat these as estimates and conversation starters, not benchmarks or a plan.

## Common mistakes
- Setting KPIs from product margin instead of fully loaded gross margin.
- Putting interest or fulfilment labour into operating expenses.
- Judging the business on blended ROAS when returning revenue is a big share.
- Using an attribution tool or an unconnected dashboard as your P&L.
- Scaling revenue and hoping margin will expand later; it rarely does on its own.
- Letting headcount grow in step with revenue.

## Related
- [[Contribution Margin and Variable Costs]] - building the per-order cost stack that feeds the waterfall
- [[LTGP to CAC Ratio and the CAC Death Spiral]] - the governing ratio read off the first-time-customer P&L
- [[Cash Flow Forecasting]] - why a profitable P&L can still run out of cash
- [[Auditing an Ad Account]] - uses the normalised P&L to check data integrity
- [[Using a Third-Party Attribution Dashboard]] - what attribution tools are and are not for
