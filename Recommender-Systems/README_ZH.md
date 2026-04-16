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
| 11 | Jester | Ratings | [Site](https://eigentaste.berkeley.edu/dataset/) | Custom / research use | 稠密显式评分协同过滤 | [Docs](https://eigentaste.berkeley.edu/about.html) | 推荐系统学术研究里寿命很长、也非常经典的稠密评分数据集之一。 |
| 12 | Book-Crossing | Ratings + metadata | [Site](https://grouplens.org/datasets/book-crossing/) | Unknown | 图书推荐与显隐式反馈建模 | [Docs](https://grouplens.org/datasets/book-crossing/) | 图书推荐方向的经典 benchmark，带稀疏评分交互和元数据。 |
| 13 | HetRec 2011 LastFM 2K | Music listening + tags | [Site](https://grouplens.org/datasets/hetrec-2011/) | Unknown | 音乐推荐与社交推荐 | [Paper](https://dl.acm.org/doi/10.1145/2043932.2043988) | 基于 Last.fm 听歌行为与标签构建，是音乐推荐方向的经典 benchmark。 |
| 14 | Adressa | English news + click logs | [Site](https://reclab.idi.ntnu.no/dataset/) | Custom / research access | 实时新闻推荐 | [Paper](https://arxiv.org/abs/1808.03162) | 它是 session-aware 与流式新闻推荐研究里最常见的公开 benchmark 之一。 |
| 15 | Taobao User Behavior Dataset | E-commerce behavior logs | [Site](https://tianchi.aliyun.com/dataset/649) | Custom / Tianchi terms | 序列推荐与 CTR 式行为建模 | [Docs](https://tianchi.aliyun.com/dataset/649) | 阿里电商行为数据里最常被推荐论文复用的一批公开数据之一。 |
| 16 | XING / RecSys Challenge 2016 | Job recommendation logs | [Site](https://2016.recsyschallenge.com/) | Custom / challenge terms | 职位推荐与隐式反馈排序 | [Docs](https://2016.recsyschallenge.com/challenge.html) | 一个很强的大规模工业级 benchmark，适合隐式反馈和丰富元数据推荐研究。 |
| 17 | Trivago / RecSys Challenge 2019 | Session interactions | [Site](https://www.recsyschallenge.com/2019/) | Custom / challenge terms | 会话推荐与上下文排序 | [Docs](https://www.recsyschallenge.com/2019/challenge.html) | 会话推荐和反事实排序研究里信号很高的一类公开 challenge 数据。 |
| 18 | Ali-CCP | CTR + conversion logs | [Site](https://tianchi.aliyun.com/dataset/408) | Custom / Tianchi terms | CTR 与转化率联合预测 | [Docs](https://tianchi.aliyun.com/dataset/408) | 它是工业界点击率与转化率多任务建模里最常见的大规模公开 benchmark 之一。 |
| 19 | Gowalla | Location check-ins + social graph | [Site](https://snap.stanford.edu/data/loc-gowalla.html) | Unknown | POI 推荐与序列化出行建模 | [Paper](https://cs.stanford.edu/people/jure/pubs/mobile-kdd11.pdf) | 它是 next-location recommendation、移动轨迹建模和图推荐中的长期经典数据集。 |
| 20 | Million Song Dataset / Taste Profile Subset | Music listening logs | [Site](https://millionsongdataset.com/tasteprofile/) | Custom / Echo Nest API license | 音乐推荐与隐式反馈排序 | [Docs](https://millionsongdataset.com/tasteprofile/) | 它把真实听歌行为与 Million Song Dataset 连接起来，是音乐推荐里最经典的资源之一。 |
| 21 | Criteo Terabyte Click Logs | CTR logs | [Site](https://ailab.criteo.com/criteo-1tb-click-logs-dataset/) | CC BY-NC-SA 4.0 | Web 级 CTR 预测 | [Docs](https://ailab.criteo.com/ctr-at-scale-using-open-technologies/) | 它是原始 Criteo challenge 之后更偏工业规模的一类标准 CTR benchmark。 |
| 22 | Outbrain Click Prediction | Content recommendation logs | [Site](https://www.outbrain.com/blog/outbrain-challenge/) | Custom / competition terms | 大规模内容推荐与 CTR 排序 | [Docs](https://www.outbrain.com/blog/outbrain-challenge/) | 它基于真实内容分发交互构建，是内容推荐和点击排序研究里高信号的数据集。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [RecSys Challenges](https://recsys.acm.org/challenges/)
- [MIND](https://msnews.github.io/)
- [Open Bandit Dataset](https://research.zozo.com/data.html)
- [Ali-CCP](https://tianchi.aliyun.com/dataset/408)

## 收录说明

- 本页优先覆盖协同过滤、排序、CTR、bandit evaluation、新闻推荐与会话推荐中最常用的学术与工业 benchmark。
- 文本信息较丰富的推荐数据也会和 [NLP](../NLP/README_ZH.md) 及 [Search-Retrieval](../Search-Retrieval/README_ZH.md) 有交叉。
