# Forward Collision Warning (FCW) System

A MATLAB/Simulink-based **Forward Collision Warning (FCW)** system developed using the **Model-Based Design (MBD)** approach. The project estimates collision risk using **Safe Braking Distance (Ds)** and **Time-to-Collision (TTC)** calculations and generates appropriate warning levels for the driver.

The controller was validated through **Model-in-the-Loop (MIL)**, **Software-in-the-Loop (SIL)**, and **Processor-in-the-Loop (PIL)** testing using the **STM32 Nucleo-F446RE** development board.

---

## Features

- Safe Braking Distance (Ds_min & Ds_max) calculation
- Time-to-Collision (TTC) estimation
- Multi-level warning generation using Stateflow
- Model-Based Design workflow
- Automatic Embedded C code generation
- MIL, SIL, and PIL validation on STM32

---

## Repository Contents

| File | Description |
|------|-------------|
| **fcw.slx** | Main Simulink model of the Forward Collision Warning system. |
| **dataset.xlsx** | Representative input dataset used for simulation and testing. |
| **fcw_ppt.pdf** | Project presentation summarizing the implementation and results. |
| **fcw_report.pdf** | Detailed project report including methodology, implementation, validation, and conclusions. |
| **README.md** | Repository overview and project documentation. |

---

## Software Used

- MATLAB R2026a
- Simulink
- Stateflow
- Embedded Coder
- STM32CubeIDE
- STM32CubeProgrammer

---

## Hardware Used

- STM32 Nucleo-F446RE
- STM32F446RE (ARM Cortex-M4)
- ST-LINK Programmer

---

## Validation

The developed FCW controller was verified using:

- Model-in-the-Loop (MIL)
- Software-in-the-Loop (SIL)
- Processor-in-the-Loop (PIL)

---

## Note

The dataset included in this repository was created for project demonstration and testing purposes. It is representative in nature and should not be considered real-world driving data.

---

## Authors

Developed as part of the **KPIT Apex Lab Internship**.

### Team Members

- Omkar Meher
- Swapnil Kumbhar
- Prathmesh Lokhande

### Mentor

- Shubhada Mane
