---
static_root: /assets/images/quick-start-guide/rak4200-breakout/main
rak_img: RAK4200-breakout.png
rak_grp: lora-node
params:
  qlinks1:
    learnMore:
      - name: Projects
        href: https://www.hackster.io/search?q=rak4200&i=projects
      - name: Community
        href: https://forum.rakwireless.com
      - name: Support
        href: mailto:fomi@rakwireless.com
    resources:
      - name: Datasheet
        href: /en-us/datasheet/rak4200-breakout-module/#rak4200-breakout-module
      - name: Schematic Diagram
        href: /en-us/datasheet/rak4200-breakout-module/#schematic-diagram
      - name: CE Certification Report
        href: https://downloads.rakwireless.com/LoRa/RAK4200/Certification-Report/
      - name: Firmware
        href: https://downloads.rakwireless.com/en/LoRa/RAK4200/Firmware/
      - name: Downloads
        href: https://downloads.rakwireless.com/LoRa/RAK4200/
---

# RAK4200 LPWAN Breakout Module

<rk-img
  :src="`${$frontmatter.static_root}/peojuzuyfj5wzl51igyk.jpg`"
  width="50%"
  figure-number="1"
  caption="RAK4200 LPWAN Breakout Module"
/>

## Product Description

The **RAK4200 Breakout Module** is specifically designed to allow easy excess to the pins on the module in order to simplify development and testing. The breakout board utilized is of an **Xbee form factor** and its main purpose is to allow the RAK4200 stamp module form factor pin-out to be transferred to 2.54mm headers. 

The module itself has the RAK4200 at its core, integrating an **STM32L071 MCU and a SX1276 LoRa® chip**. It has Ultra-Low Power Consumption of 1.5 uA in sleep mode, high LoRa® max output power at 19 dBm in work mode. 

The module complies with **LoRaWAN® 1.0.2 protocols**. It also supports Lora® Point to Point (P2P) communication. The RF communication capabilities of the module make it suitable for a variety of applications in the IoT field such as home automation, sensor networks, building automation, personal area networks applications (health/fitness sensors and monitors, etc.).

<rk-btn
  src="prerequisites.html"
  label="Set up Your RAK4200 LPWAN Evaluation Board"
/>

<rk-quick-links :params="$page.frontmatter.params.qlinks1" />

## Product Features

- LPWAN module for Smart City, Smart Agriculture, Smart Industry 
- I/O ports: **UART/I2C/GPIO**
- Temperature range: -40°C to +85°C 
- Frequency range: 863–870MHz (EU) / 902–928MHz (US), ISM and SRD systems 
- Low-Power Wireless Systems with 7.8kHz to 500KHz Bandwidth 
- Core: ARM 32-bit Cortex - M0+ with MPU 
- Up to 128KB flash memory with ECC 
- 20KB RAM

