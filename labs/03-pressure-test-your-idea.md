# Lab 03 — Pressure-Test Your Idea

**Time:** 50 minutes · **Work in:** individually, with your partner beside you
for a second opinion
**Module:** 03 · **Objective:** LO3

## What you'll do

Run your own idea through a chain of five prompts: ground it, widen it,
challenge it with simulated customers, imagine it failing, and check the facts.
Save each prompt that works. You'll reuse them in the capstone.

## What you need

- Your AI assistant, in **one new chat** for steps 1–4 (so the model keeps
  your idea in context)
- Your v1 prompt from Lab 02
- A web search in another tab, for step 5
- Your [prompt log](../handouts/prompt-log.md)

**Data rule:** describe your idea in general terms. No client names, unreleased
financials, or anything under NDA.

## Steps

1. **Ground it (5 min).** Write a short brief of your idea (what it is, who
   it's for, what you know, what constraints you have, what you're unsure of)
   and paste it as the first message. End with: *"Confirm your understanding in
   three bullet points. Don't give advice yet."* Fix anything it misread.

2. **Widen it (10 min).** Ask for variations that differ on purpose:

   > Give me 12 variations of this idea. Vary at least two of these in each:
   > customer, pricing model, channel, scale. Make at least three of them seem
   > wrong at first glance. Present as a table: variation, what changed, why it
   > might work.

   Star the two you find most interesting, including one you wouldn't have
   thought of.

3. **Meet skeptical customers (10 min).** Ask the model to play three
   *different* potential customers, reacting honestly to your idea, including
   the reasons they wouldn't buy. Then ask: *"What would I need to ask real
   customers to find out if these objections are true?"*

   ⚠️ These are **hypotheses, not evidence.** The model is guessing what people
   might say. Its output is a list of questions for real conversations.

4. **Run a pre-mortem (10 min).**

   > It's 18 months from now and this idea has failed. Write the five most
   > likely reasons, ranked by likelihood. For each, give an early warning sign
   > I could watch for in the first three months.

   Show your partner the top reason. Do they find it convincing?

5. **Check the facts (10 min).** Ask:

   > List every factual claim you've made in this conversation — numbers,
   > trends, competitors, regulations. Label each as: known, likely, or guess.

   Pick **two** claims that matter to your decision and check them with a
   web search. Note which held up.

6. **Save what worked (5 min).** Copy the prompts that gave useful output into
   your prompt log, with a note on what you'd change.

## You're done when

Your prompt log has at least three prompts from this lab, two checked claims
(true / false / couldn't confirm), and a list of questions for real customers.

## If you finish early

Ask the model to argue *for* the variation you starred in step 2 as if pitching
it to an investor in 100 words, then ask it to critique its own pitch. Which
critique was sharper, its own or the pre-mortem's?

## Debrief questions

1. Which of the five steps changed your thinking most?
2. How many of your checked claims held up?

---

### Instructor notes (remove from the participant copy)

- **Expected output.** Step 2 tables with real variety. If someone gets 12
  near-identical variants, they skipped the "vary at least two" constraint.
  Step 3 objections that sound plausible. Step 5 labels the model gives that are
  often overconfident, so verification usually turns up at least one wrong or
  unconfirmable claim.
- **Where people get stuck.** (a) Participants without a clear idea: give them
  a fallback, e.g. *"a service you wish existed in your neighbourhood"* or
  Loop Laundry. (b) Free-tier message caps: the chat is long by step 5. If
  they hit a cap, they continue in a new chat by pasting their step 1 brief.
  (c) Treating step 3 output as validation. Correct this out loud, once, for the
  whole room.
- **While circulating,** check for confidential details in step 1 briefs, and
  ask people what surprised them. The best answers make good debrief openers.
