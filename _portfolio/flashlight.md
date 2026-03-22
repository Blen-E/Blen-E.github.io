---
title: "RGBW Flashlight System"
collection: portfolio
---

## Overview
Our project develops a programmable flashlight that is designed to be more versatile and functional than a standard flashlight. Unlike typical flashlights, this device allows for the user to adjust brightness levels, switch between multiple colors, operate in strobe mode as a stroboscope, and output morse code.
The goal of this flashlight is to create a compact, user-friendly tool that can adapt to different environments and needs, such as emergency situations, measuring rotating objects, outdoor activities, and general everyday use. By integrating programmable controls, the flashlight provides flexibility without needing multiple other devices. 
The current prototype represents the core features of the design, including adjustable brightness, selectable colors, and a strobe mode. One key strength of this design is its flexibility. While it already achieves its primary specifications, the programmability of this product allows for additional features to be incorporated in the future.

## Images

### Finished Flashlight
![Flashlight Photo](/images/flashlight/flashlight-photo.png)

<h3>Schematic Design</h3>

<div style="display: flex; gap: 20px;">

  <div style="flex: 1; text-align: center;">
    <img src="/images/flashlight/flashlight-schematic.png" width="100%">
    <p>Schematic </p>
  </div>

  <div style="flex: 1; text-align: center;">
    <img src="/images/flashlight/flashlight-schematic2.png" width="100%">
    <p>LED Driver Circuit</p>
  </div>

</div>

<h3>PCB Design</h3>

<div style="display: flex; gap: 20px;">

  <div style="flex: 1; text-align: center;">
    <img src="/images/flashlight/flashlight-layout.png" width="100%">
    <p>PCB Layout</p>
  </div>

  <div style="flex: 1; text-align: center;">
    <img src="/images/flashlight/flashlight-pcb.png" width="100%">
    <p>Assembled PCB</p>
  </div>

</div>

## Key Contributions
- Developed firmware in C for LED control  
- Implemented PWM signals for color mixing  
- Designed and Assempled PCBI
- Used Git for version control and collaboration of PCB

## Technical Details
- Language: C  
- Concepts: PWM, embedded systems, hardware-software integration  
- Components: XIAO ESP32 c6 microcontroller, RGBW LED, High power LED, OLED display  

## Project Link
[View on GitHub](https://github.com/psu-epl/mcu_flashlight)
