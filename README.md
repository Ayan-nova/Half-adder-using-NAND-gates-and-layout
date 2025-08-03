# 🔢 Half Adder Using NAND Gates

## 📘 Overview

This project presents the implementation of a **Half Adder** circuit using only **NAND gates**. A Half Adder is a combinational logic circuit that adds two single-bit binary numbers and produces two outputs:
- **Sum (A ⊕ B)**
- **Carry (A · B)**

Instead of using the standard XOR and AND gates, this design uses only NAND gates, demonstrating how universal gates can be used to construct any logic function.

## 🎯 Objectives

- Understand the working of a Half Adder.
- Implement XOR and AND logic using only NAND gates.
- Simulate the logic using Verilog HDL.
- Visualize the layout and gate-level connections.

## 🔧 Logic Design Using NAND Gates

### Sum (A ⊕ B)
Sum = (A NAND (A NAND B)) NAND (B NAND (A NAND B))

### Carry (A · B)
Carry = (A NAND B) NAND (A NAND B)

| A | B | Sum | Carry |
| - | - | --- | ----- |
| 0 | 0 | 0   | 0     |
| 0 | 1 | 1   | 0     |
| 1 | 0 | 1   | 0     |
| 1 | 1 | 0   | 1     |



📌 Conclusion
This project demonstrates the practical use of universal gates in logic circuit design. Using only NAND gates simplifies manufacturing and highlights core digital logic principles.


Let me know if you’d like this adapted for a specific simulation tool or include sample testbenches.
