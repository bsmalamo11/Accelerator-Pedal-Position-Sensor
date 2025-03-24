# Accelerator Pedal Position (APP) Sensor Validation

## Overview
This project focuses on validating an Accelerator Pedal Position (APP) sensor using Model-Based Design (MBD) in Simulink. It includes fault detection mechanisms, signal validation, and embedded C code generation for real-time execution.

## Features
- **Sensor Signal Processing**: Reads APP sensor signals and processes them for validation.
- **Fault Detection**: Identifies sensor failures, including out-of-range values and discrepancies.
- **Model-In-the-Loop (MIL) & Software-In-the-Loop (SIL) Testing**: Ensures reliability through simulations before deployment.
- **Embedded C Code Generation**: Uses Simulink Coder to convert models into C code for embedded applications.

## System Structure
The project consists of:
1. **APP Model**: Processes sensor signals and applies validation logic.
2. **Failure Detection Logic**: Compares sensor readings against defined thresholds.
3. **MIL & SIL Testing**: Ensures correctness before deploying the model in embedded systems.
4. **Code Generation**: Generates efficient C code for ARM-based microcontrollers.


### Prerequisites
- MATLAB/Simulink (R2024a or later recommended)
- Simulink Coder (for C code generation)
- Embedded Coder (optional, for optimized embedded implementation)
