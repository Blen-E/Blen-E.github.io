---
title: "Flashlight Project"
collection: portfolio
excerpt: "Smart flashlight with mutliple LEDs, strobscope function, morse code output and more."
image: /images/flashlight/flashlight-photo.png

---

## Overview
This project is a programmable flashlight that is designed to be more versatile and functional than a standard flashlight. It was sponsored by the Electronics Prototyping Lab (EPL) at PSU and will be kept as lab equipment. Unlike typical flashlights, this device allows for the user to adjust brightness levels, switch between multiple colors, operate in strobe mode as a stroboscope, and output morse code. 
The goal of this flashlight is to create a compact, user-friendly tool that can adapt to different environments and needs, such as emergency situations, measuring rotating objects, outdoor activities, and general everyday use. By integrating programmable controls, the flashlight provides flexibility without needing multiple other devices. 
The current prototype represents the core features of the design, including adjustable brightness, selectable colors, and a strobe mode. One key strength of this design is its flexibility. While it already achieves its primary specifications, the programmability of this product allows for additional features to be incorporated in the future.

---

## Features
- Programmable 
- Battery Operatated
- RGBW and High Power LED
- Rechargable PCB
  - PCB consists of power switch, 5 LED driver circuits, 2 menu buttons, battery holder (back of board)
- OLED screen with various menu options: Strobescope function, Brightness control, variable flashing frequnecy, Morse code output, color mixing 

---

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
---
## L1 Block diagram
Power is supplied by a Li-ion battery (3.2-4.2 nominal V), which passes through a power switch to distribute power to the whole flashlight when switched on. The XIAO ESP32-C6 microcontroller receives input from the buttons and controls the OLED’s display menu interface for the user. The microcontroller generates PWM signals that turns the LED driver MOSFET on, and regulates current flow to turn the RGBW LEDs on. This allows the system to control brightness, flashing frequency, and color output of the flashlight. These components (LED drivers, microcontroller, battery holder) are integrated on a PCB that provides connections between each component.  
![Flashlight Photo](/images/flashlight/block-photo.png)

---

## Key Contributions
- Designed and assembled PCB using KiCAD
- Implemented color mixing function 
- Used Git for version control and collaboration of PCB

---

## Technical Details
- Language: C  
- Concepts: LED drivers, firmware, KiCAD, Audrino IDE
- Components: XIAO ESP32 c6 microcontroller, RGBW LED, High power LED, OLED display, PCB 


