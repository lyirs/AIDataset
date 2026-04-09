# 大语言模型评测（LLM-Evals）

覆盖大语言模型指令遵循、推理、真实性、聊天与长上下文能力的 benchmark 数据目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | BIG-bench | English | [GitHub](https://github.com/google/BIG-bench) | Apache-2.0 | 跨任务广谱能力探测 | [Paper](https://arxiv.org/abs/2206.04615) | 这是最早也是最有代表性的协作式 LLM 综合评测之一。 |
| 2 | HELM | English | [GitHub](https://github.com/stanford-crfm/helm) | Apache-2.0 | 基于场景的整体评测 | [Paper](https://arxiv.org/abs/2211.09110) | 强调透明和可复现，是影响力很大的 LLM 评测框架。 |
| 3 | MMLU | English | [GitHub](https://github.com/hendrycks/test) | MIT | 广覆盖学科知识评测 | [Paper](https://arxiv.org/abs/2009.03300) | 仍然是通用 LLM 报告里出现频率最高的一类 benchmark。 |
| 4 | HellaSwag | English | [GitHub](https://github.com/rowanz/hellaswag) | MIT | 常识续写与 grounded 推理 | [Paper](https://aclanthology.org/P19-1472/) | 开源模型报告里几乎默认会出现的常识推理 benchmark。 |
| 5 | ARC-Challenge | English | [Site](https://allenai.org/data/arc) | CC BY-SA 4.0 | 科学推理与高难度选择题问答 | [Paper](https://arxiv.org/abs/1803.05457) | ARC 的困难子集至今仍是高频推理参考基准。 |
| 6 | WinoGrande | English | [GitHub](https://github.com/allenai/winogrande) | CC BY 4.0 (dataset) / Apache-2.0 (code) | 常识指代消解 | [Paper](https://arxiv.org/abs/1907.10641) | 现在经常作为更稳健的 Winograd 风格测试被使用。 |
| 7 | IFEval | English | [GitHub](https://github.com/google-research/google-research/tree/master/instruction_following_eval) | CC BY 4.0 (dataset) / Apache-2.0 (code) | 指令遵循能力评测 | [Paper](https://arxiv.org/abs/2311.07911) | 2024 年后几乎成为 instruction-following 的标准评测之一。 |
| 8 | BIG-Bench Hard (BBH) | English | [GitHub](https://github.com/suzgunmirac/BIG-Bench-Hard) | MIT | 高难推理与 CoT 压力测试 | [Paper](https://arxiv.org/abs/2210.09261) | BIG-bench 的高信号困难子集，现代 reasoning 表里经常会报。 |
| 9 | TruthfulQA | English | [GitHub](https://github.com/sylinrl/TruthfulQA) | Apache-2.0 | 真实性与幻觉倾向评测 | [Paper](https://aclanthology.org/2022.acl-long.229/) | 仍然是前沿模型评测里最常见的 factuality benchmark 之一。 |
| 10 | GPQA | English | [HF](https://huggingface.co/datasets/Idavidrein/gpqa) | CC BY 4.0 | 专家级科学问答评测 | [Paper](https://arxiv.org/abs/2311.12022) | 前沿模型报告中高频出现的高信号推理 benchmark。 |
| 11 | LiveBench | English | [GitHub](https://github.com/LiveBench/LiveBench) | Apache-2.0 | 防污染的动态评测 | [Paper](https://arxiv.org/abs/2406.19314) | 会持续刷新，近两年在新模型发布表里非常常见。 |
| 12 | WildBench | English | [GitHub](https://github.com/allenai/WildBench) | Apache-2.0 | 真实用户开放式聊天评测 | [Paper](https://allenai.github.io/WildBench/WildBench_paper.pdf) | 用更贴近真实用户的问题来补足 arena 风格评测的不足。 |
| 13 | MuSR | English | [GitHub](https://github.com/Zayne-sprague/MuSR) | MIT | 多步软推理 | [Paper](https://arxiv.org/abs/2310.16049) | 是近年越来越常见的一类更强 reasoning benchmark。 |
| 14 | SimpleQA | English | [Site](https://openai.com/index/introducing-simpleqa/) | Unknown | 短事实问答评测 | [Paper](https://cdn.openai.com/papers/simpleqa.pdf) | 已经成为前沿模型报告里高频出现的 factuality 参考 benchmark。 |
| 15 | RULER | English | [GitHub](https://github.com/NVIDIA/RULER) | Apache-2.0 | 长上下文检索与推理评测 | [Paper](https://arxiv.org/abs/2404.06654) | 当前最清晰的一类 long-context 压力测试之一。 |
| 16 | InfiniteBench | English | [GitHub](https://github.com/OpenBMB/InfiniteBench) | MIT | 超长上下文评测 | [Paper](https://arxiv.org/abs/2402.13718) | 在长上下文论文里常与 RULER 和 LongBench 一起报告。 |
| 17 | LongBench v2 | Multilingual long context | [Site](https://longbench2.github.io/) | Unknown | 更真实的长上下文推理评测 | [Paper](https://aclanthology.org/2025.acl-long.183/) | 比 synthetic needle test 更接近真实 long-context 使用场景。 |
| 18 | MMLU-Pro | English | [GitHub](https://github.com/TIGER-AI-Lab/MMLU-Pro) | Apache-2.0 | 比 MMLU 更难的学科推理评测 | [Paper](https://papers.neurips.cc/paper_files/paper/2024/file/ad236edc564f3e3156e1b2feafb99a24-Paper-Datasets_and_Benchmarks_Track.pdf) | 2024-2026 模型报告里常见的 MMLU 强化版。 |
| 19 | MMLU-Redux | English | [GitHub](https://github.com/aryopg/mmlu-redux) | CC BY 4.0 | 更干净、错误更少的知识评测 | [Paper](https://aclanthology.org/2025.naacl-long.262/) | 用于缓解原始 MMLU 的标注和答案噪声问题。 |
| 20 | Arena-Hard-Auto | English | [GitHub](https://github.com/lmarena/arena-hard-auto) | Apache-2.0 | 自动化聊天模型评测 | [Paper](https://arxiv.org/abs/2403.04132) | 在 arena-style 评测基础上加入自动评分流程。 |
| 21 | RewardBench / RewardBench 2 | English | [GitHub](https://github.com/allenai/reward-bench) | Apache-2.0 | Reward model 与 judge model 评测 | [Paper](https://arxiv.org/abs/2506.01937) | 当前最清晰的一类开放 reward-model benchmark 家族，也常用于后训练 judge 分析。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [Safety-Evals](../Safety-Evals/README_ZH.md)
- [OpenCompass](https://github.com/open-compass/opencompass)
- [OpenAI Evals](https://github.com/openai/evals)
- [WildBench](https://github.com/allenai/WildBench)

## 收录说明

- 本页主要收录会在现代 LLM 能力对比表里单独报告的 benchmark 数据集与评测套件。
- 训练语料与偏好数据仍然保留在 [LLM](../LLM/README_ZH.md)。
