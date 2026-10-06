## Introduction

I'm a Data Scientist at AT&T and the technical lead for [Open Telco (OTel) AI](https://github.com/farbodtavakkoli/OTel), AT&T's open model family for telecom AI within the broader Open Telco AI initiative launched by GSMA at MWC 2026. GSMA provided core telecom standards data, while AT&T developed and trained OTel models, including the [31B OTel 2.0 release](https://huggingface.co/farbodtavakkoli/OTel-2.0-LLM-31B-IT). Our work on OTel datasets, benchmarks, and models was accepted as a [Spotlight at NeurIPS 2026](https://github.com/farbodtavakkoli/OTel/blob/main/docs/OTel-NeurIPS-2026.pdf) in the Evaluations & Datasets Track.

OTel has grown from open telecom datasets and specialized language, embedding, reranking, classification, and safety models into a reproducible training and inference ecosystem. The repository now includes 27 distinct training stacks and nine inference stacks across AMD, NVIDIA, Apple, and Intel hardware. AMD Instinct MI355X and NVIDIA H100 received the most extensive end-to-end verification. Twenty-two of the 27 training stacks run on both AMD and NVIDIA without changes to the training code; only the environment setup changes, including ROCm or CUDA and compatible PyTorch versions.

My work spans data curation, model development, post-training, evaluation, benchmarking, hardware validation, deployment, documentation, and open-source release. Current work includes publishing the OTel 2.0 training implementation, releasing a comprehensive OTel 2.0 evaluation through MLPerf in collaboration with MLCommons, expanding training and inference support with the AWS and Tenstorrent teams, comparing GRPO and multi-node training stacks, and benchmarking AMD Ryzen inference. OTel models have reached tens of millions of downloads worldwide.

### Featured OTel Links

**Project resources**

- [OTel paper - NeurIPS 2026 Spotlight](https://github.com/farbodtavakkoli/OTel/blob/main/docs/OTel-NeurIPS-2026.pdf)
- [OTel paper - ACM AI Leadership Summit 2026 Breakthrough Impact](https://arxiv.org/abs/2608.15436)
- [Hardware- and software-agnostic recipes for training and inference](https://github.com/farbodtavakkoli/OTel)
- [OTel 2.0 31B model card and weights](https://huggingface.co/farbodtavakkoli/OTel-2.0-LLM-31B-IT)
- Model collections: [LLMs](https://huggingface.co/collections/farbodtavakkoli/otel-llm), [embeddings](https://huggingface.co/collections/farbodtavakkoli/otel-embedding), and [rerankers](https://huggingface.co/collections/farbodtavakkoli/otel-reranker)
- [OTel datasets](https://huggingface.co/farbodtavakkoli/datasets)
- [OTel 1.0 media coverage](https://github.com/farbodtavakkoli/OTel/blob/main/docs/OTel-1.0-media-coverage.md)
- [OTel 2.0 blogs and coverage](https://github.com/farbodtavakkoli/OTel/blob/main/docs/OTel-2.0-blogs.md)
- [OTel technical session recording at MWC](https://www.youtube.com/watch?v=QOYdtVT5Qxw)

**Selected organizational and media coverage**

- **GSMA:** [AT&T's OTel 2.0 release and Open Telco AI leaderboard](https://www.gsma.com/newsroom/article/atts-otel-2-0-is-now-live-the-largest-and-best-performing-open-source-model-built-for-telecoms/)
- **AT&T:** [OTel 2.0 and the tokenomics equation](https://about.att.com/blogs/2026/the-tokenomics-equation.html)
- **Google Cloud:** [Accelerating telecom AI with OTel and Gemma](https://cloud.google.com/blog/topics/telecommunications/open-models-global-networks-how-att-and-gsma-are-accelerating-innovation-with-gemma)
- **Microsoft:** [Scaling AT&T's trillion-token workflow](https://azure.microsoft.com/en-us/blog/att-and-microsoft-scale-trillion-token-workloads-with-microsoft-foundry-and-amd/)
- **AMD:** [AT&T's reported 94 percent training efficiency](https://www.amd.com/en/resources/case-studies/att-achieves-94-efficiency-for-ai-training-with-amd.html) and [Open Telco AI progress update](https://newsroom.amd.com/news/aai-2026-att-open-telco-update/)
- **Dell Technologies:** [Bringing OTel 2.0 to scale](https://www.dell.com/en-us/blog/otel-2-0-dell-technologies-at-t-and-amd-bring-open-telco-ai-to-scale/)
- **Red Hat:** [Training an open telecom model for an industry](https://www.redhat.com/en/blog/open-telco-ai-training-model-industry)
- ***The Wall Street Journal***: [Why AT&T is betting big on open-weight AI](https://www.wsj.com/cio-journal/why-at-t-is-betting-big-on-open-weight-ai-a0ea03b1) (subscription)
- ***Fierce Network***: [Open models and AT&T's tokenomics strategy](https://www.fierce-network.com/cloud/open-models-are-driving-atts-ai-tokenomics-strategy)
- ***The Information***: [AT&T is using open-source models to curb Anthropic bills](https://www.theinformation.com/newsletters/applied-ai/t-using-open-source-models-curb-anthropic-bills) (subscription)
- **Yahoo Finance:** [AT&T, NVIDIA, and the “token apocalypse”](https://finance.yahoo.com/technology/ai/articles/t-t-says-not-scared-231933381.html) (secondary coverage)

---

## Publications

- **OTel: Open Telco AI Datasets, Benchmarks, and Models**  
  F. Tavakkoli, G. Diamos, K. Church, et al. *NeurIPS 2026, Evaluations & Datasets Track — Spotlight.*  
  [Paper](https://github.com/farbodtavakkoli/OTel/blob/main/docs/OTel-NeurIPS-2026.pdf) · [Code](https://github.com/farbodtavakkoli/OTel) · [Models and datasets](https://huggingface.co/farbodtavakkoli)

- **OTel: Building Domain-Specialized Telecom LLM Foundations for Intelligent Networks**  
  F. Tavakkoli, R. Paulk, J. Terrazas, et al. *ACM AI Leadership Summit 2026, Breakthrough Impact Highlights Track.*  
  [arXiv:2608.15436](https://arxiv.org/abs/2608.15436)

<details>
<summary>BibTeX</summary>

```bibtex
@inproceedings{tavakkoli2026otel,
  title     = {OTel: Open Telco AI Datasets, Benchmarks, and Models},
  author    = {Tavakkoli, Farbod and Diamos, Gregory and Church, Kenneth and Kanter, David and Austin, Mark and Karim, Imtiaz and Rahman, Mirza Masfiqur and Debbah, Merouane Abdelkader and Nezami, Zeinab and Maatouk, Ali and Tassiulas, Leandros and Ying, Rex and Sorros, Nick and Powell, Louis and Vasiloglou, Nikolaos and Vaswani, Ashish and Singla, Somanshu and Chaluvaraju, Adarsh},
  booktitle = {Advances in Neural Information Processing Systems (NeurIPS), Evaluations and Datasets Track},
  year      = {2026},
  url       = {https://github.com/farbodtavakkoli/OTel}
}

@misc{tavakkoli2026foundations,
  title         = {OTel: Building Domain-Specialized Telecom LLM Foundations for Intelligent Networks},
  author        = {Tavakkoli, Farbod and Paulk, Roderic and Terrazas, Jorden and Church, Kenneth and Austin, Mark and Powell, Louis and Diamos, Gregory and Bariah, Lina and Zaidi, Syed Ali Raza and Hafeez, Maryam and Maatouk, Ali and Karim, Imtiaz},
  year          = {2026},
  eprint        = {2608.15436},
  archivePrefix = {arXiv},
  note          = {ACM AI Leadership Summit, Breakthrough Impact Highlights Track}
}
```

</details>

---

## Research, Benchmarks & Evaluation

I actively work with and contribute to modern evaluation frameworks and benchmarks for language models, including benchmarks on which our models have achieved #1 rankings a total of 10 times across multiple evaluation cycles.

- **GSMA Open Telco AI Leaderboard — 7-Benchmark Telecom LLM Evaluation Suite**  
  https://huggingface.co/spaces/GSMA/open-telco-leaderboard

- **TeleLogs — Agentic Root Cause Analysis**  
  https://huggingface.co/spaces/otellm/leaderboard

- **BIRD — Text-to-SQL Benchmark**  
  https://bird-bench.github.io/

- **Spider 2.0 — Text-to-SQL Benchmark**  
  https://spider2-sql.github.io/

---

## Community Impact Projects

These public-interest technology, nonprofit analytics, and responsible AI projects are maintained in the [Community Impact Projects repository](https://github.com/farbodtavakkoli/community-impact-projects).

- **OTel Safety Bench — Responsible AI Evaluation**  
  [Source and documentation](https://github.com/farbodtavakkoli/community-impact-projects/tree/main/otel-safety-bench)

- **Texas Trees Foundation — Climate and Environmental Sustainability**  
  [Live website](https://farbodtavakkoli.github.io/community-impact-projects/texas-tree-foundation/) · [Source](https://github.com/farbodtavakkoli/community-impact-projects/tree/main/texas-tree-foundation)

- **Builders of Hope CDC — Public Policy and Social Equity**  
  [Live website](https://farbodtavakkoli.github.io/community-impact-projects/builders-of-hope/) · [Source](https://github.com/farbodtavakkoli/community-impact-projects/tree/main/builders-of-hope)

- **Child Poverty Action Lab — Community Development & Public Safety**  
  [Live website](https://farbodtavakkoli.github.io/community-impact-projects/child-poverty-action-lab/) · [Source](https://github.com/farbodtavakkoli/community-impact-projects/tree/main/child-poverty-action-lab)

---
