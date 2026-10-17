---
title: "my-keeb"
github: "https://github.com/Ahmedjk4/my-keeb"
description: "A custom 60% mechanical keyboard designed from scratch using KiCad, Onshape, and RMK firmware."
created_at: "2026-08-11"
total_time: "~20h"
---

## August 11, 2026: Planning the keyboard

I started by deciding what kind of keyboard I wanted to make. I settled on a custom 60% mechanical keyboard and planned to include RGB LEDs, a rotary encoder, and a buzzer.

The planning itself was pretty quick. I spent around 15 minutes figuring out the general layout and the features I wanted. The real challenge was going to be turning that idea into an actual PCB and case.

![Keyboard planning](https://github.com/Ahmedjk4/my-keeb/blob/main/photos/rx22jeb0mpx01.jpg)

**Total time spent: 15m**

## August 11, 2026: Designing the PCB in KiCad

This was probably the hardest part of the project. It was my first time designing a PCB, so I had to figure out how to turn my keyboard layout into a working schematic and board.

I spent about 14 hours working on the PCB. There were a lot of details to deal with, from arranging the components to making sure the connections were correct and everything fit together.

This step taught me how much work goes into designing a PCB, even for something that looks relatively simple from the outside. Getting the design right in software was important because mistakes here could cause problems later when manufacturing the board.

![PCB design in KiCad](https://github.com/Ahmedjk4/my-keeb/blob/main/photos/Screenshot%202026-08-11%20084955.png)

![PCB layout](https://github.com/Ahmedjk4/my-keeb/blob/main/photos/Screenshot%202026-08-11%20084939.png)

![PCB components](https://github.com/Ahmedjk4/my-keeb/blob/main/photos/Screenshot%202026-08-11%20084626.png)

![PCB routing](https://github.com/Ahmedjk4/my-keeb/blob/main/photos/Screenshot%202026-08-11%20084857.png)

![PCB design progress](https://github.com/Ahmedjk4/my-keeb/blob/main/photos/Screenshot%202026-08-11%20084606.png)

![PCB design details](https://github.com/Ahmedjk4/my-keeb/blob/main/photos/Screenshot%202026-08-11%20084541.png)

**Total time spent: 14h**

## August 12, 2026: Designing the case in Onshape

After finishing the PCB, I moved on to designing the keyboard case in Onshape. I had to make the case fit the PCB and leave enough room for the keyboard components.

This took around six hours. One thing that kept frustrating me was Onshape's sketch constraints. Moving a rectangle to adjust the position of a key sometimes became more complicated than expected because of the constraints already applied to the sketch.

It was a good learning experience, though. I got more familiar with CAD sketches, constraints, and designing a physical enclosure around an electronic board instead of designing each part independently.

![Keyboard case designed in Onshape](https://github.com/Ahmedjk4/my-keeb/blob/main/photos/Screenshot%202026-08-12%20035022.png)

Here is my [Onshape Model](https://cad.onshape.com/documents/ac0d0c8a76d47f62a8847ed2/w/3e72c33e2d57221932c06f57/e/e20cd8668801a9152e116827)

**Total time spent: 6h**

## August 12, 2026: Setting up the firmware

With the PCB and case designs done, I moved on to the firmware. I used RMK, a keyboard firmware framework, and configured it by editing a `.toml` file rather than writing the firmware from scratch.

I also set up a separate repository for the custom keyboard firmware and used GitHub Actions to build it. This gave me experience with configuring existing embedded software and using CI to build a project automatically.

![Firmware build](https://github.com/Ahmedjk4/my-keeb/blob/main/photos/Screenshot%202026-08-12%20043313.png)

Firmware repository: https://github.com/Ahmedjk4/custom-keyboard-firmware/

**Total time spent: 1h**

## Final thoughts

Building my-keeb taught me a lot about PCB design, CAD, and embedded keyboard firmware. Since this was my first time designing a PCB, I had to learn a lot along the way, especially when working with KiCad and Onshape.

I also learned that designing hardware involves much more than just making something look good. The electronic design, physical dimensions, and software configuration all need to work together.

Thanks to Hack Club for sponsoring the project! ❤️
