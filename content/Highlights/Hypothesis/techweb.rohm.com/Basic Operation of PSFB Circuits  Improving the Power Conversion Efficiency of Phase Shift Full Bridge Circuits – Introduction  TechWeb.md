---
doc_type: hypothesis-highlights
url: 'https://techweb.rohm.com/product/power-device/si/si-evaluation/9769/'
---

# Basic Operation of PSFB Circuits | Improving the Power Conversion Efficiency of Phase Shift Full Bridge Circuits – Introduction | TechWeb

## Metadata
- Author: [techweb.rohm.com]()
- Title: Basic Operation of PSFB Circuits | Improving the Power Conversion Efficiency of Phase Shift Full Bridge Circuits – Introduction | TechWeb
- Reference: https://techweb.rohm.com/product/power-device/si/si-evaluation/9769/
- Category: #article

## Page Notes
## Highlights
- [[2023-10-10]] 15:07 Below, operation and current paths for Modes (1) to (14) are described — [original](https://hyp.is/_fEJ2GdtEe6VNjeGzPDDfA/techweb.rohm.com/product/power-device/si/si-evaluation/9769/)
    -   #electronics/psfb 
    - how PSFB works step by step

- [[2023-10-10]] 15:10 Q2 turns on. At this time DQ2 is conducting, so the Q2 drain-source voltage VDS_Q2 is essentially zero. That is, ZVS operation is achieved, and so a turn-on loss does not occur — [original](https://hyp.is/ajXUtmduEe6cYwe-Ii_Aog/techweb.rohm.com/product/power-device/si/si-evaluation/9769/)
    -   #electronics/zvs 
    - how zvs achieved

- [[2023-10-10]] 15:23 Due to these changes in current paths, and as explained for Modes (7) and (14) in particular, the turn-on of a MOSFET in the lagging leg causes the input power supply and LS to be series-connected, and the energy in LS decreases rapidly. Because this action does not occur in the leading leg, differences occur in the current waveforms for the leading leg and the lagging leg as a result. Because of these differences in current waveforms, losses are different in the leading-leg MOSFETs and in the lagging-leg MOSFETs, and the amounts of heat generated are different, so care must be exercised in the thermal design. — [original](https://hyp.is/L9ivOmdwEe6pU1-goOKRbg/techweb.rohm.com/product/power-device/si/si-evaluation/9769/)
    - why lagging leg and leading leg has different heat.

- [[2023-10-10]] 15:25 As in the explanations of Modes (5) and (6) and Modes (12) and (13), in the lagging leg, if the amount of energy stored in LS is not greater than that stored in COSS for a MOSFET, the MOSFET charging and discharging are not completed, and so ZVS operation is not achieved. — [original](https://hyp.is/a4FgrmdwEe6HOcPiWh5ttw/techweb.rohm.com/product/power-device/si/si-evaluation/9769/)
    -   #electronics/zvs 
    - how to not achieve ZVS

- [[2023-10-10]] 15:30 From equation (1) we see that under light loading, IL1 is small, so that ZVS operation is not easily achieved, but as the load is increased ZVS operation is more easily realized. — [original](https://hyp.is/IYwCUGdxEe6O8t_TeSxxxw/techweb.rohm.com/product/power-device/si/si-evaluation/9769/)
    -   #electronics/zvs 
    - more load means easier ZVS



