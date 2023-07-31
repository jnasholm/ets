# ets
<!-- [![GitHub release (latest by date)](https://img.shields.io/github/v/release/jnasholm/ets)](https://github.com/jnasholm/ets/releases) -->
<!-- ![GitHub last commit](https://img.shields.io/github/last-commit/jnasholm/ets) -->

# ESP32 External Temperature Sensor

Project to create a smart external temperature sensor for private homes. Brief project description:

- The controller is an [ESP32](https://www.olimex.com/Products/IoT/ESP32/ESP32-DevKit-LiPo/open-source-hardware) programmed with [ESPHome](https://esphome.io/).
- The temperature sensor is a digital DS18B20 in an IP65 enclosure from [Energibutiken](https://www.energibutiken.se/sv/dallas-1-wire-givare/24-dallas-1-wire-pro-utegivare-02002.html) 
- Integration with [Home Assistant](https://www.home-assistant.io/) is recommende. Sensor data and configuration parameters can be imported to operate the controller.
