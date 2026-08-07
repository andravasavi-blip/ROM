# 8×8 ROM using Verilog

## Overview

This project implements an **8×8 Read-Only Memory (ROM)** using Verilog HDL.

The ROM stores eight predefined 8-bit values. The output data depends on the 3-bit address input.

---

## Features

- 8 memory locations
- 8-bit data output
- 3-bit address input
- Combinational read operation
- Predefined memory contents

---

## Memory Contents

| Address | Data (Binary) | Decimal |
|---------|---------------|---------|
|000|00000011|3|
|001|00000110|6|
|010|00001001|9|
|011|00001100|12|
|100|00001111|15|
|101|00010010|18|
|110|00010101|21|
|111|00011000|24|

---

## Files

- `rom8x8.v` – Verilog ROM design
- `rom8x8_tb.v` – Testbench
- `README.md` – Documentation
- `simulation_result.png` – Waveform screenshot

---

## Software Used

- Icarus Verilog
- ModelSim
- Xilinx Vivado
- GTKWave (optional)

---

## How to Run

Compile:

```bash
iverilog -o rom rom8x8.v rom8x8_tb.v
```

Run:

```bash
vvp rom
```

View Waveform:

```bash
gtkwave dump.vcd
```

---

## Expected Output

| Address | Data |
|---------|----------|
|000|00000011|
|001|00000110|
|010|00001001|
|011|00001100|
|100|00001111|
|101|00010010|
|110|00010101|
|111|00011000|

---

## Applications

- Lookup tables (LUTs)
- Firmware storage
- Embedded systems
- Character generators
- Fixed data storage

---

## Author

Your Name