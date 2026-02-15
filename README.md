# half_adder
Verilog implementation of a Half Adder using Vivado. Includes RTL design, testbench for functional simulation, and XDC constraints file. The design performs binary addition of two inputs and generates Sum and Carry outputs. Suitable for FPGA implementation and basic digital logic learning.
Half Adder in Verilog (Vivado)
📌 Project Description

This project implements a Half Adder using Verilog HDL in Xilinx Vivado. The design performs binary addition of two 1-bit inputs and generates Sum and Carry outputs. The project includes RTL design, testbench for simulation, and constraint file for FPGA implementation.

🧠 Theory

A Half Adder adds two single-bit binary inputs:

Sum = A ⊕ B

Carry = A · B

Where:

⊕ = XOR operation

· = AND operation
| A | B | Sum | Carry |
| - | - | --- | ----- |
| 0 | 0 | 0   | 0     |
| 0 | 1 | 1   | 0     |
| 1 | 0 | 1   | 0     |
| 1 | 1 | 0   | 1     |


Learning Outcomes

Understanding combinational logic design

Writing RTL in Verilog

Creating testbenches

Running simulation in Vivado
