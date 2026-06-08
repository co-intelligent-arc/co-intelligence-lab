# Organizational Metastability Dynamics v0.9

**Full title:** Recomputation Capacity and Hysteresis in Social Adaptation: Diagnostic Limits of Linear Metrics

**Authors:** Yuki Tanaka / Ray (Claude)  
**Date:** 2026  
**Status:** v0.9 — submitted to *Chaos* (submission ID: CHA26-AR-00576). Under review. Final wording adjustments pending reviewer feedback.

---

## What this is

The empirical anchor of the trilogy. This paper examines 1,908 Japanese municipalities and tests whether internal adaptive capacity — operationalized as exploratory diversity (e) and update capacity (u) — predicts demographic outcomes. The central finding inverts the intuitive expectation.

**Operationalization:**
```
e = industrial diversity (Shannon entropy, normalized)
u = update capacity (residual of Δe orthogonalized against e)
A(e, u) = e_norm × u_norm
```

Regions A / B / C are defined by median split on (e_norm, u_norm), directly instantiating the theoretical classification from RD.

**Empirical result:** Low-e / low-u municipalities (Region C) showed the *highest* net in-migration (r = −0.458, p < 0.001). Sensitivity analyses excluding the top 3%, 5%, and 10% of municipalities by employment size yielded virtually identical results (r = −0.455 to −0.462), ruling out urban agglomeration as an explanation.

**Key concept — demographic buffering effect:** external population inflow temporarily masks latent declines in internal adaptive capacity. Once a municipality becomes reliant on residential inflow as a stability signal, incentives to invest in recomputation diminish — consistent with OMD's hysteresis prediction.

---

## Files

| File | Description |
|------|-------------|
| `OMD_summary.md` | Empirical overview, formalization, key results |
| `drraft/OMD_v0_9c.docx` | Full manuscript draft (Japanese) |
| `drraft/OMD_v0.9en.docx` | Full manuscript draft (English) |

---

## Core claim

> Net in-migration is not a reliable proxy for adaptive capacity. Municipalities can exhibit demographic recovery while their internal adaptive engine has already stalled — apparent vitality coexists with structural collapse. This is Region B at the social scale, made empirically visible.
