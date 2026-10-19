# Independent Astra sensing challenge

Analysis only: independent initial pass, without reading Sol reviews or parent verdicts. Six original papers examined; no experimental or code reproduction. Locators identify original sources, not other reviews. S10 supplement reviewed; S30 extended tables inspected as images; S31 appended methods reviewed; S33 supplementary plotting code unavailable. Objections below distinguish reporting/derivation defects from scope and missing evidence.

## S10 — Optical clocks at sea

Primary: https://www.nature.com/articles/s41586-024-07225-2

**Defensible result.** Three engineered iodine clocks operated at sea; pairwise PICKLES–EPIC instability was 8e-15 at 100000 s without drift removal, with independent NIST comparisons before deployment. [S10]

**Analysis — scope restriction.** Long-time sea result is pairwise, normalized by sqrt(2) assuming equal contributions; no independent reference at sea. Supplement provides land sensitivity tests and argues correlations small, rather than measuring absolute shipboard timing. Preserves pairwise stability; individual absolute holdover is inferred and assumption-dependent. [S10 Main following Fig.3; Supplement Potential Correlations in At-Sea Data]

**Analysis — scope restriction.** VIPER restarted once after external power-supply software fault; displayed record begins after restart. Three-clock metrology installation occupied 23 U with supplies/laptops/UPS. Qualifies uptime and platform burden; does not undermine clock stability. [S10 Main RIMPAC deployment; Methods RIMPAC test setup; Fig.3a]

**Verdict.** Strong field result; do not equate Allan-deviation-derived holdover with independently observed absolute error. **Would resolve:** Independent diverse reference at sea, direct holdover residuals with specified initialization, full installation SWaP and uptime logs.

## S13 — Quantum-assured magnetic navigation

Primary: https://arxiv.org/abs/2504.08167v1

**Defensible result.** Reported map-aided navigation improves endpoint error over strategic-grade INS across aircraft and ground trials, including onboard sensors with scalar airspeed aiding. [S13]

**Analysis — scope restriction.** Table1 assigns both headline endpoints to 3D-velocity-aided configurations; Fig.4b explicitly singles out scalar-airspeed configuration as complete GNSS denial. Source of 3D velocity is not specified in reviewed version. Cannot assign best numbers to GNSS-free velocity aiding. This is missing provenance, not proof that GNSS leaked. Scalar-airspeed endpoints 515/566 m remain. [S13 Table1; Fig.1 caption; Demonstration of MagNav; Fig.4]

**Analysis — missing evidence.** INS alone is comparator; no equivalent conventional-magnetometer MagNav ablation. Algorithm coefficients, likelihood and data are not supplied in sufficient detail for independent reconstruction. System-level advantage survives; quantum-specific advantage and independent reproducibility unestablished. [S13 Q-CTRL magnetic denoising and map-matching algorithms; Discussion optimal sensor architecture]

**Analysis — scope restriction.** Cold start refers to platform magnetic model; initial position supplied, tolerated errors reported up to4 km. Iterative filter is designed for real-time; discussion calls correction quasi-real-time; live flight-management integration not documented. Preserves causal algorithm claim, restricts initialization and operational claims. No evidence of whole-flight smoothing was found. [S13 Algorithms; Fig.6; Discussion]

**Analysis — scope restriction.** 22m is best final position, 46x is endpoint ratio; maps have coverage and relief limitations explicitly acknowledged. Cannot substitute endpoints for RMS/percentiles or infer global robustness. [S13 Abstract; Table1; Discussion final paragraphs]

**Verdict.** Promising preprint, with headline aiding and comparator qualifications. **Would resolve:** Velocity-input provenance, held-out routes, full error distributions, algorithm/data release, conventional MagNav comparator and logged live integration.

## S14 — GNSS-free quantum gravity-aided navigation

Primary: https://arxiv.org/abs/2608.25563v1

**Defensible result.** A reported GNSS-withheld gravity-aided chain reduces terminal inertial error from26 km to4.0–4.1 km on83 km route; separate GNSS-aided survey supports repeatable gravity recovery. [S14]

**Analysis — central-result flaw.** Abstract says DRMS; Fig.2 caption explicitly says1nmi band is not a reported DRMS statistic. Results give2.2nmi terminal error and1nmi only first38 of45nmi; Discussion describes~1nmi bound over evaluation. Internal reporting inconsistency invalidates specific full-route1nmi/DRMS characterization, not demonstrated error reduction. [S14 Abstract; Fig.2 caption; Results Quantum navigation; Discussion second paragraph]

**Analysis — scope restriction.** 70x is an Allan-deviation ratio at80000s in56h stationary laboratory record;0.16mGal is mean inter-trace difference, whereas spatial residual RMS0.67mGal. Classical-only ablation omits atomic bias correction without optimized classical drift calibration. Preserves bias-stabilization evidence but not70x mobile navigation improvement or0.16mGal spatial accuracy; authors acknowledge superior classical survey benchmarks. [S14 Fig.7; Methods hybridization; Results Strapdown; Discussion classical benchmarks]

**Analysis — scope restriction.** Gimbaled coastal runs typically Sea States2–3; strapdown typically1; only northbound gimbaled run samples largest motion. Noisy northbound trace excluded from other traces’ reference ensembles. Comparison valid in overlapping motion range; unequal exposure/selection limits broader robustness inference. [S14 Methods Maritime details; Methods gravity signal; Fig.4 caption]

**Analysis — missing evidence.** Recorded raw IMU is independently mechanized and both estimates share initial state; quantitative initialization uncertainty/source and live closed-loop timing are not detailed. Paper explicitly calls long-duration fully closed campaign future work. No basis to allege hidden GNSS; insufficient to establish cold-start or online autonomy. GNSS-aided survey branch explicitly separate. [S14 Results Quantum navigation; Methods Gravity-aided navigation; Discussion future work]

**Verdict.** Useful preprint with consequential metric inconsistency; application superiority remains unproved. **Would resolve:** Correct DRMS/endpoint language; publish trajectory/error statistics and initialization; live long-duration trial; matched-motion and optimized classical comparisons.

## S30 — Quantum sensing for gravity cartography

Primary: https://www.nature.com/articles/s41586-021-04315-3

**Defensible result.** Outdoor quantum gradiometry detects a known tunnel anomaly consistent with site model; test-mass control agrees205±13.1E with202E prediction. [S30]

**Analysis — scope restriction.** Known tunnel/site supported by CAD/GPR/topographic model. Inference assumes buried cuboid, informative density prior−1.80±0.10g/cm3; depth1.89−0.59/+2.3m broad and parameter ambiguity explicit. Horizontal prior sigma4m is broad, so accurate location is not simply fixed by tight prior. Survives detection/localization on characterized site; does not establish blind unknown-target discrimination. [S30 pp591–592; Methods Inference; Extended Data Table2]

**Analysis — scope restriction.** SNR estimated150E approximate signal divided17.9E mean point uncertainty; survey uses600shots per measurement, repeats, interleaved base stations and line drift subtraction.15min/SNR3 explicitly conditional future calculation. No false-alarm/null-model probability follows from SNR; projected survey speed not measured total time. [S30 p593; Methods Survey practice pp7–8 PDF]

**Analysis — scope restriction.** Authors state survey repeatability similar to commercial gravimeters and systematic-limited; table gives<26E yaw-related point-to-point effects and<43E magnetic bound limited by calibration resolution. Preserves differential noise rejection but not blanket operational superiority or exhaustive systematic immunity. [S30 p593; Extended Data Table1]

**Verdict.** Strong scientific/engineering result; blind detection, geometry certainty and faster survey extrapolations restricted. **Would resolve:** Blind sites with target-absent controls, matched-time classical survey, prior/model sensitivity tests and complete survey elapsed time.

## S31 — Demonstration of Quantum Advantage in Microwave Quantum Radar

Primary: https://arxiv.org/abs/2211.05684v2 (criticism restricted to this version; journal version not checked)

**Defensible result.** Joint microwave signal-idler measurement reports Q1.2(1) relative to modeled optimal coherent-state bound in cold, known-target binary detection experiment. [S31]

**Analysis — scope restriction.** Position, speed and reflectivity assumed known; target coaxial delay/filter at15mK, delay86ns; added thermal noise switched on only after state preparation. Does not demonstrate unknown-target search/ranging or warm open-air operation. These restrictions are explicit, not concealed. [S31 pp1–3; Fig.1; Methods B3]

**Analysis — missing evidence.** Methods F says photon-number uncertainties mostly statistical, omit protocol imperfections, and classical bound propagation assumes independent calibrations. Gain and outcome weights selected to maximize E; no separate held-out tuning evaluation specified. Modest excess needs systematic and selection-robust validation. This is not evidence advantage vanishes. Optimal classical bound is a strong comparator, not straw man. [S31 Eq.1; Figs3–4; Methods E–F pp11–12]

**Analysis — central-result flaw.** p4 prints Ecl2.1(1)e-5, but printed kappa0.0302,NS0.0353,NN10.8 and formula kappaNS/(4NN) give approximately2.47e-5. E2.9e-5 divided latter gives1.18, consistent Q1.2; divided2.1e-5 gives1.38. Later p4 Ecl=kappaNS/NN also omits factor4. Reporting/arithmetic error warrants correction; does not itself refute Q1.2, which agrees with parameter-derived denominator. [S31 pp1,3–4; Methods F Eq.8]

**Analysis — missing evidence.** Authors explicitly note model systematically underestimates Q with origin unresolved, possible measurement model issue. Limits mechanistic quantitative confidence, not independent demonstration by itself. [S31 p4 Fig.4 discussion]

**Verdict.** Credible narrow result; quantitative uncertainty and reporting require care, deployment not shown. **Would resolve:** Correct denominator text; systematic calibration covariance and independent tuning/test sets; direct error-vs-attempt curves for claimed exponent.

## S33 — Performance of antenna-based and Rydberg quantum RF sensors in the electrically small regime

Primary: https://doi.org/10.1063/5.0222827

**Defensible result.** Model comparison properly includes active high-impedance classical receivers and predicts present warm-vapour REIT sensitivity worse than amplified small dipoles. [S33]

**Analysis — central-result flaw.** Eq7 multiplies amplifier noise by voltage-divider squared; input-referred amplifier noise should divide by squared transfer, while antenna Johnson input noise remains at input. Limit Ramp→0 gives zero printed NEV despite lost signal. Separately definitions Q=omega*tau*exp(−tau*Gamma), Vout_noise²=tau/N imply NEVin²=exp(2tauGamma)/(N*omega²*tau); at tau=1/(2Gamma) this is2eGamma/(N*omega²), but Eq10 prints2Gamma/(e*N*omega²). Concrete internal equation inconsistencies; numerical-curve impact unresolved without supplement. Does not establish reversal of Fig3 qualitative ordering. [S33 Published p144002-3, Eq7; paragraph defining Q; Eqs9–10 (PDFp4, visually checked)]

**Analysis — scope restriction.** RSQL assumes tightly packed cold atoms, optimized~1e8 atoms in1cm3, interaction shift cap1MHz; authors call ideal sensor likely physically unrealizable and note collective effects.1cm comparison is sensing region, not lasers/control/vacuum. Ideal sensitivity is model-dependent benchmark, not achieved performance or full-platform SWaP. [S33 pp144002-3–4; Fig3]

**Analysis — scope restriction.** Assumes equal dipole directivity3/2 and same external noise; both ideal curves below atmospheric background. Improvement requires appropriate external-noise regime; not a generic communications advantage. [S33 p144002-2 Eq1; p144002-4 Fig3]

**Verdict.** Useful benchmark, but two printed algebraic inconsistencies demand qualification before numerical ideal limits are reused. **Would resolve:** Author correction and static inspection of supplementary plot code; matched-bandwidth full-system experiments; feasible atom-density/decoherence validation.

## Verification and limits

Six IDs accounted for; consequential objections have original-source locators. Numerical S31 discrepancy checked by substitution; S33 inconsistencies derived directly from printed definitions, with page image confirmation. No claim of experimental refutation follows. Supplementary S33 code remains unavailable, so curve impact is unresolved. No independent replication search or raw-data reanalysis. S10 supplementary metadata are logged in the accompanying JSON.
