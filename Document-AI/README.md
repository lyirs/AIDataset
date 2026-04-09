# Document-AI

OCR, layout parsing, receipt understanding, chart reasoning, and document question answering datasets.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | RVL-CDIP | English | [Site](https://adamharley.com/rvl-cdip/) | Unknown | Document classification and layout baselines | [Docs](https://adamharley.com/rvl-cdip/) | Canonical scanned-document classification dataset. |
| 2 | FUNSD | English | [Site](https://guillaumejaume.github.io/FUNSD/) | Unknown | Form understanding and key-value extraction | [Paper](https://aclanthology.org/2020.findings-emnlp.48/) | Small but standard benchmark for form parsing. |
| 3 | XFUND | Multilingual | [GitHub](https://github.com/doc-analysis/XFUND) | CC BY-NC-SA 4.0 | Multilingual form understanding | [Paper](https://aclanthology.org/2022.findings-acl.253/) | Extends FUNSD-style parsing across several languages. |
| 4 | DocVQA | Multilingual | [Site](https://www.docvqa.org/) | Custom / challenge terms | Document visual question answering | [Docs](https://www.docvqa.org/datasets) | Main challenge hub for DocVQA and related document QA tracks. |
| 5 | PubLayNet | English | [GitHub](https://github.com/ibm-aur-nlp/PubLayNet) | Unknown | Layout detection and page element segmentation | [Paper](https://arxiv.org/abs/1908.07836) | One of the most common large-scale PDF layout corpora. |
| 6 | DocBank | English | [GitHub](https://github.com/doc-analysis/DocBank) | Apache-2.0 | Token-level document layout labeling | [Paper](https://aclanthology.org/2020.coling-main.82/) | Useful when structure needs to be modeled at token granularity. |
| 7 | CORD | English | [GitHub](https://github.com/clovaai/cord) | CC-BY-4.0 | Receipt understanding and information extraction | [Docs](https://github.com/clovaai/cord) | High-signal receipt benchmark from the OCR/document parsing community. |
| 8 | SROIE | English | [Site](https://rrc.cvc.uab.es/?ch=13) | Custom / challenge terms | Receipt OCR and key information extraction | [Docs](https://rrc.cvc.uab.es/?ch=13) | Long-running receipt understanding challenge used in many OCR pipelines. |
| 9 | ChartQA | English | [GitHub](https://github.com/vis-nlp/ChartQA) | GPL-3.0 | Chart reasoning and chart question answering | [Paper](https://arxiv.org/abs/2203.10244) | Strong chart understanding benchmark for multimodal document reasoning. |
| 10 | OCR-VQA | English | [Site](https://ocr-vqa.github.io/) | Unknown | OCR-grounded visual question answering | [Paper](https://arxiv.org/abs/1909.09482) | Bridges OCR extraction and question answering over text-rich images. |
| 11 | DocLayNet | Multilingual documents | [GitHub](https://github.com/DS4SD/DocLayNet) | Unknown | Human-annotated document layout analysis | [Paper](https://arxiv.org/abs/2206.01062) | Broader layout diversity than scientific-paper-only corpora. |
| 12 | InfographicVQA | English | [Site](https://www.docvqa.org/datasets/infographicvqa) | Custom / challenge terms | Infographic question answering | [Docs](https://www.docvqa.org/datasets/infographicvqa) | Adds OCR, layout, and visual reasoning beyond receipts and forms. |
| 13 | PubTabNet | English | [GitHub](https://github.com/ibm-aur-nlp/PubTabNet) | Unknown | Table structure recognition | [Paper](https://arxiv.org/abs/1911.10683) | One of the most widely used table recognition datasets in document AI papers. |
| 14 | TableBank | English | [GitHub](https://github.com/doc-analysis/TableBank) | Unknown | Table detection and table recognition | [Paper](https://arxiv.org/abs/1903.01949) | A standard large-scale benchmark for table extraction from Word and LaTeX documents. |
| 15 | PubTables-1M | English | [GitHub](https://github.com/microsoft/table-transformer) | Unknown | Table extraction and structure parsing | [Paper](https://arxiv.org/abs/2110.00061) | A canonical modern benchmark behind many table transformer baselines. |
| 16 | Marmot | Multilingual documents | [Site](https://www.icst.pku.edu.cn/szwdclyjs/sjzy/index.htm) | Research-only / non-commercial | Table detection and layout analysis | [Docs](https://www.icst.pku.edu.cn/szwdclyjs/sjzy/index.htm) | A long-running benchmark for document layout and table detection evaluations. |
| 17 | MP-DocVQA | Multilingual documents | [Site](https://www.docvqa.org/) | Custom / challenge terms | Multi-page document question answering | [Paper](https://arxiv.org/abs/2212.05935) | The multi-page DocVQA track has become the stronger default successor to single-page document QA. |
| 18 | DocILE | Business documents | [Site](https://docile.rossum.ai/) | Custom / access-controlled terms | Business document information extraction | [Paper](https://arxiv.org/abs/2302.05658) | High-signal benchmark for invoices, orders, and line-item extraction. |
| 19 | OmniDocBench | Multilingual documents | [GitHub](https://github.com/opendatalab/OmniDocBench) | Unknown | PDF parsing and end-to-end document understanding | [Paper](https://arxiv.org/abs/2412.07626) | A strong 2025-era benchmark for modern document foundation models. |
| 20 | OCRBench v2 | Bilingual | [Site](https://99franklin.github.io/ocrbench_v2/) | Unknown | OCR-centric multimodal evaluation | [Paper](https://arxiv.org/abs/2501.00321) | A newer large bilingual benchmark for text localization, recognition, and reasoning. |
| 21 | SlideVQA | English | [GitHub](https://github.com/nttmdlab-nlp/SlideVQA) | Evaluation license | Multi-image document visual question answering | [Paper](https://arxiv.org/abs/2301.04883) | A high-signal benchmark for reasoning across slide decks rather than single-page documents. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [DocVQA](https://www.docvqa.org/)
- [InfographicVQA](https://www.docvqa.org/datasets/infographicvqa)
- [ICDAR Robust Reading Competitions](https://rrc.cvc.uab.es/)
- [PubTables-1M / Table Transformer](https://github.com/microsoft/table-transformer)
- [OCRBench v2](https://99franklin.github.io/ocrbench_v2/)
- [MMMU](https://mmmu-benchmark.github.io/)

## Selection Note

- This page prioritizes datasets that remain common in document parsing, OCR, and document QA papers.
- Challenge portals are included when they are the official distribution point for the dataset.
