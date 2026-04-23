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
| 6 | CMAPSS Jet Engine Simulated Data | Multivariate time series | [Site](https://catalog.data.gov/dataset/cmapss-jet-engine-simulated-data) | Unknown | 剩余寿命预测与工业预测性维护 | [Docs](https://data.nasa.gov/dataset/damage-propagation-modeling-for-aircraft-engine-run-to-failure-simulation) | 它是 NASA 官方维护的 run-to-failure 基准，至今仍是工业 RUL 预测论文的默认参考之一。 |
| 7 | Electricity Transformer Temperature (ETT) | Multivariate time series | [GitHub](https://github.com/zhouhaoyi/ETDataset) | Unknown | 长时序预测 | [Paper](https://arxiv.org/abs/2012.07436) | 长序列预测论文中最常出现的基准家族之一，包含小时级与 15 分钟级版本。 |
| 8 | METR-LA | Traffic time series + graph | [GitHub](https://github.com/liyaguang/DCRNN) | Unknown | 时空交通预测 | [Paper](https://arxiv.org/abs/1707.01926) | 官方 DCRNN 仓库提供的数据与预处理流程，沿用至今。 |
| 9 | PEMS-BAY | Traffic time series + graph | [GitHub](https://github.com/liyaguang/DCRNN) | Unknown | 路网交通预测 | [Paper](https://arxiv.org/abs/1707.01926) | 常与 METR-LA 配套出现，是图时序建模的重要基准。 |
| 10 | Individual Household Electric Power Consumption | Time series | [Site](https://archive.ics.uci.edu/dataset/235/individual%2Bhousehold%2Belectric%2Bpower%2Bci) | CC BY 4.0 | 家庭能耗预测与负荷分析 | [Docs](https://archive.ics.uci.edu/dataset/235/individual%2Bhousehold%2Belectric%2Bpower%2Bci) | 它是分钟级家庭电力时序的经典基准，在多变量预测和能耗分析论文里一直很常见。 |
| 11 | Numenta Anomaly Benchmark (NAB) | Time series | [GitHub](https://github.com/numenta/NAB) | Unknown | 流式异常检测 | [Paper](https://arxiv.org/abs/1510.03336) | 经典的实时异常评分 benchmark，适合在线检测场景。 |
| 12 | PhysioNet/CinC Challenge 2012 | Clinical multivariate time series | [Site](https://physionet.org/content/challenge-2012/1.0.0/) | Open access / PhysioNet terms | 临床时序风险建模 | [Docs](https://physionet.org/content/challenge-2012/1.0.0/) | 面向 ICU 死亡风险预测，包含不规则采样的生理观测序列。 |
| 13 | M3 Competition | Time series | [Site](https://forecasters.org/resources/time-series-data/m3-competition/) | Unknown | 经典大规模预测评测 | [Docs](https://forecasters.org/resources/time-series-data/m3-competition/) | 作为 M4 的前代，它在 forecasting benchmark 对比里仍然经常出现。 |
| 14 | ElectricityLoadDiagrams20112014 | Time series | [Site](https://archive.ics.uci.edu/dataset/321/electricityloaddiagrams20112014) | CC BY 4.0 | 电力负荷预测 | [Docs](https://archive.ics.uci.edu/dataset/321/electricityloaddiagrams20112014) | 长时序预测论文里反复出现的标准电力负荷数据集。 |
| 15 | Beijing PM2.5 | Multivariate time series | [Site](https://archive.ics.uci.edu/dataset/381/beijing%2Bpm2%2B5%2BdataCompeting) | CC BY 4.0 | 空气质量预测与环境时序建模 | [Docs](https://archive.ics.uci.edu/dataset/381/beijing%2Bpm2%2B5%2BdataCompeting) | 它是多变量环境时间序列建模里最常被复用的一类污染预测基准。 |
| 16 | PhysioNet/CinC Challenge 2019 | Clinical multivariate time series | [Site](https://physionet.org/challenge/2019/) | Unknown | 早期脓毒症预测 | [Docs](https://physionet.org/static/published-projects/challenge-2019/1.0.0/physionet_challenge_2019_ccm_manuscript.pdf) | 临床时序预警里很高信号的 ICU benchmark，强调早期识别。 |
| 17 | PTB-XL | Clinical multivariate time series | [Site](https://physionet.org/content/ptb-xl/1.0.3/) | CC BY 4.0 | ECG 分类与表征学习 | [Paper](https://www.nature.com/articles/s41597-020-0495-6) | 现代临床时间序列建模里最常出现的 ECG benchmark 之一。 |
| 18 | HiRID | Clinical multivariate time series | [Site](https://physionet.org/content/hirid/1.1.1/) | PhysioNet Contributor Review Health Data License 1.5.0 | 高分辨率 ICU 预测与插补 | [Docs](https://hirid.intensivecare.ai/) | 需要凭证访问，但在早预警、预测与不规则 ICU 时序研究里非常高频。 |
| 19 | WeatherBench | Spatiotemporal weather fields | [GitHub](https://github.com/pangeo-data/WeatherBench) | Copernicus / ERA5 terms | 数据驱动天气预测 | [Paper](https://arxiv.org/abs/2002.00469) | 它是全球中期天气预测里最常见的机器学习 benchmark 之一。 |
| 20 | WeatherBench 2 | Spatiotemporal weather fields | [GitHub](https://github.com/google-research/weatherbench2) | Copernicus / ERA5 terms | 新一代全球天气模型评测 | [Paper](https://arxiv.org/abs/2308.15560) | 它已经成为现代天气大模型和数据驱动天气系统对比的默认 benchmark 之一。 |
| 21 | Beijing Multi-Site Air Quality | Multivariate time series | [Site](https://archive.ics.uci.edu/dataset/501/beijingmultisiteairqualitydata) | CC BY 4.0 | 多站点空气质量预测 | [Docs](https://archive.ics.uci.edu/dataset/501/beijingmultisiteairqualitydata) | 它是北京单站污染预测数据的多站点扩展版，在时空预测论文里出现频率很高。 |
| 22 | SWaT | Multivariate industrial time series | [Site](https://itrust.sutd.edu.sg/itrust-labs_datasets/dataset_info/) | Request-based / iTrust terms | 工业控制异常检测 | [Docs](https://itrust.sutd.edu.sg/itrust-labs_datasets/dataset_info/) | 它是网络物理系统与工业异常检测里最常用的多变量时序数据集之一。 |
| 23 | WADI | Multivariate industrial time series | [Site](https://itrust.sutd.edu.sg/itrust-labs_datasets/dataset_info/) | Request-based / iTrust terms | 供水系统异常检测 | [Docs](https://itrust.sutd.edu.sg/itrust-labs_datasets/dataset_info/) | 它常与 SWaT 配套使用，是工业控制安全论文里的经典异常检测 benchmark。 |
| 24 | Building Data Genome Project 2 | Multivariate building-energy time series | [GitHub](https://github.com/buds-lab/building-data-genome-project-2) | Unknown | 建筑能耗预测与分析 | [Paper](https://arxiv.org/abs/2006.02273) | 它是建筑能耗预测、负荷建模与长期能耗分析里很高信号的 benchmark。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [M Competitions](https://www.unic.ac.cy/iff/research/forecasting/m-competitions/)
- [Monash Time Series Forecasting Repository](https://forecastingdata.org/)
- [PhysioNet Challenges](https://physionet.org/challenge/)
- [WeatherBench](https://github.com/pangeo-data/WeatherBench)

## 收录说明

- 本页优先覆盖在 forecasting、classification、anomaly detection 与 spatiotemporal modeling 论文里反复出现的核心时间序列资源。
- 交通图时序基准也与 [Graph-Learning](../Graph-Learning/README_ZH.md) 有交叉，临床纵向数据则与 [Medical-AI](../Medical-AI/README_ZH.md) 互补。
