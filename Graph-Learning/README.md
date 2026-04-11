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
| 11 | Temporal Graph Benchmark (TGB) | Temporal graphs | [Site](https://tgb.complexdatalab.com/) | Mixed / source-specific | Temporal link prediction and dynamic graph learning | [Paper](https://arxiv.org/abs/2307.01026) | The clearest modern benchmark family for realistic machine learning on temporal graphs. |
| 12 | Heterogeneous Graph Benchmark (HGB) | Heterogeneous graphs | [GitHub](https://github.com/THUDM/HGB) | Mixed / source-specific | Heterogeneous graph learning and evaluation | [Paper](https://arxiv.org/abs/2112.14936) | A standard benchmark suite for heterogenous node classification, link prediction, and recommendation-style tasks. |
| 13 | Reddit | Text-attributed graph | [Site](https://snap.stanford.edu/graphsage/) | Unknown | Inductive node classification at scale | [Paper](https://arxiv.org/abs/1706.02216) | Canonical large attributed graph benchmark from the GraphSAGE line of work. |
| 14 | PPI | Biological interaction graphs | [Site](https://snap.stanford.edu/graphsage/) | Unknown | Inductive generalization to unseen graphs | [Paper](https://arxiv.org/abs/1706.02216) | A long-running multi-graph benchmark for learning across disjoint protein interaction graphs. |
| 15 | FB15k-237 | Knowledge graph | [GitHub](https://github.com/TimDettmers/ConvE) | Unknown | Leakage-reduced KG completion | [Paper](https://arxiv.org/abs/1707.01476) | Still one of the most common small-to-mid-scale knowledge graph completion baselines. |
| 16 | WN18RR | Knowledge graph | [GitHub](https://github.com/TimDettmers/ConvE) | Unknown | WordNet KG completion | [Paper](https://arxiv.org/abs/1707.01476) | The standard WordNet counterpart to FB15k-237 for leakage-reduced link prediction. |
| 17 | Geom-GCN Heterophily Suite | Heterophilous graphs | [GitHub](https://github.com/bingzhewei/geom-gcn) | Unknown | Disassortative node classification | [Paper](https://arxiv.org/abs/2002.05287) | Classic heterophily suite covering Actor, Chameleon, Squirrel, Texas, Wisconsin, and Cornell. |
| 18 | Yandex Heterophilous Graph Datasets | Heterophilous graphs | [Site](https://research.yandex.com/datasets/heterophilous-graph-datasets) | Unknown | Modern heterophily benchmarking | [Docs](https://research.yandex.com/publications/a-critical-look-at-the-evaluation-of-gnns-under-heterophily-are-we-really-making-progress) | Includes Roman-empire, Amazon-ratings, Minesweeper, Tolokers, and Questions. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [Open Graph Benchmark](https://ogb.stanford.edu/)
- [OGB-LSC](https://ogb.stanford.edu/docs/lsc/)
- [Long Range Graph Benchmark](https://github.com/vijaydwivedi75/lrgb)
- [Temporal Graph Benchmark](https://tgb.complexdatalab.com/)
- [GraphSAGE benchmarks](https://snap.stanford.edu/graphsage/)
- [Yandex heterophilous graph datasets](https://research.yandex.com/datasets/heterophilous-graph-datasets)

## Selection Note

- This page prioritizes graph benchmarks repeatedly used in GNN, graph transformer, molecule, and knowledge graph papers.
- Traffic and recommender graph resources may also overlap with [Time-Series](../Time-Series/README.md) and [Recommender-Systems](../Recommender-Systems/README.md).
