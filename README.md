# Design-and-Implementation-of-a-Synchronous-FIFO
## Overview
This project implements and verifies a parameterised First-In-First-Out (FIFO) memory at RTL level. The FIFO supports configurable data width and depth. The design is suitable for buffering and synchronizing data between digital modules.

## Features
- **Parameterised configuration:** Data width & depth are set via parameters
- **Synchronous single-clock operation**
- **Full, almost full, empty, almost empty flags**
- Overflow and underflow detection
- Robust pointer management
- Clean separation of design and verification

## RTL Design
- Written in Verilog
- Easy integration into larger designs
- Reset and clock management
- Efficient read/write logic

## Verification
- Testbench in Verilog
- Self-checking with directed and random stimulus
- Checks for data integrity, corner cases (full/empty/overflow/underflow)
- Functional and code coverage
- Assertions for protocol/flag correctness

## Usage
1. **Edit Parameters:** Set FIFO width/depth 
2. **Simulate:** Run testbench via ModelSim, Vivado, or equivalent
3. **Analyze:** Check simulation logs and waveforms for verification results


