---
title: "Drafting Video Ad Scripts With an LLM"
topic: "12 AI Workflows for Ecom"
stage: intermediate
tags: [video-scripts, llm, hook-bridge-hold, learnings, awareness-levels, claims]
summary: "Draft video ad scripts with an LLM by processing learnings first, supplying four specific inputs, and requesting three hooks and bridges over one shared hold, then overriding the model on awareness levels."
---
# Drafting Video Ad Scripts With an LLM

## What it is
A structured prompt flow for short video ad scripts. The model writes three hook variations, a bridge matched to each hook, one shared hold (the body of the ad), a call to action and a strategy note. It gets you roughly 70 to 80 percent of the way; the remaining human pass is covered in [[The Human Pass on AI Video Scripts]].

## When to use it
When you have a defined angle and avatar, research documents ready, and results from earlier ads on the same angle. If you cannot produce huge volume, the quality of each script matters more, so the process is built around intent rather than speed.

## How (steps)
1. **Process learnings first.** Build the prompt so it will not draft anything until you have covered: which previous ads on this angle succeeded or failed, which ones the platform spent on, their main numbers, your read on why viewers cared or shrugged, and anything new you learned. See [[Learnings From Losing Ads]].
2. **Supply four inputs:**
   - angle and avatar
   - your hypothesis for this ad
   - information specific to the angle
   - supporting files: the mechanism work, your new-information research, the product document, and customer evidence like reviews
3. **Let the model audit claims before writing.** It should question every number and study. Keep customer-count claims to what you can prove: write "thousands" only when the true number sits in that range, fall back on trial results when those are your only evidence, and otherwise leave numbers out.
4. **Request the output in five parts:**
   - three hooks, every one paired with a shot direction and a phrase to search stock libraries with
   - three bridges, one per hook, so the variants differ enough to be treated as distinct creatives
   - one shared hold running through objection, claim, proof, main benefit, extra benefit, then a guarantee or price framing
   - a call to action
   - strategy notes: what varies and what is fixed, running time, the mechanism, the target awareness level, and where to show rather than tell
5. **Aim for about 45 seconds total** for a short-form script.
6. **Override awareness labels.** Models routinely mislabel awareness levels. A hook built on a little-known fact sits closer to unaware or problem aware than product aware. A truly unaware headline must not name the problem at all.
7. **Use a correction prompt when it slips.** Paste the bad line, explain why it is the wrong level ("it names the problem, so it is problem aware"), ask for three to five replacements, and make the model explain what it got wrong and apply the fix for the rest of the chat.
8. **Assemble the brief line by line:** the hook and bridge options first, the common hold after them, and shot notes beneath every line. Work through the objection, claim, proof and benefit lines yourself instead of pasting them.
9. **Research more once you have direction.** The draft often shows you exactly what to go and find.

## Example
Say a sleep-support brand's best static takes a tiny share of spend, had a CTR under 1 percent, high frequency and a basic design. Even though it was profitable, it is classed as a loser because it will not scale: it told the viewer something was easy instead of showing it. The next step is a video that demonstrates and explains. The model drafts three hooks (a science discovery about what changes in the body at night, a "why trying harder backfires" frame, and a validation hook that it is not your fault), bridges that name a hidden cause as the villain, and a hold that ends on a guarantee. The objection line "you've tried supplements before" is too vague, so the strategist swaps in the specific things this buyer has already tried, taken from forum threads.

## Common mistakes
- Writing before learnings are processed.
- Accepting generic objection lines instead of specific ones.
- Scripts that read as written rather than spoken.
- Figures drifting between assets; re-verify product-document numbers every time.
- Using clinical claims from a product document without checking you are allowed to make them.
- Over-specific numbers that exclude part of the audience.
- Working on visuals before the copy is right.

## Related
- [[Cold-Audience Video Ad Script Structure]] — the script structure the prompt follows
- [[Writing the Bridge After the Hook]] — why bridges vary with hooks
- [[Market Awareness Levels]] — the judgment the model gets wrong
- [[Unaware Ads - Identity Hooks and Openers]] — writing true unaware hooks
- [[The Human Pass on AI Video Scripts]] — finishing the draft
- [[Rewriting a Dying Ad With an LLM]] — the same flow applied to a near-winner
