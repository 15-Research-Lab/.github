[![15 Research Lab: the physical layer.](https://www.15researchlab.com/github-banner.jpg)](https://www.15researchlab.com)

**A 1,200 square foot physical-layer shop being built in San Francisco.**
One operator, four service lanes. This account holds the design work and the
research artifacts.

> **Status: pre-commissioning.** Space and equipment are gated on funding.
> Everything below is design work and data that exists today. Nothing on the
> hardware side has been physically qualified yet, and where that is true it
> says so rather than being implied away.

## The four lanes

**Electronics and same-day PCBA.** Pick-and-place, hand and BGA rework, and a
test-and-measurement bench. Same-day board respins against the one-to-three-week
offshore loop, plus infrared scanning of a powered board to localise the part
dissipating more than it should.

**Robotics test.** Dynamometer axes, torque cells and an endurance station.
Torque against speed, thermal derating measured under the duty cycle you actually
intend to run, and backlash measured rather than quoted from a datasheet.

**Silicon and failure analysis.** Wire bonding, encapsulation removal,
cross-sectioning and lock-in thermography. Per-part pricing for the gap between
university cleanrooms that need badge access and OSAT vendors that need a lot
minimum.

**Instrumentation and ground truth.** Flash thermography, ultrasonically verified
reference defect panels, and an agent that operates the instrument and writes the
report. Built to produce labeled physical ground truth for machine-learning
evaluation, which is the part of the pipeline that is usually synthetic.

## What exists today

| Workstream | State | What it is |
| :--- | :--- | :--- |
| **Bench Node A2** | Digital prep complete | RP2040, USB-C, isolated RS-485, INA226, MAX31856, strain-gauge expansion, two protected outputs, isolated trigger I/O, hardware thermal inhibition. Editable KiCad, Gerbers, 141-part BOM and CPL, factory instructions, firmware and host tools. Factory acceptance and physical commissioning outstanding. |
| **Motor controller** | In progress | Four layers, 12 to 48 V, 40 A design target. RP2350, three-phase bridge, inline current sensing, CAN-FD / RS-485 / USB-C, encoder interfaces, independent hardware overcurrent and thermal shutdown. Revision D carries 392 source components against an original 150-part target, so cost and assembly need a separate evaluation. |
| **Shop layout** | Digital prep complete | Dimensioned 1,200 sqft plan: equipment placement, electrical schedule, ventilation, storage, ESD and receiving. Site and commissioning evidence outstanding. |
| **E-01 development kit** | Digital prep complete | Native parametric CAD, 49-row BOM, 28 reviewed drawing and manual pages. Fit, strength, cabling and calibrated trajectories unqualified; blocked configurations recorded rather than dropped. |
| **Dyno rig** | Digital prep complete | Mechanical CAD, guards, mounts, couplings, assembly and alignment package, acceptance checker. Motor interface adoption pending. |
| **Quality binder** | Digital prep complete | SOPs, calibration records, service procedures and qualification documentation. |
| **Synthetic thermography corpus** | Digital prep complete | Labeled simulated defect sequences plus evaluation methodology, built to be replaced by real-panel validation. Synthetic results retain their measured numerical and detection limits. |

## Published research

| | DOI |
| :--- | :--- |
| Grokking Has Finite Capacity | [10.5281/zenodo.19346536](https://doi.org/10.5281/zenodo.19346536) |
| Side-Channel Exfiltration and Narrative Erosion in Frontier Language Models | [10.5281/zenodo.19346069](https://doi.org/10.5281/zenodo.19346069) |
| The Verbosity Premium | [10.5281/zenodo.19346709](https://doi.org/10.5281/zenodo.19346709) |

Repositories on this account carry the machine-readable side of that work:
attack/alignment mappings and AI-control monitor evaluation harnesses.

## Rates

Every service rate is posted publicly, in advance, at
**[15researchlab.com](https://www.15researchlab.com/#prices)**. The counter is
not open yet; there is a waitlist.

---

San Francisco &middot; [15researchlab.com](https://www.15researchlab.com) &middot;
hello@15researchlab.com &middot; an [Authensor](https://www.authensor.com) initiative
