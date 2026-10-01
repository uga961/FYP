# High Performance SRAM Design for Energy Efficient Systems

A VLSI project focused on the design, analysis, and optimization of static random-access memory (SRAM) architectures for low-power, high-performance embedded and energy-efficient systems.

## Overview

This project investigates the trade-offs between conventional 6T SRAM and alternative 7T SRAM cell designs to improve read stability, reduce power consumption, and enhance overall memory efficiency under voltage-scaling conditions. The design includes supporting peripheral circuitry such as decoders, timing generators, drivers, multiplexers, latches, and error detection blocks, all developed in a Cadence-based digital/analog design workflow.

The work aligns with the broader goal of designing memory systems suitable for portable electronics, edge devices, IoT platforms, and battery-powered applications where power efficiency and reliability are critical.

## Project objective

- Design and evaluate high-performance SRAM memory cells for energy-efficient operation
- Analyze the limitations of conventional 6T SRAM under low-voltage and high-speed conditions
- Improve read stability and reduce leakage/static power using alternative SRAM cell structures
- Develop complete memory architecture blocks for simulation, verification, and layout-level exploration
- Present the implementation in a clear, documented VLSI design flow

## Key design highlights

### 6T SRAM cell
- Conventional static memory cell architecture
- Widely used for compact SRAM implementation
- Baseline for comparison in performance, area, and stability analysis

### 7T SRAM cell
- Improved read sensing margin and voltage scalability
- Suitable for low-power and variation-tolerant operation
- Targeted for better read stability compared to 6T alternatives

### Peripheral circuitry
The project includes multiple supporting logic blocks and control modules, such as:

- 1-to-2 Decoder
- 2:1 MUX
- 3-input AND gate
- 3-to-8 Decoder
- WWL/RWL drivers
- Timing generator control circuits
- D flip-flop and latch blocks
- Output latch and error-detection logic
- Buffer and inverter cells

## Repository structure

```text
VLSI Project/
├── README.md
├── A_Low-Power_Variation-Tolerant_7T_SRAM_With_Enhanced_Read_Sensing_Margin_for_Voltage_Scaling.pdf
├── High Performance SRAM Design for Energy Efficient Systems.pptx
├── ECE_ZEROTH_REVIEW_FORM[1].docx
├── FYP P2 R1[1].docx
├── Final Report/
│   ├── Report.docx
│   ├── Final report.docx
│   └── ...
├── Phase 1 report/
│   ├── Report.docx
│   ├── Starting Report.docx
│   └── ...
├── Research Paper/
│   └── ...
├── Project Files (All)/
│   ├── 6tsram/
│   ├── 7t_sram/
│   ├── Main_Arch/
│   ├── Main_Arch_6T/
│   ├── Main_Arch_7T_test/
│   ├── 3_to_8_Decoder/
│   ├── WWL_RWL_Drivers/
│   ├── control_timing/
│   ├── error_detection/
│   └── ...
└── ...
```

## Tools and design environment

The project is implemented using a Cadence-based EDA workflow, typical for analog and mixed-signal VLSI design:

- Cadence Virtuoso
- Schematic design and symbol creation
- Layout and extracted views
- DRC/LVS-oriented design verification
- Simulation-driven optimization of SRAM cell behavior

## Typical workflow

1. Define the SRAM cell topology and transistor sizing
2. Create schematics and symbols for the cell and peripheral blocks
3. Run transient and DC simulations to evaluate read/write stability and power
4. Compare 6T versus 7T performance under target operating conditions
5. Assemble the memory architecture and control timing logic
6. Validate overall functionality using layout and extraction views

## Expected outcomes

This project aims to demonstrate that:

- SRAM performance can be improved through cell-level optimization
- 7T-based memory cells provide better read margin and robustness in low-voltage operation
- Power-aware VLSI memory design remains feasible for energy-efficient embedded systems
- Architectural design and peripheral logic are essential for realizing practical low-power SRAM macros

## Documentation included

The workspace contains project documentation and evaluation materials such as:

- phase review documents
- final project report
- research paper materials
- presentation deck
- project annexures and review forms

## License and usage

This repository is intended for academic and project documentation purposes. The design files and related material are provided as part of a student VLSI project and should be used for study, review, and educational reference.

## Contributors

- N. Umesh Surya Kiran
- Vaddi Ugandhar
- Guide: Dr. T. Ravi

## Related materials

- [Final Report](Final%20Report)
- [Phase 1 report](Phase%201%20report)
- [Project Files (All)](Project%20Files%20%28All%29)
- [Research Paper](Research%20Paper)

## Summary

This project demonstrates a complete approach to designing a high-performance SRAM memory architecture for energy-efficient systems, combining cell-level optimization with practical VLSI design methodology and supporting circuitry.
