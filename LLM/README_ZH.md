# 大语言模型（LLM）

覆盖大语言模型预训练语料、指令数据、偏好数据与对齐资源的目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

## 覆盖范围

- Pretraining: `C4`, `The Pile`, `Dolma`, `FineWeb`
- Instruction: `FLAN Collection`, `OpenAssistant Conversations`, `Dolly 15k`
- Preference: `UltraFeedback`, `HH-RLHF`
- Safety: `PKU-SafeRLHF`, `BeaverTails`, `WildChat`

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | C4 | English | [Site](https://www.tensorflow.org/datasets/catalog/c4) | Unknown | Web 规模预训练基线 | [Docs](https://www.tensorflow.org/datasets/catalog/c4) | T5 一类训练流程里最经典的清洗 Common Crawl 语料。 |
| 2 | The Pile | English | [Site](https://pile.eleuther.ai/) | Mixed / component-specific | 开放预训练混合语料 | [Paper](https://arxiv.org/abs/2101.00027) | 最常被引用的开放 LLM 预训练语料之一。 |
| 3 | Dolma | English | [Site](https://allenai.org/dolma) | Mixed / source-specific | 高质量开放预训练 | [Docs](https://allenai.org/dolma) | AI2 提供的大规模高质量预训练语料与透明处理流程。 |
| 4 | FLAN Collection | Multilingual | [GitHub](https://github.com/google-research/FLAN/tree/main/flan/v2) | Mixed / task-specific | 指令微调混合数据 | [Paper](https://arxiv.org/abs/2301.13688) | 开源模型里最常见的 instruction-tuning 数据混合方案之一。 |
| 5 | OpenAssistant Conversations | Multilingual | [HF](https://huggingface.co/datasets/OpenAssistant/oasst1) | Apache-2.0 | 开源助手式 SFT 数据 | [Docs](https://github.com/LAION-AI/Open-Assistant) | 面向聊天助手训练的大规模开放对话数据资源。 |
| 6 | Dolly 15k | English | [GitHub](https://github.com/databrickslabs/dolly) | CC BY-SA 3.0 | 轻量级指令微调 | [Docs](https://www.databricks.com/blog/2023/03/24/hello-dolly-democratizing-magic-chatgpt-open-models.html) | Databricks 发布的小规模但影响力很大的开放指令集。 |
| 7 | UltraFeedback | English | [GitHub](https://github.com/OpenBMB/UltraFeedback) | MIT | 偏好建模与 DPO 式后训练 | [Docs](https://github.com/OpenBMB/UltraFeedback) | 开源偏好学习和后训练里非常常见的数据家族。 |
| 8 | HH-RLHF | English | [HF](https://huggingface.co/datasets/Anthropic/hh-rlhf) | Unknown | Helpful/Harmless 偏好建模 | [Docs](https://github.com/anthropics/hh-rlhf) | 奖励模型与 RLHF 研究中的长期锚点数据集。 |
| 9 | PKU-SafeRLHF | English | [Site](https://sites.google.com/view/pku-saferlhf) | Unknown | 安全约束下的偏好优化 | [Paper](https://arxiv.org/abs/2406.15513) | PKU-Alignment 提供的高频安全对齐训练资源。 |
| 10 | BeaverTails | English | [Site](https://sites.google.com/view/pku-beavertails/home) | Unknown | 安全 SFT 与有害内容过滤 | [Paper](https://arxiv.org/abs/2307.04657) | 带细粒度风险标签的高信号安全语料。 |
| 11 | FineWeb | English | [HF](https://huggingface.co/datasets/HuggingFaceFW/fineweb) | ODC-By 1.0 | 高质量网页预训练 | [Docs](https://huggingface.co/datasets/HuggingFaceFW/fineweb) | 面向强开放预训练流程构建的现代网页语料。 |
| 12 | WildChat | Multilingual | [HF](https://huggingface.co/datasets/allenai/WildChat) | ODC-BY | 真实用户对话分布分析 | [Docs](https://huggingface.co/datasets/allenai/WildChat) | 适合研究真实聊天分布，而不只是合成式指令数据。 |

## 相关评测

- [LLM-Evals 总览](../LLM-Evals/README_ZH.md)
- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [Safety-Evals](../Safety-Evals/README_ZH.md)
- [OpenAI Evals](https://github.com/openai/evals)
- [OpenCompass](https://github.com/open-compass/opencompass)

## 收录说明

- 本页只收录训练资源，不收纯模型权重，也不把 benchmark-only 套件直接当成训练数据。
- LLM 评测资源依然重要，但会通过 `LLM-Evals`、`Benchmarks` 和 `Safety-Evals` 交叉链接，而不是在这里重复维护。
