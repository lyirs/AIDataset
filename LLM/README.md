# LLM

Pretraining corpora, instruction data, preference data, and alignment resources for large language models.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

## Coverage Map

- Pretraining: `C4`, `The Pile`, `Dolma`, `FineWeb`, `RefinedWeb`, `RedPajama-Data-1T`
- Instruction: `FLAN Collection`, `Super-NaturalInstructions`, `Aya Dataset`, `Self-Instruct`, `OpenAssistant Conversations`, `Dolly 15k`, `P3`
- Preference: `UltraFeedback`, `HH-RLHF`
- Safety: `PKU-SafeRLHF`, `BeaverTails`
- Real conversations: `WildChat`

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | C4 | English | [Site](https://www.tensorflow.org/datasets/catalog/c4) | Unknown | Web-scale pretraining baselines | [Docs](https://www.tensorflow.org/datasets/catalog/c4) | Canonical cleaned Common Crawl corpus used by T5-style training. |
| 2 | The Pile | English | [Site](https://pile.eleuther.ai/) | Mixed / component-specific | Open pretraining mixtures | [Paper](https://arxiv.org/abs/2101.00027) | One of the most cited open LLM pretraining corpora. |
| 3 | Dolma | English | [Site](https://allenai.org/dolma) | Mixed / source-specific | High-quality open pretraining | [Docs](https://allenai.org/dolma) | AI2's large curated pretraining corpus with transparent pipeline notes. |
| 4 | FLAN Collection | Multilingual | [GitHub](https://github.com/google-research/FLAN/tree/main/flan/v2) | Mixed / task-specific | Instruction-tuning mixtures | [Paper](https://arxiv.org/abs/2301.13688) | Canonical instruction-tuning mixture used across many open models. |
| 5 | OpenAssistant Conversations | Multilingual | [HF](https://huggingface.co/datasets/OpenAssistant/oasst1) | Apache-2.0 | Open assistant-style SFT data | [Docs](https://github.com/LAION-AI/Open-Assistant) | Large open conversational dataset built for chat assistant training. |
| 6 | Dolly 15k | English | [GitHub](https://github.com/databrickslabs/dolly) | CC BY-SA 3.0 | Lightweight instruction tuning | [Docs](https://www.databricks.com/blog/2023/03/24/hello-dolly-democratizing-magic-chatgpt-open-models.html) | Small but influential open instruction set from Databricks. |
| 7 | UltraFeedback | English | [GitHub](https://github.com/OpenBMB/UltraFeedback) | MIT | Preference modeling and DPO-style tuning | [Docs](https://github.com/OpenBMB/UltraFeedback) | Common open preference dataset family for post-training. |
| 8 | HH-RLHF | English | [HF](https://huggingface.co/datasets/Anthropic/hh-rlhf) | Unknown | Helpful and harmless preference modeling | [Docs](https://github.com/anthropics/hh-rlhf) | Long-running anchor dataset for reward modeling and RLHF research. |
| 9 | PKU-SafeRLHF | English | [Site](https://sites.google.com/view/pku-saferlhf) | Unknown | Safety-aware preference optimization | [Paper](https://arxiv.org/abs/2406.15513) | Widely used open safety-alignment resource from PKU-Alignment. |
| 10 | BeaverTails | English | [Site](https://sites.google.com/view/pku-beavertails/home) | Unknown | Safety SFT and harmfulness filtering | [Paper](https://arxiv.org/abs/2307.04657) | High-signal safety corpus with fine-grained harm labels. |
| 11 | FineWeb | English | [HF](https://huggingface.co/datasets/HuggingFaceFW/fineweb) | ODC-By 1.0 | High-quality web pretraining | [Docs](https://huggingface.co/datasets/HuggingFaceFW/fineweb) | Modern open web corpus built for strong large-scale pretraining pipelines. |
| 12 | WildChat | Multilingual | [HF](https://huggingface.co/datasets/allenai/WildChat) | ODC-BY | Real user-assistant dialogue analysis | [Docs](https://huggingface.co/datasets/allenai/WildChat) | Useful when studying real-world chat distributions beyond synthetic prompts. |
| 13 | Super-NaturalInstructions | English | [GitHub](https://github.com/allenai/natural-instructions) | Mixed / task-specific | Cross-task instruction tuning | [Paper](https://arxiv.org/abs/2204.07705) | Strong instruction-generalization collection spanning hundreds of task templates and source datasets. |
| 14 | Self-Instruct | English | [GitHub](https://github.com/yizhongw/self-instruct) | Apache-2.0 | Synthetic instruction generation | [Paper](https://arxiv.org/abs/2212.10560) | Foundational synthetic instruction dataset family behind many Alpaca-style pipelines. |
| 15 | P3 (Public Pool of Prompts) | English | [HF](https://huggingface.co/datasets/bigscience/P3) | Apache-2.0 | Prompted multitask instruction tuning | [Paper](https://arxiv.org/abs/2110.08207) | Canonical prompted mixture used in T0-style training and instruction generalization studies. |
| 16 | RefinedWeb | English | [HF](https://huggingface.co/datasets/tiiuae/falcon-refinedweb) | ODC-By 1.0 | Web-only LLM pretraining | [Paper](https://arxiv.org/abs/2306.01116) | Important open web corpus behind Falcon and later pretraining comparisons. |
| 17 | RedPajama-Data-1T | English | [HF](https://huggingface.co/datasets/togethercomputer/RedPajama-Data-1T) | Mixed / subset-specific | Open LLaMA-style pretraining mixtures | [Docs](https://github.com/togethercomputer/RedPajama-Data) | Major open reproduction of the LLaMA data recipe with subset-level license constraints. |
| 18 | Aya Dataset | Multilingual | [HF](https://huggingface.co/datasets/CohereLabs/aya_dataset) | Apache-2.0 | Multilingual instruction tuning | [Paper](https://arxiv.org/abs/2402.06619) | High-signal multilingual instruction dataset spanning dozens of languages for open multilingual LLMs. |

## Related Benchmarks

- [LLM-Evals overview](../LLM-Evals/README.md)
- [Benchmarks overview](../Benchmarks/README.md)
- [Safety-Evals](../Safety-Evals/README.md)
- [OpenAI Evals](https://github.com/openai/evals)
- [OpenCompass](https://github.com/open-compass/opencompass)

## Selection Note

- This page focuses on training resources rather than model checkpoints or benchmark-only suites.
- LLM eval resources still matter, but they are cross-linked through `LLM-Evals`, `Benchmarks`, and `Safety-Evals` instead of duplicated here.
