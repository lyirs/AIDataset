# 推荐系统（Recommender-Systems）

覆盖协同过滤、排序、点击率预测、新闻推荐、bandit feedback 与工业级推荐评测的数据集目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | MovieLens | Ratings + tags | [Site](https://grouplens.org/datasets/movielens/) | Custom / README terms | 协同过滤基线 | [Docs](https://grouplens.org/datasets/movielens/) | 显式反馈推荐里最经典、也最常被首先引用的数据集之一。 |
| 2 | MIND | English news + click logs | [Site](https://msnews.github.io/) | Microsoft Research License Terms | 新闻推荐 | [Paper](https://aclanthology.org/2020.acl-main.331/) | 基于 Microsoft News 行为日志构建的大规模新闻推荐 benchmark。 |
| 3 | Yelp Open Dataset | English reviews + business metadata | [Site](https://business.yelp.com/data/resources/open-dataset/) | Custom / educational use | 本地推荐与评论建模 | [Docs](https://business.yelp.com/data/resources/open-dataset/) | 同时包含评论、商户、照片、签到与丰富商户属性。 |
| 4 | Criteo Display Advertising Challenge | CTR logs | [Site](https://ailab.criteo.com/display-advertising-challenge-criteo/) | Custom / competition terms | 点击率预测与排序 | [Docs](https://ailab.criteo.com/display-advertising-challenge-criteo/) | 广告 CTR 学习中最经典的大规模 benchmark 之一。 |
| 5 | Avazu CTR Prediction | CTR logs | [Site](https://www.kaggle.com/c/avazu-ctr-prediction) | Custom / competition terms | 大规模广告点击预测 | [Docs](https://www.kaggle.com/c/avazu-ctr-prediction) | 稀疏类别特征场景下非常常见的 CTR 基准。 |
| 6 | Open Bandit Dataset | Bandit logs | [Site](https://research.zozo.com/data.html) | Unknown | 推荐中的离线策略评估 | [Paper](https://arxiv.org/abs/2008.07146) | 来自大型时尚电商平台的真实 bandit feedback 数据。 |
| 7 | KuaiRec | Video recommendation logs | [Site](https://kuairec.com/) | Unknown | 稠密反馈推荐评估 | [Paper](https://doi.org/10.1145/3511808.3557220) | 来自快手的近乎全观测交互矩阵，非常适合离线评估研究。 |
| 8 | KuaiRand | Sequential recommendation logs | [Site](https://kuairand.com/) | Unknown | 去偏序列推荐 | [Paper](https://doi.org/10.1145/3511808.3557624) | 通过随机曝光机制支持反事实学习和 unbiased recommendation 研究。 |
| 9 | YOOCHOOSE / RecSys Challenge 2015 | Session clicks | [Site](https://recsys.acm.org/recsys15/challenge/) | Unknown | Session-based recommendation | [Docs](https://recsys.acm.org/recsys15/challenge/) | RecSys Challenge 2015 的代表性会话推荐 benchmark。 |
| 10 | Amazon Reviews'23 | Reviews + metadata + graphs | [Site](https://amazon-reviews-2023.github.io/) | Unknown | 大规模商品检索与推荐 | [Paper](https://arxiv.org/abs/2403.03952) | 现代推荐研究中很重要的大规模资源，包含评论文本、元数据与商品关联结构。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [RecSys Challenges](https://recsys.acm.org/challenges/)
- [MIND](https://msnews.github.io/)
- [Open Bandit Dataset](https://research.zozo.com/data.html)

## 收录说明

- 本页优先覆盖协同过滤、排序、CTR、bandit evaluation、新闻推荐与会话推荐中最常用的学术与工业 benchmark。
- 文本信息较丰富的推荐数据也会和 [NLP](../NLP/README_ZH.md) 及 [Search-Retrieval](../Search-Retrieval/README_ZH.md) 有交叉。
