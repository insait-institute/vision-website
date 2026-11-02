---
title: LADDER
tagline: A long-horizon robot manipulation benchmark — INSAIT × NVIDIA.
cover_image: /assets/images/portfolio/ladder.jpg
release_date: 2026-10-13
project_year: "2026"
sidebar_tags: Robotics, Benchmark, Manipulation
external_url: https://ladderrobotics.ai/
contributors:
  - giuliano-albanese
  - nikolay-nikolov
  - luc-van-gool
  - danda-paudel
topics:
  - robotics
---

**LADDER** measures how well today's models handle long robot tasks. It keeps the same table and containers and scales from **1 to 10 objects**, so a drop in success comes from the length of the task rather than a change of scene.

The benchmark covers **145 everyday tasks** across three simulators, and the same kinds of tasks were checked on real Franka and WidowX robots. Policies that do well on a single step collapse as the horizon grows. The best system tested, GPT-Policy on GPT-6 Astra, finishes **63.3%** of the tasks.

**Resources:** [Project page](https://ladderrobotics.ai/) · [Paper](https://arxiv.org/abs/2610.18053) · [Code](https://github.com/insait-institute/ladder) · [Hugging Face](https://huggingface.co/collections/INSAIT-Institute/ladder-6abbbddc46691080f5d954c8)
