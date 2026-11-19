# SMPS-DIN-LITE (Compact DIN-Rail SMPS Variant)

> Lightweight, single-rail 12V DC auxiliary flyback power supply for DIN-rail modular installations.

## Overview

`SMPS-DIN-LITE` is a simplified, cost- and space-optimized variant of the standard `SMPS-DIN` power supply. While sharing the core **Power Integrations TNY267PN** flyback topology and **Myrra 74080** transformer, it reduces component count and PCB footprint for secondary distribution boxes and lower-power sensor nodes.

## Key Differences from Standard SMPS-DIN

| Feature | Standard SMPS-DIN | SMPS-DIN-LITE |
| :--- | :--- | :--- |
| **Output Rails** | Dual: +12V DC & +5V DC | Single: +12V DC |
| **Linear Regulators** | ST L7812ABV & L7805ACV | ST L7812ABV only |
| **Input Connection** | 3-pin terminal block (L, N, PE) | 2-pin terminal block (L, N) |
| **Input Protection** | PTC Fuse, MOV, NTC Thermistor, Y-caps | PTC Fuse, MOV |
| **Output Filtering** | 2x 1000 µF + 10 µH + 470 µF | 1x 1000 µF + 10 µH + 470 µF |
| **Resistor Footprints** | Horizontal 7.5 mm pitch | Compact standing (`_STOJ`) footprints |
| **Target Enclosure** | Kradex Z106J (modular DIN) | Compact DIN / sub-enclosure |

## Schematic & Board Files

- `SMPS-DIN-LITE.sch` – Autodesk Eagle schematic
- `SMPS-DIN-LITE.brd` – Autodesk Eagle 2-layer PCB layout
- `SMPS-DIN-LITE.pdf` – Schematic and PCB preview
- `DRILEGEND.CFG` – CAM drill legend configuration
