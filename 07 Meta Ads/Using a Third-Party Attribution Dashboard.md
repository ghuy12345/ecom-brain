---
title: "Using a Third-Party Attribution Dashboard"
topic: "07 Meta Ads"
stage: scaling
tags: [attribution, triple-whale, multi-channel, new-customer-roas, tracking]
summary: "How to read a third-party attribution dashboard by channel and model, what it is not for, and how to clean up tracking after a busy season."
---
# Using a Third-Party Attribution Dashboard

## What it is
Ad platforms grade their own homework. A third-party attribution tool (Triple Whale and similar) sits on your store data, sees every channel at once and lets you switch between attribution models: click-through only, click plus view, first click, last click, and a survey-driven incrementality or "total impact" model. It is a cross-check and a channel-comparison tool. It is not an accounting system and it is not precise at ad level.

## When to use it
- Once you run more than one paid channel (Meta plus Google, email, TikTok) and need to compare them.
- When you want new-customer ROAS rather than blended ROAS.
- Facebook-only brands at modest spend usually do not need a premium tool yet.

## How (steps)
1. **Set the attribution window to about 14 days.** Leaving it on lifetime gives nonsense figures.
2. **Judge channels, and at most campaigns.** Survey-driven models drop any revenue they cannot tie to a campaign into a general bucket, so the totals look right while the ad-set and ad rows are off. For ad-level decisions inside Meta, use Meta's own numbers, because that is what delivery optimises on.
3. **Pick models per channel.**
   - Meta, TikTok, Snapchat, Pinterest and similar: use click-through numbers alongside the incrementality model. Prefer click-through over click-plus-view even though the latter matches the platform more closely.
   - Google: set click-through, first-click and last-click side by side; bring in the incrementality model only when YouTube or display is running.
4. **Read Google correctly.** Branded search is rarely incremental, so very high branded ROAS misleads. For shopping campaigns, first-click ROAS at or above last-click suggests the campaign is prospecting (finding shoppers who later convert elsewhere); a much higher last-click figure means it mostly catches demand that already existed. When first-click, click-through and new-customer ROAS all meet target, treat it as incremental and keep scaling.
5. **Track new-customer ROAS.** A platform ROAS of 2x can fall below 1x on new customers when the ads keep re-buying your existing customers. This matters most for subscription and established brands; filter out existing subscribers where you can.
6. **Use incrementality to rank top-of-funnel channels against one another.** Treat it as directional; it improves with more survey responses. YouTube, for example, often shows weak in-platform returns but a strong incrementality score.
7. **Investigate big gaps.** If the tool shows far lower ROAS than Meta, the likely causes are heavy view-through credit or weak incrementality, and run the checks in [[Click vs View-Through Attribution]].
8. **Judge scaling on blended results first,** then use platform numbers for ad-level choices.

## Keep it out of your P&L role
Attribution tools mishandle bundles, tiered pricing and true COGS, and they never see overheads. Profit comes from your accountant's P&L and your own contribution margin calculations. Use the dashboard for "which channel is earning its budget", not for "is the business making money".

## Post-season tracking clean-up
After a peak season, check for double-counted revenue. The usual cause is the store's native pixel integration and a separate tracking app both firing purchase events. Keep only the native platform integration and one attribution tool. Server-side tracking is mostly worth it when there are genuine tracking gaps, a third-party checkout, or category restrictions on pixel data (common in health and wellness); otherwise it rarely improves performance.

## Example
Say a supplement brand's dashboard shows Meta at 2.4x click-through and Google at 5.1x last-click. Switching Google to first click drops it to 1.6x, and most of its revenue is branded search. The brand keeps Google's branded budget lean and shifts incremental budget to Meta, where new-customer ROAS holds near target.

## Common mistakes
- Making ad-level kill decisions from dashboard ad rows.
- Leaving the window on lifetime.
- Treating blended ROAS as proof that paid ads are working when much revenue is organic.
- Running two trackers and believing the inflated total.
- Paying for a premium tool before you run multiple channels.

## Related
- [[Click vs View-Through Attribution]] — the Meta-side attribution checks
- [[Reading an Ecommerce P&L]] — where profit is actually measured
- [[Brand Search and Branded Shopping Campaigns]] — why branded returns mislead
- [[Is Performance Max Incremental]] — Google incrementality in depth
- [[Cohort LTV Modelling]] — why new-customer value matters
