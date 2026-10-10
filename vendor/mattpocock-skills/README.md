# Matt Pocock's writing skills (vendored)

Unmodified copies of the writing-related skills from
[mattpocock/skills](https://github.com/mattpocock/skills), MIT licensed (see
`LICENSE`). They are kept here as reference. This repo's own prose rules live
in `guides/prose-style.md`, which adapts the principles below for research
outputs.

| Skill | Upstream path | What it is |
|---|---|---|
| `writing-for-agents` | `skills/productivity/writing-for-agents/` | How to write documents an agent reads (skills, AGENTS.md). Use when editing this repo's skills. |
| `writing-fragments` | `skills/in-progress/writing-fragments/` | Interactive: interviews you for raw fragments of writing. Beta upstream. |
| `writing-shape` | `skills/in-progress/writing-shape/` | Interactive: shapes raw material into an article, block by block, arguing over format choices. Beta upstream. |
| `writing-beats` | `skills/in-progress/writing-beats/` | Interactive: builds an article as a sequence of beats, grounding each concept before it is used. Beta upstream. |
| `edit-article` | `skills/personal/edit-article/` (deleted upstream) | Restructure sections in dependency order, tighten paragraphs to 240 characters at most. Recovered from the parent of commit `c66bdee`. |

Snapshot taken from upstream commit `49dd158` (2026-10-09).

## When to use them here

- The research skills run autonomously and follow `guides/prose-style.md`.
  You do not need these to produce a brief or report.
- Use `writing-shape` or `writing-beats` when you want to hand-craft a
  piece (an article, a client narrative) from a project's `findings.md`, with
  you choosing each step. Pass `findings.md` as the raw-material pile.
- Use `writing-for-agents` when changing anything in `skills/`, `guides/` or
  `AGENTS.md`.

The interactive skills carry `disable-model-invocation: true`: they run only
when you ask for them by name.
