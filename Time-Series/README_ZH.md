# 时间序列（Time-Series）

覆盖预测、分类、异常检测与时空序列建模的时间序列数据集与 benchmark archive。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | UCR Time Series Classification Archive | Time series | [Site](https://www.cs.ucr.edu/~eamonn/time_series_data_2018/) | Unknown | 单变量时间序列分类 | [Paper](https://arxiv.org/abs/1810.07758) | 最经典的时间序列分类归档之一，提供标准化 train/test 划分。 |
| 2 | UEA Time Series Classification Archive | Multivariate time series | [Site](https://www.timeseriesclassification.com/) | Unknown | 多变量时间序列分类 | [Paper](https://arxiv.org/abs/1811.00075) | 多变量 TSC 论文中最常见的维护者官方归档之一。 |
| 3 | Monash Time Series Forecasting Repository | Time series | [Site](https://forecastingdata.org/) | Mixed / source-specific | 跨领域预测 benchmark | [Paper](https://arxiv.org/abs/2105.06643) | 汇总了经典竞赛和应用预测数据，并做了统一整理。 |
| 4 | M4 Competition | Time series | [Site](https://www.unic.ac.cy/iff/research/forecasting/m-competitions/m4/) | Unknown | 大规模预测评测 | [Docs](https://pure.unic.ac.cy/en/publications/the-m4-competition-100000-time-series-and-61-forecasting-methods) | 覆盖 100,000 条真实时间序列，是 forecasting 领域标志性基准。 |
| 5 | M5 Forecasting Competition | Time series + tabular covariates | [Site](https://www.unic.ac.cy/iff/research/forecasting/m-competitions/m5/) | Unknown | 分层零售需求预测 | [Docs](https://pure.unic.ac.cy/en/publications/the-m5-competition-background-organization-and-implementation/) | 在时间序列之外加入价格、促销、节假日等外生变量。 |
| 6 | Electricity Transformer Temperature (ETT) | Multivariate time series | [GitHub](https://github.com/zhouhaoyi/ETDataset) | Unknown | 长时序预测 | [Paper](https://arxiv.org/abs/2012.07436) | 长序列预测论文中最常出现的基准家族之一，包含小时级与 15 分钟级版本。 |
| 7 | METR-LA | Traffic time series + graph | [GitHub](https://github.com/liyaguang/DCRNN) | Unknown | 时空交通预测 | [Paper](https://arxiv.org/abs/1707.01926) | 官方 DCRNN 仓库提供的数据与预处理流程，沿用至今。 |
| 8 | PEMS-BAY | Traffic time series + graph | [GitHub](https://github.com/liyaguang/DCRNN) | Unknown | 路网交通预测 | [Paper](https://arxiv.org/abs/1707.01926) | 常与 METR-LA 配套出现，是图时序建模的重要基准。 |
| 9 | Numenta Anomaly Benchmark (NAB) | Time series | [GitHub](https://github.com/numenta/NAB) | Unknown | 流式异常检测 | [Paper](https://arxiv.org/abs/1510.03336) | 经典的实时异常评分 benchmark，适合在线检测场景。 |
| 10 | PhysioNet/CinC Challenge 2012 | Clinical multivariate time series | [Site](https://physionet.org/content/challenge-2012/1.0.0/) | Open access / PhysioNet terms | 临床时序风险建模 | [Docs](https://physionet.org/content/challenge-2012/1.0.0/) | 面向 ICU 死亡风险预测，包含不规则采样的生理观测序列。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [M Competitions](https://www.unic.ac.cy/iff/research/forecasting/m-competitions/)
- [Monash Time Series Forecasting Repository](https://forecastingdata.org/)
- [PhysioNet Challenges](https://physionet.org/challenge/)

## 收录说明

- 本页优先覆盖在 forecasting、classification、anomaly detection 与 spatiotemporal modeling 论文里反复出现的核心时间序列资源。
- 交通图时序基准也与 [Graph-Learning](../Graph-Learning/README_ZH.md) 有交叉，临床纵向数据则与 [Medical-AI](../Medical-AI/README_ZH.md) 互补。
