# Remote-Sensing

Datasets for overhead imagery, satellite scene understanding, aerial detection, land-cover mapping, and multispectral remote sensing.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | BigEarthNet | Multispectral + SAR | [Site](https://bigearth.net/) | CDLA-Permissive-1.0 | Large-scale satellite representation learning | [Paper](https://arxiv.org/abs/1902.06148) | A high-signal Sentinel benchmark for modern remote-sensing pretraining. |
| 2 | EuroSAT | Satellite imagery | [GitHub](https://github.com/phelber/EuroSAT) | Unknown | Lightweight satellite scene classification | [Paper](https://arxiv.org/abs/1709.00029) | Still a common quick baseline for land-use classification. |
| 3 | SpaceNet | Satellite imagery | [Site](https://spacenet.ai/) | Unknown | Building, road, and mapping extraction | [Docs](https://spacenet.ai/datasets/) | One of the most visible challenge ecosystems in geospatial vision. |
| 4 | xView | Overhead imagery | [Site](https://xviewdataset.org/) | Unknown | Object detection in overhead imagery | [Paper](https://arxiv.org/abs/1802.07856) | A classic high-resolution benchmark for rare-object detection from above. |
| 5 | fMoW | Overhead imagery | [GitHub](https://github.com/fMoW/dataset) | Unknown | Functional understanding of the world from satellite imagery | [Paper](https://arxiv.org/abs/1711.07846) | Useful when scene function matters more than single-object labels. |
| 6 | DOTA | Aerial imagery | [Site](https://captain-whu.github.io/DOTA/index.html) | Unknown | Oriented object detection in aerial images | [Paper](https://arxiv.org/abs/1711.10398) | The default anchor benchmark for rotated aerial detection. |
| 7 | iSAID | Aerial imagery | [Site](https://captain-whu.github.io/iSAID/index.html) | Unknown | Instance segmentation from overhead views | [Paper](https://arxiv.org/abs/1905.12886) | Extends aerial vision beyond boxes into large-scale instance masks. |
| 8 | LoveDA | Remote sensing imagery | [GitHub](https://github.com/Junjue-Wang/LoveDA) | Unknown | Domain adaptation and segmentation | [Docs](https://github.com/Junjue-Wang/LoveDA) | Frequently cited for rural-urban domain gaps in segmentation. |
| 9 | SEN12MS | Multispectral + SAR | [Site](https://mediatum.ub.tum.de/1474000) | Unknown | Multimodal remote-sensing representation learning | [Paper](https://arxiv.org/abs/1906.07789) | Combines Sentinel-1 and Sentinel-2 for cross-modal earth observation. |
| 10 | OpenEarthMap | Satellite imagery | [Site](https://open-earth-map.org/) | Unknown | Modern land-cover segmentation | [Paper](https://arxiv.org/abs/2210.10732) | A more recent open benchmark for pixel-level earth observation. |
| 11 | GEO-Bench | Geospatial multimodal | [GitHub](https://github.com/ServiceNow/geo-bench) | Apache-2.0 | Foundation-model evaluation for Earth observation | [Paper](https://arxiv.org/abs/2306.03831) | One of the strongest recent benchmark suites for geospatial foundation models. |
| 12 | SatlasPretrain | Satellite imagery | [Site](https://satlas-pretrain.allen.ai/) | Unknown | Large-scale remote-sensing pretraining | [Paper](https://arxiv.org/abs/2211.15660) | A high-signal pretraining corpus for recent earth-observation foundation models. |
| 13 | MMEarth | Multimodal Earth observation | [GitHub](https://github.com/vishalned/MMEarth-data) | Unknown | Sensor-rich multimodal geospatial pretraining | [Paper](https://arxiv.org/abs/2405.02771) | Adds a newer multimodal earth-observation resource with richer sensor coverage. |
| 14 | xBD / xView2 | Disaster imagery | [Site](https://xview2.org/dataset) | Unknown | Disaster damage assessment and building-level change analysis | [Paper](https://arxiv.org/abs/1911.09296) | Still the default open benchmark for satellite-based disaster-response modeling. |
| 15 | ISPRS 2D Semantic Labeling (Vaihingen / Potsdam) | Aerial imagery | [Site](https://www.isprs.org/resources/datasets/benchmarks/UrbanSemLab/2d-sem-label-vaihingen.aspx) | Unknown | Urban aerial semantic segmentation | [Docs](https://www.isprs.org/resources/datasets/benchmarks/UrbanSemLab/2d-sem-label-potsdam.aspx) | A long-running canonical benchmark pair for high-resolution remote-sensing segmentation. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [SpaceNet Challenges](https://spacenet.ai/challenges/)
- [DOTA Benchmark](https://captain-whu.github.io/DOTA/evaluation.html)
- [xView](https://xviewdataset.org/)
- [GEO-Bench](https://github.com/ServiceNow/geo-bench)

## Selection Note

- This page prioritizes datasets that remain common in remote-sensing vision, earth observation, overhead detection, and geospatial mapping papers.
- General-purpose natural-image datasets stay in [CV](../CV/README.md), while driving-specific street-scene data lives in [Autonomous-Driving](../Autonomous-Driving/README.md).
