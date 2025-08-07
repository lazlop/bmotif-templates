# Building Motif Templates

This repository contains building motif templates and SHACL shapes for semantic modeling and validation of HVAC systems using the ASHRAE 223P standard. The templates enable automated generation of building system models, while the shapes provide validation and inference capabilities for ensuring model compliance with specific control strategies and standards. This repository also includes example models prepared using these templates and validated using these shapes.

## Repository Structure

The repository is organized into three main components:

### 📋 Guideline 36 (`guideline36/`)
ASHRAE Guideline 36 compliant system templates and validation shapes.

- **Templates**: Comprehensive models of G36 compliant systems based on system diagrams from Guideline 36's informative appendix
- **Shapes**: SHACL constraints defining G36 data requirements for air-side equipment (Section 4), including validation rules and inference capabilities for equipment labeling
- **Models**: Example system models created using these templates, also stored at models.open223.info

modeled systems:
- Multi-zone VAV AHU
- Single-zone VAV AHU  
- Dual-duct AHU
- VAV terminal units
- Fan-powered terminal units
- Dual-duct terminal units

### 🌡️ Hot Water Reset (`hot-water-reset/`)
Templates and shapes for a field test of hot water temperature reset control strategies at a real large building.

- **Templates**: Templates for a model of a real building HVAC system
- **Shapes**: Validation rules ensuring systems have necessary equipment and data points for hot water reset strategy deployment
- **Models**: Anonymized model of a real medium-large building created using these templates, where the application was deployed

### 🔄 HPFlex-MPC (`hpflex-mpc/`)
Heat pump flexibility model predictive control (MPC) templates and shapes.

- **Templates**: Templates for modeling of small-medium commercial buildings with packaged RTUs for an MPC application
- **Shapes**: Generated validation and inference rules for MPC configuration, enabling survey-driven setup of MPC and alignment of S223 with MPC data model and other ontology (Brick)
- **Models**: Anonymized version of a small building modeled using these templates, where this application was deployed

## File Types

- **`.yml` files**: YAML template definitions for building system components
- **`.ttl` files**: Turtle/RDF SHACL shape definitions for validation and inference
- **`README.md`**: Description of folder contents
