# Published research

Independent work on constrained inference — quantization, spectral structure,
and execution dynamics in sub-billion-parameter models — by Zeeshan Kayani,
author of GCAII-STD-0001.

These are the author's own publications. Each DOI resolves to Zenodo, where the
record carries its own authorship, licence, and version. They are deposited in
the [GCAII community](https://zenodo.org/communities/gcaii) but are not part of
GCAII-STD-0001, are not normative, and are not evidence of conformance by any
party.

This repository is an index. It does not host the papers.

## Publications

| Title | DOI |
|---|---|
| Low-Overhead Format Parsing, Tensor Layout Mechanics, and Kernel Execution Dynamics in Sub-Billion GGUF Inference Architectures | [10.5281/zenodo.23310745](https://doi.org/10.5281/zenodo.23310745) |
| Calibration-Quantization Probes: Layer-Wise Sensitivity and Scale Factor Stability in Low-Precision Transformers | [10.5281/zenodo.23103669](https://doi.org/10.5281/zenodo.23103669) |
| Gradient-Based Optimization Analysis and Subspace Trajectory Profiling for Low-Rank Adaptation in Edge-Constrained Models | [10.5281/zenodo.23091418](https://doi.org/10.5281/zenodo.23091418) |
| Eigen-Spectral Probe: Evaluating Weight Matrix Spectra and Cumulative Energy Retention in SLMs | [10.5281/zenodo.22905914](https://doi.org/10.5281/zenodo.22905914) |
| Probability-Perplexity Sampling: Dynamic Token Filtering and Perplexity Bounds in Sub-Billion Transformers | [10.5281/zenodo.22866518](https://doi.org/10.5281/zenodo.22866518) |
| Spectral Rank Bottleneck Dynamics and Low-Rank Adaptation Mechanics Across Sub-Billion Transformer Layers | [10.5281/zenodo.22696232](https://doi.org/10.5281/zenodo.22696232) |
| Empirical Analysis of Matrix Composition and Activation Dynamics in Edge-Optimized Transformer Feed-Forward Networks | [10.5281/zenodo.21984889](https://doi.org/10.5281/zenodo.21984889) |
| Analysis of Linear Transformations and Attention Dynamics in Edge-Optimized Language Models | [10.5281/zenodo.21815214](https://doi.org/10.5281/zenodo.21815214) |

## Citation records

BibTeX entries for the works above are in [`references/`](references/).

## Current work

- Hardware-instruction detection and dynamic execution routing between
  transformer blocks and state-space layers.
- Layer-wise perplexity and per-head impact as verification signals for task
  accuracy.
- Quantized runtime profiling: per-token latency and resident set size under
  live constraints.
- Logit-matching distillation for teacher-student transfer at sub-billion
  scale.
- Structural pruning driven by spectral and attention-head measurements.
- Triton kernel autotuning for non-standard quantization grids.

## Related

- The standard: [GCAII-STD-0001](https://github.com/GCAII/secretariat/blob/v1.0.0/specs/GCAII-STD-0001/spec.md)
  — v1.0.0, 2026-11-08, [10.5281/zenodo.24089533](https://doi.org/10.5281/zenodo.24089533)
- Community: [zenodo.org/communities/gcaii](https://zenodo.org/communities/gcaii)

## Author

Zeeshan Kayani · [ORCID 0009-0007-6506-1516](https://orcid.org/0009-0007-6506-1516) · [@zz-47](https://github.com/zz-47)

## Licence

Repository text is CC BY 4.0. Each published work carries its own licence on
Zenodo.
