**Embodied AI safety.** Independent research in San Francisco into how AI systems sense, act and experiment in the physical world.

The central question is what we can trust an AI system to do when its tools can move, heat, sense or change something in the world. The work connects software, electronics, mechanisms and measurement in experiments whose outcomes can be checked.

## Research areas

- **Embodied AI safety:** authority, operating limits, observable outcomes, stopping behavior and recovery when an agent controls a physical device.
- **MHS testing:** Model Hardware Standard interfaces and related agent-to-instrument control patterns, including device state, units, permissions and acknowledgments.
- **Physical AI experimentation:** repeatable tasks in manipulation, measurement and autonomous science, compared with conventional baselines.
- **Frontier design:** new instruments, mechanisms, tactile systems, experimental electronics, materials and unconventional computing devices.

## Current stage

Design, software and simulation work are underway. The dedicated shop and physical commissioning are still being established. Software acknowledgments, simulated results and measured physical outcomes are different evidence, and each result here says which one it is. A research focus on MHS does not mean membership in a vendor research preview or a partnership.

## Hardware design work

| Workstream | State | What it is |
| :--- | :--- | :--- |
| **Bench Node A2** | Digital prep complete | RP2040, USB-C, isolated RS-485, INA226, MAX31856, strain-gauge expansion, two protected outputs, isolated trigger I/O, hardware thermal inhibition. Editable KiCad, Gerbers, 141-part BOM and CPL, factory instructions, firmware and host tools. Factory acceptance and physical commissioning outstanding. |
| **Motor controller** | In progress | Four layers, 12 to 48 V, 40 A design target. RP2350, three-phase bridge, inline current sensing, CAN-FD / RS-485 / USB-C, encoder interfaces, independent hardware overcurrent and thermal shutdown. |
| **E-01 development kit** | Digital prep complete | Native parametric CAD, 49-row BOM, 28 reviewed drawing and manual pages. Fit, strength, cabling and calibrated trajectories unqualified. |
| **Dyno rig** | Digital prep complete | Mechanical CAD, guards, mounts, couplings, assembly and alignment package, acceptance checker. Motor interface adoption pending. |
| **Synthetic thermography corpus** | Digital prep complete | Labeled simulated defect sequences plus evaluation methodology, built to be replaced by real-panel validation. |

## Published research

| | DOI |
| :--- | :--- |
| Grokking Has Finite Capacity | [10.5281/zenodo.19346536](https://doi.org/10.5281/zenodo.19346536) |
| Side-Channel Exfiltration and Narrative Erosion in Frontier Language Models | [10.5281/zenodo.19346069](https://doi.org/10.5281/zenodo.19346069) |
| The Verbosity Premium | [10.5281/zenodo.19346709](https://doi.org/10.5281/zenodo.19346709) |

---

San Francisco &middot; [15researchlab.com](https://www.15researchlab.com) &middot;
hello@15researchlab.com &middot; founded by [John Daniel Kearney](https://johndanielkearney.com)
