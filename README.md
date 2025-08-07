# Building Motif Templates

This repository contains building system templates and SHACL shapes for semantic modeling and validation of HVAC systems using the ASHRAE 223P standard. The templates enable automated generation of building system models, while the shapes provide validation and inference capabilities for ensuring model compliance with specific control strategies and standards.

## Repository Structure

The repository is organized into three main components:

### 📋 Guideline 36 (`guideline36/`)
ASHRAE Guideline 36 compliant system templates and validation shapes.

- **Templates**: Comprehensive models of G36 compliant systems based on system diagrams from Guideline 36's informative appendix
- **Shapes**: SHACL constraints defining G36 data requirements for air-side equipment (Section 4), including validation rules and inference capabilities for equipment labeling

Supported systems:
- Multi-zone VAV AHU
- Single-zone VAV AHU  
- Dual-duct AHU
- VAV terminal units
- Fan-powered terminal units
- Dual-duct terminal units

### 🌡️ Hot Water Reset (`hot-water-reset/`)
Templates and shapes for hot water temperature reset control strategies.

- **Templates**: Real building models for deploying energy-efficient supervisory control with hot water temperature setpoint reset
- **Shapes**: Validation rules ensuring systems have necessary equipment and data points for hot water reset strategy deployment

### 🔄 HPFlex-MPC (`hpflex-mpc/`)
Heat pump flexibility model predictive control (MPC) templates and shapes.

- **Templates**: Support deployment of portable load-shifting MPC for packaged RTUs in small/medium commercial buildings
- **Shapes**: Generated validation and inference rules for MPC configuration, enabling survey-driven setup and cross-ontology compatibility (223P/Brick)

## File Types

- **`.yml` files**: YAML template definitions for building system components
- **`.ttl` files**: Turtle/RDF SHACL shape definitions for validation and inference
- **`description.md`**: Detailed documentation for each component
