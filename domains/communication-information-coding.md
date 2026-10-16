# Communication, Information & Coding Theory

[← Portfolio overview](../README.md) · [All courses and evidence](../COURSE_COVERAGE.md) · [Computing & algorithms →](computing-algorithms-optimization.md) · [Devices & physical systems →](quantum-devices-physical-systems.md)

**Focus:** Mathematical limits of communication, information representation, error correction, classical and quantum channels, and optical-network foundations.

This is a map of academic topics and observed coursework. It does not imply a built telecom network or independently implemented quantum communication system.

## Courses and studied topics

| Academic source | Documented topics | Evidence boundary |
| --- | --- | --- |
| **Mathematical Foundations of Information Theory and Coding Theory** | Entropy, relative entropy, Kraft–McMillan, prefix coding, Huffman, Markov processes, entropy rates, typical sets | Passed analytical coursework; archived graded assignments |
| **Coding Theory** | Linear/cyclic and BCH codes, Hamming distance, cyclotomic cosets, generator polynomials, convolutional encoding and Viterbi-decoding concepts | Passed course; computational group component |
| **Computational Experiments in Coding Theory** | MATLAB calculations on cyclic codes and matrices; bit-error trends versus SNR | Passed ungraded **group** lab component; not a personally authored complete decoder |
| **Network Information Theory** | Slepian–Wolf distributed source coding, state-dependent channels, encoder-side noncausal information, Gelfand–Pinsker / dirty-paper coding and achievable rates | Passed course; individual technical presentation |
| **Quantum Communication Networks** | Quantum states/channels, entanglement, CHSH, dense coding, teleportation and network concepts | Passed course; individual technical presentation |
| **Nonlinear Photonics** *(cross-domain)* | Dispersion, wave mixing, fiber nonlinearities and propagation foundations | Passed course and analytical submissions; no fiber experiment |
| **Advanced Applications of Field Theory** *(cross-domain)* | Field and wave foundations, electromagnetic energy transport and radiation | Passed course; theoretical/analytical work |
| **QKD / next-generation optical networks seminar** | Planned focus on coexistence of QKD signals and classical optical communication | **In preparation**; no completed presentation or experiment claimed |

**Additional source folder:** Semester-three *Information Theory* notes and exercise materials cover mutual information, the binary symmetric channel, and constrained power allocation. This is **not** counted as another independently completed university module.

## Knowledge map

### Information theory and coding
- Entropy and source/channel descriptions; coding-length and unique-decodability principles.
- Prefix codes, Kraft–McMillan and Huffman coding.
- Stochastic sources, Markov entropy rates and asymptotic typical-set concepts.
- For a binary symmetric channel, the course formula `C = 1 − H_b(ε)` relates capacity to crossover probability; the result applies to that channel model, not all channels.
- Linear/cyclic block-code structure, Hamming distance and error-correction mechanisms.
- Binary BCH code construction through cyclotomic cosets and generator polynomials; convolutional-code state memory and Viterbi decoding at the **supplied-exercise** level, not independently implemented code.
- Numerical coding-theory worksheets using MATLAB at a **collaborative coursework** level.

### Networks and quantum communication
- Correlated-source distributed lossless coding in the Slepian–Wolf setting, including binning and joint-entropy rate constraints.
- Multiuser and state-dependent information-theoretic models.
- Dirty-paper coding / Gelfand–Pinsker channel model, where the transmitter knows the state sequence noncausally, and random-binning/rate arguments studied theoretically.
- Capacity and water-filling allocation for a parallel Gaussian channel under a total-power constraint, at the course-formula level.
- Quantum-channel and entanglement concepts, Bell/CHSH examples, superdense coding and teleportation.
- QKD co-propagation in optical networks is a **current seminar topic**, not an achieved research result. The collected QKD implementation-vulnerability survey is externally authored reading material, not a student-performed security audit.

### Optical/field foundations
- Dispersive propagation, nonlinear optical interactions and field analysis as supporting theory.
- Photonics and electromagnetics also belong to [Quantum Devices & Physical Systems](quantum-devices-physical-systems.md).

## Four-semester evidence boundary

The source folders mix lectures, instructor solution handouts and student-associated work. The BCH/Viterbi worked solutions are **supplied teaching examples**, not personal decoder code. The additional Information Theory folder overlaps the already credited information/coding curriculum; folder count is not a credential count. Original QKD research, a finished seminar and optical-system measurements are not evidenced by these materials.

## Existing academic work

| Work | Source-supported contribution |
| --- | --- |
| **Coding Theory computational group lab** | MATLAB-based cyclic-code, generator-matrix and error-behavior exercises; personal code ownership not established |
| **Information/coding written coursework** | Analytical exercises; archived solutions require checking before technical reuse |
| **Channel Coding with State presentation** | Technical synthesis of state-dependent channels, random binning and dirty-paper coding |
| **Quantum Communication Networks presentation** | Technical synthesis of quantum states, CHSH, entanglement, dense coding and teleportation |
| **Nonlinear Photonics exercises** | Analytical wave/optical calculations; no original experimental measurements |

## Connections to other domains

- **Coding → quantum error correction:** Classical error models and syndromes can motivate a small quantum model; see [Computing, Algorithms & Optimization](computing-algorithms-optimization.md).
- **Optical channels → physical photonics:** Phase matching, dispersion and electromagnetic propagation are cross-listed under [Quantum Devices & Physical Systems](quantum-devices-physical-systems.md).
- **Quantum networks → algorithms:** Entanglement, gates, measurements and channels underpin both [quantum communication](#networks-and-quantum-communication) and the [computing domain](computing-algorithms-optimization.md).

See the [Course Coverage & Evidence Index](../COURSE_COVERAGE.md) for status and coverage across the wider M.Sc.

## Possible next experiments (proposals, not outcomes)

1. Build and personally verify a small classical coding/decoding simulator, with independent correctness checks.
2. Add a clearly identified toy quantum-error-correction example **after** validating the classical baseline.
3. Develop a source-based QKD/optical coexistence model while preparing the pending seminar, with stated assumptions and no unsupported key-rate claims.

---

Instructor material and private university records are not redistributed. Coursework, collaborative contribution, and personally implemented results are represented separately.
