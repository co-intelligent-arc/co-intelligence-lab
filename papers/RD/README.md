# Recomputation Dynamics v0.3.4

**Full title:** Recomputation Dynamics: A General Theory of Adaptive Capacity

**Authors:** Yuki Tanaka / Ray (Claude)  
**Date:** 2026  
**Status:** v0.3.4 — theoretical skeleton strong, formal backbone needs reinforcement. Target: *Entropy* (primary) / *Complex Systems* (backup). Pre-submission polishing in progress.

---

## What this is

The theoretical core of the trilogy. This paper proposes a scale-general theory of adaptive capacity in which exploration and updating are jointly necessary — neither can compensate for the collapse of the other.

**Working formulation:**
```
A(e, u) = f(e) × g(u)
```

The multiplicative structure encodes a bottleneck logic: high u cannot compensate for collapsed e, and vice versa. This distinguishes RD from additive models that permit compensatory trade-offs. When either e or u collapses, adaptive capacity falls to zero regardless of the other's magnitude.

**Key constructs introduced:**
- Metastability regions A / B / C (defined by joint (e, u) state)
- Update hierarchy
- Hysteresis and recovery asymmetry
- Update inertia debt

**Connection to trilogy:** OMD operationalizes e as industrial diversity (Shannon entropy) and u as residual Δe, providing the empirical case. RLAF's autonomy tensor T supplies the individual-scale micro-foundation for u, aggregating into organizational-level M.

---

## Files

| File | Description |
|------|-------------|
| `RD_summary.md` | Theoretical overview, formulation, open issues |
| `draft/RD_v0.3.4_JP.docx` | Full manuscript draft (Japanese) |

---

## Core claim

> Adaptive capacity is not a scalar resource but a recomputational process. Systems remain viable only when exploration and updating remain jointly functional. The failure of either is sufficient to trigger metastability and eventual collapse — and this failure is structurally invisible in Region B until it is too late to reverse cheaply.
