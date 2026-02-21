# LAMMI: Hierarchical Multi-Agent Reasoning for Pathology-Molecular Intelligence

[![Status](https://img.shields.io/badge/status-under%20construction-orange)]()
[![Paper](https://img.shields.io/badge/paper-coming%20soon-blue)]()
[![License](https://img.shields.io/badge/license-TBD-lightgrey)]()

> Official repository of **LAMMI**.
> Hierarchical LVLM-driven multi-agent framework for pathology-molecular, tool-grounded reasoning.

## Core Ideas

- **Scalable hierarchical architecture (anti-task-drift):** Planner-led decomposition with component agents enables stable long-horizon reasoning.
- **Execution-grounded AEN:** each reasoning unit is derived from real tool feedback, `AEN = (Query, Action, Observation)`.
- **Trajectory-Aware Finetuning (TA):** optimize on executable trajectories to improve tool-use consistency and final-answer reliability.

## LAMMI Architecture

![LAMMI Architecture](assets/LAMMI_arch.png)

- Planner-level decomposition.
- Specialist-level execution (`ImageAgent`, `GeneAgent`, ...).
- Extensible component-agent design for plug-and-play expansion to diverse vertical domains.

## TA Finetuning

![LAMMI Trajectory-Aware Finetuning](assets/LAMMI_training.png)

- TA objective: learn executable tool trajectories, not only final answers.
- Better tool consistency; lower redundancy and hallucination in long-chain runs.

## Evaluation Scope

- **PathSpatial-DocQA**
- **ST-Traj**
- **PathMMU**

## Inference Case Overview

![LAMMI Case Study](assets/case_study.png)

- Multi-tool evidence aggregation.
- Failure recovery and trajectory correction.

## Citation

BibTeX will be updated after acceptance.

```bibtex
@article{lammi2026,
  title   = {LAMMI: Hierarchical Multi-Agent Reasoning for Pathology-Molecular Intelligence},
  author  = {Anonymous},
  journal = {arXiv preprint},
  year    = {2026}
}
```
