---
title: "Product-Level Reporting and Zombie Products"
topic: "08 Google Ads"
stage: scaling
tags: [google-ads, shopping, product-reports, zombie-products, catalog]
summary: "See which products absorb Shopping and PMax spend and whether they earn it, then give products that never get spend a campaign and budget of their own."
---
# Product-Level Reporting and Zombie Products

## What it is
In Shopping and Performance Max, Google decides which products in a campaign receive budget, and it tends to concentrate spend on a few. In a large catalogue, a handful of SKUs can take most of the money while hundreds sit idle. Product-level reporting shows you where the money goes. A **zombie product** is an enabled, in-stock product that received roughly zero Shopping spend over the last 30 days. Isolating zombies in their own campaign can unlock extra scale without touching your main campaigns.

With 2-20 SKUs this rarely matters. With hundreds or thousands, many products can sit unspent month after month.

## When to use it
- Weekly, to spot budget hogs that do not convert.
- When a large-catalogue account has stopped growing.
- Before excluding products, so you know what each is doing.

## How (steps)
**1. Know the three product views.**
- *Inside a standard Shopping campaign:* open the ad group's Products view. If rows are grouped (for example by product type), edit the grouping and split every product out by item ID, making sure every product is selected, and save without changing bids. Sort by cost.
- *Account level:* the Products view across all campaigns shows Shopping and PMax together. Sort by cost high to low for top spenders, low to high for bottom spenders.
- *Shopping report:* in predefined reports, open the Shopping category report, swap the default row segments for product title, and put the cost and conversions columns first in the table. Save it. You rarely need more detail than this.

**2. Review top spenders weekly.** Sort by cost and check conversions beside it. A product taking a large share of spend with no purchases is a candidate for a price check, a feed fix ([[Shopping Feed Optimisation]]) or exclusion. Remove products gradually, never in huge batches ([[A Staged Google Ads Roadmap for Ecommerce]]).

**3. Find zombies.** Either use a PMax insights script that lists products with impressions but no spend, or filter the account-level Products view to cost under $1 and status enabled. Filtering on enabled matters: out-of-stock products cannot spend, so they would clutter the list.

**4. Export and copy the item IDs** into a sheet.

**5. Choose a campaign type for them.**
- If your buyers are mostly new and repeat rates are low, PMax is reasonable.
- If returning customers are a large share of revenue, use standard Shopping, because PMax would lean into retargeting.

**6. Build the zombie campaign.** In product groups, add a subdivision by item ID, bulk-add the copied IDs and exclude everything else. Give it its own budget and leave it through a full learning window before judging.

**7. Re-audit every 30 days.** Promote SKUs that start converting into the main campaign, and refresh the zombie list.

## Example
Say a store has 800 SKUs and the account-level view shows the top 10 taking about 70% of spend. Three of those ten have no purchases in 30 days: two get title and image fixes, one gets a price review. Meanwhile a hypothetical 4,000-SKU store finds 1,600 zombies, puts them in a standard Shopping campaign at $50/day for 30 days, then promotes the 40 that sold into its main campaign.

## Common mistakes
- Only ever looking at campaign totals, so you never see which products drive results.
- Forgetting to subdivide by item ID, so the Products view shows a few grouped rows.
- Counting out-of-stock items as zombies.
- Putting zombies in PMax when your revenue is mostly repeat buyers.
- Judging the zombie campaign after a few days instead of a full learning window.
- Excluding thousands of low performers at once and resetting the main campaign.

## Related
- [[Google Ads Account Structure for Ecommerce]] — when a separate campaign is justified
- [[Shopping Feed Optimisation]] — fixing products that spend without converting
- [[A Staged Google Ads Roadmap for Ecommerce]] — removing products in safe chunks
- [[Google Ads Interface Basics]] — building the columns used in these reports
- [[Google Ads Self-Audit and Bottleneck Diagnosis]] — product bloat as a failure mode
