---
title: "Google Bidding - Manual, Smart and Target ROAS"
topic: "08 Google Ads"
stage: scaling
tags: [google-ads, bidding, smart-bidding, target-roas, scaling]
summary: "Use value-based smart bidding by default, understand how target ROAS narrows toward warm buyers as you raise it, and change targets and budgets in steps tied to new-customer revenue."
---
# Google Bidding - Manual, Smart and Target ROAS

## What it is
Google offers three families of bidding:
- **Manual CPC / maximise clicks**: you or the system bid for clicks, with no conversion data involved.
- **Expansive conversion bidding**: maximise conversions or maximise conversion value. These chase volume and win auctions you would otherwise lose, effectively reserving a good share of budget for exploration.
- **Restrictive conversion bidding**: target CPA or target ROAS (tROAS). These act like bid caps: efficient and stable, but they test almost nothing new when the target is aggressive.

In almost every case, bidding on conversions is the sensible default. A keyword only tells you the query, not the person; a narrow query can come from a casual browser and a broad one from a ready buyer. Google weighs user-level signals (estimated income, household, home ownership and many more) that no manual bidder can see.

## When to use it
- Choosing a strategy for a new campaign.
- Deciding whether to raise a ROAS target to "improve efficiency".
- Diagnosing a campaign whose spend has slowly shrunk while it still "hits target".

## How (steps)
**1. Match strategy to data.**
- No conversion history (brand-new account): manual CPC or maximise clicks.
- Some data: maximise conversion value to gather more.
- Enough conversions at campaign level: move to tROAS if you need stability.
In ecommerce, use value-based bidding about 90% of the time. Maximise conversions chases the lowest CPA, which tends to mean the cheapest, least profitable product.

**2. Understand what tROAS does.** It learns from conversions inside the campaign, weighting recent ones more, and bids on people who resemble past buyers. It needs real volume: feed it only 5-10 conversions and the sample is too small to trust. New campaigns inherit very little from the rest of the account. A higher target stabilises daily results; it does not raise average performance. And because CPA depends on CPC and conversion rate, both of which have limits, you cannot push ROAS up indefinitely.

**3. Know the two risks of raising tROAS.**
- *Shrinking spend and a bias loop.* A higher target narrows bidding to people closest to past buyers, so only they convert, so only their data comes back, narrowing it further. The exploration budget drops toward zero. The symptom is a campaign that has sat on a high target for months, hitting it while spend and volume slowly decay. If ROAS then dips below target, spend pulls back, conversions fall, modelling worsens and it spirals. Pull the target back decisively, not timidly.
- *Bottom-of-funnel capture.* Many Google buyers are already warm from Meta, email or a previous visit. A high target teaches the model to bid hard on them. Very high conversion rates on generic-looking queries (say 80%) are a red flag that you are re-capturing warm users.

**4. Decide whether raising is safe.**
- Little spend on other channels: raising is generally fine.
- Heavy spend elsewhere and new customers are the goal: raising increases capture risk.
- Volume is the priority: do not raise.
- Cold-looking campaign (low target, brand negatives, customer exclusions): reasonably safe to add budget.

**5. Guard against warm drift.** Keep brand and existing-customer audiences out of cold campaigns, split campaigns by funnel stage so none can swallow another's audience, and watch new vs returning revenue. Once a campaign settles into warm traffic it is hard to pull back. Changing between tCPA and maximise conversions can change who you reach without touching audiences.

**6. Change things in steps.** There is no fixed "raise X% every Y days" rule. Move targets in small steps and watch spend, CPC, impression share and new-customer revenue. Raise budgets roughly 20% at a time; do not double overnight. Sharp cuts are usually fine. Treat "limited by budget" as a signal, not an instruction ([[Google Ads Interface Basics]]).

**7. Use the extras.** Portfolio strategies share learning across campaigns and allow CPC floors and caps. Smart bidding exploration (Search only) lets bids range 10-30% outside target and is worth enabling. Feeder setups pair a very low-target standard Shopping campaign that reaches searchers nobody else bids on with a high-target campaign that converts them later.

## Example
Imagine a campaign on a 400% target, spending $300/day at 4.6 attributed ROAS, where Meta is the main channel and spend has fallen 20% across two months. Run this test: lower the target to 300%, add negatives for the brand and for customer lists, then assess it over three to four weeks by revenue from new customers and by how steady spend stays, rather than by ROAS.

## Common mistakes
- Creeping the target up until spend dries up.
- Using maximise conversions on a catalogue with very different margins.
- Running a cold Shopping campaign beside PMax, then watching PMax drift into warm traffic and starve the Shopping campaign.
- Judging bidding changes on platform ROAS instead of contribution to profit.
- Doubling budgets or halving CPA targets overnight.

## Related
- [[Setting a Target ROAS - Breakeven Plus One]] — where to set the target in the first place
- [[Breakeven ROAS and KPI Tiers]] — margin maths behind any ROAS target
- [[Is Performance Max Incremental]] — measuring warm capture
- [[Google Ads Account Structure for Ecommerce]] — conversion volume per campaign
- [[Contribution Margin and Variable Costs]] — tying bids to profit, not revenue
