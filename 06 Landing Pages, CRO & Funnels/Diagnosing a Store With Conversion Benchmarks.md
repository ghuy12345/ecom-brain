---
title: "Diagnosing a Store With Conversion Benchmarks"
topic: "06 Landing Pages, CRO & Funnels"
stage: intermediate
tags: [store-health-score, add-to-cart-ratio, page-speed, heatmaps, store-diagnosis]
summary: "Use AOV x conversion rate as a quick health score, add-to-cart ratio and click-to-page-view rate as diagnostics, and revenue-based heatmaps to find the weak areas of a page."
---
# Diagnosing a Store With Conversion Benchmarks

## What it is
A short set of rules of thumb for working out where a store stands and where it leaks. None of them is an industry standard; they are diagnostics, not goals.

- **Store health score** = AOV x conversion rate, written as a whole number (2.2% x $100 = 220). It is revenue per session expressed without the decimals.
- **Add-to-cart ratio** = the number of add-to-carts needed before one order results (add-to-cart rate divided by conversion rate).
- **Link-click to landing-page-view rate** = how many people who clicked the ad actually saw the page load.

It helps to remember that ROAS is driven by conversion rate, AOV and click-through rate together. Great ads lift CTR and conversion; great pages lift conversion and AOV.

## When to use it
- Auditing a new store or an acquired store before deciding what to fix.
- When ads look fine but sales are weak and you need to know which side to work on.
- Periodically while scaling, because the score drops as more cold traffic arrives.

## How (steps)
1. **Score the store.** Rough bands:
   - **0-100:** a serious problem. The value is not coming across, the price is wrong, the traffic is junk or bots, or something is broken. Look at product and pricing first; if they are sound, suspect the traffic.
   - **100-250:** partly working, but not yet able to absorb scale. Keep improving store and pages.
   - **250-400:** where you want to be. Add traffic and keep optimising in parallel.
   - **400+:** the store converts traffic extremely well. Spend aggressively; if you cannot spend more, your ads are what is holding you back.
   High-margin products (70-85%) often score a little lower and lower-margin ones (50-55%) a little higher, though not always. A high-margin store under 100 should consider a lower price or more value in the offer.
2. **Read the add-to-cart ratio.** Four carts per order or more usually means poor traffic quality. 3:1 is ideal, 2:1 is elite, 1:1 is almost never seen. Plenty of carts but few orders signals friction after the click: unexpected shipping costs, an awkward cart, an overload of upsells. Very cheap global traffic can carry a bad ratio and still make money, so always read it in context.
3. **Check click-to-page-view rate.** Above about 60% is generally acceptable. Below that, look at load speed or ads that are so clickbaity people bounce before the page renders.
4. **Check page speed.** A page that takes around seven seconds to load is a real bottleneck. Builder pages can be fast enough to start; a custom-coded page is the lasting answer if speed limits you.
5. **Verify the conversion data.** Some page builders count users who reach checkout as conversions, which inflates the store's conversion rate. Reconcile against actual orders.
6. **Map weak areas with a revenue heatmap.** Revenue per click lets you rank unlike elements against each other; revenue per session compares one element between test versions. Then act:
   - Collection pages: order product tiles from highest to lowest revenue per click, drop the poorest, and fit more products per row.
   - Product pages: keep the add-to-cart button in the first screen, place badges to the left of the main image (eyes scan in a Z), move the best-earning thumbnails first, show low-star reviews with good service replies, default to the best-selling variant, reorder accordion tabs by revenue per click, and split-test removing a sticky add-to-cart or dead-click areas that earn less than the main button.
   - FAQs: keep 6-8 questions, order by revenue per session, swap the lowest earner for a question customers actually ask.
   - Rage clicks show where something is broken or frustrating.

## Example
Hypothetical: a home-goods store converts at 1% with a $50 AOV, a score of 50. Ads have a healthy CTR, so traffic is not obviously bad. Add-to-cart ratio is 6:1 and click-to-page-view is 48%. The page takes six seconds on mobile and the price shown in cart differs from the product page. Fixing speed and the price display moves the score toward 120, still not scalable, so the team then reworks the offer into a two-pack to lift AOV.

## Common mistakes
- Treating the add-to-cart ratio as something to optimise. A better ratio does not mean more orders.
- Reading the score once and forgetting it. Raising it, adding traffic, watching it fall and raising it again is the normal scaling loop.
- Trusting builder-reported conversion rates without checking real orders.
- Blaming a page for low scores when the ads are sending curiosity clicks.

## Related
- [[Revenue and Profit Per Session]] — the same formula used for offer tests
- [[The CRO Priority Order - Clarity, Copy, Offer, Proof, Friction]] — what to fix once you know where the leak is
- [[Auditing Pages - First Visit, Mobile and Pre-Publish]] — hands-on audits that find broken elements
- [[Diagnosing Clicks That Do Not Convert]] — when the problem is upstream in the ad
- [[Contribution Margin and Variable Costs]] — why margin shifts the score bands
