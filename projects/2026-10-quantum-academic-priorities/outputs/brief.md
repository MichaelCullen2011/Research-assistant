# Quantum academic scan: findings worth carrying forward

*12 October 2026. Scope: 1 January 2016–12 October 2026. Twenty-four full-paper reviews; 26 opened sources, including two correction/challenge records, plus a separate internal audit. Eleven studies received an independent Astra challenge pass. [S01] [Selection record](../search-log.md).*

## Assessment

The strongest application-facing evidence is for optical timing, motion compensation and controlled gravity-anomaly sensing. Magnetic and gravity navigation preprints add useful field results, but their best figures depend on aiding mode and metric definition. [S10][S11][S12][S30][S13][S14]

Emerging phenomena also produce real metrological gains. Their measurement tasks, loss budgets and interrogation times constrain the application story. Quantum-inspired optimisation has useful results on particular workloads; no reviewed paper establishes a generally superior solver. [S70][S71][S72][S51][S52][S53][S54][S55]

*Assessment:* confidence is medium in the synthesis, high in the explicitly scoped journal timing and known-target demonstrations, and lower in operational superiority. Some published studies were reviewed through preprint manuscripts; those detailed claims retain a version caveat and T2 access tier.

## Key findings

1. **Timing deserves the strongest position.** Roslund's shipboard clock pair shows strong stability; individual long-time holdover is inferred under assumptions. Hilton's ensemble supplies useful restart and installation detail, including one deployed system's 310 kg and 1,300 W support burden. [S10 Fig.3; Methods][S11 Fig.3; Methods ORAFS]

2. **Navigation results need the aiding mode attached.** In the magnetic-navigation preprint, the 22 m best endpoint and 46-fold improvement use 3D-velocity aiding. The onboard scalar-airspeed example ends at 515 m over 365 km. Those are different tests. [S13 Table1]

3. **The newest gravity-navigation result survives a narrower reading.** The August 2026 preprint reports an endpoint reduction from about 26 km to 4.1 km over 83 km. Its DRMS and one-mile-bound wording is internally inconsistent. Keep the error reduction; withhold the disputed accuracy characterisation. [S14 Fig.2; Results; Discussion]

4. **Detection proof is stronger than claims of general operational superiority.** Stray detects a known tunnel with a quantum gradiometer; survey repeatability remains similar to commercial gravimeters. Assouly's microwave experiment reports a modest quantum advantage in a cold, known-target setup. Neither establishes an unrestricted search capability. [S30 pp.591–593][S31 pp.1–5]

5. **Quantum-inspired methods need native classical competitors.** Transport-robot scheduling favours native Gurobi on smaller instances and a hybrid Digital Annealer on the largest group. The 2026 industrial study's “end-to-end” timing excludes APIs and queues, and its large references are best-found schedules, not certified optima. [S52 §§4.1–4.2][S55 §§V-A,V-C,VII-E]

6. **Emerging gains must stay with the demonstrated task.** Distributed photonic sensing beats its shot-noise limit at 240 m, but the 10 km random-phase test does not. Earth-field spin locking is a numerical proposal. The 2026 cavity device produces electrical output under continuous illumination; delayed discharge and round-trip storage efficiency are not established by those measurements. [S70 p.5][S73 Discussion][S75 Fig.4; Methods]

## Priority view

| Priority | Carry forward | Next evidence to demand |
|---|---|---|
| Navigation and timing | Clock stability, motion compensation, qualified map-aiding results [S10][S11][S12][S13][S14][S15] | Independent-reference holdover; matched aiding; route-wide errors |
| Detection and awareness | Known-target gravity result; atomic receiver mechanisms [S30][S32][S34] | Blind targets, false alarms, active classical receiver comparison |
| Quantum-inspired | Workload-specific solver and formulation results [S51][S52][S53][S54][S55] | Equal-quality native benchmarks with complete workflow timing |
| Emerging phenomena | Loss-aware sensing, interferometer gain, cavity electrical output [S70][S71][S72][S73][S74][S75] | Full resource accounting, longer interrogation, net energy and cycling |

*Table: selection priorities are analyst judgement based on the cited studies; they are not deployment certifications.*

## Implications

*Analysis, based on F001–F024, F025–F054, F055–F073 and F074–F103.* Build the whitepaper around measured mechanisms and the conditions under which they work. Use the disputed metrics as examples of how to assess evidence. Treat claimed application advantage as a separate test from scientific novelty.

## Caveats and reading

*Analysis:* two printed equations in the antenna/Rydberg comparison fail internal algebraic checks; their effect on its numerical curves remains unresolved. Its useful lesson about including active classical receivers survives provisionally. [S33 Eqs.7,9–10; Fig.3]

The scan does not adjudicate the Greve critique, reproduce experiments or execute paper code. [S01][S76] Older 2016–2020 leads were screened; the deep selection concentrates on newer studies. [S01] Start with the [report](report.md), then use the [paper reviews](paper-reviews.md) for methods, limitations and original links.

## Sources


| ID | Source | Date | Evidence access |
|---|---|---|---|
| S01 | [Search, selection and review audit record](../search-log.md) | 2026-10-12 | internal |
| S10 | [Optical clocks at sea](https://www.nature.com/articles/s41586-024-07225-2) | 2024-04-24 | T1 |
| S11 | [Demonstration of a mobile optical clock ensemble at sea](https://www.nature.com/articles/s41467-025-61140-2) | 2025-07-02 | T1 |
| S12 | [Atom interferometry at arbitrary orientations and rotation rates](https://www.nature.com/articles/s41467-024-50804-0) | 2024-07-30 | T1 |
| S13 | [Quantum-assured magnetic navigation achieves positioning accuracy better than a strategic-grade INS in airborne and ground-based field trials](https://arxiv.org/html/2504.08167v1) | 2025-04-10 | T2 |
| S14 | [GNSS-free quantum gravity-aided navigation and fine-scale marine surveying with a strapdown quantum gravimeter](https://arxiv.org/html/2608.25563v1) | 2026-08-26 | T2 |
| S15 | [Integration of a high-fidelity model of quantum sensors with a map-matching filter for quantum-enhanced navigation](https://arxiv.org/html/2504.11119v2) | 2025-08-06 | T2 |
| S30 | [Quantum sensing for gravity cartography](https://www.nature.com/articles/s41586-021-04315-3) | 2022-02-23 | T1 (peer-reviewed study; version examined specified) |
| S31 | [Quantum advantage in microwave quantum radar](https://arxiv.org/abs/2211.05684) | 2023-06-29 | T2 |
| S32 | [Waveguide-coupled Rydberg spectrum analyzer from 0 to 20 GHz](https://arxiv.org/abs/2009.14383) | 2021-01-27 | T2 |
| S33 | [Performance of antenna-based and Rydberg quantum RF sensors in the electrically small regime](https://inspirehep.net/files/ac16594fd5658d98b52993e9f1437037) | 2024-09-30 | T1 (peer-reviewed study; version examined specified) |
| S34 | [Electrometry of extremely-low frequencies from kHz to sub-Hz with a Rydberg-atom sensor](https://link.springer.com/article/10.1140/epjqt/s40507-026-00550-7) | 2026-08-05 | T1 (peer-reviewed study; version examined specified) |
| S51 | [Benchmark of quantum-inspired heuristic solvers for quadratic unconstrained binary optimization](https://www.nature.com/articles/s41598-022-06070-5) | 2022-02-09 | T1 |
| S52 | [An Optimization Case Study for solving a Transport Robot Scheduling Problem on Quantum-Hybrid and Quantum-Inspired Hardware](https://arxiv.org/abs/2309.09736) | 2023-10-31 | T2 |
| S53 | [Toward quantum scaling advantage in approximate optimization](https://arxiv.org/abs/2505.22514) | 2026-07-08 | T2 |
| S54 | [Limitations of tensor-network approaches for optimization and sampling: A comparison to quantum and classical Ising machines](https://arxiv.org/abs/2411.16431) | 2025-05-19 | T2 |
| S55 | [A Reality Check on Quantum Optimisation: Evidence from an Industrial Case Study](https://arxiv.org/abs/2607.13325) | 2026-07-14 | T2 |
| S70 | [Field Demonstration of Distributed Quantum Sensing without Post-Selection](https://journals.aps.org/prx/pdf/10.1103/PhysRevX.11.031009) | 2021-07-14 | T1 |
| S71 | [Distributed quantum sensing with mode-entangled spin-squeezed atomic states](https://arxiv.org/html/2205.06382) | 2022-11-23 | T2 |
| S72 | [Entanglement-enhanced matter-wave interferometry in a high-finesse cavity](https://www.nature.com/articles/s41586-022-05197-9) | 2022-10-19 | T1 |
| S73 | [Quantum locking of intrinsic spin squeezed state in Earth-field-range magnetometry](https://www.nature.com/articles/s41534-025-00971-9) | 2025-03-03 | T1 |
| S74 | [Superabsorption in an organic microcavity: Toward a quantum battery](https://arxiv.org/pdf/2012.06026) | 2022-01-14 | T2 |
| S75 | [Superextensive electrical power from a quantum battery](https://www.nature.com/articles/s41377-026-02240-6) | 2026-03-13 | T1 |
| S76 | [Matters Arising: Entanglement-enhanced matter-wave interferometry in a high-finesse cavity](https://arxiv.org/abs/2301.04396v2) | 2023-05-03 | T2 |
