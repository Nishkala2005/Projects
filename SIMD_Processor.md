# 3-Stage SIMD Pipeline Processor (Verilog)

## Overview
This project implements a simplified 3-stage SIMD-style pipeline processor in Verilog.

Stages:
1. Fetch
2. Decode
3. Register Read

## Architecture
- 32-bit RISC-style instruction format
- 32-register file
- PC increment by 4
- Instruction memory initialized with sample ADDI instructions

## Simulation
Testbench verifies:
- PC increment
- Instruction fetch
- Register decode
- Register file read

## Tools Used
- Cadence Xcelium
- GTKWave
- Verilog HDL

## Future Improvements
- Add ALU stage
- Add Hazard Detection
- Add Memory Stage
- Add Forwarding Unit
