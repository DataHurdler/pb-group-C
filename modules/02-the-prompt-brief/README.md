# Module 02 — The Prompt Brief

Status: draft
Time: 10:35–11:50 (75 min — lecture 25 / activity 50)
Objective: LO2

## Objective

By the end of this module, participants will be able to **write** a prompt that
specifies goal, context, audience, constraints, and format, and **diagnose**
which of these is missing from a weak prompt.

## Why this module is here

Module 01 showed that context drives output. This module turns that into a
repeatable habit: a six-part brief, the same thing you'd give a capable new
hire on their first day. It's the core skill of the course. Modules 03 and 04
assume it, so it sits in the morning, before the mid-afternoon dip in
alertness ([Monk, 2005, *The post-lunch dip in performance*](https://pubmed.ncbi.nlm.nih.gov/15892914/)).

## Outline

| Min | Segment | What happens | Who's talking |
| --- | --- | --- | --- |
| 0–5 | Hook | (The analogy is Anthropic's: "a brilliant but new employee who lacks context", [Anthropic, *Prompting best practices*](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices).) "You've hired a brilliant contractor who started this morning and knows nothing about your business. What would you tell them before asking for a pricing strategy?" Collect answers from the room; they will name most of the six parts | Instructor, room |
| 5–25 | Teach | The six parts of the brief (below); one worked rebuild of a weak prompt about Loop Laundry, live; "let it interview you" | Instructor |
| 25–60 | Activity | [Lab 02 — Rescue a Weak Prompt](../../labs/02-rescue-a-weak-prompt.md) | Pairs, then individually |
| 60–75 | Debrief | Three pairs show weak vs. rebuilt; room names which part caused each improvement; quick poll on the role-line experiment | Pairs, then instructor |

### The six parts of the brief

| Part | The question it answers | Example (Loop Laundry) |
| --- | --- | --- |
| **Goal** | What do I want, and what will I do with it? | "Help me decide whether to pilot a delivery subscription" |
| **Context** | What does it need to know? | The case: numbers, the new apartments, what Dana doesn't know |
| **Audience** | Who's the output for? | "For Dana, a practical owner, not a business-school reader" |
| **Constraints** | What limits apply? | "$15k max, no full-time hire, no vehicle, decision in 3 months" |
| **Format** | What should it look like? | "A table of three options with cost, risk, first step; under 250 words" |
| **Example** | What does good look like? *(optional, powerful)* | A short sample of the tone or structure you want |

Two points to make explicitly:

- **"Act as a world-class expert" sets tone, not facts.** Anthropic's
  guidance says a role focuses behavior and tone ([Anthropic, *Prompting best practices*](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices)). But a study of 162
  personas on 2,410 factual questions found that adding a persona didn't
  improve accuracy ([Zheng et al., 2024, *When "A Helpful Assistant" Is Not Really Helpful*](https://arxiv.org/abs/2311.10054)). A role line can't supply facts the model doesn't
  have; context can. The Lab 02 early-finisher task lets pairs test this.
- **You don't have to write the brief alone.** Ending with *"Ask me up to five
  questions before you answer"* makes the model find the gaps. It's the
  fastest fix for a prompt you're unsure about.

## Key points

1. Brief it like a capable new hire: goal, context, audience, constraints,
   format, example.
2. When output is weak, look for a missing part first. Diagnose before you
   rewrite.
3. Format is the easiest part to add. Be specific about the output you want
   ([Anthropic, *Prompting best practices*](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices)).
4. When in doubt, ask the model to interview you first.

## Materials

- [ ] Slides: hook question, six-part table, live rebuild
- [ ] Lab 02 handout
- [ ] [Reference handout](../../handouts/reference.md), handed out now (it's
      used for the rest of the day)

## Common problems and what to do

| Problem | Response |
| --- | --- |
| Prompts get very long and people worry that's wrong | Long is fine when every line is information. Cut adjectives, not facts |
| "Isn't this just for ChatGPT?" | The brief is built on general principles, not one tool's features. Try it on two tools and compare |
| Pairs rebuild prompt A (the easiest) | Fine, but ask them to try diagnosing C in the debrief |
| Step 5 (own task) runs over into lunch | Stop at 11:50. Participants can finish v1 in the afternoon; Labs 03 and 04 build on it |

## If running behind

1. Do the live rebuild in the teach segment faster, showing only before/after
   (saves ~5 min)
2. Cut Lab 02 step 4 (interview) and demonstrate it in the debrief instead
   (saves 5 min)
3. Don't cut into lunch. Protect the break
