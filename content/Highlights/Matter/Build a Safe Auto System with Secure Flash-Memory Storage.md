---
title: "Build a Safe Auto System with Secure Flash-Memory Storage"
draft: false
creator: "[[Zhi Feng]]"
publisher: "[[electronicdesign.com]]"
published_date: 2019-07-23
tags:
---
publisher: "[[electronicdesign.com]]"


## Highlights
* [[2024-01-19]] 13:32  Non-volatile flash memories are essential in all of these embedded systems.

* [[2024-01-19]] 13:34  Flash-memory vendors have been providing pure data storage for many years. For these applications, endurance and retention are the two main measures for the quality of flash memories. Security isn’t a part of these flash devices, meaning that data on the flash either isn’t protected at all or protected with commands that have no authentication.

* [[2024-01-19]] 13:34  If attackers can access the bus interface of the flash device, they can easily extract or modify data on the device.

* [[2024-01-19]] 13:36  Another type of MIM attack is to replay an intercepted legitimate message after a certain time. To prevent replay attacks, the host and the flash device must use a monotonic counter—whose value is incremented upon every message—to generate the MAC. Therefore, if the same message is replayed, the MAC verification will not pass because the current monotonic counter value would have been different from the previous message.

* [[2024-01-19]] 13:38  The UDS can be used to derive a compound device identifier (CDI) that’s the basis for generating a Device ID Certificate as defined in the TCG (Trusted Computing Group) DICE (Device Identifier Composition Engine) specification. Typically, the device also generates an Alias Private and Public key pair based on the CDI for all key derivations with the host. As a result, the Device ID private key needn’t be exposed. With the UDS and the DICE processes, it’s impossible for hackers to clone the device because the UDS is physically unclonable.

* [[2024-01-19]] 13:40  In modern multicore embedded systems, multiple MCUs or HSMs (hardware secure module) may have access to the same flash storage. It’s desirable for the flash device to provide a flexible memory structure that can be partitioned and provisioned so that different regions are manageable via different cores. These different regions can provide different levels of security, or no security at all if not needed.

* [[2024-01-19]] 13:42  However, to boot up securely, the entire bootloader code needs to be checked and authenticated to make sure that it’s trustworthy. This process requires time on the MCU. A secure flash storage that can provide boot load authentication will substantially help shorten boot time.

* [[2024-01-19]] 13:43  Provide secure firmware over-the-air (FOTA) update

