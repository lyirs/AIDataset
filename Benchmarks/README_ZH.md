# 基准评测（Benchmarks）

覆盖 NLP、检索、多模态、代码、Agent 与通用评测平台的跨领域 benchmark 目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | GLUE | English | [Site](https://gluebenchmark.com/) | Unknown | 通用语言理解评测 | [Paper](https://aclanthology.org/W18-5446/) | 经典多任务 NLP benchmark。 |
| 2 | SuperGLUE | English | [Site](https://super.gluebenchmark.com/) | Unknown | 更难的 GLUE 后继 | [Paper](https://arxiv.org/abs/1905.00537) | 仍然适合做紧凑型推理评测。 |
| 3 | CLUE | Chinese | [GitHub](https://github.com/CLUEbenchmark/CLUE) | Unknown | 中文语言理解评测 | [Paper](https://arxiv.org/abs/2004.05986) | 中文 benchmark 体系中的核心项目。 |
| 4 | FewCLUE | Chinese | [GitHub](https://github.com/CLUEbenchmark/FewCLUE) | Unknown | 中文小样本评测 | [Paper](https://arxiv.org/abs/2107.07498) | 面向低资源场景非常有价值。 |
| 5 | CBLUE | Chinese | [GitHub](https://github.com/CBLUEbenchmark/CBLUE) | Unknown | 中文生物医学 NLP 评测 | [Paper](https://arxiv.org/abs/2204.04167) | 重要的垂直领域 benchmark。 |
| 6 | MTEB | Multilingual | [GitHub](https://github.com/embeddings-benchmark/mteb) | Apache-2.0 | Embedding 多任务评测 | [Docs](https://github.com/embeddings-benchmark/mteb) | 现代 embedding 评测中最活跃的注册表之一。 |
| 7 | BEIR | English | [GitHub](https://github.com/beir-cellar/beir) | Apache-2.0 (code) / mixed datasets | 零样本信息检索评测 | [Paper](https://arxiv.org/abs/2104.08663) | 检索系统的重要参考基准。 |
| 8 | MMMU | Multimodal | [Site](https://mmmu-benchmark.github.io/) | Unknown | 高难度多模态推理 | [Paper](https://arxiv.org/abs/2311.16502) | 学术型 VLM benchmark 中很有代表性。 |
| 9 | SWE-bench | English | [Site](https://www.swebench.com/) | Unknown | 代码 Agent 解决真实 GitHub issue | [Paper](https://arxiv.org/abs/2310.06770) | 代码代理方向的核心 benchmark。 |
| 10 | GAIA | English / tools | [HF](https://huggingface.co/datasets/gaia-benchmark/GAIA) | Unknown | 带工具调用的通用助手评测 | [Paper](https://arxiv.org/abs/2311.12983) | 用来评估实用型 assistant 的代表性 benchmark 之一，不止是静态问答。 |
| 11 | OpenOOD | Visual | [GitHub](https://github.com/Jingkang50/OpenOOD) | MIT | 分布外检测评测 | [Paper](https://arxiv.org/abs/2306.09301) | 近年视觉论文里 generalized OOD detection 最常见的开放 benchmark suite。 |
| 12 | OpenCompass | Multilingual / multimodal | [GitHub](https://github.com/open-compass/opencompass) | Apache-2.0 | 多模型多任务统一评测执行 | [Docs](https://opencompass.readthedocs.io/en/latest/) | 当前最常用的开放评测平台之一，聚合了大量现代 LLM 与多模态 benchmark。 |
| 13 | MMBench | Chinese/English multimodal | [Site](https://mmbench.opencompass.org.cn/home) | Unknown | 全面视觉语言 benchmark 评测 | [Paper](https://arxiv.org/abs/2307.06281) | 它是目前引用频率最高的中英双语综合型 VLM benchmark 之一。 |
| 14 | MathVista | Multimodal | [Site](https://mathvista.github.io/) | CC BY-SA 4.0 | 视觉数学推理评测 | [Paper](https://arxiv.org/abs/2310.02255) | 现在几乎已经成了多模态数学推理对比表里的默认 benchmark。 |
| 15 | Video-MME | Video + language | [Site](https://video-mme.github.io/home_page.html) | Unknown | 通用视频语言模型评测 | [Paper](https://arxiv.org/abs/2405.21075) | 近两年比较视频大模型时最常出现的 benchmark 之一。 |
| 16 | AgentBench | English / environments | [GitHub](https://github.com/THUDM/AgentBench) | Apache-2.0 (benchmark repo) / mixed task backends | 交互环境中的 Agent 评测 | [Paper](https://arxiv.org/abs/2308.03688) | 它是“把 LLM 当 Agent 来评测”这条线里最经典的早期 benchmark 之一。 |
| 17 | WILDS | Multidomain | [Site](https://wilds.stanford.edu/datasets/) | Mixed / dataset-specific | 真实世界分布偏移评测 | [Paper](https://arxiv.org/abs/2012.07421) | 它是评估 in-the-wild distribution shift 的标准 benchmark suite，覆盖视觉、语言和生物等多类任务。 |
| 18 | RobustBench | Visual | [Site](https://robustbench.github.io/) | Apache-2.0 (benchmark code) | 标准化对抗鲁棒性评测 | [Paper](https://openreview.net/forum?id=SSKZPJCt7B) | 它是现代视觉鲁棒性论文里最常用的开放 benchmark 和 leaderboard 之一。 |
| 19 | SEED-Bench | Multimodal | [GitHub](https://github.com/AILab-CVC/SEED-Bench) | Apache-2.0 | 生成式多模态评测 | [Paper](https://arxiv.org/abs/2307.16125) | 它是评估多模态大模型 generative comprehension 能力时最常见的一组 benchmark 家族之一。 |

## 额外交叉索引

- [LLM-Evals 总览](../LLM-Evals/README_ZH.md)
- [MMBench](https://mmbench.opencompass.org.cn/home)
- [MathVista](https://mathvista.github.io/)
- [Video-MME](https://video-mme.github.io/home_page.html)
- [BRIGHT](https://brightbenchmark.github.io/)
- [OpenOOD](https://github.com/Jingkang50/OpenOOD)
- [WILDS](https://wilds.stanford.edu/datasets/)
- [RobustBench](https://robustbench.github.io/)
- [SEED-Bench](https://github.com/AILab-CVC/SEED-Bench)
- [CRAG](../Search-Retrieval/README_ZH.md)
- [RealMMRAg](../Search-Retrieval/README_ZH.md)
- [AfriMTEB](../Search-Retrieval/README_ZH.md)
- [HarmActionsEval](../Safety-Evals/README_ZH.md)

## 收录说明

- 本页保留跨领域、任务族和平台型 benchmark 资源。
- 已经形成独立簇的大语言模型评测，现单独维护在 [LLM-Evals](../LLM-Evals/README_ZH.md)。
