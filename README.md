# Neural Network Based Digital Predistortion (DPD) on FPGA for RF Power Amplifier Linearization

## Overview

This repository presents the development and FPGA implementation of a Neural Network based Digital Predistortion (DPD) framework for mitigating nonlinear distortion in RF Power Amplifiers (PAs).

The work encompasses:

- RF Power Amplifier behavioral modeling
- Memory Polynomial (MP) modeling and evaluation
- Neural Network based PA modeling
- Neural Network based Digital Predistortion (DPD)
- Performance evaluation using NMSE and ACPR
- Fixed-point optimization for hardware deployment
- FPGA implementation using SystemVerilog
- Vivado synthesis and implementation
- Validation using real communication system datasets

---

## Project Workflow

```text
RF Dataset
    ↓
PA Behavioral Modeling
    ↓
Neural Network Training
    ↓
Digital Predistortion (DPD)
    ↓
Weight Extraction
    ↓
Fixed-Point Conversion
    ↓
SystemVerilog RTL Design
    ↓
FPGA Implementation
    ↓
Hardware Validation
```

---

## Repository Structure

```
docs/
python/
matlab/
rtl/
vivado/
results/
images/
```


