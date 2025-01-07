---
doc_type: hypothesis-highlights
url: 'https://github.com/espressif/esp-idf/tree/master/examples/system/ota'
---

# esp-idf/examples/system/ota at master · espressif/esp-idf

## Metadata
- Author: [github.com]()
- Title: esp-idf/examples/system/ota at master · espressif/esp-idf
- Reference: https://github.com/espressif/esp-idf/tree/master/examples/system/ota
- Category: #article

## Page Notes
## Highlights
- [[2024-02-21]] 15:33 The ESP-IDF offers two methods to perform Over The Air (OTA) upgrades: Using the native APIs provided by the app_update component. Using simplified APIs provided by the esp_https_ota component, which provides functionality to upgrade over HTTPS. — [original](https://hyp.is/NsfZHtDGEe6PpHOsMTQZuQ/github.com/espressif/esp-idf/tree/master/examples/system/ota)


- [[2024-02-21]] 15:40 If you want to rollback to the factory app after the upgrade (or to the first OTA partition in case the factory partition does not exist), run the command idf.py erase_otadata. This restores the ota_data partition to its initial state. — [original](https://hyp.is/Nz8TetDHEe6YSJOA7ULwJA/github.com/espressif/esp-idf/tree/master/examples/system/ota)


- [[2024-02-21]] 15:43 Make sure to run "idf.py erase-flash" after making changes to the partition table. — [original](https://hyp.is/pXyQENDHEe6Pj4N4IpA07A/github.com/espressif/esp-idf/tree/master/examples/system/ota)




