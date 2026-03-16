
# Pyramidal Horn Antenna Design & Simulation

This project involves the complete design cycle of a high-gain pyramidal horn antenna, from initial mathematical calculations to full-wave EM simulation using Ansys HFSS.

## Project Overview

The objective was to design an antenna with a specific target gain of **25 dB** at an operating frequency of **14 GHz**. The antenna is fed by a standard **WR-62 waveguide**.

### Design Specifications

* **Operating Frequency:** 14 GHz 
* **Target Gain:** 25 dB 
* **Feed Type:** WR-62 Waveguide 
* **Aperture Efficiency ($\epsilon_{ap}$):** 51.8% 

---

## Technical Parameters

The design was optimized to meet performance requirements through MATLAB calculations and verified via Ansys HFSS 2023 R2.

### Physical Dimensions

| Parameter | Description | Value (mm) |
|-----------|-------------|------------|
| A | Aperture Width | 166.89 |
| B | Aperture Height | 133.67 |
| Rp | Horn Length | 392.25 |

### Performance Comparison

| Metric | MATLAB (Calculated) | HFSS (Simulated) |
|------|----------------------|------------------|
| Gain (dB) | 25.00 | 25.20 |
| Gain (W/W) | 316.23 | 330.94 |
| E-Plane Beamwidth | 8.64° | 8.52° |
| H-Plane Beamwidth | 10.02° | 9.94° |

---

## Simulation Results

The antenna shows excellent performance across the target frequency range.

* **S-Parameters:** The $|S_{11}|$ return loss remains below -30 dB at 14 GHz, indicating a very efficient impedance match.
* **Radiation Pattern:** Highly directional beam with well-defined E-plane and H-plane patterns.

## Repository Contents
* **Simulation:** HFSS project files and design properties.

* **Calculations:** MATLAB scripts for design parameter verification.

* **Results:** Detailed tables comparing calculated vs. simulated data.

* **Plots:** $S_{11}$ frequency response and 2D/3D radiation patterns. 

## Tools Used
* **Ansys HFSS 2023 R2 (Student Edition):** EM Simulation.
* **MATLAB:** Numerical calculations.
---
Developed as part of the Wave Transmission and Reception (EE 557/457) curriculum at Western New England University.
