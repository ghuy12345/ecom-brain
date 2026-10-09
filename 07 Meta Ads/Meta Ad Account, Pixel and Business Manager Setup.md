---
title: "Meta Ad Account, Pixel and Business Manager Setup"
topic: "07 Meta Ads"
stage: beginner
tags: [meta-ads, business-manager, pixel, dataset, account-setup, shopify]
summary: "How to set up a Meta Business Manager, ad account, page and pixel cleanly, then warm up a new ad account, so tracking works from day one and one lost login does not lock you out of everything."
---
# Meta Ad Account, Pixel and Business Manager Setup

## What it is
Before you spend a dollar, Meta needs four connected assets: a Business Manager (now called a business portfolio), an ad account inside it, a Facebook page that ads run from, and a pixel (Meta now labels pixels "datasets") that reports purchases back. Most early restrictions and tracking headaches come from sloppy setup; getting it right once saves weeks later.

## When to use it
- You are launching a new brand or a new store on Meta.
- You are rebuilding after a messy setup (several pixels, unclear ownership, one person holding every login).
- You are giving an agency or freelancer access and want them working on your assets, not theirs.

## How (steps)
1. **Decide the permanent settings first.** Timezone, currency and account name are effectively fixed once the ad account exists. Pick the time zone where your customers are, not where you live, so budgets reset at your customers' midnight. Use the currency you are billed in; billing in a different currency usually adds a small conversion fee on every charge.
2. **Inside the Business Manager, add a new ad account** (Accounts, Ad accounts, Add, Create new).
3. **Add payment at Business Manager level.** Add the card under Billing and Payments in the business settings and set it as the default for the ad account. Make sure the card's country and billing address match the business details; mismatches are a common trigger for reviews and restrictions.
4. **Create the page from a real personal profile.** A page owned by a real profile stays usable even if the Business Manager runs into trouble. Complete every field (images, bio, contact details) and add at least one original post or video so the page reads as a real business.
5. **Install the pixel through the store's native integration.** On Shopify, install the official Facebook and Instagram sales channel, connect the profile that administers the Business Manager, select the right business, set data sharing to Maximum, create or pick the pixel and assign it to the ad account. The Conversions API is wired up automatically through this integration. Hold off on third-party trackers until the native setup works; two trackers usually double-count revenue. No warm-up period is needed for the pixel.
6. **Verify the wiring.** In the business settings under Data sources, confirm the dataset is connected to the ad account. In a draft campaign, check you can pick the dataset with Purchase at ad-set level and your page as the identity at ad level.
7. **Warm up a new ad account before selling.** Pushing a fresh account straight into conversion campaigns invites restrictions, so build a record of approved ads first. Run an engagement campaign optimised for page likes at about $5 a day with worldwide or very broad targeting (for this warm-up only; you can leave out countries that require extra payer or beneficiary declarations). Any simple image with a short quote will do, since approval is the goal, not results. When the first ad clears review (a few hours to two days on a new account), duplicate it to five live ads, then keep doubling as approvals land (10, 20, 40) up to about 50. Switch to real sales campaigns after roughly three days (about $15 spent) once around 50 ads are approved and none are still processing.
8. **Add backup admins.** Invite at least two more trusted, real people as admins on the Business Manager and the page. If the only admin profile gets locked, nobody can reach the account, the page or running ads. Business admin rights do not include asset access, so assign the ad account and dataset to each person (People, Assign assets).
9. **Use partner sharing for outside help.** Give agencies, freelancers or your other businesses partner access to the pixel or ad account through their business ID (asset, Partners, Assign partner) instead of sharing logins; they must accept before the asset appears.

## Example
A new skincare brand selling into the US from Europe sets the ad account to US Eastern time and USD, adds the company card at business level with the registered address, builds a complete page from the founder's profile, installs the Shopify sales channel and confirms Purchase events. It runs the $5-a-day page-likes warm-up for three days, laddering one approved ad up to 50, before launching its first sales test. It adds two co-founders as admins and gives a freelance buyer partner access.

## Common mistakes
- Setting the account timezone to where you live rather than where customers buy.
- A card whose billing address does not match the business.
- A single admin profile with no backup.
- Launching sales campaigns on a brand-new account with no history of approved ads.
- Buying aged accounts, profiles or pages from sellers: such assets get hacked, banned or reclaimed mid-spend, and they break platform rules.
- Skipping asset assignment, which leaves admins unable to see the ad account.

## Related
- [[Ad Account Protection and Payment Hygiene]] — keeping the account healthy once it is live
- [[Ads Manager Setup - Columns, Benchmarks, Naming and UTMs]] — the next setup job after tracking works
- [[Creative Testing Campaign Setup]] — your first campaign on the new account
- [[Using a Third-Party Attribution Dashboard]] — when to add tracking beyond the native pixel
- [[Ad Account Billing and Credit Float]] — how billing method affects cash flow
