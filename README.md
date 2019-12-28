# Merry Christmas!
This tiny computer has been loaded with many emulators (Arcade, NES, SNES, etc, etc) and 
nearly 600 games. It has a lot of the classics and I've already favorited some of my 
personal favorites ( I'm not sure how you look at Favorites, XD )

Beyond the obvious video game aspect, I've found that the RetroPie distribution of Linux may
turn out to be a great and fun way to learn a bit about this well-known but wildly different
operating system! That being said, this might be quite the learning curve at times. Please
don't hesitate to text/chat/call/email/etc/etc with any questions you have. Honestly, I've
had to do my own digging to get this setup well for you, but I've been using Linux for years
so I may be able to speed up your learning process a bit. Shameless plug:
https://www.picoctf.com/ is a great place to learn some **General Skills** with Linux as 
well.

But, here's some quick info to get you started:


# The fundamentals

## Hardware

* Raspberry Pi 1 model B
* 8 GB SD card w RetroPie installed
* 1 white case
* micro USB power supply
* 1 4-port USB A hub
* 1 USB Playstation-style Logitech controller
* 1 male-to-female USB A 10-ft extension cable
* 1 HDMI cable

## Terminology

* **Raspberry Pi:** a system on a chip; inexpensive, performant, great for teaching/learning(/playing retro games)
* **RetroPie:** most specifically, the distribution (distro) of Linux with all kinds of retro gaming software preloaded, and some user-friendly Linux tools
* **EmulationStation:** this is what you get dropped into when you turn on the Raspberry Pi. It can be completely traversed with a controller and it will show any console as an option when there is 1 or more ROMs available to be played with that console's emulator.


# Source of truth
When I was trying to figure out how to do stuff with the RetroPie, I went to the official docs:

https://github.com/RetroPie/RetroPie-Setup/wiki

I learned a lot. This documentation is uncommonly good.

## Highlights
* It's important to know how to leave an emulator, otherwise you may have to power cycle the pi to get back to EmulationStation.
  * On the Logitech controller press and hold 9 ("select" button on SNES controller) and then press 10 ("start" button).
  * Some more special keys (like saving anywhere) can be found here: https://github.com/RetroPie/RetroPie-Setup/wiki/First-Installation#hotkey


# ROMs

## Provenance
My dad collected a lot of ROMs while we were visiting them over Christmas. I've included 
nearly 600 of them. I excluded only the ones to the more advanced systems that I'm 
guessing would not run well on the Raspberry Pi 1 Model B.

## Lag
Most of the ROMs I've included run well, but some do have some lag. 
*Super Mario World 2: Yoshi's Island* is one of my favorites and it runs ok, but the music
is always lagging. Plenty of games do run well though, see *Time Pilot* under Arcade, 
*Super Mario World* under SNES, etc.

## Arcade
I've selected `lr-mame2003` as the default emulator for arcade games, however the needed
version can change based on the ROM. There are some arcade ROMs that might benefit from
using a different version of MAME than is provided by `lr-mame2003`.

## Sources of ROMs
I found the Secret of Mana ROM here, a long time ago:
https://www.fantasyanime.com/index

My dad got a lot of ROMs from here at my suggestion:
https://vimm.net/?p=vault

I think this site would be good for arcade ROMs:
https://www.planetemu.net/roms/mame-roms?page=T
