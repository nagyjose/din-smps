# SMPS Design Documentation, Calculations & Datasheets

This directory contains component selection spreadsheets, procurement orders, and component datasheets used for the SMPS-DIN and SMPS-DIN-LITE power supplies (consolidated from project `PRJ-35`).

## Structure

### 1. Calculations & Sourcing (`calculations/`)
- `Součástky.xlsx`: Primary component calculation and selection spreadsheet detailing component dimensions, footprints, current/voltage ratings, and TME catalog parts.
- `Součástky (version 1).xlsb.xlsx`: Early calculation sheet.
- `order_32668509.csv`: Direct bill of materials / export from TME distributor for prototype fabrication.

### 2. Component Datasheets (`datasheets/`)
- **Controller & Active ICs:**
  - `tny263-268g_p.pdf`: Power Integrations TinySwitch-II Family (TNY267PN) offline flyback switcher.
  - `PC817X3NSZ1B.pdf`: Sharp PC817 optocoupler for galvanic isolation and feedback regulation.
  - `L78.pdf`: STMicroelectronics L78 series (L7812, L7805) positive voltage regulators.
  - `lm317.pdf` / `lm337.pdf`: Adjustable linear regulators.
- **Magnetics:**
  - `74080.pdf`: Myrra 74080 flyback transformer specifically designed for TinySwitch converters.
  - `COIL1010-2.2.pdf`: Ferrocore 2.2 mH input filter choke.
  - `COIL0608-0.01.pdf`: Ferrocore 10 µH output smoothing inductor.
- **Protection & Passives:**
  - `PTF77.pdf` / `FX100-30`: Stelvio Kontek PTF/77 fuseholder and PTC resettable fuse.
  - `SR_PASSIVES- VAR7 series.pdf`: HEL-7D681K metal oxide varistor (MOV) for AC surge suppression.
  - `NTCS-10-10-2`: 10 Ω NTC inrush current limiting thermistor.
  - `1N5822-ST.pdf`: 3A 40V Schottky barrier rectifier for high-efficiency secondary rectification.
  - `1n4001.pdf`: 1N4001-1N4007 silicon rectifiers for AC line bridge.
  - `bzx55c.pdf` / `BZX55C10-TAP.pdf`: Zener voltage reference diodes.
  - `ECA1VM470.pdf`, `JYC.pdf`, `Ceramic Capacitor CCH.pdf`, `CY1Y-1N.pdf`, `MPEM datasheet.pdf`, `WH-series.pdf`: High-voltage AC filter, Y-safety, and secondary low-ESR electrolytic capacitors.
