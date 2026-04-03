# 📌 Hybrid Octet–Voronoi Lattice Scaffold

 **B.Tech Project (BTP) — Ongoing Research & Development**
 
Computational design, optimization, and validation of a hybrid bio-inspired lattice structure for potential biomedical implant applications.

---

## 📖 Overview

The core objective of this project is to develop a mechanically optimized, bioresorbable polymer scaffold that mimics natural bone architecture. To achieve this, the project combines two distinct topologies:
* **Periodic Octet-Truss Lattice (Core):** Ensures predictable and robust load-bearing behavior.
* **Stochastic Voronoi Lattice (Outer Shell):** Mimics natural trabecular bone to enhance osseointegration and reduce stress shielding.

---

## 🚧 Current Status

**Active**

This is an ongoing research and development project. The objective is to build a complete, end-to-end pipeline from **parametric design → geometry processing → finite element validation → physical testing**.

---

## ⚙️ Methodology & Scope

### 1. Parametric Lattice Generation
* **Grasshopper-based workflow** for generating 3D Voronoi structures.
* Granular control over parameters like point spacing, strut thickness, and target porosity (~60%).

### 2. Standardized Geometry Design
* Models are strictly constrained to **ASTM D695** compression testing dimensions.
* **Domain size:** 25.4 × 12.7 × 12.7 mm.

### 3. Hybrid Topology Integration
* Merging the structured octet-truss core with the irregular Voronoi outer topology.
* **Aim:** Reduce stress concentrations and improve overall load distribution across the model.

### 4. FEA & Meshing Challenges
* Resolving complex, overlapping lattice intersections in **ANSYS**.
* Utilizing patch-conforming tetrahedral meshing to overcome standard geometry failures.

### 5. Material Modeling
* Simulating the mechanical response and evaluating the stress distribution of a **PLA-based scaffold**.

---

## 🎯 Primary Objectives

- [x] Mitigate stress shielding through bio-mimetic design.
- [x] Emulate the organic architecture of natural bone.
- [ ] Ensure reliable performance under compression, impact, and cyclic loading.

---

## 🔬 Future Work Roadmap

- [ ] Dynamic impact and fatigue testing simulations.
- [ ] Physical validation using a Universal Testing Machine (UTM).
- [ ] AI/ML-based topology optimization (utilizing Python).
- [ ] Physical manufacturing via FDM (Fused Deposition Modeling) 3D printing.

---

## 🧠 Tech Stack

* **CAD / Parametric Design:** Rhino 3D + Grasshopper
* **Simulation / FEA:** ANSYS (Static Structural)
* **Manufacturing:** Additive Manufacturing (FDM)
* **Optimization / Scripting:** Python *(Planned)*

---

*Note: This project is part of an ongoing Bachelor’s Thesis (BTP) and is under continuous development.*
