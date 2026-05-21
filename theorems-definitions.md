# BLOC Theory — Definitions
Canonical definitions for all core objects in the BLOC formal universe.

---

## Definition 1 — Artifact (A)
An artifact is any system, process, document, or experience‑proxy that can be decomposed into BLOCs.

Examples:  
- A policy  
- A workflow  
- A software module  
- A cognitive model  

---

## Definition 2 — BLOC (B)
A BLOC is a self‑contained, typed unit representing one of four cognitive‑engineering dimensions:

- Conceptual (C) — meaning, purpose, intent  
- Procedural (P) — action, execution, mechanism  
- Structural (S) — architecture, templates, patterns  
- Contextual (X) — environment, constraints, time, conditions  

A BLOC is the atomic unit of decomposition.

---

## Definition 3 — Type Function (T)
The type function assigns each BLOC exactly one type:

```
T(b) ∈ {C, P, S, X}
```

This enforces categorical separation.

---

## Definition 4 — Decomposition Function (D)
The decomposition function maps an artifact to a set of BLOCs:

```
D : A → P(B)
```

Where P(B) is the power set of BLOCs.

---

## Definition 5 — Composition Operator (+)
The composition operator reconstructs an artifact from its BLOCs:

```
+ D(a) = a
```

Recomposition is structurally lossless.

---

## Definition 6 — Meaning Projection (M)
Meaning projection extracts Conceptual and Contextual BLOCs:

```
M(a) = { b ∈ D(a) | T(b) ∈ {C, X} }
```

---

## Definition 7 — Mechanism Projection (R)
Mechanism projection extracts Procedural and Structural BLOCs:

```
R(a) = { b ∈ D(a) | T(b) ∈ {P, S} }
```

---

## Definition 8 — Binary Tunnel Loss (IA)
Binary discretization of continuous signals introduces irreducible loss:

```
IA = ∫ s(t) dt − Σ s(t_i) Δt   > 0
```

---

## Definition 9 — Refinement Relation (≤)
A decomposition E1 refines E2 if every BLOC in E1 is contained within a BLOC of E2.

This induces a lattice structure.

---

## End of File
