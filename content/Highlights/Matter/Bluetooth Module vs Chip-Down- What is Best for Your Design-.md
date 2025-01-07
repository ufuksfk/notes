---
title: "Bluetooth Module vs Chip-Down: What is Best for Your Design?"
draft: false
creator: "[[Matt Dunham]]"
publisher: "[[punchthrough.com]]"
published_date: 2022-08-24
tags:
---


## Highlights
* [[2024-01-22]] 20:06  In addition to the costs of engineering and manufacturing efforts to convert to the new design, there’s also the cost and risk of EMC (Electro-magnetic Compliance) lab testing. A certified test lab will provide a quote for the testing and filings needed. A ballpark cost for this testing and filings will be roughly $20,000 for US (FCC) and Canada (ISED).

* [[2024-01-22]] 20:07  A shipping quantity of about 10,000 units annually is roughly the threshold where going “chip-down” starts to make sense, and it’s a “no-brainer” at volumes of 25k or more.

* [[2024-01-22]] 20:07  In comparison, the time to create a design using a pre-certified module in the first place (just for integrating the RF module, assuming nearly identical firmware), will be 4 to 8 weeks of design work and about $3,000 of FCC/ISED testing. In total, the design cycle will probably take about 4 months.

* [[2024-01-23]] 18:29  Your product, even without the radio, might have a noisy power supply or LCD data lines – among a host of other challenges. Adding a radio to that mix can compound and emphasize any EMC problems that product already has. Nonetheless, if your design has already passed EMC testing with a certified module, the chip-down design is relatively low-risk as long as you follow the RF chip manufacturer’s guidance carefully.

