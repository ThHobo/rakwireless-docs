---
static_root: /assets/images/quick-start-guide/rak7243c/1.product-overview/1.index
rak_img: RAK7243C.svg
rak_grp: lora-gateway
params:
  qlinks:
    learnMore:
      - name: Projects
        href: https://www.hackster.io/search?q=RAK7243C&i=projects
      - name: Community
        href: https://forum.rakwireless.com/
      - name: Support
        href: mailto:fomi@rakwireless.com
    resources:
      - name: Datasheet
        href: /en-us/datasheet/rak7243c/#rak7243c-pilot-gateway
      - name: Assembly Guide
        href: http://docs.rakwireless.com/en/LoRa/Pilot-Gateway-Pro-RAK7243/Application-Notes/Pilot_Gateway_Pro_RAK7243_with_LTE_Assembly_Guide.pdf
      - name: Installation Guide
        href: http://docs.rakwireless.com/en/LoRa/Pilot-Gateway-Pro-RAK7243/Application-Notes/Pilot_Gateway_Pro_RAK7243_Installation_Guide_V1.0.pdf
      - name: Environment Test Report
        href: https://downloads.rakwireless.com/LoRa/Pilot-Gateway-Pro-RAK7243/Hardware-Specification/RAK7243_Environment_Test_Report.pdf
      - name: CE and FCC Certification Report
        href: https://downloads.rakwireless.com/LoRa/Pilot-Gateway-Pro-RAK7243/Certification-Report/
      - name: Firmware
        href: https://downloads.rakwireless.com/LoRa/Pilot-Gateway-Pro-RAK7243/Firmware/RAK7243C_Latest_Firmware.zip
      - name: Downloads
        href: https://downloads.rakwireless.com/LoRa/Pilot-Gateway-Pro-RAK7243/

---

# RAK7243C LPWAN Developer Gateway

<rk-img
  :src="`${$frontmatter.static_root}/1.pnebj6mub4bpzc83ehzw.jpg`"
  width="100%"
  figure-number="1"
  caption="RAK7243C LPWAN Developer Gateway"
/>

## Product Background

The **RAK7243C LPWAN** **Developer Gateway** is a complete and cost efficient Gateway Solution that will help you get started in developing a full LoRa System. It is built with the RAK2245 Pi Hat stacked with the Raspberry Pi 3B+ along with the GPS module and Heat Sink, increasing its performance and thermal dissipation, plus a RAK2013 Cellular Pi HAT for cellular connectivity. The housing for the device is durable and entirely built from aluminum.

The RAK7243C LPWAN Developer Gateway is ideal for prototyping, proof-of concept evaluation and demonstration. It includes everything you need to help you get started in building your own LoRaWAN® Network in just a couple of minutes. It provides great value and flexible functionality for a variety of applications: Smart Grids, Intelligent Farming and other IoT applications.

<rk-btn
  src="quick-start-guide.html"
  label="Set up Your RAK7243C LPWAN Developer Gateway"
/>

<rk-quick-links :params="$frontmatter.params.qlinks" />

## Product Features

- Pre-assembled, fully functioning Gateway
- SX1301 base band processor, emulates 49 x LoRa® demodulators 10 programmable parallel demodulation paths, support 8 uplinks channel, 1 downlink channel.
- Support optional Cellular module (Quectel BG96 or EG95) for NB-IOT / LTE CAT-M1 / LTE CAT1 / LTE CAT4.
- Built-in the Ublox MAX-7Q GPS Module.
- TX power up to 27dBm, RX sensitivity down to -139dBm@SF12, BW 125KHz.
- Full LoRa® Global bans support (EU433, CN470, IN865, EU868, US915, AU915, AS920, KR920, and AS923 ).
- Housing with top cover, body, bottom cover with riveted motherboard standoff (the top acts as a heat-sink).
- Includes Pi ready 'ID EEPROM', GPIO setup and device tree can be automatically configured from vendor information.

::: warning
 The RAK7243C LPWAN Developer Gateway is different from RAK7243 LPWAN Developer Gateway . The RAK7243C LPWAN Developer Gateway is the Cellular Version and it comes with the Cellular Pi Hat.
:::
