# M5Stack Core S3 Esphome Home Assistant Voice Assistant Micro Wake Words detection

This directory contains an ESPHome configuration file tailored for the M5Stack Core S3, featuring support for on-device Micro Wake Words. The configuration allows the device to respond to wake words directly without the need for external services, enhancing responsiveness and reducing latency.

## Features

- **Micro Wake Words on Device**: The configuration supports wake words detection directly on the device, utilizing the capabilities of the ESP32-S3 chip.
- **Home Assistant Wake Words Pipeline**: A selection option has been added to choose between on-device wake words detection or using the Home Assistant pipeline for wake words processing.
- **Display Brightness Slider**: A slider has been added to control the display brightness directly from Home Assistant, allowing fine-tuned adjustments from 0% to 100%.
- **Fixed LCD Backlight Switch Issue**: The issue with the LCD backlight switch has been addressed, ensuring that the display correctly reflects the desired on/off state.
- **ESP-IDF Framework Compilation**: The configuration is fully compatible with the ESP-IDF framework, ensuring robust and reliable operation on the M5Stack Core S3.

## Acknowledgements

This configuration was made possible thanks to the repositories and contributions from:
- [M5CoreS3-Esphome](https://github.com/m5stack/M5CoreS3-Esphome) by [M5Stack](https://github.com/m5stack).
- [esphome_m5stack_core_s3](https://github.com/gnumpi/esphome_m5stack_core_s3) by [gnumpi](https://github.com/gnumpi).

Thank you for providing the necessary tools and resources to make this config-File.

