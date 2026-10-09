---
title: "Cohort LTV Modelling"
topic: "11 Finance & Unit Economics"
stage: intermediate
tags: [ltv, cohort-analysis, cac, payback, promo-cohorts, spreadsheet-model]
summary: "How to build a cohort LTV spreadsheet in dollars to see how fast each month's new customers pay back, and how much you can afford to outspend competitors."
---
# Cohort LTV Modelling

## What it is
A cohort LTV model tracks a group of customers who all joined within one period (usually a month) and records the money they generate in month 0, month 1, month 2 and onward. Its purpose is practical: it tells you how aggressively you can spend to acquire customers while still ending up with contribution profit. The brand that can afford to pay most for a customer wins distribution, and distribution tends to win the market.

Cumulative cohort margin decides whether to scale: if it turns positive fast enough, scale. If it does not, you are buying revenue.

## When to use it
- Before deciding whether a negative or breakeven first order is acceptable.
- When setting a maximum CAC or CPA based on lifetime value.
- After a big promotion, to judge whether the customers it brought in were worth it.
- As the input for cash timing (see [[Cash Conversion Cycle]]).

## How (steps)
1. **Get CAC from the right sources.** New-customer counts come from your store platform (filtered to first-time customers), not from the ad platform, whose attribution is distorted. Use the ad platforms only for spend. CAC = total ad spend for the period / new customers in that same period. CPA (cost per platform-reported purchase) is a different number; mixing them breaks the model.
2. **Pull cohort revenue by month.** Use a cohort or LTV analytics app to get months 0-12 for each acquisition month. Dedicated LTV tools tend to be more accurate here than general attribution dashboards.
3. **Model dollars, not heads.** Retention counts people who stay; LTV counts money. A brand can keep many customers who spend little, or fewer customers who spend a lot. Express each month as a percentage of month-0 revenue (month 1 at 60% means every $1 of first-month revenue brings another $0.60).
4. **Separate first-order and repeat-order inputs.** First orders often include free gifts, intro bundles, deeper discounts and one-time upsells that never recur, so AOV and margin both change afterwards. A razor brand that ships the expensive handle first and only blades later is the classic case.
5. **Build the sheet.** Columns per month: LTV %, revenue (LTV % x AOV), margin (revenue x contribution margin %, minus CAC in month 0, times customers), cumulative revenue, cumulative margin. Inputs: first-order and repeat AOV, first-order and repeat margin, CAC, number of customers acquired (your scenario lever), COGS plus processing. Lock formula cells.
6. **Read three numbers.** Margin in month 0 (is it below or above zero?), the month in which cumulative margin turns positive, and total margin at 90 days.
7. **Set a CPA ceiling from it.** Calculate 3-, 6- and 12-month value per cohort and use the horizon your cash can support to set the most you will pay for a customer. With strong LTV, acquiring at an initial loss can be acceptable (see [[LTGP to CAC Ratio and the CAC Death Spiral]]).
8. **Optional: add overhead.** Divide estimated monthly operating costs by expected transactions to get a per-order cost and add it to the stack. Do not let this step delay decisions.

**Judging promo cohorts.** Heavy-discount periods should be judged on what their customers are worth over time, not on day-one profit. Compare the Black Friday cohort's 90- and 180-day value with a normal month's. Discount buyers and gift buyers often return less, so a promo that looked great on launch day may have bought weaker customers.

## Example
Say a grooming brand has a first-order AOV of $60, an 80% contribution margin before ad cost and a CAC of $70 (all hypothetical). Month 0: $48 margin minus $70 CAC leaves about -$22 per customer. Month 1 brings back 60% of first-month revenue, $36, worth about $29 in margin, so cumulative margin turns positive at roughly +$7 by the end of month 1. The model says the brand can scale, as long as cash covers the month-0 trough.

Real data often shows month 0 slightly above 100% because a few customers reorder inside the same window. A healthy business usually keeps adding meaningful revenue in months 1 to 3. If payback looks poor, change the inputs (offer, AOV, margin, CAC) rather than hoping.

## Common mistakes
- Taking CAC from the ad platform instead of store new-customer counts.
- Calling CPA "CAC".
- Modelling customer counts instead of dollars.
- Assuming the first-order margin equals the repeat margin.
- Treating one-time upsells as recurring revenue.
- Judging a discount period only on first-order profit.
- Over-engineering overhead allocation and never making a decision.

## Related
- [[Contribution Margin and Variable Costs]] - the first-order and repeat-order margins the model needs
- [[LTGP to CAC Ratio and the CAC Death Spiral]] - turning cohort value into a CAC target
- [[Stress-Testing Unit Economics]] - running pessimistic scenarios through the model
- [[Cash Conversion Cycle]] - checking payback against bill due dates
- [[Black Friday and Q4 Offer Strategy]] - promo offers whose cohorts you should judge over time
