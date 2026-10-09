---
title: "Filling the Product Document With AI"
topic: "12 AI Workflows for Ecom"
stage: beginner
tags: [product-document, llm, research, reviews, knowledge-base]
summary: "Use a brand-loaded AI project to draft the product document quickly, then audit every field, because the output is an educated guess rather than research."
---
# Filling the Product Document With AI

## What it is
The product document maps each feature to a benefit and then to the desire it serves (the template itself lives in [[The Product Document - Feature to Benefit to Desire]]). An AI project can fill a first draft of that template in minutes from your reviews, research and brand questionnaire. The catch: every answer is an assumption the model inferred, not something it verified. That is why fields in a good template are framed as "assumed" until you confirm them.

## When to use it
- After you have filled at least one product document by hand, so you understand what each field is asking.
- When you onboard a new product or brand and need a fast starting point before deeper research.
- When you want a second opinion to compare against your own manual version.

Do not use it as a replacement for the manual exercise the first time. The reading and thinking you do while filling the document changes how you understand the product; letting a model do it for you skips that learning.

## How (steps)
1. **Open a brand project** in an assistant that supports projects (see [[Setting Up an LLM Project Per Brand]]). On a free plan, an ordinary chat with those files uploaded does the job, only less neatly.
2. **Write project instructions** describing the brand and the jobs: understanding customers and market trends, competitor analysis, creative ideation, script and copy writing, and ad performance review using metrics such as spend, ROAS, hook rate, hold rate and CTR. Tell it to base every answer on the attached files and the direct-response principles you supply, and to say when a recommendation relies on a specific principle.
3. **Upload the knowledge base:**
   - customer reviews (strongly preferred; if you have none, use the research document but go and get real reviews)
   - your research document
   - a short brand brief or questionnaire
4. **Paste the blank template** and ask the model to complete it. Add a line such as: "List any field you could not fill and any questions you have for me."
5. **Audit field by field.** For each line ask: is this accurate, is it specific to this product, and is there evidence in the reviews or research? Mark confirmed fields, rewrite weak ones and flag guesses for follow-up research.
6. **Answer its questions** and re-run only the fields that were thin.
7. **Store the final version** back in the project knowledge base so later prompts use the corrected document, not the draft.

## Example
Say a pet-supplement brand uploads 300 reviews, its brand brief and a research document. The model fills the feature-benefit-desire chain quickly, but lists "supports joint health" as the main desire. When you check the reviews, owners talk far more about their older dog playing again and climbing stairs without hesitation. You rewrite the desire in those words, mark the joint-health line as a functional benefit, and add a research task to find more language about the dog "acting young again". The AI saved an hour of typing; the audit produced the insight.

## Common mistakes
- Using the AI version first and never doing the work by hand, so you cannot tell good output from plausible output.
- Running it without customer reviews, which leaves the model guessing from the product page and returns generic benefits.
- Accepting every field because the formatting looks complete.
- Leaving the draft in the knowledge base after you corrected it elsewhere, so later prompts inherit the errors.
- Skipping the "what could you not fill?" instruction, which hides the gaps the model papered over.

## Related
- [[The Product Document - Feature to Benefit to Desire]] — the template and its logic
- [[Understanding Your Product - Physical vs Functional Value]] — what to look for when you audit the output
- [[Setting Up an LLM Project Per Brand]] — the project this task runs in
- [[Review Mining - Your Reviews and Competitors' One-Star Reviews]] — the input that makes the draft accurate
- [[AI Needs Human Judgment]] — why the audit matters more than the draft
