---
name: gather-sources
description: Find, assess and log credible sources for a research project. Starts from user-provided material, searches from several perspectives using the playbook for the research type, tiers each source for credibility, and records it in sources.md. Use after the brief is written, or whenever findings reveal gaps.
---

# Gather sources

Read first: the project's `brief.md`, `guides/source-credibility.md`, and the
matching section of `guides/research-playbooks.md`.

## 1. Seed from what the user gave you
Log every file in `inbox/` and every link under *Starting sources* first.
Follow their references to find further sources.

## 2. Plan searches
For each sub-question, take the playbook angles and write 2–4 queries. Cover
several perspectives (buyer, vendor, regulator, academic, sceptic). Put
UK/EU-specific queries first unless the brief sets a different region. Apply
the brief's time window if it has one.

## 3. Search, open, assess
For each promising result:
1. **Open it.** Never log a source from a search snippet alone. If only an
   abstract or snippet is visible, log `access: abstract-only` and use no more
   than that.
2. **Assign a tier** (T1–T4). T4 sources are leads only: follow them to a
   better source and do not log the T4 itself unless nothing better exists.
3. **Check the date** against the time window.
4. **Check independence**: is this just a restated press release? If so,
   find and log the original.

## 4. Log it
Add a row to the index and a source-notes entry in `sources.md` using the
template format. Assign the next ID (S01, S02, …). Record:
- the key points, each with a locator (page, section or paragraph)
- **verbatim** quotes for anything likely to be cited directly
- caveats (vendor interest, preprint, small sample, age)

Capture enough detail at this stage that later steps never need to guess
what a source said.

## 5. Know when to stop
Stop gathering when **either**:
- every sub-question has at least one T1/T2 source, or a note explaining why
  none exists, **and** new results mostly repeat what you already have; **or**
- the user's effort limit is reached (if they set one).

Typical scale: 8–15 sources for a brief, 15–40 for a deep-dive report.

## 6. Hand off
Set `status: synthesising` and go to `skills/capture-findings/SKILL.md`.
Come back here whenever findings show a gap.
