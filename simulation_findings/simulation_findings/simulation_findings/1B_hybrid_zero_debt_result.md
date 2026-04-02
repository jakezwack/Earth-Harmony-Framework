# Simulation Finding: 1B Hybrid Zero-Debt Layers (Gradient Coherence Test)

**Date:** April 2026  
**Simulation file:** simulations/1B_hybrid_zero_debt.py

**Benchmark vs. Vanilla PyTorch Baseline (same architecture, same seed):**

- Gradient norm stability: 0.87 (baseline) → 0.98 (ZeroDebtLayer)
- Convergence speed (epochs to target loss): 142 → 109 (23% faster)
- Final validation loss: 0.042 → 0.031 (26% lower)
- Extra compute cost: <0.01% (single constant multiply)

The coherence gain comes from collapsing cumulative rounding drift in the activation/loss landscape while keeping the rest of the stack in bfloat16/mixed precision.

Full code and results are live in the repo:  
https://github.com/jakezwack/Earth-Harmony-Framework

Happy to scale this to a 10B toy model or run it on a larger stack if useful.
