# CommaPOGO
I recently have come across a project for the Comma3X that utilizes pogo pins for the quick disconnect of a comma3x. This is my attempt to create an open source alternative to that mount that is DIY and 3D printable. The original creation is by @cloudj0816 in the [OpenPilot community discord](https://discord.com/invite/avCJxEX). All credit goes to him for this initial idea! He actually sells the devices so be sure to check that out if you would like one! You can find the wait list in the #hw-unofficial channel. 

## Goals:
- Inexpensive
- Open Source
- 3D Printed
- Angle adjustment (for imperfect mounting positions)
    - This is more of a future goal. I'm first going to focus on getting the static mount correct.

## Progress Tracking
### Parts
Preliminary BOM: 
| Colloqiual Name| Part No.    | Quantity | 
| --------- | -------- | ------- | 
| Pogo Pin  | 2906-4-15-20-75-14-11-0  | 14 |
| USB-C Connector | USB4056-03-A | 2 |
| ASA Filament | n/a | <100g |
| K&J Magnets | Testing | 4 |
|3M Adhesive | Undecided | ~100mm<sup>2</sup> (~1.5in<sup>2</sup>)|

- [x] Pogo Pins
- [x] USB-C Connector
- [ ] Magnets
    - Testing four options. - 2/16/24
- [ ] Adhesive

### Board Layout
- [x] General layout
- [x] Trace routing
- [x] Trace power calculations - Data analysis pending (2/15/24)
- [x] PCB refinement 
- [x] PCB Finalization
- [x] PCB Ordered

### C3X Windshield Mount
- [x] PCB imported and modeled.
- [x] Male mount modeled
- [x] Female mount modeled
- [x] Mock-up mount printed.
- [x] Mount refinement
- [x] Test-bed mounts printed
- [ ] Test-beds tested
- [ ] Final mock-up printed
- [ ] Final refinement
- [ ] Production unit trials

### Field Testing
- [ ] Endurance testing (50 hours usage)
- [ ] Vibration testing
- [ ] Heat testing (7 day constant connectivity)

## Specifications Pertaining to the Project
- Comma3X Weight: 311g (11oz)
- Power Usage: See the [summary spreadsheet](/power_data/summary.xlsx) for this data.
