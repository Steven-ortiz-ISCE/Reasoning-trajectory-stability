# Structural Coherence Evaluation of Reasoning Trajectories (Research)

This repository documents a research effort focused on detecting **structural instability
in multi-step reasoning trajectories**, independent of semantic correctness or task success.

Core idea:
> Reasoning can fail structurally (inflate, drift, lose closure) *before* failure is visible in outputs.

This work evaluates reasoning as **trajectories**, using pre-semantic structural signals derived from trajectory geometry.

These invariants are computed over sequential reasoning steps, treating reasoning as a geometric process rather than a semantic one.

## Included
- Conceptual overview (docs)
- P0: early regime separation experiments
- P1: cross-model consistency experiments
- Figures (figures/)

## Not included
- Core engine implementation
- Proprietary datasets
- Production API

This is a research artifact intended to communicate the evaluation concept clearly.
