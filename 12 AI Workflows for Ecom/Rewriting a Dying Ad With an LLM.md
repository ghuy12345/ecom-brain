---
title: "Rewriting a Dying Ad With an LLM"
topic: "12 AI Workflows for Ecom"
stage: intermediate
tags: [learnings, iteration, video-scripts, llm, text-on-screen, mechanism]
summary: "Turn an ad that spent well and then faded into a new script by diagnosing what failed, feeding those learnings to a loaded LLM project, and rewriting for belief, pacing and mechanism."
---
# Rewriting a Dying Ad With an LLM

## What it is
A near-winner is an ad that picked up spend, showed promise and then faded. It is often more valuable than a fresh idea, because the market has already told you something resonated. This workflow turns a structured learnings review into a rewrite brief for an LLM, keeping what drew attention and fixing what lost people.

## When to use it
When an ad attracted meaningful spend and early signs (hook rate, purchases) before declining, and you can name at least one hypothesis for why. Rank your learning sources: a clear winner teaches the most, a spend-then-die ad is next, and a zero-spend ad is hardest to read (still review it, since the platform never judged it worth showing).

## How (steps)
1. **Hold a learnings review.** Record and transcribe it if you work in a team, then use a standing prompt to summarise the transcript into learnings. If you are new to this, set a 20 to 30 minute timer and study the ad: what grabbed attention, where people likely dropped off, what was missing.
2. **Work inside a pre-loaded project rather than a blank chat.** Its knowledge base needs to hold brand information, customer research and summaries of copywriting classics such as *Breakthrough Advertising*.
3. **Warm the model up on the audience.** Ask it to research community threads about the avatar before writing, and to give you the links. Spend 10 to 15 minutes reading those threads yourself.
4. **Write a full rewrite prompt** (expect this to take 30 to 45 minutes). Cover: the original ad and its results, the transcript and your learnings, your theory about what caught attention, its main weakness, a request to make it more convincing and simpler to follow using the buyer's own words, which mechanism must appear ahead of the product, and the format you want.
5. **Keep the structure that showed promise.** Ask for a similar shape but stronger persuasion: tell the story first, then the mechanism, and only then ease toward the product.
6. **Read it as the customer.** Copy the script into your own document, go through it line by line, and ask for specific fixes with specific reasons. Delete filler phrases that mean nothing.
7. **Check readability.** Aim for around grade six or lower.
8. **Brief it in segments.** Colour-code each section and add shot notes next to it so the editor understands what every part is for; include three hooks.

## Example
Say a sleep-aid brand has an ad whose hooks draw spend by naming a hidden cause and moving blame from willpower to biology. Suppose it fades for three reasons: the belief was never established (the explanation got one line), the product showed up too soon and lost viewers who needed more context, and the product's own exclusive ingredient was never named.

The rewrite is a slower text-on-screen ad of about two minutes, set to music without narration. It agrees with the viewer in its second line, opens against the category ("here is why waking at 3 a.m. is not a willpower problem" instead of "sleep through the night tonight"), names and quantifies the mechanism, holds the product back until roughly the last third, and closes with a call to action that under-promises. Choose text-on-screen if earlier ads in that format held attention; viewers read the text in their own inner voice. For a tired, sceptical audience, candour and accepting where they are now beats high-energy promises. Models can sometimes supply a sharper analogy than you would write yourself, such as a stress signal acting like a smoke alarm that keeps going off after the fire is out.

## Common mistakes
- Letting the LLM play strategist instead of directing it with your own diagnosis.
- Expecting a one-shot script to be good.
- Moving from a one-line problem straight into the pitch.
- Leaving the differentiating ingredient or mechanism unnamed.
- Accepting clinical numbers you have not checked; confirm both the figure and that you are allowed to use it.
- Skipping the reading of source threads the model found.

## Related
- [[Learnings From Losing Ads]] — diagnosing why an ad died
- [[Feedback Loops - Learning Why an Ad Worked]] — building the learnings habit
- [[Iterating a Winning Ad in Order]] — the sequence for iterating on what works
- [[Drafting Video Ad Scripts With an LLM]] — the base script workflow
- [[Breakthrough Advertising Ch 9 - Gradualization - Part 1]] — why belief must be built before the product appears
