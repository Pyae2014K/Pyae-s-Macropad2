# Pyae-s-Macropad2

My macropad is a 13 key macropad with a rotary encoder and per-key RGB.
It uses QMK firmware

It serves as a macropad that I can use every day to be more productive.

## Features:
- EC11 Rotary encoder for volume
- 13 keys, 12 for macros and 1 for swapping layers
- Per-key RGB
- [VIA](https://www.caniusevia.com/) support

## PCB:
My PCB was made using Kicad.

Schematic

<img width="1285" height="510" alt="image" src="https://github.com/user-attachments/assets/007bf995-8d9c-457a-b393-4bedcd193f1b" />


PCB

<img width="500" height="686" alt="image" src="https://github.com/user-attachments/assets/10e6f1d2-34a9-400c-8221-69f8841f73a2" />



I used [Joe Scotto's](https://www.youtube.com/@joe_scotto) footprints for most of my footprints.

## CAD Model
Everything fits together perfectly using just 4 M3 Bolts and heat-set inserts.

It has 4 different pieces, Top Case, Bottom Case, Plate, and a Rotary Encoder Knob

<img width="1147" height="957" alt="image" src="https://github.com/user-attachments/assets/69e50abd-dd3c-4a28-bfe3-26817f550342" />


This model was made using Shapr 3D.

## Firmware
This macropad uses [QMK](https://qmk.fm/) firmware for its code.
- 13 keys; 12 for macros, 1 for layers
- Rotary encoder used to change volume
- Per-key LEDs

  ## BOM:
  Here is everything that is needed to make this macropad
| Qty | Part | Description |
|-----:|------|-------------|
| 1 | Seeed XIAO RP2040 | Microcontroller |
| 13 | MX-Style Switches | Mechanical keyboard switch |
| 13 | DSA Keycaps | DSA profile keycap |
| 14 | 1N4148 Diodes | DO-35 through-hole diode |
| 1 | EC11E Rotary Encoder | Rotary encoder |
| 4 | M3x16mm Screws | M3 screw |
| 4 | M3x5mx4mm Heatset Inserts | M3 threaded heat-set insert |
| 13 | SK6812 MINI-E LEDs | LEDs |
| 1 | Case Top | 3D printed top case |
| 1 | Case Bottom | 3D printed bottom case |
| 1 | Plate | Switch plate |
| 1 | Knob | Rotary encoder knob |
