# ANSYS CFD Analysis – NACA 2412 Airfoil

## Overview

This project presents a computational fluid dynamics (CFD) analysis of a **NACA 2412 airfoil** using **ANSYS Fluent**.

The analysis involved preparing the airfoil geometry, creating a surrounding fluid domain, generating a computational mesh, defining the flow boundaries, and performing the CFD simulation to study the airflow around the airfoil.

## Software

* ANSYS Workbench
* ANSYS Fluent
* CFD-Post / ANSYS post-processing tools

## Airfoil

**NACA 2412**

The NACA 2412 airfoil was used as the aerodynamic geometry for the analysis.

## CFD Setup

The airfoil was placed inside a surrounding fluid domain to model the airflow around it.

The simulation setup included:

* Fluid domain surrounding the airfoil
* Computational mesh
* Airfoil surface defined as a wall
* Velocity inlet
* Pressure outlet
* Symmetry boundaries
* Wall boundaries

The ANSYS report shows the computational domain as a fluid region with the airfoil represented as a wall boundary.

## Mesh

A computational mesh was generated around the airfoil and surrounding flow region.

The ANSYS Fluent report recorded:

* **Nodes:** 385,644
* **Elements:** 383,903

The mesh provided the discretized domain required for solving the flow field around the airfoil.

## Boundary Conditions

The main boundary conditions identified in the Fluent setup were:

| Boundary         | Type            |
| ---------------- | --------------- |
| Airfoil          | Wall            |
| Inlet            | Velocity Inlet  |
| Outlet           | Pressure Outlet |
| Symmetry 1       | Symmetry        |
| Symmetry 2       | Symmetry        |
| Additional walls | Wall            |

## Results & Visualization

The repository contains the exported ANSYS figures and simulation visualizations showing the CFD setup and analysis results.

These include the geometry/domain, mesh, boundary setup, and post-processing visualizations generated during the analysis.

## Project Purpose

This project was carried out to gain practical experience with:

* Airfoil CFD analysis
* ANSYS Fluent workflow
* Computational domain creation
* Mesh generation
* Boundary-condition definition
* CFD simulation setup
* Visualization and interpretation of aerodynamic flow fields

## Files

The repository contains the available ANSYS analysis files, exported figures, and supporting project material.

---

**Software:** ANSYS Fluent
**Analysis Type:** CFD
**Airfoil:** NACA 2412
