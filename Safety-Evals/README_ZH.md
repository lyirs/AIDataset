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

## 说明

- 本页有意混合了 eval registry、benchmark 与安全 taxonomy。
- 这些条目不应被误解成原始训练数据集。
