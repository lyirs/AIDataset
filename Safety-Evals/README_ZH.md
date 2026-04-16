# 安全评测（Safety-Evals）

面向 LLM 与 Agent 系统的安全评测、benchmark 与 failure taxonomy 目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | OpenAI Evals | English | [GitHub](https://github.com/openai/evals) | MIT | 构建和运行自定义 LLM 评测 | [Docs](https://platform.openai.com/docs/guides/evals) | 它是公开 eval registry，不是单个数据集。 |
| 2 | HarmActionsEval | English | [GitHub](https://github.com/Pro-GenAI/Agent-Action-Guard) | Unknown | Agent 动作安全评测 | [Issue context](https://github.com/openai/evals/issues/1636) | 关注有害工具调用，而不只是最终回答安全。 |
| 3 | WFGY RAG 16 Problem Map | English | [GitHub](https://github.com/onestardao/WFGY) | MIT | RAG 失败分析与调试 taxonomy | [Issue context](https://github.com/openai/evals/issues/1629) | 更像 failure map，而不是 raw dataset。 |
| 4 | BIG-bench | English | [GitHub](https://github.com/google/BIG-bench) | Apache-2.0 | 大范围能力与鲁棒性评测 | [Paper](https://arxiv.org/abs/2206.04615) | 在公开 eval 框架 issue 里经常被请求接入。 |
| 5 | Agent-Action-Guard | English | [GitHub](https://github.com/Pro-GenAI/Agent-Action-Guard) | Unknown | 工具型 Agent 的防护与审计 | [Docs](https://github.com/Pro-GenAI/Agent-Action-Guard) | 与 HarmActionsEval 高度相关，偏实战防护。 |
| 6 | HarmBench | English | [GitHub](https://github.com/centerforaisafety/HarmBench) | MIT | 标准化 LLM 有害性与拒答评测 | [Docs](https://github.com/centerforaisafety/HarmBench) | 自动化 red teaming 与 robust refusal 测试中的高信号 benchmark。 |
| 7 | JailbreakBench | English | [GitHub](https://github.com/JailbreakBench/jailbreakbench) | MIT | 越狱鲁棒性评测 | [Docs](https://github.com/JailbreakBench/jailbreakbench) | 强调跨模型、跨攻击方式的可复现 jailbreak 评测。 |
| 8 | SafetyBench | Chinese/English | [GitHub](https://github.com/thu-coai/SafetyBench) | MIT | 中英双语 LLM 安全 benchmark 评测 | [Paper](https://arxiv.org/abs/2309.07045) | ACL 方向里很有代表性的安全 benchmark，同时覆盖中文和英文选择题。 |
| 9 | AgentDojo | English | [GitHub](https://github.com/ethz-spylab/agentdojo) | MIT | Agent 提示注入攻击与防御评测 | [Paper](https://openreview.net/forum?id=m1YYAQjO3w) | 它是目前最清晰、最官方的 agent security 与 tool-use defense benchmark 之一。 |
| 10 | StrongREJECT | English | [GitHub](https://github.com/dsbowen/strong_reject) | Mixed / source-specific | 越狱 benchmark 与有害提示评测 | [Paper](https://arxiv.org/abs/2402.10260) | 信号很强的越狱评测资源，但提示来源混合了原创与既有数据集，许可需要保守处理。 |
| 11 | AdvBench | English | [GitHub](https://github.com/llm-attacks/llm-attacks) | MIT (repo) / dataset terms unclear | 越狱攻击集评测 | [Paper](https://arxiv.org/abs/2307.15043) | 它大概是 jailbreak 与 refusal 研究里复用率最高的一批 harmful-behavior attack set。 |
| 12 | XSTest | English | [GitHub](https://github.com/paul-rottger/xstest) | CC BY 4.0 | 过度拒答与夸张安全行为评测 | [Paper](https://aclanthology.org/2024.naacl-long.301/) | 这是目前最干净的一类 false refusal / exaggerated safety benchmark。 |
| 13 | ToxicChat | English | [Site](https://www.lmsys.org/blog/2023-10-30-toxicchat/) | CC BY-NC 4.0 | 内容安全审核与有毒越狱检测 | [Paper](https://arxiv.org/abs/2310.17389) | 基于真实用户与助手交互构建，在 safety classifier 论文里出现频率很高。 |
| 14 | DecodingTrust | English | [Site](https://decodingtrust.github.io/) | CC BY-SA 4.0 | 广义可信与安全评测 | [Paper](https://arxiv.org/abs/2306.11698) | 它是最常被引用的一类大而全安全套件之一，覆盖毒性、鲁棒性、隐私、公平与伦理。 |
| 15 | CyberSecEval | English | [Site](https://meta-llama.github.io/PurpleLlama/CyberSecEval/) | MIT / mixed components | 面向 LLM 与 Agent 的网络安全风险评测 | [Docs](https://github.com/meta-llama/PurpleLlama/tree/main/CybersecurityBenchmarks) | Meta 官方 benchmark 家族，覆盖不安全代码、提示注入、攻击能力与 agentic cyber 风险。 |
| 16 | Agent Security Bench (ASB) | English | [Site](https://luckfort.github.io/ASBench/) | MIT | Agent 攻防评测 | [Paper](https://openreview.net/forum?id=V4y0CpX4hK) | 面向工具型 Agent 的安全风险与防御评测，信号很强。 |
| 17 | SALAD-Bench | English | [GitHub](https://github.com/OpenSafetyLab/SALAD-BENCH) | Apache-2.0 | 分层式 LLM 安全与越狱评测 | [Paper](https://arxiv.org/abs/2402.05044) | 它是当前规模较大、结构最完整的一类安全 benchmark 之一，还配有 MD-Judge 自动评测器。 |
| 18 | AgentHarm | English | [HF](https://huggingface.co/datasets/ai-safety-institute/AgentHarm) | MIT + safety-use clause | 工具型 Agent 有害行为评测 | [Paper](https://arxiv.org/abs/2410.09024) | 它专门评估显式恶意、多步骤 agent 任务；当前公开版是 UK AISI 托管的部分发布。 |
| 19 | Do-Not-Answer | English | [HF](https://huggingface.co/datasets/LibrAI/do-not-answer) | CC BY-NC-SA 4.0 | 安全拒答与 abstention 评测 | [Paper](https://arxiv.org/abs/2308.13387) | 这是安全对齐研究里最经典、也最常被引用的一类“该不该回答” benchmark。 |
| 20 | ToxiGen | English | [HF](https://huggingface.co/datasets/toxigen/toxigen-data) | Research use / gated access | 隐式毒性与有害文本安全评测 | [Paper](https://arxiv.org/abs/2203.09509) | 它在 toxicity、moderation 与 harmful generation 评测中复用率很高。 |

## 说明

- 本页有意混合了 eval registry、benchmark 与安全 taxonomy。
- 这里也包含 attack set、moderation 数据与 cyber benchmark family，而不只是一类标准数据集。
- 这些条目不应被误解成原始训练数据集。
