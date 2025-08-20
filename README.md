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
- Written in Verilog/SystemVerilog
- Easy integration into larger designs
- Reset and clock management
- Efficient read/write logic

## Verification
- Testbench in SystemVerilog
- Self-checking with directed and random stimulus
- Checks for data integrity, corner cases (full/empty/overflow/underflow)
- Functional and code coverage
- Assertions for protocol/flag correctness

## Usage
1. **Edit Parameters:** Set FIFO width/depth in `FIFO.sv`
2. **Simulate:** Run testbench via ModelSim, Vivado, or equivalent
3. **Analyze:** Check simulation logs and waveforms for verification results


[1] https://repository.rit.edu/cgi/viewcontent.cgi?article=11135&context=theses
[2] https://vlsiverify.com/verilog/verilog-codes/synchronous-fifo/
[3] https://github.com/MohamedHussein27/FIFO-Verification
[4] https://www.youtube.com/watch?v=9D7Es7PS78c
[5] https://arxiv.org/html/2504.10901v1
[6] https://www.asic-world.com/verilog/assertions2.html
[7] https://www.ijirset.com/upload/2024/ncfcsps'24/1_RTL.pdf
[8] https://www.scribd.com/document/455412602/Design-verification-of-FIFO
[9] https://vlsifirst.com/blog/practical-rtl-design-and-verification-projects-for-students
