---
title: "Reading an Ad-Driven Landing Page Test"
topic: "06 Landing Pages, CRO & Funnels"
stage: intermediate
tags: [landing-page-testing, stop-rules, aov, conversion-rate, scaling]
summary: "Read a page test run in the ad account with 7-day click data, a spend floor of 2-3x target CPA, at least three to seven days, conversion rate and AOV together, and the control analysed first; then scale the winner in stages."
---
# Reading an Ad-Driven Landing Page Test

## What it is
How to judge a landing page test that is funded through your ads instead of a split-testing app. Because these tests make real sales while they run, the question is not "is this statistically significant?" but "is this ad-plus-page combination beating your target, reliably enough to scale?" Getting the timing and stop rules right matters, because new pages often start slowly and then outperform.

## When to use it
- During and after any test set up as in [[Testing Landing Pages Through Ad Spend]].
- When deciding whether to kill, extend or scale a new page.

## How (steps)
1. **Analyse the control first.** Know the existing page's conversion rate, AOV and CPA over the same period so you can attribute differences. If your control runs at much higher spend, expect its conversion rate to be somewhat lower than a small test's; note that before comparing.
2. **Switch to 7-day click attribution.** Purchases that disappear under click-only attribution were view-through. Count those days as spend without a purchase.
3. **Add custom columns** for AOV (purchase value over purchases) and conversion rate (purchases over landing page views).
4. **Respect the spend floor.** Do not judge before the test has spent roughly 2-3x your target CPA (with a $38 CPA target, roughly $76-114). Do not run page tests at very small spend: you cannot read much below about $100/day per test ad set, and larger accounts should start at $150-200/day.
5. **Respect the time floor.** Do not judge before day three; new funnels often take that long to start. When budget allows, give pages five to seven days, since results can arrive late.
6. **Resolve the conflict between the two floors.** Five to seven days at $100/day is well above 3x CPA. Lean toward giving it time when you have test budget to spare and strong research behind the page; cut sooner when money is tight. Whichever you choose, a few empty days at the start are not grounds to kill a page, but hundreds of dollars spent with zero sign of life are.
7. **Judge conversion rate and AOV together.** Multiply them (or compare revenue per session). A page can triple conversion while lowering AOV and still win clearly. Compare rates, not total purchase value, when spend differs.
8. **Remember a cheaper entry can be fine** for repeat-purchase or subscription products, where first orders are naturally small.
9. **Scale only on trailing performance.** When the last three days all run well above target, raise the test ad set's budget in stages over successive days (for example $100, $150, $200, $300), and scale the old version down if it declines. A single strong day does not justify doubling the budget while the rolling ROAS is still under target.
10. **Next moves after a win:** lift AOV back toward the control's level while holding conversion, then test offers on the new page.
11. **Test personalised pages for at least seven days** and keep specificity balanced with broad enough appeal that you do not alienate the rest of the traffic.

## Example
Hypothetical run: nothing sells for the first three days; day four brings several orders, day five is quiet, and days six to eight each convert at several times the control's rate. Control: 3% conversion x $100 AOV, a score of 300. Test: 7% x $65, about 455. The test also roughly halves cost per purchase. Because the trailing three days are well above target, budget steps up daily. Had the team cut at day three, they would have killed the best page in the account.

Counter-example: after four days the test has nine purchases and the control six. That is not a result; it is far too few orders to conclude anything.

## Common mistakes
- Judging on view-through purchases.
- Shutting a well-researched page off at twice target CPA with no sale yet, when there was budget to keep going.
- Comparing control and test conversion without noting their very different spend.
- Comparing total purchase value instead of rates.
- Doubling budget after one strong day.
- Treating one strong day in a weak account week as proof.

## Related
- [[Testing Landing Pages Through Ad Spend]] — how the test is set up
- [[Revenue and Profit Per Session]] — combining AOV and conversion rate
- [[Budget Increase Rules for Evergreen Scaling]] — staged scaling after a win
- [[Click vs View-Through Attribution]] — why click-only data here
- [[Reading Performance Swings and Stabilising Volatility]] — not overreacting to single days
