---
title: "Google Ads Data - Enhanced Conversions and Customer Lists"
topic: "08 Google Ads"
stage: intermediate
tags: [google-ads, tracking, enhanced-conversions, customer-lists, audiences]
summary: "Feed Google clean first-party data: a direct conversion tag with enhanced conversions, uploaded or synced customer lists for exclusions and retargeting, and a calm reading of reporting quirks."
---
# Google Ads Data - Enhanced Conversions and Customer Lists

## What it is
Google's bidding is only as good as the data you give it. Two inputs matter most for a store:
- **Conversion tracking with enhanced conversions.** Enhanced conversions pass hashed customer details collected at checkout over to Google Ads, which improves how many purchases it can match to ad clicks.
- **Customer lists.** Your own customer and subscriber data, uploaded or synced, used to exclude buyers from cold campaigns or to retarget them. Lists from your store or email platform are far more accurate than audiences built automatically by a tag or GA4.

## When to use it
- Setting up a new account, or as step one of any account repair.
- When cold campaigns seem to be spending on existing customers.
- Before running Display retargeting or customer exclusions.

## How (steps)
**1. Track purchases with a direct Google Ads tag.** Use the Google Ads conversion tag as your primary purchase conversion, plus enhanced conversions and auto-tagging. Using a GA4 event as the primary conversion usually leaves a gap of 10-15% or more versus a direct tag.

**2. Turn on enhanced conversions.**
- *Preferred route (Ads tag):* open the purchase conversion action in Google Ads and enable enhanced conversions on the tag. Have a developer pass checkout customer details into the tracking code as variables.
- *Fallback (GA4):* when the GA4 purchase event is your only option, open the web data stream in GA4 admin, then the tag settings. Turn on user-provided data, pick automatic detection (manual selectors if detection fails), and save.
- Place test purchases and check the diagnostics in Google Ads.

**3. Upload a customer list.**
1. Export customers from your store as a plain CSV limited to these columns: email, phone, first name, last name, country code and postcode. Drop tags and metafields. Large lists take a while to export.
2. In Google Ads, go to the audience manager, create a customer list and upload the file. Name it, set the customer type and confirm consent.
3. Map each column correctly and remove every other column; a wrong mapping fails the upload.
4. Expect only part of the list to match. The audience fills over a few days.
5. Use it once it passes about 1,000 matched users.
Push the same list into Meta as a baseline too.

**4. Automate with an email-platform sync.** Manual uploads go stale. Connect your email platform (Klaviyo, for example) to Google Ads, choose a list or segment and map it to a new Google audience, one audience per segment with a clear name. Turn regional consent settings on if you operate in Europe. Useful segments: all profiles, purchasers in the last 180 days, VIPs with three or more orders, subscribers who have never bought. Allow up to a week for matching; a size of zero at first is normal.

**5. Put the lists to work.** Exclude recent purchasers and VIPs from cold PMax and Shopping so spend goes to new customers. Target non-buying subscribers or recent buyers with small Display campaigns ([[Google Display Retargeting]]).

**6. Do not panic at the "{ignore}" quirk.** In the landing page report, some URLs show a literal "{ignore}" before the query string, and clicking them gives a 404. This is a display artefact, probably from custom UTM parameters in the final URL suffix colliding with Google's own tracking parameters. The real ad URL works. Do not change your ads; instead crawl the site to confirm no live page returns 404, and check that UTM-tagged sessions arrive correctly in your store and CRM. Keep that evidence on file.

## Example
Say a store with about 10,000 customers uploads its list and around 6,800 match. That audience is excluded from the cold PMax and Shopping campaigns, and the store runs a $5-10/day Display campaign to subscribers who have never purchased, fed by an automatic email-platform sync so new buyers move out of the prospect audience by themselves.

## Common mistakes
- GA4 events as the primary purchase conversion.
- Enhanced conversions switched on but no customer data actually passed.
- Uploading every export column, so the mapping fails.
- Using a list of a few hundred matched users and wondering why nothing serves.
- Uploading once and never refreshing.
- "Fixing" working ad URLs because of a report display quirk.

## Related
- [[Google Display Retargeting]] — the main use for synced customer lists
- [[Retention Flows and Segmentation]] — building the segments you sync
- [[Ads Manager Setup - Columns, Benchmarks, Naming and UTMs]] — UTM conventions across platforms
- [[Using a Third-Party Attribution Dashboard]] — checking platform data against store data
- [[A Staged Google Ads Roadmap for Ecommerce]] — tracking as step one
