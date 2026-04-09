# 搜索与检索（Search-Retrieval）

覆盖检索、跨语言 IR、RAG grounding 以及音频文本检索的数据集与 benchmark 型资源目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | MS MARCO | English | [Site](https://microsoft.github.io/msmarco/) | Non-commercial research only / terms | 大规模网页段落与文档排序 | [Paper](https://arxiv.org/abs/1611.09268) | 现代检索训练中最核心的数据族之一。 |
| 2 | BEIR | English | [GitHub](https://github.com/beir-cellar/beir) | Apache-2.0 (code) / mixed datasets | 零样本检索评测 | [Paper](https://arxiv.org/abs/2104.08663) | 把多个公开 IR 数据集统一到一个 benchmark。 |
| 3 | MIRACL | Multilingual | [Site](https://project-miracl.github.io/) | Apache-2.0 | 多语言信息检索 | [Paper](https://aclanthology.org/2023.tacl-1.63/) | 覆盖 18 种语言的人工相关性标注。 |
| 4 | Natural Questions | English | [Site](https://ai.google.com/research/NaturalQuestions) | Unknown | 开放域 QA 的检索 grounding | [Paper](https://research.google/pubs/pub47761/) | 真实搜索查询与 Wikipedia 证据配对。 |
| 5 | MKQA | Multilingual | [GitHub](https://github.com/apple/ml-mkqa) | Unknown | 跨语言检索与问答评测 | [Paper](https://arxiv.org/abs/2007.15207) | 26 种语言对齐的问题集合。 |
| 6 | HAGRID | English | [GitHub](https://github.com/project-miracl/hagrid) | Apache-2.0 | 带引用的生成式检索 | [Paper](https://arxiv.org/abs/2307.16883) | 基于 MIRACL 构建，强调 attribution。 |
| 7 | SQuTR | English | [HF](https://huggingface.co/datasets/SLLMCommunity/SQuTR) | Unknown | 面向 LLM 的检索与问题 grounding | [Paper](https://huggingface.co/papers/2602.12783) | 来自近期 MTEB issue 的新增候选。 |
| 8 | RealMMRAg | Multimodal | [HF](https://huggingface.co/datasets/ibm-research/REAL-MM-RAG_FinReport_BEIR) | Unknown | 多模态金融报告 RAG | [Paper](https://arxiv.org/abs/2502.12342) | 适合更真实的 multimodal RAG 评测。 |
| 9 | AfriMTEB | Multilingual | [GitHub](https://github.com/masakhane-io/afrimteb) | Unknown | 非洲语言 embedding 与检索评测 | [Docs](https://github.com/masakhane-io/afrimteb) | 补足高资源语言之外的多语覆盖。 |
| 10 | Clotho | English | [Site](https://zenodo.org/records/3490684) | Mixed / source-specific + non-commercial captions | 音频文本检索与音频描述 | [Paper](https://arxiv.org/abs/1910.09387) | 与音频理解页交叉引用，适合音频搜索研究。 |
| 11 | Mr.TyDi | Multilingual | [GitHub](https://github.com/castorini/mr.tydi) | Apache-2.0 | 多语言稠密检索评测 | [Paper](https://arxiv.org/abs/2108.08787) | 覆盖多种语言与书写系统的高信号检索 benchmark。 |
| 12 | TriviaQA | English | [Site](http://nlp.cs.washington.edu/triviaqa/) | Custom / third-party copyright | 开放域问答检索 grounding | [Paper](https://aclanthology.org/P17-1147/) | 在 evidence retrieval 和 reader-retriever 流水线中仍很常见。 |
| 13 | TREC Deep Learning Track | English | [Site](https://trec.nist.gov/data/deep.html) | Unknown | 段落排序与重排序评测 | [Docs](https://trec.nist.gov/data/deep.html) | 现代 passage retrieval 论文里最常见的标准测试集之一。 |
| 14 | TREC-COVID | English | [Site](https://ir.nist.gov/covidSubmit/index.html) | Unknown | 领域检索与科学文献搜索 | [Paper](https://arxiv.org/abs/2104.09632) | 在 BEIR 风格评测和生物医学检索论文中复用率很高。 |
| 15 | LoTTE | English | [GitHub](https://github.com/stanford-futuredata/ColBERT/blob/main/LoTTE.md) | Unknown | 长文档与论坛式检索评测 | [Docs](https://github.com/stanford-futuredata/ColBERT/blob/main/LoTTE.md) | 常被用来测试更接近真实搜索和社区问答场景的检索能力。 |
| 16 | NFCorpus | English | [Site](https://www.cl.uni-heidelberg.de/statnlpgroup/nfcorpus/) | Unknown | 生物医学与消费者健康检索 | [Docs](https://www.cl.uni-heidelberg.de/statnlpgroup/nfcorpus/) | 经典 IR benchmark，在 BEIR 和 biomedical retrieval 对比里仍然高频出现。 |
| 17 | BRIGHT | English | [Site](https://brightbenchmark.github.io/) | Unknown | 强推理型检索评测 | [Paper](https://arxiv.org/abs/2407.12883) | 专门针对标准 BEIR 式检索难以覆盖的多跳和推理型失败模式。 |
| 18 | CRAG | English | [GitHub](https://github.com/facebookresearch/CRAG) | CC BY-NC 4.0 | 端到端 RAG 评测 | [Paper](https://arxiv.org/abs/2406.04744) | 加入更真实的检索、模拟网页访问和生成评估流程。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [MTEB](https://github.com/embeddings-benchmark/mteb)
- [BEIR](https://github.com/beir-cellar/beir)
- [TREC Deep Learning Track](https://trec.nist.gov/data/deep.html)
- [Audio-Understanding 总览](../Audio-Understanding/README_ZH.md)
