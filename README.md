# eSpray

!!!! WORK IN PROGRESS !!!!

Yet another ESPHome-based sprinkler controller..

## Features:

- 6 channel sprinkler controller
- Main valve control logic uses the native ESPHome sprinkler component (https://esphome.io/components/sprinkler.html)
- Touch screen with local control functions, feedback, and information (current state, date, Wi-Fi and HA connection status, etc.)
- High-quality industrial relay board based on ESP32-S3
- Configurable zone run times and scheduling from Home Assistant frontend
- Time setting via SNTP and API
- Edit weekly schedule on local touch interface (WIP)
- Integration with rain sensor and soil moisture probes (WIP)
- Home Assistant dashboard config (WIP)
- Nextion HMI file included (WIP)

## Components:

- Waveshare ESP32-S3 6ch relay board: https://www.waveshare.com/esp32-s3-relay-6ch.htm
- Nextion 2.8" HMI display: https://nextion.tech/discovery-series-introduction/
