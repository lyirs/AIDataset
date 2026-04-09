# Graph-Learning

Datasets, archives, and benchmark suites for node classification, link prediction, graph property prediction, knowledge graphs, and long-range graph reasoning.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Open Graph Benchmark (OGB) | Graph / molecule / KG | [Site](https://ogb.stanford.edu/) | Mixed / source-specific | Standard graph ML benchmarking | [Paper](https://arxiv.org/abs/2005.00687) | Core benchmark family for node, link, and graph property prediction. |
| 2 | OGB-LSC | Large-scale graphs | [Site](https://ogb.stanford.edu/docs/lsc/) | Mixed / source-specific | Web-scale graph learning | [Paper](https://arxiv.org/abs/2103.09430) | Large-scale challenge track covering MAG240M, WikiKG90Mv2, and PCQM4Mv2. |
| 3 | SNAP Network Dataset Collection | Graphs / networks | [Site](https://snap.stanford.edu/data/) | Mixed / dataset-specific | Network science and graph mining | [Docs](https://snap.stanford.edu/data/) | Large repository of social, web, citation, and temporal network datasets. |
| 4 | TUDataset | Graphs | [Site](https://chrsmrrs.github.io/datasets/docs/datasets/) | Unknown | Graph classification baselines | [Docs](https://chrsmrrs.github.io/datasets/docs/datasets/) | Long-running graph classification collection used across graph kernels and GNNs. |
| 5 | Planetoid | Citation graphs | [GitHub](https://github.com/kimiyoung/planetoid) | Unknown | Semi-supervised node classification | [Paper](https://arxiv.org/abs/1603.08861) | Cora, CiteSeer, and PubMed splits remain canonical citation-graph baselines. |
| 6 | Wiki-CS | Text-attributed graphs | [GitHub](https://github.com/pmernyei/wiki-cs-dataset) | Mixed / source-derived | Wikipedia node classification | [Paper](https://arxiv.org/abs/2007.02901) | Provides 20 standard splits to reduce overfitting to a single small training set. |
| 7 | CoDEx | Knowledge graph | [GitHub](https://github.com/tsafavi/codex) | Mixed / source-derived | Knowledge graph completion | [Paper](https://aclanthology.org/2020.emnlp-main.669/) | Harder and more interpretable KG completion benchmark derived from Wikidata and Wikipedia. |
| 8 | Long Range Graph Benchmark (LRGB) | Graphs | [GitHub](https://github.com/vijaydwivedi75/lrgb) | Mixed / source-specific | Long-range graph reasoning | [Paper](https://arxiv.org/abs/2206.08164) | Focuses on long-range dependencies that challenge local message-passing GNNs. |
| 9 | MoleculeNet | Molecular graphs | [GitHub](https://github.com/deepchem/moleculenet) | Mixed / source-specific | Molecular property prediction | [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.7b00083) | Benchmark suite spanning QM, biophysics, and physiology tasks with multiple split strategies. |
| 10 | ZINC | Molecular graphs | [Site](https://zinc.docking.org/) | Unknown | Molecular graph regression and generation | [Docs](https://zinc.docking.org/) | Small ZINC subsets remain standard in graph regression and graph generation papers. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [Open Graph Benchmark](https://ogb.stanford.edu/)
- [OGB-LSC](https://ogb.stanford.edu/docs/lsc/)
- [Long Range Graph Benchmark](https://github.com/vijaydwivedi75/lrgb)

## Selection Note

- This page prioritizes graph benchmarks repeatedly used in GNN, graph transformer, molecule, and knowledge graph papers.
- Traffic and recommender graph resources may also overlap with [Time-Series](../Time-Series/README.md) and [Recommender-Systems](../Recommender-Systems/README.md).
