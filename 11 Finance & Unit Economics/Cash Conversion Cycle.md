---
title: "Cash Conversion Cycle"
topic: "11 Finance & Unit Economics"
stage: scaling
tags: [cash-conversion-cycle, payback, payment-terms, float, cohort-risk]
summary: "How to line up when cash leaves your account with when each customer cohort pays back, so scaling does not drain the bank before the profit arrives."
---
# Cash Conversion Cycle

## What it is
The cash conversion cycle measures how long your money is tied up between paying for something and getting paid for it:

**Cash conversion cycle = days inventory outstanding + days sales outstanding - days payable outstanding**

For a paid-acquisition brand the practical version is simpler. Ask three timing questions: when does money leave your account, when does money come in, and does each cohort turn cash-positive before its bills are due? Plenty of brands fail with decent ads because the cohort model says "profitable by month 3" while the ad invoice lands in month 0. At scale that gap between spend and payback can run very large.

## When to use it
- Before scaling a channel where the first order loses money or only breaks even.
- When supplier lead times or upfront payment terms are squeezing you.
- When deciding whether to use extended payment terms or credit to fund growth.
- Any time the cohort model and the bank account disagree.

## How (steps)
1. **Find your payback month.** In the cohort model, locate the first month in which cumulative contribution margin turns positive (see [[Cohort LTV Modelling]]).
2. **Write down every real due date.** Ad-platform invoice dates, supplier terms (net 0, 30 or 60), card statement close and due dates. Use the date the bill actually lands, not the month you consider yourself profitable.
3. **Compare the two.** If cohorts go positive before the bills are due, scaling will not drain your cash. If not, choose one or more fixes: raise payback speed (AOV, margin, repeat rate), cut CAC, extend supplier terms, or hold growth to a pace your cash can fund.
4. **Understand the float layers available to you.** Monthly invoicing from the ad platform, longer supplier terms, and paying through a charge card with long interest-free terms can each push cash-out later. Stacked, they can create a gap of roughly three months between spend and payment. The mechanics and costs are in [[Ad Account Billing and Credit Float]].
5. **Build in a buffer.** Until your numbers are proven over several cohorts, aim for cash-positive payback by around month 2, leaving roughly a month of slack before the bill.
6. **Stress-test before scaling.** At minimum: CAC up 20%, early-month LTV down 10%, refund rate up two points, and payouts delayed one to two weeks. If the plan only works in the optimistic case, it does not work (see [[Stress-Testing Unit Economics]]).
7. **Never grow debt faster than fulfilment.** If fulfilment breaks, refunds and chargebacks spike and the float you were relying on collapses.

*General information, not financial advice:* float from invoicing, cards and supplier credit is borrowed time. It is a liability as much as a lever, it carries fees, and the bill is due whether or not the cohort performs. It does not fix a weak offer or messy operations. Verify current platform, card and supplier terms yourself and talk to a finance professional before relying on credit to fund ad spend.

## Example
Say a pet-supplement brand's cohorts keep 60%, 40% and 25% of first-month revenue in months 1, 2 and 3, and its model shows a strong cumulative result by month 3. Now imagine each of those retention figures slips by a few points. In a hypothetical model at large scale, that small slip can swing month-3 cumulative cash from a healthy six-figure positive to a six-figure negative, even though the cohort is still clearly profitable by months 6 and 12. Only the timing moved.

Without float, the month-0 ad bill comes straight out of the bank and the brand has to survive the trough. With invoicing and longer card terms aligned, the bill is paid after the cohort has already turned positive. That is the whole point of managing the cycle, and also why sloppy cohort data is dangerous: a few percent of error compounds into a large cash hole at scale.

## Common mistakes
- Scaling because "month 3 is profitable" without checking bill dates.
- Treating float-funded first orders as profitable; at best they are cash-neutral at payment time.
- Believing card rewards cover the cost of funding fees without doing the arithmetic.
- Using credit to paper over operational problems.
- Forgetting that inventory and COGS still need cash even when ad spend is deferred.
- Planning around the optimistic model instead of a shorter payback.

## Related
- [[Ad Account Billing and Credit Float]] - the billing tiers and the real cost of float
- [[Cohort LTV Modelling]] - where the payback month comes from
- [[Cash Flow Forecasting]] - the wider forecast of cash in and out
- [[Supplier Payment Terms and Incoterms]] - lengthening days payable with suppliers
- [[Stress-Testing Unit Economics]] - scenarios to run before scaling on float
