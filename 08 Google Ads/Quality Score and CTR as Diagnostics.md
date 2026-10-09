---
title: "Quality Score and CTR as Diagnostics"
topic: "08 Google Ads"
stage: intermediate
tags: [google-ads, quality-score, ctr, diagnostics, ad-relevance]
summary: "Treat Quality Score components as pointers to what to fix, not targets, and remember that on a pay-per-click platform CTR affects rank, not the number of clicks your budget buys."
---
# Quality Score and CTR as Diagnostics

## What it is
Quality Score is Google's rating of how well your ad, keywords and landing page fit a search. It has three components:
- **Ad relevance** (visible as low/medium/high): how closely your ad and keywords match the search.
- **Expected CTR** (not shown as its own column): a projection based on your historical click-through rate.
- **Landing page experience** (visible as low/medium/high): how relevant and fast the page is, and plausibly how well it converts.

Quality Score adjusts your effective bid. A top score can roughly double the weight of your bid (a $1 bid competes like $2), an average score leaves it unchanged, and a poor score is penalised heavily. A higher-CTR advertiser can outrank a rival at the same bid.

None of this makes Quality Score or CTR a goal. Revenue and ROAS are the KPIs; the components only tell you where to look. Nobody outside Google knows the exact internal inputs, so claims like "landing page experience is your bounce rate" are guesses.

## When to use it
- CPCs are rising without an obvious competitor or bidding change.
- You are losing impression share to rank.
- Someone proposes "improving CTR" to fix a ROAS drop.

## How (steps)
**Why CTR rarely explains a ROAS drop.** Meta bills per impression, so a higher CTR cuts your cost per click. Google bills per click. With the same budget and CPC you buy the same number of clicks whatever your CTR. Say you have 5,000 daily impressions available, a $100 budget and a $1 CPC. At 5% CTR you use 2,000 impressions for 100 clicks; at 2.5% you use 4,000 impressions for the same 100 clicks. Same clicks, same spend. CTR only turns into a constraint when it sits low enough that impressions run dry before the budget is used (at 1% you would get 50 clicks and spend $50). That is rare, and mostly a concern for larger accounts.

**Diagnosing a drop**
1. Check CPC first. If it is stable, CTR is not your problem.
2. Look at the conversion rate for the same traffic.
3. Shortlist what could be dragging conversion rate: price, stock levels, page speed, any change to the offer, message match between ad and page (for example an ad promising a sale that has ended), and keyword relevance.
4. Check whether you are actually impression-constrained: spending below budget while losing share.
5. Work on CTR only to improve rank.
Useful columns: CPC, conversion rate, impression share lost to budget, impression share lost to rank.

**Using the components**
Bring in the landing page experience and ad relevance columns, at campaign, ad group and keyword level. Find the weakest component and apply the matching fix.
- *Low ad relevance:* make sure you are placed on the right queries (subtle mismatches, such as physical books showing for "digital books", count). Make titles and descriptions as keyword-rich as reads naturally. Bidding on unrelated terms gives the lowest relevance, high CPCs and lost auctions.
- *Low expected CTR:* add negatives for irrelevant terms; in PMax, where you have fewer controls, remove irrelevant words from titles and descriptions. For Shopping, make pricing competitive, add promotion and review feeds, change the main image and title, and show differentiators like shipping. Study the top six listings and find a way to stand out. For Search, put specific value propositions in the top headlines instead of generic lines.
- *Low landing page experience:* use the relevant keywords on the page, make it load fast and get conversion rate to a normal benchmark. A very low conversion rate teaches Google to send you less traffic at higher prices.
Re-check after each change.

## Example
Say ROAS drops from 4.5 to 3.0. CPC is steady at $0.90 and CTR is steady. Conversion rate fell: the landing page had moved away from a bundle offer and now showed one full-price product. No CTR work would have helped.

A paperback-books Shopping campaign shows low ad relevance, average expected CTR and high landing page experience. The fix is in the feed (format, title and author in product titles, plus promotion and review feeds); the page is left alone.

## Common mistakes
- Chasing a 10/10 score as if it were a KPI.
- Treating CTR on Google like CTR on Meta.
- Rebuilding a landing page because of a guess about what Google measures.
- Ignoring the rank side: a poor score quietly raises every CPC you pay.

## Related
- [[Google Ads Self-Audit and Bottleneck Diagnosis]] — where these checks sit in a full diagnosis
- [[Shopping Feed Optimisation]] — fixing relevance and expected CTR in Shopping
- [[Ad-to-Page Congruency]] — message match between ad and landing page
- [[Search Terms and Negative Keywords]] — removing irrelevant queries
- [[Diagnosing Clicks That Do Not Convert]] — the conversion-rate side of the same problem
