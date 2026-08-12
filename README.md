# 5V LED Indicator PCB

A beginner-to-job-ready PCB design project created in **EasyEDA Pro**. The board
provides a simple visual indication when a 5V supply is connected.

## Project Overview

The circuit uses a 330 ohm current-limiting resistor and a 5 mm through-hole LED.

### Electrical path

```text
J1 Pin 1 (+5V)
      |
     R1
    330 ohm
      |
    LED1
      |
J1 Pin 2 (GND)
```

## Features

- 5V DC power indication
- Through-hole components for easy hand soldering
- 2-pin 2.54 mm power connector
- 330 ohm LED current-limiting resistor
- 5 mm indicator LED
- Simple single-path routing
- DRC checked before fabrication
- Gerber manufacturing package generated
- Plated through-hole drill data included

## Component List

| Ref | Component | Value | Footprint |
|---|---|---|---|
| J1 | 2-pin connector/header | 5V / GND | `HDR-TH_2P-P2.54-V-F` |
| R1 | THT resistor | 330 ohm | `R_AXIAL-0.4` |
| LED1 | 5 mm THT LED | 5 mm | `LED-TH_BD5.8-P2.54-FD` |

See [`Manufacturing/BOM.csv`](Manufacturing/BOM.csv).

## PCB Specifications

- CAD: EasyEDA Pro
- Board type: 2-layer
- Components: THT
- Approx. board size: 52.45 mm × 12.07 mm
- Supply: 5V DC
- DRC violations: 0

See [`Docs/PCB_Specifications.md`](Docs/PCB_Specifications.md).

## Design Workflow

1. Schematic capture
2. Component selection
3. THT footprint assignment
4. PCB conversion
5. Component placement
6. PCB routing
7. Design Rule Check (DRC)
8. 3D PCB verification
9. Gerber generation
10. Manufacturing-package inspection

## Manufacturing Files

The Gerber ZIP is in:

[`Gerber/Gerber_PCB1_2026-08-12.zip`](Gerber/Gerber_PCB1_2026-08-12.zip)

The extracted files are also provided in [`Gerber/Extracted/`](Gerber/Extracted/).

The package contains top/bottom copper, solder mask, silkscreen, board outline,
drill drawing and plated-through-hole drill data.

## DRC

The PCB passed the EasyEDA DRC check with **0 reported violations** before
Gerber export.

See [`Manufacturing/DRC_Report.md`](Manufacturing/DRC_Report.md).

## Repository Status

### Included
- [x] Gerber manufacturing package
- [x] BOM
- [x] PCB specifications
- [x] DRC report
- [x] Manufacturing documentation

### To add from EasyEDA
- [ ] EasyEDA schematic source file
- [ ] EasyEDA PCB source file
- [ ] Schematic screenshot
- [ ] PCB layout screenshot
- [ ] 3D PCB screenshot
- [ ] Fabricated PCB photographs

## Resume-Ready Description

**5V LED Indicator PCB — EasyEDA Pro:** Designed a through-hole 5V LED
indicator PCB from schematic capture through PCB layout and manufacturing
output. Selected THT footprints, routed the board, completed DRC with zero
reported violations, verified the design in 3D, and generated/inspected
Gerber and plated-through-hole drill files.

## Author

**Aparna Peddireddy Nadipolla**

## License

This project is intended as a personal learning and portfolio project.
