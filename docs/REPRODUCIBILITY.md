# Reproducibility Notes

## Current state

This repository is notebook-first. It preserves the original study path and
reference material, but it does not pin a full packaged runtime.

## Recommended notebook order

Run the tutorial notebooks in this order:

1. `Tutorials/1. Hello World.ipynb`
2. `Tutorials/2. Building Blocks of Quantum Circuits.ipynb`
3. `Tutorials/3. Quantum Teleportation Algoirthim.ipynb`
4. `Tutorials/4. Bernstein-Vazirani Algorithm.ipynb`

`Tutorials/Advocate Test Work Notebook.ipynb` is scratch material and is not
part of the main path.

## Environment expectations

Use a Python 3 environment with Jupyter and a working Qiskit install
(`qiskit`, `qiskit-aer`, `numpy`, `matplotlib`). The archive does not pin a
single exact version set, so exact notebook rendering may vary slightly across
machines.

## Deterministic reference result

The Bernstein-Vazirani notebook ends with a qasm simulator result that returns
the expected hidden bitstring exactly:

```text
{'"'"'101010010101'"'"': 1}
```

## Hygiene

- Do not commit notebook checkpoints.
- Do not commit generated outputs unless they are part of the archival record.
- Keep the papers folder as reference material rather than execution input.
