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
| Pogo Pin  | 0906-4-15-20-75-14-11-0  | 14 |
| USB-C Connector | USB4056-03-A | 2 |
| ASA Filament | n/a | <100g |
| K&J Magnets | Will be testing 3 different sizes. | 4 |

- [x] Pogo Pins
- [x] USB-C Connector
- [ ] Magnets
- [ ] Adhesive

### Board Layout
- [x] General layout
- [x] Trace routing
- [ ] Trace power calculations - Data analysis pending (2/15/24)
- [ ] PCB refinement 
- [ ] PCB Finalization
- [ ] PCB Ordered

### C3X Windshield Mount
- [x] PCB imported and modeled.
- [x] Male mount modeled
- [x] Female mount modeled
- [x] Mock-up mount printed.
- [ ] Mount refinement - Started 2/14/24
- [ ] Mock-up two printed
- [ ] Secondary refinement
- [ ] Initial finalization

### Field Testing
- [ ] Endurance testing (50 hours usage)
- [ ] Vibration testing
- [ ] Heat testing (7 day constant connectivity)

## Specifications Pertaining to the Project
- Comma3X Weight: 311g (11oz)
- Power Usage: See spreadsheets/csv in the power_data folder!
