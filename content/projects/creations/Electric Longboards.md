---
title: "Electric Longboard"
# link: "https://github.com/colefuerth/ElectricMotorcycle"
image: "/img/electric_boards/IMG_20210617_211804.jpg"
description: "Custom electric longboards with telemetry, logging, and more. Open-source ESC, dual drive, custom longboard deck, and hand-assembled batteries are the notable features. Assembling batteries by hand is very time-consuming, but is a third the cost of pre-assembled cells. ~30km range (in summertime). Telemetry and logging, speed limiting, current control, range estimation, total draw, and more are tracked by the controller and displayed on an LCD screen on the hand-held remote."
featured: true
tags: ["CAN & UART", "Battery Management Systems", "Data Collection", "Power Electronics"]
fact: "This was later used as a data collection platform for the University of Windsor's BMSLabs team!"
weight: 50
sitemap: 
    priority : 0.8
---

![electric board](/img/electric_boards/IMG_20210702_203611.jpg)

### Summary

Custom electric longboards with telemetry, logging, and more. Open-source ESC, dual drive, custom longboard deck, and hand-assembled batteries are the notable features. Assembling batteries by hand is very time-consuming, but is a third the cost of pre-assembled cells. ~30km range (in summertime). Telemetry and logging, speed limiting, current control, range estimation, total draw, and more are tracked by the controller and displayed on an LCD screen on the hand-held remote.

### Where it started

After finishing my [Electric Motorcycle](/projects/creations/electric-motorcycle/), I was left with a lot of spare parts. I had a longboard sitting around, so I decided to electrify it next, since it was more useful for city commuting. The first iteration was very much strapped together, but it worked, and proved how fun the concept could be.

![First iteration](/img/electric_boards/IMG_20210505_175926.jpg)
<!-- redo the link but with a max width -->
<!-- <img src="/img/electric_boards/IMG_20210505_175926.jpg" alt="First Iteration" width="200"> -->

### The second iteration

After seeing how fun the first iteration was, and having improved it enough it was now reliable, I started over with parts actaully meant for the board. The most notable upgrades were a dual-motor controller (and the two motors), a custom deck, and all terrain rubber wheels. Double kingpin trucks make it easier to maneuver, and all the mounting was designed and 3d-printed by yours truly. This design went through many iterations, but today's version is very reliable and has a lot of features.

This version used a FlipSky ESC, hard mounts for the battery and ESC, and was not waterproof.

One notable quality of life change is the deceptively simple front battery mounts. Adding these clamps was a game changer, the battery is now rock solid and never moves no matter how much I beat on the board. The original clamps were 3d printed PLA, but this quickly failed when I hit a curb. The new clamps are 3d printed TPU, with some flex to them. They are more than strong enough to take a massive hit, and can flex a little bit, so they do not shatter on impact.

The main battery mount is just a bungie snaked through some hooks, which looks terrible, but is **by far** the best mounting solution I have seen yet. Hard mounting, enclosures, and other solutions all have their own problems, but the bungie is simple, cheap, and works perfectly. It is also very easy to remove the battery for charging, and the bungie can be replaced in seconds if it ever breaks (which it never has, the bungie is the only solution that has *never failed on me*).

![Second Iteration](/img/electric_boards/IMG_20210617_211944.jpg)
![Second iteration](/img/electric_boards/IMG_20210525_112727.jpg)

### The final iteration

The second iteration was very much duck-taped together, with the electronics enclosure being a sandwich container double-sided-taped to the bottom of the board.

The final iteration's biggest challenges were a new 3d-printed ESC enclosure I designed in SketchUp, and a new battery pack.

This included new batteries (21700 HV Li-Ion cells rather than regular 18650 cells) hand-assembled, a new charging system, higher voltages, and a much better open-source ESC that actaully provided me with the necessary CAD files to create an enclosure.

The biggest quality-of-life changes have to be the inclusion of Bluetooth for use with the VESC phone app for in-flight tuning, the low form factor of the new battery pack, and the new waterproof enclosure for the ESC and batteries.

![Second Iteration](/img/electric_boards/IMG_20211216_161854.jpg)
![Second Iteration](/img/electric_boards/IMG_20220110_142510.jpg)
![Second Iteration](/img/electric_boards/IMG_20220111_172720.jpg)
![Second Iteration](/img/electric_boards/IMG_20220112_122322.jpg)

*Weirdly enough, I don't have any pictures of the finished board on-hand, so I will fix this later.*
