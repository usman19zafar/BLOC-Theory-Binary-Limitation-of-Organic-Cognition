# src/bloc.py
class BLOC:
    def __init__(self, bloc_type, content):
        assert bloc_type in ["C", "P", "S", "X"]
        self.type = bloc_type
        self.content = content

    def __repr__(self):
        return f"BLOC(type={self.type}, content={self.content})"


# src/decomposition.py
from bloc import BLOC

def decompose(artifact):
    """
    Placeholder decomposition.
    Replace with real logic for your domain.
    """
    return [
        BLOC("C", "Purpose of artifact"),
        BLOC("P", "Actions required"),
        BLOC("S", "Architecture or structure"),
        BLOC("X", "Context and constraints")
    ]


# src/composition.py
def compose(blocs):
    """
    Reconstruct artifact from BLOCs.
    """
    return {
        "conceptual": [b.content for b in blocs if b.type == "C"],
        "procedural": [b.content for b in blocs if b.type == "P"],
        "structural": [b.content for b in blocs if b.type == "S"],
        "contextual": [b.content for b in blocs if b.type == "X"],
    }


# src/loss.py
def discretization_loss(signal_continuous, signal_discrete, dt):
    """
    Computes IA = ∫ s(t) dt − Σ s(t_i) Δt
    """
    integral = sum(signal_continuous) * dt
    discrete_sum = sum(signal_discrete) * dt
    return integral - discrete_sum


# src/projections.py
def meaning_projection(blocs):
    return [b for b in blocs if b.type in ["C", "X"]]

def mechanism_projection(blocs):
    return [b for b in blocs if b.type in ["P", "S"]]
