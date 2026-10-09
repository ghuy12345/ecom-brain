---
title: "Stress-Testing Unit Economics"
topic: "11 Finance & Unit Economics"
stage: intermediate
tags: [unit-economics, scenario-modelling, aov, cogs, cac, ltv]
summary: "How to push your cohort model through worse-case scenarios and tell which weak metrics you can fix and which ones make a business hard to scale."
---
# Stress-Testing Unit Economics

## What it is
A stress test runs your real numbers through pessimistic scenarios to see whether the business still makes contribution profit within an acceptable payback window. It also sorts your weak metrics into two piles: ones you can realistically fix, and ones that are close to fatal. You cannot fix everything at once, so the goal is to find the one lever that matters most and work on the easiest high-impact fix first.

A low ad-account ROAS is not automatically a problem. The only question that matters is whether the model earns contribution profit inside your payback window.

## When to use it
- Before scaling spend significantly.
- Before relying on payment terms or credit to fund growth (see [[Cash Conversion Cycle]]).
- When choosing between projects: new creative, a price change, a new supplier, a subscription offer.
- When launching a low-priced product or subscription.

## How (steps)
1. **Load real inputs.** AOV, CAC, margin and the month 0-12 LTV curve from your cohort model (see [[Cohort LTV Modelling]]). Scenario verdicts built on placeholder retention data are worthless.
2. **Run at least three shocks:** CAC up 20%, LTV down 20%, COGS up 5%. Add refund rate up a couple of points and slower payouts if cash timing is tight.
3. **Classify what breaks.**
   - *High CAC* is fixable: better creative and better landing pages.
   - *Weak LTV* is fixable: offer structure, subscription take rate, pricing, first-order vs repeat economics.
   - *Poor COGS* is fixable: raise prices, renegotiate, change manufacturer, cut fulfilment cost. As a rough ceiling, product cost above about 30% of price usually means the price is too low or supplier terms are weak.
   - *Low AOV* is hard to fix. Ad platforms have cost floors (CPM, CPC, realistic CTR and conversion rate), so a cheap product may not leave enough room to buy customers consistently, however good its margin and creative.
4. **Pick the one lever.** Slow payback points to AOV and the offer. Ugly CAC points to creative and pages. Crushed margin points to pricing and COGS.
5. **Consider trading CAC for LTV.** A change that raises CAC can still be the right move if it lifts take rate and LTV enough to shorten payback.
6. **Keep a buffer.** In a cohort-payback model, holding first-order ROAS around 0.7 or higher leaves room to absorb CPM spikes, refund spikes and creative fatigue.
7. **Remember the cash.** Profitable by month 3 does not mean you can scale freely; acquiring a large cohort needs cash upfront to cover the deficit until payback.

## Example
Say a coffee subscription brand has a $60 AOV and a $70 CAC, a first-order ROAS of about 0.85 (hypothetical numbers). Its cohort model shows a workable payback. Stress test: CAC rises to $100 (ROAS about 0.6). The model still accumulates a small profit per customer by month 3 and a healthier one by months 6 and 12, so the business survives, but more slowly.

Next scenario: month-1 LTV halves, from 60% to 30%. On a subscription that usually signals a take-rate problem, meaning too few buyers choose to subscribe. The fix is to widen the gap between one-time and subscription pricing, for example raising the one-time price by 10-20%. That may push CAC up by a few dollars, but if far more buyers subscribe, month-3 profit can jump from roughly breakeven to clearly positive at a ROAS near 0.7.

Contrast a $20-a-month subscription with excellent margins. Even with 80% gross margin, the CAC it needs is lower than paid social can reliably deliver. As a rough guide, subscriptions priced below the high-$30s need exceptional margins or a very different structure.

## Common mistakes
- Obsessing over ROAS instead of contribution payback.
- Optimising a low-AOV business endlessly instead of changing the offer.
- Treating COGS as fixed.
- Refusing to raise prices because being cheap feels like the brand.
- Trusting scenario results built on dummy data.
- Assuming month-3 profitability means unlimited scaling.

## Related
- [[Cohort LTV Modelling]] - the model you stress-test
- [[Contribution Margin and Variable Costs]] - the cost stack behind each scenario
- [[Pricing Strategy - Premium, Match or Undercut]] - price changes as a fix for margin and LTV
- [[Subscription Programs - Intro Offers to Recurring Revenue]] - take rate and subscription pricing
- [[Cash Conversion Cycle]] - making sure the cash survives the scenario too
