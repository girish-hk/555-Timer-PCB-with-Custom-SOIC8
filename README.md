# 555 Timer PCB with Custom SOIC-8 Library – Fusion 360 and also Enclosure for it.

## Project Overview

This project documents my first complete PCB workflow in Autodesk Fusion 360 Electronics, where I designed a custom SOIC-8 component library from scratch and implemented it in a 555 timer PCB.

Instead of using a default library part, I created the full component package manually — including the schematic symbol, SMD footprint, device mapping, and 3D model integration — and then used that custom component in a working 555 timer astable circuit.

This project was done as part of my transition from KiCad to Fusion 360 to understand the complete electronics workflow in a new environment.

---

## What I Designed from Scratch

### 1. Custom SOIC-8 Library

- Created schematic symbol manually based on datasheet pin configuration
- Designed SOIC-8 SMD footprint (1.27 mm pitch)
- Defined pad dimensions and spacing using mechanical drawing reference
- Mapped symbol pins to PCB pads in the device editor
- Integrated 3D model for accurate PCB visualization
- Verified alignment in 3D PCB view

The footprint dimensions were derived from the Texas Instruments D0008A SOIC-8 mechanical specification.

---

## 2. 555 Timer Circuit Implementation

After building the custom library, I implemented a 555 timer in astable configuration:

- RC timing network
- Dual LED output
- Proper routing and placement
- Silkscreen labeling
- Board outline definition

The PCB was fully routed and verified before generating manufacturing outputs.

---

## 3. Manufacturing Outputs Generated

From the final PCB layout, I generated:

- Gerber files (RS-274X)
- NC Drill (Excellon) file
- Bill of Materials (BOM)
- Pick and Place file
- STEP file for mechanical integration

The project includes fabrication-ready outputs.

---

## Tools Used

- Autodesk Fusion 360 (Electronics workspace)
  
---

## What I Learned

- Complete custom component creation workflow
- Datasheet-based footprint design
- Symbol-to-footprint pin mapping
- 3D PCB verification
- Manufacturing file generation
- Assembly documentation export

This project helped me understand the full hardware development flow — from component definition to fabrication outputs.


---

## Enclosure Concept Design (Fusion 360)

To extend the PCB into a complete product-level concept, a custom enclosure was modeled in Fusion 360 and integrated with the 3D PCB assembly.

The enclosure was designed to validate mechanical fit, clearance, and component accessibility.

### Design Specifications

- Overall dimensions: 45.42 mm (L) × 34.38 mm (W) × 18 mm (H)
- Enclosure wall thickness: 2 mm
- Base clearance from PCB: 3 mm
- Side clearance: 5 mm
- PCB mounting standoff height: 4 mm
- LED and connector openings aligned with PCB layout

### Mechanical Integration Highlights

- PCB-to-enclosure alignment verified in 3D assembly
- Internal standoff-based PCB mounting structure
- LED visibility and external connector access defined
- Clearance validated for component height


---

## Reference

SOIC-8 mechanical dimensions referenced from Texas Instruments D0008A package specification.

