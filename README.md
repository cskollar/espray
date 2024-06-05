# eSpray

Yet another ESPHome-based sprinkler controller...

## Features:

- 6 channel sprinkler controller
- Main valve control logic uses the native ESPHome sprinkler component (https://esphome.io/components/sprinkler.html)
- Touch screen with local control functions, feedback, and information (current state, date, Wi-Fi and HA connection status, etc.)
- High-quality industrial relay board based on ESP32-S3
- Configurable zone run times and scheduling from Home Assistant frontend
- Time setting via SNTP
- Edit weekly schedule on local touch interface (WIP)
- Integration with rain sensor and soil moisture probes (WIP)
- Home Assistant dashboard template (WIP)

## Components:

- Waveshare ESP32-S3 6ch relay board: https://www.waveshare.com/esp32-s3-relay-6ch.htm
- Nextion 2.8" HMI display: https://nextion.tech/discovery-series-introduction/

![Screenshot 2024-06-05 at 11 51 42](https://github.com/cskollar/espray/assets/46558488/37aac64f-19b2-465a-9cee-0cacaab574dc)

## Installation:

- Flash the nextion_espray.hmi file to the Nextion display using Nextion Editor
- Connect the display to the relay board (GPIO17, GPIO18, GND, 5V). Be careful, the UART on the display is very sensitive to incorrect wiring!
- Change the passwords (WiFi, API, OTA) in espray.yaml
- Run `esphome run espray.yaml`

