# 大语言模型（LLM）

覆盖大语言模型预训练语料、指令数据、偏好数据与对齐资源的目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

## 覆盖范围

- 预训练：`C4`, `The Pile`, `Dolma`, `FineWeb`, `RefinedWeb`, `RedPajama-Data-1T`, `SlimPajama-627B`, `OpenWebMath`
- 指令数据：`FLAN Collection`, `Super-NaturalInstructions`, `Aya Dataset`, `Self-Instruct`, `OpenAssistant Conversations`, `Dolly 15k`, `P3`, `UltraChat 200k`, `No Robots`, `Tulu V2 SFT Mixture`, `LIMA`
- 偏好数据：`UltraFeedback`, `HH-RLHF`, `Nectar`
- 安全对齐：`PKU-SafeRLHF`, `BeaverTails`
- 真实对话：`WildChat`, `LMSYS-Chat-1M`

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
| 13 | Super-NaturalInstructions | English | [GitHub](https://github.com/allenai/natural-instructions) | Mixed / task-specific | 跨任务指令微调 | [Paper](https://arxiv.org/abs/2204.07705) | 覆盖大量任务模板与源数据集，是 instruction generalization 研究中的核心资源。 |
| 14 | Self-Instruct | English | [GitHub](https://github.com/yizhongw/self-instruct) | Apache-2.0 | 合成指令数据生成 | [Paper](https://arxiv.org/abs/2212.10560) | Alpaca 一类合成指令流程背后最有代表性的开源数据家族之一。 |
| 15 | P3 (Public Pool of Prompts) | English | [HF](https://huggingface.co/datasets/bigscience/P3) | Apache-2.0 | Prompt 化多任务指令微调 | [Paper](https://arxiv.org/abs/2110.08207) | T0 一类训练与指令泛化研究里最经典的 prompted mixture。 |
| 16 | RefinedWeb | English | [HF](https://huggingface.co/datasets/tiiuae/falcon-refinedweb) | ODC-By 1.0 | 纯网页 LLM 预训练 | [Paper](https://arxiv.org/abs/2306.01116) | Falcon 及后续开放基座模型预训练对比中经常出现的网页语料。 |
| 17 | RedPajama-Data-1T | English | [HF](https://huggingface.co/datasets/togethercomputer/RedPajama-Data-1T) | Mixed / subset-specific | 开放 LLaMA 风格预训练混合语料 | [Docs](https://github.com/togethercomputer/RedPajama-Data) | 面向复现 LLaMA 数据配方的重要开放语料，但许可需按子集分别理解。 |
| 18 | Aya Dataset | Multilingual | [HF](https://huggingface.co/datasets/CohereLabs/aya_dataset) | Apache-2.0 | 多语言指令微调 | [Paper](https://arxiv.org/abs/2402.06619) | 覆盖数十种语言，是开放多语言 LLM 里很高频的 instruction 数据。 |
| 19 | SlimPajama-627B | English | [HF](https://huggingface.co/datasets/cerebras/SlimPajama-627B) | Mixed / subset-specific | 去重后的开放大规模预训练 | [Docs](https://www.cerebras.net/blog/slimpajama-a-627b-token-cleaned-and-deduplicated-version-of-redpajama) | 它是 RedPajama 清洗和去重后的高频替代版本，在开放预训练里复用率很高。 |
| 20 | OpenWebMath | English | [HF](https://huggingface.co/datasets/open-web-math/open-web-math) | ODC-By 1.0 | 数学导向预训练 | [Paper](https://arxiv.org/abs/2310.06786) | 它是近两年开放数学与推理模型最常引用的数学网页语料之一。 |
| 21 | UltraChat 200k | English | [HF](https://huggingface.co/datasets/HuggingFaceH4/ultrachat_200k) | MIT | 多轮指令微调 | [Paper](https://arxiv.org/abs/2305.14233) | 它是 Zephyr 一类开放聊天模型后训练里非常常见的多轮 SFT 数据。 |
| 22 | No Robots | English | [HF](https://huggingface.co/datasets/HuggingFaceH4/no_robots) | CC BY-NC 4.0 | 人工编写指令微调 | [Docs](https://huggingface.co/datasets/HuggingFaceH4/no_robots) | 它是开放对齐研究里很重要的人写指令数据，可作为合成数据的对照。 |
| 23 | Tulu V2 SFT Mixture | English | [HF](https://huggingface.co/datasets/allenai/tulu-v2-sft-mixture) | ODC-BY / subset-specific | 开放指令混合后训练 | [Paper](https://arxiv.org/abs/2311.10702) | 它是 Tulu 与后续 open-instruct 系列中很核心的一套后训练混合数据。 |
| 24 | LMSYS-Chat-1M | Multilingual | [HF](https://huggingface.co/datasets/lmsys/lmsys-chat-1m) | Custom / LMSYS dataset agreement | 真实世界聊天建模与分析 | [Paper](https://arxiv.org/abs/2309.11998) | 它来自 Chatbot Arena 与 Vicuna demo 的真实用户对话，是研究真实 prompt 分布的重要资源。 |
| 25 | LIMA | English | [HF](https://huggingface.co/datasets/GAIR/lima) | CC BY-NC-SA / source-specific | 小样本高质量指令微调 | [Paper](https://arxiv.org/abs/2305.11206) | 它以“小而精”的 SFT 设计著名，是开放对齐论文里被反复引用的代表性数据。 |
| 26 | Nectar | English | [HF](https://huggingface.co/datasets/berkeley-nest/Nectar) | Custom / non-commercial restrictions | 偏好建模与奖励训练 | [Docs](https://huggingface.co/datasets/berkeley-nest/Nectar) | 它是高质量排序响应数据，在奖励模型和 DPO 一类实验里出现频率很高。 |

## 相关评测

- [LLM-Evals 总览](../LLM-Evals/README_ZH.md)
- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [Safety-Evals](../Safety-Evals/README_ZH.md)
- [OpenAI Evals](https://github.com/openai/evals)
- [OpenCompass](https://github.com/open-compass/opencompass)

## 收录说明

- 本页只收录训练资源，不收纯模型权重，也不把 benchmark-only 套件直接当成训练数据。
- LLM 评测资源依然重要，但会通过 `LLM-Evals`、`Benchmarks` 和 `Safety-Evals` 交叉链接，而不是在这里重复维护。
