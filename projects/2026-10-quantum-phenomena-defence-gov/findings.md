# Findings: Quantum phenomena to technologies to defence and government use cases

Each finding makes one specific, checkable claim. Group findings under the
brief's sub-questions.

Confidence levels:
- **high**: at least one T1 source, or several independent T2 sources, and no credible contradiction
- **medium**: one T2 source, or several T3 sources from different parties
- **low**: one T3 source only, or sources conflict

Maturity tags used in Notes: *theory*, *lab demo*, *prototype*, *field
trial*, *product/deployed*. "Evidenced" means a source shows the
application working at that level; "asserted" means the source only claims
it.

## Sub-question 1: Phenomena map: which phenomena underpin first-wave technologies, and which are being researched now?

### Framing

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F01 | Dowling and Milburn set out the "second quantum revolution": the first revolution used quantum rules to explain the world (semiconductors, photoelectric effect, laser); the second engineers quantum states on purpose to build new technology. | [S10 abstract, intro] | medium | arXiv version, 2002; framing only |
| F02 | Dowling and Milburn list six principles that quantum technology exploits: quantisation, uncertainty, superposition, tunnelling, entanglement and decoherence. | [S10 "Quantum principles"] | medium | Useful spine for the phenomenon list |
| F03 | UK government separates first-generation quantum technologies (lasers, superconducting devices in medical imaging, MRI) from second-generation ones based on "the ability to generate, detect and control quantum states". | [S13 intro, foreword] | high | |
| F04 | Government and alliance strategies group quantum by application, not phenomenon: EU uses computing and simulation, sensing, communication; NATO uses sensing, imaging, PNT, communications, computing, modelling and simulation. | [S15 fn.1], [S14 intro], [S12 intro] | high | Only academic sources enumerate phenomena |
| F05 | The Nobel Committee (2022) credits early Bell-test experiments on entanglement with driving the "Second Quantum Revolution". | [S29 conclusions] | high | |
| F06 | The 2025 Nobel Prize in Physics recognised macroscopic quantum tunnelling and energy quantisation in superconducting circuits; the release calls the transistor an established quantum technology and links the work to quantum cryptography, computers and sensors. | [S18] | high | Applications are stated as "opportunities" |

### First-wave anchors (phenomenon → established technology)

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F07 | Nuclear magnetic resonance became MRI once field gradients were added (Lauterbur; Mansfield at Nottingham); by 2002 there were about 22,000 scanners and over 60 million exams a year. | [S20] | high | product/deployed |
| F08 | Transistors and lasers exploit the fixed (quantised) energies of electrons in crystals; the Blackett review calls quantum technology "the foundation of the digital age". | [S16 Ch.1, foreword], [S18] | high | product/deployed |
| F09 | The maser and laser came from "quantum electronics" (Nobel 1964). | [S26], [S13] | high | Naming the phenomenon "stimulated emission" is a gloss, not in S26 |
| F10 | Quantum tunnelling underpins the tunnel diode (Esaki, 1958) and the scanning tunnelling microscope (Nobel 1986). | [S19], [S23] | high | product/deployed |
| F11 | The Josephson effect and the quantum Hall effect give the voltage and resistance standards; since the 2019 SI redefinition their constants are exact. | [S27], [S25] | high | product/deployed |
| F12 | The first caesium atomic clock was built at NPL in 1955; the SI second has been defined by the caesium transition since 1967; satnav, phones and the internet depend on atomic clocks. | [S16 timeline, Ch.2] | high | product/deployed |
| F13 | The CCD image sensor (1969) uses the photoelectric effect. | [S22] | high | product/deployed |
| F14 | Giant magnetoresistance (1988, Fert at CNRS/Thales and Grünberg) reached hard-disk read heads in 1997. | [S21] | high | Classing GMR as a quantum spin effect is *Analysis*; S21 does not say "quantum" |
| F15 | Magnetic tunnel junctions (spin-dependent tunnelling) are commercial as hard-disk read heads and MRAM memory elements. | [S53 intro] | medium | One review sentence; product/deployed |

### Second-wave phenomena under active applied research

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F16 | Quantum sensing works at three levels: quantised energy levels, coherence (superposition), and entanglement used to beat classical limits; only the third is described as "truly quantum". | [S30 §II] | high | |
| F17 | Atom interferometry (superposition of atomic matter waves) is applied to gravity, rotation and acceleration sensing. | [S30], [S31], [S12] | high | |
| F18 | Spin coherence in diamond NV centres gives millisecond coherence at room temperature and is used for magnetic, temperature, electric-field and pressure sensing. | [S12 spin sensing], [S30 Table I] | high | |
| F19 | Rydberg atoms have large electric dipole moments and are read out optically (EIT), making them electric-field and RF sensors; Rydberg blockade also enables neutral-atom quantum gates. | [S30 §III.C], [S44 §II], [S28] | high | |
| F20 | Squeezed light reduces quantum noise in gravitational-wave detectors (GEO600, LIGO). | [S12], [S46] | high | |
| F21 | Entanglement underpins QKD, teleportation, quantum repeaters and quantum computing. | [S29], [S17] | high | |
| F22 | The no-cloning theorem is the security basis of quantum communication and also forces the use of repeaters or satellites, because quantum signals cannot be amplified classically. | [S29] | high | |
| F23 | Quantum measurement randomness is the basis of quantum random number generators (QRNGs). | [S12], [S75] | high | Band B: product (see F109) |
| F24 | Topological phases explain the quantised Hall steps; hoped-for applications include topological electronics and quantum computers. | [S25] | high | Established use is only the resistance standard |
| F25 | Further phenomena under active research for applications: magnetic skyrmions, polariton condensates, superabsorption ("quantum batteries"), time crystals, moiré superconductivity in twisted graphene, radical-pair magnetoreception, strong light–matter coupling in chemistry and optomechanical entanglement. | [S53], [S59], [S54], [S55], [S58], [S62], [S64], [S66] | high | Maturity of each in SQ3 |

## Sub-question 2: Phenomenon → technology: what does recent research connect each phenomenon to?

### Sensing, timing and navigation

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F26 | A Birmingham cold-atom gravity gradiometer (Dstl co-author, MoD-contracted) detected a 2 m buried utility tunnel with signal-to-noise ratio 8 and 0.5 m resolution in a static outdoor survey. | [S31 abstract, acknowledgements] | high | field trial (static); on-the-move mapping not shown |
| F27 | A UK simulation study found cold-atom sensors would roughly halve the drift of an aviation-grade inertial navigation system by calibrating its biases, but not remove drift, and are unlikely to suit small, cheap systems near term. | [S32 §5–6] | high | Peer-reviewed simulation, 2022 |
| F28 | A French hybrid quantum–classical accelerometer triad showed 50× better bias stability than its navigation-grade classical accelerometers, in the lab. | [S33 abstract] | medium | Preprint version read; lab demo |
| F29 | The UK flew a quantum inertial navigation system (atomic clock and cold-atom motion sensor) on an RJ100 at Boscombe Down in May 2024; no performance data was published. | [S48] | medium | Single T2 news source |
| F30 | Three 35-litre iodine optical clocks ran for 20 days on a naval ship in the Pacific with timing error below 300 ps per day, matching hydrogen masers at one-tenth the volume. | [S37 abstract] | high | field trial, peer-reviewed |
| F31 | Aquark announced that its cold-atom AQlock clock ran for three days aboard HMS Pursuer with Dstl test-and-evaluation support; no performance figures were given. | [S38] | low | Vendor release only |
| F32 | Dstl ran long-term unattended trials of next-generation atomic clocks outside the lab (reported Feb 2026), cites GPS denial as the driver, plans a broader military trial in 2027 and restates the goal of quantum navigation on UK aircraft by 2030. | [S39] | high | field trial |
| F33 | Optically pumped magnetometers spin-polarise alkali atoms with light and read out their precession; sensitivity reaches about 100 aT/√Hz, on a par with SQUIDs. | [S30 §III.A.1] | high | |
| F34 | Q-CTRL reports airborne magnetic-anomaly navigation with quantum magnetometers up to 19,000 ft, claiming up to 46× lower position error than a strategic-grade inertial system (best 22 m). | [S34 abstract] | medium | Vendor-authored preprint; CEO quoted at 94× in [S47]. Researcher-over-relay: use 46× |
| F35 | A Warwick and Element Six diamond NV magnetometer worked in a moving van, but low-frequency sensitivity on the move was about 140–210 nT/√Hz per axis. | [S35 abstract, p.1] | medium | Preprint; prototype |
| F36 | SQUIDs are the most commercially advanced quantum sensor (used in clinical MEG) but need cryogenic cooling. | [S30 §III.G.1] | high | product/deployed |
| F37 | Wearable OPM-MEG brain scanners are in research use but not clinically approved; developers hope for approval in 2027. | [S107], [S36 abstract] | medium | S107 is T3; S36 abstract-only |
| F38 | Rydberg receivers detect from MHz to THz but usually have instantaneous bandwidth below 10 MHz. | [S44 §III.C] | medium | Preprint |
| F39 | DARPA states that Rydberg sensor capability has been validated only in lab-scale proof-of-concept and seeks an integrated prototype under 10 litres and 50 W for spectrum awareness and signal identification. | [S49] | high | lab demo → prototype |
| F40 | LIGO's frequency-dependent squeezing cut detector noise by up to 5.8 dB and raised its astrophysical detection rate by up to 65%. | [S46 abstract] | high | Deployed in a science facility |
| F41 | Entanglement improved a pair of optomechanical force sensors by 25% in sensitivity–bandwidth in a lab demo funded by ONR and DARPA; the authors suggest inertial navigation as an application. | [S66 abstract, Fig. 5, acknowledgements] | medium | Application author-asserted |

### Computing and cryptography

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F42 | A fault-tolerant quantum computer running Shor-type algorithms could break RSA and elliptic-curve public-key cryptography (RSA, FFDH, ECDH, DSA, ECDSA, EdDSA). | [S73], [S74] | high | |
| F43 | Gidney's 2025 estimate for breaking RSA-2048 is under one million noisy qubits in under a week, down from 20 million qubits in his 2019 estimate, under the same hardware assumptions. | [S70 abstract] | medium | Preprint |
| F44 | NCSC says current quantum computers are limited, with relatively high error rates, and the arrival of a cryptographically relevant one is hard to predict. | [S74] | high | |
| F45 | Symmetric cryptography with keys of at least 128 bits and hashes such as SHA-256 are "not significantly impacted" by quantum computing (NCSC); Grover's algorithm gives at most a quadratic speedup. | [S74], [S81 intro] | high | |
| F46 | QKD detects eavesdropping using measurement disturbance, but provides no authentication, so it must be paired with PQC or pre-shared keys. | [S75] | high | |
| F47 | NCSC says classical random number generators still meet security needs; QRNGs may offer higher entropy rates and need assurance research. | [S75] | high | |
| F48 | Deterministic quantum-dot single-photon sources now match or beat heralded sources and InGaAs dots are commercially available; telecom-wavelength dots still fall short. | [S60] | medium | Preprint of review; Band B component (networking) |
| F49 | Microsoft's Nature paper reports a fermion-parity readout in InAs–Al nanowires but states the measurements "do not, by themselves, determine whether the low-energy states ... are topological"; qubit claims were made by press release, not in the paper. | [S50 Discussion], [S51] | high | Excluded from bands A–C; hype-check example only (see Analysis) |

### Quantum-inspired (classical) methods

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F50 | Toshiba's simulated bifurcation is a classical algorithm inspired by quantum adiabatic optimisation in nonlinear oscillators; its authors report a 2,000-node MAX-CUT solved on FPGA in 0.5 ms, about 10× faster than a coherent Ising machine. | [S83] | medium | Peer-reviewed but vendor-authored, chosen baselines |
| F51 | Fujitsu's Digital Annealer is classical CMOS hardware running enhanced simulated annealing; it gave about 100× speedups on dense spin glasses against single-core baselines and none on sparse 2D problems. | [S84] | high | |
| F52 | Tensor-network methods, whose efficiency rests on limited entanglement in the simulated state, reproduced IBM's 2023 127-qubit "utility" experiment classically within weeks, one more accurately than the quantum processor and one finding errors in IBM's extrapolations. | [S78], [S79], [S80] | high | |
| F53 | D-Wave published a "beyond-classical" quantum-simulation result in Science (2025); a tensor-network preprint reports matching accuracy with modest classical resources. | [S85], [S86] | medium | Rebuttal is a preprint; contested |
| F54 | Tang (STOC 2019) showed the leading quantum recommendation algorithm has a classical analogue only polynomially slower, removing its exponential speedup ("dequantisation"). | [S77] | high | |

## Sub-question 3: Reality check: how mature is each link, and where are application claims speculative?

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F55 | Lab optical clocks reach better than 10⁻¹⁸ fractional inaccuracy, but transportable versions have been held back by size, environmental sensitivity and cost. | [S37 abstract] | high | |
| F56 | DARPA describes quantum sensors as "notoriously fragile in real-world environments"; its RoQS programme tests walk-on sensors on a helicopter and defers platform integration to a later phase. | [S42] | high | |
| F57 | CSIS notes platform noise, vibration and thermal drift degrade quantum sensors on moving platforms. | [S99] | medium | Think tank |
| F58 | Quantum-illumination radar only shows an advantage at source powers 15–20 orders of magnitude below radar practice; the French review calls its practical relevance limited. | [S45 §VI] | high | Supported by [S93], [S103], [S99] |
| F59 | The US Defense Science Board concluded quantum radar "will not provide upgraded capability to DOD". | [S93] | high | DSB study date not verified, possibly pre-2022 |
| F60 | Almost all field-trialled defence quantum sensors (clocks, atom interferometers, OPMs, NV, Rydberg) rely on quantised levels and superposition, not entanglement. | [S30 Table I], [S41] | medium | Partly *Analysis* by the sensing stream |
| F61 | A 46-author review concludes "more tools are needed to realize a quantum advantage in optimization" and notes classical heuristics often solve practical instances near-optimally. | [S81 intro] | high | |
| F62 | QOBLIB (2025) provides ten classically hard optimisation problem classes with state-of-the-art classical baselines; it reports quantum baselines, not advantage. | [S82 abstract] | medium | Preprint |
| F63 | In a 2026 Siemens industrial scheduling study, IBM gate-based hardware solved only toy instances, D-Wave did better only with a compact formulation, and the Fujitsu Digital Annealer handled industry-scale instances and beat classical heuristics on solution quality. | [S110 §VI.D, §VIII.B–C] | medium | Preprint; baseline at scale is heuristics, not best-in-class solvers |
| F64 | A UK critique argues the Microsoft topological-qubit data are "not reliable"; a Matters Arising and Microsoft reply appeared in Nature in June 2026, and an earlier Microsoft-funded Majorana paper was retracted in 2021. | [S52 abstract], [S50 article page], [S51] | high | Contested, unresolved. Excluded from bands A–C; hype-check example only (see Analysis) |
| F65 | MRAM is a product, while skyrmion racetrack memory and logic remain research-stage. | [S53] | medium | |
| F66 | Magnetic tunnel junctions for STT-MRAM kept key properties under high gamma and neutron doses in one 2019 study; the authors suggest space and nuclear use. | [S69 abstract] | medium | Preprint, 2019 (stale) |
| F67 | The quantum-battery field's own review states "a fully operational quantum battery is yet to be demonstrated". | [S54 Sec. VII] | medium | Preprint of review |
| F68 | Google observed a time-crystal phase on a quantum processor (2021); a 2026 review says current applications "are limited", while a 2025 Aalto press release says time crystals "could power" quantum-computer memory. | [S55], [S57 Sec. V], [S56] | medium | Example of press framing ahead of evidence |
| F69 | A twisted bilayer graphene device detected single 1550 nm photons at tens of millikelvin; one author is at Raytheon BBN; no defence application is stated. | [S58] | medium | lab demo |
| F70 | Polariton condensates support room-temperature polariton lasing; uses in computing and qubits are described as "promising". | [S59] | high | lab demo / prototype |
| F71 | An 18-author review finds quantum coherences in photosynthesis "too short lived to have any functional significance". | [S61 abstract] | high | 2020 |
| F72 | Robin cryptochrome 4 is magnetically sensitive in vitro, supporting the radical-pair model of bird navigation; the in-vivo mechanism is still unproven. | [S62 abstract] | high | 2021; no navigation device exists |
| F73 | Oxford engineered magneto-sensitive fluorescent proteins that work at room temperature in living cells, proposed for biomedical imaging. | [S63] | medium | Specialist press; lab demo |
| F74 | Reported cavity-enhanced reaction rates under vibrational strong coupling have not reproduced (Penn State 2021), and in May 2026 the US Naval Research Laboratory reported its own 2023 effect vanishes once artefacts are corrected. | [S64 abstract], [S65 abstract] | medium | S65 is a conference abstract |
| F75 | LK-99 single crystals are insulating, and the Dias group's 2023 room-temperature superconductor paper was retracted by Nature on 7 November 2023. | [S67 abstract], [S68] | high | Refuted claims |
| F76 | Dstl forecast in 2020 that a quantum-annealer AI capability could reach initial operating capability "as soon as 2025"; no evidence that this happened was found. | [S102] | medium | Stale; absence of evidence, not proof |

## Sub-question 4: Technology → defence and government use cases

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F77 | UK National Quantum Strategy Mission 4 targets quantum navigation systems, including clocks, deployed on aircraft by 2030, independent of satellite signals. | [S40 Mission 4] | high | Target, not achievement |
| F78 | Mission 5 targets mobile, networked quantum sensors across critical infrastructure by 2030, naming defence ("find objects in challenging environments"), underground sensing for transport, RF sensors for telecoms and gas sensing for energy. | [S90 Mission 5] | high | |
| F79 | Mission 3 targets every NHS Trust benefiting from quantum sensing by 2030, with quantum brain scanners guiding paediatric surgery by 2028. | [S90 Mission 3] | high | Stretched given F37 (*Analysis*) |
| F80 | The 2025 Strategic Defence Review says quantum could reduce dependence on vulnerable satellite GPS and quantum computing could break encryption. | [S95 Box 2] | high | Thin on detail |
| F81 | A 24-hour UK-wide GNSS outage is estimated to cost £1,424m (2021 evidence base). | [S105] | high | SDR's "£1bn a day" rests on a 2018 source [S95 fn 88] |
| F82 | DSIT and NPL committed £180m (March 2026) to a National Timing Centre distributing atomic-clock time by fibre, satellite and radio as an alternative to GNSS for telecoms, banking, transport and emergency services. | [S106] | high | product/deployed technology, scaling |
| F83 | NATO's strategy names GNSS-independent PNT and space-based data collection as military uses of quantum sensors, and sets the goal of transition to quantum-safe cryptography. | [S14] | high | |
| F84 | NATO's Quantum Technology Roadmap (approved 30 July 2026) commits to a use-case repository, Quantum Assessment Criteria by Q2 2027 and QUESTOR sea trials of quantum PNT in 2026–27. | [S92] | high | |
| F85 | The European Commission says quantum sensing gives defence gravimetry, magnetometry and inertial navigation for detecting underground structures, tracking submarines and threat detection. | [S94 §2.4] | medium | Policy assertion, not evidenced in the text |
| F86 | The EU plans quantum inertial navigation prototypes on Galileo satellites and a ground network of quantum gravimeters (including defence and civil protection uses), with a space gravimetry pathfinder after 2030. | [S15 §2.2.3], [S94 §2.4] | high | Plans |
| F87 | The EDA-funded QuantaQuest project (Thales-led, about €1.5m, closed Dec 2023) produced a building block towards a quantum inertial measurement unit and an urban free-space QKD demonstration. | [S104] | high | lab / field demo |
| F88 | CRS (May 2026) says quantum technology "has not yet reached maturity for most applications"; the Defense Science Board rated sensing the most mature military application, "poised for mission use", for alternative PNT, detecting underground structures and nuclear materials, and electronic warfare. | [S93] | high | DSB date unverified |
| F89 | DIU's Transition of Quantum Sensing programme runs field tests in five lines (inertial, gravimetry, magnetic anomaly detection, magnetic navigation, components), with over ten tests planned in about 12 months from March 2025. | [S41] | high | No results published |
| F90 | DOD assessed quantum computers as at least ten years away in July 2025; DOD requested $593.7m for quantum in FY2026. | [S93] | high | |
| F91 | Singapore's MINDEF agencies partnered with IBM in July 2026 to evaluate quantum optimisation for mission planning and logistics, saying it "could eventually help". | [S89] | high | Evaluation only |
| F92 | Dstl (2020) listed logistics, scheduling, AI/ML and materials as candidate defence uses of quantum information processing, and classed the Fujitsu Digital Annealer as conventional-silicon competition. | [S87] | medium | Stale (2020) |
| F93 | CSIS argues the near-term payoff of quantum sensing is "better cueing, more resilient navigation, and more persistent wide-area search", not stealth-defeating radar. | [S99] | medium | |
| F94 | NASA JPL is building a space quantum gravity gradiometer pathfinder, described as the first attempt to fly one, for water, resources and national-security mapping. | [S109] | high | prototype |
| F95 | QKD is rejected for UK government and military use by NCSC, judged niche-only by French, German, Dutch and Swedish agencies, judged not deployable for DOD mission use by the DSB, left open "in the future" by NATO, and described as "ultra-secure" by the European Commission. | [S75], [S76], [S93], [S14], [S94 §2.4] | high | Contradiction is between policy positions, not facts |
| F96 | RUSI suggests 1,000–10,000-qubit machines could enable "meaningful cryptanalysis of specific classical encryption schemes" within about ten years. | [S100] | low | Author co-founded a company named in the report; conflicts with [S70], [S93] |

## Sub-question 5: Where PQC, sensing and quantum-inspired methods sit in the chain

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F97 | PQC runs on classical computers and rests on classical mathematics: module lattices (ML-KEM, ML-DSA), hashes (SLH-DSA) and error-correcting codes (HQC). | [S71], [S72] | high | |
| F98 | NIST finalised FIPS 203, 204 and 205 on 13 August 2024 and selected HQC as a backup on 11 March 2025, with its final standard expected in 2027. | [S71], [S72] | high | |
| F99 | NCSC's migration milestones are discovery and planning by 2028, priority migrations by 2031 and complete migration by 2035; it recommends ML-KEM-768 and ML-DSA-65. | [S73], [S74] | high | |
| F100 | NCSC states "PQC is the best mitigation to the threat to cryptography from quantum computing". | [S75] | high | |
| F101 | Quantum-inspired solvers are classical algorithms or hardware: simulated bifurcation (inspired by adiabatic quantum optimisation), the Digital Annealer (enhanced simulated annealing in CMOS), tensor networks (exploiting limited entanglement) and dequantised algorithms (sampling in place of superposition). | [S83], [S84], [S79], [S77] | high | |
| F102 | The user's prior scan frames quantum-inspired methods as "classical methods drawn from quantum ideas, usable now", and sensing as closest to the field "only for clocks and magnetic navigation". | [S01] | internal | Team framing, used for context only |

## Additional findings (added while writing the report)

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F103 | Q-CTRL's CEO is quoted saying aircraft magnetic noise is 100–1,000 times the anomaly signal used for MagNav. | [S47 "Delicate systems"] | low | CEO claim relayed by T2 press; the preprint [S34 abstract] attributes performance to magnetometers plus denoising and map-matching algorithms but gives no noise ratio. Researcher-over-relay: lead with S34 |
| F104 | NCSC says harvest-now-decrypt-later collection makes a future cryptographically relevant quantum computer a relevant threat now for long-lived, high-value data. | [S74] | high | SQ4 |
| F105 | The US Navy is a primary interested party for gravity-aided navigation, and ONR is maturing an atomic accelerometer for naval navigation under TQS. | [S41 Quantum Gravimeters] | high | SQ2; no trial results found |
| F106 | The EU supports a European quantum MRI (Q-MRI) pilot infrastructure from 2025 for clinical validation. | [S94 §2.2.3] | high | SQ1/SQ4; prototype |

### Quantum networking components (added in the second round)

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F107 | Single-photon detectors for visible and near-infrared light are commercially available; mid-infrared and terahertz detection "remains a significant challenge". | [S58 MCQST news quote] | medium | Band B component (networking and imaging) |
| F108 | The Micius satellite distributed entanglement over 1,203 km and served as a trusted relay for a Beijing–Vienna key; fibre loses on average every second photon in 10 km. | [S29 "Quantum repeaters"] | high | Field demonstration (China); QKD, so Band C |
| F109 | A 2017 EU community roadmap describes QKD and QRNG as commercially available. | [S12 Quantum Communication intro] | medium | Stale (2017). QKD products exist but security maturity and government rejection keep QKD in Band C [S75][S76] |
| F110 | Device-independent QKD was demonstrated by three groups in 2022 using loophole-free Bell tests, at lab scale. | [S29 Quantum cryptography] | high | Band C; key rates and distances not given |

## Quantum radar and radar-like detection (second gathering round; SQ2–SQ4)

Supporters are researchers who report or expect a quantum advantage; doubters are those who judge it impractical. Researcher statements are preferred over press framing of the same work.

| ID | Finding | Sources | Confidence | Notes |
|---|---|---|---|---|
| F111 | An IST Austria team illuminated a room-temperature object 1 m away with entangled microwaves; its receiver beat a symmetric classical noise radar but, by the authors' account, cannot outperform the best classical (coherent-state homodyne) radar. A 1 dB advantage over homodyne is simulated, assuming perfect photon counting. | [S111 abstract, Introduction] | high | Supporter. Lab, dilution refrigerator; press called it a "prototype" |
| F112 | An ENS Lyon team measured a quantum advantage of 1.2 ± 0.1 over the best possible classical radar using a joint measurement in a superconducting circuit; the authors say practical use is "a tremendous challenge". | [S112 p.3, conclusion] | high | Supporter. Lab only, inside a dilution refrigerator; theoretical maximum is 4 |
| F113 | Shapiro (MIT) concludes that the quantum-illumination advantage is real but "severely limited" in practice: idler storage loss limits range, and the advantage shrinks as transmitter power rises. | [S113 abstract, microwave section] | high | Corroborated by [S45 §VI]; one of the field's originators |
| F114 | A supporters' 2023 review sees grounds for "cautious optimism" but names two microwave hurdles: very low signal intensities and ultra-low temperatures; it suggests intense-jamming scenarios at optical frequencies as a niche. | [S114 Conclusions] | medium | Preprint; co-author led F111 |
| F115 | Radar engineers argue (2025) that because of very low transmitted power, quantum radar "cannot produce neither significant results nor real world applications", and that most of the scientific community ignored this. | [S115 abstract], [S103 abstract] | medium | Doubter. Abstract only; same lead authors in both |
| F116 | SIPRI (2025) calls RF quantum radar "largely impractical with current technology" and treats quantum detection of submarines from orbit as an overstated narrative; theory puts quantum-magnetometer SSBN detection at up to about 10 km. | [S123 Box 4.2] | medium | Think tank; SSBN figure is a cited theoretical estimate |
| F117 | UK MOD (Feb 2026): quantum radar and quantum illumination are "immature" and their defence benefit "uncertain"; MOD research focuses on clocks and on sensing for navigation and situational awareness, and works with the Birmingham-led QuSIT Hub on "Quantum enhanced RADAR". | [S116] | high | Government position (UK). Priorities classified |
| F118 | MOD contracted Aquark Technologies for "Quantum Optimised Radar Phase 1" (£295,000, Aug 2025 – Mar 2026). | [S117] | high | |
| F119 | Aquark reports a June 2026 trial in which two cold-atom clocks timed two networked Saab Giraffe 1X radars under simulated GNSS denial and spoofing, with the Royal Navy, QinetiQ and Dstl; no performance figures were published. Aquark itself distinguishes this from quantum-illumination radar. | [S118], [S117] | low | Vendor release; trial existence corroborated by the contract. The quantum element is timing, not detection |
| F120 | Birmingham's quantum-oscillator staring radar aims at small drones in clutter; its peer-reviewed results (2021) are a classical baseline before integrating the oscillator, and no integrated result was found. | [S120 abstract], [S119] | medium | Field installation; planned integration date (2022–23) passed without a public result |
| F121 | Canada's DND funded a $2.7m (currency not stated; Canadian programme) University of Waterloo project (2018) to build an on-demand entangled-photon source for quantum radar; the university release says quantum illumination "has only been explored in the laboratory". | [S121] | low | T3, stale; headline goes beyond the project goal; no later results found |
| F122 | China's CETC announced in 2016 that it tested a quantum radar to 100 km; no independent verification was found. | [S122] | low | Claim relayed by press; stale |
| F123 | A NIST-led FMCW radar using a Rydberg-atom receiver imaged targets at up to 5 m with 4.7 cm range resolution; the authors say a matched narrowband antenna is more sensitive. | [S124 abstract, body] | medium | Preprint; lab demo. Not entanglement-based |

## Contradictions & open questions

- **QKD.** Positions differ by organisation (F95). UK NCSC, the EU security
  agencies and the US DSB reject or limit it; the European Commission promotes
  it; NATO leaves room for it later. For a UK D&G whitepaper, weight NCSC
  [S75] as the national technical authority.
- **Code-breaking timelines.** RUSI's ~10 years at 1–10k qubits [S100]
  conflicts with Gidney's under one million noisy qubits [S70] and CRS's ~20
  million qubits figure [S93]. CRS's figure tracks Gidney's 2019 estimate and
  looks dated next to S70. Weight S70 (method published) over S100 (author
  conflict of interest).
- **Q-CTRL MagNav figure.** 46× in the preprint [S34] versus 94× quoted by the
  CEO [S47]. Use the preprint figure as a vendor claim.
- **UK aircraft target wording.** Euronews says "all commercial aircraft by
  2030" [S48]; gov.uk says "deployed on aircraft" [S40]. Use gov.uk.
- **GNSS outage cost.** SDR's £1bn a day (2018 source) [S95] versus £1,424m
  per 24 hours [S105], repeated by government in 2026 [S106]. Use S105.
- **Quantum radar: researchers versus press.** Both supporter experiments
  [S111][S112] state their own limits; press coverage called S111 a
  "prototype" and Waterloo's release says quantum radar "will expose stealth
  aircraft" [S121]. Weight the papers. CETC's 100 km claim [S122] has no
  research behind it in this evidence set.
- **Government positions on quantum radar.** The US DSB rejects it (F59), UK
  MOD calls it immature with uncertain benefit (F117), Canada funded
  research in 2018 (F121) and China claimed a field test in 2016 (F122). No
  French, German or NATO position was found.
- **Gaps.**
  - Flash memory as a tunnelling anchor is `[unsupported]`: no source logged.
  - SQUID defence uses (e.g. airborne magnetic anomaly detection),
    squeezed-light lidar for defence, Rydberg field results and gravity-map
    navigation results were not found in T1/T2 sources.
  - No published performance data exists for any UK quantum navigation trial.
  - No post-2020 Dstl source on quantum computing or quantum-inspired
    optimisation was found; S87 and S102 are stale.
  - Topological insulators, topological photonics, hBN emitters and quantum
    simulation for defence materials were not covered.
  - The DSB study quoted by CRS was not opened and its date is unverified.
  - Quantum radar: no performance data from the UK radar-timing trial
    (F119) or Birmingham's quantum-oscillator radar (F120). Royal Navy,
    NATO STO (Birmingham paper MP-SET-311) and media.defense.gov pages
    returned 403. No peer-reviewed Chinese quantum radar result was found.

## Analysis (agent interpretation, not sourced fact)

- **The phenomenon list splits cleanly into three bands.** Band A, deployed
  for decades: quantised energy levels, tunnelling, NMR, Josephson and
  quantum Hall effects, photoelectric effect, atomic transitions (F07–F15).
  Band B, field-trialled for defence or government now, or commercially
  available as components: atomic transitions in compact and optical clocks,
  matter-wave interference, spin precession in vapour cells (F26–F34), and
  the networking components QRNG, quantum-dot photon sources and
  single-photon detectors (F23, F48, F107). Band C, lab or theory with
  asserted applications: QKD and wider quantum networking (F21, F22, F95,
  F108, F110), entanglement-based quantum radar (F58, F111–F115), time
  crystals, superabsorption, polaritonic chemistry, moiré materials
  (F65–F75). Microsoft's Majorana and topological-qubit claims (F49, F64)
  are left out of the bands; see the hype-check bullet. PQC stays outside
  the bands because it rests on no quantum phenomenon (F97). This gives the
  whitepaper a ready shortlist rule: Band B is where the defence story sits
  today.
- **Today's defence sensors use the "old" quantum, not entanglement.** The
  sensors in trials rely on quantised levels and coherence (F16, F60).
  Entanglement-enhanced sensing exists only in lab demos (F41) and quantum
  radar (F58, F59). A whitepaper that leads with entanglement for sensing
  would overstate the evidence.
- **"Quantum radar" covers two different things, and the evidence splits
  with them.** Entanglement-based quantum illumination has a measured
  advantage of 1.2 over the best classical radar, in a dilution
  refrigerator, with supporters and doubters agreeing that practical use
  is hard (F111–F115). That is Band C. Radar that uses quantum *timing*
  (cold-atom clocks or quantum oscillators) or quantum *receivers* (Rydberg
  atoms) rests on Band B phenomena, and it is where government trials are
  happening: the UK's June 2026 radar-timing trial and the Birmingham
  drone-radar testbed (F119, F120, F123). Government positions follow the
  same line: the US and UK reject or doubt entanglement radar (F59, F117)
  while the UK funds quantum-timed radar (F118). Where the whitepaper puts
  quantum radar is the user's call; this split is offered as the basis.
- **The binding constraint in sensing is engineering, not physics.** Fragility
  (F56), platform noise (F57, F34 notes), lab-to-field performance gaps (F55,
  F35) and the drift limits of inertial systems (F27) all point to
  integration, ruggedisation and sensor fusion as the work. This matches the
  prior scan's view [S01].
- **PQC and quantum-inspired methods are both classical responses to the
  quantum chain, at opposite ends.** PQC defends against what superposition,
  entanglement and interference will eventually enable in a quantum computer
  (F42, F97). Quantum-inspired methods borrow the mathematics of tunnelling,
  adiabatic evolution and entanglement structure without the hardware (F50–F54,
  F101). The chain for the whitepaper is therefore "phenomenon → quantum
  technology → (threat or idea) → classical product", not "phenomenon →
  product".
- **Classical methods keep catching quantum claims.** Tensor networks
  reproduced IBM's utility result (F52), D-Wave's claim is challenged (F53)
  and dequantisation removed a headline speedup (F54). The Siemens study
  (F63) shows the practical near-term value is in the inspired hardware.
  Implication: defence optimisation pilots should benchmark against
  quantum-inspired and best classical solvers before any quantum hardware.
- **A hype-check pattern recurs.** The clearest case is Microsoft's Majorana
  work. Its Nature paper says the data "do not, by themselves, determine"
  whether the states are topological, while the qubit claim came by press
  release (F49). An independent UK critique calls the data "not reliable",
  the dispute ran to a Matters Arising in Nature in June 2026, and an earlier
  Microsoft-funded Majorana paper was retracted in 2021 (F64). For that
  reason this project keeps Majorana and topological-qubit claims out of the
  bands altogether. The same pattern shows elsewhere: press releases go
  beyond peer-reviewed content (F68, F111, F121), and headline results fail
  to replicate or are retracted (F74, F75). Defence use cases attached to Band C phenomena are mostly
  author-asserted. A simple test for the whitepaper: has anyone outside the
  originating group reproduced it, and has it left the lab?
- **Official timelines have slipped before.** Dstl's 2020 forecast (F76) and
  the UK 2030 targets (F77, F79), set against unapproved OPM-MEG (F37) and
  unpublished trial data (F29), suggest presenting the 2030 missions as
  targets, not forecasts.

---

## Verification log
### Verification: 2026-10-10
- Claims checked: every cited sentence in `outputs/brief.md` (34 sources) and `outputs/report.md` (87 sources) traced to a finding (F01–F106) and a logged source. All cited IDs exist in `sources.md`. Spot-checked against originals by re-opening the source: 10 (S37 clock trial figures; S75 NCSC QKD quote; S93 CRS quotes and $593.7m; S106 £180m; S57 "are limited"; S71 13 Aug 2024; S42 "notoriously fragile"; S31 SNR 8; S45 15–20 orders of magnitude; S16 caesium wording). All matched.
- Issues found / fixed:
  - Report claims not yet in findings (MagNav platform noise, harvest-now-decrypt-later, ONR atomic accelerometer, EU Q-MRI pilot) added as F103–F106 before citing.
  - MagNav noise figure reworded as a Q-CTRL CEO claim (T3 relayed by T2).
  - Several findings re-pointed to the duplicate entry that holds the cited detail (S90 Mission 3 and 5; S94 §2.4).
  - Brief wording on quantum radar corrected to "shows an advantage only at" to match S45.
  - S16 "caesium microwave transition" quote verified and added to source notes; report now cites it.
  - Vague attributions ("popular accounts", "vendor narratives") removed; bold-label bullets removed outside key findings.
- Remaining caveats:
  - Several sensing and frontier sources are preprints or vendor-authored (S34, S35, S44, S54, S58, S60, S70, S110); findings that rely on them are rated medium or low.
  - Stale sources used only for definitions or as cautionary examples: S10, S12, S16, S28, S61, S62, S64, S69, S87, S101, S102.
  - The Defense Science Board judgments are quoted via CRS (S93); the DSB study itself and its date were not checked.
  - Royal Navy, GAO and NSA pages were blocked; related claims rest on other sources.
  - Flash memory left `[unsupported]`.
- Result: PASS WITH CAVEATS

### Verification: 2026-10-10 (second round: bands, Majorana, radar)
- Claims checked: every new or changed sentence in `outputs/brief.md`, `outputs/report.md` and `outputs/reading-pack-sensing.md` traced to F107–F123 or existing findings, and to logged sources. All cited IDs exist in `sources.md`; both source tables list every ID cited in the body (brief 40, report 99). Spot-checked against originals re-opened this session: 8 (S111 "never be outperformed"; S112 Q = 1.2(1) and "a tremendous challenge"; S113 "severely limited"; S114 "cautious optimism"; S116 MOD answer wording; S117 £295,000 and dates; S121 "has only been explored in the laboratory"; S124 5 m and 4.7 cm). All matched.
- Issues found / fixed:
  - Waterloo funding figure had no stated currency; finding now says so.
  - Q-CTRL figures re-checked under the new researcher-over-relay rule: outputs use the preprint's 46×, and the CEO's noise ratio stays framed as a quote.
  - Curly quotation marks restored in four verbatim quotes.
  - Tells scan and em-dash scan on all three outputs found nothing.
- Remaining caveats:
  - Aquark's radar-timing trial (S118) is vendor-reported with no figures; only the contract (S117) is independent.
  - S115 and S120 are abstract-only; S113 and S114 are arXiv versions.
  - CETC (S122) and Waterloo (S121) are stale (2016, 2018) and used only to show claims ahead of evidence.
  - royalnavy.mod.uk, media.defense.gov, sto.nato.int and cnbc.com returned 403.
  - Band placement of quantum radar is left open for the user.
- Result: PASS WITH CAVEATS
