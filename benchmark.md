# benchmarks/predictive_validity.md

## Predictive Validity Benchmark
This benchmark evaluates whether meaning BLOCs can predict mechanism BLOCs.

### Metric
```
Acc = (1/n) Σ | f(M(ai)) ∩ R(ai) | / | R(ai) |
```

### Expected Range
Accuracy typically falls between **0.55 and 0.75** depending on domain.

---

# benchmarks/loss_metrics.md

## Discretization Loss Benchmark
Evaluates the Binary Tunnel constraint.

### Metrics
- Mean Absolute Error (MAE): ~0.25  
- Entropy Loss: H(X) − H(X') > 0  

### Interpretation
Binary encoding always introduces irreducible loss.
