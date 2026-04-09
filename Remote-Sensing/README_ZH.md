# 遥感（Remote-Sensing）

覆盖高空影像、卫星场景理解、航拍检测、地表覆盖制图与多光谱遥感的数据集目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | BigEarthNet | Multispectral + SAR | [Site](https://bigearth.net/) | CDLA-Permissive-1.0 | 大规模卫星表征学习 | [Paper](https://arxiv.org/abs/1902.06148) | 现代遥感预训练里高频出现的 Sentinel 系锚点数据集。 |
| 2 | EuroSAT | Satellite imagery | [GitHub](https://github.com/phelber/EuroSAT) | Unknown | 轻量级卫星场景分类 | [Paper](https://arxiv.org/abs/1709.00029) | 土地利用分类快速基线里仍然非常常见。 |
| 3 | SpaceNet | Satellite imagery | [Site](https://spacenet.ai/) | Unknown | 建筑、道路与地图抽取 | [Docs](https://spacenet.ai/datasets/) | 地理空间视觉领域最有影响力的 challenge 生态之一。 |
| 4 | xView | Overhead imagery | [Site](https://xviewdataset.org/) | Unknown | 高空影像目标检测 | [Paper](https://arxiv.org/abs/1802.07856) | 高分辨率俯视视角稀有目标检测的经典基准。 |
| 5 | fMoW | Overhead imagery | [GitHub](https://github.com/fMoW/dataset) | Unknown | 基于卫星影像的功能场景理解 | [Paper](https://arxiv.org/abs/1711.07846) | 当研究重点是场景功能而非单个目标时尤其常用。 |
| 6 | DOTA | Aerial imagery | [Site](https://captain-whu.github.io/DOTA/index.html) | Unknown | 航拍旋转目标检测 | [Paper](https://arxiv.org/abs/1711.10398) | 旋转框航拍检测方向的默认锚点基准。 |
| 7 | iSAID | Aerial imagery | [Site](https://captain-whu.github.io/iSAID/index.html) | Unknown | 俯视视角实例分割 | [Paper](https://arxiv.org/abs/1905.12886) | 让遥感视觉从框检测进一步扩展到大规模实例分割。 |
| 8 | LoveDA | Remote sensing imagery | [GitHub](https://github.com/Junjue-Wang/LoveDA) | Unknown | 域适应与语义分割 | [Docs](https://github.com/Junjue-Wang/LoveDA) | 在城乡域差异的遥感分割研究里引用频率很高。 |
| 9 | SEN12MS | Multispectral + SAR | [Site](https://mediatum.ub.tum.de/1474000) | Unknown | 多模态遥感表征学习 | [Paper](https://arxiv.org/abs/1906.07789) | 组合 Sentinel-1 与 Sentinel-2 的跨模态地球观测资源。 |
| 10 | OpenEarthMap | Satellite imagery | [Site](https://open-earth-map.org/) | Unknown | 现代地表覆盖分割 | [Paper](https://arxiv.org/abs/2210.10732) | 较新的开源像素级地球观测基准。 |
| 11 | GEO-Bench | Geospatial multimodal | [GitHub](https://github.com/ServiceNow/geo-bench) | Apache-2.0 | 地球观测基础模型评测 | [Paper](https://arxiv.org/abs/2306.03831) | 遥感 foundation model 评测里近两年最强信号的一类 benchmark suite。 |
| 12 | SatlasPretrain | Satellite imagery | [Site](https://satlas-pretrain.allen.ai/) | Unknown | 大规模遥感预训练 | [Paper](https://arxiv.org/abs/2211.15660) | 新一代 earth-observation foundation model 很常引用的预训练语料。 |
| 13 | MMEarth | Multimodal Earth observation | [GitHub](https://github.com/vishalned/MMEarth-data) | Unknown | 多传感器地球观测预训练 | [Paper](https://arxiv.org/abs/2405.02771) | 提供更丰富传感器覆盖的新型多模态地球观测资源。 |
| 14 | xBD / xView2 | Disaster imagery | [Site](https://xview2.org/dataset) | Unknown | 灾害损伤评估与建筑级变化分析 | [Paper](https://arxiv.org/abs/1911.09296) | 目前仍是卫星灾后响应建模里最常见的开放 benchmark。 |
| 15 | ISPRS 2D Semantic Labeling (Vaihingen / Potsdam) | Aerial imagery | [Site](https://www.isprs.org/resources/datasets/benchmarks/UrbanSemLab/2d-sem-label-vaihingen.aspx) | Unknown | 城市航拍语义分割 | [Docs](https://www.isprs.org/resources/datasets/benchmarks/UrbanSemLab/2d-sem-label-potsdam.aspx) | 这是高分辨率遥感分割方向持续多年的 canonical benchmark 组合。 |
| 16 | UAVid | UAV imagery | [Site](https://uavid.nl/) | CC BY-NC-SA 4.0 | 无人机城市场景语义分割 | [Paper](https://doi.org/10.1016/j.isprsjprs.2020.05.009) | 在 UAV 语义分割与低空遥感论文里，它属于最常被复用的 benchmark 之一。 |
| 17 | Inria Aerial Image Labeling | Aerial imagery | [Site](https://project.inria.fr/aerialimagelabeling/) | Unknown | 航拍建筑物轮廓分割 | [Paper](https://doi.org/10.1109/IGARSS.2017.8127684) | 它是高分辨率建筑提取与跨城市泛化研究中最经典的 benchmark 之一。 |
| 18 | LEVIR-CD | Aerial imagery | [Site](https://justchenhao.github.io/LEVIR/) | Academic use only / non-commercial | 双时相影像建筑变化检测 | [Paper](https://arxiv.org/abs/2007.09244) | 它是遥感变化检测里最常被复用的大规模 building change benchmark 之一。 |
| 19 | DeepGlobe | Satellite imagery | [Site](https://deepglobe.org/resources.html) | Challenge-only / custom terms | 道路提取、建筑检测与地表覆盖分割 | [Paper](https://openaccess.thecvf.com/content_cvpr_2018_workshops/w4/html/Demir_DeepGlobe_2018_A_CVPR_2018_paper.html) | 它是 CVPR challenge 体系里非常经典的一组遥感分割数据资源。 |
| 20 | HRSCD | Aerial imagery | [Site](https://rcdaudt.github.io/hrscd/) | CC BY-NC-SA + source-data terms | 高分辨率航拍语义变化检测 | [Paper](https://rcdaudt.github.io/files/2018cviu-hrscd.pdf) | 它不只给二值变化掩码，还提供语义层面的地物变化标签，是非常经典的 change detection benchmark。 |
| 21 | S2Looking | Satellite imagery | [GitHub](https://github.com/S2Looking/Dataset) | Unknown | 侧视条件下的建筑变化检测 | [Paper](https://arxiv.org/abs/2107.09244) | 它是近年更贴近真实场景的遥感变化检测 benchmark，常被拿来和 LEVIR-CD 一起比较。 |
| 22 | WHU Building Dataset | Aerial + satellite imagery | [Site](https://gpcv.whu.edu.cn/data/building_dataset.html) | Unknown | 建筑物轮廓提取与大规模分割 | [Paper](https://doi.org/10.1109/TGRS.2018.2858817) | 它是建筑提取方向最标准的数据家族之一，提供高质量矢量与栅格标注。 |
| 23 | DIOR | Aerial imagery | [Site](https://gcheng-nwpu.github.io/) | CC BY-NC 4.0 | 大类别遥感目标检测 | [Paper](https://arxiv.org/abs/1909.00133) | 它是光学遥感目标检测里使用频率最高的大规模 benchmark 之一。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [SpaceNet Challenges](https://spacenet.ai/challenges/)
- [DOTA Benchmark](https://captain-whu.github.io/DOTA/evaluation.html)
- [xView](https://xviewdataset.org/)
- [GEO-Bench](https://github.com/ServiceNow/geo-bench)

## 收录说明

- 本页优先覆盖在遥感视觉、地球观测、高空检测与地理制图论文中持续高频出现的数据集。
- 通用自然图像数据仍保留在 [CV](../CV/README_ZH.md)，驾驶街景类数据则单独归入 [Autonomous-Driving](../Autonomous-Driving/README_ZH.md)。
