# Documentation

This directory contains the theoretical foundations, modeling methodologies, implementation details, experimental studies, and architectural decisions associated with the development of a Neural Network Based Digital Predistortion (DPD) framework for RF Power Amplifier (PA) linearization.

The documentation follows the complete research and development workflow adopted during the project, beginning with an introduction to Software Defined Radio (SDR) systems and RF transmitter architectures, followed by an investigation of Power Amplifier nonlinearities and conventional linearization techniques.

Subsequent sections cover the development of Memory Polynomial (MP) behavioral models, neural network based PA behavioral modeling, inverse modeling for digital predistortion, and validation using real communication system datasets. The final sections focus on fixed-point optimization, FPGA-oriented design considerations, SystemVerilog implementation, and hardware deployment methodologies.

## Documentation Roadmap

### 01. SDR and RF Background

Introduction to Software Defined Radio systems, wireless communication architectures, RF transmitter chains, and the role of Power Amplifiers in modern communication systems.

### 02. PA Nonlinearity and Linearization

Analysis of gain compression, spectral regrowth, constellation distortion, and commonly used linearization techniques for mitigating nonlinear PA effects.

### 03. Memory Polynomial Model

Mathematical formulation, coefficient extraction, implementation methodology, performance evaluation, and limitations of Memory Polynomial based behavioral modeling.

### 04. Neural Network PA Behavioral Model

Development of neural network based behavioral models for accurately reproducing Power Amplifier characteristics using measured datasets.

### 05. Neural Network Digital Predistortion

Inverse modeling methodology, DPD training workflow, performance evaluation, communication system validation, and weight extraction for hardware deployment.

### 06. FPGA Architecture and Deployment

Fixed-point optimization, SystemVerilog architecture, hardware implementation strategy, synthesis results, timing analysis, and FPGA deployment considerations.
