---
title: "FRAMer"
github: "https://github.com/wilrak0v/FRAMer"
description: ""
created_at: "2026-11-02"
total_time: "1h30"
---

## November 2, 2026: Search for components!
To start the project, I begun by searching for the different components.

First of all: the mcu. I need one that doesn't use a lot of power, and for that the msp430 family from Texas Instrument is probably the best. Then, I need certains features such as a lot of RAM and a lot of FLASH, maybe something better than FLASH... The FRAM!
That's why this project is called "**FRAM**er", because of the usage of a FRAM in the choosen mcu. So I choosed the MSP430FR5994 which is really great for this usage. FRAMer isn't a complex or powerful cyberdeck, it's just a small one with basic features so I don't need something like a stm32. However there are great stm32 for low power cyberdecks such as the stm32u5 which is quite convenient for a complete micro pc without any lithium battery.

![An image of MSP430FR5994](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ffile.welllinkchips.com%2Fview%3Fid%3D3225047%26k%3D7ddc783e6844ed5c1d4e37c72cafa7d1&f=1&nofb=1&ipt=34d3d20145a3cd97762becb7a19c2b9b53b5bbcf64420be99e93a8a9d75ed00c&ipo=images)

Then I'll need a screen for displaying a cute terminal. So I went on [reichelt](https://reichelt.com) which is an european provider for electronic components.
So I know a lot of displays for embedded applications because I had multiple projects like a game console in the past. So I knew exactly which kind of screen I'll need. Finally, I choosed the "EA DOGL128W-6" which is a LCD monochrome 128x64 screen. Why this one?
Because it consumes only 320µA maximum. So it's one of the best screen for my usage. It is compatible with I2C and SPI. I don't need colors for this specific project.

![The screeeeennnnn!](https://cdn-reichelt.de/bilder/web/artikel_ws/A500%2FDOGL128W-W_1.jpg?type=Product&)

Finally I thought about the keyboard.
Since the screen is really small, I'd like to be able to have a small device for typing. Because of that, I could'nt make a fully mechanical keyboard, and I don't really like small push-buttons one. So what's the solution? Idk but I have an idea: why not typing in morse?
Because it's slow of course, but we can improve the speed by adding 2 supplement keys. So we have one switch for the ., another one for the - and the others for ending a letter, a word or returning to the next line.
It's not my last idea but I'd like to try that. So first I'll do a prototype and see if it's convenient or not.


That's all for today! It's already a lot and I have an idea of the design in mind so I'll work on that now. I also need to make a list of the functionalities of the device, then I'll start my keyboard prototype. So yeah let's keep working!

> Oh and I didn't talk about it but I started to read the datasheet too, that's why it took a long time.

**Total time spent: 1h30**
