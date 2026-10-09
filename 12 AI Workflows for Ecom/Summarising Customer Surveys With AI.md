---
title: "Summarising Customer Surveys With AI"
topic: "12 AI Workflows for Ecom"
stage: intermediate
tags: [surveys, custom-assistant, voice-of-customer, personas, llm]
summary: "Summarise written survey answers into frequency-ranked, quote-backed themes with a custom assistant, then turn the summaries into a shareable assistant the team can question."
---
# Summarising Customer Surveys With AI

## What it is
A customer survey can return thousands of written answers. Reading them all matters, but you also need a structured summary: which themes come up most, how often, and in whose words. A custom assistant (a custom GPT or a project) set up to act as a data analyst can produce theme lists ranked by frequency with direct quotes as evidence. Once the summaries exist, the same assistant becomes a tool your team can question about its own customers.

## When to use it
After a survey has closed and you have exported the responses (see [[Customer Survey Giveaways - When and How to Run One]]). Use it alongside, not instead of, the analysis in [[Analysing Customer Survey Responses]].

## How (steps)
1. **Create a custom assistant** named for the brand. Its instructions: turn survey responses into themes, insights and overall sentiment.
2. **Prepare each open-text column.** Current models accept spreadsheets directly; with older file limits, copy each column into its own sheet, remove the question row and export it. Keep website-improvement and product-improvement questions separate.
3. **Use one prompt skeleton per topic.** A template to adapt:

> Act as a data analyst. Group these answers about [topic] into common themes. Order the themes from most to least frequently mentioned. For each, write a one-line definition and include three to five direct customer quotes as evidence. Finish with an overall summary.

   Run it for topics such as: why they bought, what worried them before buying, how they see price and value, why they picked you instead of a competitor, what difference the product made to their day-to-day, how they discovered and purchased it, website fixes, and product fixes. For the life-impact, competitor and product-fix topics, require the final summary and ask for actionable recommendations.
4. **Paste each result into a summary sheet** with clear headings.
5. **Re-run if needed.** Output varies between runs; loading all data at once gives broadly similar results to one topic at a time, so choose based on effort and re-run until the result is stable.
6. **Build a shareable assistant.** Upload all the summaries, plus, if you like, your reviews, rivals' reviews and market research. Add conversation starters based on your survey questions, such as "Which product would buyers want from the brand next?" or "What ads would convince a new customer?"
7. **Optional persona pass.** A heavier prompt can draft a buyer-psychology profile: a short demographic sketch and the main problem, leading emotions and fears, how fears affect relationships, past solutions and why they failed, an ideal-outcome scenario, who they blame and top objections, all in the prospect's own voice. Because this invents soundbites, treat it as hypotheses and use the frequency summaries as evidence.

## Example
Say an outdoor-apparel brand surveys a couple of thousand buyers. The purchase-reason summary ranks comfort first, with quotes, followed by fit. The product-improvement summary repeatedly asks for more sizes, which becomes input for the product roadmap. The team then asks the shared assistant for ad ideas aimed at buyers who struggle with fit and treats the answers as ideation, not finished creative.

## Common mistakes
- Treating the persona pass as data rather than hypothesis.
- Merging website and product improvement questions, which muddies both.
- Sharing an assistant built on raw responses by public link when the data includes names or personal details. Remove personal data first and share privately.
- Reading only the summaries and never the raw answers.
- Running one prompt once and treating the output as final.

## Related
- [[Analysing Customer Survey Responses]] — the wider analysis method
- [[Customer Survey Giveaways - When and How to Run One]] — collecting the data
- [[Voice of Customer and Psychographic Research]] — where survey language fits in research
- [[Building Buyer Avatars With an LLM]] — using the summaries as avatar inputs
- [[Setting Up an LLM Project Per Brand]] — adding the summaries to the brand knowledge base
