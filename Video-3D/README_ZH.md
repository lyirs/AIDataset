# 视频与三维（Video-3D）

覆盖视频理解、第一视角视频、三维场景、点云与三维形状数据的目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Kinetics-700 | Visual | [GitHub](https://github.com/google-deepmind/kinetics-dataset) | Unknown | 大规模动作识别 | [Paper](https://arxiv.org/abs/1907.06987) | 视频预训练最常见的起点之一。 |
| 2 | Something-Something V2 | Visual | [Site](https://developer.qualcomm.com/software/ai-datasets/something-something) | Custom | 细粒度时序推理 | [Paper](https://openaccess.thecvf.com/content_ICCV_2017/html/Goyal_The_Something_Something_ICCV_2017_paper.html) | 强调人与物交互的时间关系。 |
| 3 | EPIC-KITCHENS-100 | Visual | [Site](https://epic-kitchens.github.io/2021) | Custom | 第一视角动作识别 | [Paper](https://arxiv.org/abs/2006.13256) | 典型厨房场景第一视角数据集。 |
| 4 | Ego4D | Visual | [Site](https://ego4d-data.org/) | Custom | 第一视角视频预训练与评测 | [Paper](https://arxiv.org/abs/2110.07058) | 大规模多场景第一视角视频语料。 |
| 5 | Charades | Visual | [Site](https://prior.allenai.org/projects/charades) | Custom | 室内活动识别 | [Paper](https://arxiv.org/abs/1604.00627) | 日常动作会在长视频中重叠出现。 |
| 6 | ScanNet | Visual | [Site](https://www.scan-net.org/) | Custom | 室内三维场景理解 | [Paper](https://arxiv.org/abs/1702.04405) | RGB-D 扫描加语义标注。 |
| 7 | ShapeNet | Visual | [Site](https://shapenet.org/) | Custom | 三维形状生成与检索 | [Paper](https://arxiv.org/abs/1512.03012) | 三维物体研究中的常用基础资源。 |
| 8 | Objaverse-XL | Visual | [Site](https://objaverse.allenai.org/) | Unknown | 开放三维物体预训练 | [Paper](https://arxiv.org/abs/2307.05663) | 海量公开 3D 资产集合。 |
| 9 | KITTI | Visual | [Site](https://www.cvlibs.net/datasets/kitti/) | Custom | 自动驾驶检测与深度估计 | [Paper](https://www.cvlibs.net/publications/Geiger2012CVPR.pdf) | 自动驾驶研究中的经典基准。 |
| 10 | nuScenes | Visual | [Site](https://www.nuscenes.org/) | Custom | 三维检测与跟踪 | [Paper](https://arxiv.org/abs/1903.11027) | 多模态自动驾驶街景数据。 |
| 11 | ActivityNet | Visual | [Site](http://activity-net.org/) | Unknown | 时序动作定位与视频理解 | [Paper](https://arxiv.org/abs/1505.04582) | 长视频和未裁剪视频时序定位里的经典 benchmark。 |
| 12 | Waymo Open Dataset | Visual | [Site](https://waymo.com/open/) | Custom / terms of use | 自动驾驶感知与轨迹预测 | [Paper](https://arxiv.org/abs/1912.04838) | 现代自动驾驶三维感知研究中最有代表性的数据集之一。 |
| 13 | Video-MME | Visual | [Site](https://video-mme.github.io/home_page.html) | Unknown | 视频 MLLM 评测 | [Paper](https://arxiv.org/abs/2405.21075) | 2024-2026 视频语言模型报告里最常见的一类评测集。 |
| 14 | ScanNet++ | Visual | [Site](https://scannetpp.mlsg.cit.tum.de/scannetpp/) | Unknown | 高保真三维场景理解 | [Paper](https://arxiv.org/abs/2308.11417) | 新一代很强的 3D benchmark，常见于重建、渲染和场景理解论文。 |
| 15 | UCF101 | Visual | [Site](https://www.crcv.ucf.edu/research/data-sets/ucf101/) | Unknown | 裁剪视频动作识别 | [Paper](https://www.crcv.ucf.edu/wp-content/uploads/2019/03/UCF101_CRCV-TR-12-01.pdf) | 最经典、沿用时间也最长的一批动作识别 benchmark 之一。 |
| 16 | NTU RGB+D 120 | Visual + depth + skeleton | [Site](https://rose1.ntu.edu.sg/dataset/actionRecognition/) | Custom / academic non-commercial | 三维人体动作理解 | [Paper](https://arxiv.org/abs/1905.04757) | RGB+D、骨架与多模态动作识别论文里最核心的 benchmark 之一。 |
| 17 | AVA | Visual | [Site](https://research.google.com/ava/download.html) | CC BY 4.0 | 时空动作定位 | [Paper](https://arxiv.org/abs/1705.08421) | 面向电影场景中 person-centric action localization 的高频基准。 |
| 18 | DAVIS | Visual | [Site](https://davischallenge.org/) | Unknown | 视频目标分割 | [Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Perazzi_A_Benchmark_Dataset_CVPR_2016_paper.html) | 半监督和无监督 VOS 论文里几乎绕不开的默认参考数据集。 |
| 19 | ModelNet40 | Visual / 3D CAD | [Site](https://modelnet.cs.princeton.edu/) | Academic research only | 三维物体分类与检索 | [Docs](https://modelnet.cs.princeton.edu/download.html) | 点云与三维形状学习论文中最基础的形状 benchmark 之一。 |
| 20 | Matterport3D | Visual / RGB-D | [Site](https://niessner.github.io/Matterport/) | Custom / terms of use | 室内三维场景理解 | [Paper](https://arxiv.org/abs/1709.06158) | 建筑级 RGB-D 场景数据，常被复用于重建、具身智能与场景推理。 |
| 21 | TUM RGB-D | Visual / RGB-D | [Site](https://cvg.cit.tum.de/data/datasets/rgbd-dataset) | CC BY 4.0 | RGB-D SLAM 与三维重建 | [Paper](https://cvg.cit.tum.de/_media/spezial/bib/sturm12iros.pdf) | 带轨迹、深度与评测工具链的经典 RGB-D benchmark。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [MMMU](https://mmmu-benchmark.github.io/)
- [EgoSchema](https://egoschema.github.io/)
- [GAIA](https://huggingface.co/gaia-benchmark)

## 收录说明

- 本页聚焦通用视频、第一视角、三维场景与形状资源，不再把自动驾驶作为主要整理中心。
- 驾驶专门数据集已经进一步拆分到 [Autonomous-Driving](../Autonomous-Driving/README_ZH.md)。
