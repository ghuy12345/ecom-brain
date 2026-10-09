---
title: "Google Ads Self-Audit and Bottleneck Diagnosis"
topic: "08 Google Ads"
stage: intermediate
tags: [google-ads, audit, diagnosis, conversion-latency, performance-max]
summary: "Diagnose a Google account from the business down, one layer at a time, until you can name the root cause; then fix rather than rebuild, and run a six-point audit to catch the usual leaks."
---
# Google Ads Self-Audit and Bottleneck Diagnosis

## What it is
Two tools. **Top-down diagnosis** finds why performance changed. **A six-point self-audit** catches the structural leaks that quietly distort most ecommerce accounts.

The rule behind both: only touch the account when you can finish this sentence: "This campaign underperforms because [metric] fell; the sub-metric behind it is [X]; the trigger for that is [Y]; and [Y] is the underlying root cause." The common errors are making a change you should not, missing one you should, or piling on many changes for a dip that Google had no part in.

## When to use it
- Performance drops and you feel the urge to "do something".
- Taking over an account.
- A quarterly health check.

## How (steps)
**Three pre-checks**
1. Read the change history: yours, colleagues', anyone with access.
2. Zoom out. No one-day diagnoses; the fewer conversions you have, the longer the window you need.
3. Allow for conversion latency. Google credits a sale to the click date, which means the most recent 3-7 days will always appear weak. Use a "conversions by conversion time" column.

**The ladder: business, then channel, campaign type, campaign, ad or asset group, followed by the metric, the sub-metric, the cause, and finally the root cause.**

*Level 1, the business (often you stop here).*
- Where is spend? If 90% sits on another platform, a revenue dip is probably not Google.
- What changed outside Google: a sale ending, an offer change, a broken site, new creative elsewhere?
- Revenue = sessions x conversion rate x AOV. Lower CVR points to the site; fewer sessions means a channel lost clicks; lower AOV points to merchandising or product mix.
- Is the fallen number attributed, or a real KPI (revenue, contribution, MER)?
- Check against seasonality and your forecast.

*Levels 2-3, inside Google.* Sort campaigns by cost; the culprit is nearly always in the top five. View 90-180 days by week and cycle through cost, conversions, value, cost per conversion, ROAS and CTR to find the inflection date. Repeat at ad group or asset group level. A campaign with 10% of budget barely moves the account.

*Levels 4-5, metric to sub-metric.* CPA = CPC / CVR; clicks = impressions x CTR.
- Efficiency worse, volume flat: CPC or CVR.
  - CPC up: Quality Score, a new competitor (compare auction insights before and after), or pricier auctions after a bid change.
  - CVR down: tracking, a landing page change (price, URL, redirect, upsell, merchandising, the most common cause), a shift in search terms, a learning reset, or an offer change.
- Efficiency flat, volume down: impressions or CTR. Check share lost to budget vs lost to rank. On Shopping, a competitor's price cut explains CTR drops almost one to one.

**Failure modes by campaign type**
- *PMax:* warm/cold drift (brand in search terms, existing customers in the audience report, usually a broken exclusion or a target set too high), feed disapprovals or out-of-stock top sellers, a high target narrowing to warm users, and product bloat resetting learning.
- *Search:* term drift under broad match and smart bidding, a new competitor, a squeezing target, Display network left on.
- *Shopping:* the PMax list minus warm drift, plus feed errors, title changes, too many products and search-partner spend.

**Fix, don't rebuild.** Rebuilds reset learning and start a decline-change-decline loop. Apply one fix, give it time, then choose the next. Stack fixes only when things are dire. Be honest about impact: a headline tweak will not fix a business problem.

**The six-point self-audit**
1. *Brand leakage.* Check search terms in every cold campaign for your brand. Brand leakage often means most "prospecting" conversions are existing or warm customers, with brand clicks costing dollars there instead of cents.
2. *Merchant Center health.* Disapprovals under 5%; remove what cannot be fixed.
3. *Channel mix.* Below about $50K/month, put nearly all spend through product ads.
4. *Attribution windows.* Match click, engaged-view and view windows to real time-to-purchase. High-ticket, slow decisions (AOV above roughly $600) keep long windows; fast, low-ticket purchases need tighter ones. Over-tight windows over-credit brand.
5. *Consolidation.* Merge campaigns split without a business reason.
6. *Demand Gen.* Off, unless running as a small controlled test.

## Example
Say a store spends $15K/month and Google revenue dips. Business level: Google carries most of the paid spend, sessions are flat and conversion rate fell on one date, the same day a free-shipping threshold was raised. That is the first fix, and no bid is touched.

The six-point audit on the same account then finds roughly 70% brand queries in the PMax search terms. Adding a brand exclusion and negatives and launching a small brand search campaign lowers cold PMax spend and raises new-customer revenue, even as overall Google-attributed ROAS drops. The lower number is the honest one.

## Common mistakes
- Diagnosing from the bottom up.
- Reacting to the last three days before conversions have landed.
- Adjusting settings all day when the setting was never the cause.

## Related
- [[Quality Score and CTR as Diagnostics]] — reading CPC and CTR changes correctly
- [[Auditing an Ad Account]] — the cross-platform audit with data integrity first
- [[Diagnosing a Store With Conversion Benchmarks]] — when the root cause is the site
- [[Brand Search and Branded Shopping Campaigns]] — fixing brand leakage
- [[Shopping Feed Optimisation]] — fixing feed-driven failures
- [[Product-Level Reporting and Zombie Products]] — finding which products drive a change
