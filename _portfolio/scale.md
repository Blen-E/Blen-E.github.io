---
title: "Smart Bathroom weight scale"
collection: portfolio
excerpt: "A smart bathroom weight scale"
image: /images/scale/scale-photo.png

---
## Overview
This project was inspired by [Wi-Fi smart scale project](https://www.instructables.com/Wi-Fi-Smart-Scale-with-ESP8266-Arduino-IDE-Adafrui/) and is essentially a bathroom weight scale. At the core of this project, an ESP8266 to drive the scale. Weight is read from load cells that utilize a force-sensing component that’s converted to an electrical signal. The microcontroller connects to an HX711 module that interprets/reads the signals from the load cells and sends them to the ESP8266. The interpreted data is then displayed on an LCD as weight in pounds. 

---

## Features
- Programmable 
- 4 loads cells and HX711 Amplifer
- ESP8266 Microcontroller
- Plywood base 
- Displays accurate weight on LCD screen
- Scale zero's out when weight is removed
- Can be calibrated

---
### Schematic 
![Load Cells →  HX711 Amplifier →  ESP8266 →  LCD display](/images/scale/scale-sch.png)

---
### Weight Scale
![Weight Scale Photo](/images/scale/scale-photo.png)

