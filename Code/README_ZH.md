# 代码（Code）

覆盖代码生成、程序修复、执行式评测与仓库理解的数据目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | HumanEval | Python | [GitHub](https://github.com/openai/human-eval) | MIT | 执行式代码生成评测 | [Paper](https://arxiv.org/abs/2107.03374) | 代码 LLM 里最经典的 pass@k 基准之一。 |
| 2 | APPS | Python | [GitHub](https://github.com/hendrycks/apps) | MIT | 带测试用例的程序合成 | [Paper](https://arxiv.org/abs/2105.09938) | 竞赛风格题目，包含公开与隐藏测试。 |
| 3 | CodeSearchNet | Multilingual code | [GitHub](https://github.com/github/CodeSearchNet) | Mixed / source-repo licenses | 代码搜索与自然语言检索代码 | [Paper](https://arxiv.org/abs/1909.09436) | 代码检索方向长期使用的锚点数据集。 |
| 4 | CodeXGLUE | Multilingual code | [GitHub](https://github.com/microsoft/CodeXGLUE) | Mixed / task-specific | 统一代码智能任务评测 | [Paper](https://arxiv.org/abs/2102.04664) | 把多种代码任务聚合进一个 benchmark 套件。 |
| 5 | SWE-bench | Python | [Site](https://www.swebench.com/) | Unknown | issue-to-code 评测与修复代理 | [Paper](https://arxiv.org/abs/2310.06770) | 真实仓库 bug fixing 的高信号标准基准。 |
| 6 | The Stack | Multilingual code | [Site](https://www.bigcode-project.org/docs/about/the-stack/) | Mixed / source-repo licenses | 大规模代码预训练 | [Paper](https://arxiv.org/abs/2211.15533) | 许多开源代码模型都会引用的大规模代码语料。 |
| 7 | DS-1000 | Python | [Site](https://ds1000-code-gen.github.io/) | Unknown | 数据科学代码生成与修复 | [Paper](https://arxiv.org/abs/2211.11501) | 强调真实 Python 数据科学库与工作流。 |
| 8 | CoNaLa | Python | [Site](https://conala-corpus.github.io/) | Unknown | 自然语言到代码生成 | [Paper](https://arxiv.org/abs/1805.08949) | NL2Code 方向最经典的文本到代码数据集之一。 |
| 9 | MultiPL-E | Multilingual code | [GitHub](https://github.com/nuprl/MultiPL-E) | Unknown | 多语言代码生成评测 | [Paper](https://arxiv.org/abs/2208.08227) | 将 HumanEval 风格问题扩展到多种编程语言。 |
| 10 | CodeContests | Multilingual code | [GitHub](https://github.com/google-deepmind/code_contests) | CC BY 4.0 (data) / Apache-2.0 (code) | 竞赛式程序合成 | [Paper](https://arxiv.org/abs/2203.07814) | 比 toy-function 更难、更接近真实竞赛环境。 |
| 11 | MBPP | Python | [HF](https://huggingface.co/datasets/google-research-datasets/mbpp) | Unknown | 提示到代码的程序合成 | [Paper](https://arxiv.org/abs/2108.07732) | NL2Code 对比里最常见的轻量级编程基准之一。 |
| 12 | BigCodeBench | Multilingual code | [GitHub](https://github.com/bigcode-project/bigcodebench) | Apache-2.0 | 高难度 instruction-to-code 评测 | [Docs](https://github.com/bigcode-project/bigcodebench) | 比 HumanEval 风格任务更强调真实复杂编码指令。 |
| 13 | LiveCodeBench | Multilingual code | [GitHub](https://github.com/LiveCodeBench/LiveCodeBench) | MIT | 防污染的实时代码评测 | [Paper](https://arxiv.org/abs/2403.07974) | 2024-2026 代码模型发布里非常高频的 live benchmark。 |
| 14 | EvalPlus | Python | [GitHub](https://github.com/evalplus/evalplus) | Apache-2.0 | 更严格的 HumanEval 与 MBPP 评测 | [Paper](https://arxiv.org/abs/2305.01210) | 为经典代码基准补充更难测试用例和更严格清洗。 |
| 15 | RepoBench | Multilingual code | [GitHub](https://github.com/Leolty/repobench) | CC BY 4.0 | 仓库级代码补全与理解 | [Paper](https://arxiv.org/abs/2306.03091) | 适合评估需要更大代码库上下文的模型，而不只是单函数生成。 |
| 16 | CRUXEval | Python | [GitHub](https://github.com/facebookresearch/cruxeval) | MIT | 代码推理与执行理解 | [Paper](https://arxiv.org/abs/2401.03065) | 一个紧凑但信号很强的程序推理 benchmark，不只看生成结果。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [SWE-bench](https://www.swebench.com/)
- [HumanEval](https://github.com/openai/human-eval)
- [BigCodeBench](https://github.com/bigcode-project/bigcodebench)
- [BigCode Evaluation Harness](https://github.com/bigcode-project/bigcode-evaluation-harness)

## 收录说明

- 本页优先覆盖带可执行测试、真实仓库上下文，或在代码 LLM 论文中长期使用的数据集。
- 只有提示词集合、缺少清晰数据说明的资源不会被纳入这里。
