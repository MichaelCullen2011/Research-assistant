# Critical academic scan of quantum priorities

*12 October 2026. Navigation and timing; detection and situational awareness; quantum-inspired optimisation; emerging phenomena.*

## Executive assessment

The most useful papers connect a measured mechanism to a constrained application test. Shipboard optical-clock experiments, atomic motion compensation and outdoor gravity sensing provide that connection. Recent magnetic and gravity navigation preprints extend the field evidence, but their headline accuracy needs aiding, initialization and metric qualifications. [S10][S11][S12][S30][S13][S14]

Quantum-inspired optimisation is best understood as a choice among classical solver architectures. The reviewed papers show problem-dependent winners and sensitivity to formulation, comparison budget and runtime accounting. They do not establish a broadly dominant quantum-inspired approach. [S50][S51][S52][S53][S54][S55]

Entanglement and collective effects support useful emerging results. Photonic and atomic network metrology, a complete matter-wave interferometer and a cavity device with electrical extraction each advance their defined task. The proposed Earth-field magnetometer remains numerical, while practical energy storage is not demonstrated by steady-illumination electrical output. [S70][S71][S72][S73][S74][S75]

*Analysis:* scientific value and operational readiness need separate verdicts. A reporting error can invalidate a headline metric while leaving an experimental improvement intact. An idealised or short-duration result can be useful enabling science without supporting the attached mission claim. (F001–F103)

## Scope and review method

The inclusive window was 1 January 2016–12 October 2026, with emphasis on newer work. Searches recorded 96 screening records in 82 candidate identity groups after title, DOI and arXiv de-duplication. Twenty-four core papers received full-text review; two additional opened sources concern an interferometry critique and publisher correction. Counts and access decisions are in the [selection record](../search-log.md). [S01]

Luna supplied bounded discovery leads. Sol selected and extracted full papers across the four strands, including negative results and strong-comparator studies. Astra independently challenged six sensing and five optimisation/emerging studies without the first reviewers' verdicts. Its second batch saved five complete records before a usage-limit interruption; the orchestrator checked those records against original evidence. [S01]

Review considered the claim, estimator, controls, baseline, uncertainty, resource accounting, scaling, reproducibility and application boundary. Criticism was classified as a result/reporting flaw, scope restriction, missing evidence or unsupported concern. An absent dataset or replication was recorded as a search/access gap, not proof that the result is false. [S01]

This is a targeted critical scan. Article-level citation searches were bounded; no exhaustive database harvesting or experimental replication was performed. Deep reviews concentrate on 2021–2026 journal publications and preprints back to 2020; earlier 2016–2020 candidates remain visible in the screen, including an August 2016 lead whose attempted publisher page could not be opened. [S01]

Some journal studies were accessible in preprint manuscripts. The exact version is logged, and detailed claims from unmatched manuscripts retain T2 access status even when publication metadata is verified. Source tier, scientific plausibility and mission readiness are different assessments. [S01]

## 1. Navigation and timing

### Optical clocks: useful engineering with an explicit measurement boundary

Roslund's *Optical clocks at sea* reports a compact iodine-clock package and strong shipboard pairwise stability. The PICKLES–EPIC pair reaches 8×10^-15 instability at 100,000 s, expressed by the paper as roughly 400 ps equivalent daily holdover without drift correction. Long-time individual estimates assume equal contributions, and no independent high-performance reference was present at sea. [S10 Fig.3; Main; Methods]

Hilton's *Mobile optical clock ensemble at sea* adds practical recovery and installation evidence. Short-time performance resembles shore measurements, but stability degrades at longer times; after a power interruption some clocks recover automatically while ORAFS needs personnel. ORAFS's deployed ancillary installation totals 310 kg and 1,300 W. [S11 Figs.3,5–6; Methods ORAFS]

Both clock studies used the RIMPAC 2022 exercise. They provide different clock architectures under that campaign, rather than two independent environmental replications. [S10 RIMPAC test setup][S11 RIMPAC2022 paragraph]

*Analysis:* these are strong timing prototypes. A resilient-timing claim should specify raw versus corrected holdover, restart continuity, complete installation burden and an environmentally independent reference. The papers do not demonstrate a navigation fix or a distributed timing service. (F001–F008)

### Motion compensation: an enabling result, with classical sensors retained

The arbitrary-orientation atom-interferometry study restores atomic fringes under substantial tilt and rotation using a classical accelerometer, gyroscopes and controlled mirror motion. It reports 24 micro-g per-shot inferred sensitivity at 20 ms interrogation, with rotation up to 14 degrees/s. Reconstruction uses a fitted correction and an assumed accelerometer response/delay. [S12 Fig.3; Methods]

The high-fidelity navigation simulation makes the engineering limitation explicit. Some Sea State 2 cases fail to produce stable useful aiding; successful high-dynamic flight cases assume 100-fold reduced roll and pitch. The model also supplies transfer alignment and initial errors. [S15 §IV; Figs.7–8]

*Analysis:* the measured motion-compensation advance deserves attention, while the simulation identifies a requirement that is not yet delivered by that simulation. Neither paper establishes a complete autonomous inertial navigator. (F009–F012, F021–F024)

### Magnetic navigation: promising combined-system results

The Q-CTRL magnetic preprint must be read by configuration. Its 22 m endpoint uses onboard sensing and 3D-velocity aiding; the 46-fold endpoint improvement uses an outboard sensor and 3D velocity. The onboard scalar-airspeed case ends at 515 m over 365 km, while another higher-altitude onboard case ends at 2 km over 300 km. [S13 Table1]

The public manuscript does not sufficiently specify best-case 3D-velocity provenance to assign the strongest numbers to complete GNSS denial. Its comparator is an INS, with no same-input conventional scalar-magnetometer/map-matching ablation. The hardware and algorithms are proprietary. [S13 Fig.1 caption; System architecture; Table1; Discussion]

*Analysis:* system-level improvement survives. Quantum-specific causal advantage, unrestricted cold-start localization and general flight accuracy remain unestablished. Compare sensor choices using the same maps, motion, aiding and filter, then report route-wide errors and withheld-geography performance. (F013–F016)

### Gravity navigation: a new result with a consequential reporting inconsistency

The August 2026 maritime preprint reports GNSS exclusion from the evaluated gravity-aided processing chain. Its 83 km route ends at about 4.1 km error, versus about 26 km for the unaided INS. A separate surveying branch uses GNSS-derived position/velocity/attitude for corrections and georeferencing. [S14 Fig.2; Methods Gravity-aided navigation; Fig.8]

Its full-text abstract invokes nautical-mile DRMS, but the figure caption says the shaded one-mile region is not a reported DRMS statistic. Discussion wording suggests an approximately one-mile bound although the reported endpoint is 2.2 nautical miles. This is an internal reporting inconsistency. [S14 Abstract; Fig.2 caption; Results; Discussion]

*Analysis:* retain the reported endpoint error reduction; do not cite a demonstrated full-route one-mile bound or a computed DRMS. Initial-state provenance, live execution and long-duration closed navigation remain acceptance questions. Unequal sea conditions also limit broad gimbaled-versus-strapdown equivalence. (F017–F020, F096)

## 2. Detection and situational awareness

### Gravity cartography: demonstrated known-target sensing

Stray's outdoor gradiometer detects a known tunnel and estimates its horizontal location. Plans, ground-penetrating radar and topographic information support site modelling; depth inference remains broad and density uses an informative prior. The paper states that survey repeatability is similar to commercial gravimeters. [S30 pp.591–593; Methods; Extended Data Table2]

*Analysis:* this is a valuable field demonstration with controls and disclosed processing. It does not establish blind underground discovery, a false-alarm rate or unique target geometry. The estimated signal-to-noise ratio is not a null-hypothesis detection probability, and the projected faster survey needs further systematic-error reduction. (F025–F029)

### Microwave quantum radar: preserve the narrow result

Assouly's joint signal–idler receiver reports Q=1.2±0.1 relative to the modelled optimal coherent-state error-exponent bound. The target is a controllable filter/delay apparatus at 15 mK, with position, speed and reflectivity assumed known. The supplement excludes some measurement-protocol imperfections from its calibration uncertainty; the model also underestimates the measured advantage. [S31 pp.1–5; SupplementF]

*Analysis:* Astra identified a printed numerical discrepancy in the reviewed arXiv v2: the stated parameters give a classical exponent of about 2.47×10^-5, while one line prints 2.1×10^-5. The former produces Q≈1.18 from the stated measured exponent, consistent with the reported 1.2. The journal text was not checked for this specific error. [S31 pp.3–4; SupplementF]

*Analysis:* the arithmetic issue does not refute the reported modest advantage. Unknown-target search, open-air operation, systematic calibration robustness and practical range remain other tests. The 2025 efficient-operation paper further shows why receiver type, noise occupation and absolute time/resources must accompany comparisons; its analytical scope is not a universal radar no-go theorem. (F030–F034, F050–F054, F097) [S35 §§II–V]

### Atomic RF reception: distinguish tuning range, measured noise and comparator

Meyer's waveguide-coupled receiver spans DC–20 GHz tuning with 4 MHz instantaneous bandwidth. Direct sensitivity, phase-noise-subtracted limits and amplifier-referred calculations are different curves. Ambient reception uses an external antenna and amplification, and the manuscript discloses deteriorating waveguide transmission over seven months. [S32 Figs.1,3–4; AppendicesA,D]

The 2026 extremely-low-frequency study extends controlled response to 0.5 Hz–10 kHz. Its sensitivity comparison uses an estimated 3 cm dipole rather than a matched active classical experiment. Outdoor pickup, ground loops and drift remain engineering work. [S34 Figs.4–5; Outlook]

*Analysis:* the antenna/Rydberg comparison usefully includes an active high-impedance classical receiver, whose modelled performance exceeds present warm-vapour EIT sensing in the stated regime. Its printed input-referred-noise Eq.7 and ideal atomic Eq.10, however, do not follow the preceding definitions. The numerical-curve impact cannot be established without the supplementary implementation. [S33 Fig.3; p.144002-3; Eqs.7,9–10]

*Analysis:* atomic receivers have worthwhile bandwidth and coupling mechanisms. Advantage requires matched frequency, bandwidth, antenna, active electronics, optical support and external-noise conditions. Withhold numerical ideal-limit reuse from S33 until the equation/implementation discrepancy is resolved. (F035–F049, F098–F099)

## 3. Quantum-inspired optimisation

### Algorithmic results are real but benchmark-specific

Goto's simulated-bifurcation work shows fast results on selected Ising benchmarks using dedicated hardware. Large instances use 16 GPUs, with statistically estimated targets; some comparator times come from earlier publications because the authors could not access those machines. [S50 Figs.3–4; Results]

The multi-solver QUBO benchmark does not identify one winner across problem families. Its network time is excluded, requested versus reported time differs by solver, and the score reference is the best found by tested solvers. The sample also draws its 45 MQLib instances from a prior vendor benchmark set. [S51 pp.2–4; Eq.4]

*Analysis:* these papers justify considering physics-inspired algorithms. They do not replace a task-specific native classical portfolio, equal resource budgets or certified bounds. (F055–F060)

### Scheduling: formulation can decide the winner

The transport-robot study compares solver-specific native MIPs and QUBOs. Sequence Gurobi reaches Digital Annealer quality 10–100 times faster on minor instances; the hybrid Digital Annealer wins the equal-quality comparison for the largest N20 group. Submission-to-return timing includes network delays but excludes model construction. [S52 §§4.1–4.2; Figs.5,7]

The July 2026 industrial study adds useful hardware/formulation and feasibility evidence. Its timing excludes communications, APIs and queues despite end-to-end wording. Larger schedule references are one-hour best-found values; the model data are realistic but not live production, and dynamic arrivals are omitted. [S55 §§V-A,V-C,VII-E]

*Analysis:* neither result should be dismissed because the authors work in industry. Both need qualified comparator and workload descriptions. Native MILP/constraint-programming/heuristic portfolios, full workflow latency and feasibility should determine pilot value. (F061–F063, F071–F073, F100–F101)

### Scaling and tensor networks: include the negative results

The July 2026 revision of *Toward quantum scaling advantage* closes a reported gap with simulated bifurcation on the compared ensemble. It explicitly distinguishes compute and total runtime; four-GPU small-instance total times are roughly 100 times single-GPU times despite a better fitted exponent. Larger quantum counterparts are not measured in the classical-only extension. [S53 Main; SupplementsS1,S2,S5]

The tensor-network comparison exposes geometry and contraction limitations. Largest cases require severe local-state truncation, while planted cases reverse some quality rankings. Unknown-ground references use the best combined solver energy, with a particular normalization. [S54 §V; Eq.14; Fig.10; AppendixA]

*Analysis:* these are valuable precisely because they limit easy advantage narratives. An exponent, approximate energy or preferred graph family does not establish operational superiority. Keep latency, resource use, optimum certification and problem geometry visible. (F064–F070)

## 4. Emerging phenomena

### Distributed sensing: credible metrology with loss and infrastructure constraints

The published photonic field experiment achieves 0.916 dB below its photon-pass shot-noise limit at 240 m. The journal adds a separate 0.326 dB result without multipass weighting; its 10 km random-phase experiment fails to beat shot noise because of efficiency. Lost photons and multipair events are included in accounting. [S70 pp.2–5; AppendicesA,E]

The atomic network paper reports 11.6 dB below coherent-state projection noise in its four-mode clock task and 1.6 dB in a differential interferometer. These are modes sharing laboratory cavity infrastructure, not geographically separated operational clocks. A stronger mode-separable benchmark is projected rather than field-operated. [S71 Figs.3–4]

*Analysis:* reject a blanket objection that coincidences automatically invalidate the photonic result; its loss accounting addresses that concern. Equally, do not combine short-range gain with long-range reach or clock-network gain with interferometer gain. These mechanisms merit research on links, synchronization and acquisition bandwidth. (F074–F080)

### Matter-wave entanglement: a complete interferometer, at short evolution time

Greve reports 1.7±0.5 dB beyond its calibrated standard quantum limit in a complete matter-wave interferometer at 0.112 ms evolution time. The larger 3.4 dB comparison is against the actual imperfect-contrast unsqueezed instrument. Below-SQL phase sensitivity persists to approximately 0.7 ms. [S72 Fig.4; Methods Wineland parameter]

A separate preprint disputes the SQL/phase interpretation; this scan did not independently adjudicate its proposed alternative benchmark. The publisher correction restores omitted hbar labels and removes an incorrect manuscript link, without withdrawing numerical performance. [S76 pp.1–5][S77 correction notice]

*Analysis:* the demonstrated interferometer gain is relevant enabling science. Longer useful interrogation, calibrated acceleration response and complete-cycle resources matter more for navigation than a standalone squeezing number. An unadjudicated critique should not receive equal weight merely because it is sceptical. (F081–F083, F094–F095)

### Earth-field locking: useful proposal, not a measured magnetometer

The 2025 spin-locking paper is theoretical/numerical. Its predicted 4.29 fT/√Hz follows assumed cell volume, atom number and 10 ms coherence. Its maximum modelled rubidium gain approaches 2.9 dB; the resource is nuclear–electronic entanglement inside each atom, with no interatomic entanglement and no gain scaling with atom number. [S73 Discussion; Eqs.4–5; Fig.1]

*Analysis:* absence of interatomic entanglement does not discredit the stated intra-atomic mechanism. The unresolved questions concern measured readout noise, finite pulses and varying fields. This belongs in a research watchlist, not a field-demonstrated sensitivity table. (F084–F086)

### Collective absorption and electrical extraction: revise the frontier story carefully

The 2022 microcavity precursor infers stored excitation and charging dynamics from pump–probe spectroscopy. Only 6–8% of incident pump energy enters the cavity; extraction is not the demonstrated result. [S74 main pp.6–11; Table1]

The 2026 study adds electrical output of approximately 10–40 microW/cm² under continuous 625 nm illumination at 10 mW/cm². Separate spectroscopy tracks excitations lasting tens of nanoseconds. The cavity/control power ratio grows across its device family, but composition and detuning also vary, and its transport model supports the trend qualitatively. [S75 Figs.2–4; Methods; SupplementIV]

*Analysis:* electrical extraction is a substantive advance over optical charging alone. It does not establish delayed dark discharge, round-trip efficiency, cycle life or necessary nonclassical resources. Fixed-composition controls, net energy accounting and repeated charge/hold/discharge operation would make the storage claim assessable. (F087–F093, F102–F103)

## 5. Claims versus evidence

| Claim to qualify | What survives | What remains unresolved |
|---|---|---|
| Best-case quantum navigation accuracy [S13] | Improved map-aided endpoints in specified configurations | Aiding provenance, route-wide metrics, conventional-sensor ablation |
| One-mile/DRMS gravity-navigation performance [S14] | Reported 26 km→4.1 km endpoint reduction | Internally inconsistent metric; initialization and live autonomy |
| General quantum radar advantage [S31] | Modest cold known-target error-exponent result | Unknown targets, systematics, useful range and power |
| Numerical Rydberg/antenna limits [S33] | Need for an active classical baseline | Printed equations versus supplementary curves |
| End-to-end industrial optimisation superiority [S55] | Formulation and feasibility evidence | Excluded latency, native competitors, certified large bounds |
| Ten-kilometre advantageous sensing [S70] | Defined 240 m phase-estimation gain | Ten-kilometre test does not beat shot noise |
| Measured Earth-field quantum sensitivity [S73] | Numerical intra-atomic squeezing proposal | Instrument noise and experimental implementation |
| Practical quantum storage battery [S75] | Cavity-enhanced electrical extraction | Delayed discharge, cycling, net efficiency and resource causality |

*Table: adjudicated analyst interpretations. The cited sources define the measured/modelled boundaries; no row is a blanket rejection of its paper.*

## 6. What to carry into the next research stage

*Analysis, based on the located findings above.* Prioritise timing and motion engineering, qualified map-aiding, known-target gravity sensing and fair RF-receiver comparisons. Build optimisation evaluation around native formulations and complete costs. Carry squeezing/network metrology as enabling mechanisms, with cavity energy extraction as a frontier result requiring other storage tests.

The most useful new evidence would be independent route/data replay for navigation, blind multi-site underground surveys, matched active-receiver tests, native industrial scheduling benchmarks and experimental Earth-field locking. For quantum energy devices, require an electrically measured charge/hold/discharge sequence and net efficiency. These are proposed tests, not predictions of success.

## Evidence quality and remaining gaps

No experimental or computational replication was attempted. Requests-only or restricted data, unmatched preprint versions and unaccessed external supplements limit reproducibility assessment. No claim is made that independent replication does not exist outside the bounded search. [S01]

The radar arithmetic observation is restricted to arXiv v2, and the antenna-comparison equation/curve discrepancy remains unresolved. The 2025 correction to an earlier radar-engineering article was inaccessible, so predecessor-specific numerical limits are not reused. The Greve preprint critique remains unadjudicated. [S31 pp.3–4][S33 Eqs.7,9–10][S35 access record][S76]

Older literature, SQUID military applications, squeezed lidar, topological sensing/materials and time crystals were not deeply covered. No general computing or cryptographic-risk survey was performed, as agreed. This limits breadth; it does not establish that those areas lack useful research. [S01]

## Sources and detailed reviews

Use [paper reviews](paper-reviews.md) for each study's contribution, method, comparator, limitations, availability and application assessment. [Sources](../sources.md) records exact versions and located evidence; [findings](../findings.md) separates atomic claims from interpretation. [Challenge reconciliation](../reviews/reconciliation.md) records accepted, restricted and unresolved objections.


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
| S35 | [A Note on the Efficient Operation of Quantum Radar and the Fair Classical Comparison](https://elib.dlr.de/214537/1/A_Note_on_the_Efficient_Operation_of_Quantum_Radar_and_the_Fair_Classical_Comparison.pdf) | 2025-06-12 | T1 (peer-reviewed study; version examined specified) |
| S50 | [High-performance combinatorial optimization based on classical mechanics](https://doi.org/10.1126/sciadv.abe7953) | 2021-02-03 | T1 |
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
| S77 | [Publisher Correction: Entanglement-enhanced matter-wave interferometry in a high-finesse cavity](https://www.nature.com/articles/s41586-022-05582-4) | 2022-12-06 | T1 |
