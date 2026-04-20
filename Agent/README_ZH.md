# 智能体（Agent）

覆盖工具调用、软件工程、长上下文记忆与通用交互 agent 的数据目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | ToolBench | English | [Site](https://openbmb.github.io/ToolBench/) | Apache-2.0 | 工具调用规划与 API 使用 | [Paper](https://arxiv.org/abs/2307.16789) | 带 API 文档的高信号开源 tool-use 数据资源。 |
| 2 | APIBank | English | [GitHub](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank) | Unknown | API 编排与工具增强问答 | [Docs](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank) | 早期但很实用的 agent API 使用基准。 |
| 3 | ALFWorld | English | [Site](https://alfworld.github.io/) | Unknown | 具身家庭任务规划与指令执行 | [Paper](https://arxiv.org/abs/2010.03768) | 结合文本与具身规划的长期经典基准。 |
| 4 | SWE-bench | Python / English | [Site](https://www.swebench.com/) | Unknown | 面向真实 issue 的软件工程代理 | [GitHub](https://github.com/SWE-bench/SWE-bench) | 仓库级 coding agent 的事实标准 benchmark。 |
| 5 | AgentBench | English | [GitHub](https://github.com/THUDM/AgentBench) | Apache-2.0 | 多环境 Agent 评测 | [Paper](https://arxiv.org/abs/2308.03688) | 同时覆盖推理、工具使用与交互任务的广谱 benchmark。 |
| 6 | LoCoMo | English | [GitHub](https://github.com/snap-research/locomo) | Unknown | 长期对话记忆评测 | [Paper](https://arxiv.org/abs/2402.17753) | 面向 memory-aware assistant 的高信号长对话 benchmark。 |
| 7 | LongMemEval | English | [GitHub](https://github.com/xiaowu0162/LongMemEval) | MIT | 长上下文记忆检索与问答 | [Paper](https://arxiv.org/abs/2407.12580) | 评估模型能否保留并正确检索长跨度对话中的关键信息。 |
| 8 | BFCL | English | [HF](https://huggingface.co/datasets/gorilla-llm/Berkeley-Function-Calling-Leaderboard) | Apache-2.0 | 函数调用与工具使用评测 | [Docs](https://gorilla.cs.berkeley.edu/leaderboard) | Berkeley Function Calling Leaderboard 已经成为 tool-using agent 的标准参考之一。 |
| 9 | tau2-bench | English | [GitHub](https://github.com/sierra-research/tau2-bench) | MIT | 双控制环境下的工具代理交互 | [Paper](https://arxiv.org/abs/2506.07982) | 相比 tau-bench 更新，强调协同、约束和真实策略交互。 |
| 10 | MLE-bench | English / code | [GitHub](https://github.com/openai/mle-bench) | MIT | 机器学习工程 agent 评测 | [Paper](https://arxiv.org/abs/2410.07095) | 面向端到端 ML engineering workflow 的高信号 agent benchmark。 |
| 11 | AppWorld | English | [Site](https://appworld.dev/) | Apache-2.0 | 函数调用与交互式编码 Agent | [Paper](https://arxiv.org/abs/2407.18901) | 它是 ACL 方向里很强的一类 benchmark，强调多应用执行、有状态工具使用和交互式代码生成。 |
| 12 | GAIA | English / tools | [HF](https://huggingface.co/datasets/gaia-benchmark/GAIA) | Unknown | 带工具调用与文件处理的通用助手评测 | [Paper](https://arxiv.org/abs/2311.12983) | 它是超越静态问答、衡量通用助手真实能力时最常被引用的 benchmark 之一。 |

## 相关评测

- [Computer-Use 总览](../Computer-Use/README_ZH.md)
- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [Safety-Evals](../Safety-Evals/README_ZH.md)
- [GAIA](https://huggingface.co/gaia-benchmark)
- [SWE-bench](https://www.swebench.com/)

## 收录说明

- 浏览器、桌面与移动端的 computer-use 资源现已集中到 [Computer-Use](../Computer-Use/README_ZH.md)。
- 本页主要保留工具调用、软件工程、通用 agent 执行与长程记忆相关资源。
