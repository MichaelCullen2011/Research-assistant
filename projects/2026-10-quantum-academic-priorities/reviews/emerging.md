# Emerging quantum phenomena: six full-paper reviews

Reviewed2026-10-12. Six core studies; two contextual challenge/correction sources. This is a targeted scan, not a systematic review. Preprint access versions are explicitly separated from journal metadata. No experimental replication performed.

## S70 — Field Demonstration of Distributed Quantum Sensing without Post-Selection

2021-07-14; DOI 10.1103/PhysRevX.11.031009; T1 journal; T2 accessed preprint. Access: full text with version caveat. [S70]

Entangled photons and coherent repeated phase sampling estimate a weighted combination of two separated phases without hiding lost photons through postselection. Telecom polarization-entangled pairs are delivered to two sensors; Bob samples his phase twice. Single and multiple detector events, heralding efficiencies and higher-order pair emissions enter photon-pass resource accounting. The SNL reference is an ideal lossless local estimation strategy with optimally allocated independent photon passes. [S70, Methods/main results]

At240m fiber separation the reported best phase precision is0.916dB below the photon-pass SNL; average heralding efficiency73.88%. The10km extension measures unknown random phases but does not beat SNL because losses push performance below the efficiency requirement. [S70, preprint pp.3–4, Fig.2]

**Critical assessment.** The measured parameters are waveplate-imposed phases, not physical target fields. The10km experiment uses fiber spools; do not equate it with10km geographical deployment. Calibration and polarization stability, very efficient superconducting detectors and a narrow advantage window matter. Photon-pass SNL comparison does not establish superiority over every classical strategy with comparable preparation, multipass interaction time, cryogenics or bandwidth. [S70, Results/Discussion/Methods]

Experimental apparatus, estimators and efficiency/resource derivation are documented in main text and appendicesA–C; no independent replication established in this bounded search. Raw public dataset/code not identified in examined preprint. Not located in examined preprint; journal declaration not independently retrieved. [S70, access record and availability/declarations]

Analysis: credible loss-aware network metrology mechanism for research on distributed sensing; no demonstrated defence sensing application. High confidence in scoped240m result; limited network scalability and operational relevance. [S70]

## S71 — Distributed quantum sensing with mode-entangled spin-squeezed atomic states

2022-11-23; DOI 10.1038/s41586-022-05363-z; T1 journal; T2 accessed preprint. Access: full text with version caveat. [S71]

A shared quantum nondemolition measurement creates nonlocal entanglement between atomic modes, enabling differential clock and interferometer protocols. Rubidium ensembles in a common cavity are divided into as many as four spatial modes; a shared QND observation prepares correlated populations. Microwave Ramsey operations and Raman-pulse differential interferometry test the prepared modes. Each clock mode contains45000atoms. Baselines include projection-noise-limited coherent states and a projected mode-separable spin-squeezed network. [S71, Methods/main results]

Four-mode clock-network noise is11.6(1.1)dB below coherent-state QPN and4.5(0.8)dB below the projected mode-separable reference. The differential interferometer improves1.6(0.9)dB relative to its non-entangled counterpart; do not assign the clock-network gain to the interferometer. [S71, arxivv1 main text, four-mode network paragraph and Fig.3]

**Critical assessment.** All nodes share laboratory cavity infrastructure; the atom modes are not a geographically separated clock network. The4.5dB reference is projected, not a separately field-operated competitor. Gains exploit improved squeezing efficiency as the total atom count entangled increases. Differential rejection of Raman common-mode phase noise is also present and must be separated from entanglement benefit. No broad optimized-classical end-to-end network comparison is demonstrated. [S71, Results/Discussion/Methods]

Full arxivv1 main text and Methods inspected; peer-reviewed title/date/DOI cross-checked on Nature landing page. Journal main text is paywalled; preprint-versus-final changes remain a version caveat. Journal data and analysis code are available from corresponding author upon reasonable request, not an open repository. Journal declaration: no competing interests. [S71, access record and availability/declarations]

Analysis: a promising seam for differential gravity sensing and clock comparisons, requiring remote-node links and realistic interrogation cycles before defence interpretation becomes an observed application. High confidence in laboratory metrology; medium confidence in extrapolation beyond common apparatus. [S71]

## S72 — Entanglement-enhanced matter-wave interferometry in a high-finesse cavity

2022-10-19; DOI 10.1038/s41586-022-05197-9; T1. Access: full text and methods; supplement where provided. [S72]

Cavity-mediated entanglement is injected into a complete light-pulse matter-wave interferometer rather than demonstrated only as state preparation. Free-falling rubidium wave packets receive Raman momentum kicks in a high-finesse cavity. QND measurement and one-axis twisting prepare squeezed momentum states. The full Mach–Zehnder sequence uses OAT; phase noise and contrast define the Wineland parameter, with atom number and spatially varying coupling calibrated separately. [S72, Methods/main results]

For660(15)atoms the full interferometer has1.7±0.5dB enhancement beyond the calibrated SQL at evolution time0.112ms. Phase variance improves3.4(+0.9/−1.2)dB against the actual unsqueezed interferometer, which itself has imperfect contrast. Below-SQL sensitivity lasts less than0.7ms. Standalone squeezed-state gains are distinct. [S72, journal Fig.4b and Entangled matter-wave interferometry]

**Critical assessment.** Short interrogation time and residual spin-related decoherence sharply limit practical inertial advantage. An independent unreviewed critique by McGuinness(arxiv2301.04396v2) disputes phase/SQL interpretation and resource accounting; its blanket denial is not established by citing it. Authors explicitly distinguish contrast-adjusted entanglement witness from larger ordinary noise cancellation. Independent calibrated acceleration-versus-phase and full-cycle comparisons would be more useful than accepting either universal claim. [S72, Results/Discussion/Methods; S76 pp.1–5]

Full corrected journal text and Methods read; public datasets at doi10.25810/t39m-c562 declared. Publisher correction(2022-12-06) restores omitted hbar labels and removes an incorrect peer-review-manuscript link, not a reported numerical-result retraction. Independent experimental replication not established. Authors declare no competing interests; NSF,DOE,NIST,DARPA funding listed. [S72, access record and availability/declarations; S77 correction notice]

Analysis: directly relevant enabling physics for future inertial/gravity sensing; not a demonstrated navigation instrument or GNSS-denial test. High confidence in reported local calibrated laboratory variance/contrast; practical inertial superiority remains untested and critique warrants explicit parameter definition. [S72]

## S73 — Quantum locking of intrinsic spin squeezed state in Earth-field-range magnetometry

2025-03-03; DOI 10.1038/s41534-025-00971-9; T1. Access: full text and methods; supplement where provided. [S73]

Nonlinear Zeeman dynamics create intrinsic single-atom squeezing; optimized dynamical decoupling locks its changing axis to the observable instead of simply suppressing that dynamics. Breit–Rabi expansion yields a quadratic spin Hamiltonian. A differential-evolution algorithm chooses discretized RF rotation pulses. Numerical state fidelity and signal/noise propagation assess dark-interval and continuous-readout protocols; supplementary notes derive SQL and the nuclear-electron entanglement mechanism. [S73, Methods/main results]

Modelled87Rb maximum metrological gain approaches2.9dB. Under assumed1cm³ room-temperature cell,N=1.42e10 and10ms coherence, Discussion calculates4.29fT/sqrt(Hz) versus5.99fT/sqrt(Hz) CSS SQL and14.04fT/sqrt(Hz) NLZ-degraded reference. These are predictions, not recorded instrument sensitivity. [S73, Results Fig.1b, Eq.5]

**Critical assessment.** Explicitly no atom–atom entanglement is needed; gain is single-atom nuclear-electron correlation and independent ofN. The largest apparent improvement also restores assumed coherence, not squeezing alone. Instantaneous-rotation and rotating-wave approximations constrain pulse duration. Readout backaction, gradients and measurement-duty trade-offs are discussed but no complete measured noise budget or moving-platform demonstration is supplied. [S73, Results/Discussion/Methods]

Main Results,Methods,Discussion and supplementary notes1–3,8 inspected. Equations and optimized pulse sequence are given; authors say evaluation data are within paper/supplement and additional data on request. No code repository identified; no experimental replication established because this is a proposed protocol. Authors declare no competing interests. [S73, access record and availability/declarations]

Analysis: a relevant control proposal for Earth-field sensing and potential magnetic navigation research; claimed operational sensitivity must await an experiment. High confidence in classification as numerical proposal; medium confidence in achievable hardware gain. [S73]

## S74 — Superabsorption in an organic microcavity: Toward a quantum battery

2022-01-14; DOI 10.1126/sciadv.abk3160; T1 journal; T2 accessed preprint. Access: full text with version caveat. [S74]

Organic-molecule collective light–matter coupling produces faster absorption as absorber count increases; dephasing moves energy into less radiative dark modes. Lumogen-F Orange dye in polystyrene is placed between dielectric mirrors. Concentrations0.5%,1%,5%,10% span weak to strong coupling. Femtosecond pump–probe differential reflectivity is fit to an open-system model; peak population-derived energy density, rise time and charging power are extracted from model fits, with supporting spectroscopy and fit sensitivity in supplement. [S74, Methods/main results]

Spectroscopy supports superextensive charging and storage-capacity behaviour over tested regimes; scaling varies with coupling/decay regime. Only6–8% of initial pump energy enters the cavity according to reflectivity estimates. The observed energy is molecular excitation, not delivered electrical energy. [S74, arxiv main pp.6–11,Figs.2–3,Table1]

**Critical assessment.** This precursor has no demonstrated electrical extraction, useful discharge cycle or net wall-plug efficiency. Increased concentration and coupling regimes change together; fitted collective dynamics should not be reported as proof that entanglement uniquely causes practical energy advantage. Finite experimental concentration range, molecular quenching at larger concentration and dephasing/decay assumptions limit extrapolation. A fixed-resource comparison requires incident/absorbed energy,mode volume,loss and preparation accounting. [S74, Results/Discussion/Methods]

Full accessible arxiv PDF main text plus supplement examined; DOI/journal identity verified through opened publisher DOI and author university research portal. Version is latest downloadable arxiv manuscript, not an independently diffed journal PDF. Detailed fabrication,spectroscopy and fitting documented; independent replication/open code repository not established in this bounded review. Declaration not verified from examined version; treat unknown, not no conflict. [S74, access record and availability/declarations]

Analysis: UK/European foundational energy-capture physics useful to evaluate the2026 extraction study; defence battery procurement relevance remains remote. High confidence in spectroscopic collective enhancement; no demonstrated usable battery output. [S74]

## S75 — Superextensive electrical power from a quantum battery

2026-03-13; DOI 10.1038/s41377-026-02240-6; T1. Access: full text and methods; supplement where provided. [S75]

Charge-transport layers turn an organic polariton microcavity into a steady-state electrical-output device, addressing the missing extraction step in earlier spectroscopy-only battery demonstrations. Eight CuPc:C60 devices vary absorber count within a nominal126nm cavity. Cavity and no-cavity controls share substrates. Reflectance establishes strong coupling; ultrafast pump–probe data quantify excitation dynamics; current–voltage scans under625nm illumination measure electrical output. Intersystem crossing populates metastable triplet states; coupled-oscillator and open-system models connect these stages. [S75, Methods/main results]

Maximum electrical power density is roughly10–40microW/cm². The ratio of cavity/no-cavity peak power increases withN; authors interpret this as superextensive output, with modelPc~N². Optical excited-state signals persist tens of nanoseconds; the six-orders-of-magnitude ratio compares to charging times, not hours or years of storage. [S75, Results electrical discharge paragraph,Fig.4c; supplementIV.A]

**Critical assessment.** Always-illuminated steady-state photocurrent does not by itself demonstrate sustained useful dark discharge. Controls omit a metal mirror and therefore differ optically as well as in coupling; comparisons to an independently optimized photovoltaic architecture and equal absorbed/incident energy are needed for practical superiority. Concentration alters carrier dynamics,cavity detuning andQ; authors normalize with same-run controls and discussD8 deviation. No entanglement witness isolates uniquely quantum causal advantage. No complete round-trip/net external efficiency,macroscopic capacity or cycling durability demonstrated. [S75, Results/Discussion/Methods]

Full journal text,Methods and32-page supplement inspected, emphasizing geometry/controls,ultrafast normalization and electrical model. Data available on request; no public code repository identified. Independent replication not established. Authors declare no competing interests. [S75, access record and availability/declarations]

Analysis: worthwhile frontier test in low-light harvesting rather than evidence for near-term defence energy storage. Require dark-discharge energy,integrated photon-to-electric efficiency and optimized equal-resource classical controls. High confidence in measured electrical output; medium confidence in causal scaling interpretation; low deployment maturity. [S75]

## Coverage and decisive caveats

The eligible2016Hosten anchor was screened but not promoted from abstract-only access. All six selected studies have full primary manuscript access; S70,S71,S74 rely on accessible preprint versions rather than independently diffed journal texts. Claims about unique battery entanglement advantage or deployed military performance are not established by these studies. [S70–S75]

S76 is an unreviewed challenge to S72; S77 is a publisher correction. Neither should be conflated with an experimental replication or scientific retraction. [S76; S77]

Skipped: paid-access chasing, experimental replication and battery procurement claims. Risk: narrow SQL/control comparisons cannot establish full-system operational advantage.
