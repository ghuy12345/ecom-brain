---
title: "Budget Increase Rules for Evergreen Scaling"
topic: "07 Meta Ads"
stage: intermediate
tags: [meta-ads, scaling, budgets, change-log, stabilisation]
summary: "Entry conditions, step sizes and stabilisation rules for raising evergreen budgets: flat steps of about 20% for smaller or less consistent budgets, steps sized by distance above KPI for larger stable ones."
---
# Budget Increase Rules for Evergreen Scaling

## What it is
Once the account qualifies to scale (see [[Meta Scaling Decision Tree]]), you still have to decide how big each step is and how long to wait between steps. Evergreen campaigns, the always-on ones that run outside sale periods, need smaller and steadier steps than sales, because there is no deadline forcing you to capture demand fast and every step pushes delivery toward colder people.

## When to use it
- Any time you raise budget outside a promotion.
- When a winning ad or campaign is clearly above target and you want to capture more volume.
- Not during sale periods, where faster intraday steps apply.

## How (steps)
1. **Confirm entry.** Two to three consecutive days above KPI across the account, on click-based data.
2. **Increase the campaign budget; do not clone high-spend ads.** Duplicates compete with the original and reset learning.
3. **Choose the step size** using the conditions below.
4. **Let it settle.** After a scale-up, give the account roughly 3-4 days before judging, unless it falls clearly below break-even. Drastic cuts during this window can spiral performance further.
5. **Keep a change log.** Record every budget change, launch and pause with the date, so you can explain later swings instead of guessing.
6. **Respect per-ad ceilings.** Every ad has a spend level beyond which it degrades. Continued growth past that point becomes a question of creative supply: fresh ads that can carry more spend, not bigger steps on the old one. Design ads with headroom in mind.
7. **Watch frequency and attribution** after each step, so you can tell genuine performance from view-through inflation.
8. **Do the arithmetic when a winner drops on scale.** If a winning ad falls from 3x to 2.4x after doubling its spend, ask whether the higher spend at the lower return produces more absolute profit. Include customer lifetime value in the target rather than defending a fixed ROAS.

## Choosing the step size
Both rules below are valid; which one fits depends on the size and consistency of your budget. The percentages (20%, 50%, 100%) are rough estimates, not benchmarks; tune them to your account.

**Flat steps of about 20%**
- Raise 20% and wait. Some operators step every 24 hours once in protocol; others step every 2-3 days. Waiting 2-3 days is the safer choice when the account is volatile, when you are new to the product, or when the scale-up just ran into a settling period.
- Best for: smaller budgets, accounts with uneven day-to-day results, teams that want one simple rule. On smaller spend you can comfortably afford jumps of about 20% at a time, provided the account is above KPI.

**Steps sized by distance above KPI**
- Just above KPI: +20%.
- About 50% above (target 2x, hitting 3-3.5x): +50%.
- Far above (target 2x, hitting 5x or 50-100% over): up to double.
- Best for: larger budgets with stable, consistent results, where enough daily purchases make the distance above KPI a reliable signal. Even here, let a day and several purchases pass before any doubling.

**At very large budgets** (tens of thousands a day), shrink any step: proportional steps are rarely above 20% and almost never 100%, and flat steps can drop to 10-15% or even 5%.

In short: smaller or less consistent budgets take flat steps of about 20% while above KPI; larger, stable budgets size the step by how far above KPI they are; the very largest step slowly whichever rule they use.

## Example
Say a candle brand spends $500/day at a target of 2x and has run 3.2x for three days with 75% click-based purchases. At this size it uses flat steps, raising 20% to $600 and repeating every two days while it stays above target. A couple of months later at $3,000/day, with results now stable from day to day, it switches to steps sized by distance above KPI: a week at 3.1x earns a 50% step, while a week just above target earns 20%. It also begins briefing new concepts, because its top ad loses efficiency above about $1,200/day.

## Common mistakes
- Using sale-sized steps on evergreen campaigns.
- Duplicating a high-spend ad to "scale" it.
- Judging a scale-up on the next day.
- Treating a fixed ROAS threshold as sacred when absolute profit shows otherwise.
- No change log, so nobody knows what caused a drop.

## Related
- [[Meta Scaling Decision Tree]] — when you qualify to take a step
- [[Intraday Budget Scaling for Sale Periods]] — why sale steps differ
- [[Reading Performance Swings and Stabilising Volatility]] — reading the days after a step
- [[Isolating Winners in a Dedicated ABO]] — scaling single winners in their own ad sets
- [[Stress-Testing Unit Economics]] — checking that more spend at lower ROAS still pays
