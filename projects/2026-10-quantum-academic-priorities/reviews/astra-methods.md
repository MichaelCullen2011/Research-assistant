# Independent Astra methods challenge

Independent original-source pass; no Sol or Luna assessments read. All judgments below are **Analysis**. Final source IDs reconciled by study title. Five records were saved before the agent turn ended with a usage-limit error. The orchestrator verified the substantive findings; the optional Greve critique was not completed. No experimental replication or code execution of research packages. Publisher supplements belong to their parent source IDs.

## Toward quantum scaling advantage in approximate optimization

GPU simulated bifurcation is a substantive counterexample to the previously reported scaling gap on the same QAC-native Sidon-28 instances. It includes tuned replicas and steps, explicit CPU–GPU overheads, and comparisons under several quantum runtime definitions. This survives independent scrutiny as a benchmark-specific result. [S53 main Figs1–2; SupplementS5]

**Analysis — scope restriction:** finite-size fitted exponents do not establish general asymptotic complexity or scheduling advantage. The quantum comparison spans142–1322 variables; the larger classical-only extension reaches38320 with ten instances per size. The authors themselves show overhead-sensitive slopes. Four GPUs improve fitted scaling while approximately multiplying small-instance total runtime by100: exponent improvement is not latency improvement. Common initialization is omitted. [S53 SupplementS1–S2,S5]

**Analysis — missing evidence:** promising3D spin-glass scaling uses anneal time; practical QPU/access overheads remove the apparent advantage. Out-of-search-range optima are excluded from fits, and tighter target gaps produce unreliable optimization. This is a route to test on future hardware, not evidence that the application advantage already exists. No central-result flaw is established. Broader held-out ensembles and matched complete costs would resolve the application question. [S53 Fig4; SupplementS6]

## A Reality Check on Quantum Optimisation: Evidence from an Industrial Case Study

The strongest result is practical sensitivity to formulation: the Digital Annealer handles the tested larger assignment problems, whereas quantum feasibility degrades. Importantly, the study includes a native sequence-aware greedy/iterated-greedy classical comparator, not only an artificially awkward classical QUBO baseline. [S55 III-C,V,VI]

**Analysis — central reporting flaw:** V-C names “end-to-end” execution time, but VII-E explicitly excludes communication, APIs and queues. These measurements cannot establish operational end-to-end superiority. **Scope restriction:** the certified optimum stops at six machines,five rigs,fourteen jobs; larger references are one-hour best-found values. Later true-optimum/lower-bound descriptions must be qualified. [S55 V-A,V-C,VII-A,VII-E; Fig8]

**Analysis — missing evidence:** common empirical quadratic scaling does not substitute for equal wall-clock budgets or well-tuned native solver comparisons. Assignment QUBOs omit sequencing, and mean setup costs plus classical ordering restrict what is solved. Hardware-supported constraint separation also prevents treating DA performance as a lower bound for future physical annealers. [S55 III-A/B,VI-D,VII-B/C]

The case study remains useful for formulation and feasibility decisions. It needs matched full-workflow benchmarks and certified bounds before stronger advantage claims; industrial authorship and preprint status are not objections. [S55 VII–IX]

## Field Demonstration of Distributed Quantum Sensing without Post-Selection

The journal paper supports0.916dB phase-precision improvement over its photon-pass SNL across240m of fibre. It additionally reports0.326dB for the equal-weight two-sensor function. The loss-aware accounting includes lost photons,multipair events and Bob’s two phase passes; coincidence processing alone does not invalidate the no-postselection claim. [S70 II Eq2; III; AppendicesA/B/E]

**Analysis — scope restriction:**10km is a spool-extended experiment, and the six random-phase measurements there explicitly fail to beat SNL. Do not combine the short-distance advantage with long-distance reach. Waveplates encode the measurand, polarization calibration precedes acquisition, and synchronized single-photon apparatus supplies the network. This is a genuine field distribution experiment, not demonstrated defence sensing. [S70 II Fig1; III Fig3/TableI]

The resource metric is optical photon-passes, not infrastructure cost, wall energy or arbitrary classical architectures. The journal’s visibility-aware threshold is59.1%, replacing57.7% in the initial preprint; journal confidence regions and extra comparator likewise take precedence. **Analysis:** no central-result disproof found. Unknown physical-signal tests, bandwidth accounting and sustained long-distance advantage remain the useful next evidence. [S70 AppendixA; III Fig2; arXiv2011.02807v1]

## Quantum locking of intrinsic spin squeezed state in Earth-field-range magnetometry

This is a theoretical/numerical proposal, despite assertive abstract wording. The Discussion calls the magnetometer proposed and assumes a1cm3 room-temperature cell,1.42×10^10 atoms and10ms coherence time to calculate4.29fT/√Hz versus5.99fT/√Hz CSS SQL. These are not measured instrument sensitivities. [S73 Discussion; Eqs4–5; SupplementNote1]

**Analysis — scope restriction:** the squeezing comes from electron–nuclear coupling within individual atoms; its gain is independent of ensemble atom number. Lack of interatomic entanglement therefore does not refute its stated quantum resource. The supplement explicitly analyses intra-atomic entanglement. [S73 Eq4 discussion; SupplementNote3]

**Analysis — missing evidence:** preserving a model spin state does not demonstrate below-SQL total sensor noise after readout,finite pulses and technical field fluctuations. The paper considers readout/backaction and feedback, so claiming they are ignored would be unfair. But calculated1pT uncertainty and a±50pT robustness interval are not tracking measurements. Pulse timing requires instantaneous-rotation and rotating-wave approximations; timing-error robustness reoptimizes each deviation. [S73 Methods Figs7–8; SupplementNotes4–5]

Retain the mechanism as a promising control proposal. Experimental total-noise benchmarking against an optimized CSS magnetometer is the decisive unresolved test. [S73 Discussion]

## Superextensive electrical power from a quantum battery

The devices produce real electrical output under illumination, alongside ultrafast optical charging and metastable excitations. Paired no-cavity controls and a rising cavity/control power ratio make this more than an optical charging-only result. [S75 Results Fig2–4; SupplementIV-A]

**Analysis — scope restriction:** steady625nm illumination and I–V scans do not demonstrate delayed electrical discharge of previously stored energy,cycle endurance or round-trip efficiency. The reported10–40µW/cm2 output under10mW/cm2 illumination implies approximately0.1–0.4% incident optical conversion, not storage efficiency. [S75 MethodsDischarging power; Fig4]

**Analysis — missing evidence:** the precise scaling mechanism is less settled than headline language. Device composition,thickness and detuning vary; matched controls and fixed-average-cavity modelling address these concerns partly. SupplementS17 fits voltage asN^0.77 after excluding anomalousD4, rather than directly measuring an exact square-root law. The electrical model is explicitly qualitative. [S75 Deviceengineering,Fig2; SupplementTablesS1/S3,S17,IV-B]

Strong coupling and a successful quantum model do not alone demonstrate that nonclassical correlations are necessary for the electrical enhancement. That is an unresolved attribution question, not proof of a classical explanation. Replicated fixed-composition controls,delayed discharge,efficiency/cycle measurements and a resource-discriminating test would strengthen the application claim. [S75 MethodsTheoreticalmodel; SupplementII,IV]

Verification: five source identities and primary locators checked; JSON parsed on write. No research package, raw-data reanalysis or optional Greve/critical-preprint adjudication performed.
