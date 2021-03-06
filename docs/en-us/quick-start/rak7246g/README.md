---
static_root: /assets/images/quick-start-guide/rak7246
rak_img: rak7246.png
rak_grp: lora-gateway
params:
  qlinks1:
    learnMore:
      - name: Projects
        href: https://www.hackster.io/search?i=projects&q=rak7246g
      - name: Community
        href: https://forum.rakwireless.com
      - name: Support
        href: mailto:fomi@rakwireless.com
    resources:
      - name: Datasheet
        href: /en-us/datasheet/rak7246g/#rak7246g-lpwan-developer-gateway
      - name: Environment Test Report
        href: https://downloads.rakwireless.com/LoRa/NeoPi-Gateway-RAK7246/Hardware_Specification/RAK7246G_Environment_Test_Report.pdf
      - name: Firmware
        href: https://downloads.rakwireless.com/LoRa/NeoPi-Gateway-RAK7246/Firmware/RAK7246_Latest_Firmware.zip 
      - name: Downloads
        href: https://downloads.rakwireless.com/LoRa/NeoPi-Gateway-RAK7246/
---

# RAK7246G LPWAN Developer Gateway

<rk-img
  :src="`${$frontmatter.static_root}/rak7246.jpg`"
  width="100%"
  figure-number="1"
  caption="RAK7246G LPWAN Developer Gateway"
/>

## Product Background

The **RAK7246G** is an LPWAN Developer Gateway with GPS function. It is a device composed of a the **RAK2246 Pi HAT LPWAN Concentrator** module and **Raspberry Pi Zero W**.

The RAK2246 Pi HAT is based on a **Semtech SX1308** chip, which allows for simultaneous reception over 8 LoRa® channels, which cover the entirety of the international high-frequency LoRaWAN® space.

The RAK7246G LPWAN Developer Gateway is an ideal choice for prototype design, concept verification and demonstrations, development evaluation and other scenarios. It is developer-friendly due to its minimalistic design that reduces cost and allows for easily accessing the internals. It is easy to set-up, which makes it a good choice for both experienced and novice LoRa® specialists.

<rk-btn
  src="quick-start-guide.html"
  label="Set up Your RAK7246G LPWAN Developer Gateway"
/>

<rk-quick-links :params="$page.frontmatter.params.qlinks1" />

## Product Features

- Using SX1308 baseband processor, full 8 uplink channels and 1 downlink channel Gateway;
- The Pre-installed radiator guarantees the stable thermal performance
- Tx max 20dbm, Rx min -139dbm @ SF12 at 125kHz;
- Covers the entirety of the LoRa® high-frequency band space: RU864, IN865, EU868, US915, AU915, KR920, AS923;
- Power supply 5V / 2.5A (power adapter sold separately).
