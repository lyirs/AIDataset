# 金融与法律（Finance-Legal）

覆盖金融、监管与法律领域推理、抽取、分类和合规流程的数据目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | SEC EDGAR | English | [Site](https://www.sec.gov/os/accessing-edgar-data) | Unknown | 财报检索与披露文本建模 | [Docs](https://www.sec.gov/os/accessing-edgar-data) | 美国上市公司 filings 与披露文本的官方公共入口。 |
| 2 | SEC Financial Statement and Notes Data Sets | English / structured financial tables | [Site](https://www.sec.gov/data-research/sec-markets-data/financial-statement-notes-data-sets) | Unknown | 结构化财务报表抽取 | [Docs](https://www.sec.gov/data-research/sec-markets-data/financial-statement-notes-data-sets) | 基于 XBRL 的财务报表和附注数据，适合表格推理与金融 NLP。 |
| 3 | CFPB Consumer Complaint Database | English | [Site](https://www.consumerfinance.gov/data-research/consumer-complaints/) | Unknown | 消费金融投诉分析 | [Docs](https://www.consumerfinance.gov/data-research/consumer-complaints/) | 来自美国监管机构的真实投诉文本及产品、公司元数据。 |
| 4 | FinQA | English | [Site](https://finqasite.github.io/) | CC BY 4.0 | 金融数值推理 | [Docs](https://github.com/czyssrs/FinQA) | 面向财报、表格与金融叙述联合推理的高信号 benchmark。 |
| 5 | CUAD | English | [Site](https://www.atticusprojectai.org/cuad/) | CC BY 4.0 | 合同问答与条款抽取 | [Docs](https://www.atticusprojectai.org/cuad/) | 法律合同审阅里最常见的数据集之一。 |
| 6 | ContractNLI | English | [Site](https://stanfordnlp.github.io/contract-nli/) | CC BY 4.0 | 合同蕴含与文档级 NLI | [Paper](https://arxiv.org/abs/2110.01799) | 基于真实合同的强 document-level NLI benchmark。 |
| 7 | LexGLUE | English | [GitHub](https://github.com/coastalcph/lex-glue) | Unknown | 法律 NLP 多任务评测 | [Docs](https://github.com/coastalcph/lex-glue) | 法律分类与理解任务中使用频率很高的一套 benchmark。 |
| 8 | CaseHOLD | English | [GitHub](https://github.com/reglab/casehold) | Apache-2.0 | 法律观点预测与引文推理 | [Docs](https://github.com/reglab/casehold) | 美国法律判例推理方向的高信号 benchmark。 |
| 9 | Caselaw Access Project | English | [Site](https://case.law/) | Unknown | 判例检索与法律语料预训练 | [Docs](https://case.law/) | 美国 case law 的重要公共档案资源，常用于 legal IR 和 legal NLP。 |
| 10 | EUR-Lex | Multilingual | [Site](https://eur-lex.europa.eu/) | Unknown | 多语言法规检索与分类 | [Docs](https://eur-lex.europa.eu/) | 欧盟法规与多语言法律文本最 canonical 的公共来源。 |
| 11 | TAT-QA | English | [GitHub](https://github.com/NExTplusplus/TAT-QA) | MIT | 金融表格文本问答与算术推理 | [Paper](https://aclanthology.org/2021.acl-long.254/) | 是 FinQA 之外最常见的金融表格与叙述联合推理 benchmark 之一。 |
| 12 | MultiEURLEX | 23 EU languages | [GitHub](https://github.com/nlpaueb/multi-eurlex) | Unknown | 多语言法律文档分类 | [Paper](https://aclanthology.org/2021.emnlp-main.559/) | 相比原始 EUR-Lex 门户，它提供了可直接复用的多语多标签法律分类划分。 |
| 13 | MAUD | English | [Site](https://www.atticusprojectai.org/maud) | CC BY 4.0 | 并购协议理解与法律问答 | [Paper](https://arxiv.org/abs/2301.00876) | 这是并购合同阅读、尽调和条款理解里很高信号的专家标注数据集。 |
| 14 | LegalBench | English | [GitHub](https://github.com/HazyResearch/legalbench) | Mixed / task-specific | 广谱法律推理评测 | [Paper](https://arxiv.org/abs/2209.06120) | 当前最有代表性的开放法律推理 benchmark suite 之一，覆盖多种法律任务。 |
| 15 | ConvFinQA | English | [GitHub](https://github.com/czyssrs/ConvFinQA) | MIT | 对话式金融问答与数值推理 | [Paper](https://arxiv.org/abs/2210.03849) | 它把 FinQA 扩展到了多轮问答场景，已经是金融 LLM 评测里很常见的基准。 |
| 16 | FinanceBench | English | [GitHub](https://github.com/patronus-ai/financebench) | Unknown | 基于真实 SEC 文件的金融问答 | [Paper](https://arxiv.org/abs/2311.11944) | 这是当前最有代表性的企业级金融问答 benchmark 之一，直接基于真实披露文件构建。 |
| 17 | FiQA | English | [Site](https://sites.google.com/view/fiqa/home) | Non-commercial use only | 金融情感分析与观点问答 | [Docs](https://sites.google.com/view/fiqa/home) | 它同时覆盖金融细粒度情感分析和 opinion-based QA，是早期但仍常被引用的金融任务资源。 |
| 18 | LEDGAR | English | [GitHub](https://github.com/dtuggener/LEDGAR_provision_classification) | Unknown | 合同条款分类 | [Paper](https://aclanthology.org/2020.lrec-1.155/) | 它是法律 NLP 中最常见的大规模合同条款分类数据集之一。 |
| 19 | Pile of Law | English legal text | [GitHub](https://github.com/Breakend/PileOfLaw) | Mixed / source-specific | 法律语料预训练与语料挖掘 | [Paper](https://arxiv.org/abs/2207.00220) | 这是法律语言模型和法律检索工作里非常高频的大规模法律语料。 |
| 20 | ECtHR Cases | English | [HF](https://huggingface.co/datasets/AUEB-NLP/ecthr_cases) | CC BY-NC-SA 4.0 | 法律裁判预测与依据抽取 | [Paper](https://arxiv.org/abs/2103.13084) | 它是欧洲人权法院案件预测与 rationale extraction 方向最经典的数据集之一。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [Search-Retrieval 总览](../Search-Retrieval/README_ZH.md)
- [LexGLUE](https://github.com/coastalcph/lex-glue)
- [LegalBench](https://github.com/HazyResearch/legalbench)
- [MAUD](https://www.atticusprojectai.org/maud)
- [FinanceBench](https://github.com/patronus-ai/financebench)

## 收录说明

- 本页会同时收录原始数据集与官方监管/法律文本门户，因为这些门户本身往往就是该领域最权威的公共数据来源。
- 金融和法律资源经常混合 narrative text、表格、元数据与专业访问条款，因此许可字段在不明确时会保持保守写法。
