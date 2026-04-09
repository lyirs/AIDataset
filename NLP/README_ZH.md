# 自然语言处理（NLP）

覆盖经典与现代文本任务的数据集目录，包括命名实体识别、问答、摘要、推理、文本分类与多语评测。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | CoNLL-2003 | English | [HF](https://huggingface.co/datasets/eriktks/conll2003) | Unknown | 命名实体识别与序列标注 | [Paper](https://aclanthology.org/W03-0419/) | 经典新闻领域 NER 基准。 |
| 2 | Universal Dependencies | Multilingual | [Site](https://universaldependencies.org/) | Mixed / treebank-specific | 依存句法分析与多语语法研究 | [Docs](https://universaldependencies.org/) | 来自高星目录仓库 issue 的高价值补充。 |
| 3 | SQuAD 2.0 | English | [Site](https://rajpurkar.github.io/SQuAD-explorer/) | CC BY-SA 4.0 | 含不可回答样本的抽取式问答 | [Paper](https://arxiv.org/abs/1806.03822) | 最常用的阅读理解数据之一。 |
| 4 | XNLI | Multilingual | [HF](https://huggingface.co/datasets/facebook/xnli) | Unknown | 跨语言自然语言推断 | [Paper](https://aclanthology.org/D18-1269/) | 覆盖 15 种语言。 |
| 5 | WikiANN | Multilingual | [HF](https://huggingface.co/datasets/unimelb-nlp/wikiann) | CC BY-SA 3.0 | 多语言命名实体识别 | [Docs](https://huggingface.co/datasets/unimelb-nlp/wikiann) | 基于 Wikipedia 自动构建。 |
| 6 | PAWS-X | Multilingual | [HF](https://huggingface.co/datasets/google-research-datasets/paws-x) | Unknown | 释义识别与句对匹配 | [Paper](https://arxiv.org/abs/1908.11828) | 高词面重叠的困难句对。 |
| 7 | CMRC 2018 | Chinese | [GitHub](https://github.com/ymcui/cmrc2018) | Unknown | 中文抽取式阅读理解 | [Paper](https://aclanthology.org/D19-1600/) | 常用中文 MRC 基线数据集。 |
| 8 | DuReader | Chinese | [GitHub](https://github.com/baidu/DuReader) | Apache-2.0 | 开放域问答与阅读理解 | [Paper](https://arxiv.org/abs/1711.05073) | 来自真实百度搜索问题。 |
| 9 | THUCNews | Chinese | [GitHub](https://github.com/thunlp/THUCNews) | Unknown | 中文主题分类 | [Docs](https://github.com/thunlp/THUCNews) | 适合快速训练中文分类模型。 |
| 10 | FewCLUE | Chinese | [GitHub](https://github.com/CLUEbenchmark/FewCLUE) | Unknown | 中文小样本 NLP 任务 | [Paper](https://arxiv.org/abs/2107.07498) | 适合提示学习与少样本微调。 |
| 11 | TyDi QA | Multilingual | [GitHub](https://github.com/google-research-datasets/tydiqa) | Unknown | 多语言信息型问答 | [Paper](https://arxiv.org/abs/2003.05002) | 语言类型覆盖很广。 |
| 12 | TREC-6 | English | [HF](https://huggingface.co/datasets/CogComp/trec) | Unknown | 问句分类 | [Docs](https://huggingface.co/datasets/CogComp/trec) | 在 dataset-request issue 中反复被提到。 |
| 13 | Yelp Review Full | English | [HF](https://huggingface.co/datasets/Yelp/yelp_review_full) | Unknown | 评论情感与文档分类 | [Docs](https://huggingface.co/datasets/Yelp/yelp_review_full) | 常见的大规模文本分类语料。 |
| 14 | MPQA | English | [Site](https://mpqa.cs.pitt.edu/) | Custom / registration | 观点挖掘与主观性分析 | [Docs](https://mpqa.cs.pitt.edu/) | 经典情感和主观性标注资源。 |
| 15 | Amazon Reviews Multi | Multilingual | [HF](https://huggingface.co/datasets/amazon_reviews_multi) | Unknown | 多语言商品评论分类 | [Docs](https://huggingface.co/datasets/amazon_reviews_multi) | 实用的跨语言评论数据。 |
| 16 | SNLI | English | [Site](https://nlp.stanford.edu/projects/snli/) | CC BY-SA 4.0 | 自然语言推断 | [Docs](https://nlp.stanford.edu/projects/snli/) | 迁移学习论文里最常见的 entailment 锚点之一。 |
| 17 | MultiNLI | English | [Site](https://cims.nyu.edu/~sbowman/multinli/) | Unknown | 多体裁自然语言推断 | [Paper](https://aclanthology.org/N18-1101/) | 把 NLI 从图像描述文本扩展到多种真实体裁。 |
| 18 | ANLI | English | [GitHub](https://github.com/facebookresearch/anli) | Other / custom | 对抗式鲁棒性自然语言推断 | [Paper](https://aclanthology.org/2020.acl-main.441/) | 通过 human-and-model-in-the-loop 方式构造，难度高于常规 NLI。 |
| 19 | HotpotQA | English | [Site](https://hotpotqa.github.io/) | CC BY-SA 4.0 | 多跳问答 | [Paper](https://aclanthology.org/D18-1259/) | 提供 supporting facts 监督，适合可解释推理。 |
| 20 | FEVER | English | [Site](https://fever.ai/dataset/fever.html) | Wikipedia terms / CC BY-SA 3.0 | 带证据检索的事实核验 | [Docs](https://fever.ai/dataset/fever.html) | 围绕证据选择与真假判断的经典 fact-checking 基准。 |
| 21 | Natural Questions | English | [Site](https://ai.google.com/research/NaturalQuestions) | Unknown | 开放域问答与长答案检索 | [Docs](https://ai.google.com/research/NaturalQuestions/download) | 来自真实 Google 查询，至今仍是 QA 论文常用锚点。 |
| 22 | CNN/DailyMail | English | [HF](https://huggingface.co/datasets/ccdv/cnn_dailymail) | Unknown | 新闻摘要基线 | [Docs](https://huggingface.co/datasets/ccdv/cnn_dailymail) | 抽象式摘要对比里几乎默认会出现的参考数据集。 |
| 23 | XSum | English | [GitHub](https://github.com/EdinburghNLP/XSum) | Unknown | 极短摘要生成 | [Paper](https://aclanthology.org/D18-1206/) | ACL 系摘要评测中非常常见的单句新闻摘要基准。 |
| 24 | BoolQ | English | [GitHub](https://github.com/google-research-datasets/boolean-questions) | CC BY-SA 3.0 | 是非问答 | [Paper](https://aclanthology.org/N19-1300/) | 来自自然搜索问题的 yes/no QA 基准，也常出现在 SuperGLUE 风格对比里。 |
| 25 | GSM8K | English | [GitHub](https://github.com/openai/grade-school-math) | Unknown | 数学文字推理 | [Paper](https://arxiv.org/abs/2110.14168) | 现代 LLM 与 NLP 推理评测表里最常见的数据集之一。 |
| 26 | WikiText-103 | English | [HF](https://huggingface.co/datasets/Salesforce/wikitext) | CC BY-SA 4.0 | 语言模型与长上下文预训练 | [Paper](https://arxiv.org/abs/1609.07843) | 语言模型 perplexity 和预训练比较中长期高频出现。 |
| 27 | WMT14 Translation Task | Multilingual | [Site](https://statmt.org/wmt14/translation-task.html) | Mixed / source-specific | 机器翻译 benchmark | [Docs](https://statmt.org/wmt14/) | 尤其是英德翻译设置，至今仍是 MT 论文里的默认参考点之一。 |
| 28 | BIRD | English / SQL | [Site](https://bird-bench.github.io/) | Unknown | Text-to-SQL 与数据库问答生成 | [Paper](https://arxiv.org/abs/2305.03111) | 现代 text-to-SQL 和数据库 agent 查询论文里最核心的 benchmark 家族之一。 |
| 29 | Belebele | Multilingual | [HF](https://huggingface.co/datasets/facebook/belebele) | CC BY-SA 4.0 | 大规模多语言阅读理解 | [Paper](https://arxiv.org/abs/2308.16884) | 覆盖 100 多种语言变体，是近年多语言阅读理解里信号很强的 benchmark。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [GLUE](https://gluebenchmark.com/)
- [SuperGLUE](https://super.gluebenchmark.com/)
- [XTREME](https://github.com/google-research/xtreme)
- [WMT](https://www.statmt.org/wmt24/)
- [CLUE](https://github.com/CLUEbenchmark/CLUE)
- [FewCLUE](https://github.com/CLUEbenchmark/FewCLUE)
- [BIRD](https://bird-bench.github.io/)
- [Belebele](https://huggingface.co/datasets/facebook/belebele)

## 收录说明

- 本页优先覆盖那些在 ACL、EMNLP、NAACL 论文、教程和强基线比较里持续高频出现的数据集。
- 如果缺少某个 canonical 的 NLI、QA、摘要或事实核验数据集，应视为后续整理需要优先补齐的缺口。
