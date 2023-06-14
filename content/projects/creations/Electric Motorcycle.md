---
title: "Electric Motorcycle"
link: "https://github.com/colefuerth/ElectricMotorcycle"
image: "/img/electric_motorcycle/electric_bike_cover.jpg"
description: "Uses an Arduino to control a custom electric motorcycle. Safety features include a kill switch, brake light, and speedometer. Range estimation is provided by a custom algorithm that uses a current sensor and voltage sensor to estimate battery capacity. Electronics are completely custom, including a custom PCB and custom firmware."
featured: true
tags: ["Electric Vehicles", "PCB Development", "UART", "Power Electronics", "C++", "Arduino", "Firmware"]
fact: "Create a custom electric motorcycle from scratch."
weight: 100
sitemap: 
    priority : 0.8
---

- Programmed and assembled a fully electric dirt-bike from scratch.
- Assembled using an Arduino Mega for control with C++, a touchscreen display, custom aluminum panels, isolated inputs and outputs, and all-custom power distribution and analog sensing, mounted on a stripped frame.
- This project was my capstone for Electronics Engineering Technology.
- Features fully-fleshed out faults, including current, voltage, range, charging, and temperature faults.
- A fully-custom, hand-wired analog amplifier stack for telemetry. PCBs were designed and assembled by hand.
- A fully-custom, switching charging circuit. (note: I only had a 4S charger and this system runs at 24S, so a switching relay circuit changes the cell layout with the press of a button!)
- Safety features for over-current, over-voltage, over-temperature, and under-voltage. I also included a kill switch and brake light. A fallback control system was implemented, so if the Arduino or related control systems fail, the bike will still run.
- The killswitch was hard-wired to the main control relay, so if the switch is thrown, the bike will not run, *no matter what*.
- A Nextion touchscreen display with speed, telemetry, range estimation, faults, and all the normal indicators you would get on a motorcycle!
- Every single system on this bike was built by hand, from the ground-up!
- Range predictions can be made based on the remaining charge and the current session's usage history!
- Communication between the Arduino and the display is done over UART.
- RJ45 connectors are used for all data connections.
