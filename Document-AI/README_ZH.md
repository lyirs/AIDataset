# 文档 AI（Document-AI）

覆盖 OCR、版面解析、票据理解、图表推理与文档问答的数据目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | RVL-CDIP | English | [Site](https://adamharley.com/rvl-cdip/) | Unknown | 文档分类与版面基线 | [Docs](https://adamharley.com/rvl-cdip/) | 最经典的扫描文档分类数据集之一。 |
| 2 | FUNSD | English | [Site](https://guillaumejaume.github.io/FUNSD/) | Unknown | 表单理解与键值抽取 | [Paper](https://aclanthology.org/2020.findings-emnlp.48/) | 虽然规模不大，但仍是表单解析标准基准。 |
| 3 | XFUND | Multilingual | [GitHub](https://github.com/doc-analysis/XFUND) | CC BY-NC-SA 4.0 | 多语言表单理解 | [Paper](https://aclanthology.org/2022.findings-acl.253/) | 将 FUNSD 风格任务扩展到了多种语言。 |
| 4 | DocVQA | Multilingual | [Site](https://www.docvqa.org/) | Custom / challenge terms | 文档视觉问答 | [Docs](https://www.docvqa.org/datasets) | DocVQA 及相关文档问答赛道的官方入口。 |
| 5 | PubLayNet | English | [GitHub](https://github.com/ibm-aur-nlp/PubLayNet) | Unknown | 版面检测与页面元素分割 | [Paper](https://arxiv.org/abs/1908.07836) | PDF 版面分析里最常见的大规模语料之一。 |
| 6 | DocBank | English | [GitHub](https://github.com/doc-analysis/DocBank) | Apache-2.0 | Token 级文档结构标注 | [Paper](https://aclanthology.org/2020.coling-main.82/) | 适合需要细粒度结构建模的文档任务。 |
| 7 | CORD | English | [GitHub](https://github.com/clovaai/cord) | CC-BY-4.0 | 收据理解与信息抽取 | [Docs](https://github.com/clovaai/cord) | OCR 与文档解析论文里高频出现的 receipt benchmark。 |
| 8 | SROIE | English | [Site](https://rrc.cvc.uab.es/?ch=13) | Custom / challenge terms | 收据 OCR 与关键信息抽取 | [Docs](https://rrc.cvc.uab.es/?ch=13) | 长期使用的收据理解挑战赛数据入口。 |
| 9 | ChartQA | English | [GitHub](https://github.com/vis-nlp/ChartQA) | GPL-3.0 | 图表推理与图表问答 | [Paper](https://arxiv.org/abs/2203.10244) | 文档图表理解和多模态推理里的高信号数据集。 |
| 10 | OCR-VQA | English | [Site](https://ocr-vqa.github.io/) | Unknown | OCR 感知问答 | [Paper](https://arxiv.org/abs/1909.09482) | 连接 OCR 提取与文本富图像问答的经典桥接数据集。 |
| 11 | DocLayNet | Multilingual documents | [GitHub](https://github.com/DS4SD/DocLayNet) | Unknown | 人工标注文档版面分析 | [Paper](https://arxiv.org/abs/2206.01062) | 文档版面和样式多样性明显强于纯论文类数据。 |
| 12 | InfographicVQA | English | [Site](https://www.docvqa.org/datasets/infographicvqa) | Custom / challenge terms | 信息图问答 | [Docs](https://www.docvqa.org/datasets/infographicvqa) | 在票据和表单之外补齐 OCR、版面与视觉推理。 |
| 13 | PubTabNet | English | [GitHub](https://github.com/ibm-aur-nlp/PubTabNet) | Unknown | 表格结构识别 | [Paper](https://arxiv.org/abs/1911.10683) | 文档 AI 论文里最常用的表格识别数据集之一。 |
| 14 | TableBank | English | [GitHub](https://github.com/doc-analysis/TableBank) | Unknown | 表格检测与表格识别 | [Paper](https://arxiv.org/abs/1903.01949) | 从 Word 和 LaTeX 文档构建的大规模经典表格提取 benchmark。 |
| 15 | PubTables-1M | English | [GitHub](https://github.com/microsoft/table-transformer) | Unknown | 表格抽取与结构解析 | [Paper](https://arxiv.org/abs/2110.00061) | 现代 table transformer 和表格抽取论文中的核心 benchmark 之一。 |
| 16 | Marmot | Multilingual documents | [Site](https://www.icst.pku.edu.cn/szwdclyjs/sjzy/index.htm) | Research-only / non-commercial | 表格检测与版面分析 | [Docs](https://www.icst.pku.edu.cn/szwdclyjs/sjzy/index.htm) | 文档版面和表格检测评测里长期被引用的经典数据集。 |
| 17 | MP-DocVQA | Multilingual documents | [Site](https://www.docvqa.org/) | Custom / challenge terms | 多页文档问答 | [Paper](https://arxiv.org/abs/2212.05935) | 多页 DocVQA 赛道已经成为单页文档问答之后更常见的进阶 benchmark。 |
| 18 | DocILE | Business documents | [Site](https://docile.rossum.ai/) | Custom / access-controlled terms | 商业文档信息抽取 | [Paper](https://arxiv.org/abs/2302.05658) | 发票、订单和 line-item 抽取方向里信号很强的 benchmark。 |
| 19 | OmniDocBench | Multilingual documents | [GitHub](https://github.com/opendatalab/OmniDocBench) | Unknown | PDF 解析与端到端文档理解 | [Paper](https://arxiv.org/abs/2412.07626) | 2025 年后文档基础模型评测里非常值得保留的一类新 benchmark。 |
| 20 | OCRBench v2 | Bilingual | [Site](https://99franklin.github.io/ocrbench_v2/) | Unknown | OCR 导向的多模态评测 | [Paper](https://arxiv.org/abs/2501.00321) | 覆盖文本定位、识别和推理的新一代大规模双语 benchmark。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [DocVQA](https://www.docvqa.org/)
- [InfographicVQA](https://www.docvqa.org/datasets/infographicvqa)
- [ICDAR Robust Reading Competitions](https://rrc.cvc.uab.es/)
- [PubTables-1M / Table Transformer](https://github.com/microsoft/table-transformer)
- [OCRBench v2](https://99franklin.github.io/ocrbench_v2/)
- [MMMU](https://mmmu-benchmark.github.io/)

## 收录说明

- 本页优先覆盖在文档解析、OCR 与文档问答论文中长期高频出现的数据集。
- 如果官方数据通过 challenge portal 分发，这类 portal 会被视为正式主入口。
