# Structural Coherence Evaluation (Research)

This repository documents a research effort focused on detecting **structural instability
in multi-step reasoning trajectories**, independent of semantic correctness or task success.

Core idea:
> Reasoning can fail structurally (inflate, drift, lose closure) *before* failure is visible in outputs.

This work evaluates reasoning as **trajectories**, using pre-semantic structural invariants such as:
- re-entry vs. inflation,
- stabilization behavior,
- trajectory collapse.

## Included
- Conceptual overview (docs)
- P0: minimal regime separation
- P1: cross-model regime separation across prompts
- Figures (figures/)

## Not included
- Core engine implementation
- Proprietary datasets
- Production API

This is a research artifact intended to communicate the evaluation concept clearly.
