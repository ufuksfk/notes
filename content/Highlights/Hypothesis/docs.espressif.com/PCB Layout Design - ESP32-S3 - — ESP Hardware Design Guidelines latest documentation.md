---
doc_type: hypothesis-highlights
url: >-
  https://docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32s3/pcb-layout-design.html
---

# PCB Layout Design - ESP32-S3 - — ESP Hardware Design Guidelines latest documentation

## Metadata
- Author: [docs.espressif.com]()
- Title: PCB Layout Design - ESP32-S3 - — ESP Hardware Design Guidelines latest documentation
- Reference: https://docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32s3/pcb-layout-design.html
- Category: #article

## Page Notes
## Highlights
- [[2024-03-13]] 09:48 Make sure there is a complete reference ground plane and surround the USB traces with ground copper. — [original](https://hyp.is/d9Nl0OEWEe67YbP7L1sR_g/docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32s3/pcb-layout-design.html)
    -   #esp32 
    - usb trace

- [[2024-03-13]] 09:52 If the PCB antenna cannot be placed outside the board, please ensure a clearance of at least 15 mm around the antenna area (no copper, routing, or components on it), and place the feed point of the antenna closest to the board — [original](https://hyp.is/9vQIkuEWEe6JZ5-Io38j1w/docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32s3/pcb-layout-design.html)
    -   #esp32 
    - how to cutout under antenna

- [[2024-03-13]] 09:53 The drill diameter on other power traces should be no smaller than the width of the power traces. — [original](https://hyp.is/OGbKsuEXEe644Icy2kXTQw/docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32s3/pcb-layout-design.html)


- [[2024-03-13]] 09:54 The ground pad at the bottom of the chip should be connected to the ground plane through at least nine ground vias. — [original](https://hyp.is/UYhvMuEXEe65PjvLe9RmFA/docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32s3/pcb-layout-design.html)


- [[2024-03-13]] 09:56 The width of the main power traces should be no less than 25 mil. The width of VDD3P3 power traces should be no less than 20 mil. The recommended width of other power traces is 10 mil. — [original](https://hyp.is/n5-xROEXEe65Qa_Aun-J9A/docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32s3/pcb-layout-design.html)
    -   #esp32 
    - power traces

- [[2024-03-13]] 09:59 The UART trace should be surrounded by ground copper and ground vias stitching. — [original](https://hyp.is/CXno3OEYEe6mewNWeKamGg/docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32s3/pcb-layout-design.html)


- [[2024-03-13]] 10:00 The trace length for SDIO_CMD and SDIO_DATA0 ~ SDIO_DATA3 should be 3 mil longer or shorter than the trace length for SDIO_CLK. If necessary, use serpentine routing. — [original](https://hyp.is/GEGAAOEYEe6dD0cntXwe4g/docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32s3/pcb-layout-design.html)


- [[2024-03-13]] 10:00 It is better to surround the SDIO_CLK trace with ground copper. — [original](https://hyp.is/H-s5uOEYEe6keTfMfzEaSA/docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32s3/pcb-layout-design.html)


- [[2024-03-13]] 10:05 The trace width (W) can not be larger than 0.18 mm (7 mil). — [original](https://hyp.is/46TRPuEYEe6cUVvfuLlRxg/docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32s3/pcb-layout-design.html)


- [[2024-03-13]] 10:08 Generally, the peak-to-peak value of the ripple should be <80 mV when ESP32-S3 sends MCS7@11n packets, and <120 mV when ESP32-S3 sends 11 MHz@11b packets. — [original](https://hyp.is/NWGIguEZEe6ovd-0JcZmjQ/docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32s3/pcb-layout-design.html)


- [[2024-03-13]] 10:09 Add a 10 μF filter capacitor to the branch of the power trace (the branch powering the chip’s analog power pin). The 10 μF capacitor should be as close to the analog power pin as possible for small and stable voltage ripples. — [original](https://hyp.is/UWqRIuEZEe6s9gsjjkbFCg/docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32s3/pcb-layout-design.html)
    - The voltage ripple is not large, but the TX performance of RF is rather poor

- [[2024-03-13]] 10:10 Good TX performance indicates proper RF impedance matching. Poor RX sensitivity may result from external coupling to the antenna. For instance, the crystal signal harmonics could couple to the antenna. If the TX and RX traces of UART cross over with RF trace, they will affect the RX performance, as well. If there are many high-frequency interference sources on the board, signal integrity should be considered. — [original](https://hyp.is/cQjRYOEZEe6EsLP3MbdECQ/docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32s3/pcb-layout-design.html)
    - TX performance is not bad, but the RX sensitivity is low.



