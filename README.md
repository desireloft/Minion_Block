# Minion Block Assembly

## Overview

This repository showcases a Minion-themed block assembly designed in **SolidWorks** to demonstrate my expertise in CAD modeling, configuration management, and technical documentation. The project features a modular Minion assembly built from block components with multiple configurations, a wheel-hub eye assembly, technical drawings, and STEP files for interoperability. The design leverages SolidWorks configuration tables to create various block sizes and shapes, optimized for manufacturing and prototyping (e.g., 3D printing), highlighting skills in efficient parametric design and assembly modeling.

## Project Details

The Minion Block Assembly is a creative mechanical design that constructs a Minion character using modular block components, inspired by block-based construction toys. The project emphasizes proficiency in:

- SolidWorks configuration management for creating multiple part variants from base models.
- Assembly modeling with precise component mating to form a cohesive Minion character.
- Technical drawing creation for manufacturing and assembly visualization.
- Exporting interoperable STEP files for prototyping or collaboration.
- Consideration of manufacturing processes (e.g., injection molding, 3D printing) and rapid prototyping workflows.

### Components

The Minion assembly is built from the following key models, with configurations defined via SolidWorks configuration tables:

1. **1x2 Block (`1X2 BLOCK.SLDPRT`)**:
   - A base block model with two configurations:
     - **1x2 Block**: Standard rectangular block for structural components.
     - **1x2 Angle Block**: Angled variant for specialized Minion features.
   - Used in various quantities to form parts of the Minion’s body.
2. **2x2 Block (`2X2 BLOCK.SLDPRT`)**:
   - A versatile block model with multiple configurations:
     - **2x2 Block**: Standard square block.
     - **2x2 Block with Shaft**: Includes a shaft for rotational components (e.g., eye attachment).
     - **2x3 Block, 2x4 Block, ..., 2x10 Block**: Extended lengths for larger structural elements.
3. **2x2 Short Block (`2X2 SHORT BLOCK.SLDPRT`)**:
   - A shorter block model in height with multiple configurations:
     - **2x2 Short Block, 2x3 Short Block, 2x4 Short Block, 2x5 Short Block, 2x6 Short Block**: Varying lengths for compact structural elements.
     - **4x2 Short Block, 4x3 Short Block, 4x4 Short Block, 4x5 Short Block, 4x6 Short Block**: Wider variants for broader features.
4. **Eye Assembly (`EYE.SLDASM`)**:
   - A sub-assembly comprising:
     - **Wheel (`WHEEL.SLDPRT`)**: Circular component representing the Minion’s eye lens.
     - **Hub (`HUB.SLDPRT`)**: Central component for eye attachment.
     - **Wheel-Hub Assembly (`WHEEL-HUB ASSY.SLDASM`)**: Combines wheel and hub for functional eye motion.
5. **Minion Assembly (`Final Assy.SLDASM`)**:
   - The complete assembly integrating various block configurations, eye assembly, and other components (e.g., `HEAD WITH NECK.SLDASM`, `MAIN UPPER BODY.SLDASM`, `MINION LEG.SLDASM`).
   - Features an **exploded view** in the technical drawing to illustrate assembly sequence.

### Technical Drawings

- **Individual Part Drawings**:
  - Detailed drawings for `1X2 BLOCK.SLDPRT`, `2X2 BLOCK.SLDPRT`, `2X2 SHORT BLOCK.SLDPRT`, `WHEEL.SLDPRT`, and `HUB.SLDPRT`.
  - Include dimensions and annotations for manufacturing, with tolerance.
- **Assembly Drawings**:
  - Comprehensive drawing for `Final Assy.SLDASM` with an exploded view.
  - Sub-assembly drawings.
  - Includes a **Bill of Materials (BOM)** listing all components and configurations.
- **PDF Exports**:
  - All drawings are exported as PDFs for easy sharing and review (located in the `PDF/` folder).

### STEP Files

- STEP files (`.stp`) are provided for key parts and assemblies (`Final Assy.stp`, `EYE.SLDASM.stp`, etc.) to enable:
  - Interoperability with other CAD software (e.g., Fusion 360, etc.).
  - Rapid prototyping.
  - Compatibility with manufacturing processes like injection molding or machining.
