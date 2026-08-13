# Single-Phase-Auto-Transformer-Project

## Overview

This project presents the **design, construction, and experimental analysis of a single-phase shell autotransformer**. The transformer was designed with a target apparent power of approximately **80 VA**, a rated voltage of **210/22 V**, and an operating frequency of **50 Hz**.

The project combines transformer design calculations with practical winding, core selection, testing, and performance evaluation. It demonstrates how an autotransformer can provide voltage transformation using a **single winding with common and series sections**, resulting in reduced material usage and a compact construction.

## Objectives

* Optimize efficiency and power transfer while minimizing losses.
* Design a compact and lightweight transformer.
* Reduce material and manufacturing requirements through a shared winding.
* Ensure suitable operation without excessive saturation or overloading.
* Provide flexible voltage transformation through winding taps.
* Investigate practical performance through experimental testing.

## Design Specifications

| Parameter            | Specification                      |
| -------------------- | ---------------------------------- |
| Transformer type     | Single-phase shell autotransformer |
| Apparent power       | 80 VA                              |
| Rated voltage        | 210/22 V                           |
| Frequency            | 50 Hz                              |
| Cooling              | Air                                |
| Core material        | Silicon steel                      |
| Maximum flux density | 1.2 T                              |
| Core                 | E-1114H                            |

The selected core has a cross-sectional area of approximately **1132.5 mm²**, and the design uses **64 laminations**.

## Design Calculations

The design was developed from the selected core dimensions and maximum flux density.

Key calculated parameters include:

* Core cross-sectional area: **1132.5 mm²**
* Maximum flux density: **1.2 T**
* Maximum flux: approximately **1.359 × 10⁻³ Wb**
* Induced voltage per turn: approximately **0.302 V/turn**
* High-voltage winding turns: approximately **696 turns**
* Low-voltage winding turns: approximately **73 turns**

Wire gauges were selected according to the calculated current requirements, with **SWG-23** used for the higher-voltage section and **SWG-15** for the higher-current low-voltage section.

## Core & Winding Design

The transformer uses an **E-1114H silicon-steel laminated core**. The number of laminations and winding dimensions were selected while considering both magnetic requirements and the physical limitations of the transformer reel.

The calculated winding radial dimension was approximately **12.668 mm**, which remained within the available **15 mm winding space**.

## Experimental Tests

### Open-Circuit Test

The open-circuit test was performed to investigate the transformer core loss.

**Measured core loss: 7 W**

The test was conducted at the rated voltage with an LV-side current measurement of approximately **0.76 A**.

### Short-Circuit Test

The short-circuit test was used to determine the transformer copper loss.

**Measured copper loss: 4.5 W**

Measured currents were approximately:

* LV current: **3.4 A**
* HV current: **0.42 A**

### Load Test

A **200 W incandescent bulb** was connected to the low-voltage side.

Measured values:

* Input power: **16 W**
* Output power: **5 W**
* Measured efficiency: **31.25%**

The report notes that the relatively low efficiency is associated with the low-voltage tapping point. A higher-voltage tap, such as **100–150 V**, would reduce the current and consequently reduce copper losses, potentially resulting in significantly higher efficiency.

## Practical Design Challenges

The project involved several practical construction challenges, including:

* Selecting an appropriate number of core laminations.
* Maintaining the winding within the reel's physical dimensions.
* Selecting suitable SWG wire based on current capacity.
* Managing the air gap between winding layers.
* Achieving the required number of winding turns.
* Avoiding internal winding shorts.
* Preventing excessive flux density and core saturation.

Due to practical limitations in wire availability, the final transformer was wound with approximately **620 HV turns and 74 LV turns**, resulting in the final **210/22 V rating** rather than the initially considered higher voltage rating.

## Key Engineering Concepts

This project demonstrates practical knowledge of:

* Transformer design
* Autotransformer operation
* Magnetic circuit design
* Core selection
* Flux density calculation
* Turns-per-volt calculation
* Winding and wire-gauge selection
* Open-circuit testing
* Short-circuit testing
* Load testing
* Transformer losses
* Efficiency analysis
* Practical electrical machine construction

## Conclusion

The project successfully demonstrated the **design and construction of a compact single-phase autotransformer** while considering magnetic, electrical, and mechanical constraints. The experimental work provided practical insight into core losses, copper losses, winding limitations, voltage tapping, and efficiency.

A major observation was that the **voltage tapping point strongly affects efficiency**. Higher-voltage tapping reduces the winding current and therefore reduces copper loss, making higher efficiency achievable.

## Technologies / Skills

`Electrical Machine Design` `Transformer Design` `Autotransformer` `Power Systems` `Magnetic Circuits` `Core Design` `Winding Design` `Electrical Testing` `Efficiency Analysis` `Power Engineering`

