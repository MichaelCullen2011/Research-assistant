# Findings: Critical academic scan of quantum priorities

Confidence applies to the scoped statement, not readiness: high = direct T1 support; medium = single T2 or version caveat; low = unresolved challenge. Paper-reported outcomes are not independent replications. Every result below is conditional on its paper’s protocol.

## Navigation and timing

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F001 | 35 L clock package excludes external power supply; ~85 W and 26 kg. | [S10 Main prototype integration paragraph; Fig.1a] | high | primary experimental paper; version/access caveat in sources |
| F002 | At sea PICKLES–EPIC pair instability is 8×10^-15 at 100,000 s, reported equivalent holdover ~400 ps/24 h without drift correction. | [S10 Main ship performance paragraph; Fig.3d] | high | primary experimental paper; version/access caveat in sources |
| F003 | Long-time single-clock upper bound divides pair performance by sqrt(2), assuming equal contributions. | [S10 Main summary performance paragraph; Fig.1c,d] | high | primary experimental paper; version/access caveat in sources |
| F004 | No independent standard reference was available at sea; correlated environmental sensitivities are acknowledged. | [S10 Main co-located clocks paragraph] | high | primary experimental paper; version/access caveat in sources |
| F005 | Yb stability is in the 10^-14 domain from 100 ms to 80 ks. | [S11 Results Individual clock stabilities; Fig.6] | high | primary experimental paper; version/access caveat in sources |
| F006 | Underway short-time clock performance resembles shore performance, but times above 100 s show decreased stability. | [S11 Results Individual clock stabilities; Figs.5–6] | high | primary experimental paper; version/access caveat in sources |
| F007 | ORAFS deployed ancillary system totals 310 kg and 1300 W. | [S11 Methods Optical rubidium atomic frequency standard—ORAFS; Table1] | high | primary experimental paper; version/access caveat in sources |
| F008 | Power interruption required personnel to restart ORAFS; UofA systems recovered automatically. | [S11 Results Clock frequency measurements; Fig.3] | high | primary experimental paper; version/access caveat in sources |
| F009 | Reconstructed fringe SNR 5.3 corresponds to 24 micro-g per shot at 20 ms interrogation. | [S12 Results Rotation compensation; Fig.3] | high | primary experimental paper; version/access caveat in sources |
| F010 | Experiment reaches tilts 0–30 degrees and rotation rates up to 14 degrees/s on a manual rotation platform. | [S12 Results setup; Fig.3] | high | primary experimental paper; version/access caveat in sources |
| F011 | Mirror-rate reconstruction uses fitted correction epsilon=-0.013. | [S12 Results Rotation compensation; Methods Correction of phase shift] | high | primary experimental paper; version/access caveat in sources |
| F012 | Vibration compensation assumes constant accelerometer response and global 610-microsecond delay. | [S12 Methods Limits of fringe reconstruction due to strong vibrations] | high | primary experimental paper; version/access caveat in sources |
| F013 | 22 m endpoint uses onboard sensor with 3D-velocity aid over 365 km. | [S13 Table1 row(a), 3D velocity] | medium | primary experimental paper; version/access caveat in sources |
| F014 | 46× endpoint improvement uses outboard sensor with 3D velocity; endpoint112 m. | [S13 Table1 row(a)dagger; Fig.4a] | medium | primary experimental paper; version/access caveat in sources |
| F015 | Onboard scalar-airspeed example ends at515 m over365 km; high-altitude onboard example ends at2 km over300 km. | [S13 Table1 rows(a) airspeed and(b) onboard] | medium | primary experimental paper; version/access caveat in sources |
| F016 | Algorithms and scalar sensor are proprietary; public text gives no same-input classical scalar-sensor ablation. | [S13 Q-CTRL MagNav System; Demonstration of MagNav; full v1 inspected] | medium | primary experimental paper; version/access caveat in sources |
| F017 | 83 km evaluated route ends at2.2 nmi (~4.1km), compared with14 nmi (~26km) unaided. | [S14 Results Quantum navigation with gravity map matching; Fig.2] | medium | primary experimental paper; version/access caveat in sources |
| F018 | Methods explicitly exclude embedded Boreas GNSS-derived position/velocity/attitude from navigation mechanization. | [S14 Methods Gravity-aided navigation] | medium | primary experimental paper; version/access caveat in sources |
| F019 | Separate surveying branch uses GNSS-disciplined PVA for rotation, Eotvos correction and georeferencing. | [S14 Methods Gravity signal for surveying and anomaly detection; Fig.8] | medium | primary experimental paper; version/access caveat in sources |
| F020 | Coastal strapdown traversals typically experienced Sea State1 versus gimbaled Sea States2–3. | [S14 Methods Maritime and land traversal details] | medium | primary experimental paper; version/access caveat in sources |
| F021 | Moderate/enhanced Sea State2 simulated measurements could not be tuned to useful stable aiding. | [S15 §IV; Fig.7] | medium | primary simulation/method paper; version/access caveat in sources |
| F022 | Successful high-dynamic flight aiding assumes100-fold reduced roll/pitch. | [S15 §IV; Fig.8] | medium | primary simulation/method paper; version/access caveat in sources |
| F023 | 3.3-degree static tilt requirement follows a specified10 E error budget, not universal accuracy tolerance. | [S15 AppendixB.1 Static tilts] | medium | primary simulation/method paper; version/access caveat in sources |
| F024 | Runs start with30 s transfer alignment and assumed100 m north/east initialization errors. | [S15 §IV Integration with a map-matching navigation filter] | medium | primary simulation/method paper; version/access caveat in sources |

## Detection and situational awareness

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F025 | Outdoor sensitivity 466 ± 8 E/√Hz; 20 E uncertainty in ten minutes. | [S30 p.591, Fig.2] | high | field experiment; version/access caveat in sources |
| F026 | Survey known 2m×2m tunnel with plans/GPR/topography informing site model. | [S30 pp.591–592] | high | field experiment; version/access caveat in sources |
| F027 | Horizontal-centre inference 0.19 ± 0.19 m; depth 1.89 −0.59/+2.3 m. | [S30 Methods PDF p.8] | high | field experiment; version/access caveat in sources |
| F028 | Survey repeatability similar to commercial gravimeters; systematics remain. | [S30 p.593] | high | field experiment; version/access caveat in sources |
| F029 | 75 kg head, 250 kg cases, approximately 800 W. | [S30 Extended Data Fig.2, PDF p.10] | high | field experiment; version/access caveat in sources |
| F030 | Measured Q=1.2 ± 0.1 relative to coherent-state error-exponent bound. | [S31 Fig.3; PDF pp.3–4] | medium | cryogenic laboratory experiment; version/access caveat in sources |
| F031 | 15 mK apparatus and target built from notch filter/12m coaxial line. | [S31 PDF p.2] | medium | cryogenic laboratory experiment; version/access caveat in sources |
| F032 | Target position, speed and reflectivity assumed known. | [S31 PDF p.1, protocol paragraph] | medium | cryogenic laboratory experiment; version/access caveat in sources |
| F033 | Population-calibration uncertainty mostly statistical; measurement imperfections not included. | [S31 Supplement F, PDF p.11] | medium | cryogenic laboratory experiment; version/access caveat in sources |
| F034 | Model underestimates measured advantage; origin unresolved. | [S31 PDF p.5, Fig.4 discussion] | medium | cryogenic laboratory experiment; version/access caveat in sources |
| F035 | Carrier tuning DC–20GHz; 4MHz instantaneous bandwidth. | [S32 PDF pp.1,4, Fig.3c] | medium | laboratory receiver experiment; version/access caveat in sources |
| F036 | PSN-limited sensitivity removes independently calibrated phase noise; amplifier noise curves calculated. | [S32 PDF p.3, Fig.1d] | medium | laboratory receiver experiment; version/access caveat in sources |
| F037 | Ambient signal reception uses external antenna and amplification. | [S32 PDF pp.4–5, Fig.4] | medium | laboratory receiver experiment; version/access caveat in sources |
| F038 | Approximately 50°C chamber and 500mW coupling laser. | [S32 Appendix A, PDF p.7] | medium | laboratory receiver experiment; version/access caveat in sources |
| F039 | Waveguide transmission deteriorated over seven months; contamination attribution provisional. | [S32 Appendix D, PDF p.8] | medium | laboratory receiver experiment; version/access caveat in sources |
| F040 | Example uses 1cm sensors and 30kHz–30MHz frequency range. | [S33 article pp.144002-2–3] | high | analytical baseline comparison; version/access caveat in sources |
| F041 | Active baseline assumes 1nV/√Hz voltage noise and 100MΩ input impedance. | [S33 p.144002-3] | high | analytical baseline comparison; version/access caveat in sources |
| F042 | Active unmatched antenna outperforms contemporary warm EIT within model. | [S33 p.144002-4, Fig.3] | low | analytical baseline comparison; printed-equation consistency unresolved; figure implementation not checked |
| F043 | Ideal cold-atom SQL limit likely physically unrealizable; collective effects omitted. | [S33 p.144002-4] | high | analytical baseline comparison; version/access caveat in sources |
| F044 | All sensor external-noise directivities assumed equal dipole. | [S33 p.144002-2, Eq.1 discussion] | high | analytical baseline comparison; version/access caveat in sources |
| F045 | Controlled sensing spans 0.5Hz–10kHz. | [S34 p.8, Fig.4; Appendix E] | high | laboratory electrometry experiment; version/access caveat in sources |
| F046 | Sensitivity 819 μV/cm/√Hz at 1Hz and 2 μV/cm/√Hz at 1kHz. | [S34 p.1; p.9 Fig.5] | high | laboratory electrometry experiment; version/access caveat in sources |
| F047 | Classical comparator theoretically estimated for 3cm dipole. | [S34 p.9, Fig.5b] | high | laboratory electrometry experiment; version/access caveat in sources |
| F048 | Microscopic charge-transport mechanism not directly measured. | [S34 p.6] | high | laboratory electrometry experiment; version/access caveat in sources |
| F049 | Outdoor pickup, ground loops and drift require further mitigation. | [S34 p.10 Outlook] | high | laboratory electrometry experiment; version/access caveat in sources |
| F050 | Efficiency differs from maximum relative advantage for specified receiver. | [S35 pp.877–878, Eqs.10–22, Fig.1] | high | analytical receiver comparison; version/access caveat in sources |
| F051 | Model assumes large sample number/Gaussian approximation. | [S35 p.877 Section III restrictions] | high | analytical receiver comparison; version/access caveat in sources |
| F052 | Follow-up leaves channel loss parameterised rather than computing target range. | [S35 p.876 Eq.5 discussion] | high | analytical receiver comparison; version/access caveat in sources |
| F053 | Comparator prediction mismatch depends on noise occupancy. | [S35 pp.878–879 Eqs.23–28] | high | analytical receiver comparison; version/access caveat in sources |
| F054 | Ideal implementation assumed; real implementation may degrade further. | [S35 p.879 Conclusion] | high | analytical receiver comparison; version/access caveat in sources |

## Quantum-inspired optimisation

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F055 | The bSB K2000 TTT is 0.26 ms; dSB TTS is 1.3 s. | [S50 Results: Benchmarking using time-to-solution and time-to-target; Fig.3B–C] | high | journal article; version/access caveat in sources |
| F056 | Ultralarge benchmarks use 16 GPUs and statistically estimated optimal/target values. | [S50 Results: Fig.4 and accompanying text] | high | journal article; version/access caveat in sources |
| F057 | Other-machine TTS/TTT is cited or estimated from literature because authors could not use those machines. | [S50 Results: Benchmarking using time-to-solution and time-to-target] | high | journal article; version/access caveat in sources |
| F058 | 45 MQLib problems were selected from the HSS white-paper benchmark set. | [S51 p.2, Problem instances for benchmarking] | high | journal article; version/access caveat in sources |
| F059 | Network time is ignored; HSS and SBM use requested budgets whereas DA uses reported elapsed time. | [S51 p.3, Results] | high | journal article; version/access caveat in sources |
| F060 | Reference score denominator is lowest value found by tested solvers, not certified optimum. | [S51 p.4 Eq.(4)] | high | journal article; version/access caveat in sources |
| F061 | 260 instances split161 minor2071–8080 variables and99 major10822–22692. | [S52 §3.1; Table1] | medium | journal article; version/access caveat in sources |
| F062 | Submission-to-return runtimes include network delays but exclude programmatic model construction. | [S52 §4.1 opening paragraph] | medium | journal article; version/access caveat in sources |
| F063 | Sequence Gurobi reaches QFDA quality10–100 times faster on minor instances; hybrid DA advantage for N20 major instances. | [S52 §4.1 Fig.5; §4.2 Fig.7] | medium | journal article; version/access caveat in sources |
| F064 | Original comparison uses125 instances per size N142–1322 and100 solver runs; Gurobi certifies original ground reference. | [S53 main text Thermal vs Chaotic vs Quantum Annealing, Eq.1] | medium | journal article; version/access caveat in sources |
| F065 | Total SBM runtime includes CPU-GPU transfer/memory/result handling; pure GPU time excludes those. | [S53 main text Eq.1 discussion; supplement S5] | medium | journal article; version/access caveat in sources |
| F066 | Common initialization costs are neglected and GPU samples are parallel whereas QA samples sequential. | [S53 supplement S5 Runtime accounting] | medium | journal article; version/access caveat in sources |
| F067 | Four-GPU total TT-epsilon is about100 times the single-GPU value for the small-instance comparison due to dispatch/collection overhead, despite improved fitted exponent. | [S53 Supplement S1 Multi-GPU Simulated Bifurcation Machine, Fig.S1] | medium | journal article; version/access caveat in sources |
| F068 | Largest5376-spin Pegasus TN runs require local dimension reduction to2^16 states due to memory. | [S54 §V.3 Fig.10] | medium | journal article; version/access caveat in sources |
| F069 | Reference dE=(E-Ebest)/(2/Ebest/) uses combined solver best when true ground unknown. | [S54 §V.2 Eq.14] | medium | journal article; version/access caveat in sources |
| F070 | Planted cases improve best-energy difference by factor3–4; ground states not found for721/3065-spin cases. | [S54 §V.3; AppendixA Fig.A1] | medium | journal article; version/access caveat in sources |
| F071 | Beyond6 machines5 rigs14 jobs, reference is best found within1h rather than certified optimal. | [S55 §V-A Benchmark] | medium | preprint; version/access caveat in sources |
| F072 | Communication latencies, API overhead and queue delays excluded despite end-to-end label in metrics. | [S55 §V-C item3; §VII-E Ecological Validity] | medium | preprint; version/access caveat in sources |
| F073 | Data realistic but not directly sourced from live production; dynamics such as new job arrivals omitted. | [S55 §VII-E] | medium | preprint; version/access caveat in sources |

## Emerging phenomena

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F074 | At 240 m, best phase precision is 0.916 dB below the loss-accounted photon-pass shot-noise limit. | [S70 journal pp.2,5; Fig.2] | high | experiment; version/access caveat in sources |
| F075 | The non-multipass equal-weight phase experiment is 0.326 dB below its shot-noise limit. | [S70 journal p.5; Appendix E p.8] | high | experiment; version/access caveat in sources |
| F076 | The 10 km random-phase experiment does not beat the shot-noise limit because of losses. | [S70 journal p.5; Fig.3 and Table I] | high | experiment; version/access caveat in sources |
| F077 | Visibility-aware threshold efficiency in the journal version is 59.1%. | [S70 journal p.2; Appendix A p.6] | high | experiment; version/access caveat in sources |
| F078 | Four-mode clock result11.6(1.1)dB below coherent-state QPN. | [S71 arxivv1 main text, four-mode network paragraph and Fig.3] | medium | published journal study; reviewed preprint manuscript; version/access caveat in sources |
| F079 | 4.5(0.8)dB improvement uses a projected mode-separable baseline. | [S71 arxivv1 Fig.3 and accompanying paragraph] | medium | published journal study; reviewed preprint manuscript; version/access caveat in sources |
| F080 | Differential atom-interferometer improvement1.6(0.9)dB. | [S71 arxivv1 Fig.4 and accompanying paragraph] | medium | published journal study; reviewed preprint manuscript; version/access caveat in sources |
| F081 | Full interferometer shows1.7±0.5dB below calibrated SQL at0.112ms. | [S72 journal Fig.4b and Entangled matter-wave interferometry] | high | experiment; version/access caveat in sources |
| F082 | 3.4dB compares actual squeezed and imperfect-contrast unsqueezed interferometers. | [S72 journal Entangled matter-wave interferometry; Methods Wineland parameter] | high | experiment; version/access caveat in sources |
| F083 | Below-SQL phase sensitivity persists up to approximately0.7ms evolution time. | [S72 journal Fig.4d and accompanying text] | high | experiment; version/access caveat in sources |
| F084 | Rb maximum modelled metrological gain approaches2.9dB. | [S73 Results Fig.1b, Eq.5] | high | theory and numerical simulation; version/access caveat in sources |
| F085 | No atom–atom entanglement appears; gain independent ofN. | [S73 Results Spin squeezing, Eq.4–5] | high | theory and numerical simulation; version/access caveat in sources |
| F086 | 4.29fT/sqrt(Hz) comes from assumed cell,atom number and coherence. | [S73 Discussion numerical sensitivity paragraph] | high | theory and numerical simulation; version/access caveat in sources |
| F087 | Pump–probe spectroscopy extracts excitation energy and fitted charging dynamics. | [S74 arxiv main pp.6–11,Figs.2–3,Table1] | medium | published journal study; reviewed preprint manuscript; version/access caveat in sources |
| F088 | Only6–8% of incident pump energy enters cavity. | [S74 arxiv main p.7,Experimental setup] | medium | published journal study; reviewed preprint manuscript; version/access caveat in sources |
| F089 | Dissipation/dephasing suppresses collective re-emission and stabilizes energy. | [S74 arxiv main pp.3,11–14; supplementary model] | medium | published journal study; reviewed preprint manuscript; version/access caveat in sources |
| F090 | Electrical output densities approximately10–40microW/cm². | [S75 Results electrical discharge paragraph,Fig.4c; supplementIV.A] | high | experiment; version/access caveat in sources |
| F091 | Cavity/control power ratio increases withN; modeledPc~N². | [S75 Results Fig.4d; supplementIV.B] | medium | experiment; version/access caveat in sources |
| F092 | Metastable optical excitation persists tens of nanoseconds. | [S75 Fig.3a and accompanying text] | high | experiment; version/access caveat in sources |
| F093 | 126nm cavity length fixed while optical length varies. | [S75 supplement p.3,Fig.S1] | high | experiment; version/access caveat in sources |

## Corrections and challenges

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F094 | A non-peer-reviewed preprint disputes the interpretation of the Greve interferometer experiment. This scan has not independently adjudicated its proposed alternative SQL benchmark. | [S76 v2 pp.1–5] | low | preprint critique; version/access caveat in sources |
| F095 | Publisher correction restores omitted hbar labels and removes a mistaken peer-review-manuscript link. | [S77 correction notice, correction paragraph] | high | publisher correction; version/access caveat in sources |

## Additional located findings from independent challenge and reconciliation

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F096 | The full-text abstract invokes nautical-mile DRMS, but Fig.2 explicitly says the one-mile band is not reported DRMS; Results endpoint is2.2nmi while Discussion describes an approximately one-mile bound. | [S14 Abstract; Fig.2 caption; Results Quantum navigation; Discussion] | medium | Reporting detail; consequence adjudicated separately |
| F097 | The reviewed arXivv2 prints Ecl=2.1×10^-5 alongside kappa=0.0302, NS=0.0353, NN=10.8 and Ecl=kappa NS/(4NN). | [S31 arXivv2 pp.3–4; SupplementF] | medium | Reporting detail; consequence adjudicated separately |
| F098 | Printed Eq.7 multiplies voltage-noise variance by the voltage-divider magnitude squared, despite describing input-referred noise. | [S33 p.144002-3, Eq.7] | high | Reporting detail; consequence adjudicated separately |
| F099 | Definitions Q=omega tau exp(-tau Gamma) and output variance tau/N precede printed Eq.10 containing2Gamma/(e omega²N). | [S33 p.144002-3, Eqs.9–10] | high | Reporting detail; consequence adjudicated separately |
| F100 | Native sequence Gurobi reaches Digital Annealer quality10–100times faster on minor instances; the hybrid Digital Annealer wins the equal-quality comparison for the largest N20 group. | [S52 §§4.1–4.2; Figs.5,7] | medium | Reporting detail; consequence adjudicated separately |
| F101 | Digital Annealer results are compared with greedy and iterated-greedy approximations; the paper does not establish superiority over all tuned native scheduling solvers. | [S55 §§III-C,V-B,VI-D,VII-C] | medium | Reporting detail; consequence adjudicated separately |
| F102 | Electrical output is measured under constant625nm illumination; excitation persistence is measured separately by transient optical spectroscopy. | [S75 Fig.3; Fig.4b–d; Methods Discharging power] | high | Reporting detail; consequence adjudicated separately |
| F103 | Electrical input illumination is10mW/cm²; measured output densities are10–40microW/cm². | [S75 Methods Discharging power; SupplementIV-A] | high | Reporting detail; consequence adjudicated separately |

| F104 | Both clock studies used the RIMPAC2022 exercise; different architectures do not constitute independent marine campaigns. | [S10 RIMPAC test setup], [S11 RIMPAC2022 paragraph] | high | Shared test environment |

## Contradictions and open questions

- S14 contains inconsistent DRMS/full-route-bound wording; retain reported endpoint reduction and separate GNSS-aided survey metrics. [S14 Abstract; Fig.2 caption; Results; Discussion]
- S31 printed v2 classical exponent is inconsistent with its printed calibration parameters; the parameter-derived ratio agrees with Q≈1.2. Journal-version correction status was not checked. [S31 arXiv v2 pp.3–4; Supplement F]
- S33 printed Eqs.7 and10 do not follow the stated input-referred-noise definitions. Numerical-curve impact remains unresolved without the supplementary implementation. [S33 p.144002-3]
- S55 end-to-end wording conflicts with explicit exclusion of API/communication/queue latency; large references are best-known, not certified optimal. [S55 §§V-A,V-C,VII-E]
- S70 journal version adds a non-multipass result and adjusts threshold versus the initial preprint; final outputs use journal values. [S70 pp.2,5; AppendixE]
- S76 challenges S72 but its alternative baseline was not independently adjudicated. S77 is a label/link correction, not a withdrawal of numerical results. [S76 pp.1–5; S77 correction notice]

## Detailed method and context observations

Per-paper method, baseline, apparatus, availability and caveat observations are retained in the corresponding source-notes entries in [sources.md](sources.md). These support the detailed paper reviews in addition to the104atomic main findings. Numerical/result statements carry the original reviewer locators; own interpretation remains labelled.

## Analysis (orchestrator interpretation)

- Prioritise complete-system timing evidence, motion compensation and well-controlled anomaly sensing. Strong laboratory performance needs a separate operational acceptance test. (F001–F028)
- Report navigation accuracy by aiding mode and route-wide metric; do not attribute combined sensor/software/map gains uniquely to the quantum device. (F013–F024)
- Select optimisation methods by native problem structure and equal-quality full-workflow cost. A favourable exponent, best-known energy or QUBO solver result does not establish a service advantage. (Quantum-inspired findings above)
- Emerging sensing gains are scientifically useful when SQL/resource definitions are explicit. Intra-atomic entanglement is a valid mechanism despite absent interatomic entanglement. (Emerging findings above)
- Cavity-enhanced electrical output is a material advance; delayed discharge, storage efficiency and operational energy density require other measurements. (S75 located findings above)

## Verification log

### Verification: 2026-10-12
- Claims checked: all 104 atomic findings and all factual output paragraphs checked for source coverage and scoped wording; detailed apparatus/method context also retained in source notes. Source/index equality:27 entries, comprising24core studies,2contextual academic/correction sources and internal auditS01. All output source IDs exist. Brief/report source tables cover every cited ID.
- Original-source spot checks by orchestrator:12sources (S10 pairwise timing/reference and RIMPAC; S11 restart/support and shared campaign; S13 Table1 aiding modes; S14 route endpoint/DRMS/survey separation; S31 printed parameters and exponent; S33 visual Eqs7/9/10; S53 version/runtime initialization; S55 latency exclusion; S70 journal added result/loss limit; S72 evolution-time/gain distinction; S73 proposed versus measured sensitivity; S75 steady illumination/output versus storage). Relevant original text or journal PDF reopened/read; no reliance on search snippets for these claims.
- Independent review:6sensing and5methods/emerging Astra records reconciled. Second batch saved complete records before usage-limit interruption; orchestrator verified substantive findings. Unsupported automatic postselection/no-interatomic-entanglement objections rejected. Greve critique adjudication not completed.
- Figures/equations: S33 checked visually in original publisher PDF. S31 parameter-derived exponent/Q and S33 exponential-factor algebra cross-checked with assert-based arithmetic. No experimental or dataset/code replication performed.
- Issues fixed: manuscript-access tiers made consistentlyT2; claim confidence capped accordingly; S33 comparison confidence reduced to low pending implementation checks; S70 updated from initial preprint to journal result; provisional Astra IDs matched by title;0.7ms boundary corrected; both timing studies identified as RIMPAC2022; Greve contextual citations attached; source/metadata/selection counts reconciled.
- Prose: repository edit-prose pass completed on brief/report and paper reviews; no listed tells or em-dashes remain. Brief body689words before the source table; report within the requested deep-dive scale. All quotations are short labels/terms or source titles; no long verbatim excerpts used.
- Links and changed files: local output links resolve; external URLs are complete but not all live availability rechecked. Git status/diff and the untracked changed-file list reviewed: only this new task folder changed. Working-document caches are Git-ignored. No existing project, instructions, dependencies or application code modified. No commits/pushes or external messages.
- Remaining caveats: unmatched journal/manuscript versions; S31 numerical observation restricted to arXivv2; S33 equation-versus-curve impact unresolved; several external supplements/access/reproduction archives unverified; correction to earlier radar article inaccessible; S76 critique unadjudicated; older2016–2020covered mainly through screening; no replication; broad frontier topics outside deep coverage.
- Result: PASS WITH CAVEATS
