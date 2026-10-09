# AGENTS.md

This repo is a lightweight research assistant. It runs discrete research tasks
(market/news scans, industry context, technical literature) and records the
sources, findings and outputs of each one in plain markdown.

## Rules that always apply

1. **One folder per task**: `projects/YYYY-MM-<slug>/`. Never mix tasks.
2. **No claim without a source.** Every factual statement in findings and
   outputs cites a logged source ID, e.g. `[S03]` or `[S03 p.12]`. If you cannot
   source it, mark it `[unsupported]` or leave it out.
3. **Never invent sources, quotes, figures or URLs.** Only log sources you
   have actually opened. Quotes must be verbatim.
4. **Credibility matters.** Tag every source with a tier from
   `guides/source-credibility.md`. Vendor press releases prove that something
   was *announced*, not that it *works*.
5. **Region**: prefer UK / European sources and context first, then global,
   unless the brief says otherwise.
6. **Recency**: there is no default window. Use the one set in the brief. If
   the brief sets none, record each source's date and flag anything stale.
7. **Separate fact from interpretation.** Label your own analysis as
   *Analysis* or *Implication*.

## Workflow

Run the skills in order. Each one is a self-contained instruction file:

| Step | Skill | Output |
|---|---|---|
| 1 | `skills/start-research/SKILL.md` | `brief.md` (autonomous or guided mode) |
| 2 | `skills/gather-sources/SKILL.md` | entries in `sources.md` |
| 3 | `skills/capture-findings/SKILL.md` | `findings.md` |
| 4 | `skills/write-brief/SKILL.md` | `outputs/brief.md` |
| 5 | `skills/write-report/SKILL.md` | `outputs/report.md` (only when asked or warranted) |
| 6 | `skills/verify/SKILL.md` | verification log at the end of `findings.md` |

Steps 2 and 3 can loop. Go back to gathering whenever the findings show gaps.

## Reference

- `guides/source-credibility.md`: credibility tiers and how to treat each
- `guides/research-playbooks.md`: search approach per research type
- `guides/visuals.md`: when to use a table, Mermaid diagram or richer graphic
- `templates/`: copy into each new project; do not edit in place

## Finishing a task

A task is done when `verify` passes. Then give the user a 3–5 line summary:
what was answered, confidence level, number of sources, and the main open
questions.
