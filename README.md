 Reconfigurable, RISC-like Processing Element for Multi-Precision Neural Network Interface - FPGA team
 
# PE Verification Environment

## Introduction
This repository contains the verification environment developed for the PE (Processing Element) chip. The verification framework is written in SystemVerilog and is intended to validate both the functional correctness and the control behavior of the PE under a wide range of operating scenarios.

The main verification file is `pe_tb.sv`, which serves as the top-level testbench for simulation. The environment was designed to be readable, modular, and easy to adapt as the RTL evolves.
