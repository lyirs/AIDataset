# Agent

Tool use, software engineering, long-context memory, and general interactive agent datasets.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | ToolBench | English | [Site](https://openbmb.github.io/ToolBench/) | Apache-2.0 | Tool-use planning and API calling | [Paper](https://arxiv.org/abs/2307.16789) | High-signal open tool-use corpus with API documentation. |
| 2 | APIBank | English | [GitHub](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank) | Unknown | API orchestration and tool-augmented QA | [Docs](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank) | Early benchmark focused on practical API usage by agents. |
| 3 | ALFWorld | English | [Site](https://alfworld.github.io/) | Unknown | Embodied household planning and instruction following | [Paper](https://arxiv.org/abs/2010.03768) | Long-running text-and-embodiment benchmark for grounded agents. |
| 4 | SWE-bench | Python / English | [Site](https://www.swebench.com/) | Unknown | Software engineering agents on real issues | [GitHub](https://github.com/SWE-bench/SWE-bench) | The de facto benchmark for repo-based coding agents. |
| 5 | AgentBench | English | [GitHub](https://github.com/THUDM/AgentBench) | Apache-2.0 | Multi-environment agent evaluation | [Paper](https://arxiv.org/abs/2308.03688) | Broad benchmark spanning reasoning, tool use, and interactive tasks. |
| 6 | LoCoMo | English | [GitHub](https://github.com/snap-research/locomo) | Unknown | Long-term conversational memory evaluation | [Paper](https://arxiv.org/abs/2402.17753) | High-signal benchmark for memory-aware assistants over long dialogues. |
| 7 | LongMemEval | English | [GitHub](https://github.com/xiaowu0162/LongMemEval) | MIT | Long-context memory retrieval and QA | [Paper](https://arxiv.org/abs/2407.12580) | Focuses on whether assistants can retain and retrieve salient long-horizon facts. |
| 8 | BFCL | English | [HF](https://huggingface.co/datasets/gorilla-llm/Berkeley-Function-Calling-Leaderboard) | Apache-2.0 | Function calling and tool-use evaluation | [Docs](https://gorilla.cs.berkeley.edu/leaderboard) | The Berkeley Function Calling Leaderboard is now a standard reference for tool-using LLM agents. |
| 9 | tau2-bench | English | [GitHub](https://github.com/sierra-research/tau2-bench) | MIT | Dual-control tool-agent-user interaction | [Paper](https://arxiv.org/abs/2506.07982) | A newer successor to tau-bench with stronger coordination and policy constraints. |
| 10 | MLE-bench | English / code | [GitHub](https://github.com/openai/mle-bench) | MIT | Machine learning engineering agents | [Paper](https://arxiv.org/abs/2410.07095) | High-signal benchmark for agents that run end-to-end ML engineering workflows. |
| 11 | AppWorld | English | [Site](https://appworld.dev/) | Apache-2.0 | Function calling and interactive coding agents | [Paper](https://arxiv.org/abs/2407.18901) | A strong ACL-era benchmark for multi-app execution, stateful tool use, and interactive code generation. |
| 12 | GAIA | English / tools | [HF](https://huggingface.co/datasets/gaia-benchmark/GAIA) | Unknown | General AI assistants with tool use and file handling | [Paper](https://arxiv.org/abs/2311.12983) | One of the most frequently cited general-assistant benchmarks beyond static QA. |

## Related Benchmarks

- [Computer-Use overview](../Computer-Use/README.md)
- [Benchmarks overview](../Benchmarks/README.md)
- [Safety-Evals](../Safety-Evals/README.md)
- [GAIA](https://huggingface.co/gaia-benchmark)
- [SWE-bench](https://www.swebench.com/)

## Selection Note

- Browser, desktop, and mobile computer-use resources now live in [Computer-Use](../Computer-Use/README.md).
- This page focuses on tool use, software engineering, general agent execution, and long-horizon memory resources.
