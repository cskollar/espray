# eSpray

!!!!WORK IN PROGRESS!!!

Yet another ESPHome-based sprinkler controller..

## Features:

- 6 channel sprinkler controller
- main valve control logic uses Native ESPHome sprinkler component (https://esphome.io/components/sprinkler.html)
- touch screen with local control functions, feedback, and information (actual state, date, wifi and HA connection status, etc..)
- high-quality industrial relay board based on ESP32-S3
- configurable zone run times and scheduling from Home Assistant frontend
- setting time from SNTP
- using data from rain sensor and soil moisture probes (WIP)
- Home Assistant dashboard config (WIP)
- Nextion HMI file included (WIP)
- STL file for display bezel (WIP)

## Components:

Waveshare ESP32-S3 6ch relay board:
https://www.waveshare.com/esp32-s3-relay-6ch.htm

Nextion 2.8" HMI display:
https://nextion.tech/discovery-series-introduction/
