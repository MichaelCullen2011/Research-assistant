# Quantum-inspired optimisation: six full-text reviews

Reviewed 12 October 2026. These six studies were selected from discovery for complementary roles: a methods anchor, cross-family benchmark, realistic constrained scheduling, rebuttal to scaling claims, tensor-network failure diagnosis, and recent industrial counterweight. Discovery candidates were leads and original full texts were reopened. Selection does not add to Luna’s distinct-candidate count.

No correction/retraction notice was found in targeted searches or Crossref update metadata; this bounded check does not certify absence. Versions and dates below supersede discovery aliases. Five studies have linked journal publications; S55 remains a preprint. No solver replication was performed.

## S50 — High-performance combinatorial optimization based on classical mechanics

- **Source:** https://doi.org/10.1126/sciadv.abe7953 (T1); Version of record, full article via EuropePMC XML; publisher online date 3 February; Crossref issue date 5 February 2021.
- **Dates:** first preprint not established; journal 2021-02-03; region Japan.
- **Access:** full-text; local extraction `projects/2026-10-quantum-academic-priorities/reviews/inspired-docs/anchor.txt`.

Goto and colleagues introduce ballistic and discrete simulated bifurcation, numerical classical dynamics inspired by nonlinear quantum oscillators. Inelastic walls improve convergence; sign discretisation suppresses continuous-variable errors. The paper compares FPGA implementations and larger GPU calculations with other Ising machines. Its K2000 result is target time-to-target of 0.26 ms for bSB and optimal/best-known time-to-solution of 1.3 s for dSB, using a 99% success criterion. These metrics answer different questions. [S50 Results, Fig.3]

The large-scale demonstration is valuable, but the million-spin claim needs care: the GPU experiments use statistically estimated reference energies rather than certified instance optima. The 16-GPU implementation combines an algorithmic improvement with substantial parallel hardware. Other-machine results were cited or estimated from literature because the authors lacked access; some comparators were older hardware or simulator predictions. The time step was selected from five values and step counts optimised separately for the target metric. [S50 Results, Fig.4; Benchmarking; Methods]

*Analysis:* this establishes a useful competitive classical baseline, not a general theorem that quantum-inspired dynamics win. The central method is explicit enough to reconstruct, but independent matched-budget replication, tuned contemporary classical heuristics, and native constrained scheduling comparisons would strengthen transfer. End-to-end formulation and constraint feasibility are absent from these Ising tests. Toshiba employment and a declared patent interest warrant recording without dismissing the equations or results. [S50 Competing interests; Discussion]

The full main article was reviewed; the separately hosted supplement was not retrieved. Consequently its detailed FPGA resource and comparator reconstruction tables remain an access gap. *Analysis:* retain this as a historical methods anchor, with deployment confidence low.

## S51 — Benchmark of quantum-inspired heuristic solvers for quadratic unconstrained binary optimization

- **Source:** https://www.nature.com/articles/s41598-022-06070-5 (T1); Publisher PDF version of record; arXiv latest v3 15 December 2021.
- **Dates:** first preprint 2021-04-29; journal 2022-02-09; region Japan.
- **Access:** full-text; local extraction `projects/2026-10-quantum-academic-priorities/reviews/inspired-docs/benchmark.txt`.

This benchmark is most useful for its changing winners: HSS leads the mixed MQLib set, DA leads the tested NAE-3SAT regime, and SBM leads SK spin glasses. The five-minute MQLib experiment counts ties, producing 22 HSS, 20 DA, 16 SBM and seven SA wins; these are comparative wins rather than optimum certificates. Its score uses the best observed energy among the four solvers. [S51 pp.3–7, Eq.4, Figs.1–3]

The comparator is D-Wave neal SA on one i9-9900K CPU thread, against specialised or cloud systems. SBM automatically searches parameters; its evaluation build is proprietary. HSS internals are closed, so the benchmark cannot isolate any QPU contribution. Time is also heterogeneous: requested HSS/SBM budgets, reported DA elapsed time, and locally measured SA sampling time; network communication is excluded. [S51 pp.2–3]

*Analysis:* the paper supports problem-dependent solver selection, but provides a weak basis for a blanket claim that these services beat competitive classical optimisation. Equal wall-clock allocations on unspecified unequal compute resources are not equal resource budgets. An operational follow-up should add tuned parallel tempering, modern QUBO/local-search portfolios and native mathematical models, reporting feasibility and true business objectives rather than only encoded energy.

The MQLib set comprises 45 instances inherited from HSS’s white-paper selection; synthetic tests average ten NAE-3SAT and six SK instances, with independent runs for plotted points. Public instance generators help reproducibility, but additional data are request-only and service internals remain opaque. D-Wave and Toshiba research support is acknowledged despite a no-conflicts declaration. [S51 pp.2,7,9–10] *Analysis:* confidence is moderate for the reported ranking on these configurations and low for broad logistical superiority.

## S52 — An Optimization Case Study for solving a Transport Robot Scheduling Problem on Quantum-Hybrid and Quantum-Inspired Hardware

- **Source:** https://arxiv.org/abs/2309.09736 (T1); arXiv v4 24 October2023; linked Scientific Reports13,18743.
- **Dates:** first preprint 2023-09-18; journal 2023-10-31; region Germany / UK-linked collaboration.
- **Access:** full-text; local extraction `projects/2026-10-quantum-academic-priorities/reviews/inspired-docs/robot.txt`.

The case study models robot movements and laboratory processing motivated by BASF, comparing a QUBO with two native Gurobi MIPs. This is a stronger application comparison than forcing every solver through the same QUBO. Its 260 generated instances split into 161 minor cases with 2,071–8,080 QUBO variables and 99 major cases with 10,822–22,692. [S52 §§2–3, Table1]

The crucial contribution is equal-quality timing: Gurobi’s progress log identifies when it first matches each heuristic’s final objective, avoiding comparison of heuristic approximation time with exact optimality-proof time. Sequence Gurobi reaches DA quality 10–100 times faster on minor instances; the hybrid DA is faster at comparable quality for the largest 20-sample instances. Gurobi still generally finds better final objectives. Some D-Wave hybrid outputs are infeasible. [S52 §4.1, Figs.3–5; §4.2, Figs.6–7]

Reported end-to-end time includes network delays from submission to solution return but excludes constructing the optimisation model. Major-instance Gurobi equal-quality times are capped at 3,600 seconds when the target is not reached; this is censoring rather than a measured matching time. DA hybrid budgets were allocated from five hours, approximately proportional to variable count. The comparator is an out-of-box solver; tailored metaheuristics were explicitly excluded. [S52 §§3.2,4.1]

*Analysis:* this supports a bounded positive case for specialised classical annealing in large constrained scheduling, while preserving a strong negative result for smaller problems. Near-constant heuristic runtimes are partly budget choices, so they do not establish superior asymptotic complexity. Transfer to defence logistics requires representative constraints, repeated-run uncertainty, tuned classical alternatives, and model-construction costs. The paper itself describes a technology snapshot rather than general advantage. [S52 §5]

## S53 — Toward quantum scaling advantage in approximate optimization

- **Source:** https://arxiv.org/abs/2505.22514 (T1); arXiv v2 10 July2026; PhysRevApplied26,014024; earlier title Closing the Quantum-Classical Scaling Gap in Approximate Optimization.
- **Dates:** first preprint 2025-05-28; journal 2026-07-08; region Poland.
- **Access:** full-text; local extraction `projects/2026-10-quantum-academic-priorities/reviews/inspired-docs/scaling.txt`.

This is the revised, published successor to the 2025 preprint titled “Closing the Quantum-Classical Scaling Gap”; using its old title or calling it unreviewed would misstate the source. The reviewed v2 is dated 10 July 2026 and links to Physical Review Applied 26, 014024. [S53 arXiv identity/version; journal DOI]

The authors test the same Sidon-28 QAC-graph instances as the challenged study: 125 per size, 142–1,322 variables, and 100 independent solver runs. They optimise simulated-bifurcation steps and parallel replicas against a 99%-success time-to-epsilon metric, with original reference ground energies certified using Gurobi. GPU SBM closes the reported scaling gap on these problems. Larger classical instances extend to 38,320 variables, beyond the tested QPU range. [S53 main text, Eq.1, Figs.1–3]

The supplement distinguishes GPU compute time, total CPU/GPU execution, QPU access and externally measured runtime. Common initialization costs are nevertheless omitted; GPU replicas execute together whereas annealer samples are sequential. Sparse 3D spin glasses retain favourable quantum annealing-time scaling, but current operational overhead prevents demonstrated practical scaling advantage. [S53 S5–S7; Fig.4]

*Analysis:* the strongest conclusion is that the earlier classical baseline was insufficient and runtime accounting can change the verdict. It is not evidence that SBM dominates every sparse instance, nor that fits at relaxed energy targets establish exact-optimisation complexity. Tuning steps and replicas is legitimate but its search budget should accompany operational procurement comparisons. Improved four-GPU scaling comes with about100-fold small-instance total-time overhead versus one GPU: an exponent is not absolute speed. [S53 S1] Extended-size classical success does not directly measure a future QPU. Quantumz.io affiliations and request-only new data constrain independence and reproducibility. [S53 acknowledgments/data availability] *Analysis:* high confidence in the need for this baseline, moderate in generalisation beyond this benchmark.

## S54 — Limitations of tensor-network approaches for optimization and sampling: A comparison to quantum and classical Ising machines

- **Source:** https://arxiv.org/abs/2411.16431 (T1); arXiv v3 16 June2025; PhysRevApplied23,054049.
- **Dates:** first preprint 2024-11-25; journal 2025-05-19; region Poland / US.
- **Access:** full-text; local extraction `projects/2026-10-quantum-academic-priorities/reviews/inspired-docs/tensor.txt`.

This study makes tensor-network failure an object of investigation rather than hiding it behind selected successes. The method combines approximate marginals with branch-and-bound, sparse PEPS representations and GPU computation. Twenty instances per selected size underpin the comparisons; random Pegasus and Zephyr graphs test more difficult connectivity than earlier Chimera examples. [S54 §§III–V, Fig.10]

At 5,376 Pegasus spins, memory forces local state reduction to 2^16 configurations per cluster. On the tested random problems, TN is slower and returns worse energies than SBM/QA; planted square-lattice cases embedded into Pegasus reverse the quality ranking, improving the best-energy gap by a factor of three to four. The larger planted cases still do not reach their known ground states. Thus the negative finding is geometry and instance dependent. [S54 §V.3; AppendixA, Fig.A1]

The error measure is dE=(E−Ebest)/(2|Ebest|), and Ebest pools solver outputs when ground truth is unknown. This must not be silently relabelled as a conventional certified optimality gap. A 216-spin diagnostic shows a trade-off between low-temperature search resolution and approximate contraction stability; dimensional preprocessing can itself remove the optimum. [S54 §V.2, Eq.14; §VI, Fig.12]

*Analysis:* this is persuasive evidence of a concrete limitation in this implementation, not a no-go theorem for tensor networks. Sampling diversity is separately assessed and cannot be inferred from one best-energy result. Runtime comparisons also need cloud-access overhead and hardware budgets before operational interpretation. Open Julia code and an instance/results repository make this relatively reproducible, though neither was executed here. [S54 §VII; Data availability; AppendicesD–E] *Analysis:* useful for screening solver proposals, with no demonstrated constrained-logistics deployment.

## S55 — A Reality Check on Quantum Optimisation: Evidence from an Industrial Case Study

- **Source:** https://arxiv.org/abs/2607.13325 (T2); arXiv v1 14 July2026; no journal reference displayed at review.
- **Dates:** first preprint 2026-07-14; journal none displayed; region Germany.
- **Access:** full-text; local extraction `projects/2026-10-quantum-academic-priorities/reviews/inspired-docs/reality.txt`.

Safi and colleagues compare industrially motivated scheduling across IBM, D-Wave, Fujitsu DA and classical approaches. Their QUBOs encode job-to-machine assignments; sequencing remains classical. Constraint-rich and compact formulations deliberately trade fidelity against solvability. DA reaches more than 10,000 logical variables, while current quantum devices are limited to small cases, and QUBO compilation choices materially affect DA validity. [S55 §§III,V–VI]

The reference-quality caveat is decisive: the exact branch-and-bound solver certifies small cases only, with the largest tractable example at six machines, five rigs and 14 jobs. Larger references are the best found within one hour, although some figures use optimal-reference language. DA exceeds the tested greedy/iterative approximations; this does not establish superiority over a broadly tuned classical portfolio. [S55 §V-A; §VI-D, Fig.8; §VII-C]

Runtime also needs correction before reuse. Section V-C labels a metric end-to-end execution time, but Section VII-E explicitly excludes communication latency, API overhead and queues. The authors further acknowledge realistic data are not drawn directly from live production and omit dynamic arrivals. Outputs from DA and hybrid D-Wave expose limited top solutions rather than full sample distributions. [S55 §§V-C,VII-B,VII-E]

*Analysis:* the useful result concerns formulation, feasibility and specialised classical hardware, not an operational quantum speedup. Claiming DA as a lower bound for future fault-tolerant annealing is an assumption, not an experimental result; the authors themselves note DA’s separate constraint handling is unavailable on current physical annealers. [S55 §VII-B] The v1 preprint and claimed reproduction package warrant independent review before high-confidence adoption. *Analysis:* moderate confidence in configuration-specific engineering lessons, low in universal solver ranking or live scheduling advantage.

## Verification and gaps

Claims are tied to section/figure/equation locators and checked against downloaded primary full text. JSON includes author/version identities, baseline/runtime/feasibility caveats, reproducibility, conflicts and reviewed sections. Main text and integrated supplements were reviewed for S53/S54; S50’s external supplement, S52’s external supplementary tables and S55’s archive remain unverified access gaps. No abstracts were presented as full reviews.

*Analysis:* none of these studies establishes quantum-inspired superiority across constrained government or defence logistics. S52 supplies the strongest bounded application-positive result; S53 demonstrates why a strong GPU baseline and explicit timing accounting are compulsory; S54 shows a concrete negative result can coexist with class-specific success. Portfolio optimisation was not deeply reviewed in this six-paper allocation.
