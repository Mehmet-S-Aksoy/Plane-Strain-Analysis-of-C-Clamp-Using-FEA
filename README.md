# FEA-Plane-Strain-Analysis-of-C-Clamp

 This repository presents a Finite Element Analysis (FEA) of a C-clamp under plane strain conditions. The study analyzes stress distribution when pressure is applied to inner surfaces, focusing on mesh refinement effects and numerical singularity. The material is structural steel with linear elastic assumptions.


## Key Features:

- **Plane strain analysis** of a C-clamp device under pressure.
- Applied forces of 100 kN on inner surfaces of the C-clamp.
- **Mesh refinement** to study the effects on stress regions and numerical singularity.
- **Structural Steel** as the material (default in ANSYS).
- Boundary conditions include fixed displacement on the top surface and applied forces on the inner surfaces.
- **Finite Element Method (FEM)** used for solving the boundary value problem.


## Simulation Overview:

In this analysis, the C-clamp device is subjected to pressure on its inner surfaces with the top part fixed. The primary goal is to understand the stress distribution and identify numerical singularities that occur when refining the mesh in certain regions.

We begin by defining the mathematical model, setting boundary conditions, and calculating hand results to compare with FEM outputs. The device's material is **Structural Steel** and the analysis assumes **small displacements**, **linear, isotropic** behavior, and **plane strain conditions**.


## Pre-Analysis:

1. **Mathematical Model**: This is a boundary value problem with boundary conditions on the edges and governing equilibrium equations.
2. **Hand Calculations**: The normal stress in the section is calculated due to the applied force and bending moment.
    - The normal stress due to the applied force is 4 MPa.
    - The normal stress due to the bending moment is calculated using the section's moment of inertia and distance from the neutral axis.
3. **Expected Results**: The resulting normal stress distribution is calculated and expected to be:
    - Compressive stress on the top surface: -44 MPa.
    - Tensile stress on the bottom surface: 52 MPa.
4. **Finite Element Solution**: The **Finite Element Method (FEM)** is used to solve for nodal displacements and post-process the results to obtain stress contour plots.


## Files:

The **FEA simulation file** for this analysis is available for download via Google Drive:

https://drive.google.com/file/d/13r05sEu5WoUsxdoa85VeVuJoZRt0rk_7/view?usp=sharing



## Conclusion:

This repository demonstrates the **plane strain analysis** of a C-clamp device under applied forces, with a focus on mesh refinement and its effect on stress distribution. The results are essential for understanding material behavior and numerical behavior in FEA, applicable to engineering applications requiring accurate stress predictions.


## Contact:

- LinkedIn: https://www.linkedin.com/in/mehmet-sabri-aksoy/
- Email: maksoy@uab.edu

