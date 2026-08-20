# EVIDENCE INDEX

## Purpose

This index provides a structured map of the evidence-oriented artifacts contained in the BSC-Forensics repository.

The repository is organized to support independent inspection, reproducibility, validation, and separation between observations, analytical results, and attribution hypotheses.

---

## 1. Evidence Model

The evidence workflow separates the following layers:

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

These layers should remain distinguishable throughout acquisition, validation, analysis, and documentation.

---

## 2. Current Evidence Artifacts

### BSC_FORENSIC_RESULTS

Primary forensic results record associated with the BSC-Forensics research workflow.

This record contains the documented evidence framework and research-status information currently established for the project.

---

### EVIDENCE.md

Evidence-first methodological record describing:

- Evidence handling
- Reproducibility requirements
- BEMBA Phase 2 reproduction status
- Evidence separation
- BNB Smart Chain research status
- Evidence record requirements
- Validation classifications
- Limitations
- Repository evidence policy

---

## 3. BEMBA Phase 2 Reproduction

The documented reproduction record reports:

```text
REPRODUCTION RESULT: CLEAN

Target: 216 heights [66312-66527]
Found: 216
HTTP 404: 0
Errors: 0
