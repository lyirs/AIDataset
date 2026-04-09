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

## Notes

- This page intentionally mixes eval registries, benchmarks, and safety taxonomies.
- These entries should not be confused with raw training datasets.
