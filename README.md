# GSoC 2026 — QML-HEP Evaluation Tasks

Evaluation tasks for the **Equivariant Quantum Neural Networks for HEP Analysis at the LHC** project (ML4Sci).

## Tasks

| Task | Description | Framework |
|------|-------------|-----------|
| **Task I** | Quantum circuits — Hadamard, CNOT chain, SWAP, swap test | Cirq |
| **Task II** | Quark/Gluon jet classification — GCN vs GAT on ParticleNet data | PyTorch Geometric |
| **Task III** | Open task — Commentary on symmetry-aware quantum circuits for HEP | — |
| **Task VII** | Z₂×Z₂ equivariant QNN vs standard QNN | PennyLane |

## How to run

All notebooks can be run on [Google Colab](https://colab.research.google.com/). Task II requires a GPU runtime for reasonable training times.

**Dependencies:**
- `pennylane` (Tasks I, VII)
- `cirq` (Task I)
- `torch`, `torch-geometric` (Task II)
- `scikit-learn`, `matplotlib`, `numpy` (Tasks II, VII)
