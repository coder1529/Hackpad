# Hackpad

My first real hardware project — a 5-key macropad with a rotary encoder and a tiny OLED screen, built for Hack Club Stardance. I designed the whole thing from scratch: schematic, PCB, and the 3D printed case.

## What it actually is

A macropad is basically a mini keyboard just for shortcuts, so instead of digging through hotkey combos you tap one button and it's done. Mine has:

- 5 mechanical switches
- 1 rotary encoder with a click function, so it acts as a 6th button too
- A 0.91" I2C OLED screen
- A Seeed XIAO RP2040 running the whole thing
- A custom PCB with my dog on the silkscreen (non-negotiable)

## Status

Hardware side is finished — schematic's done, PCB is routed, and the case is modeled and ready to print. Firmware is next, haven't started coding it yet.

## Files

- `PCB folders/` — KiCad schematic and PCB layout
- `Macropad/` — KiCad project files
- `3d print folder/` — STL for the case

## Why I made this

I've done robotics and competitive programming for a while, but I'd never actually designed a PCB before, so this was my first time going from a blank schematic to something I could actually order and solder. Lots of "wait, why is this net not connecting" moments along the way. Shipping this for Stardance.

## IMAGES

PCB
<img width="739" height="1240" alt="image" src="https://github.com/user-attachments/assets/c3c23da0-fb9c-4f1a-9616-0c2c260beffb" />
3D DESIGN
<img width="1948" height="1435" alt="image" src="https://github.com/user-attachments/assets/f3018529-c728-46cf-9fb7-5f6d12f9a346" />
