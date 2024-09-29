# ets
<!-- [![GitHub release (latest by date)](https://img.shields.io/github/v/release/jnasholm/ets)](https://github.com/jnasholm/ets/releases) -->
<!-- ![GitHub last commit](https://img.shields.io/github/last-commit/jnasholm/ets) -->

# ESP32 External Temperature Sensor

Project to create a smart external temperature sensor for private homes. Brief project description:

- The controller is an [ESP32](https://www.olimex.com/Products/IoT/ESP32/ESP32-DevKit-LiPo/open-source-hardware) programmed with [ESPHome](https://esphome.io/).
- The temperature sensor is a digital [DS18B20](https://www.stg-maximintegrated.com/en/products/sensors/DS18B20.html) in an IP65 enclosure from [Energibutiken](https://www.energibutiken.se/sv/dallas-1-wire-givare/24-dallas-1-wire-pro-utegivare-02002.html).
- Integration with [Home Assistant](https://www.home-assistant.io/) is recommende. Sensor data and configuration parameters can be imported to operate the controller.
- Direct communication between ESP nodes through the network broadcast [UDP Component](https://esphome.io/components/udp) in ESPHome from version 2024.9.

> [!TIP]
> The external temperature sensor is recommended for: [ESP32 SSR Mixing valve actuator controller](https://github.com/jnasholm/mvc-pwm)

## Prototype

![Prototype on experiment board](/images/prototype-experimentboard_1.png)
<br>
*Prototype wired on experiment board.*

![Prototype on experiment board](/images/prototype-experimentboard_2.png)
<br>
*Prototype wired on experiment board with battery.*

![Prototype in enclosure](/images/prototype-enclosure_1.png)
<br>
*Prototype in enclosure with status LEDs and running on battery power.*

![Prototype installed](/images/prototype-installed_1.png)
<br>
*Prototype installed in DIN rail connection cabinet with a 5V DC power supply.*
