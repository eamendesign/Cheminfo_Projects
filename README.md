
---
# Cheminformatics

Minimal **Python examples for cheminformatics and materials informatics tools**.

This repository demonstrates the basic usage of several widely used libraries for **molecular and materials modeling**.
Designed for **students and beginners** learning computational chemistry with Python.

---

## Modules

**C1 — RDKit**
Basic molecular cheminformatics: SMILES parsing, molecular structures, descriptors, fingerprints, and similarity.

**C2 — ASE**
Atomic Simulation Environment examples for building molecules/crystals, structure manipulation, and simulation workflows.

**C3 — OpenBabel**
Chemical format conversion and molecular data handling using the Pybel interface.

**C4 — Pymatgen**
Materials science toolkit for crystal structures, file I/O, and materials analysis.

**C5 — YAML**
Human-readable configuration language for defining simulation inputs and workflow parameters.

**C6 — TOML**
Minimal and structured configuration format for managing project settings and outputs.

---

## Purpose

This project provides **simple, practical scripts** to help students quickly understand how Python tools are used in:

* cheminformatics
* computational chemistry
* materials modeling

---

## Installation

It is recommended to install dependencies using **conda-forge**:

```bash
conda create -n cheminfo python=3.10
conda activate cheminfo

conda install -c conda-forge rdkit
conda install -c conda-forge ase
conda install -c conda-forge openbabel
conda install -c conda-forge pymatgen
```

---

## Ongoing Development

This repository is **continuously evolving**.
More examples, tutorials, and educational scripts will be added over time to expand coverage of **cheminformatics and materials modeling workflows**.

---
