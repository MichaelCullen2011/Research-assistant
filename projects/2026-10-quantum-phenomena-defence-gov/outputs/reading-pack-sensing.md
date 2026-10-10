# Reading pack: quantum sensing and quantum radar

*10 October 2026 · For getting up to speed before deciding where quantum radar sits. Every item is logged in `sources.md`.*

Read in order. Each part ends with what to take from it.

## 1. How quantum sensing works (start here)

| Read | Why | Time |
|---|---|---|
| Degen, Reinhard & Cappellaro, *Quantum sensing*, §II and Table I [S30] | Defines the three levels of quantum sensing: quantised energy levels, coherence, and entanglement. Only the third is "truly quantum". Table I maps each sensor type to the level it uses. | 45 min |
| Wright et al., *Cold atom inertial sensors for navigation*, §5–6 [S32] | A UK simulation showing what cold-atom sensors would do for an aircraft's inertial navigation: roughly halve the drift, not remove it. | 30 min |
| DARPA, *RoQS launches first phase* [S42] | Short. Explains why sensors that work in the lab are "notoriously fragile in real-world environments". | 5 min |

**Take-away:** every defence quantum sensor now in field trials uses the first two levels [S30 Table I][S41]. Entanglement is the hard, mostly lab-bound level.

## 2. What has actually been fielded

| Read | Why | Time |
|---|---|---|
| Roslund et al., *Optical clocks at sea* (abstract) [S37] | The strongest peer-reviewed field result: three optical clocks, 20 days on a ship. | 5 min |
| Stray et al., *Quantum sensing for gravity cartography* (abstract) [S31] | UK gravity sensor that found a buried tunnel in a static survey. | 5 min |
| CSIS, *Quantum Sensing and the Future of Warfare* [S99] | A grounded view of the near-term military payoff: "better cueing, more resilient navigation, and more persistent wide-area search". | 20 min |
| SIPRI, *Military and Security Dimensions of Quantum Technologies*, Box 4.2 [S123] | Why "quantum makes the oceans transparent" and "quantum radar kills stealth" keep recurring, and why the evidence does not back either. | 10 min |

## 3. Quantum radar: supporters and doubters

Read the supporters first, then the doubters. The two sides agree on the physics more than the headlines suggest.

| Side | Read | What it says |
|---|---|---|
| Supporter | Barzanjeh et al. 2020, abstract, introduction and discussion [S111] | Entangled microwaves found an object 1 m away. The receiver beat a classical noise radar but, by the authors' account, cannot beat the best classical radar. |
| Supporter | Assouly et al. 2023, abstract and conclusion [S112] | First measured advantage over the best possible classical radar: a factor of 1.2, inside a dilution refrigerator. The authors call practical use "a tremendous challenge". |
| Supporter | Torromé & Barzanjeh 2023, Conclusions [S114] | The supporters' review: "cautious optimism", with low signal power and cryogenics as the main hurdles. |
| Originator | Shapiro 2019, abstract and concluding remarks [S113] | The advantage is real in theory but "severely limited" in practice. |
| Doubter | Sorelli et al. 2020, §VI [S45] | Written for radar engineers with ONERA. The advantage appears only at powers 15–20 orders of magnitude below radar practice. |
| Doubter | Galati, Pavan & Daum 2025, abstract [S115] | Radar engineers argue the low transmitted power rules out real applications. |

## 4. What governments say and do

| Read | Position |
|---|---|
| CRS, *Defense Primer: Quantum Technology* [S93] | US Defense Science Board: quantum radar "will not provide upgraded capability to DOD". |
| UK written answer 113398 [S116] | UK MOD: quantum radar and quantum illumination are "immature"; research focuses on clocks and sensing for navigation and situational awareness. |
| MOD contract notice [S117] and Aquark release [S118] | The UK funds radar networks timed by cold-atom clocks; June 2026 trial reported by the vendor, no figures. |
| Birmingham EuRAD paper [S120] | Quantum-oscillator radar for drone detection; published results so far are a classical baseline. |

*Analysis:* "quantum radar" in policy writing can mean entanglement-based detection, which is lab-only, or classical radar improved by quantum clocks or receivers, which is in field trials. Before placing it in a band, check which one a source means.
