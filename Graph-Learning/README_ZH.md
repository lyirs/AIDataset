# 图学习（Graph-Learning）

覆盖节点分类、链路预测、图级预测、知识图谱补全与长距离图推理的数据集、归档与 benchmark 套件。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Open Graph Benchmark (OGB) | Graph / molecule / KG | [Site](https://ogb.stanford.edu/) | Mixed / source-specific | 标准图学习评测 | [Paper](https://arxiv.org/abs/2005.00687) | 覆盖节点、链路与图级任务，是图学习里最核心的 benchmark 家族之一。 |
| 2 | OGB-LSC | Large-scale graphs | [Site](https://ogb.stanford.edu/docs/lsc/) | Mixed / source-specific | 大规模图学习 | [Paper](https://arxiv.org/abs/2103.09430) | 面向超大图数据，包含 MAG240M、WikiKG90Mv2 与 PCQM4Mv2。 |
| 3 | SNAP Network Dataset Collection | Graphs / networks | [Site](https://snap.stanford.edu/data/) | Mixed / dataset-specific | 图挖掘与网络科学 | [Docs](https://snap.stanford.edu/data/) | 斯坦福维护的大型网络数据集合，覆盖社交、网页、引用与时序网络。 |
| 4 | TUDataset | Graphs | [Site](https://chrsmrrs.github.io/datasets/docs/datasets/) | Unknown | 图分类基线 | [Docs](https://chrsmrrs.github.io/datasets/docs/datasets/) | 图核方法与 GNN 论文中最常见的图分类数据集集合之一。 |
| 5 | Planetoid | Citation graphs | [GitHub](https://github.com/kimiyoung/planetoid) | Unknown | 半监督节点分类 | [Paper](https://arxiv.org/abs/1603.08861) | Cora、CiteSeer、PubMed 这些经典 citation graph 划分仍被广泛沿用。 |
| 6 | Wiki-CS | Text-attributed graphs | [GitHub](https://github.com/pmernyei/wiki-cs-dataset) | Mixed / source-derived | Wikipedia 节点分类 | [Paper](https://arxiv.org/abs/2007.02901) | 提供 20 组标准划分，减少只对单一 split 过拟合的问题。 |
| 7 | CoDEx | Knowledge graph | [GitHub](https://github.com/tsafavi/codex) | Mixed / source-derived | 知识图谱补全 | [Paper](https://aclanthology.org/2020.emnlp-main.669/) | 基于 Wikidata 与 Wikipedia 构建，难度和可解释性都更强。 |
| 8 | Long Range Graph Benchmark (LRGB) | Graphs | [GitHub](https://github.com/vijaydwivedi75/lrgb) | Mixed / source-specific | 长距离图推理 | [Paper](https://arxiv.org/abs/2206.08164) | 专门考察长距离依赖，对局部 message passing 模型更有挑战。 |
| 9 | MoleculeNet | Molecular graphs | [GitHub](https://github.com/deepchem/moleculenet) | Mixed / source-specific | 分子性质预测 | [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.7b00083) | 覆盖量子化学、生物物理和生理等任务，是分子图学习的常用套件。 |
| 10 | ZINC | Molecular graphs | [Site](https://zinc.docking.org/) | Unknown | 分子图回归与生成 | [Docs](https://zinc.docking.org/) | 小型 ZINC 子集至今仍是图回归和分子生成论文里的常见基准。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [Open Graph Benchmark](https://ogb.stanford.edu/)
- [OGB-LSC](https://ogb.stanford.edu/docs/lsc/)
- [Long Range Graph Benchmark](https://github.com/vijaydwivedi75/lrgb)

## 收录说明

- 本页优先覆盖在 GNN、graph transformer、分子图学习与知识图谱论文里反复出现的核心 benchmark。
- 交通图与推荐图资源也会和 [Time-Series](../Time-Series/README_ZH.md) 及 [Recommender-Systems](../Recommender-Systems/README_ZH.md) 有交叉。
