# Mode-I Fracture Analysis of 3D Printed CFRP Composites

A research-oriented project focused on investigating the Mode-I interlaminar fracture behavior of 3D-printed Carbon Fiber Reinforced Polymer (CFRP) composites using Double Cantilever Beam (DCB) experiments and finite element simulation in Abaqus.

---

## Project Overview

Carbon Fiber Reinforced Polymers (CFRPs) are lightweight, high-strength composite materials widely used in:
- Aerospace
- Automotive
- Civil engineering
- Structural applications

Despite their excellent in-plane strength, CFRPs are vulnerable to:
- Interlaminar failure
- Delamination
- Weak interlayer bonding

This project investigates the fracture behavior of 3D-printed CFRP composites under Mode-I loading conditions using:
- Experimental DCB testing
- Finite Element Analysis (FEA)
- Cohesive Zone Modeling (CZM)

---

## Objectives

- Determine Mode-I fracture toughness (G_IC)
- Perform DCB testing on CFRP and PLA specimens
- Develop Abaqus finite-element simulations
- Analyze crack initiation and propagation
- Validate experimental results using numerical simulation

---

## Technologies & Tools Used

### Software
- Abaqus/Standard
- Python
- Excel

### Experimental Equipment
- Universal Testing Machine (UTM)
- DCB Test Fixture

### Materials
- CFRP Filament
- PLA Specimens
- Epoxy-Hardener Adhesive

### Manufacturing
- FDM 3D Printing

---

## Experimental Methodology

### Double Cantilever Beam (DCB) Test

The DCB test was performed according to:
- ASTM D5528 Standard

### Specimen Dimensions

| Parameter | Value |
|-----------|-------|
| Length | 180 mm |
| Width | 25 mm |
| Thickness | 10 mm |
| Initial Crack Length | 70 mm |

### Printing Parameters

| Parameter | Value |
|-----------|-------|
| Nozzle Temperature | 210°C |
| Bed Temperature | 60°C |
| Layer Height | 0.2 mm |
| Infill Density | 100% |
| Raster Angle | 0° |

---

## Material Properties

| Property | Symbol | Value |
|----------|---------|-------|
| Longitudinal Modulus | E₁ | 159.3 GPa |
| Transverse Modulus | E₂ | 9.00 GPa |
| Elastic Modulus | E₃ | 7.52 GPa |
| Poisson Ratio | ν₁₂ | 0.324 |
| Shear Modulus | G₁₂ | 4.49 GPa |

---

## Finite Element Simulation

The DCB test was simulated using:
- Abaqus/Standard
- Cohesive Zone Modeling (CZM)

### Simulation Features
- Crack initiation prediction
- Delamination propagation
- Stress distribution analysis
- Energy release rate calculation
- Load-displacement curve generation

---

## Fracture Toughness Equation

G_IC = (3Pδ) / (2b(a + Δ))

Where:
- P = Applied Load
- δ = Displacement
- b = Specimen Width
- a = Crack Length
- Δ = Correction Factor

---

## Results

### Experimental Results

| Parameter | Specimen 1 | Specimen 2 |
|-----------|------------|------------|
| Peak Load | 45.47 N | 14.86 N |
| Displacement | 0.02638 m | 0.04028 m |
| G_IC | 1029 J/m² | 513 J/m² |

### Simulation Result
- Abaqus Predicted G_IC ≈ 950 J/m²

### Key Observations
- Strong correlation between experimental and simulation results
- Better interlayer bonding improved fracture toughness
- Weak bonding caused early delamination
- Printing quality significantly affected performance

---

## Repository Structure

```bash
├── Abaqus_Simulation/
├── Experimental_Data/
├── Graphs/
├── Images/
├── README.md
```

---

## Applications

- Aerospace structures
- Lightweight automotive components
- Structural composite design
- Additive manufacturing research
- Fracture mechanics studies

---

## Future Improvements

- Multi-directional raster analysis
- Mixed-mode fracture analysis
- Dynamic loading simulations
- Machine learning-based fracture prediction

---

## Learning Outcomes

- Fracture mechanics concepts
- Abaqus finite element modeling
- Cohesive Zone Modeling (CZM)
- Experimental DCB testing
- Composite material behavior

---

## Author

**Dhaval Nikam**  
B.Tech Project  
Indian Institute of Technology Goa

Faculty Adviser:  
**Prof. Sandip Halder**

---

## References

- ASTM D5528 Standard
- Abaqus Documentation
- NASA Technical Reports
- Research papers on CFRP fracture mechanics

---

## License

This project is developed for academic and research purposes.
