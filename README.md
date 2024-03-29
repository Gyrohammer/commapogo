# CommaPOGO
I recently have come across a project for the Comma3X that utilizes pogo pins for the quick disconnect of a comma3x. This is my attempt to create an open source alternative to that mount that is DIY and 3D printable. I was inspired after seeing the mount that @cloudj0816 made in the [OpenPilot community discord](https://discord.com/invite/avCJxEX). All credit goes to him for this initial idea! If you'd like to purchase one of his connectors (full CNC metal), you can find the wait list in the #hw-unofficial channel. 

## Goals:
- Inexpensive
- Open Source
- 3D Printed
- ~~Angle adjustment (for imperfect mounting positions)~~
    - This is more of a future goal. I'm first going to focus on getting the static mount correct.

## Progress Tracking
### Parts
Preliminary BOM: 
| Colloqiual Name| Part No.    | Quantity | 
| --------- | -------- | ------- | 
| Pogo Pin  | 2906-4-15-20-75-14-11-0  | 14 |
| USB-C Connector | HC005-1A1H1A103-0HR | 2 |
| ASA Filament | n/a | <100g |
| K&J Magnets | D83-N52 | 4 |
|3M Adhesive | 3M™ VHB™ Tape 5952 | ~100mm<sup>2</sup> (~1.5in<sup>2</sup>)|

- [x] Pogo Pins
- [x] USB-C Connector
- [x] Magnets
- [x] Adhesive

### Board Layout
- [x] General layout
- [x] Trace routing
- [x] Trace power calculations - Data analysis pending (2/15/24)
- [x] PCB refinement 
- [x] PCB Finalization
- [x] PCB Ordered
- [x] PCB Delivered
- [ ] PCB Rework One - Awaiting delivery
- [ ] PCB Testing 
- [ ] PCB Finalized

### C3X Windshield Mount
- [x] PCB imported and modeled.
- [x] Male mount modeled
- [x] Female mount modeled
- [x] Mock-up mount printed.
- [x] Mount refinement
- [x] Test-bed mounts printed
- [x] Test-beds tested
- [x] 'Gravimatrix' mock-up printed
- [ ] 'Gravimatrix' refinement - Minor adjustments being made
- [ ] Preliminary testing
- [ ] Production unit trials

### Field Testing
- [ ] Endurance testing (50 hours usage)
- [ ] Vibration testing
- [ ] Heat testing (7 day constant connectivity)

## Specifications Pertaining to the Project
- Comma3X Weight: 311g (11oz)
- Power Usage: See the [summary spreadsheet](/power_data/summary.xlsx) for this data.

# Separate Updates

## March 10th, 2024
I've gotten the first hand-built boards put together and making a solid connection! The most likely candidate for the mounting system will be the Gravimatrix design, as that is the most solid. But as of 3/10/24 I have a working prototype! Soldering USB-C connectors by hand is extremely difficult, who'da thunk it?

These connectors will likely be soldered on from the manufacturer going forward, this will ensure consistency and quality at the cost of a few cents per board. A compromise I am more than willing to make.

## March 19th, 2024

PCB no worky! I believe I have some crosstalk/interference throughout the coupler. I'll be re-assessing and redesigning the PCB to hopefully counteract this and get a working connection.

## March 21st, 2024

This weekend I'll be using an oscilloscope to check signal integrity. Hopefully its simple as that, and adding a ground plane(s) will solve it. I had no idea what a ground-plane was until I asked for ideas/advice on the electrical engineering stack exchange. [Heres the thread where that was suggested!](https://electronics.stackexchange.com/questions/706633/usb-c-pogo-pin-coupler-troubleshooting).
