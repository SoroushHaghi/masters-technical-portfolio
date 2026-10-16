# Computing, Algorithms & Optimization

[← Portfolio overview](../README.md) · [All courses and evidence](../COURSE_COVERAGE.md) · [Communication & coding →](communication-information-coding.md) · [Devices & physical systems →](quantum-devices-physical-systems.md)

**Scientific question:** How can computational problems be represented, analyzed, simulated and solved using classical and quantum algorithms?

This domain links quantum information foundations with computer-science algorithms, optimization, and scientific programming. **Topics covered in class are not automatically independently implemented skills.**

## Master's coursework and external training

| Course or training | Source-supported topics | Evidence status |
| --- | --- | --- |
| **Introduction to Quantum Information Technology and Quantum Computing** | State vectors, density operators, measurement, tensor products, entanglement, gates, channels, information-theoretic quantum concepts | Passed M.Sc. coursework |
| **Advanced Quantum Technology for Engineers** *(cross-listed)* | Quantum-mechanical operators and eigenvalue problems, Schrödinger dynamics, perturbation methods, multi-particle principles, platform foundations | Passed M.Sc. coursework; primarily analytical |
| **Applied Quantum Computing: Basics and Devices** *(cross-listed)* | Qubit/circuit concepts; DiVincenzo criteria, physical qubit platforms, coherence and hardware constraints | Passed M.Sc. coursework; device principles rather than demonstrated control-code development |
| **Algorithms and Complexity for Quantum Computing** | Computational problems as languages, polynomial-time certificates, 2-qubit separability, quantum Fourier transform and algorithmic complexity | A **5-ECTS graded examination/component passed**; official module-completion annotation requires separate confirmation |
| **Approximation Algorithms** | Approximation guarantees, reductions, matching, Set Cover/Set Packing, LP and primal–dual methods, Bin Covering, metric TSP, Max-Cut and Steiner Tree | **Studied topics only; no completed-module credential claimed** |
| **Quantum Programming Languages** *(ongoing, external to the TU degree)* | Foundations, optical/continuous-variable computation, adiabatic optimization, Qiskit circuits, Bernstein–Vazirani, Simon, and introductory VQE | [Public topic-oriented learning repo](https://github.com/SoroushHaghi/quantum_programming_languages_lab); AI-assisted reference code exists, personally executed/tested results not yet verified |

## Scientific topics

### Quantum information and circuit models
- Linear algebra in Hilbert spaces; Dirac notation; normalization and operators.
- Unitary/Hermitian operations, tensor products and measurement.
- Single- and multi-qubit gates, Bell states, entanglement and no-cloning.
- Density operators, quantum channels and measurement concepts.
- Pauli matrices, Bloch sphere, controlled operations, elementary state transformations.

### Quantum algorithms and computational complexity
- Classical versus quantum computational models; reversible operations and oracle interfaces.
- Two-qubit pure-state separability can be checked through a vanishing coefficient determinant, `γ00γ11 − γ01γ10 = 0`, in the source's computational-basis setting; this is theoretical linear-algebra work.
- Complexity theory: decision problems represented as languages, certificates enabling polynomial-time verification of yes-instances, P, NP, BPP, BQP and reductions at coursework level.
- Course discussion of the Deutsch black-box/oracle problem and QFT roots-of-unity structure, with introductory Shor/order-finding context; Grover/amplitude-amplification details have partly **classmate-supported reconstruction** provenance. **No personal implementation implied**.
- In QPL: Bernstein–Vazirani and Simon’s oracle setting, phase kickback and GF(2) post-processing as taught topics.

### Classical and quantum optimization
- Selected graph/optimization homework: Independent Set-to-Vertex Cover reasoning, directed acyclic subgraphs, geometric diameter, maximal matchings, Bin Covering ILP, Set Cover/Set Packing, LP relaxations and primal–dual methods.
- Metric versus unrestricted TSP, local-search Max-Cut guarantees and metric Steiner Tree constructions are also documented as **assigned theoretical problems**, not student-built software.
- Approximation Algorithms provides **source-supported studied topics** from a course **not claimed as completed**; instructor exercise sheets do not alone prove independent solution of every assignment.
- Adiabatic Hamiltonian interpolation, gaps, quantum annealing, Max-Cut/Ising/QUBO encodings at QPL coursework level.
- Parameterized quantum circuits, expectation values, classical optimizers and introductory VQE; future optimization experiments must be personally executed and verified.

### Physical computing interfaces
- The distinction between abstract algorithms and implementation on superconducting, trapped-ion and photonic hardware.
- Coherence, physical resources, DiVincenzo criteria and noise considerations as **academic knowledge**, not calibration/hardware execution experience.

## Four-semester provenance and code audit

- **QIT and QTC** are overlapping source collections of the introductory quantum-information curriculum. They are not counted as two independent university pass results.
- Three Python solution scripts stored with *Applied Quantum Computing* identify an external instructor author; they are **not personally authored quantum-software artifacts**.
- Two `build_visuals.py` files from the ACQC `_AI_WORKSPACE` create educational illustrations; no personal end-to-end execution, quantum-algorithm implementation or validation is established.
- Some later ACQC QFT, Shor and Grover notes derive from classmate-provided material and AI-supported reconstruction. They remain learning references with lower provenance confidence than lecturer recordings.
- The formal ACQC graded component is recorded as passed in the academic record, while completion of the parent module remains separately unresolved. *Approximation Algorithms* has studied-topic evidence without course completion.

## Existing public learning work

### [Quantum Programming Languages — Learning Lab →](https://github.com/SoroushHaghi/quantum_programming_languages_lab)

The repository currently organizes material by **scientific topic**, including quantum foundations, photonic continuous variables, adiabatic optimization, Qiskit simulation, oracle algorithms and variational methods.

Illustrative AI-assisted study code includes GHZ-state, Bernstein–Vazirani and small VQE examples. The source README explicitly notes that **a full Qiskit runtime execution and independent student verification have not yet been established**. These files are learning references, not proof of completed original research or independently built quantum software.

### Existing software foundations, outside the M.Sc. coursework claim

Separately documented Python/ML project experience and AI-assisted system development support general programming and engineering ability. They must not be silently re-labeled as quantum-software implementation. The [Career OS framework](https://github.com/SoroushHaghi/career-os) is a separate software/system-design project, not a quantum algorithm.

## Connections to other domains

- **Quantum error correction:** Classical coding, Hamming distance and syndrome ideas are described under [Communication, Information & Coding Theory](communication-information-coding.md); a quantum demonstration would require separate student implementation and validation.
- **Quantum hardware:** The practical physical constraints on gates and qubits connect to [Quantum Devices & Physical Systems](quantum-devices-physical-systems.md).
- **QPL topic pages:** [Quantum foundations](https://github.com/SoroushHaghi/quantum_programming_languages_lab/blob/main/topics/quantum-foundations-and-gates.md) · [Qiskit circuits](https://github.com/SoroushHaghi/quantum_programming_languages_lab/blob/main/topics/qiskit-circuits.md) · [Oracle algorithms](https://github.com/SoroushHaghi/quantum_programming_languages_lab/blob/main/topics/oracle-algorithms.md) · [Variational methods](https://github.com/SoroushHaghi/quantum_programming_languages_lab/blob/main/topics/variational-algorithms.md). These link to learning documentation, not verified independent execution.

For an at-a-glance map of every relevant course and its status, see the [Course Coverage & Evidence Index](../COURSE_COVERAGE.md).

## Practical project directions — not yet completed

1. Rebuild and **personally** execute a small quantum circuit/algorithm in a pinned Qiskit environment; explain bit ordering, expected outcomes and validation tests.
2. Verify a one-qubit variational Hamiltonian against an independent mathematical baseline, then study finite sampling and reproducibility.
3. Build a focused **coding-to-quantum-error-correction bridge** with classical ground truth and a clearly labeled toy quantum model; see [Communication, Information & Coding Theory](communication-information-coding.md).
4. Consider an original Max-Cut/Ising classical-versus-quantum comparison only after a sound problem specification, competitive classical baselines and personally verified code exist.

---

**Evidence standard:** This portfolio distinguishes passed coursework, unfinished modules, educational reference code, software work outside the degree, and individually verified implementation. No quantum advantage or fault-tolerant quantum-computing capability is claimed.
