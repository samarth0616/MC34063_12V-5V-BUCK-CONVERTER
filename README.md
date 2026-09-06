# MC34063_12V-5V-BUCK-CONVERTER
12V-5V BUCK CONVERTER DESIGN USING MC34063
# 12V to 5V Buck Converter (MC34063)

A compact DC-DC step-down (buck) converter that converts a 12V input to a regulated 5V output, built around the MC34063 switching regulator IC. Designed as a USB mobile charger circuit — output is delivered directly through a USB-A connector.

Designed and routed entirely in **Proteus 8 Professional** (schematic capture + PCB layout).

---

## Features

- Input: 12V DC
- Output: 5V DC (regulated)
- Switching regulator topology using MC34063
- USB-A output connector for direct device charging
- Power indicator LED
- Two-layer PCB with bottom-layer ground plane for noise reduction
- Fully DRC/CRC clean routing

---

## Schematic



## PCB Layout


---

## Bill of Materials (BOM)

| Ref | Component | Value | Qty |
|-----|-----------|-------|-----|
| U1 | MC34063 DC-DC Converter IC | — | 1 |
| R1 | Resistor | 6.8k | 1 |
| R2 | Resistor | 18k | 1 |
| R3 | Resistor | 2k | 1 |
| R4, R5 | Resistor | 1R | 2 |
| R6 | Resistor | 10k | 1 |
| C1 | Capacitor | 10uF | 1 |
| C2 | Capacitor | 100nF | 1 |
| C3 | Capacitor | 100uF | 1 |
| L1 | Inductor | 100uH | 1 |
| D1, D2 | Schottky Diode | 1N5819 | 2 |
| D3 | LED | Red | 1 |
| J1 | USB-A Connector | — | 1 |
| J2 | 2-Pin Header (12V Input) | — | 1 |



---

## Repository Structure


## Tools Used

- **Proteus 8 Professional** — Schematic capture, PCB layout, auto-routing, DRC/CRC verification, Gerber export
- **MC34063** — Monolithic switching regulator IC (step-down configuration)

---

## Manufacturing



## What I Learned

- Designing a switching regulator layout and the importance of keeping the switching loop (IC, inductor, diode, output capacitor) physically tight to reduce noise and improve efficiency
- Using Proteus's auto-router and Power Plane Generator to add a ground copper pour
- Running DRC/CRC checks iteratively while refining component placement
- Generating manufacturing-ready Gerber/Excellon files and a Bill of Materials

---

## License

Feel free to use, modify, or build upon this design. Attribution appreciated but not required.
