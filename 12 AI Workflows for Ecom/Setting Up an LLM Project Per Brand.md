---
title: "Setting Up an LLM Project Per Brand"
topic: "12 AI Workflows for Ecom"
stage: intermediate
tags: [llm, project-setup, knowledge-base, custom-assistant, prompts, static-ads]
summary: "Build one persistent LLM project per brand loaded with research, rules and winning examples, so every prompt inherits full context instead of starting from a blank chat."
---
# Setting Up an LLM Project Per Brand

## What it is
A brand project is a saved workspace in your LLM (a "project" or a custom assistant, depending on the tool) that holds a standing instruction block plus a knowledge base of brand documents. Every chat inside it starts with that context already loaded. A bare chat with no brand knowledge produces generic output; a loaded project produces work that reflects your customer, your claims and your proven ads.

## When to use it
As soon as you write ads for a brand more than once. Uploading the same brand briefs, research and reviews to each fresh chat costs time and eats into usage limits. Set up the project before you run any of the research, static or script workflows in this section.

## How (steps)
1. **Create and name the project** after the brand, and paste an instruction block that includes the brand name and what the store sells.
2. **Define the jobs in the instructions.** A useful block covers: learning about buyers from surveys and reviews, researching the market and competitors, generating ideas, writing scripts and critiquing copy against classic direct-response principles, and reading ad results (CTR, hold rate, hook rate, ROAS and spend) so wins and losses feed the next round. Add a rule that every answer must rest on the uploaded files and to name the principle or data point behind each recommendation.
3. **Upload the knowledge base:**
   - a human-written brand debrief (history, quirks, what makes it different); this beats any AI summary
   - the brand brief and the cleaned research document
   - avatars and sub-avatars
   - customer reviews and survey summaries
   - deep-research output and an ingredient or mechanism study for the hero product
   - summaries of direct-response books and swipe files
   - a "claims the brand will not make" file, which stops the model inventing authority or claims
4. **Choose a model by testing, not reputation.** Run the identical prompt sequence (research, avatar, product, tone) in two tools and compare. Judge on whether it follows the specific formula you asked for, avoids generic phrasing and fits the awareness level. Some tools accept very large files; others follow creative instructions more closely. Re-run the test whenever models update.
5. **Fork prompts with your own winners.** A static-ad prompt is mostly as good as the sample ads inside it. Duplicate the prompt, add strong ads you have found (in an ad library, filter recent image ads and sort by engagement), and remove examples you do not rate. Ask the model to break each new example down in a fixed structure: what stops the scroll, which sub-avatar it speaks to, which desire it touches, and what pushes the purchase.
6. **Iterate inside the loaded chat.** If a concept appeals to you, request further variations in that same conversation instead of starting over.
7. **Split projects as you grow.** One large project per brand is the right start; separate projects for particular jobs (rewrites, iterations, statics, video) serve you better over time.

## Example
A rough instruction block you can adapt:

> You are the creative and research partner for [brand], which sells [product] at [site]. Your jobs: understand the brand's customers from the attached surveys and reviews, research competitors, generate ad concepts, write and critique scripts using direct-response principles, and review any ad results pasted into the chat. Base every answer on the attached files. For each recommendation, name the file or principle it relies on. Never use a claim listed in the claims file. If you lack information, ask before guessing.

Say an outdoor-gear brand loads this plus its research. A request for headlines in a reversed-review style (a one-star "complaint" voiced by the very thing the product protects you from, like bad weather) returns usable lines on the first pass, and three more in the same style come back instantly because nothing needs re-uploading.

## Common mistakes
- Doing every job in an empty chat and uploading the files again each time.
- Skipping the human-written debrief and letting the model guess the brand story.
- Pasting an ad along with the page text around it, which leads the model to pick the wrong headline. Copy just the ad.
- Adding winning examples you cannot explain.
- Uploading paid material from others that you have no right to share.
- Treating a model comparison as permanent, or using multiple accounts to dodge usage limits; check provider terms or reduce the context instead.
- Judging a funny headline by your own laugh rather than by a test.

## Related
- [[AI Needs Human Judgment]] — why context and direction matter more than the prompt
- [[Setting Up the Research Document]] — the core file the project depends on
- [[Filling the Product Document With AI]] — a first task to run inside the project
- [[Researching Competitor Ads in Ad Libraries]] — where to find examples to fork into prompts
- [[Generating Static Ad Hooks and Headlines With AI]] — workflows that run on top of the project
- [[Product Integrity and Claims That Outgrow Reality]] — why the claims file belongs in the knowledge base
