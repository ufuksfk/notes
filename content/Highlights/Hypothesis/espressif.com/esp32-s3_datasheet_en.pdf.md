---
doc_type: hypothesis-highlights
url: >-
  https://www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf
---

# esp32-s3_datasheet_en.pdf

## Metadata
- Author: [espressif.com]()
- Title: esp32-s3_datasheet_en.pdf
- Reference: https://www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf
- Category: #article

## Page Notes
## Highlights
- [[2024-03-05]] 22:09 The functional block diagram of the SoC is shown below. — [original](https://hyp.is/nVgz6ts0Ee6U6UvUc9PnEQ/www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf)
    - first check this page

- [[2024-03-05]] 22:18 CoreMark® score:– 1 core at 240 MHz: 613.86 CoreMark; 2.56CoreMark/MHz — [original](https://hyp.is/1bfG5ts1Ee6OIR_j4ug9OQ/www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf)
    - https://www.eembc.org/coremark/

- [[2024-03-05]] 22:19 – ULP-RISC-V coprocessor– ULP-FSM coprocessor — [original](https://hyp.is/-2lymts1Ee6t1TcP3kNB2w/www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf)
    - They are 2 ULP coprocessor?

- [[2024-03-05]] 22:19 Cryptographic hardware acceleration:– AES-128/256 (FIPS PUB 197)– Hash (FIPS PUB 180-4)– RSA– Random Number Generator (RNG)– HMAC– Digital signature — [original](https://hyp.is/FyeyEts2Ee6JFqsZtNfgCg/www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf)
    - learn more about that part

- [[2024-03-05]] 22:23 In Table 2-3 IO MUX and GPIO Pin Functions and Table 2-4 RTC and Analog Pin Functions some pin functions arehighlighted . The non-highlighted GPIO or RTC_GPIO pins are recommended for use first. If more pins areneeded, the highlighted GPIOs or RTC_GPIOs should be chosen carefully to avoid conflicts with important pinfunctions. — [original](https://hyp.is/kxbM-ts2Ee6x7L-UC-sX7Q/www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf)
    - how to choose pinout

- [[2024-03-05]] 22:24 VDD3P3_RTC Input RTC and part of Digital power domains — [original](https://hyp.is/sVhJPNs2Ee6tNXscXAC46A/www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf)
    - we need to use this to have RTC on while shutdown all other peripherals

- [[2024-03-05]] 22:27 VDD3P3_RTC 2 Recommended input voltage 3.0 3.3 3.6 V — [original](https://hyp.is/EEFpGts3Ee6JHsNQ54PagQ/www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf)
    - But RTC voltage has 3.6V absolute maximum

- [[2024-04-02]] 10:59 Only RTC is powered on. Wireless connection data is stored in RTC memory. — [original](https://hyp.is/SOX0XvDPEe6422cYf5e4Mw/www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf)




