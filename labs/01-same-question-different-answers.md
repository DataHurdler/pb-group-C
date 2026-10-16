# Lab 01 — Same Question, Different Answers

**Time:** 30 minutes · **Work in:** pairs
**Module:** 01 · **Objective:** LO1

## What you'll do

Ask an AI assistant the same business question several ways and watch what
changes. By the end you'll be able to say *why* the answers differed, and
you'll have caught the model making something up.

## What you need

- Your AI chat assistant, open in a **new chat**. If you and your partner
  use different tools, even better
- [The Loop Laundry practice case](practice-case.md)
- Somewhere to take notes. [handouts/prompt-log.md](../handouts/prompt-log.md)
  works

## Steps

1. **Ask it cold (5 min).** Both partners, in new chats, type exactly:

   > Should a laundromat start a delivery subscription?

   Read both answers side by side. Note what's the same, what's different,
   and how much of it would actually help Dana.

2. **Ask again (5 min).** Regenerate the answer (or paste the same prompt into
   another new chat). What changed? What stayed the same?

3. **Give it the case (10 min).** Start a new chat. Paste the whole practice
   case, then ask:

   > Based only on the information above, what are the three biggest risks of
   > Dana's subscription idea, and what should she find out first?

   Compare with step 1. List two specific things the answer now includes that it
   couldn't have known before.

4. **Catch a confident error (7 min).** In the same chat, ask:

   > What do the main competitors in Dana's city charge for laundry delivery,
   > and how big is the local market?

   Sort every factual claim in the answer into three columns:
   **From the case** · **Plausible, but where would it get that?** ·
   **Admits it doesn't know**. The case names no city and no competitors, so
   any specific figure is invented.

5. **Say why (3 min).** Together, write one sentence that finishes: *"The
   answers changed because…"*

## You're done when

You have notes on all four comparisons and a one-sentence explanation of why
the outputs changed that mentions **context**.

## If you finish early

Ask the model: *"Which parts of your previous answer are you least confident
about, and why?"* Does its self-assessment match your column sort?

## Debrief questions

1. What did adding the case change, and what did it *not* fix?
2. Did the model ever say "I don't know" without being asked? What made it
   more or less likely to?

---

### Instructor notes (remove from the participant copy)

- **Expected output.** Step 1 gives a generic pros/cons list that could apply
  to any laundromat. Step 3 should mention the $15k budget, the lack of a
  vehicle, the no-hire constraint, the 600 new units, and the cannibalization
  worry. Step 4 often produces made-up price ranges and market sizes stated
  plainly, which is the moment to land the lesson.
- **Where pairs get stuck.** Some tools refuse step 4 or hedge heavily. That's
  a good outcome. Ask that pair to compare with a neighbour whose tool *did*
  produce numbers. Some tools search the web and cite real sources. If so, ask:
  "Is that source about Dana's city? Dana's city isn't named."
- **While circulating,** listen for "it's wrong" vs. "it didn't have the
  information." The second is the insight you want.
