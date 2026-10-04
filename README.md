## Roman Khalikov

AI Researcher at **Sber AI Research**, working on LLM evaluation, agentic systems
and reasoning models. Researcher (part-time) at **Lomonosov Moscow State University**.
7 publications, 2 patents. Reviewer for AAAI and IJCAI.

Most of my work lives in papers rather than repositories. The code below is the
exception worth reading.

### HeroBench - multi-agent baseline

[**`A2_Agent`**](https://github.com/stefanrer/HeroBench/tree/master/A2_Agent) -
the multi-agent baseline system for
[HeroBench](https://github.com/stefanrer/HeroBench)
([arXiv:2508.12782](https://arxiv.org/abs/2508.12782)), a benchmark for
long-horizon planning and structured reasoning of LLM agents in virtual worlds.
I designed and built this agent; the benchmark is co-authored with
P. Anokhin and colleagues and has since been cited in independent industry
evaluations.

The architecture decomposes a long-horizon goal into a curriculum of subgoals and
critiques its own intermediate plans:

| Module | Role |
|---|---|
| `decomposer` | Splits a long-horizon goal into ordered subgoals |
| `curriculum` | Sequences subgoals against current world state |
| `critic` | Evaluates intermediate plans and triggers revision |
| `crafter`, `mapper`, `action`, `fight_analytic` | Domain-specific reasoning and execution |

### Selected publications

- **Wearable optomyography enables continuous neuroprosthetic control** -
  *Scientific Reports* 16, 9604 (2026). First author.
  [DOI](https://doi.org/10.1038/s41598-025-32646-y)
- **HeroBench: A Benchmark for Long-Horizon Planning and Structured Reasoning in
  Virtual Worlds** - [arXiv:2508.12782](https://arxiv.org/abs/2508.12782)
- **Search, Fail, Recover: A Training Framework for Correction-Aware Reasoning** -
  [arXiv:2607.07492](https://arxiv.org/abs/2607.07492)

Full list on [Google Scholar](https://scholar.google.com/citations?user=AThsPAMAAAAJ&hl=en).

### Interests

LLM reasoning and agentic systems, end-to-end data generation pipelines, judges, evaluation
methodology, and interpretability.

[LinkedIn](https://www.linkedin.com/in/roman-khalikov/) ·
[Google Scholar](https://scholar.google.com/citations?user=AThsPAMAAAAJ&hl=en)
