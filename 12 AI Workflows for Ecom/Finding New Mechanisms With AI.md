---
title: "Finding New Mechanisms With AI"
topic: "12 AI Workflows for Ecom"
stage: intermediate
tags: [unique-mechanism, new-information, market-sophistication, llm, prompts]
summary: "A prompt workflow that uses your sophistication analysis to generate candidate mechanisms and new-information leads, which you then verify, tone-check and test."
---
# Finding New Mechanisms With AI

## What it is
In sophisticated markets the buyer has heard every plain promise. A new mechanism (a process, technology, ingredient, delivery method or combination that delivers the familiar result in a new way) restores belief, and new information (a fact the buyer had not heard, about where earlier fixes went wrong or what makes yours different) does the same without needing anything unique in the product. The theory is covered in [[Unique Mechanism - Problem Cause and Solution]] and [[New Information Angles]]. This note is the AI workflow for generating candidates.

## When to use it
- When your market is at a high sophistication stage and direct claims are saturated.
- When you have tested several angles without a breakthrough.
- After you have written a market sophistication analysis, because the model needs to know which claims are already used up.

## How (steps)
1. **Open a fresh chat.** No project is needed, and unrelated context contaminates the output.
2. **Attach your sophistication analysis** (as a PDF or document) and fill in the product name and page.
3. **Use a mechanism-finder prompt.** A template you can adapt:

> Using the attached market analysis, propose new mechanisms for [product]. Look for new delivery methods, unusual ingredients or materials, specific technologies or methods, fresh pairings of familiar components, and approaches that go against category norms. Judge every idea by one test: would it make the buyer believe again that [problem] can be solved, this time by this product? For each, give the reasoning, a sample line of copy and one hook. Rank them.

4. **Run a new-information pass** the same way: ask for facts the buyer probably does not know about the problem, why previous solutions fail, or why your approach works.
5. **Shortlist** the mechanisms that tie into a powerful desire your research already uncovered.
6. **Verify every finding** against primary sources and the product's documentation. Hyper-informed buyers will call out a hallucinated fact, and the information must be congruent with your product (do not claim a form of an ingredient is destroyed by digestion if that is the form you sell).
7. **Check tone with valence and intensity.** Negative-feeling messages can work, but a negative message delivered at full intensity turns into fear-mongering. Ask whether you would put it in front of your own parent or sibling; if it frightens you, it should not run. Telling the model to "be ethical" will not reliably stop fear angles, so review manually and re-prompt by naming the exact offending phrases, explaining why, and showing an example of the mildest tone you would accept.
8. **Build the curiosity structure.** Open on the finding plus an unanswered question, explain it with a credible source, then show how the product creates the condition that finding requires.
9. **Test.** What you get is a mechanism worth testing, not a finished ad; execution still decides.

## Example
Say a hypothetical kettle-descaler brand has tested "powerful" and "fast" angles for months without a breakthrough. A mechanism prompt ranks its slow-release formula first, tied to the desire for a kettle that stays clean without scrubbing, with a hook in the spirit of "your kettle might be the thing spoiling your tea". A dog-harness brand running the same prompt gets a single-click buckle and a clip that switches between chest and back positions, aimed at dogs that pull. Note the limit: the prompt often surfaces mechanisms already on the product page, confirming rather than discovering. Use it as a rich supply of ideas to test, not as evidence.

On tone: a sleep-product draft framed as a "brain health emergency" with a frightening statistic can be rewritten around the claim you can actually defend (light at night disrupts the hormones that drive deep sleep).

## Common mistakes
- Running the prompt in a cluttered project chat full of unrelated context.
- Treating ranked output as validated because it sounds technical.
- Introducing too much jargon; one new term creates curiosity, five create confusion.
- Shipping fear-based framings because the model produced them.
- Using information that contradicts your own product.

## Related
- [[Unique Mechanism - Problem Cause and Solution]] — what a mechanism is and how it works in copy
- [[Types of Unique Mechanism]] — categories to steer the prompt toward
- [[New Information Angles]] — the theory behind the new-information pass
- [[Market Sophistication Stages]] — the analysis you attach to the prompt
- [[Emotional Valence and Intensity]] — the tone check
- [[Product Integrity and Claims That Outgrow Reality]] — keeping mechanism claims honest
