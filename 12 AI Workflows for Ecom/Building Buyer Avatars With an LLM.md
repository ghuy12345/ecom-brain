---
title: "Building Buyer Avatars With an LLM"
topic: "12 AI Workflows for Ecom"
stage: beginner
tags: [avatars, personas, llm, research, reviews]
summary: "Feed an LLM cleaned research, reviews and brand information to draft a primary avatar and supporting avatars, then check and correct them against raw customer language."
---
# Building Buyer Avatars With an LLM

## What it is
An LLM can turn your research document, reviews and brand information into a written buyer avatar in a few minutes, and can propose a primary avatar plus a couple of supporting ones from the same inputs. It is no substitute for research; its job is to help you use the research you already gathered. The quality of the avatar tracks the quality of what you feed it: a thin research file gives a thin avatar.

## When to use it
- After you have gathered real customer language (reviews, survey answers, forum quotes) and cleaned your research document.
- When you want several candidate buyers side by side before committing creative to one.
- When an existing avatar feels stale and you have new data to feed in.

For what a good avatar contains, see [[Avatar Fundamentals - Beyond Demographics]] and [[Building Core Avatars From Desires]].

## How (steps)
1. **Collect inputs:** a short brand brief (history, positioning, products), your research document, exported reviews and any survey or post-purchase data. Keep review exports to a manageable size (a few hundred rows, sorted so the richest ones are first) so the model is not overloaded.
2. **Clean the research document.** Strip out unfilled template headings, logos, random images, stale notes, offer brainstorms, audit notes on the site or creative, and anything unrelated to the buyer or the product. Retain your brain-dump, headline and avatar sketches, the main research, product facts and competitor notes. Export as a PDF.
3. **Prompt in two steps or one.** First set context and attach the files; then ask for the avatar. Or use one combined prompt that asks for a primary avatar and two supporting avatars written out in full. If you attach more files than the prompt mentions, update the count.
4. **Pick a focus if asked.** If the model wants to know which buyer to centre on, choose one yourself or take whichever has the strongest backing in your data.
5. **Cross-check against raw language.** Read the avatar next to actual reviews and survey answers. Does the way it describes fears and desires match words customers really used?
6. **Correct a wrong avatar.** When a persona contradicts what you have observed, give the model the evidence (for example "buyers are mostly 35 to 50, not early twenties; here are five quotes") and ask it to rebuild that persona.
7. **Save the result** into your project knowledge base. Formatting varies from run to run, so keep the version you approved.
8. **Plan how to use several avatars.** Write separate angles per avatar, or test the same script against different avatars as a deliberate test axis.

## Example
Say a postnatal-recovery brand uploads its research, 400 reviews and brand details and asks for three personas. It gets a first-time mother in the weeks after birth, a grandparent buying it as a gift, and an experienced parent on their second child who just wants something reliable. The first draft makes the new mother unrealistically young. Pasting in survey age data and a handful of review quotes fixes it. The grandparent persona is new to the team, so it goes into the research backlog to validate before any ads are written for it.

## Common mistakes
- Expecting the avatar to solve everything, when it is only a working hypothesis.
- Approving it simply because it agrees with your existing assumptions. The model may simply be echoing your uploads; there is no independent check unless you compare against raw customer words.
- Keeping stale or unrelated notes in the research file, which drags the avatar off target.
- Feeding poor reviews and expecting a sharp avatar. If reviews are weak, collect better ones or look at the product.
- Generating three avatars with no plan for which gets tested first.

## Related
- [[Avatar Fundamentals - Beyond Demographics]] — what the avatar should capture
- [[Building Sub-Avatars From a Core Desire]] — splitting a core avatar into testable segments
- [[Setting Up the Research Document]] — the input that most affects avatar quality
- [[Summarising Customer Surveys With AI]] — turning survey data into usable inputs
- [[Setting Up an LLM Project Per Brand]] — where the finished avatars should live
