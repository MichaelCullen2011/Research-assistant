---
name: capture-findings
description: Turn logged sources into atomic, cited findings grouped by sub-question, each with a confidence rating, plus contradictions, gaps and clearly labelled analysis. Use after sources are gathered and before writing any output.
---

# Capture findings

Input: `brief.md` and `sources.md`. Output: `findings.md`.

## 1. Write atomic findings
Under each sub-question heading, add rows to the findings table:
- **One claim per row.** It must be specific and checkable: who, what, when,
  how much.
  - Good: "Dstl awarded £X to Y for quantum navigation trials in March 2025."
  - Bad: "Defence is investing heavily in quantum."
- **Cite with locators**: `[S03 p.12]`, `[S07 §4.2]`. Use only information
  recorded in `sources.md`. If you need more detail, go back to the source
  and update its notes first.
- **Word claims to match their tier.** If the only source is T3, write
  "Company X **announced** / **claims** …".
- **Rate confidence** using the definitions in the template.
- **Notes**: preprint, vendor-only, figures differ between sources, or stale.

## 2. Record contradictions & gaps
- Where sources disagree, list both, say which you weight more, and why.
- List sub-questions that are only partly answered. If a gap matters, go back
  to `gather-sources` before continuing.

## 3. Write analysis, kept separate
In the *Analysis* section, write patterns, implications and "so what" for
the brief's stated purpose. Every point references the finding IDs it builds
on. This is the only place for unsourced reasoning, and it must be clearly
labelled as the agent's interpretation.

## 4. Self-check before moving on
- Does every sub-question have findings, or a stated gap?
- Is there no finding without a source ID?
- Is every confidence rating consistent with the tier rules?

## 5. Hand off
Set `status: writing` and go to `skills/write-brief/SKILL.md`.
