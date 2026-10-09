---
title: "Building Static Ads With an LLM"
topic: "12 AI Workflows for Ecom"
stage: beginner
tags: [static-ads, llm, sub-avatars, concept-brief, ad-cloning, claims]
summary: "Build a complete static ad from a master research document and sub-avatars with an LLM, and use ad-cloning tools only for fast drafts and research direction, never to ship a copy."
---
# Building Static Ads With an LLM

## What it is
A complete process that takes you from research to a finished static in a couple of hours: the LLM proposes angles and headlines per sub-avatar, you choose and refine, you build the ad from a proven layout, and the LLM writes supporting bullets from real customer quotes. The information in the ad matters more than polish. An ugly ad with sharp, specific information beats a beautiful ad with generic claims, and a designer can rebuild the winners afterwards.

## When to use it
When you need a steady flow of static concepts (a realistic target is one or two finished concepts per day) and have a research document and sub-avatars ready. Image and video ads share this process; video just needs more time.

## How (steps)
1. **Work from a single master file** split into tabs for product, research (customer language), sub-avatars, new information and new mechanism. Everything you paste into the LLM comes from here. Never just ask it to "write me an ad".
2. **Generate angles.** Paste your angle prompt with the sub-avatars appended. You should get a handful of angles for each sub-avatar, each with candidate headlines.
3. **Choose a testing method:** several angles inside one concept (broad), or a single angle tested through multiple hooks (narrow).
4. **Refine, do not accept.** Tell the model your own idea and the reasoning behind it, and give it your headline starts. A plain, punchy line you wrote often beats its polished rewrite.
5. **Check every factual premise** against the product document and a second source. Lead bullets with a hard figure only after confirming it.
6. **Complete a concept brief** covering the concept, the angle or angles, how it will be tested and the format. Log it in your tracking sheet.
7. **Choose a layout** from your collection of proven static structures and confirm the headline fits. Prefer reference ads from outside your industry so you do not mirror direct competitors.
8. **Build it** in a design tool with real brand colours, a product photo with space for text, and a background remover.
9. **Write bullets with the model.** Screenshot your layout, attach the inspiration ad and paste raw customer quotes; ask for a specific number of bullets in the same pattern. Quote-fed bullets are far more specific.
10. **Finish one ad completely before batching**, since a headline that reads well may not fit the design. Then rest and review with fresh eyes before shipping.

**Using ad-cloning tools.** Some tools generate several statics for your brand from a reference ad in minutes. Treat them as a fast draft and a pointer for research, not as a source of finished ads:
- Only use references you have validated with spend, engagement and run-time signals, not just ads that look good.
- Feed the tool proper brand context (correct colours and font, tone of voice drafted by your loaded LLM project). Thin inputs give generic output.
- Keep the best two or three of a batch for a small test and treat the rest as leads for angles and avatars worth researching in depth.
- Never publish a near-copy of someone else's ad; take the structure and the insight, not the execution.

## Example
Say a joint-support supplement has three sub-avatars. The model returns angles for a weekend runner ("keep the miles without the morning stiffness"), a gardener ("get back down to the flower bed") and an informed but confused buyer ("what the label actually means"). The strategist adds vivid, behaviour-specific lines from forum research ("taking the stairs one at a time") and drops generic ones ("feel better every day"). Bullets are built from verbatim comments from forum threads, and the headline percentage is checked against the product document before it goes on the ad. Hypothetically, if an appetite supplement's product document said natural GLP-1 production rises 56%, the lead bullet would open with that figure, followed by fuller-feeling signals, fewer cravings and an easier no to junk food.

A cloning-tool batch for a cookware brand produces a weak ad overall, but one line about home cooks wanting to cook like professionals points to an avatar worth researching.

## Common mistakes
- Prompting with no research context.
- Accepting "naturally" claims that show nothing.
- Letting the model call a mechanism something it is not, or cite hormones the product does not affect. Avoid unverified "root cause" language.
- Naming prescription drugs or competitor brands the brand will not reference.
- Choosing winners by personal taste rather than data. Expect only a small share of new ads to become true scaling winners.
- Over-designing before the message is right.

## Related
- [[Image-First Static Ads]] — starting from a visual style and reverse-engineering the copy
- [[Building Sub-Avatars From a Core Desire]] — the sub-avatars this process depends on
- [[Static Ad Concept Library and Quick Formats]] — layouts to build into
- [[Generating Static Ad Hooks and Headlines With AI]] — upstream headline generation
- [[Extracting Frameworks From Winning Ads Without Copying]] — the line between learning from and copying an ad
- [[Hit Rate vs Creative Volume]] — what to expect from a batch
