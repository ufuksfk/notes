---
doc_type: hypothesis-highlights
url: >-
  https://docs.espressif.com/projects/esp-idf/en/stable/esp32s3/api-reference/peripherals/touch_pad.html
---

# Touch Sensor - ESP32-S3 - — ESP-IDF Programming Guide v5.2.1 documentation

## Metadata
- Author: [docs.espressif.com]()
- Title: Touch Sensor - ESP32-S3 - — ESP-IDF Programming Guide v5.2.1 documentation
- Reference: https://docs.espressif.com/projects/esp-idf/en/stable/esp32s3/api-reference/peripherals/touch_pad.html
- Category: #article

## Page Notes
## Highlights
- [[2024-03-07]] 21:45 The touch sensor records the period of time (i.e., the number of clock cycles) over a fixed charge/discharge cycles (specified by touch_pad_set_charge_discharge_times()). The count result is the raw data that read from touch_pad_read_raw_data(). After finishing one measurement, the touch sensor sleeps until the next measurement start, this interval between two measurements can be set by touch_pad_set_measurement_interval(). — [original](https://hyp.is/jTxzqtzDEe6kyb_MaEp6ag/docs.espressif.com/projects/esp-idf/en/stable/esp32s3/api-reference/peripherals/touch_pad.html)
    -   #esp32 
    - how esp32s3 measure touch sensor

- [[2024-03-07]] 21:45 to sense smaller capacity changes, it is possible to narrow down the reference voltage range within which the touch pads are charged/discharged. The high and low reference voltages are set using the function touch_pad_set_voltage(). — [original](https://hyp.is/o2Wa2tzDEe6vhl-7Yo0CDg/docs.espressif.com/projects/esp-idf/en/stable/esp32s3/api-reference/peripherals/touch_pad.html)


- [[2024-03-07]] 21:46 Besides the ability to discern smaller capacity changes, a positive side effect is reduction of power consumption for low power applications. A likely negative effect is an increase in measurement noise. If the dynamic range of obtained readings is still satisfactory, then further reduction of power consumption might be done by reducing the measurement time with touch_pad_set_charge_discharge_times(). — [original](https://hyp.is/tUuT2tzDEe6uDkdAqlS7pw/docs.espressif.com/projects/esp-idf/en/stable/esp32s3/api-reference/peripherals/touch_pad.html)
    - how to reduce power consumption

- [[2024-04-03]] 11:36 The touch pad sensing process is under the control of a hardware-implemented finite-state machine (FSM) which is initiated by software or a dedicated hardware timer. — [original](https://hyp.is/tF3-EPGdEe66ef9mYTAiQA/docs.espressif.com/projects/esp-idf/en/stable/esp32s3/api-reference/peripherals/touch_pad.html)




