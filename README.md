# combine_xyz_structures
building script for combining xyz structures

A lightweight Python utility to merge two atomic structures—such as a magnesium nanoparticle (Mg NP) and a CPDT molecule—into a single `.xyz` file.

## Description

This script provides a simple and flexible tool for:

- Reading two atomic structures in standard `.xyz` format.
- Merging them into a single structure file `combined.xyz`, while preserving format integrity (number of atoms and comment line).
- Facilitating the preparation of composite systems such as NP–molecule assemblies.

# Use Case

Designed for computational studies involving nanoparticle–molecule interactions (e.g., Mg NPs and CPDT molecules), particularly for simulations related to strong coupling phenomena, hot carrier generation, and optical response modeling.

# Ideal for workflows involving:

- Structure setup for **DFT** and **TDDFT** simulations (e.g., using GPAW).
- Visualization with tools like VMD, ASE GUI, or Avogadro.
- Rapid prototyping in data-driven materials design.

This script was developed as part of the computational workflow for the following research article:

**Rania Zaier, et al.**  
**Influence of molecular structure on the coupling strength to a plasmonic nanoparticle and hot carrier generation, Nanoscale, 2024.**  
# DOI: 10.1039/d4nr01198h
