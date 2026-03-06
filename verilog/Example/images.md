## 📖 Top Module (and_or_top.v)

The `and_or_top.v` file contains the top-level Verilog module that implements two basic digital logic gates: **AND** and **OR**.

### Description

* The module takes two inputs: `A` and `B`.
* It produces two outputs:

  * `AND` – result of the logical AND operation.
  * `OR` – result of the logical OR operation.

These outputs follow the standard Boolean logic operations used in digital circuits.

### Truth Table

| A | B | AND | OR |
| - | - | --- | -- |
| 0 | 0 | 0   | 0  |
| 0 | 1 | 0   | 1  |
| 1 | 0 | 0   | 1  |
| 1 | 1 | 1   | 1  |

---

## 📊 Simulation Waveform

The simulation waveform shows the behavior of the AND and OR gates for all possible input combinations of `A` and `B`.

The waveform confirms that:

* `AND` becomes **1 only when both inputs are 1**.
* `OR` becomes **1 when at least one input is 1**.

<img width="1807" height="985" alt="image" src="https://github.com/user-attachments/assets/e174cfb0-4592-4e5e-9447-95835a1dae65" />

---

## 🔎 Generated Schematic

The schematic represents the synthesized hardware structure of the design.
It shows how the input signals `A` and `B` are connected to the **AND** and **OR** logic gates to produce the outputs.

This schematic was generated using synthesis tools and helps visualize the hardware implementation of the Verilog design.

<img width="1810" height="981" alt="image" src="https://github.com/user-attachments/assets/c0781837-66a0-4fbf-a3df-8fe70032c587" />

---

## 🧪 Testbench

A Verilog testbench is used to simulate the design.
It applies different combinations of input values (`A` and `B`) and prints the results using `$display` while also generating a waveform (`.vcd`) file for visualization.



