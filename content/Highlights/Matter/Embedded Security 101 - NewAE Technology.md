---
title: "Embedded Security 101 | NewAE Technology"
draft: false
creator: "[[DISTRIBUTOR Request Quotes]]"
publisher: "[[newae.com]]"
tags:
---
publisher: "[[newae.com]]"


## Highlights
* [[2024-01-21]] 13:40  This attack takes advantage of a small piece of information — how the data being processed by a system affects the power consumption of that system. This allows us to break advanced cryptography systems, such as recovering an AES-256 key in a matter of minutes. These attacks do not rely on substantial resources; they can be performed with commodity hardware and for less than $50.

* [[2024-01-21]] 13:42  A password of ADBC would entail only going through the sequence of “A/A..B..C..D/A..B../A..B…C” to find the correct password because once the correct letter is found for the first digit, the guess algorithm can move onto the next.

* [[2024-01-21]] 13:46  This works by taking advantage of the fact that changing the internal data bus is equivalent to charging or discharging a capacitor. Setting two data bits on the bus to ‘1’ takes more power than setting one data bit on the bus to ‘1’. This is not just a theoretical consideration

* [[2024-01-21]] 13:52  Fault injection typically allows us to achieve this. There are many ways of performing it — the most common are clock glitching, voltage glitching, and electromagnetic fault injection (EMFI).

* [[2024-01-21]] 13:52  Clock glitching relies on inserting very narrow clock edges near the “actual” clock edge (see Figure 6). These clock edges cause setup & hold times to be violated internally, which allows incorrect data to be propagated through the system.

* [[2024-01-21]] 13:58  irst, many devices have error detection circuitry that can be enabled. Ensuring exceptions on clock instability and memory corruption get caught and logged can be useful in reducing an attack success rate. The use of multiple checks complicates many fault injection attacks. Rather than performing a single, basic comparison, one can perform the comparison multiple times.

* [[2024-01-21]] 13:58  Comparing to a “true” value in C is highly vulnerable to fault injection because any corruption of that register — which results in a non-zero value being loaded — will result in a successful attack.

* [[2024-01-21]] 13:59  The control endpoint never needed to transfer such large information back, so a mask could have been applied to limit the return data size to 256 bytes or similar.

* [[2024-01-21]] 14:01  Another protection against memory dumping would have been to use the memory management/protection unit (depending on device), and have “trap” memory sections. These traps exist around sensitive data, or at least after sections of data that are returned to a user. A buffer over-read will run into a trap and trigger this protection.

