# stm32-falling-sticks

A DIY reaction-based "falling sticks" game controller built around an STM32 Bluepill.

## Features

- **STM32 Bluepill** as the main controller
- **10x electromagnet drivers** — MOSFET-switched, each with a flyback protection diode and pulldown resistor
- **10x Hall effect sensors** for stick drop/position detection
- **LCD output** support for game status/score
- **12V buzzer** support, driven off the same MOSFET channels as the electromagnets
- **Start button** input to trigger the game
- **Single-layer PCB** — 0-ohm jumper resistors used in place of vias/second layer for a few connections
- **CNC-mill optimized** trace layout (tested on a Wegstr 3-axis CNC)

## Power

- Dual 12V input options: screw terminal or DC jack
- **MP1584EN buck converter** steps 12V down to 5V to power the electromagnets, Hall effect sensors, and Bluepill

## Board Previews

| View | Image |
| --- | --- |
| **Top View** | ![Top View](top.png) |
| **Bottom View** | ![Bottom View](bottom.png) |
| **Side View 1** | ![Side View 1](side.png) |
| **Side View 2** | ![Side View 2](side2.png) |

## Schematics
![Schematic](schematic.svg)
