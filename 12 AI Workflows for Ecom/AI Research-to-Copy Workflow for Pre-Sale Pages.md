---
title: "AI Research-to-Copy Workflow for Pre-Sale Pages"
topic: "12 AI Workflows for Ecom"
stage: intermediate
tags: [pre-sale-pages, advertorials, master-brief, llm, research, mechanism]
summary: "A pipeline that moves from AI-assisted customer and competitor research to a master brief, a chosen mechanism and a section-by-section pre-sale page draft."
---
# AI Research-to-Copy Workflow for Pre-Sale Pages

## What it is
A repeatable pipeline for writing advertorials, listicles and other pre-sale pages with AI: research, then a mechanism, then one master brief, then a full draft, then targeted refinement. The split of labour is deliberate. A deep-research mode handles web crawling and long documents; a strong writing model handles mechanisms, drafts and rewrites; you keep the strategic calls (angle, mechanism, editorial direction).

## When to use it
When you are building a pre-sale page for a proven or promising angle and want a draft in hours rather than days. It also works for long-form ads and email sequences, because the master brief is reusable context for any asset. For choosing the page type, see [[Choosing a Pre-Sale Page Type]].

## How (steps)
1. **Customer research** in deep-research mode: demographics and beliefs, solutions already tried, forgotten attempts, and the villain the customer blames. Export as a document.
2. **Competitor research** while that session is still open: who they target, funnels, core messaging, repeated hooks, pricing, what customers love and dislike. Export.
3. **Mechanism ideation.** Attach the research and request five or more mechanisms aimed at problem-aware buyers. Spell out that a mechanism has two halves (the reason earlier attempts failed, and the reason this one succeeds) and that the buyer lacks one key piece of knowledge. Step away, then pick the most believable.
4. **Build the master brief.** Ask the model to combine everything into one document with:
   - **Target market:** age, location, income, where they spend time online, how many years they have struggled and how much money they have sunk into fixes; main and secondary awareness level.
   - **Psychographics:** pains in customer words grouped as physical, emotional, social, financial and time; the vivid future state; how they describe themselves, labels they accept and reject, phrasing that feels trustworthy versus salesy; primary promises in "get X without Y" form.
   - **Objections:** for each common objection, the exact phrasing, the belief behind it and how the copy answers it.
   - **Existing solutions:** what they tried, what failed, and the emotional residue (frustration, feeling foolish).
   - **Competitive gaps and white space.**
   - **Chosen mechanism:** the problem side, the solution side and a name.
   - **Copy guidelines:** tone, voice, a reading level around grade 7 to 8, words to use and avoid.
   Leave out market-size figures and strategy filler.
5. **Open every copy session by pasting the whole brief.** Have the model read it and acknowledge it before you hand over the writing task; never count on it remembering a previous session.
6. **Draft the page** from the chosen mechanism angle. If you are replacing an existing template, attach a screenshot of it. To emulate a page you admire, attach a screenshot and ask it to borrow only the tone, layout and flow, while all content stays specific to your brand.
7. **Generate headlines:** around fifteen under fifteen words across fear, curiosity, problem, before-and-after, revelation and social-proof styles, in the avatar's own language.
8. **Refine by section** with focused prompts: make the problem section rawer and more concrete, in the customer's own phrasing; simplify the mechanism until a friend would get it from a single sentence; write ten benefit-specific button labels instead of "buy now". For anything else, name the section and paste your feedback with a request to rework it.
9. **Ship at roughly 70 percent** and let test data tell you what to polish.

## Example
Say a sleep-aid brand runs steps 1 to 4 and chooses a mechanism built on the idea that people fail with melatonin because they take it at the wrong time. The brief records that buyers call themselves "wired but tired" and reject the label "insomniac". Every later prompt inherits that, so the advertorial opens on a scene in their language and avoids a word that would have pushed readers away.

## Common mistakes
- Writing copy before the research is complete.
- Accepting the first mechanism instead of generating several and choosing the most believable.
- Polishing every line inside the model before any traffic has seen the page.
- Sending the same ads to a listicle funnel that you send to the product page; each funnel needs creative that matches it.
- Using AI-invented testimonials; every piece of proof has to come from actual buyers.

## Related
- [[Advertorial Landing Pages]] — the page format this most often feeds
- [[Listicle Landing Pages]] — another common output of the pipeline
- [[Research-Led Landing Page Messaging]] — turning research into page copy
- [[Voice of Customer and Psychographic Research]] — the research step in depth
- [[Unique Mechanism - Problem Cause and Solution]] — the two-part mechanism logic
- [[Handling Objections in Copy]] — using the objection section of the brief
