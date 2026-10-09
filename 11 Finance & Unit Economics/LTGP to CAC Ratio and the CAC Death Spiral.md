---
title: "LTGP to CAC Ratio and the CAC Death Spiral"
topic: "11 Finance & Unit Economics"
stage: scaling
tags: [ltgp, cac, unit-economics, amer, cac-target, death-spiral]
summary: "Why lifetime gross profit divided by customer acquisition cost is the ratio that governs an ecommerce brand, how to set a CAC target from it, and how to spot the spiral that kills brands."
---
# LTGP to CAC Ratio and the CAC Death Spiral

## What it is
**LTGP** is the gross profit a new customer generates over a fixed window, after product cost, delivery and transaction fees. **CAC** is total ad spend divided by new customers (from your store back end). Their ratio is the single number most brand failures collapse into: the cost of buying a customer rose while those customers had little reason to come back.

"Lifetime" never ends, so always constrain it. Use 30-day LTGP (close to first-purchase profit) by default, and 90 or 180 days for consumables, subscriptions or strong repeat categories.

| LTGP:CAC | Meaning |
|---|---|
| Under 1 | Losing money on each new customer; fix before scaling |
| 1-2 | Thin; little left for overhead, needs lean costs or big volume |
| 2-3 | Target zone; scale |
| Above 3 | Probably under-spending; push harder unless a constraint stops you |

## When to use it
- Monthly, as the headline health check for acquisition.
- When setting a CAC or CPA target for the ad account.
- During an account audit, to test whether platform numbers reflect reality (see [[Auditing an Ad Account]]).
- When revenue is falling and everyone is blaming creative.

## How (steps)
1. **Calculate CAC and LTGP every month.** Use real cohort data and real historical margins, not a flat margin assumption. Track first-purchase gross profit separately, because it can swing a lot with discount months and product mix even when CAC is flat. Put refunds into LTGP, not CAC.
2. **Back out a CAC target.** CAC target = LTGP / chosen ratio. With $80 of 30-day LTGP and a target ratio of 2, you can pay $40; with $100 of 90-day LTGP, $50.
3. **Pick the horizon by cash and appetite.** Longer windows let you pay more today and earn it back later, but need cash or outside funding. Model it: if allowing CAC to rise 25% brings 30-40% more customers, a longer payback grows the business; when it adds hardly any customers, remain at 30 days.
4. **Sanity-check the CAC floor.** CAC = CPC / conversion rate. A very good case (around 3% conversion and a low CPC) still produces a meaningful floor; operators tend to expect CAC to fall further than it can, while underrating how much offers, bundles and subscriptions can lift LTGP.
5. **Compare platform ROAS with aMER.** aMER is new-customer revenue divided by ad spend. If platform ROAS is several times aMER, suspect view-through credit and spend on existing customers (see [[Click vs View-Through Attribution]]). In an audit, read first-purchase gross profit : CAC on the same bands as the table.
6. **Date-stamp each structural change** (a new creative partner, extra ads, a new channel, a launch) and read it alongside the two numbers.

## Example
**The spiral.** CAC creeps up; a fixed budget buys fewer customers; revenue falls because few customers return; spend is raised to defend revenue; CAC climbs again. Teams usually blame traffic, then creative, then seasonality. Diagnose from the two numbers instead. The pressure is industry-wide: public data reportedly shows the average contribution margin on a first-time customer falling from positive to substantially negative between 2013 and 2022.

**Why CAC keeps rising.** CAC = CPC / CVR and CPC is driven by CPM and CTR, so CPM sits two layers beneath CAC. Ad platforms have to grow revenue, so expect CPMs to rise yearly; to stand still you must lift CTR or conversion rate every year. Paid attention is rented; email, SMS and community lists are owned.

**Brand comparison.** Say two brands each pay $40 CAC and earn $100 first-purchase gross profit. One reaches $130 by day 90, the other $112. The first can pay $45 per customer, buy more of them and still out-earn the second. Benchmark against your category: many brands see modest LTGP growth over a year, while consumables grow far more than one-off purchases like furniture. In low-repeat categories, treat LTGP as first-purchase profit and hold CAC flat against it.

**Funding a ratio below 1.** Three routes: profit from returning customers subsidising acquisition (split the P&L into first-time and returning to check), investor capital, or debt. The last two suit experienced operators only. *General information, not financial advice:* borrowing to fund customer acquisition at a loss adds repayment pressure on top of the payback risk, and small brands carrying that pressure are fragile. Get professional advice first.

## Common mistakes
- Measuring LTV in revenue over an open-ended period.
- Using email-attributed revenue or "% returning customers" as a retention metric; the latter rises when acquisition weakens.
- Assuming a flat gross margin.
- Trusting a platform ROAS that has drifted far above aMER.
- Pulling back when CPMs rise instead of improving conversion and CTR.
- Reading a blended P&L that hides a collapsing first-time-customer P&L.

## Related
- [[Cohort LTV Modelling]] - building the cohort data behind LTGP
- [[Retention Flows and Segmentation]] - raising LTGP after the first order
- [[Auditing an Ad Account]] - using GP:CAC and aMER to test data integrity
- [[Click vs View-Through Attribution]] - why platform ROAS can overstate acquisition
- [[Reading an Ecommerce P&L]] - splitting first-time and returning P&Ls
