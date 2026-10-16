# Lab 02 — Rescue a Weak Prompt

**Time:** 35 minutes · **Work in:** pairs (steps 1–4), then individually (step 5)
**Module:** 02 · **Objective:** LO2

## What you'll do

Diagnose what's missing from three weak prompts, rebuild one with the prompt
brief, and prove the rebuild is better. Then write the first version of a
prompt for a task from your own work.

## What you need

- Your AI assistant
- [The Loop Laundry practice case](practice-case.md)
- [The prompt brief](../handouts/reference.md#the-prompt-brief) (the six
  parts: **goal, context, audience, constraints, format, example**)

## Steps

1. **Diagnose (8 min).** For each prompt below, mark which of the six parts
   are missing. Don't run them yet.

   - **A.** *Write a flyer for a laundry delivery service.*
   - **B.** *I run a laundromat and I'm thinking about adding delivery. Give me
     a pricing strategy.*
   - **C.** *Act as a world-class marketing expert. Write the best possible
     email to my customers. Make it amazing.*

2. **Rebuild (12 min).** Pick **one** prompt. Rewrite it so all six parts are
   present, using facts from the practice case. Run it in a new chat.

3. **Prove it (5 min).** Run the original weak prompt in another new chat.
   Put the two outputs side by side. Name three specific improvements, and
   which part of the brief caused each.

4. **Let it interview you (5 min).** Start a new chat with your rebuilt prompt,
   but add at the end:

   > Before you answer, ask me up to five questions about anything you'd need to
   > know to do this well. Wait for my answers.

   Answer from the case. What did it ask that you hadn't thought to include?

5. **Version 1 of your own prompt (5 min, individually).** Take the task you
   named this morning. Write a prompt for it using all six parts (for example,
   *draft this week's update to my team*, *summarize what customers complained
   about*, or *list the three questions I should answer before launching*).
   Describe anything sensitive in general terms. **Don't run it yet.** Save it
   in your prompt log; you'll use it after lunch.

## You're done when

You have a weak/rebuilt output pair with three improvements labelled by brief
part, and a saved v1 prompt for your own task.

## If you finish early

Take prompt C. Run it twice: once with "Act as a world-class marketing expert"
and once without, keeping everything else identical. Did the role line change
the output as much as adding context did?

## Debrief questions

1. Which missing part hurt the output most?
2. What did the model ask you in step 4 that surprised you?

---

### Instructor notes (remove from the participant copy)

- **Expected diagnosis.** A is missing nearly everything. B has some context
  but no audience, no constraints (budget, no vehicle), and no format. C has a
  role and enthusiasm but no goal, context, audience, or format. It's the most
  common pattern in the wild, and the one to dwell on.
- **Where pairs get stuck.** Rebuilt prompts that paste the whole case but
  never say what output is wanted. Ask: "What should Dana be holding when this
  is done?"
- **The early-finisher task** usually shows that the role line matters much less
  than context and format. Collect one example for the debrief.
- **While circulating,** check that step 5 prompts are about a real task and
  contain nothing confidential.
