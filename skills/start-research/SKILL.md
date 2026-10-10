---
name: start-research
description: Start a new research task. Creates the project folder from templates and writes the research brief, running autonomously when the request is clear or asking scoping questions first (guided mode) when the user is unsure of direction. Use at the start of any new research request.
---

# Start research

## 1. Create the project folder

```
projects/YYYY-MM-<slug>/
  brief.md      ← templates/brief.md
  sources.md    ← templates/sources.md
  findings.md   ← templates/findings.md
  inbox/        ← user-provided files (create even if empty; add .gitkeep)
  outputs/
```

Use a short kebab-case slug, e.g. `2026-10-quantum-defence-public-sector`.
If a matching project already exists, continue that one instead of creating a
duplicate.

## 2. Choose the mode

- **Autonomous**: use this when the request states the topic, purpose, and
  roughly what output is wanted. Fill in the brief, record any gaps under
  *Assumptions*, and carry straight on to `gather-sources`. Do not stop to ask.
- **Guided**: use this when the user says they are unsure, asks to "set
  questions up front", or the request is too vague to choose sub-questions.
  Ask **3–6 questions in one message**, then wait. Good questions:
  1. What decision or conversation will this research feed into?
  2. Who is the audience, and how much do they already know?
  3. Which sub-topics matter most, and which should be excluded?
  4. What time window and regions matter?
  5. Brief only, or brief plus a deep-dive report? Any visuals you want?
  6. Any sources, organisations or people to start from or to avoid?

  Record the questions and answers in the *Guided-mode Q&A* table, then
  continue autonomously.

## 3. Write the brief

Fill in every section of `brief.md`:
- Turn the request into **one main question and 2–6 sub-questions**. The
  sub-questions become the structure of `findings.md`.
- Set `type` using `guides/research-playbooks.md` (market-news,
  industry-context, technical-literature, or a combination).
- Region defaults to UK / Europe first. Leave the time window as "none set"
  unless the user or the topic implies one.
- The deliverable defaults to the brief only. Tick the report when the user
  asks for a deep dive or says the topic needs one.
- List any files or links the user provided under *Starting sources*, and
  copy the files into `inbox/`.

## 4. Hand off

Set `status: gathering` and go to `skills/gather-sources/SKILL.md`.
