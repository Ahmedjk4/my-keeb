---
title: "my-keeb"
github: "https://github.com/Ahmedjk4/my-keeb"
description: "A custom 60% mechanical keyboard designed from scratch using KiCad, Onshape, and RMK firmware."
created_at: "2026-08-11"
total_time: "21h 15m"
---

# August 11, 2026: Planning the keyboard
<!-- fabricate:entry 611 -->

I started by deciding what kind of keyboard I wanted to make. I settled on a custom 60% mechanical keyboard and planned to include RGB LEDs, a rotary encoder, and a buzzer.

The planning itself was pretty quick. I spent around 15 minutes figuring out the general layout and the features I wanted. The real challenge was going to be turning that idea into an actual PCB and case.

![Keyboard planning](https://fabricate.hackclub-assets.com/53ee988b8ca004b6219eb8d735072d38e2abe828c25c1688c39cdf98a9a68a0f/image-jpeg/rx22jeb0mpx01.jpg)

**Total time spent: 15m**

# August 11, 2026 (entry 2): Designing the PCB in KiCad
<!-- fabricate:entry 612 -->

This was probably the hardest part of the project. It was my first time designing a PCB, so I had to figure out how to turn my keyboard layout into a working schematic and board.

I spent about 14 hours working on the PCB. There were a lot of details to deal with, from arranging the components to making sure the connections were correct and everything fit together.

This step taught me how much work goes into designing a PCB, even for something that looks relatively simple from the outside. Getting the design right in software was important because mistakes here could cause problems later when manufacturing the board.

![PCB design in KiCad](https://fabricate.hackclub-assets.com/5a496d8506c938a238b1769f8dd0dfc4b11e36bb6ceb16060bb06e105069cbc1/image-png/Screenshot%202026-08-11%20084955.png)

![PCB layout](https://fabricate.hackclub-assets.com/c0bb04936c9fb90c29592951748f0f85a5b1b70f0b5442cd9e6ac6f8ed4e5d75/image-png/Screenshot%202026-08-11%20084939.png)

![PCB components](https://fabricate.hackclub-assets.com/2e8a09471762d6944bc65b9317fc74345180f1cacef38b1b6f23206bed1b30b4/image-png/Screenshot%202026-08-11%20084626.png)

![PCB routing](https://fabricate.hackclub-assets.com/66d7642b02822c4f81d4a5f7c73a843675800b05a48fb325307762831eaff59a/image-png/Screenshot%202026-08-11%20084857.png)

![PCB design progress](https://fabricate.hackclub-assets.com/cb4de1a1f25d70d0aa0c646674a2d7599723a8001450128a3b999be7997ed863/image-png/Screenshot%202026-08-11%20084606.png)

![PCB design details](https://fabricate.hackclub-assets.com/64ae615a9bcff3effa93aadcc8a30ab82e343787ca9d8148d45b30b5362c97ba/image-png/Screenshot%202026-08-11%20084541.png)

**Total time spent: 14h**

# August 12, 2026: Designing the case in Onshape
<!-- fabricate:entry 613 -->

After finishing the PCB, I moved on to designing the keyboard case in Onshape. I had to make the case fit the PCB and leave enough room for the keyboard components.

This took around six hours. One thing that kept frustrating me was Onshape's sketch constraints. Moving a rectangle to adjust the position of a key sometimes became more complicated than expected because of the constraints already applied to the sketch.

It was a good learning experience, though. I got more familiar with CAD sketches, constraints, and designing a physical enclosure around an electronic board instead of designing each part independently.

![Keyboard case designed in Onshape](https://fabricate.hackclub-assets.com/f0c94cd1a3c6ce94558d0343eb19c3770be87b3367500c81feb512778a37ab81/image-png/Screenshot%202026-08-12%20035022.png)

Here is my [Onshape Model](https://cad.onshape.com/documents/ac0d0c8a76d47f62a8847ed2/w/3e72c33e2d57221932c06f57/e/e20cd8668801a9152e116827)

**Total time spent: 6h**

# August 12, 2026 (entry 2): Setting up the firmware
<!-- fabricate:entry 614 -->

With the PCB and case designs done, I moved on to the firmware. I used RMK, a keyboard firmware framework, and configured it by editing a `.toml` file rather than writing the firmware from scratch.

I also set up a separate repository for the custom keyboard firmware and used GitHub Actions to build it. This gave me experience with configuring existing embedded software and using CI to build a project automatically.

![Firmware](https://fabricate.hackclub-assets.com/33cdfd6a0b818bbdfb86051d54968e15cf0b3915d2f49c3cf67e562e09d40b69/image-jpeg/Screenshot_20261018_094411_Chrome.jpg)
![Firmware](https://fabricate.hackclub-assets.com/ce911e81576aa13632fe7ce72a883afcc551cbe38c8383c5f247c707a99fb2f0/image-jpeg/Screenshot_20261018_094340_Chrome.jpg)
![Firmware](https://fabricate.hackclub-assets.com/fb73a57fcb84a20b3ca448a7f87d9a40367922a17fee967f2948e13b21bddf70/image-jpeg/Screenshot_20261018_094330_Chrome.jpg)


![Firmware build](https://fabricate.hackclub-assets.com/8549a261ac35427cacfcf38579c14f0aef7ede7b06a2d81fb7ef9f98eb5cc9aa/image-png/Screenshot%202026-08-12%20043313.png)

Firmware repository: https://github.com/Ahmedjk4/custom-keyboard-firmware/

**Total time spent: 1h**

# Final thoughts

Building my-keeb taught me a lot about PCB design, CAD, and embedded keyboard firmware. Since this was my first time designing a PCB, I had to learn a lot along the way, especially when working with KiCad and Onshape.

I also learned that designing hardware involves much more than just making something look good. The electronic design, physical dimensions, and software configuration all need to work together.

Thanks to Hack Club for sponsoring the project! ❤️
