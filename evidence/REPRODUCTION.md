# REPRODUCTION

## Purpose

This document defines the reproducibility procedure for the BSC-Forensics research workflow.

The objective is to allow an independent reviewer to inspect the documented inputs, processing steps, validation results, and analytical outputs without relying on undocumented assumptions.

---

## 1. Reproduction Principles

The reproduction workflow follows:

1. Acquire
2. Validate
3. Decode
4. Analyze
5. Compare
6. Record
7. Independently Verify

Each stage should preserve sufficient information to trace the reported result back to its source input.

---

## 2. Evidence Requirements

A reproducible evidence record should preserve:

- Source data
- Raw input
- Input hash
- Canonical decoded fields
- Expected values
- Observed values
- Execution result
- Exact errors
- stdout/stderr
- Reproduction command
- Invariant result
- Validation status
- Commit SHA

Empty fields must remain empty when the corresponding value has not been established.

Invented or reconstructed values must not be substituted for missing evidence.

---

## 3. Independent Reproduction

An independent reproduction should use the documented source inputs and repeat the documented processing procedure.

The reviewer should be able to determine:

- what input was used
- how the input was validated
- how the input was decoded
- what result was expected
- what result was observed
- whether an invariant was satisfied
- whether any divergence occurred
- whether the reported result can be reproduced

---

## 4. BEMBA Phase 2 — Independent Reproduction

### Verification Scope

Independent verification was performed against Blockstream for the target Bitcoin block-height range.

Target range:

`66312-66527`

Target heights:

`216`

Found:

`216`

HTTP 404:

`0`

Errors:

`0`

### Reproduction Result

`REPRODUCTION RESULT: CLEAN`

The documented verification found all 216 target heights with no HTTP 404 responses and no reported errors.

Result:

```text
216/216 FOUND
0 × HTTP 404
0 ERRORS
