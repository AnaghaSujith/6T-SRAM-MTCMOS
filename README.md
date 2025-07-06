# Low Power 6T SRAM Design using MTCMOS and Stacking

This repository contains the design, simulation, and analysis of a low-power 6T SRAM cell using MTCMOS and stacking techniques. The project was implemented and evaluated using **Cadence Virtuoso (45nm technology node)**.

---

## Overview

The goal of this project is to reduce leakage power in SRAM cells, which is critical in modern VLSI design for portable and battery-operated systems. Techniques used:
- **MTCMOS (Multi-Threshold CMOS)**
- **Transistor Stacking**
- **Power Gating with Sleep Transistors**

---

## Tools Used

- Cadence Virtuoso (schematic & simulation)
- 45nm CMOS Technology
- Linux environment

---

##  Project Structure

- **Circuit_Diagrams** – Schematic diagrams of each SRAM variant  
- **Waveforms** – Output waveforms of simulations  
- **Sim_Results** – Summary of power measurements and comparisons  
- **Report** – Full project report with design and analysis  
- **Netlists** – Optional: extracted SPICE netlists  

---

## Results Summary

| SRAM Variant | Leakage Power | Reduction |
|--------------|---------------|-----------|
| Conventional 6T SRAM | 11.33 nW | - |
| With MTCMOS | 227.2 pW | 97.9% |
| With MTCMOS + Stacking | 979.9 pW | 91.3% |

---

## Inference
The analysis shows a drastic reduction in leakage power when using MTCMOS techniques in 6T SRAM designs. Applying MTCMOS alone reduces leakage by 97.9%, while combining it with transistor stacking still achieves a significant 91.3% reduction. Although stacking slightly increases leakage compared to MTCMOS alone, it offers design flexibility and improved control. Overall, MTCMOS-based techniques are highly effective for minimizing standby power in SRAMs.
---


