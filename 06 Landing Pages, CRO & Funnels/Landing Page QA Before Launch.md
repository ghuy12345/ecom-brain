---
title: "Landing Page QA Before Launch"
topic: "06 Landing Pages, CRO & Funnels"
stage: beginner
tags: [qa, mobile-testing, proofreading, discount-links, landing-pages]
summary: "Checking that a page works, reads clearly and is error-free is the highest-leverage habit in CRO, because a broken page does not just convert badly, it gives you false test data."
---
# Landing Page QA Before Launch

## What it is
Quality assurance (QA) is verifying that a page functions, reads clearly and contains no errors before traffic hits it and after every edit. It is the most valuable habit in landing page work because a faulty page costs more than sales: it hands you misleading data. You conclude the angle or offer failed and change the wrong thing. One forgotten menu link to an outside site can drain a big slice of visitors and make a strong idea look like a failure.

Three questions frame every QA pass:
1. Does everything **function**, on every device?
2. Is everything **clear** and readable?
3. Is it **right**? A check by fresh eyes or another person.

## When to use it
Before launch, after every edit, after any developer change, after any page-builder update, and whenever an offer or discount code changes.

## How (steps)
**Functionality sweep**
1. Load the page in a new private window, other windows closed (stale cache causes phantom glitches).
2. Work from top to bottom through every element: tap it, hold and drag it, try highlighting its text, copy any code and paste it to confirm, and open every link. Ask how a visitor will behave: visitors tap pictures expecting to enlarge them or go somewhere, click the logo and menu to feel in control, and tap things that look like buttons. Decide deliberately what is linked; benefit images usually should not send people off to a single product page.
3. Check footers, terms and privacy links, and anything that looks clickable but does nothing.
4. Run a full purchase: add to cart, check the price, make sure the discount survives into checkout, not just the page.

**Device matrix**
1. Desktop in one browser, then a second browser.
2. Real phones: iPhone with Safari and Chrome, and an Android if possible. Emulation never replaces a real device.
3. Developer-tools emulation at several sizes, refreshing after each change; also a short window height (small laptops).
4. In your analytics, find the most common screen resolution over the last month and test at exactly that, as well as the smallest width and height you need to cover.
5. Watch for first-load failures (GIFs or images that only appear on refresh); visitors usually only get the first load.

**Copy proofread**
1. Copy all page text, paste it as plain text into a document and run the spelling and grammar check.
2. Use a second grammar checker as well; each one misses different errors (missing articles, stray capitals, hyphenation).
3. Check names and capitalisation against the brand guidelines.
4. Read the whole page aloud. Run-on sentences become obvious.
5. Check text baked into images by eye; leave customer reviews in quotes as written.
6. Come back the next day, then have someone else read it.

After fixing, republish (twice if the builder caches) and load the page fresh to confirm. Repeat the pass; defects keep appearing on the second and third rounds. Then stop and ship; endless tweaking is its own trap.

## Example
Hypothetical: a page copied from a competitor's layout still has "Shop" in the menu linking to the competitor's store. In a test, roughly half the clicks leave. The dashboard shows the page losing badly, and the team nearly drops the angle. A click-through QA finds the link; once fixed, the same page beats the control. The same pass catches a review with no star rating and a code that reads 50% in the hero but 15% in the offer box.

## Common mistakes
- Checking mobile only by emulation.
- Testing in a normal, cached browser window.
- Shrinking trust bars or text until unreadable to make them fit; remove clutter first.
- Changing a discount code without rebuilding every button and link that carries it.
- Offer numbers that disagree between sections.
- Handing a draft to a stakeholder before it has been proofread.

## Related
- [[Auditing Pages - First Visit, Mobile and Pre-Publish]] — the strategic and first-visit audits
- [[Landing Page Technical Setup - Hosting, Metadata and Buy Boxes]] — the links and boxes you are testing
- [[Split-Test Setup, QA and Shipping Winners]] — QA for split tests specifically
- [[Copy Proofing Checklist]] — a fuller copy-checking routine
- [[Video Ad Pre-Launch and Post-Mortem Checklist]] — the same habit applied to ads
