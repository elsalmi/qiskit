# Qiskit Hub

This repository is a notebook archive for quantum-computing study. The main
path is the four tutorials under `Tutorials/`; the longer-term QGAN/music idea
is captured in the project plan and reference papers, but this repo itself is
not a finished QGAN implementation.

The clearest concrete result in the archive is the Bernstein-Vazirani notebook:
its qasm simulator output returns the expected hidden bitstring exactly.

## Core tutorials

| Notebook | What it shows |
| --- | --- |
| [1. Hello World.ipynb](Tutorials/1.%20Hello%20World.ipynb) | First Qiskit setup and a minimal circuit. |
| [2. Building Blocks of Quantum Circuits.ipynb](Tutorials/2.%20Building%20Blocks%20of%20Quantum%20Circuits.ipynb) | Basic gates and circuit construction. |
| [3. Quantum Teleportation Algoirthim.ipynb](Tutorials/3.%20Quantum%20Teleportation%20Algoirthim.ipynb) | Teleportation workflow and circuit wiring. |
| [4. Bernstein-Vazirani Algorithm.ipynb](Tutorials/4.%20Bernstein-Vazirani%20Algorithm.ipynb) | Deterministic single-shot output from the hidden-string example. |

## Supporting material

| Artifact | Purpose |
| --- | --- |
| [Quantum Gates Cheat Sheet.pdf](Tutorials/Quantum%20Gates%20Cheat%20Sheet.pdf) | Quick reference for gates and circuit symbols. |
| `Quantum Papers/` | Reference papers that informed the project direction. |
| [Final Project Plan.docx](Final%20Project%20Plan.docx) | Original capstone planning context. |

## Archived scratch

`Tutorials/Advocate Test Work Notebook.ipynb` is kept as scratch material and is
not part of the core tutorial path.

## Reproducibility

See [docs/REPRODUCIBILITY.md](docs/REPRODUCIBILITY.md) for the recommended
notebook order, environment expectations, and a note on the deterministic
Bernstein-Vazirani output.

## Scope

This repo is a study notebook set and reference archive. It is useful for
learning Qiskit and documenting the capstone direction, but it is not a
production quantum application.
