## Introduction

I'm a Data Scientist at AT&T and the technical lead for [Open Telco (OTel) AI](https://github.com/farbodtavakkoli/OTel), AT&T's open model family for telecom AI within the broader Open Telco AI initiative launched by GSMA at MWC 2026. GSMA provided core telecom standards data, while AT&T developed and trained OTel models, including the [31B OTel 2.0 release](https://huggingface.co/farbodtavakkoli/OTel-2.0-LLM-31B-IT).

OTel has grown from open telecom datasets and specialized language, embedding, reranking, classification, and safety models into a reproducible training and inference ecosystem. The repository now includes 27 distinct training stacks and nine inference stacks across AMD, NVIDIA, Apple, and Intel hardware. AMD Instinct MI355X and NVIDIA H100 received the most extensive end-to-end verification. Twenty-two of the 27 training stacks run on both AMD and NVIDIA without changes to the training code; only the environment setup changes, including ROCm or CUDA and compatible PyTorch versions.

My work spans data curation, model development, post-training, evaluation, benchmarking, hardware validation, deployment, documentation, and open-source release. Current work includes publishing the OTel 2.0 training implementation, releasing a comprehensive OTel 2.0 evaluation through MLPeFT in collaboration with MLCommons, expanding training and inference support with the AWS and Tenstorrent teams, comparing GRPO and multi-node training stacks, and benchmarking AMD Ryzen inference. OTel models have reached tens of millions of downloads worldwide.

### Featured OTel Links

**Project resources**

- [Code, training stacks, inference stacks, and hardware-verification evidence](https://github.com/farbodtavakkoli/OTel)
- [OTel 2.0 31B model card and weights](https://huggingface.co/farbodtavakkoli/OTel-2.0-LLM-31B-IT)
- Model collections: [LLMs](https://huggingface.co/collections/farbodtavakkoli/otel-llm), [embeddings](https://huggingface.co/collections/farbodtavakkoli/otel-embedding), and [rerankers](https://huggingface.co/collections/farbodtavakkoli/otel-reranker)
- [OTel datasets](https://huggingface.co/farbodtavakkoli/datasets)
- [OTel research paper](https://arxiv.org/abs/2608.15436)
- [Media coverage](https://github.com/farbodtavakkoli/OTel/blob/main/docs/media_coverage.md)

**Selected organizational coverage**

- [GSMA: AT&T's OTel 2.0 release and Open Telco AI leaderboard](https://www.gsma.com/newsroom/article/atts-otel-2-0-is-now-live-the-largest-and-best-performing-open-source-model-built-for-telecoms/)
- [AT&T: OTel 2.0 and the tokenomics equation](https://about.att.com/blogs/2026/the-tokenomics-equation.html)
- [Google Cloud: Accelerating telecom AI with OTel and Gemma](https://cloud.google.com/blog/topics/telecommunications/open-models-global-networks-how-att-and-gsma-are-accelerating-innovation-with-gemma)
- [Microsoft: Scaling AT&T's trillion-token workflow](https://azure.microsoft.com/en-us/blog/att-and-microsoft-scale-trillion-token-workloads-with-microsoft-foundry-and-amd/)
- [AMD: AT&T's reported 94 percent training efficiency](https://www.amd.com/en/resources/case-studies/att-achieves-94-efficiency-for-ai-training-with-amd.html)
- [Dell Technologies: Bringing OTel 2.0 to scale](https://www.dell.com/en-us/blog/otel-2-0-dell-technologies-at-t-and-amd-bring-open-telco-ai-to-scale/)
- [Red Hat: Training an open telecom model for an industry](https://www.redhat.com/en/blog/open-telco-ai-training-model-industry)
- [*The Wall Street Journal*: Why AT&T is betting big on open-weight AI](https://www.wsj.com/cio-journal/why-at-t-is-betting-big-on-open-weight-ai-a0ea03b1) (subscription)
- [*Fierce Network*: Open models and AT&T's tokenomics strategy](https://www.fierce-network.com/cloud/open-models-are-driving-atts-ai-tokenomics-strategy)
- [*The Information*: AT&T is using open-source models to curb Anthropic bills](https://www.theinformation.com/newsletters/applied-ai/t-using-open-source-models-curb-anthropic-bills) (subscription)
- [Yahoo Finance: AT&T, NVIDIA, and the “token apocalypse”](https://finance.yahoo.com/technology/ai/articles/t-t-says-not-scared-231933381.html) (secondary coverage)

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

## Selected Open-Source Project Websites

- **Texas Trees Foundation — Climate and Environmental Sustainability**  
  https://farbodtavakkoli.github.io/Texas-Tree-Foundation/

- **Builders of Hope CDC — Public Policy and Social Equity**  
  https://farbodtavakkoli.github.io/Builders-of-Hope/

- **Child Poverty Action Lab — Community Development & Public Safety**  
  https://farbodtavakkoli.github.io/Child-Poverty-Action-Lab/

---
