# Code

Datasets for code generation, code repair, execution-based evaluation, and repository understanding.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | HumanEval | Python | [GitHub](https://github.com/openai/human-eval) | MIT | Execution-based code generation | [Paper](https://arxiv.org/abs/2107.03374) | Foundational pass@k benchmark for code LLMs. |
| 2 | APPS | Python | [GitHub](https://github.com/hendrycks/apps) | MIT | Program synthesis with tests | [Paper](https://arxiv.org/abs/2105.09938) | Competitive-programming style tasks with public and hidden tests. |
| 3 | CodeSearchNet | Multilingual code | [GitHub](https://github.com/github/CodeSearchNet) | Mixed / source-repo licenses | Code search and NL-code retrieval | [Paper](https://arxiv.org/abs/1909.09436) | Long-running anchor dataset for code retrieval. |
| 4 | CodeXGLUE | Multilingual code | [GitHub](https://github.com/microsoft/CodeXGLUE) | Mixed / task-specific | Unified code intelligence benchmarking | [Paper](https://arxiv.org/abs/2102.04664) | Aggregates multiple tasks in one code benchmark suite. |
| 5 | SWE-bench | Python | [Site](https://www.swebench.com/) | Unknown | Issue-to-code evaluation and repair agents | [Paper](https://arxiv.org/abs/2310.06770) | High-signal standard for real-repository bug fixing. |
| 6 | The Stack | Multilingual code | [Site](https://www.bigcode-project.org/docs/about/the-stack/) | Mixed / source-repo licenses | Code pretraining at scale | [Paper](https://arxiv.org/abs/2211.15533) | Large permissive-code corpus used in many open code LLMs. |
| 7 | DS-1000 | Python | [Site](https://ds1000-code-gen.github.io/) | Unknown | Data science code generation and repair | [Paper](https://arxiv.org/abs/2211.11501) | Focuses on realistic Python data-science libraries and workflows. |
| 8 | CoNaLa | Python | [Site](https://conala-corpus.github.io/) | Unknown | Natural-language-to-code generation | [Paper](https://arxiv.org/abs/1805.08949) | Canonical text-to-snippet dataset for NL2Code work. |
| 9 | MultiPL-E | Multilingual code | [GitHub](https://github.com/nuprl/MultiPL-E) | Unknown | Multilingual code generation evaluation | [Paper](https://arxiv.org/abs/2208.08227) | Extends HumanEval-style problems across many programming languages. |
| 10 | CodeContests | Multilingual code | [GitHub](https://github.com/google-deepmind/code_contests) | CC BY 4.0 (data) / Apache-2.0 (code) | Contest-style program synthesis | [Paper](https://arxiv.org/abs/2203.07814) | Stronger and harder coding benchmark than toy-function datasets. |
| 11 | MBPP | Python | [HF](https://huggingface.co/datasets/google-research-datasets/mbpp) | Unknown | Prompt-to-code program synthesis | [Paper](https://arxiv.org/abs/2108.07732) | Common lightweight benchmark for NL-to-code comparisons. |
| 12 | BigCodeBench | Multilingual code | [GitHub](https://github.com/bigcode-project/bigcodebench) | Apache-2.0 | Hard instruction-to-code evaluation | [Docs](https://github.com/bigcode-project/bigcodebench) | Stresses more realistic coding instructions than HumanEval-style tasks. |
| 13 | LiveCodeBench | Multilingual code | [GitHub](https://github.com/LiveCodeBench/LiveCodeBench) | MIT | Contamination-resistant live code evaluation | [Paper](https://arxiv.org/abs/2403.07974) | Frequently reported in 2024-2026 code model releases as a harder live benchmark. |
| 14 | EvalPlus | Python | [GitHub](https://github.com/evalplus/evalplus) | Apache-2.0 | Stronger HumanEval and MBPP evaluation | [Paper](https://arxiv.org/abs/2305.01210) | Extends canonical code benchmarks with harder tests and sanitization. |
| 15 | RepoBench | Multilingual code | [GitHub](https://github.com/Leolty/repobench) | CC BY 4.0 | Repository-level code completion and understanding | [Paper](https://arxiv.org/abs/2306.03091) | Useful when models need larger codebase context instead of single functions. |
| 16 | CRUXEval | Python | [GitHub](https://github.com/facebookresearch/cruxeval) | MIT | Code reasoning and execution understanding | [Paper](https://arxiv.org/abs/2401.03065) | A compact high-signal benchmark for program reasoning beyond generation only. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [SWE-bench](https://www.swebench.com/)
- [HumanEval](https://github.com/openai/human-eval)
- [BigCodeBench](https://github.com/bigcode-project/bigcodebench)
- [BigCode Evaluation Harness](https://github.com/bigcode-project/bigcode-evaluation-harness)

## Selection Note

- This page prioritizes datasets with executable tests, real repository context, or long-running use in code LLM papers.
- Pure prompt collections without transparent dataset documentation are intentionally excluded.
