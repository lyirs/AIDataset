# 智能体（Agent）

覆盖工具调用、网页代理、环境交互与软件工程代理的数据目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | ToolBench | English | [Site](https://openbmb.github.io/ToolBench/) | Apache-2.0 | 工具调用规划与 API 使用 | [Paper](https://arxiv.org/abs/2307.16789) | 带 API 文档的高信号开源 tool-use 数据资源。 |
| 2 | APIBank | English | [GitHub](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank) | Unknown | API 编排与工具增强问答 | [Docs](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank) | 早期但很实用的 agent API 使用基准。 |
| 3 | Mind2Web | English | [Site](https://osu-nlp-group.github.io/Mind2Web/) | Unknown | 基于真实轨迹的网页导航 | [Paper](https://arxiv.org/abs/2306.06070) | 从真实网站人类操作轨迹构建的强浏览器代理数据集。 |
| 4 | WebArena | English | [Site](https://webarena.dev/) | Unknown | 真实网站上的浏览器代理 | [Paper](https://arxiv.org/abs/2307.13854) | 现代网页代理研究里最常见的 benchmark 之一。 |
| 5 | MiniWoB++ | English | [Site](https://miniwob.farama.org/) | Apache-2.0 | 轻量级网页 UI 控制 | [Docs](https://miniwob.farama.org/) | 浏览器式代理交互最经典的入门环境之一。 |
| 6 | WebLINX | English | [Site](https://mcgill-nlp.github.io/weblinx/) | Unknown | 基于演示轨迹的网页代理学习 | [Docs](https://mcgill-nlp.github.io/weblinx/) | 收集了更真实的人类网页交互与轨迹信号。 |
| 7 | OSWorld | English | [Site](https://os-world.github.io/) | Unknown | 桌面与操作系统级多模态代理 | [Docs](https://os-world.github.io/) | computer-use 风格代理评测中的高信号资源。 |
| 8 | ALFWorld | English | [Site](https://alfworld.github.io/) | Unknown | 具身家庭任务规划与指令执行 | [Paper](https://arxiv.org/abs/2010.03768) | 结合文本与具身规划的长期经典基准。 |
| 9 | WorkArena | English | [Site](https://servicenow.github.io/WorkArena/) | Unknown | 企业流程自动化代理 | [Docs](https://servicenow.github.io/WorkArena/) | 很适合做真实业务流程和网页工作流代理评测。 |
| 10 | SWE-bench | Python / English | [Site](https://www.swebench.com/) | Unknown | 面向真实 issue 的软件工程代理 | [GitHub](https://github.com/SWE-bench/SWE-bench) | 仓库级 coding agent 的事实标准 benchmark。 |
| 11 | AgentBench | English | [GitHub](https://github.com/THUDM/AgentBench) | Apache-2.0 | 多环境 Agent 评测 | [Paper](https://arxiv.org/abs/2308.03688) | 同时覆盖推理、工具使用与交互任务的广谱 benchmark。 |
| 12 | BrowserGym | Interactive Web | [GitHub](https://github.com/ServiceNow/BrowserGym) | Apache-2.0 | 浏览器代理训练环境 | [Docs](https://github.com/ServiceNow/BrowserGym) | 用统一的 gym 风格接口整合多种 browser tasks。 |
| 13 | VisualWebArena | English | [GitHub](https://github.com/web-arena-x/visualwebarena) | MIT | 带视觉 grounding 的浏览器代理 | [Paper](https://arxiv.org/abs/2401.13649) | 在 WebArena 基础上加入截图和视觉感知网页任务。 |
| 14 | AndroidWorld | English | [GitHub](https://github.com/google-research/android_world) | Apache-2.0 | 手机设备代理与 Android 交互 | [Paper](https://arxiv.org/abs/2405.14573) | 当前最清晰、最官方的 smartphone-use agent 环境之一。 |
| 15 | LoCoMo | English | [GitHub](https://github.com/snap-research/locomo) | Unknown | 长期对话记忆评测 | [Paper](https://arxiv.org/abs/2402.17753) | 面向 memory-aware assistant 的高信号长对话 benchmark。 |
| 16 | LongMemEval | English | [GitHub](https://github.com/xiaowu0162/LongMemEval) | MIT | 长上下文记忆检索与问答 | [Paper](https://arxiv.org/abs/2407.12580) | 评估模型能否保留并正确检索长跨度对话中的关键信息。 |
| 17 | BFCL | English | [HF](https://huggingface.co/datasets/gorilla-llm/Berkeley-Function-Calling-Leaderboard) | Apache-2.0 | 函数调用与工具使用评测 | [Docs](https://gorilla.cs.berkeley.edu/leaderboard) | Berkeley Function Calling Leaderboard 已经成为 tool-using agent 的标准参考之一。 |
| 18 | tau2-bench | English | [GitHub](https://github.com/sierra-research/tau2-bench) | MIT | 双控制环境下的工具代理交互 | [Paper](https://arxiv.org/abs/2506.07982) | 相比 tau-bench 更新，强调协同、约束和真实策略交互。 |
| 19 | BrowseComp | English | [Site](https://openai.com/index/browsecomp/) | Unknown | 高难网页浏览与多跳事实定位 | [Paper](https://cdn.openai.com/pdf/5e10f4ab-d6f7-442e-9508-59515c65e35d/browsecomp.pdf) | OpenAI 官方浏览代理 benchmark，强调持续搜索和难定位事实。 |
| 20 | MLE-bench | English / code | [GitHub](https://github.com/openai/mle-bench) | MIT | 机器学习工程 agent 评测 | [Paper](https://arxiv.org/abs/2410.07095) | 面向端到端 ML engineering workflow 的高信号 agent benchmark。 |
| 21 | AppWorld | English | [Site](https://appworld.dev/) | Apache-2.0 | 函数调用与交互式编码 Agent | [Paper](https://arxiv.org/abs/2407.18901) | 它是 ACL 方向里很强的一类 benchmark，强调多应用执行、有状态工具使用和交互式代码生成。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [Safety-Evals](../Safety-Evals/README_ZH.md)
- [GAIA](https://huggingface.co/gaia-benchmark)
- [BrowseComp](https://openai.com/index/browsecomp/)
- [tau2-bench](https://github.com/sierra-research/tau2-bench)

## 收录说明

- 本页优先覆盖有真实交互环境和轨迹信号的资源，而不是纯静态 prompt 评测。
- Agent 研究里很多资源本来就是 environment 或 benchmark suite，而不是平面语料表，所以这里按研究实际形态收录。
- 记忆、长上下文和 agent memory 相关资源，当前先放在本页和 [Benchmarks](../Benchmarks/README_ZH.md)，等条目足够稳定再决定是否单独拆类。
