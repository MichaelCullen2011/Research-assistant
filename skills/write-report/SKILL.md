---
name: write-report
description: Write a deep-dive synthesis report organised by theme, with inline citations, comparison tables and diagrams, an evidence-quality section and clearly labelled analysis. Use when the user asks for a deep dive or the brief ticks the report deliverable.
---

# Write report

Input: `brief.md`, `findings.md`, `sources.md`, `outputs/brief.md`.
Output: `outputs/report.md` built from `templates/output-report.md`.

## Structure
1. **Executive summary**: it must stand on its own. It can expand the brief's
   bottom line, but must not contradict it.
2. **Organise by theme, not by source.** Usually each sub-question or playbook
   angle becomes a section. Each section brings several sources together into
   a narrative: what is established, what is contested, and what is new.
3. **Visuals**: aim for 2–5 across the report, chosen with
   `guides/visuals.md`. Good defaults by type:
   - market-news: timeline plus a players-and-activity table
   - industry-context: architecture or capability diagram plus an options
     matrix
   - technical-literature: technique taxonomy plus a paper table plus a
     claims-versus-evidence table
4. **Analysis & implications**: labelled interpretation, tied to finding IDs
   and to the reader's purpose.
5. **Evidence quality & gaps**: be honest about where evidence is thin,
   vendor-only or preprint-only, and what would change the conclusions.

## Rules
- Cite inline with locators, e.g. `[S05 p.7]`. Every paragraph that states a
  fact has at least one citation.
- Add new claims only by first adding them to `findings.md`.
- Explain jargon the first time it appears. Add a glossary if there are more
  than about 5 terms.
- Length follows the topic. Typically 1,500–4,000 words, and readable section
  by section.
- Write in UK English, in plain and direct language.

## Hand off
Go to `skills/verify/SKILL.md`.
