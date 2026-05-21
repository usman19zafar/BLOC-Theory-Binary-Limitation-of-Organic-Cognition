## 1. Overview

BLOC Theory formalizes the categorical limitation of digital computation relative to organic cognition. 
* **Binary encoding** imposes an ontological transformation that irreversibly removes phenomenological richness.
* **Organic cognition** is continuous, embodied, contextual, and meaning‑driven.
* **Machine cognition** is discrete, symbolic, quantized, and meaning‑blind.

This repository provides the formal universe, operators, theorems, benchmarks, and diagrams that instantiate BLOC Theory as a computable cognitive‑engineering framework.

## 2. Core Claim

All machine cognition passes through the **Binary Tunnel**:

$$\text{World} \longrightarrow \text{Encoding} \longrightarrow \text{Binary Processing} \longrightarrow \text{Decoding} \longrightarrow \text{Output}$$

This transformation is inherently lossy:
> *"Binary encoding is a forgetful functor; information loss is intrinsic."*

## 3. The BLOC Framework

A BLOC is a self‑contained unit comprised of four distinct dimensions:
* **Conceptual** — meaning / purpose
* **Procedural** — action / execution
* **Structural** — architecture / templates
* **Contextual** — environment / constraints

### Formal Universe
The cognitive‑engineering universe is defined as the tuple:

$$\mathcal{U} = \langle A, B, T, D, \oplus \rangle$$

Where:
* $A$ = Artifacts
* $B$ = BLOCs
* $T$ = Type function
* $D$ = Decomposition operator
* $\oplus$ = Recomposition operator

---

## 4. Repository Structure

```text
├── README.md        <- This documentation and citation guide
├── theorems/        <- Axioms, formal propositions, and proof structures
├── src/             <- Operational logic and executable validation models
├── benchmarks/      <- Empirical verification data and accuracy logs
├── examples/        <- Implementation templates to accelerate adoption
├── diagrams/        <- Architectural schematics and visual assets (.svg/.png)
├── api/             <- Reusable algorithmic abstractions
├── notebooks/       <- Interactive Jupyter notebooks for step-by-step replication
└── graph/           <- Inter-paper theoretical dependency graphs


## 5. Key Theorems

* **Axiom 1 (Coverage):** Every meaningful part of an artifact maps to at least one BLOC.
* **Axiom 2 (Typed Completeness):** A fully specified artifact contains at least one BLOC of each functional type.
* **Axiom 3 (Type Partition):** Each individual BLOC possesses exactly one type mapping.
* **Axiom 4 (Recomposability):** Decomposition followed immediately by a recomposition operation returns the mathematically identical original artifact.
* **Axiom 5 (Phenomenological Loss):** For a continuous signal $s(t)$ and its respective discrete representation $s(t_i)$, the intrinsic loss ($I_\Delta$) remains strictly positive:

$$I_\Delta = \int s(t) \, dt - \sum s(t_i) \Delta t > 0$$

* **Proposition 2 (Decomposition Lattice):** Decompositions structurally form a bounded mathematical lattice supporting refinement, meet, and join operations.
* **Proposition 3 (Meaning/Mechanism Split):** The decomposition of an artifact splits cleanly into orthogonal domains of Meaning ($M$) and Mechanism ($R$):

$$D(a) = M(a) \cup R(a) \quad \text{where} \quad M(a) \cap R(a) = \emptyset$$

---

## 6. Operators (API Layer)

The underlying core codebase exposes key computational hooks to make BLOC Theory executable and testable:
1. `create_bloc()` — Instantiate isolated structural/conceptual nodes.
2. `decompose_artifact()` — Execute system fragmentation based on type partitions.
3. `compose_blocs()` — Reassemble disparate nodes via the $\oplus$ operator.
4. `refine_decomposition()` — Traverse lattice layers to increase modular granularity.
5. `meet() / join()` — Standard lattice algebra transformations.
6. `project_meaning() / project_mechanism()` — Isolates programmatic segments of $D(a)$.
7. `calculate_discretization_loss()` — Quantifies information drop across the Binary Tunnel boundaries.

---

## 7. Empirical Validation

### Predictive Validity Test
The model evaluates computational parsing against continuous human cognitive alignment using the following accuracy function:

$$\text{Acc} = \frac{1}{n} \sum \frac{| f(M(a_i)) \cap R(a_i) |}{| R(a_i) |}$$

### Quantitative Loss Metrics
Baseline testing environments show consistent constraints when processing organic-semantic inputs:
* **Mean Absolute Error (MAE):** $\approx 0.25$
* **Information Entropy Loss:** $H(X) - H(X') > 0$

Detailed metrics and test harnesses can be inspected directly in the `/benchmarks/` directory.

---

## 8. Diagrams (Cognitive Compression)

Vector and raster schematics representing the core cognitive transformations are located in the `/diagrams/` folder:
* **The Binary Tunnel:** Visualizing structural compression limits.
* **The Ontological Gap:** Mapping qualitative reality against quantitative constraints.
* **The BLOC Stack:** Layer hierarchy across the 4 core dimensions.
* **The Decomposition Lattice:** Structural graph representation of meets and joins.
* **Meaning $\leftrightarrow$ Time Recursion:** Mapping temporal updates to semantic fields.

## 9. Cross‑Paper Theory Graph

BLOC Theory functions as an intermediate layer within a wider structural lineage. Visual mappings of these lineage arcs are parsed in the `/graph/` directory:

$$\text{BLOC Framework} \longrightarrow \text{DAIS-10} \longrightarrow \text{KAD Theory} \longrightarrow \text{SFPM-10}$$

---

## 10. Signature Insight

> *"If you can decompose any system into BLOCs, it can be rebuilt anywhere."*

BLOC Theory establishes a universal, hardware-agnostic decomposition grammar designed to reconcile human meaning with engineered mechanical architecture.
