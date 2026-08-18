# 8 x 4 ROM using Verilog

## Overview

This project implements an 8 x 4 Read Only Memory (ROM) using Verilog HDL.

The ROM contains 8 memory locations, and each location stores 4 bits of data.

## Inputs

- `address` – 3-bit memory address

## Output

- `data` – 4-bit stored data

## Memory Size

- Number of locations: 8
- Data width: 4 bits
- Address width: 3 bits

## Memory Table

| Address | Data |
|---------|------|
| 000 | 1010 |
| 001 | 1100 |
| 010 | 0110 |
| 011 | 1001 |
| 100 | 0011 |
| 101 | 1111 |
| 110 | 0101 |
| 111 | 0001 |

## Files

- `rom.v` – ROM Verilog design
- `rom_tb.v` – Testbench
- `README.md` – Project documentation
- `simulation_result.png` – Simulation waveform

## Software Used

- Icarus Verilog
- ModelSim / Vivado
- GTKWave

## How to Run

### Compile

```bash
iverilog -o rom rom.v rom_tb.v