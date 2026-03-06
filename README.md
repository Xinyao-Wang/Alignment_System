# Alignment System

Mechanical design project for a **laser alignment system** intended to precisely point a laser in a predetermined direction during assembly, with a removable adjustment mechanism and a locking mechanism to hold the final position. The repository currently contains four concept prototypes plus the final design report and presentation. :contentReference[oaicite:0]{index=0} :contentReference[oaicite:1]{index=1}

## Overview

This project was developed as **AS-1** for **ME175C**. The final design uses:

- a **two-axis adjustment mechanism**
- a **ball-joint-based fixing mechanism**
- **gear-driven angular adjustment**
- a **threaded-bolt mechanism** for controlled extension and shortening

The design targets precise manual alignment for applications where pointing accuracy matters, such as UAV-mounted systems and other directional devices.

## Design Requirements

The system was designed to satisfy the following requirements:

- **Adjustment range:** ±10°
- **Adjustment accuracy:** 0.2° to 0.4°
- **Mass:** under 500 g
- **Control dimensions:** 2-axis (roll and pitch)
- **Working temperature:** 0°C to 40°C
- **System size:** about 200–220 mm scale

These requirements and verification targets are documented in the final report and presentation. :contentReference[oaicite:5]{index=5} :contentReference[oaicite:6]{index=6}

## Final Design

The final concept combines an **adjustment mechanism** and a **fixing mechanism**:

- The **adjustment mechanism** uses an upper threaded adjustment path and a lower worm-gear path to control the laser orientation.
- The **fixing mechanism** uses a **ball joint** and locking structure to hold the aligned laser in place once adjustment is complete.
- After alignment, the adjustment structure can be removed while preserving the final laser direction. :contentReference[oaicite:7]{index=7} :contentReference[oaicite:8]{index=8}

## Verification Summary

The design was evaluated using **SolidWorks modeling** and **MATLAB analysis**.

### Accuracy
The report verifies that the design can achieve the required fine angular resolution, with estimated adjustment accuracy below **0.4°**, meeting the design target. :contentReference[oaicite:9]{index=9}

### Range of motion
The calculated movement range reaches about **10.36°**, satisfying the required **10°** alignment range. :contentReference[oaicite:10]{index=10}

## Repository Contents

This repository includes the following main items:

- `Prototype 1/`
- `Prototype 2/`
- `Prototype 3/`
- `Prototype 4/`
- `AS-1 Final Design Report.pdf`
- `AS-1 Final Presentation.pdf` :contentReference[oaicite:11]{index=11}

## Design Process

Four concept directions were explored before selecting the final design:

1. detachable mechanical-arm-based alignment
2. double-gear alignment with fixture system
3. ball-joint platform with perpendicular link adjustments
4. three-bolt height-adjustment platform

A decision matrix was then used to compare concepts on criteria such as weight, simplicity, safety, efficiency, precision, and ease of operation. :contentReference[oaicite:12]{index=12} :contentReference[oaicite:13]{index=13}

## Manufacturing Notes

The project includes component-level design for manufacturability, with parts made from materials such as:

- acetal rod
- UHMW sheet
- mild steel
- standard mechanical hardware

Detailed part and assembly drawings are included in the final report appendix. :contentReference[oaicite:14]{index=14} :contentReference[oaicite:15]{index=15}

## Files

- **Final Design Report:** complete design description, requirements, concept evaluation, verification, MATLAB analysis, and drawings
- **Final Presentation:** concise summary of the project scope, concepts, final design, and validation
- **Prototype folders:** concept development files for the four design directions :contentReference[oaicite:16]{index=16}

## Tools Used

- **SolidWorks** for CAD modeling and design visualization
- **MATLAB** for range and adjustment analysis
- standard mechanical design and manufacturability methods based on the project workflow described in the report and presentation. :contentReference[oaicite:17]{index=17} :contentReference[oaicite:18]{index=18}

## Authors

- Dongwei Li
- Xinyao Wang
- Shi Cheng
- Deng Pan :contentReference[oaicite:19]{index=19}

## Course Information

**Course:** ME175C  
**Team:** AS-1  
**Project:** Alignment System  
**Date:** June 2020 :contentReference[oaicite:20]{index=20}

## Notes

This repository serves as an archive of the project’s concept development, final design documentation, and presentation materials.
