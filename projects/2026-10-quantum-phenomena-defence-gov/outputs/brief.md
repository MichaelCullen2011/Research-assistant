# Quantum phenomena to defence and government use cases: Brief

*10 October 2026 · Sources: 115 logged, 40 cited · Overall confidence: medium to high (low for timelines)*

## Bottom line

Today's defence and government quantum uses rest on three phenomena: quantised atomic energy levels, matter-wave superposition and spin precession. These drive the clocks, atom interferometers and magnetometers now in field trials. Entanglement matters for computing and QKD but not yet for fielded sensing. Two of the three priority areas, PQC and quantum-inspired methods, run on classical hardware: PQC answers a future quantum threat, and quantum-inspired solvers borrow quantum mathematics. Confidence is high on the phenomenon map and sensing maturity, and low on any dated timeline.

## Key findings

1. **The phenomena split into three bands.** Some have been deployed for decades: NMR in MRI, tunnelling, the Josephson effect, atomic transitions in caesium clocks. Some are in defence field trials now: compact clocks, cold-atom sensors, optically pumped magnetometers. The rest are lab or theory with asserted applications. [S20][S19][S27][S16][S37][S31][S34][S50][S54]
2. **Field-trialled defence sensors use quantised levels and coherence, not entanglement.** Quantum radar, the main entanglement-based sensing idea, has beaten the best classical radar by a factor of 1.2, inside a dilution refrigerator. Its advantage appears only at signal powers 15–20 orders of magnitude below radar practice. The US Defense Science Board says it "will not provide upgraded capability", and UK MOD calls it "immature". The UK is trialling radar networks timed by cold-atom clocks instead. [S30 §II][S112][S45 §VI][S93][S116][S118]
3. **Timing is the most mature link.** Optical clocks ran 20 days at sea with under 300 ps/day error. Dstl plans a wider military clock trial in 2027, and the UK has committed £180m to a National Timing Centre. [S37][S39][S106]
4. **Navigation sensors are held back by engineering.** DARPA calls quantum sensors "notoriously fragile in real-world environments". Cold-atom sensors would roughly halve inertial drift, not remove it. The UK's 2024 quantum navigation flight published no performance data. [S42][S32][S48]
5. **PQC is classical mathematics responding to a quantum threat.** NIST standards have been final since August 2024. NCSC sets milestones of 2028, 2031 and 2035 and will not support QKD for government or military use. [S71][S73][S75]
6. **Quantum-inspired methods are the near-term computing offer.** In a July 2026 Siemens scheduling study, IBM hardware solved only toy instances. A quantum-inspired Digital Annealer handled industry-scale problems and beat classical heuristics. Tensor networks also reproduced IBM's 2023 "utility" experiment classically. [S110][S79][S80]
7. **Many frontier claims are theory crafting.** Microsoft's Majorana paper does not itself establish topological states, so this work leaves it out of the bands. Reviews say time-crystal applications "are limited" and that no working quantum battery exists. Room-temperature superconductor claims were refuted or retracted. [S50][S57][S54][S67][S68]

## Visual

| Band | Phenomenon | Technology | D&G use case | Maturity |
|---|---|---|---|---|
| A | Atomic transitions | Caesium clocks | Satnav and national timing | Deployed [S16][S106] |
| B | Atomic transitions | Compact optical and cold-atom clocks | Timing holdover, resilient PNT | Field trial [S37][S39] |
| B | Matter-wave superposition | Atom-interferometer gravimeters, inertial sensors | Tunnel detection, GNSS-free navigation | Field trial [S31][S48] |
| B | Spin precession | Optically pumped magnetometers | Magnetic navigation, brain scanning | Field trial; vendor-only data [S34][S107] |
| C | Rydberg atoms | RF receivers | Spectrum awareness, EW | Lab demo [S49] |
| B | Quantised levels; photoelectric effect | QRNG, single-photon sources and detectors | Components for quantum networking | Commercial [S12][S60][S58] |
| C | Entanglement | Quantum radar; QKD and quantum networks | Counter-stealth; secure comms | Rejected for UK and US mission use [S93][S116][S75] |
| Response | Superposition, entanglement, interference (qubits) | Quantum computer → PQC (classical) | Protecting government cryptography | PQC standards final [S71][S74] |
| Borrowed | Tunnelling, adiabatic evolution, limited entanglement | Quantum-inspired solvers (classical) | Logistics, scheduling | Industry-scale demo [S110][S84] |

*Band A: deployed for decades. B: field-trialled now, or commercial as components. C: lab or theory. PQC and quantum-inspired methods sit outside the bands because they run on classical hardware. The rows are a summary of Table 1 in the report, which lists 27 phenomena.*

## Implications

*Analysis.*
- Shortlist the Band B phenomena for the whitepaper's main story, and use Band A as credibility anchors. Use Band C to show judgement about what is not ready.
- Lead with the point that the "old" quantum does the work in defence sensing.
- Present PQC and quantum-inspired methods as classical answers to quantum ideas. That makes them adoptable now and easier to evidence.
- Recommend benchmarking against quantum-inspired and best classical solvers before any quantum optimisation purchase.
- Give readers two questions: has anyone else reproduced the result, and has it left the lab?

## Open questions & caveats

- No published performance data exists for UK quantum navigation trials. Magnetic navigation results are vendor-only. [S34][S48]
- The newest public Dstl view on quantum computing dates from 2020. [S87]
- Quantum radar placement is open. Entanglement radar is lab-only; quantum-timed radar is in UK field trials, but no performance figures are published. [S112][S116][S118]
- QKD positions differ: NCSC rejects it, NATO leaves it open, and the European Commission promotes it. [S75][S14][S94 §2.4]
- Code-breaking timelines are uncertain. RUSI suggests about ten years, but its author has a conflict of interest. NCSC calls the timing hard to predict, and DOD judged quantum computers at least ten years away in July 2025. [S100][S74][S93]
- Several frontier sources are preprints. The Siemens study is a preprint with heuristic baselines. [S110]

## Sources

| ID | Source | Tier | Date |
|---|---|---|---|
| S12 | [The European Quantum Technologies Roadmap](https://arxiv.org/abs/1712.03773), A. Acín et al. | T2 | 2017-12-11 |
| S14 | [Summary of NATO's Quantum Technologies Strategy](https://www.nato.int/cps/en/natohq/official_texts_221777.htm), NATO | T1 | 2024-01-16 |
| S16 | [The Quantum Age: technological opportunities (Blackett Review)](https://assets.publishing.service.gov.uk/media/5a81828c40f0b62302697b29/gs-16-18-quantum-technologies-report.pdf), UK Government Office for Science | T1 | 2016 |
| S19 | [Press release: The 1973 Nobel Prize in Physics](https://www.nobelprize.org/prizes/physics/1973/press-release/), Royal Swedish Academy of Sciences | T1 | 1973-10-23 |
| S20 | [Press release: The Nobel Prize in Physiology or Medicine 2003](https://www.nobelprize.org/prizes/medicine/2003/press-release/), Nobel Assembly at Karolinska Institutet | T1 | 2003-10-06 |
| S27 | [Ampere: The Quantum Metrology Triangle (NIST SI Redefinition)](https://www.nist.gov/si-redefinition/ampere/ampere-quantum-metrology-triangle), NIST | T1 | created |
| S30 | [Quantum sensing (Degen, Reinhard & Cappellaro)](https://arxiv.org/abs/1611.02427), Reviews of Modern Physics | T1 | 2017 |
| S31 | [Quantum sensing for gravity cartography (Stray et al.)](https://www.nature.com/articles/s41586-021-04315-3), Nature 602, 590–594 | T1 | 2022-02-23 |
| S32 | [Cold atom inertial sensors for navigation applications (Wright et al.)](https://www.frontiersin.org/journals/physics/articles/10.3389/fphy.2022.994459/full), Frontiers in Physics 10 | T1 | 2022-10-03 |
| S34 | [Quantum-assured magnetic navigation achieves positioning accuracy better than a strategic-grade INS in airborne and ground-based field trials (Muradoglu et al., Q-CTRL)](https://arxiv.org/abs/2504.08167), arXiv | T2 | 2025-04-10 |
| S37 | [Optical clocks at sea (Roslund et al.)](https://www.nature.com/articles/s41586-024-07225-2), Nature 628 | T1 | 2024 |
| S39 | [Trial speeds up next generation of atomic clocks (Dstl)](https://www.gov.uk/government/news/trial-speeds-up-next-generation-of-atomic-clocks), Defence Science and Technology Laboratory | T1 | 2026-02-18 |
| S42 | [From fragile to field-ready: RoQS program launches first phase (DARPA)](https://www.darpa.mil/news/2025/roqs-launches-first-phase), DARPA | T1 | 2025-08-27 |
| S45 | [Detecting a target with quantum entanglement (Sorelli, Treps, Grosshans & Boust)](https://arxiv.org/abs/2005.07116), arXiv; review written for radar engineers | T2 | 2020-05-14 |
| S48 | [UK completes first test flight of 'un-jammable' quantum navigation system (Euronews)](https://www.euronews.com/2024/05/13/uk-completes-first-test-flight-of-un-jammable-quantum-navigation-system), Euronews | T2 | 2024-05-13 |
| S49 | [MANTRAS: Manufacturing Technologies for Rydberg-based Atomic Sensors (DARPA SBIR-XL topic)](https://www.darpa.mil/research/programs/mantras), DARPA Small Business Programs Office | T1 | 2026 |
| S50 | [Interferometric single-shot parity measurement in InAs–Al hybrid devices](https://www.nature.com/articles/s41586-024-08445-2), Nature 638, 651–655 | T1 | 2025-02-19 |
| S54 | [Colloquium: Quantum Batteries](https://arxiv.org/abs/2308.02277), arXiv | T2 | 2023-08-04 |
| S57 | [Time Crystals on Quantum Devices](https://arxiv.org/abs/2605.27211), arXiv | T2 | 2026-05-26 |
| S58 | [Ultra-low carrier density superconducting bolometers with single photon sensitivity based on magic-angle twisted bilayer graphene](https://arxiv.org/abs/2403.02049), arXiv; Science Advances | T2 | 2024-03-04 |
| S60 | [Quantum dots for photonic quantum information technology](https://arxiv.org/abs/2309.04229), arXiv | T2 | 2023-09-08 |
| S67 | [Single crystal synthesis, structure, and magnetism of Pb10-xCux(PO4)6O](https://arxiv.org/abs/2308.06256), arXiv | T2 | 2023-08-11 |
| S68 | [RETRACTED ARTICLE: Evidence of near-ambient superconductivity in a N-doped lutetium hydride](https://www.nature.com/articles/s41586-023-05742-0), Nature 615, 244–250 | T1 | 2023-03 |
| S71 | [NIST Releases First 3 Finalized Post-Quantum Encryption Standards](https://www.nist.gov/news-events/news/2024/08/nist-releases-first-3-finalized-post-quantum-encryption-standards), NIST | T1 | 2024-08-13 |
| S73 | [Timelines for migration to post-quantum cryptography](https://www.ncsc.gov.uk/guidance/pqc-migration-timelines), UK National Cyber Security Centre | T1 | 2025-03-20 |
| S74 | [Next steps in preparing for post-quantum cryptography (white paper, v2.0)](https://www.ncsc.gov.uk/whitepaper/next-steps-preparing-for-post-quantum-cryptography), UK NCSC | T1 | originally |
| S75 | [Quantum networking technologies (NCSC white paper)](https://www.ncsc.gov.uk/whitepaper/quantum-security-technologies), UK NCSC | T1 | 2025-08-05 |
| S79 | [Efficient tensor network simulation of IBM's Eagle kicked Ising experiment](https://arxiv.org/abs/2306.14887), Joseph Tindall, Matt Fishman, Miles Stoudenmire, Dries Sels | T1 | arXiv |
| S80 | [Fast and converged classical simulations of evidence for the utility of quantum computing before fault tolerance](https://arxiv.org/abs/2308.05077), Tomislav Begušić, Johnnie Gray, Garnet Kin-Lic Chan | T1 | arXiv |
| S84 | [Physics-Inspired Optimization for Quadratic Unconstrained Problems Using a Digital Annealer](https://arxiv.org/abs/1806.08815), Maliheh Aramon, Gili Rosenberg, Elisabetta Valiante, Toshiyu | T1 | arXiv |
| S87 | [Quantum Information Processing Landscape 2020: Prospects for UK Defence and Security](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/899418/20200331-DSTL-TR121783-FINAL-pdfa.pdf), MOD, DSTL/TR121783 | T1 | 2020-06 |
| S93 | [Defense Primer: Quantum Technology (CRS IF11836)](https://www.everycrsreport.com/reports/IF11836.html), Kelley M. Sayler, Congressional Research Service | T1 | 2026-05-12 |
| S94 | [Quantum Europe Strategy, COM(2025) 363](https://digital-strategy.ec.europa.eu/en/library/quantum-europe-strategy), European Commission | T1 | 2025-07-02 |
| S100 | [Quantum Technologies in the UK: Risks and Opportunities for National Security](https://static.rusi.org/quantum-technologies-and-national-security-march-2025.pdf), Rob Young; RUSI | T2 | 2025-03 |
| S106 | [Cutting-edge timing technology to protect vital services (National Timing Centre)](https://www.gov.uk/government/news/cutting-edge-timing-technology-to-protect-vital-services), DSIT, National Physical Laboratory and Lord Vallance | T1 | 2026-03-07 |
| S107 | [A Revolution in Brain Imaging Technology (OPM-MEG)](https://wellcome.org/insights/articles/opm-meg-revolution-brain-imaging-technology), Wellcome | T3 | 2026-07-07 |
| S110 | [A Reality Check on Quantum Optimisation: Evidence from an Industrial Case Study](https://arxiv.org/abs/2607.13325), arXiv | T2 | 2026-07-14 |
| S112 | [Demonstration of Quantum Advantage in Microwave Quantum Radar](https://arxiv.org/abs/2211.05684), Assouly et al.; Nature Physics | T1 | 2023-03-02 (v2) |
| S116 | [Written question 113398: Quantum Technology: Radar](https://questions-statements.parliament.uk/written-questions/detail/2026-02-12/113398), UK Parliament (MOD answer) | T1 | 2026-02-26 |
| S118 | [Aquark Augments Networked Radars With Quantum-Based Timing in Trial](https://thequantuminsider.com/2026/08/12/aquark-augments-networked-radars-with-quantum-based-timing-in-trial/), Aquark press release via The Quantum Insider | T3 | 2026-08-12 |
