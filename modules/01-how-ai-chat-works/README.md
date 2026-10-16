# Module 01 — How AI Chat Actually Works

Status: draft
Time: 9:20–10:20 (60 min — lecture 20 / activity 40)
Objective: LO1

## Objective

By the end of this module, participants will be able to **explain** why an AI
assistant produced a given output, in terms of prediction and context, and
**flag** claims that are likely invented.

## Why this module is here

Most participants have used an AI assistant and been disappointed by generic or
wrong answers. They usually blame the tool or themselves. This module gives
them a working mental model, just enough to predict what will help. Everything
in Module 02 follows from it: if the model only has what's in the context, you
have to put it there.

## Outline

| Min | Segment | What happens | Who's talking |
| --- | --- | --- | --- |
| 0–5 | Hook | Live: ask *"Should a laundromat start a delivery subscription?"* in two tools side by side. Ask the room: "Would you act on either?" | Instructor |
| 5–20 | Teach | Three ideas, one slide each (below) | Instructor |
| 20–50 | Activity | [Lab 01 — Same Question, Different Answers](../../labs/01-same-question-different-answers.md) | Pairs |
| 50–60 | Debrief | Two pairs share their column sort from step 4; room finishes "The answers changed because…"; bridge to Module 02 | Pairs, then instructor |

### The three ideas

1. **Prediction, not lookup.** The model writes the most plausible
   continuation of your text, given everything it learned in training. It isn't
   retrieving a stored answer, so the same question can produce different
   answers, and plausible isn't the same as true.
2. **Context is its working memory.** The model knows only what was in its
   training and what's in *this* conversation. It doesn't know your business,
   your customers, or your constraints unless you say so. A generic question
   gets a generic answer because generic is the most plausible answer to a
   generic question.
3. **Confident wrongness.** When it doesn't know, it often produces something
   that *looks* like knowledge: a precise figure, a named source, a competitor.
   Tone tells you nothing about accuracy. Numbers, names, quotes, and recent
   events are the highest-risk claims. Some tools search the web, which helps,
   but only if the sources are about *your* question.

## Key points

1. The model predicts plausible text. Plausible ≠ true.
2. It only knows what you tell it about your situation. Context is the biggest
   lever you have.
3. Precise-sounding numbers and names are the claims most worth checking.
4. Different answers to the same prompt are normal, not a malfunction.

## Materials

- [ ] Slides: hook prompt + three ideas
- [ ] Two AI tools logged in on the instructor machine for the hook
- [ ] Lab handout + [practice case](../../labs/practice-case.md), printed or
      linked

## Common problems and what to do

| Problem | Response |
| --- | --- |
| "So it's just autocomplete?" | "Yes, an extremely capable one. That's why what you give it matters so much" |
| Technical tangents (training, parameters, how it "thinks") | Park it: "Great question for the break." Out of scope; keep to what changes how you prompt |
| A tool refuses or hedges heavily in step 4 | Good. Have that pair compare with a neighbour whose tool didn't |
| Someone's tool searches the web and gives real-looking citations | Ask: "Is that source about Dana's city? The case doesn't name one." |

## If running behind

1. Debrief with one pair instead of two (saves ~4 min)
2. Skip Lab 01 step 2 (regenerate) and mention it verbally (saves 5 min)
