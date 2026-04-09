# Time-Series

Datasets and benchmark archives for forecasting, classification, anomaly detection, and spatiotemporal time-series modeling.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | UCR Time Series Classification Archive | Time series | [Site](https://www.cs.ucr.edu/~eamonn/time_series_data_2018/) | Unknown | Univariate time-series classification | [Paper](https://arxiv.org/abs/1810.07758) | Canonical archive with standardized train/test splits across many domains. |
| 2 | UEA Time Series Classification Archive | Multivariate time series | [Site](https://www.timeseriesclassification.com/) | Unknown | Multivariate time-series classification | [Paper](https://arxiv.org/abs/1811.00075) | Maintainer-run archive widely used for multivariate TSC baselines. |
| 3 | Monash Time Series Forecasting Repository | Time series | [Site](https://forecastingdata.org/) | Mixed / source-specific | Forecast benchmarking across domains | [Paper](https://arxiv.org/abs/2105.06643) | Aggregates classic competitions and applied forecasting collections in a consistent format. |
| 4 | M4 Competition | Time series | [Site](https://www.unic.ac.cy/iff/research/forecasting/m-competitions/m4/) | Unknown | Large-scale forecasting evaluation | [Docs](https://pure.unic.ac.cy/en/publications/the-m4-competition-100000-time-series-and-61-forecasting-methods) | Covers 100,000 real-life series across multiple frequencies and domains. |
| 5 | M5 Forecasting Competition | Time series + tabular covariates | [Site](https://www.unic.ac.cy/iff/research/forecasting/m-competitions/m5/) | Unknown | Hierarchical retail forecasting | [Docs](https://pure.unic.ac.cy/en/publications/the-m5-competition-background-organization-and-implementation/) | Adds exogenous variables and hierarchical Walmart sales structure. |
| 6 | Electricity Transformer Temperature (ETT) | Multivariate time series | [GitHub](https://github.com/zhouhaoyi/ETDataset) | Unknown | Long-horizon forecasting | [Paper](https://arxiv.org/abs/2012.07436) | Widely used benchmark family with hourly and 15-minute variants. |
| 7 | METR-LA | Traffic time series + graph | [GitHub](https://github.com/liyaguang/DCRNN) | Unknown | Spatiotemporal traffic forecasting | [Paper](https://arxiv.org/abs/1707.01926) | Distributed from the official DCRNN benchmark repository with preprocessing guidance. |
| 8 | PEMS-BAY | Traffic time series + graph | [GitHub](https://github.com/liyaguang/DCRNN) | Unknown | Traffic forecasting on road networks | [Paper](https://arxiv.org/abs/1707.01926) | Paired with METR-LA and still common in graph-based traffic forecasting papers. |
| 9 | Numenta Anomaly Benchmark (NAB) | Time series | [GitHub](https://github.com/numenta/NAB) | Unknown | Streaming anomaly detection | [Paper](https://arxiv.org/abs/1510.03336) | Classic benchmark for real-time anomaly scoring over labeled streams. |
| 10 | PhysioNet/CinC Challenge 2012 | Clinical multivariate time series | [Site](https://physionet.org/content/challenge-2012/1.0.0/) | Open access / PhysioNet terms | Clinical time-series risk modeling | [Docs](https://physionet.org/content/challenge-2012/1.0.0/) | ICU mortality prediction benchmark with irregularly sampled physiological measurements. |
| 11 | M3 Competition | Time series | [Site](https://forecasters.org/resources/time-series-data/m3-competition/) | Unknown | Classic large-scale forecasting evaluation | [Docs](https://forecasters.org/resources/time-series-data/m3-competition/) | The predecessor to M4 still appears frequently in forecasting benchmark comparisons. |
| 12 | ElectricityLoadDiagrams20112014 | Time series | [Site](https://archive.ics.uci.edu/dataset/321/electricityloaddiagrams20112014) | CC BY 4.0 | Electricity load forecasting | [Docs](https://archive.ics.uci.edu/dataset/321/electricityloaddiagrams20112014) | A standard electricity benchmark reused across long-horizon forecasting papers. |
| 13 | PhysioNet/CinC Challenge 2019 | Clinical multivariate time series | [Site](https://physionet.org/challenge/2019/) | Unknown | Early sepsis prediction from clinical streams | [Docs](https://physionet.org/static/published-projects/challenge-2019/1.0.0/physionet_challenge_2019_ccm_manuscript.pdf) | A high-signal clinical time-series benchmark for early warning on irregular ICU data. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [M Competitions](https://www.unic.ac.cy/iff/research/forecasting/m-competitions/)
- [Monash Forecasting Repository](https://forecastingdata.org/)
- [PhysioNet Challenges](https://physionet.org/challenge/)

## Selection Note

- This page prioritizes canonical time-series resources repeatedly used in forecasting, classification, anomaly detection, and spatiotemporal modeling papers.
- Traffic graph benchmarks here also overlap with [Graph-Learning](../Graph-Learning/README.md), while clinical longitudinal data may intersect with [Medical-AI](../Medical-AI/README.md).
