# Module 03 — AI for Everyday Business Tasks

Status: draft
Time: 12:50–14:05 (75 min — lecture 15 / activity 60)
Objective: LO3

## Objective

By the end of this module, participants will be able to **apply** AI to an
analysis, communication, or idea-development task, and **verify** the output
(numbers, facts, tone) before relying on it.

## Why this module is here

The morning taught how AI works and how to brief it. This module applies that
to three broad kinds of business work (our grouping for this course):
**making sense of information, communicating, and developing ideas**. Each has
its own prompt patterns and its own things to watch for. Participants choose the track closest
to their job, so it's relevant to everyone. It's the first block after lunch,
so it's the most hands-on block of the day.

## Outline

| Min | Segment | What happens | Who's talking |
| --- | --- | --- | --- |
| 0–5 | Re-entry | "Name one of the six parts of the brief without looking." Then: "This afternoon it's real work" | Instructor, room |
| 5–15 | Teach | The three kinds of business work, the shared pattern (ground → ask → check), and what to check for each (below) | Instructor |
| 15–65 | Activity | [Lab 03 — Put AI to Work](../../labs/03-put-ai-to-work.md): choose a track | Individually, partner alongside |
| 65–75 | Debrief | One volunteer per track: "What did your check catch?" Land the line: *if it goes out under your name, you checked it* | Participants, then instructor |

### Three kinds of business work

| | Analyze | Communicate | Innovate |
| --- | --- | --- | --- |
| **Typical tasks** | Summarize reports, find trends in data, compare options, pull themes from feedback | Emails, proposals, announcements, replies to customers, rewriting for a different audience | Generate options, anticipate objections, stress-test a plan |
| **Prompt moves** | Ground it in the data → ask for the story → ask for the numbers with working shown | Full brief with audience and tone → have it read as the recipient → adapt for each audience | Vary on named dimensions → simulated customers → pre-mortem |
| **What to watch for** | Arithmetic errors ([Chen, Zaharia & Zou, 2024, *How Is ChatGPT's Behavior Changing over Time?*](https://doi.org/10.1162/99608f92.5317da47)); causes claimed from correlations; confident trends from too little data | Promises you can't keep; invented details ([Kalai et al., 2025, *Why Language Models Hallucinate*](https://arxiv.org/abs/2509.04664)); tone that's off for the relationship | Same idea in twelve costumes; simulated praise mistaken for validation, since assistants tend to agree with users ([Sharma et al., 2024, *Towards Understanding Sycophancy in Language Models*](https://arxiv.org/abs/2310.13548)) |
| **The check** | Recompute key numbers; ask "what can't this data tell me?" | Read every line as the recipient; check each promise against what's true | Verify the claims your decision rests on; take the objections to real people |

**The shared pattern is ground → ask → check.** Give it the material first and
confirm it understood. Ask in small steps, one conversation, so context builds.
Check before anything leaves your hands.

**Why Track A uses sample data:** pasting company data into an unapproved
tool is a documented way workplaces get into trouble. In 2023 Samsung
restricted staff use of generative AI after employees uploaded sensitive code
to ChatGPT ([Bloomberg, 2023, *Samsung Bans Staff's AI Use After Spotting ChatGPT Data Leak*](https://www.bloomberg.com/news/articles/2023-05-02/samsung-bans-chatgpt-and-other-generative-ai-use-by-staff-after-leak)). Practise on safe data. Use real data only in a tool your
organization has approved for it.

## Key points

1. Ground → ask → check works for every kind of business task.
2. AI can make first drafts much faster ([Noy & Zhang, 2023, *Experimental evidence on the productivity effects of generative artificial intelligence*](https://doi.org/10.1126/science.adh2586)). You're accountable for what
   goes out.
3. Numbers: recompute the ones that matter. Words: read them as the recipient.
   Ideas: test them on real people.
4. Know which data you're allowed to put in which tool.

## Materials

- [ ] Slides: re-entry question, three-kinds table
- [ ] Lab 03 handout and [practice data](../../labs/practice-data.md)
- [ ] Fallback for Track C participants without an idea: *a service you wish
      existed in your neighbourhood*

## Common problems and what to do

| Problem | Response |
| --- | --- |
| "Can I use my real data?" | Not today, and only at work if the tool is approved for it. Use the sample data or a made-up version of yours |
| Hits a free-tier message cap mid-chain | New chat, paste the step 1 material, continue. That's why grounding material is worth writing well |
| Track A: "The AI's math was right, so I'll trust it" | Good, this time. The habit is the point: you check because you can't tell in advance when it's wrong |
| Track C: "The customers loved my idea!" | Say it to the whole room, once: the model generates plausible reactions, and assistants tend to agree with users ([Sharma et al., 2024, *Towards Understanding Sycophancy in Language Models*](https://arxiv.org/abs/2310.13548)). What would real customers say? |
| Someone pastes something sensitive | Quietly suggest a general description; repeat the data rule to the room without naming anyone |

## If running behind

1. Skip the re-entry question (saves ~3 min)
2. Cut each track's step 4 (A: check the math becomes a spot-check of one total;
   B: drop the audience adaptation; C: drop the pre-mortem) (saves ~8–10 min)
