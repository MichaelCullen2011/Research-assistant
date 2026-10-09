# Research-assistent

A lightweight, agent-agnostic research assistant: plain-markdown skills and
guidance that any coding or chat agent can follow to run discrete research
tasks and record **sources, findings and insights** in a consistent, citable
structure.

There are no servers, databases or dependencies. Point your agent at
`AGENTS.md` and ask it to research something.

## How to use

Start a session in this repo and ask, for example:

> Research recent UK and European defence and public-sector activity in quantum
> technology (contracts, programmes, vendor announcements). Brief plus a
> timeline.

> I'm not sure of the direction yet. Set up some questions first: I want to
> understand core banking modernisation architecture patterns for an advisory
> engagement.

The agent will:
1. **Scope**: create `projects/YYYY-MM-<slug>/` and write `brief.md`. It runs
   autonomously if your request is clear, or asks scoping questions first if
   you say you're unsure.
2. **Gather**: find credible sources, starting from anything you drop in
   `inbox/`, and tier each one for credibility.
3. **Capture**: write atomic, cited findings with confidence ratings.
4. **Write**: produce a short brief, plus a deep-dive report if requested,
   with tables and diagrams where they help.
5. **Verify**: check that every claim is traceable to a logged source before
   handing over.

## Layout

```
AGENTS.md          Root guidance for any agent (CLAUDE.md imports it)
skills/            One SKILL.md per workflow step
  start-research/  gather-sources/  capture-findings/
  write-brief/     write-report/    verify/
guides/
  source-credibility.md   T1–T4 tiers and how each can be used
  research-playbooks.md   Market/news · industry context · technical literature
  visuals.md              Tables, Mermaid diagrams, richer figures
templates/         Copied into each new project
projects/          One folder per research task
```

## Principles

- **Every claim is cited** to a logged source ID with a locator. Nothing is
  invented.
- **Credibility tiers**: vendor press releases support "announced", not
  "works".
- **UK / Europe first** by default. Time windows are set per project.
- **Fact and analysis are kept separate.**

## Agent compatibility

Skills use the common `SKILL.md` format with a `name`/`description` header.
`.claude/skills` is a symlink to `skills/`, so Claude Code picks them up
natively. Other agents read `AGENTS.md`, which links to each skill.
