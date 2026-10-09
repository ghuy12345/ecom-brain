---
title: "Google Ads Account Structure for Ecommerce"
topic: "08 Google Ads"
stage: intermediate
tags: [google-ads, account-structure, consolidation, shopping, machine-learning]
summary: "Build a Google Ads account around as few campaigns as possible, lead with Shopping, and only split when a real commercial reason justifies starving a model of data."
---
# Google Ads Account Structure for Ecommerce

## What it is
A structural philosophy for ecommerce Google accounts: consolidate first, put most of your money behind product listing ads, and treat every extra campaign as something you have to defend.

It rests on how Google's models learn. Each layer of the account (account, campaign, ad group or asset group, and the individual ad or product) trains on the conversions recorded at that layer. Campaigns do not pool their conversions with each other. Sparse layers lean on the layer above them (a product with three sales a month borrows from its asset group, which borrows from the campaign, and so on), and the bid placed in an auction is effectively a weighted blend of what each layer suggests. You cannot see those weights, but you can control how much data each layer has.

Divide a product range into four campaigns that earn 50, 20, 15 and 5 conversions a month and you end up with four thin models, each prone to small-sample bias: a handful of buyers who happen to share a trait look like "the customer". Merge them and one model learns from roughly 90 conversions, which describes your buyers far better and bids more sensibly.

Shopping sits at the centre because shoppers see the image, price, title, reviews and rival listings before they click. They qualify themselves, so conversion rates run higher at comparable CPCs. For most stores, 80-90% of Google spend belongs in Shopping-style product ads.

## When to use it
- When you build a new account or inherit one with a long list of campaigns.
- When results are volatile and you suspect several campaigns are each too thin to learn.
- Whenever someone proposes a new campaign "to keep things organised".

## How (steps)
1. **List every campaign with a purpose column.** For each, write the reason it exists. If you cannot write one, merge or cut it. Account complexity should mirror business complexity (countries, sub-brands, a rotating catalogue), not budget size.
2. **Tally each campaign's conversions over 30 days.** Anything under roughly 30-50 is a merge candidate unless it has a commercial reason to stand alone.
3. **Accept only these reasons to split:**
   - Brand vs non-brand (always separate; see [[Brand Search and Branded Shopping Campaigns]]).
   - Geography, especially different currencies or languages.
   - Different margins or efficiency goals. A 65% margin line and a 50% margin line have different breakeven ROAS (about 1.5 vs 2.0), and Google optimises revenue, not margin. Blending raises reported ROAS while lowering profit dollars.
   - Product groups that sell to clearly different buyers (pens and heavy machinery should not share a model).
   - Inventory pressure: clearance stock that should receive a small trickle of spend, new arrivals that need visibility, minimum order quantities, seasonality.
   - Entry-product LTV. If buyers of one product repurchase twice as often as buyers of another, you can afford to acquire more aggressively through the first. Products with very low repeat rates must pay back on the first order.
4. **Lead with Shopping.** Standard Shopping plus (optionally) Performance Max, with brand excluded from both and existing customers bid down or excluded. How to weight the two is covered in [[Performance Max vs Standard Shopping]].
5. **Add brand coverage** as its own campaign(s).
6. **Hold off on other formats.** Below roughly $50K/month in spend, Shopping and PMax usually beat cold Search, YouTube and Demand Gen for an ecommerce store. Past that, test cold Search or YouTube with hold-out tests, not in-platform ROAS. A B2B or bulk-buyer component is the main exception, since those buyers search for deals outside listings.
7. **Name consistently:** team tag, region, campaign type, audience (cold, brand, feeder) and goal, so anyone can read the account at a glance.

## Example
Say a footwear brand spends $30K/month. A clean build might be: PMax with brand excluded (about 40% of budget), standard Shopping with existing customers bid down heavily (about 45%), and a small branded Shopping campaign (about 5%). One collection carries a much higher margin, so it is given a separate Shopping campaign carrying a lower ROAS target. Sneaker buyers repeat far more than boot buyers, so sneakers get a larger acquisition budget. That is four or five campaigns, each with a sentence explaining why it exists.

## Common mistakes
- Segmenting to look tidy, then wondering why every campaign is stuck in learning.
- Splitting one 90-conversion campaign into ten 9-conversion campaigns.
- Putting a 35% margin line and a 70% margin line under one ROAS target.
- Trusting higher reported ROAS from Search, YouTube or Demand Gen without testing incrementality; Google over-attributes, especially once brand traffic leaks in.
- Using single-keyword ad groups in Search. Responsive search ads have thousands of asset combinations and need hundreds of thousands of impressions to learn; use single-topic groups of 10-20 related keywords instead.

## Related
- [[Performance Max vs Standard Shopping]] — how to weight the two main product-ad campaign types
- [[A Staged Google Ads Roadmap for Ecommerce]] — the order in which to build this structure
- [[Consolidate vs Segment Campaigns]] — the same consolidation logic applied on Meta
- [[Breakeven ROAS and KPI Tiers]] — why different margins need different targets
- [[Cohort LTV Modelling]] — the data behind entry-product LTV splits
- [[Glossary - Google Ads & Shopping]] — definitions of asset groups, listing groups and ROAS targets
