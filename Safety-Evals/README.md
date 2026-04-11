# Safety-Evals

Safety-focused eval registries, benchmark suites, and failure taxonomies for LLM and agent systems.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | OpenAI Evals | English | [GitHub](https://github.com/openai/evals) | MIT | Building and running custom LLM evals | [Docs](https://platform.openai.com/docs/guides/evals) | A public eval registry rather than a single dataset. |
| 2 | HarmActionsEval | English | [GitHub](https://github.com/Pro-GenAI/Agent-Action-Guard) | Unknown | Evaluating agent action safety | [Issue context](https://github.com/openai/evals/issues/1636) | Focuses on harmful tool-use actions rather than only final responses. |
| 3 | WFGY RAG 16 Problem Map | English | [GitHub](https://github.com/onestardao/WFGY) | MIT | RAG failure analysis and debugging taxonomy | [Issue context](https://github.com/openai/evals/issues/1629) | Taxonomy-style resource for diagnosing retrieval and answer failures. |
| 4 | BIG-bench | English | [GitHub](https://github.com/google/BIG-bench) | Apache-2.0 | Broad capability and robustness probing | [Paper](https://arxiv.org/abs/2206.04615) | Commonly requested in public eval-framework issues. |
| 5 | Agent-Action-Guard | English | [GitHub](https://github.com/Pro-GenAI/Agent-Action-Guard) | Unknown | Guarding and auditing tool-using agents | [Docs](https://github.com/Pro-GenAI/Agent-Action-Guard) | Closely related to HarmActionsEval and practical agent safety testing. |
| 6 | HarmBench | English | [GitHub](https://github.com/centerforaisafety/HarmBench) | MIT | Standardized LLM harm and refusal evaluation | [Docs](https://github.com/centerforaisafety/HarmBench) | A high-signal benchmark for automated red teaming and robust refusal testing. |
| 7 | JailbreakBench | English | [GitHub](https://github.com/JailbreakBench/jailbreakbench) | MIT | Jailbreak robustness evaluation | [Docs](https://github.com/JailbreakBench/jailbreakbench) | Focuses on reproducible jailbreak evaluation across models and attacks. |
| 8 | SafetyBench | Chinese/English | [GitHub](https://github.com/thu-coai/SafetyBench) | MIT | Bilingual LLM safety benchmark evaluation | [Paper](https://arxiv.org/abs/2309.07045) | A widely cited ACL-era safety benchmark with both Chinese and English multiple-choice tests. |
| 9 | AgentDojo | English | [GitHub](https://github.com/ethz-spylab/agentdojo) | MIT | Prompt-injection attack and defense evaluation for agents | [Paper](https://openreview.net/forum?id=m1YYAQjO3w) | One of the clearest official benchmarks for agent security and tool-use defenses. |
| 10 | StrongREJECT | English | [GitHub](https://github.com/dsbowen/strong_reject) | Mixed / source-specific | Jailbreak benchmarking and harmful prompt evaluation | [Paper](https://arxiv.org/abs/2402.10260) | High-signal jailbreak benchmark; prompt sources mix original and prior datasets with different terms. |
| 11 | AdvBench | English | [GitHub](https://github.com/llm-attacks/llm-attacks) | MIT (repo) / dataset terms unclear | Jailbreak attack-set evaluation | [Paper](https://arxiv.org/abs/2307.15043) | Probably the most reused harmful-behavior attack set in jailbreak and refusal studies. |
| 12 | XSTest | English | [GitHub](https://github.com/paul-rottger/xstest) | CC BY 4.0 | Over-refusal and exaggerated safety evaluation | [Paper](https://aclanthology.org/2024.naacl-long.301/) | A clean benchmark for testing whether models incorrectly refuse benign requests. |
| 13 | ToxicChat | English | [Site](https://www.lmsys.org/blog/2023-10-30-toxicchat/) | CC BY-NC 4.0 | Moderation and toxic jailbreak detection | [Paper](https://arxiv.org/abs/2310.17389) | Built from real user-assistant interactions and widely reused in safety classifier work. |
| 14 | DecodingTrust | English | [Site](https://decodingtrust.github.io/) | CC BY-SA 4.0 | Broad trust and safety benchmarking | [Paper](https://arxiv.org/abs/2306.11698) | One of the most cited broad safety suites spanning toxicity, robustness, privacy, fairness, and ethics. |
| 15 | CyberSecEval | English | [Site](https://meta-llama.github.io/PurpleLlama/CyberSecEval/) | MIT / mixed components | Cyber-risk evaluation for LLMs and agents | [Docs](https://github.com/meta-llama/PurpleLlama/tree/main/CybersecurityBenchmarks) | Official Meta benchmark family for insecure code, prompt injection, offensive cyber capability, and agentic risk. |
| 16 | Agent Security Bench (ASB) | English | [Site](https://luckfort.github.io/ASBench/) | MIT | Agent attack and defense evaluation | [Paper](https://openreview.net/forum?id=V4y0CpX4hK) | A high-signal benchmark focused on security risks and defenses for tool-using agents. |

## Notes

- This page intentionally mixes eval registries, benchmarks, and safety taxonomies.
- Some entries are attack sets, moderation corpora, or cybersecurity suites rather than raw downloadable datasets.
- These entries should not be confused with raw training datasets.
