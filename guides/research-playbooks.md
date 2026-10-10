# Research playbooks

Choose the playbook that matches the brief's `type`. A task can combine types.
Each playbook lists the angles to cover. Write 2–4 search queries per angle.

---

## A. Market & news scan

*e.g. quantum technology in defence and the public sector*

**Goal:** who is doing what, with whom, how much money is involved, and how fast it is moving.

Angles:
1. **Government programmes & policy**: national strategies, funding calls, procurement frameworks (e.g. UK National Quantum Strategy, NQCC, DSIT, MoD/Dstl, NATO DIANA, EU Quantum Flagship, EDF).
2. **Contracts & awards**: named contracts, values, durations, buyers.
3. **Vendor announcements**: partnerships, product launches, funding rounds (all T3, so corroborate where possible).
4. **Adoption & use cases**: what is actually deployed or trialled versus only proposed.
5. **Independent commentary**: think tanks, analysts, specialist press.
6. **Risks & barriers**: export controls, security clearance, talent, maturity.

Useful outputs: a timeline of events, a table of players × activity × date ×
source, a maturity view (research → pilot → deployed).

---

## B. Industry & domain context

*e.g. banking processes, technology and architecture practices for core
banking modernisation*

**Goal:** understand how the domain works today, what good practice looks
like, and what is changing, deeply enough to advise.

Angles:
1. **Domain fundamentals**: core processes, capabilities and terminology (e.g. BIAN service landscape, ledgers, payments, product engines).
2. **Reference architectures & patterns**: e.g. hollow-the-core, progressive modernisation, strangler fig, event-driven, cloud-native cores, coexistence.
3. **Regulatory constraints**: e.g. PRA/FCA operational resilience, outsourcing and third-party risk, DORA, cloud guidance.
4. **Market landscape**: core platform vendors and their architecture positioning (T3, so stick to facts).
5. **Case studies**: named bank migrations, their outcomes and lessons (favour independent reporting over vendor case studies).
6. **Failure modes & lessons**: well-known incidents and post-mortems.

Useful outputs: a capability or architecture diagram, an options comparison
matrix, a decision-factors table, a glossary.

---

## C. Technical & literature scan

*e.g. quantum-inspired algorithms and tensor network techniques*

**Goal:** what the techniques are, where the field stands, which results are
established and which are hype, and who is commercialising them.

Angles:
1. **Foundations**: survey or review papers that define the techniques (find 1–3 good surveys first).
2. **Recent advances**: papers from the brief's time window (arXiv, journals, major conferences). Record the method, the result, and the benchmark or baseline.
3. **Applications**: finance, optimisation, ML, simulation, defence.
4. **Commercial activity**: companies, products and partnerships (T3). Compare their claims against the literature.
5. **Critiques & limits**: dequantisation results, classical baselines that match "quantum" claims, scaling limits.
6. **Key groups & people**: who publishes the most-cited work.

Useful outputs: a technique taxonomy diagram, a paper table (title, year,
venue, contribution, evidence strength), and a claims-versus-evidence table for
vendors.

---

## Search tactics (all types)

- Start from any sources in `inbox/` and follow their references.
- Search from several perspectives: buyer, vendor, regulator, academic,
  sceptic. This brings up material that a single-angle search misses.
- For UK/EU focus, add region terms and check gov.uk, europa.eu, and UK/EU
  trade press before global sources.
- Use `site:` filters for authoritative domains, e.g. `site:gov.uk`,
  `site:arxiv.org`, `site:bankofengland.co.uk`.
- Stop gathering when new sources mostly repeat what you already have
  (saturation), or when every angle in the brief has at least one T1/T2
  source.
