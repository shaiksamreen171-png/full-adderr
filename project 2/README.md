# Full Adder using Verilog

## Objective

Design and simulate a 1-bit Full Adder using Verilog HDL.

## Description

A Full Adder adds three binary inputs:
- A
- B
- Cin (Carry Input)

It produces two outputs:
- Sum
- Cout (Carry Output)

## Truth Table

| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
|0|0|0|0|0|
|0|0|1|1|0|
|0|1|0|1|0|
|0|1|1|0|1|
|1|0|0|1|0|
|1|0|1|0|1|
|1|1|0|0|1|
|1|1|1|1|1|

## Boolean Equations

Sum = A ^ B ^ Cin

Cout = (A & B) | (B & Cin) | (A & Cin)

## Software Used

- Xilinx Vivado
- ModelSim
- Icarus Verilog
- GTKWave

## Files

- full_adder.v
- full_adder_tb.v
- README.md

## Author

Your Name