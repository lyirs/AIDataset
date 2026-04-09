# Agent

Tool use, browser agents, environment interaction, and software engineering agent datasets.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | ToolBench | English | [Site](https://openbmb.github.io/ToolBench/) | Apache-2.0 | Tool-use planning and API calling | [Paper](https://arxiv.org/abs/2307.16789) | High-signal open tool-use corpus with API documentation. |
| 2 | APIBank | English | [GitHub](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank) | Unknown | API orchestration and tool-augmented QA | [Docs](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank) | Early benchmark focused on practical API usage by agents. |
| 3 | Mind2Web | English | [Site](https://osu-nlp-group.github.io/Mind2Web/) | Unknown | Real web navigation from human traces | [Paper](https://arxiv.org/abs/2306.06070) | Strong browser-agent dataset built from real-world websites. |
| 4 | WebArena | English | [Site](https://webarena.dev/) | Unknown | Browser agents on realistic websites | [Paper](https://arxiv.org/abs/2307.13854) | One of the main modern benchmarks for web agents. |
| 5 | MiniWoB++ | English | [Site](https://miniwob.farama.org/) | Apache-2.0 | Lightweight web UI control | [Docs](https://miniwob.farama.org/) | Standard starting point for browser-like agent interaction. |
| 6 | WebLINX | English | [Site](https://mcgill-nlp.github.io/weblinx/) | Unknown | Grounded web-agent learning from demonstrations | [Docs](https://mcgill-nlp.github.io/weblinx/) | Captures realistic human web interactions and trajectories. |
| 7 | OSWorld | English | [Site](https://os-world.github.io/) | Unknown | Desktop and OS-level multimodal agents | [Docs](https://os-world.github.io/) | High-signal benchmark for computer-use style agents. |
| 8 | ALFWorld | English | [Site](https://alfworld.github.io/) | Unknown | Embodied household planning and instruction following | [Paper](https://arxiv.org/abs/2010.03768) | Long-running text-and-embodiment benchmark for grounded agents. |
| 9 | WorkArena | English | [Site](https://servicenow.github.io/WorkArena/) | Unknown | Enterprise workflow automation agents | [Docs](https://servicenow.github.io/WorkArena/) | Useful for realistic business-process and web workflow agents. |
| 10 | SWE-bench | Python / English | [Site](https://www.swebench.com/) | Unknown | Software engineering agents on real issues | [GitHub](https://github.com/SWE-bench/SWE-bench) | The de facto benchmark for repo-based coding agents. |
| 11 | AgentBench | English | [GitHub](https://github.com/THUDM/AgentBench) | Apache-2.0 | Multi-environment agent evaluation | [Paper](https://arxiv.org/abs/2308.03688) | Broad benchmark spanning reasoning, tool use, and interactive tasks. |
| 12 | BrowserGym | Interactive Web | [GitHub](https://github.com/ServiceNow/BrowserGym) | Apache-2.0 | Browser-agent training environments | [Docs](https://github.com/ServiceNow/BrowserGym) | Unifies several browser tasks under a common gym-style interface. |
| 13 | VisualWebArena | English | [GitHub](https://github.com/web-arena-x/visualwebarena) | MIT | Multimodal browser agents with visual grounding | [Paper](https://arxiv.org/abs/2401.13649) | Extends WebArena with screenshot-grounded web tasks. |
| 14 | AndroidWorld | English | [GitHub](https://github.com/google-research/android_world) | Apache-2.0 | Mobile device agents and Android interaction | [Paper](https://arxiv.org/abs/2405.14573) | One of the clearest official environments for smartphone-use agents. |
| 15 | LoCoMo | English | [GitHub](https://github.com/snap-research/locomo) | Unknown | Long-term conversational memory evaluation | [Paper](https://arxiv.org/abs/2402.17753) | High-signal benchmark for memory-aware assistants over long dialogues. |
| 16 | LongMemEval | English | [GitHub](https://github.com/xiaowu0162/LongMemEval) | MIT | Long-context memory retrieval and QA | [Paper](https://arxiv.org/abs/2407.12580) | Focuses on whether assistants can retain and retrieve salient long-horizon facts. |
| 17 | BFCL | English | [HF](https://huggingface.co/datasets/gorilla-llm/Berkeley-Function-Calling-Leaderboard) | Apache-2.0 | Function calling and tool-use evaluation | [Docs](https://gorilla.cs.berkeley.edu/leaderboard) | The Berkeley Function Calling Leaderboard is now a standard reference for tool-using LLM agents. |
| 18 | tau2-bench | English | [GitHub](https://github.com/sierra-research/tau2-bench) | MIT | Dual-control tool-agent-user interaction | [Paper](https://arxiv.org/abs/2506.07982) | A newer successor to tau-bench with stronger coordination and policy constraints. |
| 19 | BrowseComp | English | [Site](https://openai.com/index/browsecomp/) | Unknown | Hard web browsing and multi-hop fact finding | [Paper](https://cdn.openai.com/pdf/5e10f4ab-d6f7-442e-9508-59515c65e35d/browsecomp.pdf) | Official OpenAI benchmark for persistent browsing agents on hard-to-find web facts. |
| 20 | MLE-bench | English / code | [GitHub](https://github.com/openai/mle-bench) | MIT | Machine learning engineering agents | [Paper](https://arxiv.org/abs/2410.07095) | High-signal benchmark for agents that run end-to-end ML engineering workflows. |
| 21 | AppWorld | English | [Site](https://appworld.dev/) | Apache-2.0 | Function calling and interactive coding agents | [Paper](https://arxiv.org/abs/2407.18901) | A strong ACL-era benchmark for multi-app execution, stateful tool use, and interactive code generation. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [Safety-Evals](../Safety-Evals/README.md)
- [GAIA](https://huggingface.co/gaia-benchmark)
- [BrowseComp](https://openai.com/index/browsecomp/)
- [tau2-bench](https://github.com/sierra-research/tau2-bench)

## Selection Note

- This page prioritizes grounded interactive resources instead of static prompt-only evaluations.
- Some entries are environments or benchmark suites rather than flat downloadable corpora, because that is how agent research is actually organized.
- Memory- and long-context-agent resources stay here and in [Benchmarks](../Benchmarks/README.md) until they justify a standalone top-level directory.
