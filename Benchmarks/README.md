# Benchmarks

Cross-domain benchmark suites for NLP, retrieval, multimodal systems, coding, agents, and general evaluation platforms.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | GLUE | English | [Site](https://gluebenchmark.com/) | Unknown | General language understanding evaluation | [Paper](https://aclanthology.org/W18-5446/) | Foundational multi-task NLP benchmark. |
| 2 | SuperGLUE | English | [Site](https://super.gluebenchmark.com/) | Unknown | Harder successor to GLUE | [Paper](https://arxiv.org/abs/1905.00537) | Still useful as a compact reasoning suite. |
| 3 | CLUE | Chinese | [GitHub](https://github.com/CLUEbenchmark/CLUE) | Unknown | Chinese language understanding evaluation | [Paper](https://arxiv.org/abs/2004.05986) | Core Chinese benchmark family. |
| 4 | FewCLUE | Chinese | [GitHub](https://github.com/CLUEbenchmark/FewCLUE) | Unknown | Few-shot Chinese NLP evaluation | [Paper](https://arxiv.org/abs/2107.07498) | Strong low-resource Chinese benchmark. |
| 5 | CBLUE | Chinese | [GitHub](https://github.com/CBLUEbenchmark/CBLUE) | Unknown | Chinese biomedical NLP evaluation | [Paper](https://arxiv.org/abs/2204.04167) | High-value domain-specific benchmark. |
| 6 | MTEB | Multilingual | [GitHub](https://github.com/embeddings-benchmark/mteb) | Apache-2.0 | Embedding evaluation across tasks | [Docs](https://github.com/embeddings-benchmark/mteb) | One of the most active modern eval registries. |
| 7 | BEIR | English | [GitHub](https://github.com/beir-cellar/beir) | Apache-2.0 (code) / mixed datasets | Zero-shot information retrieval benchmarking | [Paper](https://arxiv.org/abs/2104.08663) | A standard reference for retrieval systems. |
| 8 | MMMU | Multimodal | [Site](https://mmmu-benchmark.github.io/) | Unknown | College-level multimodal reasoning | [Paper](https://arxiv.org/abs/2311.16502) | Strong academic benchmark for advanced VLMs. |
| 9 | SWE-bench | English | [Site](https://www.swebench.com/) | Unknown | Real GitHub issue resolution by code agents | [Paper](https://arxiv.org/abs/2310.06770) | A central coding-agent benchmark. |
| 10 | GAIA | English / tools | [HF](https://huggingface.co/datasets/gaia-benchmark/GAIA) | Unknown | General assistant evaluation with tool use | [Paper](https://arxiv.org/abs/2311.12983) | Widely cited for evaluating practical assistant behavior beyond static QA. |
| 11 | OpenOOD | Visual | [GitHub](https://github.com/Jingkang50/OpenOOD) | MIT | Out-of-distribution detection benchmarking | [Paper](https://arxiv.org/abs/2306.09301) | The de facto open benchmark suite for generalized OOD detection in recent vision papers. |
| 12 | OpenCompass | Multilingual / multimodal | [GitHub](https://github.com/open-compass/opencompass) | Apache-2.0 | Unified benchmark execution across models and tasks | [Docs](https://opencompass.readthedocs.io/en/latest/) | A widely used open evaluation platform that aggregates many modern LLM and multimodal benchmarks. |
| 13 | MMBench | Chinese/English multimodal | [Site](https://mmbench.opencompass.org.cn/home) | Unknown | Holistic vision-language benchmark evaluation | [Paper](https://arxiv.org/abs/2307.06281) | One of the most cited bilingual all-around VLM benchmarks. |
| 14 | MathVista | Multimodal | [Site](https://mathvista.github.io/) | CC BY-SA 4.0 | Visual mathematical reasoning evaluation | [Paper](https://arxiv.org/abs/2310.02255) | Now a near-default benchmark for math-heavy multimodal reasoning tables. |
| 15 | Video-MME | Video + language | [Site](https://video-mme.github.io/home_page.html) | Unknown | General video-language model evaluation | [Paper](https://arxiv.org/abs/2405.21075) | A standard recent benchmark for comparing video-LLMs across broad capability slices. |
| 16 | AgentBench | English / environments | [GitHub](https://github.com/THUDM/AgentBench) | Apache-2.0 (benchmark repo) / mixed task backends | Agent benchmarking across interactive environments | [Paper](https://arxiv.org/abs/2308.03688) | A canonical early benchmark for treating LLMs as agents rather than static chatbots. |
| 17 | WILDS | Multidomain | [Site](https://wilds.stanford.edu/datasets/) | Mixed / dataset-specific | Real-world distribution shift benchmarking | [Paper](https://arxiv.org/abs/2012.07421) | A standard suite for evaluating robustness under in-the-wild distribution shifts across vision, language, and biology tasks. |
| 18 | RobustBench | Visual | [Site](https://robustbench.github.io/) | Apache-2.0 (benchmark code) | Standardized adversarial robustness benchmarking | [Paper](https://openreview.net/forum?id=SSKZPJCt7B) | The de facto open benchmark and leaderboard for adversarial robustness in modern vision papers. |
| 19 | SEED-Bench | Multimodal | [GitHub](https://github.com/AILab-CVC/SEED-Bench) | Apache-2.0 | Generative multimodal benchmark evaluation | [Paper](https://arxiv.org/abs/2307.16125) | A widely adopted benchmark family for evaluating generative comprehension in multimodal LLMs. |
| 20 | POPE | Multimodal | [GitHub](https://github.com/RUCAIBox/POPE) | MIT (benchmark repo) | Object hallucination evaluation for LVLMs | [Paper](https://aclanthology.org/2023.emnlp-main.20/) | A standard benchmark for measuring object hallucination in large vision-language models. |

## Additional Cross-References

- [LLM-Evals overview](../LLM-Evals/README.md)
- [MMBench](https://mmbench.opencompass.org.cn/home)
- [MathVista](https://mathvista.github.io/)
- [Video-MME](https://video-mme.github.io/home_page.html)
- [BRIGHT](https://brightbenchmark.github.io/)
- [OpenOOD](https://github.com/Jingkang50/OpenOOD)
- [WILDS](https://wilds.stanford.edu/datasets/)
- [RobustBench](https://robustbench.github.io/)
- [SEED-Bench](https://github.com/AILab-CVC/SEED-Bench)
- [POPE](https://github.com/RUCAIBox/POPE)
- [CRAG](../Search-Retrieval/README.md)
- [RealMMRAg](../Search-Retrieval/README.md)
- [AfriMTEB](../Search-Retrieval/README.md)
- [HarmActionsEval](../Safety-Evals/README.md)

## Selection Note

- This page keeps cross-domain, task-family, and platform-style benchmark resources in one place.
- LLM-specific evaluation sets that now form a large standalone cluster are maintained separately in [LLM-Evals](../LLM-Evals/README.md).
