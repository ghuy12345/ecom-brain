---
title: "Choosing a Split-Test Type - Template, Visual, Redirect, Theme"
topic: "06 Landing Pages, CRO & Funnels"
stage: intermediate
tags: [split-testing, shopify, template-test, redirect-test, url-targeting]
summary: "Template tests are the default for Shopify page tests; visual-editor tests suit quick headline changes, redirect tests are for pages on different templates or builders, and whole-theme tests are reserved for new site launches."
---
# Choosing a Split-Test Type - Template, Visual, Redirect, Theme

## What it is
Split-testing apps for Shopify offer several test types. Picking the wrong one causes glitches, contaminated data or tests that change pages you never meant to touch. In short:

- **Template test:** copy a theme template, change it in Shopify's own theme editor, and show that copy to a share of visitors. The cleanest and default option.
- **Visual-editor (on-site edits) test:** point-and-click text and image changes injected over the page.
- **Redirect (split-URL) test:** send a share of visitors from one address to another.
- **Theme test:** split traffic between two entire themes.
- **Builder-native redirect test:** some landing page builders can split traffic between pages they host.

## When to use it
- **Template test:** almost every page test on the store. It also works around Shopify not letting you duplicate the homepage template.
- **Visual-editor test:** quick headline changes or code a developer injects (such as a new menu). The mobile editor can be glitchy and images may not carry over from desktop, so use it sparingly given most ad traffic is mobile.
- **Redirect test:** only where the two pages run on different templates (say a custom landing page against a collection page) or one of them is hosted in a separate page builder.
- **Theme test:** launching a brand-new theme to confirm it does not hurt revenue, or perhaps a store with very little traffic that wants at least a rough read on a new theme. Never as a shortcut to test one page.
- **Builder-native test:** offer tests between two builder pages (duplicate the page, change only the offer).

## How (steps)
**Template test**
1. Create the test, choose revenue or profit as the main metric, pick the template (homepage, collection, product or page).
2. Duplicate the control, rename the copy, open it in the theme editor and confirm the variant's name, not the control's, is shown before editing.
3. Change one big thing.
4. **Targeting:** visitors enter when the template loads. If the template is used by one page, leave targeting open. If it is shared (the default product template usually serves every product), add "URL contains" plus the product handle, or every product enters the test. The theme editor shows how many items use each template.

**Visual-editor test**
- Use "URL contains" for product pages (visitors from a collection carry the collection path in the address). Use "URL equals" for the homepage; a rule like "contains" plus your domain catches every page on the site, counting everyone in the test while showing them nothing and diluting the result toward zero.
- Edit the variant only, make mobile edits separately, and check the control still renders unchanged.

**Redirect test**
- Point the redirect from the page only ads use toward the regular site page, not the other way round, since general site visitors should never be diverted to an ad page.
- Use a simple redirect, set to redirect every time; leave devices, visitor type, traffic sources and currency unrestricted, unless the change only exists on one kind of device. Restrict country only if you want.
- If one page lives on a builder subdomain, install the testing script there too.

**Theme test**
- Run no other test at the same time, install the testing script on the alternate theme, and keep both themes for at least a month after ending.

**Builder-native test**
- It needs analytics connected and can only redirect between pages inside the builder, not from the main store into the builder.
- To ship the winner without editing ads, swap slugs: rename the loser's address and give the winner the address ads already use.

## Example
Hypothetical: a neck-pillow brand wants to test a new hero on its best seller, which uses the default product template shared by 140 products. It duplicates the template, edits the hero, and targets "URL contains" the best seller's handle. Separately, to compare its builder-hosted listicle against the store's collection page, it runs a redirect test from the listicle to the collection page.

## Common mistakes
- Testing a shared template with no targeting.
- Making edits on the control by mistake.
- Mixing up the operators: homepages need "equals", product pages need "contains".
- Running a theme test to check one page, or alongside other live tests.
- Leaving old test templates littering the theme.
- Reading builder test numbers from single-digit sessions.

## Related
- [[What to Split-Test First]] — deciding what goes in the test
- [[Split-Test Setup, QA and Shipping Winners]] — configuring, checking and executing tests
- [[Reading Split-Test Results - Sample Size and Power]] — when to read them
- [[Landing Page Technical Setup - Hosting, Metadata and Buy Boxes]] — builder pages on a subdomain
- [[Testing Landing Pages Through Ad Spend]] — testing without a split-test app
