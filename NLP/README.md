# NLP

Classic and modern text datasets for NER, QA, summarization, reasoning, text classification, and multilingual evaluation.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | CoNLL-2003 | English | [HF](https://huggingface.co/datasets/eriktks/conll2003) | Unknown | NER and token classification | [Paper](https://aclanthology.org/W03-0419/) | Classic news-domain NER benchmark. |
| 2 | Universal Dependencies | Multilingual | [Site](https://universaldependencies.org/) | Mixed / treebank-specific | Dependency parsing and multilingual syntax | [Docs](https://universaldependencies.org/) | High-signal addition surfaced by dataset-directory issue discussions. |
| 3 | SQuAD 2.0 | English | [Site](https://rajpurkar.github.io/SQuAD-explorer/) | CC BY-SA 4.0 | Extractive QA with unanswerables | [Paper](https://arxiv.org/abs/1806.03822) | Widely used reading comprehension set. |
| 4 | XNLI | Multilingual | [HF](https://huggingface.co/datasets/facebook/xnli) | Unknown | Cross-lingual NLI | [Paper](https://aclanthology.org/D18-1269/) | Covers 15 languages for transfer evaluation. |
| 5 | WikiANN | Multilingual | [HF](https://huggingface.co/datasets/unimelb-nlp/wikiann) | CC BY-SA 3.0 | Multilingual NER bootstrapping | [Docs](https://huggingface.co/datasets/unimelb-nlp/wikiann) | Wikipedia-derived entity labels. |
| 6 | PAWS-X | Multilingual | [HF](https://huggingface.co/datasets/google-research-datasets/paws-x) | Unknown | Paraphrase detection | [Paper](https://arxiv.org/abs/1908.11828) | Hard sentence pairs with high overlap. |
| 7 | CMRC 2018 | Chinese | [GitHub](https://github.com/ymcui/cmrc2018) | Unknown | Chinese extractive QA | [Paper](https://aclanthology.org/D19-1600/) | Strong baseline dataset for Chinese MRC. |
| 8 | DuReader | Chinese | [GitHub](https://github.com/baidu/DuReader) | Apache-2.0 | Open-domain QA and reading comprehension | [Paper](https://arxiv.org/abs/1711.05073) | Built from real Baidu search traffic. |
| 9 | THUCNews | Chinese | [GitHub](https://github.com/thunlp/THUCNews) | Unknown | Chinese topic classification | [Docs](https://github.com/thunlp/THUCNews) | Lightweight news corpus for quick baselines. |
| 10 | FewCLUE | Chinese | [GitHub](https://github.com/CLUEbenchmark/FewCLUE) | Unknown | Few-shot Chinese NLP tasks | [Paper](https://arxiv.org/abs/2107.07498) | Useful for low-resource prompting and tuning. |
| 11 | TyDi QA | Multilingual | [GitHub](https://github.com/google-research-datasets/tydiqa) | Unknown | Information-seeking multilingual QA | [Paper](https://arxiv.org/abs/2003.05002) | Typologically diverse QA benchmark. |
| 12 | TREC-6 | English | [HF](https://huggingface.co/datasets/CogComp/trec) | Unknown | Question classification | [Docs](https://huggingface.co/datasets/CogComp/trec) | A long-running baseline dataset mentioned in dataset-request issues. |
| 13 | Yelp Review Full | English | [HF](https://huggingface.co/datasets/Yelp/yelp_review_full) | Unknown | Review sentiment and document classification | [Docs](https://huggingface.co/datasets/Yelp/yelp_review_full) | Common large-scale text classification corpus. |
| 14 | MPQA | English | [Site](https://mpqa.cs.pitt.edu/) | Custom / registration | Opinion mining and subjectivity | [Docs](https://mpqa.cs.pitt.edu/) | Still useful when you need classic subjectivity annotations. |
| 15 | Amazon Reviews Multi | Multilingual | [HF](https://huggingface.co/datasets/amazon_reviews_multi) | Unknown | Multilingual review classification | [Docs](https://huggingface.co/datasets/amazon_reviews_multi) | Practical multilingual product-review corpus. |
| 16 | SNLI | English | [Site](https://nlp.stanford.edu/projects/snli/) | CC BY-SA 4.0 | Natural language inference | [Docs](https://nlp.stanford.edu/projects/snli/) | One of the most common entailment anchors in transfer-learning papers. |
| 17 | MultiNLI | English | [Site](https://cims.nyu.edu/~sbowman/multinli/) | Unknown | Multi-genre natural language inference | [Paper](https://aclanthology.org/N18-1101/) | Extends NLI evaluation beyond image-caption style premises. |
| 18 | ANLI | English | [GitHub](https://github.com/facebookresearch/anli) | Other / custom | Robust adversarial NLI | [Paper](https://aclanthology.org/2020.acl-main.441/) | Human-and-model-in-the-loop collection makes it harder than standard NLI sets. |
| 19 | HotpotQA | English | [Site](https://hotpotqa.github.io/) | CC BY-SA 4.0 | Multi-hop question answering | [Paper](https://aclanthology.org/D18-1259/) | Adds supporting-fact supervision for explainable reasoning. |
| 20 | FEVER | English | [Site](https://fever.ai/dataset/fever.html) | Wikipedia terms / CC BY-SA 3.0 | Fact verification with evidence retrieval | [Docs](https://fever.ai/dataset/fever.html) | A long-running fact-checking benchmark centered on evidence selection. |
| 21 | Natural Questions | English | [Site](https://ai.google.com/research/NaturalQuestions) | Unknown | Open-domain QA and long-answer retrieval | [Docs](https://ai.google.com/research/NaturalQuestions/download) | Built from real Google queries and still central in QA papers. |
| 22 | CNN/DailyMail | English | [HF](https://huggingface.co/datasets/ccdv/cnn_dailymail) | Unknown | News summarization baselines | [Docs](https://huggingface.co/datasets/ccdv/cnn_dailymail) | A default reference point for abstractive summarization comparisons. |
| 23 | XSum | English | [GitHub](https://github.com/EdinburghNLP/XSum) | Unknown | Extreme abstractive summarization | [Paper](https://aclanthology.org/D18-1206/) | Common one-sentence news summarization benchmark in ACL-style evaluations. |
| 24 | BoolQ | English | [GitHub](https://github.com/google-research-datasets/boolean-questions) | CC BY-SA 3.0 | Yes/no question answering | [Paper](https://aclanthology.org/N19-1300/) | A standard naturally occurring yes-no QA benchmark that also appears in SuperGLUE-style comparisons. |
| 25 | GSM8K | English | [GitHub](https://github.com/openai/grade-school-math) | Unknown | Math word-problem reasoning | [Paper](https://arxiv.org/abs/2110.14168) | One of the most reused reasoning datasets in modern LLM and NLP evaluation tables. |
| 26 | WikiText-103 | English | [HF](https://huggingface.co/datasets/Salesforce/wikitext) | CC BY-SA 4.0 | Language modeling and long-context pretraining | [Paper](https://arxiv.org/abs/1609.07843) | A long-running language-modeling corpus that still anchors perplexity and pretraining comparisons. |
| 27 | WMT14 Translation Task | Multilingual | [Site](https://statmt.org/wmt14/translation-task.html) | Mixed / source-specific | Machine translation benchmarking | [Docs](https://statmt.org/wmt14/) | The En-De setup remains one of the default MT reference points in NLP papers. |
| 28 | BIRD | English / SQL | [Site](https://bird-bench.github.io/) | Unknown | Text-to-SQL and database-grounded generation | [Paper](https://arxiv.org/abs/2305.03111) | The anchor benchmark family for modern text-to-SQL and agentic database querying papers. |
| 29 | Belebele | Multilingual | [HF](https://huggingface.co/datasets/facebook/belebele) | CC BY-SA 4.0 | Massively multilingual reading comprehension | [Paper](https://arxiv.org/abs/2308.16884) | A high-signal multilingual reading benchmark spanning more than 100 language variants. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [GLUE](https://gluebenchmark.com/)
- [SuperGLUE](https://super.gluebenchmark.com/)
- [XTREME](https://github.com/google-research/xtreme)
- [WMT](https://www.statmt.org/wmt24/)
- [CLUE](https://github.com/CLUEbenchmark/CLUE)
- [FewCLUE](https://github.com/CLUEbenchmark/FewCLUE)
- [BIRD](https://bird-bench.github.io/)
- [Belebele](https://huggingface.co/datasets/facebook/belebele)

## Selection Note

- This page prioritizes datasets that continue to appear in ACL, EMNLP, and NAACL papers, tutorials, and strong baseline comparisons.
- If a canonical NLI, QA, summarization, or fact-verification dataset is missing, it should be treated as a curation gap for later passes.
