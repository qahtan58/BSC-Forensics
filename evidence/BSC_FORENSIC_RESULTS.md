# EVIDENCE

## Evidence-First Research Record

This document records reproducible evidence artifacts associated with the BSC-Forensics research workflow.

The evidence model separates:

- Source data
- Raw inputs
- Cryptographic hashes
- Canonical decoded fields
- Expected values
- Observed values
- Execution results
- Exact errors
- stdout/stderr logs
- Reproduction commands
- Invariant results

No attribution or causal conclusion is inferred from an observation alone.

---

## 1. Evidence Handling

Each evidence record should preserve the original input and the exact analytical path used to obtain the reported result.

Required evidence fields:

- Commit SHA
- Raw input
- Input hash
- Canonical decode
- Expected values
- Observed values
- Execution result
- Exact error
- stdout/stderr
- Reproduction command
- Invariant results

Raw bytes should remain unchanged between acquisition, validation, decoding, and analysis layers.

---

## 2. Reproducibility

A result is considered reproducible only when an independent researcher can inspect the relevant artifacts and repeat the documented procedure.

The repository therefore preserves:

- Source inputs
- Deterministic processing steps
- Analytical outputs
- Validation results
- Execution logs
- Reproduction commands
- Evidence metadata

---

## 3. BEMBA Phase 2 — Reproduction

### Reproduction Result: CLEAN

Independent verification was performed against Blockstream for the target Bitcoin block-height range:

```text
Target: 216 heights [66312-66527]
Found: 216
HTTP 404: 0
Errors: 0
