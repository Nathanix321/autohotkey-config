This is my AutoHotkey config!

It solves the issue of accents (for me, I'm a bilingual french - english speaker)! I used to write with the Canadian Multilingual Standard (CMS) keyboard, which gave me mostly easy access to the accents I needed, but I got annoyed when using other computers with US and CAFR keyboard (like university keyboards I can't change), and decided to get used to the US Intl keyboard with dead keys.

Then when I tried that, I got annoyed with the dead key behaviour, so I tried the United States (International) - Alt Gr dead keys keyboard you can find [here](https://github.com/thomasfaingnaert/win-us-intl-altgr), which only activates dead keys when pressing while holding Alt Gr. But I got annoyed with some accent sequences, mainly using the circumflex accent (^). 

In comes this AutoHotkey config, that let's me use the Alt Gr key to directly put all possible french accents exactly where I want them. I based this on [UltimateKEYS](https://pieter-degroote.github.io/UltimateKEYS/), which implements a bunch more accents and a unicode compose key. Since I don't need those accents and don't desire a compose key, I figured I'd make my own and put the accents where I want them. 

I only use AutoHotkeys for accents because I prefer the rest of my config to live on my devices (ZMK - QMK), and because handling accents in firmware is a pain, since they aren't integrated in the HID standard and are always handled by the OS. At some point I'll make a config for linux too. 

Here's a picture of the layout :