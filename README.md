# Low Power 6T SRAM Design using MTCMOS and Stacking

This repository contains the design, simulation, and analysis of a low-power 6T SRAM cell using MTCMOS and stacking techniques. The project was implemented and evaluated using **Cadence Virtuoso (90nm technology node)**.

---

## Overview

The goal of this project is to reduce leakage power in SRAM cells, which is critical in modern VLSI design for portable and battery-operated systems. Techniques used:
- **MTCMOS (Multi-Threshold CMOS)**
- **Transistor Stacking**
- **Power Gating with Sleep Transistors**

---

## 🔧 Tools Used

- Cadence Virtuoso (schematic & simulation)
- 90nm CMOS Technology
- Linux environment

---

## 🧪 Results Summary

| SRAM Variant | Leakage Power | Reduction |
|--------------|---------------|-----------|
| Conventional 6T SRAM | 11.33 nW | - |
| With MTCMOS | 227.2 pW | 97.9% |
| With MTCMOS + Stacking | 979.9 pW | 91.3% |

---

##  Project Structure

- **/Circuit_Diagrams** – Schematic diagrams of each SRAM variant  
- **/Waveforms** – Output waveforms of simulations  
- **/Sim_Results** – Summary of power measurements and comparisons  
- **/Report** – Full project report with design and analysis  
- **/Netlists** – Optional: extracted SPICE netlists  
- **/Screenshots** – Cadence screenshots and layout views (optional)  
- **/Presentation** – Project presentation (if any)

---

## How to Use

This repo is for documentation and reference. Due to Cadence licensing and NDA restrictions, design database files are not shared.  
You can replicate the results using the provided netlists and schematics.

---

## Author

**Anagha Sujith**  
BTech ECE, PES University  
📧 aka.anaghasujith@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/anaghasujith)  
🔗 [GitHub](https://github.com/entropybrains)

---

## License

This project is licensed under the [MIT License](LICENSE).
