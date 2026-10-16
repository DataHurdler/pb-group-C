# Lab 03 — Put AI to Work

**Time:** 50 minutes · **Work in:** individually, with your partner beside you
for a second opinion
**Module:** 03 · **Objective:** LO3

## What you'll do

Choose the kind of business work closest to your job and run a chain of
prompts on it, ending with a check of the output before you'd rely on it. Save
the prompts that work. You'll reuse them in the capstone.

| Track | You'll work on | Good for |
| --- | --- | --- |
| **A. Analyze** | Loop Laundry's 12-month sales data | Anyone who works with reports, numbers, or spreadsheets |
| **B. Communicate** | An unhappy customer email (or a non-confidential writing task of your own) | Anyone who writes to customers, staff, partners, or the public |
| **C. Innovate** | Your own idea or venture | Founders, product people, anyone developing something new |

## What you need

- Your AI assistant, in **one new chat** for your track (so the model keeps
  the context)
- [Practice data](practice-data.md) for Tracks A and B
- A calculator or spreadsheet (Track A), web search (Track C)
- Your [prompt log](../handouts/prompt-log.md)

**Data rule:** Track A uses sample data on purpose. Don't paste your
company's real figures, customer messages, or anything under NDA into a tool
your employer hasn't approved.

## Steps

**0. Choose your track (2 min).** Pick the one closest to work you actually do.

---

### Track A — Analyze (43 min)

1. **Ground (5 min).** Paste table A from the practice data and ask: *"Describe
   what this data contains in three bullets. Don't analyze it yet."* Check it
   read the columns correctly.
2. **Find the story (10 min).**
   > What are the three most important trends here for the owner of a small
   > laundromat? For each, give the numbers that show it and one possible
   > explanation. Label every explanation as a hypothesis.
3. **Ask for the numbers (8 min).**
   > Calculate the 12-month total for each service, wash-and-fold's share of
   > total revenue, and the average wash-and-fold order value for each month.
   > Show your working in a table.
4. **Check the math (10 min).** Compare its totals with the ones under table A
   in the practice data. Recalculate two monthly figures yourself. Note every
   error, however small. Did it say anything with more certainty than 12 rows
   of data can support?
5. **Turn it into a decision (10 min).**
   > Write a 150-word note to Dana: what this data suggests about her
   > delivery-subscription idea, what it can't tell her, and the one thing she
   > should start measuring now.

   Check: does the note claim causes the data can't show?

---

### Track B — Communicate (43 min)

*Using your own task instead? Swap in a non-confidential draft you need to
write (an announcement, a proposal, a hard email) and follow the same steps.*

1. **Ground (5 min).** Paste email B and Dana's options from the practice data.
   Ask: *"Summarize what this customer is upset about, most important first.
   Don't reply yet."*
2. **Draft (10 min).** Write a full brief: the goal (keep Priya as a customer),
   audience, constraints (only what Dana can offer, no promise that delays
   will never happen, under 150 words), format, and tone. Run it.
3. **Read it as the recipient (8 min).** In the same chat:
   > Now read your reply as Priya. What would still annoy you? What would make
   > you stay?

   Revise once based on what it says.
4. **Adapt for other audiences (10 min).** Ask for the same incident as (a) a
   three-bullet note to staff on what to change, and (b) a short public reply,
   as if Priya had posted a review. Compare tone and what each one leaves out.
5. **Check before sending (10 min).** Go through the final reply line by line.
   Does it promise anything Dana didn't offer? Invent a policy, a date, or an
   amount? Admit something that didn't happen? **Would you sign it?** Fix
   anything that fails.

---

### Track C — Innovate (43 min)

1. **Ground (5 min).** Paste a short brief of your idea: what it is, who it's
   for, what you know, your constraints, and what you're unsure of. End with:
   *"Confirm your understanding in three bullets. No advice yet."*
2. **Widen it (10 min).**
   > Give me 12 variations of this idea. Vary at least two of these in each:
   > customer, pricing model, channel, scale. Make at least three seem wrong at
   > first glance. Present as a table: variation, what changed, why it might
   > work.

   Star the two most interesting.
3. **Meet skeptical customers (10 min).** Ask the model to play three
   *different* potential customers reacting honestly, including why they
   wouldn't buy. Then ask: *"What should I ask real customers to find out if
   these objections are true?"*

   ⚠️ These are **hypotheses, not evidence.** The useful output is the list
   of questions.
4. **Run a pre-mortem (8 min).**
   > It's 18 months from now and this has failed. Give the five most likely
   > reasons, ranked, each with an early warning sign I could watch for in the
   > first three months.
5. **Check the facts (10 min).**
   > List every factual claim you've made in this conversation: numbers,
   > trends, competitors, regulations. Label each as known, likely, or guess.

   Check the **two** that matter most to your decision with a web search.

---

**6. Save what worked (5 min, all tracks).** Copy the prompts that gave
useful output into your prompt log, with a note on what you'd change.

## You're done when

Your prompt log has at least three prompts from your track, and you've
recorded what your check in step 4 or 5 found: errors in the math, promises in
the email, or checked claims.

## If you finish early

Try a second track's step 2 on the same material. Which kind of task did the
AI handle best, and which needed the most checking?

## Debrief questions

1. What did your check catch?
2. Would you use this on real work tomorrow? What would have to be true first?

---

### Instructor notes (remove from the participant copy)

- **Expected output, by track.**
  - **A:** Trends found: self-service down then recovering, wash-and-fold growing
    steadily (+35% Nov→Oct), average order steady at about $28. Check the
    arithmetic carefully: model accuracy on math can be unreliable and can
    change between versions ([Chen, Zaharia & Zou, 2024, *How Is ChatGPT's Behavior Changing over Time?*](https://doi.org/10.1162/99608f92.5317da47)). Any error is good teaching material. Watch for causal claims ("the new apartments
    caused…") that the data can't support.
  - **B:** Watch for drafts that over-apologize, promise "this will never
    happen again" despite the constraint, or invent a compensation amount.
    Step 5 should catch these.
  - **C:** Step 2 tables with real variety; if all 12 look alike, the person
    skipped "vary at least two". Treat the step 5 confidence labels with
    caution: LLMs tend to be overconfident when stating their confidence
    ([Xiong et al., 2024, *Can LLMs Express Their Uncertainty?*](https://arxiv.org/abs/2306.13063)).
- **Track balance.** If most people pick A or B, that's fine. If nobody picks C, mention it in the debrief as
  "for when you're developing something new".
- **Free-tier message caps:** continue in a new chat by pasting the step 1
  material again.
- **Debrief (10 min):** one volunteer per track, each answering "What did your
  check catch?" Then land the line: *if it goes out under your name, you
  checked it.*
