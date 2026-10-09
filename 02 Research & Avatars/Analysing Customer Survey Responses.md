---
title: "Analysing Customer Survey Responses"
topic: "02 Research & Avatars"
stage: intermediate
tags: [survey-analysis, customer-feedback, spreadsheet-tally, data-cleaning, insights]
summary: "Export survey responses, clean them and tally them in a sheet you build yourself, summarise multiple-choice results correctly and salvage heavily customised surveys - then turn the findings into angles, FAQs and fixes."
---
# Analysing Customer Survey Responses

## What it is
When a survey closes you are left with a raw spreadsheet. Analysis turns it into a feedback spreadsheet: tallied multiple-choice results, written answers you can filter by choice, a shortlist of your most engaged customers and summaries of the written answers. One good spreadsheet can feed angles, page copy, FAQs and even stock planning.

How to run the survey is in [[Customer Survey Giveaways - When and How to Run One]]; for condensing the written answers with AI, see [[Summarising Customer Surveys With AI]].

## When to use it
- Immediately after a survey or giveaway ends.

## How (steps)
1. **Export and import.** Export entrants and import them into a feedback spreadsheet of your own (one tab for raw data, one for tallies and summaries) as a new sheet.
2. **Duplicate before touching anything.** Work only on a second copy so the untouched original can always be restored.
3. **Strip the clean copy** to what you need: remove tracking columns (IP, location and similar) and anything after the final question. Delete any internal test entries.
4. **Shape the data to fit your tally sheet, never the reverse.** Reshape the data to fit the sheet you are building. Order the columns consistently: contact details first, then the questions. Give every multiple-choice question an empty helper column to its left, and place each "why" answer directly after the choice it refers to. Keeping them side by side is what lets you filter (for example, to everyone who picked "product images" as the top improvement) and read all their reasons.
5. **Handle deviations precisely.**
   - Setting up the tally: set up a sheet with one row per answer option, copy each spelling character for character from the survey tool, and count with a formula. If you count by exact text match, an unlisted option goes uncounted, so add a row for any option you missed and extend the formula.
   - Changed wording: use your actual question wording in the sheet.
   - Wrong column order: move the column into place.
   - Removed question (often pricing): delete that block.
   - Get the true option list from the survey builder, or apply a filter to the column and look at the distinct entries.
6. **Paste and verify.** Paste the clean sheet into the raw-data tab. Hover over a column to see how many answers it holds. A figure lower than the number of entrants is expected because some people skip questions (say 270 answers from 290 entrants).
7. **Fill the top answers.** Go through the multiple-choice questions one by one and paste the answer with the highest count into the summary as a value. When "Other" wins, go straight to the free-text answers - something is missing from your options.
8. **Read percentages correctly.** Every percentage is out of the people who answered that particular question, so two questions with different answer counts are not directly comparable. Remember too respondents may have been unable to correct a wrong click, so tallies are directional.
9. **Shortlist your most engaged customers** - the longest writers. Study what they said, and think about a thank-you note or a small gift.
10. **Triage customised surveys.** When a survey departs a long way from your usual questions, your standard charts and summaries stop fitting. Do not rebuild them all. Salvage the raw data, duplicate the question-plus-options column pair for each custom question, check formula ranges start on the first data row (a blank count usually means a range or spelling problem), and focus on summarising the written answers.
11. **Summarise written answers** only - multiple choice already has counts. Give each summary row a plain-English label.
12. **Route findings.** Discovery-channel results inform channel mix; "why did you buy" and "main benefit" answers feed angles; concerns feed objection handling; "how has it changed things" gives testimonial-style copy; website answers become page fixes and FAQs; product answers often turn out to be restock or new-product requests.

## Example
Say a kitchenware brand closes a survey with a few hundred entrants. The tally shows social ads as the leading discovery channel, most call pricing fair and "no concerns" is the top worry answer. Filtering "why did you buy" shows answers clustering on hosting friends and gifting rather than on materials. Concerns that do exist centre on durability; website comments ask for size guidance; product comments are mostly requests for more colours. One survey yields a new gifting angle, a couple of FAQ additions, a size-guide fix and a range idea.

## Common mistakes
- Editing the only copy of the export.
- Reshaping your tally sheet to match a messy export instead of the other way round.
- Missing a new answer option because its spelling differs by a space or capital.
- Setting percentages side by side for questions that got unequal numbers of responses.
- Rebuilding a full tally sheet for a one-off custom survey.
- Passing around, or feeding public tools, files that still hold names and personal details.

## Related
- [[Customer Survey Giveaways - When and How to Run One]] - running the survey that produces the data
- [[Summarising Customer Surveys With AI]] - summarising the written columns
- [[Giveaway Draw, Winners and ROI]] - judging whether the giveaway paid off
- [[Voice of Customer and Psychographic Research]] - using the quotes in copy
- [[Handling Objections in Copy]] - answering the concerns uncovered
- [[Proof Types and Placement on Pages]] - placing testimonial answers on pages
