# Search-Retrieval

Dense retrieval, multilingual IR, RAG grounding, and audio-text retrieval datasets and benchmark-style resources.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | MS MARCO | English | [Site](https://microsoft.github.io/msmarco/) | Non-commercial research only / terms | Web-scale passage and document ranking | [Paper](https://arxiv.org/abs/1611.09268) | A core dataset family for modern retrieval training. |
| 2 | BEIR | English | [GitHub](https://github.com/beir-cellar/beir) | Apache-2.0 (code) / mixed datasets | Zero-shot retrieval benchmarking | [Paper](https://arxiv.org/abs/2104.08663) | Unifies many public IR datasets under one benchmark. |
| 3 | MIRACL | Multilingual | [Site](https://project-miracl.github.io/) | Apache-2.0 | Multilingual information retrieval | [Paper](https://aclanthology.org/2023.tacl-1.63/) | Human relevance judgments across 18 languages. |
| 4 | Natural Questions | English | [Site](https://ai.google.com/research/NaturalQuestions) | Unknown | Open-domain QA retrieval grounding | [Paper](https://research.google/pubs/pub47761/) | Real search queries tied to Wikipedia evidence. |
| 5 | MKQA | Multilingual | [GitHub](https://github.com/apple/ml-mkqa) | Unknown | Cross-lingual retrieval and QA evaluation | [Paper](https://arxiv.org/abs/2007.15207) | Aligned questions across 26 languages. |
| 6 | HAGRID | English | [GitHub](https://github.com/project-miracl/hagrid) | Apache-2.0 | Generative retrieval with attribution | [Paper](https://arxiv.org/abs/2307.16883) | Built on top of MIRACL for attribution-aware search. |
| 7 | SQuTR | English | [HF](https://huggingface.co/datasets/SLLMCommunity/SQuTR) | Unknown | LLM-oriented retrieval and question grounding | [Paper](https://huggingface.co/papers/2602.12783) | Added after recent MTEB issue discussion. |
| 8 | RealMMRAg | Multimodal | [HF](https://huggingface.co/datasets/ibm-research/REAL-MM-RAG_FinReport_BEIR) | Unknown | Multimodal RAG on financial reports | [Paper](https://arxiv.org/abs/2502.12342) | High-signal addition for realistic multimodal RAG evaluation. |
| 9 | AfriMTEB | Multilingual | [GitHub](https://github.com/masakhane-io/afrimteb) | Unknown | African-language embedding and retrieval evaluation | [Docs](https://github.com/masakhane-io/afrimteb) | Useful for broader multilingual coverage beyond high-resource languages. |
| 10 | Clotho | English | [Site](https://zenodo.org/records/3490684) | Mixed / source-specific + non-commercial captions | Audio-text retrieval and captioning | [Paper](https://arxiv.org/abs/1910.09387) | Cross-listed with audio understanding because audio search is becoming more relevant. |
| 11 | Mr.TyDi | Multilingual | [GitHub](https://github.com/castorini/mr.tydi) | Apache-2.0 | Multilingual dense retrieval benchmarking | [Paper](https://arxiv.org/abs/2108.08787) | A strong multilingual retrieval benchmark spanning diverse languages and scripts. |
| 12 | TriviaQA | English | [Site](http://nlp.cs.washington.edu/triviaqa/) | Custom / third-party copyright | Open-domain QA retrieval grounding | [Paper](https://aclanthology.org/P17-1147/) | Still widely used for evidence retrieval and reader-retriever pipelines. |
| 13 | TREC Deep Learning Track | English | [Site](https://trec.nist.gov/data/deep.html) | Unknown | Passage ranking and reranking evaluation | [Docs](https://trec.nist.gov/data/deep.html) | One of the most standard leaderboard-style test sets for modern passage retrieval. |
| 14 | TREC-COVID | English | [Site](https://ir.nist.gov/covidSubmit/index.html) | Unknown | Domain-specific IR and scientific search | [Paper](https://arxiv.org/abs/2104.09632) | A canonical biomedical retrieval benchmark reused throughout BEIR-style evaluations. |
| 15 | LoTTE | English | [GitHub](https://github.com/stanford-futuredata/ColBERT/blob/main/LoTTE.md) | Unknown | Long-form and conversational retrieval evaluation | [Docs](https://github.com/stanford-futuredata/ColBERT/blob/main/LoTTE.md) | Widely used to test retrieval under realistic search and forum-style queries. |
| 16 | NFCorpus | English | [Site](https://www.cl.uni-heidelberg.de/statnlpgroup/nfcorpus/) | Unknown | Biomedical and consumer-health retrieval | [Docs](https://www.cl.uni-heidelberg.de/statnlpgroup/nfcorpus/) | A classic IR benchmark that still appears in BEIR and biomedical retrieval comparisons. |
| 17 | BRIGHT | English | [Site](https://brightbenchmark.github.io/) | Unknown | Reasoning-intensive retrieval evaluation | [Paper](https://arxiv.org/abs/2407.12883) | Targets harder multi-hop and reasoning-heavy retrieval failures than standard BEIR-style suites. |
| 18 | CRAG | English | [GitHub](https://github.com/facebookresearch/CRAG) | CC BY-NC 4.0 | End-to-end RAG benchmarking | [Paper](https://arxiv.org/abs/2406.04744) | Adds realistic retrieval, mock web access, and generation evaluation for RAG systems. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [MTEB](https://github.com/embeddings-benchmark/mteb)
- [BEIR](https://github.com/beir-cellar/beir)
- [TREC Deep Learning Track](https://trec.nist.gov/data/deep.html)
- [Audio-Understanding overview](../Audio-Understanding/README.md)
