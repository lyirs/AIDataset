# LLM-Evals

Instruction following, reasoning, truthfulness, chat, and long-context benchmark datasets for large language models.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | BIG-bench | English | [GitHub](https://github.com/google/BIG-bench) | Apache-2.0 | Broad capability probing across tasks | [Paper](https://arxiv.org/abs/2206.04615) | A foundational collaborative benchmark for diverse LLM capability evaluation. |
| 2 | HELM | English | [GitHub](https://github.com/stanford-crfm/helm) | Apache-2.0 | Scenario-based holistic model evaluation | [Paper](https://arxiv.org/abs/2211.09110) | One of the most influential frameworks for transparent LLM benchmarking. |
| 3 | MMLU | English | [GitHub](https://github.com/hendrycks/test) | MIT | Broad subject-matter knowledge evaluation | [Paper](https://arxiv.org/abs/2009.03300) | Still one of the most frequently reported general LLM benchmarks. |
| 4 | HellaSwag | English | [GitHub](https://github.com/rowanz/hellaswag) | MIT | Commonsense completion and grounded reasoning | [Paper](https://aclanthology.org/P19-1472/) | A near-default commonsense reasoning benchmark in open-model reports. |
| 5 | ARC-Challenge | English | [Site](https://allenai.org/data/arc) | CC BY-SA 4.0 | Science reasoning and difficult multiple-choice QA | [Paper](https://arxiv.org/abs/1803.05457) | The harder ARC split remains a standard reasoning reference point. |
| 6 | WinoGrande | English | [GitHub](https://github.com/allenai/winogrande) | CC BY 4.0 (dataset) / Apache-2.0 (code) | Commonsense coreference resolution | [Paper](https://arxiv.org/abs/1907.10641) | Commonly used as a robust replacement for older Winograd-style tests. |
| 7 | IFEval | English | [GitHub](https://github.com/google-research/google-research/tree/master/instruction_following_eval) | CC BY 4.0 (dataset) / Apache-2.0 (code) | Instruction-following evaluation | [Paper](https://arxiv.org/abs/2311.07911) | A standard post-2024 benchmark for programmatically verifiable instruction following. |
| 8 | BIG-Bench Hard (BBH) | English | [GitHub](https://github.com/suzgunmirac/BIG-Bench-Hard) | MIT | Hard reasoning and chain-of-thought stress tests | [Paper](https://arxiv.org/abs/2210.09261) | A compact but high-signal subset of BIG-bench tasks widely used in reasoning tables. |
| 9 | TruthfulQA | English | [GitHub](https://github.com/sylinrl/TruthfulQA) | Apache-2.0 | Truthfulness and hallucination-style evaluation | [Paper](https://aclanthology.org/2022.acl-long.229/) | Still a standard reference benchmark for factuality and imitative falsehoods. |
| 10 | GPQA | English | [HF](https://huggingface.co/datasets/Idavidrein/gpqa) | CC BY 4.0 | Expert-level science QA evaluation | [Paper](https://arxiv.org/abs/2311.12022) | A high-signal reasoning benchmark in frontier-model reports. |
| 11 | LiveBench | English | [GitHub](https://github.com/LiveBench/LiveBench) | Apache-2.0 | Live contamination-resistant evaluation | [Paper](https://arxiv.org/abs/2406.19314) | Frequently refreshed and now common in release tables for new models. |
| 12 | WildBench | English | [GitHub](https://github.com/allenai/WildBench) | Apache-2.0 | Real-user open-ended chat evaluation | [Paper](https://allenai.github.io/WildBench/WildBench_paper.pdf) | Complements arena-style evaluation with harder in-the-wild user requests. |
| 13 | MuSR | English | [GitHub](https://github.com/Zayne-sprague/MuSR) | MIT | Multi-step soft reasoning | [Paper](https://arxiv.org/abs/2310.16049) | A stronger recent reasoning benchmark that increasingly appears in modern eval bundles. |
| 14 | SimpleQA | English | [Site](https://openai.com/index/introducing-simpleqa/) | Unknown | Short-form factuality evaluation | [Paper](https://cdn.openai.com/papers/simpleqa.pdf) | Now a common factuality reference point in frontier model reports. |
| 15 | RULER | English | [GitHub](https://github.com/NVIDIA/RULER) | Apache-2.0 | Long-context retrieval and reasoning evaluation | [Paper](https://arxiv.org/abs/2404.06654) | One of the clearest recent long-context stress tests. |
| 16 | InfiniteBench | English | [GitHub](https://github.com/OpenBMB/InfiniteBench) | MIT | Very-long-context evaluation beyond 100K tokens | [Paper](https://arxiv.org/abs/2402.13718) | Often reported alongside RULER and LongBench in long-context papers. |
| 17 | LongBench v2 | Multilingual long context | [Site](https://longbench2.github.io/) | Unknown | Realistic long-context reasoning evaluation | [Paper](https://aclanthology.org/2025.acl-long.183/) | A stronger long-context benchmark than synthetic needle tests. |
| 18 | MMLU-Pro | English | [GitHub](https://github.com/TIGER-AI-Lab/MMLU-Pro) | Apache-2.0 | Harder subject-matter reasoning than MMLU | [Paper](https://papers.neurips.cc/paper_files/paper/2024/file/ad236edc564f3e3156e1b2feafb99a24-Paper-Datasets_and_Benchmarks_Track.pdf) | A common harder successor to vanilla MMLU in 2024-2026 reports. |
| 19 | MMLU-Redux | English | [GitHub](https://github.com/aryopg/mmlu-redux) | CC BY 4.0 | Cleaner knowledge evaluation with fewer answer errors | [Paper](https://aclanthology.org/2025.naacl-long.262/) | Reduces annotation and answer-key noise in the original MMLU. |
| 20 | Arena-Hard-Auto | English | [GitHub](https://github.com/lmarena/arena-hard-auto) | Apache-2.0 | Automatic chat-model benchmarking | [Paper](https://arxiv.org/abs/2403.04132) | Extends arena-style evaluation with automatic grading workflows. |
| 21 | RewardBench / RewardBench 2 | English | [GitHub](https://github.com/allenai/reward-bench) | Apache-2.0 | Reward-model and judge-model evaluation | [Paper](https://arxiv.org/abs/2506.01937) | The clearest open benchmark family for modern reward-model evaluation and post-training judge analysis. |
| 22 | Humanity's Last Exam (HLE) | Multimodal expert QA | [Site](https://lastexam.ai/) | MIT | Frontier-level knowledge and reasoning evaluation | [Paper](https://arxiv.org/abs/2501.14249) | Rapidly became a default frontier benchmark for testing expert-level reasoning breadth. |
| 23 | BrowseComp | Web browsing | [Site](https://openai.com/index/browsecomp/) | MIT (benchmark repo) | Web-browsing agent evaluation | [Paper](https://arxiv.org/abs/2504.12516) | A strong benchmark for persistent, hard-to-Google browsing tasks; the official implementation lives in `simple-evals`. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [Safety-Evals](../Safety-Evals/README.md)
- [OpenCompass](https://github.com/open-compass/opencompass)
- [OpenAI Evals](https://github.com/openai/evals)
- [WildBench](https://github.com/allenai/WildBench)

## Selection Note

- This page focuses on benchmark datasets and eval suites that are mainly reported in modern LLM capability tables.
- Training corpora and preference datasets remain in [LLM](../LLM/README.md).
