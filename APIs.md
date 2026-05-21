# api/operators.md

## BLOC Operators

### create_bloc(type, content)
Creates a typed BLOC.

### decompose(artifact)
Returns a set of BLOCs.

### compose(blocs)
Reconstructs artifact from BLOCs.

### refine(E1, E2)
Returns a decomposition that refines both.

### meet(E1, E2)
Coarsest decomposition both refine.

### join(E1, E2)
Finest decomposition refining both.

### meaning_projection(blocs)
Extracts Conceptual + Contextual BLOCs.

### mechanism_projection(blocs)
Extracts Procedural + Structural BLOCs.

### discretization_loss(...)
Computes Binary Tunnel loss.
