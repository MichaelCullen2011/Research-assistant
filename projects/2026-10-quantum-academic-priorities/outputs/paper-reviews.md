# Paper reviews: quantum priorities

Twenty-four core papers, grouped by the four priorities. Results cite exact locators; interpretation is labelled. Publication dates and first-preprint dates are separate in the source log. Detailed claims based on unmatched preprint manuscripts retain T2 access status. Eleven studies received Astra challenges. [S01]

Use [report](report.md) for synthesis, [sources](../sources.md) for complete metadata and availability, and [reconciliation](../reviews/reconciliation.md) for challenged claims.

## Navigation and timing

### S10: Optical clocks at sea

Roslund, Jonathan D. et al. · 2024-04-24 · T1 evidence access. [Original](https://www.nature.com/articles/s41586-024-07225-2). [S10]

*Reviewed version:* Journal HTML, version of record. Access: full-text HTML. First preprint: 2023-08-23. [S10]

**Contribution and method.** Integrated iodine-vapour optical clock and microwave frequency-comb output; field timing experiment [S10 Main; Methods]. Three clock comparison at NIST against ST05/AT1, then co-located shipboard pairwise comparisons; three-cornered-hat extraction at short times, long-time equal-contribution upper bound [S10 Figs.1–3; Methods Clock comparison]. [S10 reviewed main methods/results]

**Located results:**

- 35 L clock package excludes external power supply; ~85 W and 26 kg. [S10 Main prototype integration paragraph; Fig.1a]
- At sea PICKLES–EPIC pair instability is 8×10^-15 at 100,000 s, reported equivalent holdover ~400 ps/24 h without drift correction. [S10 Main ship performance paragraph; Fig.3d]
- Long-time single-clock upper bound divides pair performance by sqrt(2), assuming equal contributions. [S10 Main summary performance paragraph; Fig.1c,d]
- No independent standard reference was available at sea; correlated environmental sensitivities are acknowledged. [S10 Main co-located clocks paragraph]

**Critical reading.** Air-conditioned shipping container; no independent high-performance reference at sea; potential correlated environmental noise acknowledged. Individual long-time bound assumes equal contributions. VIPER external supply restarted; raw versus dedrifted laboratory results differ [S10 Main; Methods; Extended Data Fig.4]. [S10 reviewed methods/discussion]

*Independent challenge, scope restriction.* Preserves pairwise stability; individual absolute holdover is inferred and assumption-dependent. [S10 Main following Fig.3; Supplement Potential Correlations in At-Sea Data]

*Independent challenge, scope restriction.* Qualifies uptime and platform burden; does not undermine clock stability. [S10 Main RIMPAC deployment; Methods RIMPAC test setup; Fig.3a]

**Access and reproducibility.** Raw/processed data on request; analysis routines on reasonable request, not a public archive [S10 Data availability; Code availability]. Authors declare no competing interests, but author affiliations include Vector Atomic; commercial participation must remain visible [S10 Author information; Competing interests]. [S10 availability, declarations and reviewed end matter]

*Analysis.* Analysis: credible local timing holdover evidence; no GNSS-free position solution or deployable network is measured [S10 Figs.1–3]. [S10]

### S11: Demonstration of a mobile optical clock ensemble at sea

Hilton, A. P. et al. · 2025-07-02 · T1 evidence access. [Original](https://www.nature.com/articles/s41467-025-61140-2). [S11]

*Reviewed version:* Journal HTML, version of record. Access: full-text HTML. First preprint: 2024-06-06. [S11]

**Contribution and method.** Field comparison of three distinct vapour optical architectures (Yb, two-colour Rb, single-colour Rb) [S11 Results Portable optical clocks]. Optical/RF/microwave beats; 5071A counter timebase; three-cornered-hat Modified Allan deviations. Comparison separates reference/counter artefacts from optical instability [S11 Figs.2,4–6; Methods Clock comparisons and analysis]. [S11 reviewed main methods/results]

**Located results:**

- Yb stability is in the 10^-14 domain from 100 ms to 80 ks. [S11 Results Individual clock stabilities; Fig.6]
- Underway short-time clock performance resembles shore performance, but times above 100 s show decreased stability. [S11 Results Individual clock stabilities; Figs.5–6]
- ORAFS deployed ancillary system totals 310 kg and 1300 W. [S11 Methods Optical rubidium atomic frequency standard (ORAFS); Table1]
- Power interruption required personnel to restart ORAFS; UofA systems recovered automatically. [S11 Results Clock frequency measurements; Fig.3]

**Critical reading.** Total ORAFS deployed support apparatus: 46 rack units, 310 kg, 1300 W; internal 112 L/30 kg/300 W is not complete installed system. Power interruption required manual ORAFS restart; UofA clocks restarted autonomously. Rb relocks/configuration changes produce frequency steps [S11 Fig.3; Methods Optical rubidium atomic frequency standard]. [S11 reviewed methods/discussion]

**Access and reproducibility.** Data restricted by military exercise: requests require author and sponsor approval. Processing code on reasonable request [S11 Data availability; Code availability]. Andre Luiten co-founder, owner and managing director of QuantX; company has commercial IP rights to UofA clocks. Others declare none [S11 Competing interests]. [S11 availability, declarations and reviewed end matter]

*Analysis.* Analysis: valuable comparison with practical failure/restart behaviour; read superiority as stability and application-specific SWaP, not blanket accuracy [S11 Figs.3,6,7; Table1]. [S11]

### S12: Atom interferometry at arbitrary orientations and rotation rates

d’Armagnac de Castanet, Quentin et al. · 2024-07-30 · T1 evidence access. [Original](https://www.nature.com/articles/s41467-024-50804-0). [S12]

*Reviewed version:* Journal HTML, version of record; preprint v1 also inspected. Access: full-text HTML. First preprint: 2024-02-29. [S12]

**Contribution and method.** Combines atomic/classical sensing and actively steered mirror to retain interferometer contrast during rotations [S12 Results; Fig.3]. 87Rb Raman Mach–Zehnder, classical mirror accelerometer and two FOGs, manually rotated platform. Acceleration phase is servo-cancelled; rotational phase reconstructed with inertial model [S12 Results; Methods Closed-loop mode]. [S12 reviewed main methods/results]

**Located results:**

- Reconstructed fringe SNR 5.3 corresponds to 24 micro-g per shot at 20 ms interrogation. [S12 Results Rotation compensation; Fig.3]
- Experiment reaches tilts 0–30 degrees and rotation rates up to 14 degrees/s on a manual rotation platform. [S12 Results setup; Fig.3]
- Mirror-rate reconstruction uses fitted correction epsilon=-0.013. [S12 Results Rotation compensation; Methods Correction of phase shift]
- Vibration compensation assumes constant accelerometer response and global 610-microsecond delay. [S12 Methods Limits of fringe reconstruction due to strong vibrations]

**Critical reading.** One measurement axis and manual platform; 1.3% fitted mirror-rate correction; vibration compensation uses assumed flat accelerometer response and 610 microsecond delay. Uncharacterized classical sensor response and platform resonances degrade SNR. Full triad/long-term stability remains future work [S12 Methods; Discussion]. [S12 reviewed methods/discussion]

**Access and reproducibility.** Raw data deposited at Zenodo 11543715; analysis code release not stated in journal Data availability [S12 Data availability]. Four authors employed by Exail, which commercializes atom-interferometric gravimeters; other authors declare none [S12 Competing interests]. [S12 availability, declarations and reviewed end matter]

*Analysis.* Analysis: enabling motion-compensation result, not field navigation accuracy or classical-free autonomy [S12 Results; Discussion]. [S12]

### S13: Quantum-assured magnetic navigation achieves positioning accuracy better than a strategic-grade INS in airborne and ground-based field trials

Murat Muradoglu et al. · 2025-04-10 · T2 evidence access. [Original](https://arxiv.org/html/2504.08167v1). [S13]

*Reviewed version:* arXiv 2504.08167v1 HTML; no journal reference on inspected landing page. Access: full-text HTML. First preprint: 2025-04-10. [S13]

**Contribution and method.** Field magnetic-map navigation with internally mounted rubidium scalar magnetometer, vector fluxgate, INS and adaptive compensation [S13 System architecture; Field trials]. Griffith Cessna flights February 2025 (>6700 km recorded) and van trials November 2024; causal iterative filter described, online warm/cold platform learning; public Australian TMI maps, INS aided by scalar airspeed or 3D velocity [S13 Q-CTRL magnetic denoising; Field trials; Table1]. [S13 reviewed main methods/results]

**Located results:**

- 22 m endpoint uses onboard sensor with 3D-velocity aid over 365 km. [S13 Table1 row(a), 3D velocity]
- 46× endpoint improvement uses outboard sensor with 3D velocity; endpoint112 m. [S13 Table1 row(a)dagger; Fig.4a]
- Onboard scalar-airspeed example ends at515 m over365 km; high-altitude onboard example ends at2 km over300 km. [S13 Table1 rows(a) airspeed and(b) onboard]
- Algorithms and scalar sensor are proprietary; public text gives no same-input classical scalar-sensor ablation. [S13 Q-CTRL MagNav System; Demonstration of MagNav; full v1 inspected]

**Critical reading.** No same-map algorithm comparison or classical scalar magnetometer ablation. 3D velocity provenance not specified sufficiently for strict GNSS-free best-case interpretation. Algorithms proprietary; altitude extension, military dynamics, ocean coverage remain unresolved [S13 Fig.1 caption; System architecture; Table1; Discussion]. [S13 reviewed methods/discussion]

*Independent challenge, scope restriction.* Cannot assign best numbers to GNSS-free velocity aiding. This is missing provenance, not proof that GNSS leaked. Scalar-airspeed endpoints 515/566 m remain. [S13 Table1; Fig.1 caption; Demonstration of MagNav; Fig.4]

*Independent challenge, missing evidence.* System-level advantage survives; quantum-specific advantage and independent reproducibility unestablished. [S13 Q-CTRL magnetic denoising and map-matching algorithms; Discussion optimal sensor architecture]

**Access and reproducibility.** No explicit data/code availability statement found in inspected full v1; proprietary magnetometer and software descriptions prevent reconstruction from text alone [S13 Q-CTRL MagNav System; end matter inspected]. All authors affiliated Q-CTRL; proprietary/commercial full-stack system. No separate conflicts declaration found in inspected v1 [S13 author list; Q-CTRL MagNav System]. [S13 availability, declarations and reviewed end matter]

*Analysis.* Analysis: credible internally mounted field aid, but advantage is over specified INS, not GPS and not isolated quantum-sensor advantage [S13 Table1; Demonstration of MagNav]. [S13]

### S14: GNSS-free quantum gravity-aided navigation and fine-scale marine surveying with a strapdown quantum gravimeter

Patrick J. Everitt et al. · 2026-08-26 · T2 evidence access. [Original](https://arxiv.org/html/2608.25563v1). [S14]

*Reviewed version:* arXiv 2608.25563v1 HTML; no journal reference on inspected landing page. Access: full-text HTML. First preprint: 2026-08-26. [S14]

**Contribution and method.** Maritime quantum-gravity map aiding with explicit exclusion of GNSS from processing; separate gravity-survey branch [S14 Results Quantum navigation; Methods Gravity-aided navigation]. 87Rb Mach–Zehnder plus mirror accelerometer bias stabilization; recorded raw Boreas D90 IMU independently mechanized; error-state filter combines gravity map and position/velocity/attitude/bias estimates over 83 km southbound route [S14 Fig.6; Methods Quantum–classical hybridization; Gravity-aided navigation]. [S14 reviewed main methods/results]

**Located results:**

- 83 km evaluated route ends at2.2 nmi (~4.1km), compared with14 nmi (~26km) unaided. [S14 Results Quantum navigation with gravity map matching; Fig.2]
- Methods explicitly exclude embedded Boreas GNSS-derived position/velocity/attitude from navigation mechanization. [S14 Methods Gravity-aided navigation]
- Separate surveying branch uses GNSS-disciplined PVA for rotation, Eotvos correction and georeferencing. [S14 Methods Gravity signal for surveying and anomaly detection; Fig.8]
- Coastal strapdown traversals typically experienced Sea State1 versus gimbaled Sea States2–3. [S14 Methods Maritime and land traversal details]
- The full-text abstract invokes nautical-mile DRMS, but Fig.2 explicitly says the one-mile band is not reported DRMS; Results endpoint is2.2nmi while Discussion describes an approximately one-mile bound. [S14 Abstract; Fig.2 caption; Results Quantum navigation; Discussion]

**Critical reading.** Initial state only described as same for both branches; provenance/uncertainty not specified. Fully closed long-duration campaign future work; onboard real-time execution not established. Coastal strapdown typically Sea State1 versus gimbaled2–3, so not matched-motion equality. 30 L sensor head excludes electronics rack [S14 Results; Methods Maritime traversals; Quantum sensor head; Discussion]. Internal wording inconsistency: abstract invokes nautical-mile DRMS, Fig.2 says shaded one-mile band is not DRMS, Discussion suggests ~one-mile bound, while Results/Methods report 2.2-nmi endpoint. Do not infer a universal one-mile bound or computed DRMS [S14 Abstract; Fig.2 caption; Results Quantum navigation; Discussion]. [S14 reviewed methods/discussion]

*Independent challenge, central-result flaw.* Internal reporting inconsistency invalidates specific full-route1nmi/DRMS characterization, not demonstrated error reduction. [S14 Abstract; Fig.2 caption; Results Quantum navigation; Discussion second paragraph]

*Independent challenge, scope restriction.* Preserves bias-stabilization evidence but not70x mobile navigation improvement or0.16mGal spatial accuracy; authors acknowledge superior classical survey benchmarks. [S14 Fig.7; Methods hybridization; Results Strapdown; Discussion classical benchmarks]

**Access and reproducibility.** No explicit data/code release statement found in v1 full text/end matter. Filter is described structurally, without sufficient full tuning/implementation for reproduction [S14 Methods; Acknowledgments/end matter inspected]. Q-CTRL-funded/developed commercial participation; Royal Navy/DASA support acknowledged. No separate conflict statement found in inspected v1 [S14 author affiliations; Acknowledgments]. [S14 availability, declarations and reviewed end matter]

*Analysis.* Analysis: recent provisional evidence of complete processing-chain GNSS exclusion, not centimetric navigation, multiday endurance or survey performance in denial [S14 Fig.2; Methods; Discussion]. [S14]

### S15: Integration of a high-fidelity model of quantum sensors with a map-matching filter for quantum-enhanced navigation

Samuel Lellouch et al. · 2025-08-06 · T2 evidence access. [Original](https://arxiv.org/html/2504.11119v2). [S15]

*Reviewed version:* arXiv 2504.11119v2 (8 August 2025); published QST 10 045007; journal metadata via Crossref. Access: full-text HTML. First preprint: 2025-04-15. [S15]

**Contribution and method.** Microscopic sensor simulation linked to navigation filter; important adverse result: non-Gaussian motion errors can make nominal sensitivity improvements unusable [S15 §§II–V]. Monte-Carlo atomic cloud/internal–external trajectory/pulse model; maritime/aircraft trajectories, moderate/enhanced/mitigated sensor capabilities, particle map-matching filter and classical INS model [S15 §II.2; §III; §IV; App.C]. [S15 reviewed main methods/results]

**Located results:**

- Moderate/enhanced Sea State2 simulated measurements could not be tuned to useful stable aiding. [S15 §IV; Fig.7]
- Successful high-dynamic flight aiding assumes100-fold reduced roll/pitch. [S15 §IV; Fig.8]
- 3.3-degree static tilt requirement follows a specified10 E error budget, not universal accuracy tolerance. [S15 AppendixB.1 Static tilts]
- Runs start with30 s transfer alignment and assumed100 m north/east initialization errors. [S15 §IV Integration with a map-matching navigation filter]

**Critical reading.** Simulation, not field navigation. All runs have 30 s transfer alignment, 100 m north/east initial errors; particle weighting tuned to observed sensor noise and maritime sea-state segments. Mitigation assumed, not experimentally delivered [S15 §IV; App.C; §V]. [S15 reviewed methods/discussion]

**Access and reproducibility.** All supporting data/code available on reasonable request to corresponding author; no archive link in statement [S15 Data availability statement]. Authors declare no competing interests [S15 Competing Interests]. [S15 availability, declarations and reviewed end matter]

*Analysis.* Analysis: strengthens assessment by specifying where optimistic navigation simulations fail; 3.3-degree bound is conditional, not a universal navigation tolerance [S15 App.B; §IV]. Confidence medium in reported conditional simulation result, medium in physical-model fidelity outside validated conditions; not an experiment. Detailed source confidence retains the reviewed-manuscript version caveat. [S15]

## Detection and situational awareness

### S30: Quantum sensing for gravity cartography

Ben Stray et al. · 2022-02-23 · T1 (peer-reviewed study; version examined specified) evidence access. [Original](https://www.nature.com/articles/s41586-021-04315-3). [S30]

*Reviewed version:* Nature version of record incl. Methods/Extended Data; first preprint date verified from Research Square manuscript cover p.2, DOI 10.21203/rs.3.rs-882491/v1. Access: full-text PDF. First preprint: 2021-09-14. [S30]

**Contribution and method.** Stray and colleagues demonstrate an outdoor gravity-gradient survey rather than an entanglement-enhanced detector. Two vertically separated rubidium interferometers reject common vibration; a displaced test mass gives 205 ± 13.1 E against a 202 E prediction. Outdoor sensitivity is 466 ± 8 E/√Hz, reaching 20 E statistical uncertainty in ten minutes. [S30 p.591, Figs.1c–2]

The survey crosses a known tunnel with a 2 m × 2 m internal section on an 8.5 m line sampled every 0.5 m. Plans, ground-penetrating radar and topography inform the site model. [S30 pp.591–592]

Thus this is a substantial field result, but not a blind search for an unknown tunnel. *Analysis*: the distinction matters when translating an anomaly-detection experiment into an intelligence-surveillance claim. The reported SNR of approximately eight divides the estimated 150 E signal by the mean survey error of 17.9 E. Base-station measurements remove drift; ellipse fits failing a specified quality threshold are discarded, leaving 98.4% usable data. [S30 Methods, PDF p.7]

Bayesian inversion estimates the horizontal centre at 0.19 ± 0.19 m and surface-to-centre depth at 1.89 m with asymmetric −0.59/+2.3 m uncertainty. [S30 Methods, PDF p.8]

The density prior is explicitly informative, whereas the horizontal-centre prior spans the measurement line; the tunnel dimensions are not simply fixed in this inversion. [S30 Extended Data Table 2]

*Analysis*: depth and shape remain much less identifiable than horizontal position. [S30 reviewed main methods/results]

**Located results:**

- Outdoor sensitivity 466 ± 8 E/√Hz; 20 E uncertainty in ten minutes. [S30 p.591, Fig.2]
- Survey known 2m×2m tunnel with plans/GPR/topography informing site model. [S30 pp.591–592]
- Horizontal-centre inference 0.19 ± 0.19 m; depth 1.89 −0.59/+2.3 m. [S30 Methods PDF p.8]
- Survey repeatability similar to commercial gravimeters; systematics remain. [S30 p.593]
- 75 kg head, 250 kg cases, approximately 800 W. [S30 Extended Data Fig.2, PDF p.10]

**Critical reading.** Survey repeatability is similar to commercial gravimeters and limited by systematics, including Coriolis effects; the proposed fifteen-minute scan is conditional on addressing these effects. [S30 p.593] The approximately 75 kg head plus 250 kg control cases draw approximately 800 W. [S30 Extended Data Fig.2] Data and code are deposited; patents and commercial/government interests are declared. [S30 Methods, PDF p.8] *Analysis*: prioritise independent blind, multi-site surveys with false alarms and complete logistical cost. Scientific confidence is high for this demonstrated anomaly; readiness for unconstrained underground discovery remains conditional. [S30 reviewed methods/discussion]

*Independent challenge, scope restriction.* Survives detection/localization on characterized site; does not establish blind unknown-target discrimination. [S30 pp591–592; Methods Inference; Extended Data Table2]

*Independent challenge, scope restriction.* No false-alarm/null-model probability follows from SNR; projected survey speed not measured total time. [S30 p593; Methods Survey practice pp7–8 PDF]

**Access and reproducibility.** Open repository 10.25500/edata.bham.00000740 (paper declaration, Methods PDF p.8); not executed. Patent/commercial/Dstl interests declared, Methods PDF p.8. [S30 availability, declarations and reviewed end matter]

*Analysis.* Survey repeatability is similar to commercial gravimeters and limited by systematics, including Coriolis effects; the proposed fifteen-minute scan is conditional on addressing these effects. [S30 p.593] The approximately 75 kg head plus 250 kg control cases draw approximately 800 W. [S30 Extended Data Fig.2] Data and code are deposited; patents and commercial/government interests are declared. [S30 Methods, PDF p.8] *Analysis*: prioritise independent blind, multi-site surveys with false alarms and complete logistical cost. Scientific confidence is high for this demonstrated anomaly; readiness for unconstrained underground discovery remains conditional. [S30]

### S31: Quantum advantage in microwave quantum radar

Réouven Assouly et al. · 2023-06-29 · T2 evidence access. [Original](https://arxiv.org/abs/2211.05684). [S31]

*Reviewed version:* arXiv:2211.05684v2 (2023-03-02), supplement included; journal metadata checked. Access: full-text PDF. First preprint: 2022-11-10. [S31]

**Contribution and method.** Assouly and colleagues implement the critical joint measurement missing from earlier microwave correlation demonstrations. An initially entangled probe and stored idler are recombined in a superconducting circuit, and qubit-assisted photon counting estimates whether the target is present. The measured advantage is Q = 1.2 ± 0.1 in an error-exponent metric relative to the calculated optimal coherent-state bound under the same calibrated photon resources. [S31 PDF pp.1–4, Fig.3]

This is a stronger scientific benchmark than outperforming one deliberately noisy classical apparatus. *Analysis*: it does not establish superiority to a conventional radar allowed to choose its transmitted power or operating scenario. The hardware operates at 15 mK. Its target is a controllable notch filter and 12 m coaxial delay, rather than an outdoor object; position, speed and reflectivity are assumed known. [S31 PDF pp.1–2, Fig.1]

Signal/noise photon populations and target reflectivity are measured with dedicated calibration protocols. The highlighted data use fifteen series of 500,000 attempts, with signal and noise recalibrated between series. [S31 PDF pp.3–4, Fig.3]

Thermal noise is switched on after state preparation. [S31 PDF p.2]

*Analysis*: these controls make the proof interpretable but deliberately avoid several environmental and target-search difficulties. [S31 reviewed main methods/results]

**Located results:**

- Measured Q=1.2 ± 0.1 relative to coherent-state error-exponent bound. [S31 Fig.3; PDF pp.3–4]
- 15 mK apparatus and target built from notch filter/12m coaxial line. [S31 PDF p.2]
- Target position, speed and reflectivity assumed known. [S31 PDF p.1, protocol paragraph]
- Population-calibration uncertainty mostly statistical; measurement imperfections not included. [S31 Supplement F, PDF p.11]
- Model underestimates measured advantage; origin unresolved. [S31 PDF p.5, Fig.4 discussion]

**Critical reading.** The supplement explicitly says photon-population fitting uncertainties are mostly statistical and omit measurement-protocol imperfections; reflectivity uncertainty is checked across probe amplitudes. [S31 supplement F, PDF p.11] The model underestimates measured advantage, with the origin unresolved; initial thermal populations shrink the region supporting advantage. [S31 PDF pp.4–5, Fig.4] *Analysis*: these are calibration/model qualifications, not evidence that the result is false. A high-confidence application assessment would require independent calibration validation and real targets with unknown delays. [S31 reviewed methods/discussion]

*Independent challenge, scope restriction.* Does not demonstrate unknown-target search/ranging or warm open-air operation. These restrictions are explicit, not concealed. [S31 pp1–3; Fig.1; Methods B3]

*Independent challenge, missing evidence.* Evaluate the modest excess with systematic errors and parameter tuning included. The optimal classical bound remains a demanding comparator. [S31 Eq.1; Figs3–4; Methods E–F pp11–12]

**Access and reproducibility.** Journal figure source-data links checked; no code execution. EU QMICS funding and IARPA/Lincoln Labs supplied hardware, PDF p.5 acknowledgments; no competing-interest declaration located in examined preprint. [S31 availability, declarations and reviewed end matter]

*Analysis.* The journal page provides figure source data; this review did not execute an independent analysis or find an independent experimental replication. [S31 journal page, Source data] *Analysis*: prioritise as a credible entanglement-assisted detection experiment and an engineering-warning case, not as demonstrated long-range or stealth-target radar. [S31]

### S32: Waveguide-coupled Rydberg spectrum analyzer from 0 to 20 GHz

David H. Meyer et al. · 2021-01-27 · T2 evidence access. [Original](https://arxiv.org/abs/2009.14383). [S32]

*Reviewed version:* arXiv:2009.14383v4 (2021-05-20). Access: full-text PDF. First preprint: 2020-09-30. [S32]

**Contribution and method.** Meyer, Kunz and Cox demonstrate a Rydberg receiver backend coupled to a microwave waveguide, with an external antenna used to collect ambient signals. This is atomic transduction and heterodyne reception, not an entanglement-generated radar advantage. The system covers carrier tuning from DC to 20 GHz, while the instantaneous 3 dB bandwidth is 4 MHz. Its abstract reports intrinsic sensitivity up to −120 ± 2 dBm/Hz and over 80 dB linear dynamic range. [S32 PDF pp.1,4, Fig.3]

*Analysis*: the broad carrier range must not be described as simultaneous twenty-gigahertz reception bandwidth. Figure 1 distinguishes directly measured sensitivity, a photon-shot-noise-limited value obtained after independent subtraction of laser phase noise, and preamplified sensitivity. The preamplifier sensitivity curves are calculated by referring intrinsic noise to the input and combining amplifier noise, although ambient reception itself is demonstrated with amplification. [S32 PDF pp.2–3, Fig.1; p.5, Fig.4]

The strongest headline figures therefore need the measurement category attached. *Analysis*: a backend improvement cannot be credited with the entire antenna/amplifier chain's performance. [S32 reviewed main methods/results]

**Located results:**

- Carrier tuning DC–20GHz; 4MHz instantaneous bandwidth. [S32 PDF pp.1,4, Fig.3c]
- PSN-limited sensitivity removes independently calibrated phase noise; amplifier noise curves calculated. [S32 PDF p.3, Fig.1d]
- Ambient signal reception uses external antenna and amplification. [S32 PDF pp.4–5, Fig.4]
- Approximately 50°C chamber and 500mW coupling laser. [S32 Appendix A, PDF p.7]
- Waveguide transmission deteriorated over seven months; contamination attribution provisional. [S32 Appendix D, PDF p.8]

**Critical reading.** A conventional rabbit-ears antenna feeds the system; AM/FM and Wi-Fi/Bluetooth examples appear in the laboratory, including audio verification of one AM station. [S32 PDF pp.4–5] The atom chamber is approximately 50 °C, the coupling beam is approximately 500 mW, and optical path and power fluctuations are actively stabilised. [S32 Appendix A, PDF p.7] These details qualify the phrase near-room-temperature: cryogenics are avoided, but lasers and control are still necessary. [S32 reviewed methods/discussion]

**Access and reproducibility.** No explicit public data/code statement located in examined manuscript. Army authors; partial DARPA support, PDF p.6 acknowledgments. [S32 availability, declarations and reviewed end matter]

*Analysis.* The waveguide's measured transmission deteriorated over seven months, attributed provisionally to rubidium contamination; reported sensitivities retain waveguide losses rather than subtracting them. [S32 Appendix D, PDF p.8] This is a disclosed durability issue, not a confirmed failure mechanism. *Analysis*: useful next tests are stability, calibration and power accounting against an equally broadband classical backend under matched antenna conditions. No data/code availability statement was located in the examined manuscript; no independent replication was established in this bounded scan. *Analysis*: confidence is medium in integrated reception, lower in claims of surpassing established receiver limits. Detailed source confidence retains the reviewed-manuscript version caveat. [S32]

### S33: Performance of antenna-based and Rydberg quantum RF sensors in the electrically small regime

K. M. Backes et al. · 2024-09-30 · T1 (peer-reviewed study; version examined specified) evidence access. [Original](https://inspirehep.net/files/ac16594fd5658d98b52993e9f1437037). [S33]

*Reviewed version:* Applied Physics Letters version of record. Access: full-text PDF. First preprint: 2024-08-27. [S33]

**Contribution and method.** Backes and colleagues provide a consequential baseline correction: comparison with a passive unmatched antenna can overstate the attraction of an atomic receiver. Their equivalent-circuit analysis compares similarly sized dipole/loop antennas with matched passive, unmatched passive and active readout against warm-vapour EIT and ideal standard-quantum-limit Rydberg sensing. The example uses approximately 1 cm sensors over 30 kHz–30 MHz. [S33 article pp.144002-1–3, Figs.1–3]

*Analysis*: this is a theoretical comparison with literature experimental points, not a new matched field trial demonstrating defeat of every Rydberg architecture. The active classical example uses a high-impedance amplifier with 1 nV/√Hz input voltage noise and 100 MΩ input impedance. All sensors are assigned dipolar directivity, so incoming atmospheric noise affects their external signal-to-noise ratio equivalently. [S33 pp.144002-2–3, Eqs.1,7]

Under these assumptions, active unmatched dipoles exceed contemporary warm-vapour EIT sensitivity. [S33 p.144002-4, Fig.3]

*Analysis*: electrically small size alone is insufficient justification for comparison only against inefficient passive antennas; classical active electronics must receive equal engineering attention. [S33 reviewed main methods/results]

**Located results:**

- Example uses 1cm sensors and 30kHz–30MHz frequency range. [S33 article pp.144002-2–3]
- Active baseline assumes 1nV/√Hz voltage noise and 100MΩ input impedance. [S33 p.144002-3]
- Active unmatched antenna outperforms contemporary warm EIT within model. [S33 p.144002-4, Fig.3]
- Ideal cold-atom SQL limit likely physically unrealizable; collective effects omitted. [S33 p.144002-4]
- All sensor external-noise directivities assumed equal dipole. [S33 p.144002-2, Eq.1 discussion]

**Critical reading.** The most spectacular atomic bound instead assumes tightly packed cold atoms, optimised transitions, a restricted interaction-induced shift, and large atom numbers. The authors warn that collective effects could limit this idealisation and that it is likely physically unrealizable, paralleling the ideal matched dipole bound. [S33 p.144002-4] Typical atmospheric noise also sits above the ideal limits. [S33 Fig.3 and p.144002-4] *Analysis*: a quieter internal detector cannot remove the same external field noise it measures; sheltered metrology and arrays require different operational cases. [S33 reviewed methods/discussion]

*Independent challenge, central-result flaw.* Concrete internal equation inconsistencies; numerical-curve impact unresolved without supplement. Does not establish reversal of Fig3 qualitative ordering. [S33 Published p144002-3, Eq7; paragraph defining Q; Eqs9–10 (PDFp4, visually checked)]

*Independent challenge, scope restriction.* Ideal sensitivity is model-dependent benchmark, not achieved performance or full-platform SWaP. [S33 pp144002-3–4; Fig3]

**Access and reproducibility.** Notebook/Python/data described in supplementary material, article p.144002-5; supplement not retrieved. No conflicts declared; DHS/MITRE/Army support disclosed, article p.144002-5. [S33 availability, declarations and reviewed end matter]

*Analysis.* The supplement is described as containing the figure-generating notebook, Python and data; declared conflicts are absent, while DHS/MITRE/Army affiliations and funding are disclosed. [S33 p.144002-5] The supplement itself was not retrieved here. *Analysis*: confidence is high in the paper's stated comparison within its model, moderate in transfer to complete deployed systems. Its value is methodological discipline: require frequency, size, bandwidth, amplification and ambient-noise assumptions before accepting receiver advantage. [S33]

### S34: Electrometry of extremely-low frequencies from kHz to sub-Hz with a Rydberg-atom sensor

Aveek Chandra et al. · 2026-08-05 · T1 (peer-reviewed study; version examined specified) evidence access. [Original](https://link.springer.com/article/10.1140/epjqt/s40507-026-00550-7). [S34]

*Reviewed version:* EPJ Quantum Technology 13:87 version of record. Access: full-text PDF. First preprint: 2026-03-14. [S34]

**Contribution and method.** Chandra, Paensin and Dumke extend low-frequency Rydberg electrometry with a paraffin-coated caesium cell, auxiliary field reversal and lock-in detection. The laboratory observes applied electric fields between 0.5 Hz and 10 kHz. The reported sensitivity is 819 μV/cm/√Hz at 1 Hz, 33 at 10 Hz, 10 at 100 Hz and 2 at 1 kHz. [S34 pp.1,8–9, Figs.4–5]

This is an atomic electric-field receiver improvement, not entanglement-enhanced target detection. *Analysis*: it is relevant to difficult low-frequency sensing but cannot by itself establish underground or underwater detection range. Coated and uncoated-cell transient controls show slower screening in the coated cell. The proposed microscopic explanation is expressly qualitative and charge transport is not directly measured. [S34 pp.4–6, Fig.2]

Residual screening remains and reduces low-frequency responsivity. [S34 p.8]

Fields are generated by external copper plates; the term electrode-free means no electrodes inserted into the vapour, rather than no electrodes in the experiment. [S34 pp.3–4, Fig.1]

*Analysis*: retaining this distinction prevents a misleading impression of a passive stand-alone receiver. [S34 reviewed main methods/results]

**Located results:**

- Controlled sensing spans 0.5Hz–10kHz. [S34 p.8, Fig.4; Appendix E]
- Sensitivity 819 μV/cm/√Hz at 1Hz and 2 μV/cm/√Hz at 1kHz. [S34 p.1; p.9 Fig.5]
- Classical comparator theoretically estimated for 3cm dipole. [S34 p.9, Fig.5b]
- Microscopic charge-transport mechanism not directly measured. [S34 p.6]
- Outdoor pickup, ground loops and drift require further mitigation. [S34 p.10 Outlook]

**Critical reading.** Sensitivity is estimated from responsivity and combined photodetector/lock-in noise. The classical curve is theoretically estimated for a 3 cm dipole, referenced to an earlier assessment, rather than experimentally measured alongside the atoms. [S34 p.9, Fig.5] The sensor uses room-temperature vapour but a high-finesse cavity locks two lasers; a strong auxiliary field sets the operating point. [S34 pp.3,7,10–13] *Analysis*: the claimed size-based advantage should be tested against an active classical receiver and complete-system size/power, especially given the separate baseline analysis in S33. [S34 reviewed methods/discussion]

**Access and reproducibility.** Data on reasonable request, p.16; no code archive located. No competing interests; Singapore NRF/A*STAR support, p.16. [S34 availability, declarations and reviewed end matter]

*Analysis.* The authors identify laser intensity drift as a present limit and explicitly require further outdoor pickup, ground-loop and thermal/polarisation control before field deployment. [S34 pp.9–10] Data are available on reasonable request; no competing interests are declared. [S34 p.16] *Analysis*: confidence is high for controlled low-frequency response, moderate for its sensitivity estimate and low for operational advantage pending matched practical comparison. No independent replication was established in this bounded scan. [S34]

### S35: A Note on the Efficient Operation of Quantum Radar and the Fair Classical Comparison

Florian Bischeltsrieder et al. · 2025-06-12 · T1 (peer-reviewed study; version examined specified) evidence access. [Original](https://elib.dlr.de/214537/1/A_Note_on_the_Efficient_Operation_of_Quantum_Radar_and_the_Fair_Classical_Comparison.pdf). [S35]

*Reviewed version:* IEEE Transactions on Radar Systems version of record, pp.875–880. Access: full-text PDF. First preprint: not independently recorded. [S35]

**Contribution and method.** Bischeltsrieder and colleagues analyse a specific two-mode-squeezed-vacuum correlation receiver and separate outperforming a classical comparator from efficiently reaching a chosen detection error. They formulate an optimisation over noise occupation for a desired quantum advantage and channel loss, minimising required independent signal samples. The resulting efficient operating regime does not coincide with the maximum attainable relative advantage. [S35 pp.876–878, Eqs.10–22, Fig.1]

*Analysis*: this is an important antidote to optimising a headline gain while neglecting absolute acquisition time. The method assumes repeated identical trials, sufficiently many samples for a Gaussian approximation, and the specified joint quadrature-correlation observable. Channel loss remains a parameter; this follow-up does not derive a new target range or cross-section result. [S35 pp.875–877, Eqs.1–6, Section III restrictions]

*Analysis*: its conclusions belong to that receiver/model family and should not be presented as a no-go theorem for every possible quantum ranging architecture or adaptive measurement. [S35 reviewed main methods/results]

**Located results:**

- Efficiency differs from maximum relative advantage for specified receiver. [S35 pp.877–878, Eqs.10–22, Fig.1]
- Model assumes large sample number/Gaussian approximation. [S35 p.877 Section III restrictions]
- Follow-up leaves channel loss parameterised rather than computing target range. [S35 p.876 Eq.5 discussion]
- Comparator prediction mismatch depends on noise occupancy. [S35 pp.878–879 Eqs.23–28]
- Ideal implementation assumed; real implementation may degrade further. [S35 p.879 Conclusion]

**Critical reading.** A second contribution compares coherent-state and classical unmodulated-continuous-wave descriptions of the benchmark. Their prediction mismatch depends on absolute thermal occupation as well as SNR; accordingly, matching SNR alone can be insufficient. The paper argues that a classical comparison experiment under Assouly-like conditions might also need the same cryostatic environment. [S35 pp.878–879, Eqs.23–28, Fig.2] *Analysis*: this is about a fair low-power scientific comparator, not evidence that an ordinary field radar must be cryogenic. [S35 reviewed methods/discussion]

**Access and reproducibility.** Analytical equations published; no new experiment or data/code declaration located. German BMBF QUARATE support, p.875 footnote. [S35 availability, declarations and reviewed end matter]

*Analysis.* The conclusion states its bounds assume ideal implementation and real systems can degrade further. [S35 p.879] This is analytical work with no new field experiment or independent replication in the paper. [S35 Sections II–V] A correction exists to the authors' 2024 predecessor (DOI 10.1109/TRS.2025.3532053); its full text was not accessed in this scan, so predecessor-specific numerical range limits are withheld. *Analysis*: confidence is moderate in this model's comparative insight; use it to demand explicit receiver, photon-resource and time assumptions, while treating operational limits as conditional and keeping that correction gap visible. [S35]

## Quantum-inspired optimisation

### S50: High-performance combinatorial optimization based on classical mechanics

Hayato Goto et al. · 2021-02-03 · T1 evidence access. [Original](https://doi.org/10.1126/sciadv.abe7953). [S50]

*Reviewed version:* Version of record, full article via EuropePMC XML; publisher online date 3 February; Crossref issue date 5 February 2021. Access: full-text. First preprint: not independently recorded. [S50]

**Contribution and method.** Ballistic and discrete simulated-bifurcation variants improve classical Ising heuristics. Hamiltonian-inspired dynamics, inelastic boundaries, sign discretisation; FPGA and GPU-cluster benchmarks. [S50 reviewed main methods/results]

**Located results:**

- The bSB K2000 TTT is 0.26 ms; dSB TTS is 1.3 s. [S50 Results: Benchmarking using time-to-solution and time-to-target; Fig.3B–C]
- Ultralarge benchmarks use 16 GPUs and statistically estimated optimal/target values. [S50 Results: Fig.4 and accompanying text]
- Other-machine TTS/TTT is cited or estimated from literature because authors could not use those machines. [S50 Results: Benchmarking using time-to-solution and time-to-target]

**Critical reading.** Comparators often drawn from prior publications; some obsolete or simulated hardware; million-spin targets statistically estimated rather than certified optima. No scheduling constraints benchmark. [S50 reviewed methods/discussion]

**Access and reproducibility.** Algorithm equations in Methods; supplementary materials referenced; additional data on request. Supplement itself not successfully retrieved. Toshiba authors; five authors named as inventors on Toshiba patent application P2019-164742 (Competing interests). [S50 availability, declarations and reviewed end matter]

*Analysis.* Strong algorithm/hardware anchor; insufficient for universal solver advantage or operational scheduling. [S50]

### S51: Benchmark of quantum-inspired heuristic solvers for quadratic unconstrained binary optimization

Hiroki Oshiyama et al. · 2022-02-09 · T1 evidence access. [Original](https://www.nature.com/articles/s41598-022-06070-5). [S51]

*Reviewed version:* Publisher PDF version of record; arXiv latest v3 15 December 2021. Access: full-text. First preprint: 2021-04-29. [S51]

**Contribution and method.** Cross-family comparison shows solver rankings depend on benchmark structure. 45 MQLib problems, ten NAE-3SAT instances, six SK instances; commercial HSS/SBM/DA and single-thread neal SA. [S51 reviewed main methods/results]

**Located results:**

- 45 MQLib problems were selected from the HSS white-paper benchmark set. [S51 p.2, Problem instances for benchmarking]
- Network time is ignored; HSS and SBM use requested budgets whereas DA uses reported elapsed time. [S51 p.3, Results]
- Reference score denominator is lowest value found by tested solvers, not certified optimum. [S51 p.4 Eq.(4)]

**Critical reading.** No state-of-the-art tuned classical portfolio; heterogeneous hardware/parallelism; execution-time conventions differ, network excluded; best observed is not certified optimum. [S51 reviewed methods/discussion]

**Access and reproducibility.** MQLib instances public; generator listings for NAE3SAT/SK; other data on request; proprietary SBM evaluation build and HSS internals. No competing interests declared; acknowledgments report D-Wave and Toshiba research support; Ohzeki Sigma-I affiliation. [S51 availability, declarations and reviewed end matter]

*Analysis.* Good counterweight to universal-winner claims; limited evidence of classical superiority because baseline is single-thread SA. [S51]

### S52: An Optimization Case Study for solving a Transport Robot Scheduling Problem on Quantum-Hybrid and Quantum-Inspired Hardware

Dominik Leib et al. · 2023-10-31 · T2 evidence access. [Original](https://arxiv.org/abs/2309.09736). [S52]

*Reviewed version:* arXiv v4 24 October2023; linked Scientific Reports13,18743. Access: full-text. First preprint: 2023-09-18. [S52]

**Contribution and method.** Application-based scheduling comparison with native MIP formulations and equal-quality timing. 260 generated BASF-inspired laboratory schedules; sequence/time-indexed Gurobi MIPs vs QUBO LBQM, DA and hybrid DA. [S52 reviewed main methods/results]

**Located results:**

- 260 instances split161 minor2071–8080 variables and99 major10822–22692. [S52 §3.1; Table1]
- Submission-to-return runtimes include network delays but exclude programmatic model construction. [S52 §4.1 opening paragraph]
- Sequence Gurobi reaches QFDA quality10–100 times faster on minor instances; hybrid DA advantage for N20 major instances. [S52 §4.1 Fig.5; §4.2 Fig.7]
- Native sequence Gurobi reaches Digital Annealer quality10–100times faster on minor instances; the hybrid Digital Annealer wins the equal-quality comparison for the largest N20 group. [S52 §§4.1–4.2; Figs.5,7]

**Critical reading.** Out-of-box Gurobi, no tailored metaheuristics; large-instance Gurobi values capped at3600s; solver submission-to-return excludes model construction; preset budgets not scaling complexity proof. [S52 reviewed methods/discussion]

**Access and reproducibility.** Generated instance library and parameter tables referenced in supplementary material; proprietary solvers, no independent reproduction performed. Industrially motivated BASF use case; BMBF RymaxOne funding (§6); supplier internals confidential. No unverified conflict allegation. [S52 availability, declarations and reviewed end matter]

*Analysis.* Most directly transferable scheduling study in this set, with bounded positive quantum-inspired result. [S52]

### S53: Toward quantum scaling advantage in approximate optimization

J. Pawłowski et al. · 2026-07-08 · T2 evidence access. [Original](https://arxiv.org/abs/2505.22514). [S53]

*Reviewed version:* arXiv v2 10 July2026; PhysRevApplied26,014024; earlier title Closing the Quantum-Classical Scaling Gap in Approximate Optimization. Access: full-text. First preprint: 2025-05-28. [S53]

**Contribution and method.** Adds a GPU simulated-bifurcation baseline to challenge a claimed quantum scaling advantage. Same125 Sidon28 instances per size N142–1322,100 independent runs; tune steps/replicas,99% TT-epsilon target; extended classical instances up to38320. [S53 reviewed main methods/results]

**Located results:**

- Original comparison uses125 instances per size N142–1322 and100 solver runs; Gurobi certifies original ground reference. [S53 main text Thermal vs Chaotic vs Quantum Annealing, Eq.1]
- Total SBM runtime includes CPU-GPU transfer/memory/result handling; pure GPU time excludes those. [S53 main text Eq.1 discussion; supplement S5]
- Common initialization costs are neglected and GPU samples are parallel whereas QA samples sequential. [S53 supplement S5 Runtime accounting]
- Four-GPU total TT-epsilon is about100 times the single-GPU value for the small-instance comparison due to dispatch/collection overhead, despite improved fitted exponent. [S53 Supplement S1 Multi-GPU Simulated Bifurcation Machine, Fig.S1]

**Critical reading.** Class/problem-specific; hardware resources unequal; large classical benchmark cannot directly compare unavailable future QPU; common initialization overhead omitted; no constrained logistics. Supplement S1 reports four-GPU total TT-epsilon values about100 times single-GPU at small sizes despite improved scaling exponent; exponent is not absolute speed. [S53 reviewed methods/discussion]

*Independent challenge, scope restriction.* A strong counter-baseline for this ensemble; not a theorem about general optimisation. [S53 Thermal vs Chaotic vs Quantum Annealing; S2]

*Independent challenge, scope restriction.* Separate exponent, actual latency and hardware/resource budget. [S53 S1 FigS1; S5]

**Access and reproducibility.** Original benchmark Dataverse instances; new supporting data available upon reasonable request, not fully open replication package. Quantumz.io affiliations and NCBR support; NCN funding; do not label independent of solver commercial interests. [S53 availability, declarations and reviewed end matter]

*Analysis.* Strong requirement to update classical baselines and distinguish anneal-time, QPU-access and external runtime; not a universal no-advantage theorem. [S53]

### S54: Limitations of tensor-network approaches for optimization and sampling: A comparison to quantum and classical Ising machines

Anna Maria Dziubyna et al. · 2025-05-19 · T2 evidence access. [Original](https://arxiv.org/abs/2411.16431). [S54]

*Reviewed version:* arXiv v3 16 June2025; PhysRevApplied23,054049. Access: full-text. First preprint: 2024-11-25. [S54]

**Contribution and method.** Diagnoses limits of approximate tensor-network optimisation and sampling on modern annealer graphs. Approximate-marginal branch-and-bound, PEPS/GPU acceleration and dimension reduction;20 instances per class/size; QA and SBM comparator. [S54 reviewed main methods/results]

**Located results:**

- Largest5376-spin Pegasus TN runs require local dimension reduction to2^16 states due to memory. [S54 §V.3 Fig.10]
- Reference dE=(E-Ebest)/(2|Ebest|) uses combined solver best when true ground unknown. [S54 §V.2 Eq.14]
- Planted cases improve best-energy difference by factor3–4; ground states not found for721/3065-spin cases. [S54 §V.3; AppendixA Fig.A1]

**Critical reading.** Best-known energies not always certified optima; energy metric has factor2 denominator; memory truncation and geometry-specific contraction failures; QPU access overhead excluded from comparison. [S54 reviewed methods/discussion]

**Access and reproducibility.** SpinGlassPEPS.jl public; instance/results repository DOI10.18150/OUGF1O; reported open, not run here. Mohseni HPE Labs affiliation; NCN/QuantERA/EU and DARPA/AFRL support disclosed. No personal competing-interest inference. [S54 availability, declarations and reviewed end matter]

*Analysis.* Strong negative methodological evidence against treating all tensor-network approaches as scalable universal solvers. [S54]

### S55: A Reality Check on Quantum Optimisation: Evidence from an Industrial Case Study

Hila Safi et al. · 2026-07-14 · T2 evidence access. [Original](https://arxiv.org/abs/2607.13325). [S55]

*Reviewed version:* arXiv v1 14 July2026; no journal reference displayed at review. Access: full-text. First preprint: 2026-07-14. [S55]

**Contribution and method.** Industrial assignment/scheduling comparison separates feasibility, formulation and encoded quality. Siemens-motivated machines/jobs/rigs, compact and constraint-rich QUBOs; IBM, DWave, DA, native exact/MILP and greedy/iterative methods. [S55 reviewed main methods/results]

**Located results:**

- Beyond6 machines5 rigs14 jobs, reference is best found within1h rather than certified optimal. [S55 §V-A Benchmark]
- Communication latencies, API overhead and queue delays excluded despite end-to-end label in metrics. [S55 §V-C item3; §VII-E Ecological Validity]
- Data realistic but not directly sourced from live production; dynamics such as new job arrivals omitted. [S55 §VII-E]
- Digital Annealer results are compared with greedy and iterated-greedy approximations; the paper does not establish superiority over all tuned native scheduling solvers. [S55 §§III-C,V-B,VI-D,VII-C]

**Critical reading.** Unreviewed; large reference best found in1h not certified optimum; §V labels time end-to-end but §VII-E excludes API/network/queues; realistic generated data not live production; closed sample distributions. [S55 reviewed methods/discussion]

*Independent challenge, central-result flaw.* The end-to-end label is false; operational timing advantage is not established. [S55 V-C item3; VII-E]

*Independent challenge, scope restriction.* Use best-known gaps at larger sizes; no certified approximation guarantee. [S55 V-A; VII-A; Fig8 caption and VI-D]

**Access and reproducibility.** Paper cites reproduction package Zenodo DOI10.5281/zenodo.21363322; existence/content not independently verified here. Siemens authors and former employee; German BMBF support. No direct Fujitsu authorship displayed. [S55 availability, declarations and reviewed end matter]

*Analysis.* Important recent counterweight; evidence for formulation-aware classical accelerator utility, not best-in-class or quantum advantage. [S55]

## Emerging phenomena

### S70: Field Demonstration of Distributed Quantum Sensing without Post-Selection

Si-Ran Zhao et al. · 2021-07-14 · T1 evidence access. [Original](https://journals.aps.org/prx/pdf/10.1103/PhysRevX.11.031009). [S70]

*Reviewed version:* Phys. Rev. X 11,031009 version of record; original arXiv2011.02807v1 also inspected. Journal PDF checked by Astra and orchestrator.. Access: full journal PDF and initial preprint. First preprint: 2020-11-05. [S70]

**Contribution and method.** Entangled photons and coherent repeated phase sampling estimate a weighted combination of two separated phases without hiding lost photons through postselection. Telecom polarization-entangled pairs are delivered to two sensors; Bob samples his phase twice. Single and multiple detector events, heralding efficiencies and higher-order pair emissions enter photon-pass resource accounting. The SNL reference is an ideal lossless local estimation strategy with optimally allocated independent photon passes. [S70 reviewed main methods/results]

**Located results:**

- At 240 m, best phase precision is 0.916 dB below the loss-accounted photon-pass shot-noise limit. [S70 journal pp.2,5; Fig.2]
- The non-multipass equal-weight phase experiment is 0.326 dB below its shot-noise limit. [S70 journal p.5; Appendix E p.8]
- The 10 km random-phase experiment does not beat the shot-noise limit because of losses. [S70 journal p.5; Fig.3 and Table I]
- Visibility-aware threshold efficiency in the journal version is 59.1%. [S70 journal p.2; Appendix A p.6]

**Critical reading.** Analysis: controlled waveplate phases and fibre spools do not demonstrate physical target sensing. Photon passes, including losses and multipair events, are counted; full infrastructure, acquisition time and alternative classical architectures are not the comparison metric. Journal additions take precedence over initial preprint values. [S70 pp.2–5; Appendices A–E] [S70 reviewed methods/discussion]

*Independent challenge, scope restriction.* Do not combine240m advantage with10km reach into one result. [S70 III p5 Fig3/TableI]

*Independent challenge, scope restriction.* Outdoor distribution is genuine; defence target sensing or deployed network is untested. [S70 II Fig1 pp3–4; III p5]

*Objection rejected.* Concern is rebutted by explicit resource accounting; no demonstrated loophole. [S70 II Eq2 p4; AppendicesA/B p6]

**Access and reproducibility.** Experimental apparatus, estimators and efficiency/resource derivation are documented in main text and appendicesA–C; no independent replication established in this bounded search. Raw public dataset/code not identified in examined preprint. Not located in examined preprint; journal declaration not independently retrieved. [S70 availability, declarations and reviewed end matter]

*Analysis.* High confidence in scoped240m result; limited network scalability and operational relevance. [S70]

### S71: Distributed quantum sensing with mode-entangled spin-squeezed atomic states

Benjamin K. Malia et al. · 2022-11-23 · T2 evidence access. [Original](https://arxiv.org/html/2205.06382). [S71]

*Reviewed version:* arxiv full manuscript; journal metadata cross-checked. Access: full text with version caveat. First preprint: 2022-05-12. [S71]

**Contribution and method.** A shared quantum nondemolition measurement creates nonlocal entanglement between atomic modes, enabling differential clock and interferometer protocols. Rubidium ensembles in a common cavity are divided into as many as four spatial modes; a shared QND observation prepares correlated populations. Microwave Ramsey operations and Raman-pulse differential interferometry test the prepared modes. Each clock mode contains45000atoms. Baselines include projection-noise-limited coherent states and a projected mode-separable spin-squeezed network. [S71 reviewed main methods/results]

**Located results:**

- Four-mode clock result11.6(1.1)dB below coherent-state QPN. [S71 arxivv1 main text, four-mode network paragraph and Fig.3]
- 4.5(0.8)dB improvement uses a projected mode-separable baseline. [S71 arxivv1 Fig.3 and accompanying paragraph]
- Differential atom-interferometer improvement1.6(0.9)dB. [S71 arxivv1 Fig.4 and accompanying paragraph]

**Critical reading.** All nodes share laboratory cavity infrastructure; the atom modes are not a geographically separated clock network. The4.5dB reference is projected, not a separately field-operated competitor. Gains exploit improved squeezing efficiency as the total atom count entangled increases. Differential rejection of Raman common-mode phase noise is also present and must be separated from entanglement benefit. No broad optimized-classical end-to-end network comparison is demonstrated. [S71 reviewed methods/discussion]

**Access and reproducibility.** Full arxivv1 main text and Methods inspected; peer-reviewed title/date/DOI cross-checked on Nature landing page. Journal main text is paywalled; preprint-versus-final changes remain a version caveat. Journal data and analysis code are available from corresponding author upon reasonable request, not an open repository. Journal declaration: no competing interests. [S71 availability, declarations and reviewed end matter]

*Analysis.* Medium confidence in laboratory metrology; medium confidence in extrapolation beyond common apparatus. Detailed source confidence retains the reviewed-manuscript version caveat. [S71]

### S72: Entanglement-enhanced matter-wave interferometry in a high-finesse cavity

Graham P. Greve et al. · 2022-10-19 · T1 evidence access. [Original](https://www.nature.com/articles/s41586-022-05197-9). [S72]

*Reviewed version:* Journal HTML. Access: full text and methods; supplement where provided. First preprint: 2021-10-27. [S72]

**Contribution and method.** Cavity-mediated entanglement is injected into a complete light-pulse matter-wave interferometer rather than demonstrated only as state preparation. Free-falling rubidium wave packets receive Raman momentum kicks in a high-finesse cavity. QND measurement and one-axis twisting prepare squeezed momentum states. The full Mach–Zehnder sequence uses OAT; phase noise and contrast define the Wineland parameter, with atom number and spatially varying coupling calibrated separately. [S72 reviewed main methods/results]

**Located results:**

- Full interferometer shows1.7±0.5dB below calibrated SQL at0.112 ms. [S72 journal Fig.4b and Entangled matter-wave interferometry]
- 3.4dB compares actual squeezed and imperfect-contrast unsqueezed interferometers. [S72 journal Entangled matter-wave interferometry; Methods Wineland parameter]
- Below-SQL phase sensitivity persists up to approximately 0.7 ms evolution time. [S72 journal Fig.4d and accompanying text]

**Critical reading.** Short interrogation time and residual spin-related decoherence sharply limit practical inertial advantage. An independent unreviewed critique by McGuinness (arXiv2301.04396v2) disputes phase/SQL interpretation and resource accounting; its blanket denial is not established by citing it. [S76 pp.1–5] Authors explicitly distinguish contrast-adjusted entanglement witness from larger ordinary noise cancellation. Independent calibrated acceleration-versus-phase and full-cycle comparisons would be more useful than accepting either universal claim. [S72 reviewed methods/discussion]

**Access and reproducibility.** Full corrected journal text and Methods read; public datasets at doi10.25810/t39m-c562 declared. Publisher correction(2022-12-06) restores omitted hbar labels and removes an incorrect peer-review-manuscript link, not a reported numerical-result retraction. [S77 correction notice] Independent experimental replication not established. Authors declare no competing interests; NSF,DOE,NIST,DARPA funding listed. [S72 availability, declarations and reviewed end matter]

*Analysis.* High confidence in reported local calibrated laboratory variance/contrast; practical inertial superiority remains untested and critique warrants explicit parameter definition. [S72]

### S73: Quantum locking of intrinsic spin squeezed state in Earth-field-range magnetometry

Peiyu Yang et al. · 2025-03-03 · T1 evidence access. [Original](https://www.nature.com/articles/s41534-025-00971-9). [S73]

*Reviewed version:* Journal HTML. Access: full text and methods; supplement where provided. First preprint: not independently recorded. [S73]

**Contribution and method.** Nonlinear Zeeman dynamics create intrinsic single-atom squeezing; optimized dynamical decoupling locks its changing axis to the observable instead of simply suppressing that dynamics. Breit–Rabi expansion yields a quadratic spin Hamiltonian. A differential-evolution algorithm chooses discretized RF rotation pulses. Numerical state fidelity and signal/noise propagation assess dark-interval and continuous-readout protocols; supplementary notes derive SQL and the nuclear-electron entanglement mechanism. [S73 reviewed main methods/results]

**Located results:**

- Rb maximum modelled metrological gain approaches2.9 dB. [S73 Results Fig.1b, Eq.5]
- No atom–atom entanglement appears; gain independent ofN. [S73 Results Spin squeezing, Eq.4–5]
- 4.29 fT/sqrt(Hz) comes from assumed cell,atom number and coherence. [S73 Discussion numerical sensitivity paragraph]

**Critical reading.** Explicitly no atom–atom entanglement is needed; gain is single-atom nuclear-electron correlation and independent ofN. The largest apparent improvement also restores assumed coherence, not squeezing alone. Instantaneous-rotation and rotating-wave approximations constrain pulse duration. Readout backaction, gradients and measurement-duty trade-offs are discussed but no complete measured noise budget or moving-platform demonstration is supplied. [S73 reviewed methods/discussion]

*Independent challenge, scope restriction.* Label predicted sensitivity, not experimental demonstration. [S73 Discussion; Eqs4–5; Fig1; SupplementNote1]

*Independent challenge, missing evidence.* Spin-noise advantage is conditional on readout/technical noise control. [S73 Eq5; Methods atom-light interaction; Discussion]

*Objection rejected.* Reject this objection; clarify resource and absence of improved N scaling. [S73 Eq4 discussion; SupplementNote3]

**Access and reproducibility.** Main Results,Methods,Discussion and supplementary notes1–3,8 inspected. Equations and optimized pulse sequence are given; authors say evaluation data are within paper/supplement and additional data on request. No code repository identified; no experimental replication established because this is a proposed protocol. Authors declare no competing interests. [S73 availability, declarations and reviewed end matter]

*Analysis.* High confidence in classification as numerical proposal; medium confidence in achievable hardware gain. [S73]

### S74: Superabsorption in an organic microcavity: Toward a quantum battery

James Q. Quach et al. · 2022-01-14 · T2 evidence access. [Original](https://arxiv.org/pdf/2012.06026). [S74]

*Reviewed version:* arxiv full manuscript; journal metadata cross-checked. Access: full text with version caveat. First preprint: 2020-12-10. [S74]

**Contribution and method.** Organic-molecule collective light–matter coupling produces faster absorption as absorber count increases; dephasing moves energy into less radiative dark modes. Lumogen-F Orange dye in polystyrene is placed between dielectric mirrors. Concentrations0.5%,1%,5%,10% span weak to strong coupling. Femtosecond pump–probe differential reflectivity is fit to an open-system model; peak population-derived energy density, rise time and charging power are extracted from model fits, with supporting spectroscopy and fit sensitivity in supplement. [S74 reviewed main methods/results]

**Located results:**

- Pump–probe spectroscopy extracts excitation energy and fitted charging dynamics. [S74 arxiv main pp.6–11,Figs.2–3,Table1]
- Only6–8% of incident pump energy enters cavity. [S74 arxiv main p.7,Experimental setup]
- Dissipation/dephasing suppresses collective re-emission and stabilizes energy. [S74 arxiv main pp.3,11–14; supplementary model]

**Critical reading.** This precursor has no demonstrated electrical extraction, useful discharge cycle or net wall-plug efficiency. Increased concentration and coupling regimes change together; fitted collective dynamics should not be reported as proof that entanglement uniquely causes practical energy advantage. Finite experimental concentration range, molecular quenching at larger concentration and dephasing/decay assumptions limit extrapolation. A fixed-resource comparison requires incident/absorbed energy,mode volume,loss and preparation accounting. [S74 reviewed methods/discussion]

**Access and reproducibility.** Full accessible arxiv PDF main text plus supplement examined; DOI/journal identity verified through opened publisher DOI and author university research portal. Version is latest downloadable arxiv manuscript, not an independently diffed journal PDF. Detailed fabrication,spectroscopy and fitting documented; independent replication/open code repository not established in this bounded review. Declaration not verified from examined version; treat unknown, not no conflict. [S74 availability, declarations and reviewed end matter]

*Analysis.* Medium confidence in spectroscopic collective enhancement; no demonstrated usable battery output. Detailed source confidence retains the reviewed-manuscript version caveat. [S74]

### S75: Superextensive electrical power from a quantum battery

Kieran Hymas et al. · 2026-03-13 · T1 evidence access. [Original](https://www.nature.com/articles/s41377-026-02240-6). [S75]

*Reviewed version:* Journal HTML. Access: full text and methods; supplement where provided. First preprint: 2025-01-27. [S75]

**Contribution and method.** Charge-transport layers turn an organic polariton microcavity into a steady-state electrical-output device, addressing the missing extraction step in earlier spectroscopy-only battery demonstrations. Eight CuPc:C60 devices vary absorber count within a nominal126nm cavity. Cavity and no-cavity controls share substrates. Reflectance establishes strong coupling; ultrafast pump–probe data quantify excitation dynamics; current–voltage scans under625nm illumination measure electrical output. Intersystem crossing populates metastable triplet states; coupled-oscillator and open-system models connect these stages. [S75 reviewed main methods/results]

**Located results:**

- Electrical output densities approximately10–40microW/cm². [S75 Results electrical discharge paragraph,Fig.4c; supplementIV.A]
- Cavity/control power ratio increases with N; modeledPc ~ N². [S75 Results Fig.4d; supplementIV.B]
- Metastable optical excitation persists tens of nanoseconds. [S75 Fig.3a and accompanying text]
- 126nm cavity length fixed while optical length varies. [S75 supplement p.3,Fig.S1]
- Electrical output is measured under constant625nm illumination; excitation persistence is measured separately by transient optical spectroscopy. [S75 Fig.3; Fig.4b–d; Methods Discharging power]

**Critical reading.** Always-illuminated steady-state photocurrent does not by itself demonstrate sustained useful dark discharge. Controls omit a metal mirror and therefore differ optically as well as in coupling; comparisons to an independently optimized photovoltaic architecture and equal absorbed/incident energy are needed for practical superiority. Concentration alters carrier dynamics,cavity detuning andQ; authors normalize with same-run controls and discussD8 deviation. No entanglement witness isolates uniquely quantum causal advantage. No complete round-trip/net external efficiency,macroscopic capacity or cycling durability demonstrated. [S75 reviewed methods/discussion]

*Independent challenge, scope restriction.* Not delayed electrical discharge after charging, cycle life or round-trip storage efficiency; inferred incident-light conversion is roughly0.1–0.4%, not round-trip efficiency. [S75 Fig3–4; MethodsDischarging power; SupplementIV-A]

*Independent challenge, missing evidence.* Finite device family and model do not certify asymptotic exponent or universal advantage. [S75 Device engineering; Fig4d; SupplementS17,IV-B/S19]

**Access and reproducibility.** Full journal text,Methods and32-page supplement inspected, emphasizing geometry/controls,ultrafast normalization and electrical model. Data available on request; no public code repository identified. Independent replication not established. Authors declare no competing interests. [S75 availability, declarations and reviewed end matter]

*Analysis.* High confidence in measured electrical output; medium confidence in causal scaling interpretation; low deployment maturity. [S75]
