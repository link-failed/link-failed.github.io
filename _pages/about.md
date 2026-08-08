---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student in Computer Science at [Simon Fraser University](https://www.sfu.ca/), advised by [Zhengjie Miao](https://www.cs.sfu.ca/~jnmiao/). Prior to my Ph.D., I received my B.Eng. in Computer Science and Technology from [Sichuan University](https://www.scu.edu.cn/) (2019–2023), graduating with Honors.

## Research Interests

- Reinforcement Learning for Data Science
- Agentic RL

## Experience

* **Aug 2026 – Present: Research Intern**, Microsoft (Vancouver, BC, Canada — Remote)
  * Mentors: Danrui Qi and Zhongqi Yue
  * Working on post-training.

* **May 2025 – Aug 2025: Research Intern**, Microsoft (Beijing, China)
  * Mentor: Haoyu Dong
  * Post-trained tabular QA model via GRPO in a multi-node, multi-GPU environment using **verl** and **Ray**.
  * Developed a multi-stage agent pipeline with LangGraph to handle large spreadsheet QA tasks.
  * Built specialized modules for dynamic context selection, data preview and query verification, allowing the agent to navigate and synthesize information from tables that were too large to encode fully.

* **Jun 2022 – Sep 2022: Research Intern**, [Mitacs (DataPrep.ai)](https://dataprep.ai/) (Burnaby, BC, Canada)
  * Mentor: Jiannan Wang
  * Developed a module to generate performance reports with Gantt charts, CDF charts, and tables to diagnose slow SQL queries.
  * Visualized statistics like table scan history to help identify and remove unnecessary indexes.
  * Implemented error detection for common query issues (e.g., missing columns) before compilation.
  * Implemented query tuning techniques to optimize slow query bottlenecks.

## Preprints

* **[SPA: A SQL-Plan-Aware Reinforcement Learning Framework for Query Rewriting with LLMs](https://arxiv.org/abs/2606.08620)** — Submitted to VLDB 2027
  * Developed a plan-aware GRPO reward strategy, enabling Qwen-32B (LoRA) to outperform GPT-5.4 and Gemini-2.5-Pro in query rewriting by incentivizing plan change over superficial lexical changes.
  * Extended GRPO with multi-stage rewards, with **probability-gated adaptive reward** for query-level curriculum learning.
  * Designed adaptive reward shaping and **on-policy self-improvement** to mitigate sparse rewards, reduce slowdown rewrites, and improve runtime/tail-latency on IID and OOD workloads.

* **[Structure-Grounded Knowledge Retrieval via Code Dependencies for Multi-Step Data Reasoning](https://arxiv.org/abs/2604.10516)**
  * Engineered a novel retrieval framework that organizes domain knowledge via a graph induced by **function-call dependencies**, specifically for complex code generation tasks.
  * Implemented a dependency-path retrieval logic that identifies critical links between semantic input/output tags, providing a more precise context extraction than embedding-based similarity.
  * Validated performance on DABStep, demonstrating that grounding retrieval increases accuracy by 109.1%–283.3% over traditional and graph-based RAG methods while retrieving substantially less context.

* **EVE-Bench: Diagnostic Evaluation of LLMs' Capabilities in SQL Reasoning**
  * Developed EVE-Bench, an execution-grounded framework for SQL equivalence verification, utilizing counterexample generation as a diagnostic lens to pinpoint LLM reasoning bottlenecks.
  * Utilized schema abstraction to identify LLMs' potential reliance on semantic hints, detecting when models bypass structural reasoning in favor of lexical cues.
  * Benchmarked 8 LLMs across 2,900+ query pairs, discovering that the most advanced models outperform traditional formal methods by up to 155% while exhibiting complementary failure modes.

## Education

* **Ph.D. in Computer Science**, Simon Fraser University, 2024 – Present
  * GPA: 4.00/4.33
  * Advisor: [Zhengjie Miao](https://www.cs.sfu.ca/~jnmiao/)
  * Research area: RL for data science, agentic RL
  * Mitacs Globalink Graduate Fellowship

* **B.Eng. in Computer Science and Technology**, Sichuan University, 2019 – 2023
  * GPA: 3.89/4.00
  * Graduated with Honors

## News

- **Sep 2025** — Transferred to Ph.D..
- **Jan 2024** — Started MSc. in computing science at Simon Fraser University.
