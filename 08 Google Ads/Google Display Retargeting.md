---
title: "Google Display Retargeting"
topic: "08 Google Ads"
stage: intermediate
tags: [google-ads, display, retargeting, optimized-targeting, customer-lists]
summary: "Run Google Display as a small, cheap reminder campaign to known audiences, with optimised targeting switched off so it never turns into cold display."
---
# Google Display Retargeting

## What it is
A Display campaign aimed only at people who already know you: site visitors or existing customers. Google typically charges Display on clicks, so you can buy many reminder impressions on a known audience and pay only when someone clicks. The effective CPM is often far below Meta retargeting. The value is cheap, repeated presence through the buying cycle, not a stream of attributed sales. Expect few conversions.

The one setting that decides whether this works is **optimised targeting**. Google may switch it on by default or through a recommendation. It expands delivery beyond your list to people it thinks might convert, which quietly turns retargeting into cold display, a format that generally performs poorly for ecommerce.

## When to use it
- You want low-cost reminders to visitors during a long, considered purchase.
- You sell a low-AOV, high-repeat product and want to stay in front of past buyers between orders.
- You inherit Display campaigns and need to check they are not leaking into cold traffic.

## How (steps)
**1. Pick the audience by business model.**
- Low AOV, high repeat rate: target existing purchasers.
- Considered or infrequent purchase (furniture, for example): target site visitors and exclude existing purchasers.

**2. Build the audience.** In the section about how people have interacted with your business, use website visitors (imported GA4 or tag-built audiences) or customer lists. The most reliable route is syncing your store to your email platform, building an auto-updating segment there and syncing it to Google ([[Google Ads Data - Enhanced Conversions and Customer Lists]]).

**3. Create the campaign.** Sales goal, Display type, your site URL and a clear name. For locations, choose "Presence" and avoid "Presence or interest".

**4. Set budget.** Retargeting spend is capped by audience size, so do not size it on ambition. For an average small or mid-size brand optimising for cheap impressions, $5-10/day is plenty. Do not go so low that it serves a few clicks and stops.

**5. Choose bidding.** Start with maximise conversions or maximise conversion value without a ROAS target, so it reaches the whole audience at good frequency while keeping traffic quality. Optionally test viewable CPM bidding to see whether reach and CPM improve.

**6. Turn off optimised targeting** at creation if offered. Then, after launch, open the ad group's targeting settings and confirm it is off; it is buried several clicks deep.

**7. Add complete creative**: images, logos, video if you have it, short and long headlines and descriptions. Turn off auto-generated assets.

**8. Launch even with a "too narrow" warning.** Small audiences (under about 1,000 users) trigger it; publish anyway and let the list grow.

**9. Monitor reach and frequency.** Create a custom CPM column and bring in unique users from the reach metrics. Frequency is impressions divided by unique users. Judge the campaign on retention and recall alongside attributed conversions.

## Example
Say a skincare brand with a 30-day repurchase cycle syncs a "customers in the last 180 days" segment, spends $8/day on maximise conversions with optimised targeting off. After four weeks it is delivering roughly 30,000 impressions a week to about 3,000 people at a CPM near $5, around ten impressions per customer.

Say an inherited campaign spends about $100/day at roughly 1x ROAS and shows impressions on unrelated sites. Switching optimised targeting off cuts spend (now limited by the real audience) and lifts both ROAS and frequency.

## Common mistakes
- Assuming existing Display campaigns already have optimised targeting off. Check now.
- "Presence or interest" location settings.
- Large budgets on small audiences, which push Google to find cold users.
- Judging reminder campaigns purely on last-click conversions.
- Letting auto-generated assets run unchecked.

## Related
- [[Google Ads Data - Enhanced Conversions and Customer Lists]] — building and syncing the audiences
- [[Retention Flows and Segmentation]] — the email side of reaching past buyers
- [[Google Ads Interface Basics]] — custom CPM and reach columns
- [[Is Performance Max Incremental]] — why retargeting claims need sceptical reading
- [[Campaign Types - An Account Map]] — where retargeting sits in a paid account
