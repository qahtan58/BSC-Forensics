# BSC-Forensics

## Historical Consensus & State-Transition Differential Testing Framework

BSC-Forensics is an open-source research and developer-infrastructure project for reproducible differential testing of historical BNB Smart Chain client behavior.

### Research Goal

The project builds a commit-pinned testing framework for systematically evaluating consensus-critical and state-transition behavior across historical BSC client versions.

The project does **not** claim that a vulnerability exists. Its objective is to provide reproducible infrastructure to identify or rule out inconsistencies and preserve validated results as regression tests.

## Methodology

```text
Historical BSC Commit
        ↓
Valid Input Generator
        ↓
Canonical Oracle
        ↓
Controlled Mutation
        ↓
Validation / Import / State Transition
        ↓
Invariant Checks
        ↓
Differential Oracle
        ↓
Evidence Archive
