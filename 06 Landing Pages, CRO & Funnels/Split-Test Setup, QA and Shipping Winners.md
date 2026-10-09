---
title: "Split-Test Setup, QA and Shipping Winners"
topic: "06 Landing Pages, CRO & Funnels"
stage: intermediate
tags: [split-testing, cogs, qa, shopify, test-execution]
summary: "Configure product costs and shipping so profit reads are trustworthy, check every test because faulty builds sink more tests than bad ideas, and ship winners carefully by test type."
---
# Split-Test Setup, QA and Shipping Winners

## What it is
The operational side of split testing on a Shopify store: what to configure before your first test, how to confirm each test is really running as designed, and how to make a winner permanent. It feels like admin, but it decides whether your results mean anything. When split tests fail, the cause is far more often a broken build than a weak idea, and a conclusion drawn from a broken build is worse than no conclusion.

## When to use it
- Installing a split-testing app for the first time.
- Before every launch.
- When a test has a confirmed winner to roll out.
- When a test is losing suspiciously fast at low volume.

## How (steps)
**1. Configure for profit**
1. Install the app and place its theme snippet following the vendor's current instructions.
2. Let product costs sync automatically from the store; give every variant a unit cost and switch on daily syncing so new products are covered.
3. Enter shipping cost: a fixed amount if every order costs about the same to ship, or a percentage of order value if shipping is folded into prices.
4. Before any launch, check that margin and profit figures show on each variant. Decide tests on profit or revenue per visitor, never conversion rate by itself.
5. Know your tier: basic plans usually cover content tests, while price and shipping tests sit on much more expensive plans.

**2. QA each test**
1. Work through the tool's own pre-launch checklist.
2. Look at the preview, then at the real site on a phone, in more than one browser and at several screen sizes.
3. Proofread all edited copy.
4. Try to break it: tap every element, confirm images actually swap, add to cart.
5. Inspect the real variant, not only the preview. Open a private window on the test page and keep refreshing until the tool assigns you the variant (it usually marks the address), then check it on desktop and mobile. For template tests, the test details show which address the template appears on.
6. Use a VPN to view the test from any other country it targets.
7. If a variant is collapsing at low volume, inspect the build before blaming the idea. A large early gain is equally no reason to ship; check it and wait for enough orders.

**3. Roll out the winner**
First pause or stop the test (a handy convention: paused means won and waiting; stopped means rolled out). Check the live result afterwards.
- **Theme test:** publish the winning theme.
- **Visual-editor test:** there is no one-click promote; rebuild the changes permanently in the theme editor.
- **Redirect test:** update the destination in your ads. A permanent store redirect is possible, but it is not the preferred route.
- **Template test on a product, collection or page:** open the item, change its assigned template from default to the winning one, save.
- **Template test on the homepage:** no template picker exists, so you move code. Add a view parameter to the page address, carrying the template's name, to preview the winner, copy that template's JSON, save a backup of the current homepage JSON as a new template, paste the winner into the homepage JSON, save and check. To undo, paste the backup back. Rehearse on a draft theme rather than the live one, and keep a developer on call, particularly if apps or custom code are involved.

## Example
Hypothetical: a skincare store tests adding a general reviews section to every product page. Within days it is trending toward a heavy loss. Instead of abandoning the idea, the team inspects the build and finds the new section overwrote each product's own reviews. Rebuilt with one rule (only show general reviews on products that have none), the same idea becomes a clear profit winner once several hundred orders per variant are in. The hypothesis never changed; only the execution did.

## Common mistakes
- Running profit-based tests while product costs or shipping are missing, or with manually entered costs that go stale.
- Checking the preview but never the live, bucketed variant.
- Shipping on an early spike.
- Rolling out a winner while the test is still live.
- Overwriting the homepage JSON with no backup, or doing it on the live theme.

## Related
- [[Choosing a Split-Test Type - Template, Visual, Redirect, Theme]] — the test types referenced here
- [[Reading Split-Test Results - Sample Size and Power]] — when a result is ready to ship
- [[Landing Page QA Before Launch]] — page-level QA discipline
- [[Contribution Margin and Variable Costs]] — the costs that make profit reads accurate
- [[What to Split-Test First]] — choosing the next test
