---
title: "Landing Page Technical Setup - Hosting, Metadata and Buy Boxes"
topic: "06 Landing Pages, CRO & Funnels"
stage: beginner
tags: [page-builder, tracking, metadata, buy-box, cart-permalinks]
summary: "Configure a separate landing page host with tracking before building pages, give each page clean metadata, and sell directly from the page with synced buy boxes, cart permalinks and pre-applied discount links."
---
# Landing Page Technical Setup - Hosting, Metadata and Buy Boxes

## What it is
The plumbing behind ad landing pages built in a separate page builder rather than inside the store theme. It covers three things: the site-level setup (domain, fonts, analytics and pixels), page metadata (title, address, description, share image, favicon), and the purchase path (buy boxes, variant sync, cart links and discount links). None of it is persuasive copy, but mistakes here break tracking, confuse visitors or silently kill offers.

## When to use it
- When you first connect a page builder to a store.
- Every time you publish a new page.
- Whenever an offer, discount code or product variant changes.

## How (steps)
**1. Site-level setup (before any page)**
- Create the site, then go straight to site settings; every page inherits them.
- Host pages on a subdomain of the brand domain (for example a "try" or "go" subdomain) by adding a CNAME record at your domain registrar pointing to the builder. Remove any placeholder default domain once connected.
- Upload the logo and fonts. Identify the store's fonts with a font-identifier extension; use the built-in Google font option where possible, otherwise upload font files you are licensed to use.
- Connect analytics with the correct company account.
- Script placement: tracking pixels, attribution and heatmap scripts sit in the page head; email, text-message and pop-up scripts sit just before the closing body tag.
- Publish a first page, open it on the live subdomain and check the Meta pixel registers. Save at every step, and publish a second time if edits do not show (builders often cache).

**2. Page metadata (polish and congruence)**
There is no evidence this lifts conversion, but a random address and a builder's default icon feel off-brand exactly when you need the visitor's trust.
- Page title: brand plus benefit.
- Address slug: short and relevant to the angle.
- Meta description: the core brand line.
- Share image: a clean brand photo instead of the placeholder.
- Favicon: set it in theme settings, square, taken from the live site if no file exists.

**3. The purchase path**
- Choose the page type: a **pre-sell/redirect** page whose buttons go to a specific product or collection (never the homepage), or a **buy-on-page** page whose order form adds to cart and goes straight to checkout.
- **Buy boxes:** paste the product's base address (without a variant parameter), sync product data, publish, then adjust the headline, reviews, prices (current and compare-at), images, button text and quantity picker. Test by adding to cart and checking price and discount at checkout.
- **Variant sync:** only native store variants sync. To check, pick a variant on the live product page: if the address changes, it is native; if it stays the same, an app or custom code built it and it will not sync.
- **Bundle maths:** for a "buy 2, save 15%" box, work out the bundle total (two units at 85% of price), then price the second unit as that total less one full-price unit, showing full price as its compare-at. Re-check all discount arithmetic by hand.
- **Cart permalinks:** a Shopify cart permalink pre-loads the product (identified by its variant ID) and the quantity into the cart, with extra products listed one after another and the discount code optionally added. Find variant IDs by opening the product's XML version in the browser. Test every link.
- **Pre-applied discount links:** Shopify's discount link auto-applies the code and then redirects the shopper to the destination page you choose. The discount then reaches only visitors coming through that page, and nobody needs to type a code. A spreadsheet that splits and rejoins domain and path makes these quick to build.

## Example
Hypothetical: a supplement brand moves its ad pages to a "try" subdomain. During setup the team confirms the pixel fires on the first published page, sets the page title to the brand plus "Sleep through the night", and builds a three-tier buy box. The two-bottle tier uses the bundle maths above, and every button carries a discount link so the 20% offer shows in cart without a code.

## Common mistakes
- Checking the pixel when no page has been published yet.
- Connecting the wrong analytics account, or forgetting to save between steps.
- Discount links that break because the code was never created or has run out of uses.
- Custom bundle or subscription apps that use non-standard addresses, so the generic pattern breaks.
- A bundle box that makes both items compulsory when the second should be an optional extra.
- Changing a code without rebuilding every link that carries it.
- Not re-checking sections after a builder update.

## Related
- [[Landing Page QA Before Launch]] — testing everything this setup creates
- [[Landing Page Imagery and Theme]] — the theme that sits on top of site settings
- [[Meta Ad Account, Pixel and Business Manager Setup]] — the pixel side of tracking
- [[Sale Pages, Discount Formats and Savings Display]] — choosing the discount format
- [[Ads Manager Setup - Columns, Benchmarks, Naming and UTMs]] — tracking parameters on ad links
