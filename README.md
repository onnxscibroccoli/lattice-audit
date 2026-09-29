# LATTICE Audit Mirror

**Status:** Public audit mirror / external-model interface  
**Repository:** `onnxscibroccoli/lattice-audit`  
**Documentation snapshot:** 2026-09-28 23:12 EDT

This repository is the public-facing audit surface for the private LATTICE operating repository. It exists so external models and human reviewers can inspect the methodology without access to the private canonical repository.

## Contents

- `AUDIT_PROMPT.md` — primary audit instructions.
- `CODEV.md` — multi-model collaboration protocol.
- `RECOVERABILITY.md` — recovery and reproducibility guidance.
- `VOICE.md` — reporting and communication rules.
- `README.md` — this entry point.

## Development cycle

**PUBLIC AUDIT MIRROR / MAINTENANCE MODE.**

The underlying LATTICE engine lives in `onnxscibroccoli/lattice`. This repository is not a second implementation of that engine. Its purpose is transparency, review, and model-to-model auditing.

## How to use it

Start here:

```text
AUDIT_PROMPT.md
CODEV.md
RECOVERABILITY.md
VOICE.md
```

Then follow the audit protocol against the evidence actually present in this public mirror.

## AI model protocol

An AI should:

1. Read `AUDIT_PROMPT.md` before forming conclusions.
2. Read `CODEV.md` before collaborating with another model.
3. Separate repository evidence from inference.
4. Identify missing evidence rather than filling gaps with guesses.
5. Never claim access to the private canonical repository unless that access has actually been provided.
6. Preserve the documented distinction between software-engine readiness and any external real-world action.

The public mirror is deliberately narrower than the private operating project.

## Relationship to the canonical project

`onnxscibroccoli/lattice` is the private operating repository.

`onnxscibroccoli/lattice-audit` is the public audit boundary.

**Bottom line:** an external inspection interface, not the underlying engine.
