---
title: "Reading Split-Test Results - Sample Size and Power"
topic: "06 Landing Pages, CRO & Funnels"
stage: intermediate
tags: [split-testing, sample-size, statistical-power, segments, noise]
summary: "A split test is decided by order count, not days: use a floor of about 300 orders per variant (and per segment you slice), ignore early swings, and distrust dashboard significance badges."
---
# Reading Split-Test Results - Sample Size and Power

## What it is
The rules for deciding when a split-test result is real. Two ideas matter. **Significance** says the difference you see is probably not chance. **Power** says the result is likely to hold going forward. Many testing dashboards display "significance" after a tiny amount of data (sometimes after around a hundred visitors and a handful of orders). That badge is not the same as an adequately powered test, and stopping early is more likely than not to crown the wrong version.

Early test data behaves like a few coin flips. Ten flips can easily land eight heads; that does not make the coin biased. Visitor intent also swings from day to day, so a few strong days can make any variant look brilliant.

## When to use it
- Any time you are tempted to call a test.
- Before slicing a result by device or customer type.
- When a stakeholder points at a big early lift or loss.

## How (steps)
1. **Set the stopping rule by orders, not days.** A common rule of thumb is roughly 300 orders in each variant, with 400-500 being safer; the exact figure depends on the store. To trust a 10-20% lift in conversion, you need far more, on the order of a thousand conversions per variant (at a 2.5% conversion rate that is roughly 40,000 sessions per side).
2. **Apply the floor to every segment.** If you filter to mobile, desktop, new or returning visitors, each slice needs its own large sample. A segment with 20 orders is unreadable however big the gap looks.
3. **Use a significance calculator,** feeding in the visitor and conversion counts (or profit per visitor) yourself, instead of trusting a badge.
4. **Remove the opening spike.** Use the trend chart's date filter to drop the first sessions, which often show an artificial near-100% conversion.
5. **Read revenue and profit, not just conversion.** Check AOV, revenue per visitor, margin and total profit.
6. **Expect crossovers.** Conversion lines often swap places several times over weeks. Early differences in AOV usually fade, except where the variant was designed to change the offer.
7. **Discount "incremental profit".** Dashboards inflate it, because part of those sales would have come through the original page regardless.
8. **Keep traffic clean.** Email traffic hitting a test page contaminates results; tests are cleanest on pages that receive only cold paid traffic. Returning-visitor data is unreliable early, before the tool has tagged people.
9. **Know the alternative.** If you lack the volume, test pages through the ad account instead: if the new page lowers CPA and clears your ROAS target, scale it without waiting for significance (see [[Testing Landing Pages Through Ad Spend]]).
10. **Use a simple status convention:** "paused" means a winner is waiting for rollout; "stopped" means the winner is already live.

## Example
Hypothetical read of one test at three checkpoints. At about 100 orders per variant, variant B shows a strong conversion lead and looks like a clear winner. At 200 orders the lines are flat and the test looks pointless. At around 300 orders, variant C, which had been trailing, shows a steady profit lead of roughly 10-15%, and B has dropped near the bottom. Each extra hundred orders changed the story. Shipping B at 100 orders, or cancelling at 200, would both have been wrong.

A second case: a mobile-only change shows "no difference" on the desktop filter. Of course it does; desktop visitors never saw it.

## Common mistakes
- Declaring a winner after roughly 100 orders.
- Abandoning a test because it looks flat at 200 orders.
- Believing a significance badge earned on ten orders.
- Peeking daily and stopping the first time it looks significant, which inflates false positives.
- Reading segment results with tiny samples.
- Running multivariate tests (three or more arms) on modest traffic; split three ways they can take months.
- Calling a loser after a couple of dozen visitors; a few high-AOV orders can flip it.

## Related
- [[What CRO Is and Is Not]] — why classic split testing suits only larger stores
- [[Split-Test Setup, QA and Shipping Winners]] — making sure the data is trustworthy
- [[Testing Landing Pages Through Ad Spend]] — the faster route for smaller accounts
- [[Reading an Ad-Driven Landing Page Test]] — reading tests run in the ad account
- [[What to Split-Test First]] — choosing tests worth the sample size
