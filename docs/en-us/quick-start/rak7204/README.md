---
static_root: /assets/images/quick-start-guide/rak7204/1.overview
rak_img: RAK7204.svg
rak_grp: lora-node
params:
  qlinks:
    learnMore:
      - name: Projects
        href: https://www.hackster.io/search?i=projects&q=RAK7204
      - name: Community
        href: https://forum.rakwireless.com/
      - name: Support
        href: mailto:fomi@rakwireless.com
    resources:
      - name: Datasheet
        href: /en-us/datasheet/rak7204/#rak7204-lpwan-environmental-sensor
      - name: Firmware
        href : https://downloads.rakwireless.com/LoRa/RAK7204/Firmware/
      - name: Downloads
        href: https://downloads.rakwireless.com/LoRa/RAK7204/
---

# RAK7204 LPWAN Environmental Sensor

<rk-img
  :src="`${$frontmatter.static_root}/nwvusdulqxqcp5blomrd.jpg`"
  width="60%"
  figure-number="1"
  caption="RAK7204 Product Overview"
/>

## Product Background

The RAK7204 is an LPWAN node with integrated environmental sensors. The high-precision environmental sensors, can measure changes in temperature, humidity, gas pressure and provide an indoor air quality index. All the accumulated data can be send to a gateway in order for it to be forwarded to the Cloud.

The environmental sensors, LoRa® transceiver module, LoRa® antenna, and the battery are fitted in a 90 mm x 85 mm x 34 mm sized housing. These small dimensions allow for installation in tight spaces or ones that require the sensor to have a minimal impact on the overall feel of the surrounding environment. The housing adopts a hollow, permeable design to facilitate air flow in order to more accurately detect the environmental changes.

<rk-btn
  src="prerequisites.html"
  label="Set up Your RAK7204 LPWAN Environmental Sensor"
/>

<rk-quick-links :params="$frontmatter.params.qlinks" />

## Product Features

- Measurement of a variety of environmental parameters: **Temperature**, **Humidity**, **Gas Pressure** and **Indoor Air Quality (IAQ)**
- **BOSCH BME680** Integrated Environmental Unit
- **LoRaWAN® 1.0.2** fully compliant
- Low power operation and standby current of less than 15 uA
- Adjustable sampling and transmission interval.
- Comes with a replaceable 3500 mAh high capacity lithium battery
- Real time battery status monitoring.
- **Battery life of more than 2 years** (At 15 minute data transmission interval)
- Compact in size, easy to install and maintain.
