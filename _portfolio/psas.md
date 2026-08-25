---
title: "Portland State Aerospace Society (PSAS)"
excerpt: "Contributed to the development of an open-source CubeSat as part of the Portland State Aerospace Society (PSAS).My work focuses on embedded systems, firmware development, and PCB design in a interdisciplinary splinary engineering environment."
image: /images/psas/oresat.png
collection: portfolio
---
<a href="/portfolio/" class="back-button">← Back to Projects</a>

## Overview
I work in the firmware and electrical teams contributing to the development of an open-source CubeSat as part of the Portland State Aerospace Society (PSAS). The Portland State Aerospace Society (PSAS) is an interdisciplinary student group that designs, builds and flies ultra-low-cost and totally open source rockets, liquid-fuel rocket engines, satellites, and satellite ground stations. My work focused on embedded systems, flight software concepts, and hardware development in a collaborative engineering environment.


## Summer Undergraduate Research 

### Overview
Participated in undergraduate research at PSAS researching the Zephyr RTOS to program the NXP MCXN947 dev board. The MCU of this dev board would then be integrated on multiple cards of the next CubeSat project, Oresat1. I presented this research at the PSU undergraduare research Sypnosium. 

### Contributions
- Testing debugger compatability (Jlink, STlink debugger) with MCXN947 board 
- Debugging, testing, and writing applications on NXP MCXN947 microcontroller using Zephyr RTOS
- Wrote hardware descriptions, board- specific configurations, and system configuration files to build and flash applications for the OreSat1 breakout board, part of the PSAS open- source CubeSat project.


### Skills Learned
- Debugging embedded systems across hardware and firmware
- Working with the Linux kernal    
- The role of RTOS in embedded systems
- PCB design 

### Poster
![Research Poster](/images/psas/undergradresearch.png)

---

## FlatSat Breakout board project

### Overview
A "flatSat" is a an flat or open satellite that allows you to conduct system integration, software development, testing, and debugging. I worked on schematic and PCB layout of the flatsat breakout board, a board that connects various flatsat boards together. 

### Contributions
- Schematic and PCB layout
- Research on OreSat connectors
- Documentation via git
  
<h3>Schematic and PCB design</h3>

<div style="text-align: center;">

  <div style="margin-bottom: 30px;">
    <img src="/images/psas/flatsat-schematic1.png" width="80%">
    <p>Schematic</p>
  </div>

 <div>
    <img src="/images/psas/flatsat-pcb.png" width="30%">
    <p>PCB final design</p>
  </div>

</div>

---

## Zephyr RTOS Power Management implementation for CubSat project, OreSat1  

### Overview
This research investigates how Zephyr RTOS power-management strategies can reduce energy consumption in embedded systems, with the goal of improving the efficiency and reliability of power-constrained aerospace applications such as the CubeSat project OreSat1. 

### Contributions
- Researching low-power optimization of Zephyr RTOS for embedded systems and aerospace applications using the NXP MCXN947 microcontroller.
Characterizing power consumption across MCU power modes using a Joulescope to measure current draw, sleep-state behavior, and wake-up transitions.
- Investigating Zephyr System Power Management and Device Power Management to understand how the operating system manages the MCU and individual peripherals during low-power operation.
Analyzing peripheral and clock behavior to identify sources of power consumption and determine how peripherals can be disabled or clock-gated during sleep.
- Developing and testing low-power embedded applications that enter sleep states, wake on timers, and measure the energy costs associated with power-state transitions.
- Developing this research into an Honors Thesis and future technical publications, including conference and research work.
