---
title: "RePro: Proof-Verified Benchmark Rewriting for Reliable Evaluation of LLM Mathematical Problem Solving"
year: 2026
venue: "The 2026 Conference on Empirical Methods in Natural Language Processing (EMNLP 2026)"
venue_display: "The 2026 Conference on Empirical Methods in Natural Language Processing (EMNLP 2026)"
venue_chronicle: "Conference on Empirical Methods in Natural Language Processing"
venue_abbr: "EMNLP"
publication_date: "2026-10-24"
author_line_full: "Xiyuan Zhou, Zhuoqi Li, Xinlei Wang, Yirui He, Yuhao Wu, Yuheng Cheng, Yan Xu, Junhua Zhao, Jinjin Gu"
authors:
  - jinjin-gu
paper_url: "https://aclanthology.org/2026.emnlp-main.1322.pdf"
---
## Abstract

Data contamination undermines the reliable evaluation of large language models (LLMs) on mathematical problem solving. While rewriting-based evaluation mitigates memorization, existing methods lack guarantees of problem validity and answer correctness. We propose Proof-Verified Benchmark Rewriting (RePro), the first framework to integrate Lean-oriented neural automated theorem provers (ATPs) into benchmark rewriting, which rewrites problems and regenerates answers with correctness ensured by Lean-verified proofs. Experiments on GSM8K and MATH show that RePro's retained rewritten instances achieve 100% well-definedness, feasibility, and answer correctness, while existing methods still produce invalid or incorrect instances. Moreover, several models exhibit accuracy drops on proof-verified rewritten benchmarks, suggesting that their performance is sensitive to surface-level and structural variations and may partly reflect memorization effects.

## Links

- [Code and data](https://github.com/AI4Engi/RePro)
- [ACL Anthology](https://aclanthology.org/2026.emnlp-main.1322/)
