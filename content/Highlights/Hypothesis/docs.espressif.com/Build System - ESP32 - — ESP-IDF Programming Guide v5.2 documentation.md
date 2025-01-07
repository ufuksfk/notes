---
doc_type: hypothesis-highlights
url: >-
  https://docs.espressif.com/projects/esp-idf/en/stable/esp32/api-guides/build-system.html
---

# Build System - ESP32 - — ESP-IDF Programming Guide v5.2 documentation

## Metadata
- Author: [docs.espressif.com]()
- Title: Build System - ESP32 - — ESP-IDF Programming Guide v5.2 documentation
- Reference: https://docs.espressif.com/projects/esp-idf/en/stable/esp32/api-guides/build-system.html
- Category: #article

## Page Notes
## Highlights
- [[2024-02-26]] 16:58 CMake will usually handle circular dependencies automatically by repeating the component library names twice on the linker command line. However this strategy doesn't always work, and the build may fail with a linker error about "Undefined reference to ...", referencing a symbol defined by one of the components inside the circular dependency. This is particularly likely if there is a large circular dependency, i.e., A > B > C > D > A. — [original](https://hyp.is/1FSrYNS_Ee6QlveWNii12Q/docs.espressif.com/projects/esp-idf/en/stable/esp32/api-guides/build-system.html)




