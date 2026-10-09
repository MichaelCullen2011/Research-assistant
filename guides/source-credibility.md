# Source credibility

Tag every source in `sources.md` with one tier. The tier decides what the
source is allowed to support.

| Tier | Examples | Can support |
|---|---|---|
| **T1: Authoritative** | Peer-reviewed journals, conference proceedings (e.g. NeurIPS, PRX, Nature), regulators (FCA, PRA, EBA, ECB, BIS), government publications (gov.uk, MoD, DSIT, NCSC, EU Commission), official statistics, standards bodies (NIST, ETSI, ISO) | Facts, figures, findings, policy positions |
| **T2: Reputable secondary** | Established press (FT, Reuters, Bloomberg, The Economist, BBC), specialist trade press with editorial standards (e.g. The Quantum Insider, Janes, Finextra, The Banker), analyst firms (Gartner, Forrester, McKinsey, BCG), arXiv preprints from established groups, think tanks (RUSI, Chatham House) | Facts and context; analyst forecasts as *forecasts* |
| **T3: Interested party** | Company press releases, vendor white papers, vendor case studies, investor decks, company blogs | That an announcement, partnership, product or contract **was made**. Performance or impact claims only as "X claims…" |
| **T4: Leads only** | Personal blogs, Medium, LinkedIn posts, forums, Reddit, AI-generated summaries, Wikipedia | Nothing on its own. Follow the lead to a T1–T3 source and cite that instead |

## Rules

- **Corroboration**: a key finding (one that reaches the brief) needs either
  one T1 source or two independent T2/T3 sources. Otherwise mark it
  `confidence: low`.
- **Independence**: a news article that just restates a press release is not
  independent. Cite the press release (T3) and note the coverage.
- **Preprints**: arXiv papers are T2. Note "not peer reviewed" when a finding
  relies on one.
- **Vendor hype**: watch for "quantum advantage", "first", "breakthrough",
  "up to N× faster". Record the claim, the comparison baseline (if any), and
  whether anyone independent has verified it.
- **Dates**: always record the publication date. For fast-moving topics,
  note when newer information may exist.
- **Paywalls**: if you can only see an abstract or snippet, record
  `access: abstract-only` and cite only what you actually saw.
- **User-provided sources** (in `inbox/`): tier them like any other source.
  Internal or confidential documents get `tier: internal`.
