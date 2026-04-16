# Finance-Legal

Financial, regulatory, and legal-domain datasets for reasoning, extraction, classification, and compliance workflows.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | SEC EDGAR | English | [Site](https://www.sec.gov/os/accessing-edgar-data) | Unknown | Filing retrieval and disclosure modeling | [Docs](https://www.sec.gov/os/accessing-edgar-data) | The canonical public source for U.S. company filings and disclosure text. |
| 2 | SEC Financial Statement and Notes Data Sets | English / structured financial tables | [Site](https://www.sec.gov/data-research/sec-markets-data/financial-statement-notes-data-sets) | Unknown | Structured financial statement extraction | [Docs](https://www.sec.gov/data-research/sec-markets-data/financial-statement-notes-data-sets) | XBRL-derived statement data useful for financial reasoning and tabular NLP. |
| 3 | CFPB Consumer Complaint Database | English | [Site](https://www.consumerfinance.gov/data-research/consumer-complaints/) | Unknown | Consumer finance complaint analysis | [Docs](https://www.consumerfinance.gov/data-research/consumer-complaints/) | Real complaints with product, issue, and company metadata from a U.S. regulator. |
| 4 | FinQA | English | [Site](https://finqasite.github.io/) | CC BY 4.0 | Financial numerical reasoning | [Docs](https://github.com/czyssrs/FinQA) | A high-signal benchmark for reasoning over reports, tables, and financial narratives. |
| 5 | CUAD | English | [Site](https://www.atticusprojectai.org/cuad/) | CC BY 4.0 | Contract QA and clause extraction | [Docs](https://www.atticusprojectai.org/cuad/) | One of the most common contract-review datasets in legal NLP. |
| 6 | ContractNLI | English | [Site](https://stanfordnlp.github.io/contract-nli/) | CC BY 4.0 | Contract entailment and document NLI | [Paper](https://arxiv.org/abs/2110.01799) | A strong document-level NLI benchmark grounded in real contracts. |
| 7 | LexGLUE | English | [GitHub](https://github.com/coastalcph/lex-glue) | Unknown | Legal NLP multitask benchmarking | [Docs](https://github.com/coastalcph/lex-glue) | A widely used suite covering legal classification and understanding tasks. |
| 8 | CaseHOLD | English | [GitHub](https://github.com/reglab/casehold) | Apache-2.0 | Legal holding prediction and citation reasoning | [Docs](https://github.com/reglab/casehold) | High-signal benchmark for reasoning over U.S. legal opinions. |
| 9 | Caselaw Access Project | English | [Site](https://case.law/) | Unknown | Case-law retrieval and legal corpus pretraining | [Docs](https://case.law/) | A major public archive of U.S. case law used across legal IR and NLP work. |
| 10 | EUR-Lex | Multilingual | [Site](https://eur-lex.europa.eu/) | Unknown | Multilingual legislation retrieval and classification | [Docs](https://eur-lex.europa.eu/) | The canonical public source for EU legislation and multilingual legal text. |
| 11 | TAT-QA | English | [GitHub](https://github.com/NExTplusplus/TAT-QA) | MIT | Financial table-text QA with arithmetic reasoning | [Paper](https://aclanthology.org/2021.acl-long.254/) | A strong complement to FinQA for financial reasoning over tables and narratives. |
| 12 | MultiEURLEX | 23 EU languages | [GitHub](https://github.com/nlpaueb/multi-eurlex) | Unknown | Multilingual legal document classification | [Paper](https://aclanthology.org/2021.emnlp-main.559/) | Provides reusable multilingual legal classification splits beyond the raw EUR-Lex portal. |
| 13 | MAUD | English | [Site](https://www.atticusprojectai.org/maud) | CC BY 4.0 | Merger agreement understanding and legal QA | [Paper](https://arxiv.org/abs/2301.00876) | A high-signal expert-annotated dataset for M&A contract reading and due-diligence style reasoning. |
| 14 | LegalBench | English | [GitHub](https://github.com/HazyResearch/legalbench) | Mixed / task-specific | Broad legal reasoning benchmarking | [Paper](https://arxiv.org/abs/2209.06120) | The most visible open benchmark suite for diverse legal reasoning tasks with LLMs. |
| 15 | ConvFinQA | English | [GitHub](https://github.com/czyssrs/ConvFinQA) | MIT | Conversational financial QA with numerical reasoning | [Paper](https://arxiv.org/abs/2210.03849) | Extends FinQA into multi-turn settings and is now common in finance LLM evaluation tables. |
| 16 | FinanceBench | English | [GitHub](https://github.com/patronus-ai/financebench) | Unknown | Financial QA over real SEC filings | [Paper](https://arxiv.org/abs/2311.11944) | A high-signal benchmark for enterprise-style financial question answering over filings. |
| 17 | FiQA | English | [Site](https://sites.google.com/view/fiqa/home) | Non-commercial use only | Financial sentiment and opinion QA | [Docs](https://sites.google.com/view/fiqa/home) | Covers both aspect-level sentiment analysis and opinion-oriented question answering in finance. |
| 18 | LEDGAR | English | [GitHub](https://github.com/dtuggener/LEDGAR_provision_classification) | Unknown | Legal provision classification in contracts | [Paper](https://aclanthology.org/2020.lrec-1.155/) | One of the largest open contract-clause classification datasets in legal NLP. |
| 19 | Pile of Law | English legal text | [GitHub](https://github.com/Breakend/PileOfLaw) | Mixed / source-specific | Legal-domain pretraining and corpus mining | [Paper](https://arxiv.org/abs/2207.00220) | A widely used large-scale legal corpus for legal LMs and legal retrieval pipelines. |
| 20 | ECtHR Cases | English | [HF](https://huggingface.co/datasets/AUEB-NLP/ecthr_cases) | CC BY-NC-SA 4.0 | Legal judgment prediction and rationale extraction | [Paper](https://arxiv.org/abs/2103.13084) | A standard benchmark family for European human-rights case outcome prediction. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [Search-Retrieval overview](../Search-Retrieval/README.md)
- [LexGLUE](https://github.com/coastalcph/lex-glue)
- [LegalBench](https://github.com/HazyResearch/legalbench)
- [MAUD](https://www.atticusprojectai.org/maud)
- [FinanceBench](https://github.com/patronus-ai/financebench)

## Selection Note

- This page includes both raw datasets and official regulator or legal-text portals when those portals are the canonical public source for a domain.
- For finance and law, high-signal resources often mix narrative text, tables, metadata, and domain-specific access terms, so licensing is kept conservative when unclear.
