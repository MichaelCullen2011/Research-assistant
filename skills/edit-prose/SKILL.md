---
name: edit-prose
description: Edit a draft so it reads as human analyst writing rather than agent prose. Reorders sections by dependency, tightens paragraphs, and rewrites every tell listed in guides/prose-style.md. Use on every brief and report before verify, or on any text the user asks to make sound less AI-written.
---

# Edit prose

Read `guides/prose-style.md` first. Edit the draft in place.

## 1. Structure
List the sections and the main point of each. Check that every section only
relies on concepts introduced earlier (or that the reader brings with them).
Reorder sections, or add a one-line definition, until that holds.

## 2. Paragraphs
For each section in turn:
- Put the claim in the first sentence.
- Apply the cut test to every paragraph: *if I cut this, what breaks?* Remove
  any paragraph where nothing breaks.
- Tighten to the paragraph length in the guide.
- Convert between prose, list and table where the shape of the content calls
  for it.

## 3. Tells pass
Go through the draft line by line against the *Tells* list. Rewrite each hit
into the targets. Then scan for em-dashes and rewrite every sentence that has
one.

## 4. Read-aloud check
Read the bottom line and the first paragraph of each section as if to the
reader named in `brief.md`. Rewrite any sentence you would not say to them
across a table.

## Guardrails
- Keep every citation, figure, date and quote exactly as they were. Editing
  changes wording, never evidence.
- Keep confidence wording aligned with `findings.md`.

Done when the tells pass finds nothing, no em-dashes remain, and every
citation is still present and unchanged.
