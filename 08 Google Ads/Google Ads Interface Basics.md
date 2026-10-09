---
title: "Google Ads Interface Basics"
topic: "08 Google Ads"
stage: beginner
tags: [google-ads, custom-columns, assets, limited-by-budget, advertiser-verification]
summary: "Five everyday interface skills: building custom columns, reviewing whether assets earn their place, reading 'limited by budget' properly, understanding why you cannot see your own ads, and never missing a verification deadline."
---
# Google Ads Interface Basics

## What it is
A set of small, practical habits in the Google Ads interface that prevent bad decisions. None is complex, but each one regularly causes wasted spend or panic when ignored.

## When to use it
- Setting up reporting on a new account.
- Reviewing sitelinks and promotions before and during a sale.
- When Google flags a campaign as "limited by budget".
- When you search for your own product and your ad is not there.
- When Google emails about advertiser verification.

## How (steps)
**1. Build custom columns.** CPM, conversion rate and AOV are not standard columns (an average CPM column exists, but build your own for consistency).
1. In the campaign view, open columns, modify columns, custom column.
2. Make sure you are in the actual ad account, not a manager account; custom metrics built at manager level can break for other viewers.
3. Name the metric, set the format and a currency for money metrics.
4. Write the formula using the column names the editor expects (for example "Impr." for impressions).
5. Save and apply to a column preset.
Formulas: CPM = cost / impressions x 1,000; CPC = cost / clicks; CPA = cost / conversions; AOV = conversion value / conversions; conversion rate = conversions / clicks. Save separate presets for different jobs, such as account health and feed or creative review.

**2. Review assets, not just add them.** Extensions are now called assets.
1. Open ads and assets, then assets, for the whole account or one campaign.
2. Filter by type (sitelink, promotion, callout).
3. Look at the "added to" column to learn whether each asset is attached at account or campaign level.
4. Add the conversions, conversion value and conversion value / cost columns.
Assets with ROAS well above the campaign average deserve prominence; assets that take spend but never convert should be rewritten or paused. Review monthly, and check promotion assets during sales so expired offers are not still showing.

**3. Read "limited by budget" correctly.** It often means the campaign spends heavily early in the day and runs dry by evening, missing late demand. It is a signal, not an order to spend more. Adding budget, especially in Shopping, can simply raise CPCs for the same traffic.
1. Segment the campaign by hour of day to see spend distribution.
2. Overlay store sessions by hour as a proxy for demand.
3. When spend tails off earlier than demand, increase budget gradually while monitoring CPC, clicks and impression share.
4. Should CPC climb without a matching rise in clicks, undo the increase.
5. Alternatives: a tighter CPA or ROAS target to pace spend, or ad scheduling for specific hours (useful for brand search).

**4. Stop searching for your own ads.** Not seeing your ad is usually smart bidding working, not a fault. In order of likelihood: you are not the profile it is bidding for; you have searched repeatedly without clicking, so Google stopped showing you; or you are excluded (IP exclusion, or your email is in a customer exclusion list). Click your ad a few times if you must check. Only investigate real issues (budget, structure, overspend on existing customers) if several people in your target audience cannot see it and back-end revenue disagrees with the platform.

**5. Treat advertiser verification as urgent.** Missing a verification deadline can switch your ads off, and review takes about a week. Open the verification section under tools and settings, submit the requested business details on day one, and leave room for a rejection and resubmission. Put the deadline in a calendar with an owner. Verification exists for transparency: your name and location may appear in Google's public ads transparency lookup. If you run several accounts, check every one, not only those that received an email.

## Example
Say a campaign spending $1,500/day drops from $140 an hour to $30 an hour after 4pm while store sessions hold until 8pm. A 15% budget increase lifts CPC 14% and clicks only 1%, so it is rolled back and a slightly tighter ROAS target is tested to pace spend across the day instead.

## Common mistakes
- Building custom columns at manager level.
- Adding every sitelink and never checking which ones convert.
- Doubling budget whenever the "limited" label appears.
- Pausing a healthy campaign because you could not find it on your own phone.
- Leaving a verification email unread until the account stops serving.

## Related
- [[Ads Manager Setup - Columns, Benchmarks, Naming and UTMs]] — the equivalent setup habits on Meta
- [[Google Bidding - Manual, Smart and Target ROAS]] — how budget and target changes interact
- [[Product-Level Reporting and Zombie Products]] — reports that use these columns
- [[Ad Account Protection and Payment Hygiene]] — keeping accounts in good standing
- [[Glossary - Metrics & Media Buying]] — definitions of CPM, CPA, AOV and more
