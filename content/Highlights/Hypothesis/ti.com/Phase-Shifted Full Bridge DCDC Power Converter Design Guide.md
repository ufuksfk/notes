---
doc_type: hypothesis-highlights
url: 'https://www.ti.com/lit/ug/tidu248/tidu248.pdf'
---

# Phase-Shifted Full Bridge DC/DC Power Converter Design Guide

## Metadata
- Author: [ti.com]()
- Title: Phase-Shifted Full Bridge DC/DC Power Converter Design Guide
- Reference: https://www.ti.com/lit/ug/tidu248/tidu248.pdf
- Category: #article

## Page Notes
## Highlights
- [[2023-10-10]] 13:46 Figure 1 shows a simplified circuit of a phase shifted full bridge. MOSFET switches QA, QB, QC and QDform the full-bridge on the primary side of the transformer T1. QA and QB are switched at 50 % duty and180 degree out of phase with each other. Similarly, QC and QD are switched at 50 % duty and 180degree out of phase with each other. The PWM switching signals for leg QC – QD of the full bridge arephase shifted with respect to those for leg QA - QB. Amount of this phase shift decides the amount ofoverlap between diagonal switches, which in turn decides the amount of energy transferred. D1, D2provide diode current doubler rectification on the secondary, while Lo and Co form the output filter.Inductor LR provides assistance to the transformer leakage inductance for resonance operation withMOSFET capacitance and facilitates Zero Voltage Switching (ZVS). Note the two different grounds G1and G2 on the two sides of transformer T1. Figure 2 provides the switching waveforms for the system inFigure 1. — [original](https://hyp.is/nGmRDmdiEe6pMtNV2_BzpQ/www.ti.com/lit/ug/tidu248/tidu248.pdf)


- [[2023-10-10]] 13:52 Implementing PCMC for a PSFB system requires complex PWM waveform generation with precise timingcontrol. The Piccolo family of devices from Texas Instruments feature advanced on-chip controlperipherals that make this implementation possible without any external support circuitry for this purpose. — [original](https://hyp.is/hV2PoGdjEe6R4nPAQAmfog/www.ti.com/lit/ug/tidu248/tidu248.pdf)


- [[2023-10-10]] 14:05 For the system discussed here, switching transitions for switches in the Q2- Q3 leg end the power transferinterval. Therefore this leg is called the ‘Active to Passive’ leg. — [original](https://hyp.is/Q5xurmdlEe6KVWN5q5oazQ/www.ti.com/lit/ug/tidu248/tidu248.pdf)
    - active to passive leg in h-bridge

- [[2023-10-10]] 14:05 Switching transitions for switches in the Q1- Q4 leg start the power transfer interval. Therefore this leg iscalled the ‘Passive to Active’ leg. — [original](https://hyp.is/S-DVFGdlEe6WN4NbV_g1FQ/www.ti.com/lit/ug/tidu248/tidu248.pdf)
    - passive to active leg in h-bridge



