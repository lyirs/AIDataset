# 自动驾驶（Autonomous-Driving）

覆盖自动驾驶感知、三维检测、跟踪、地图、轨迹预测与车路协同感知的数据集目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | KITTI | Sensor | [Site](https://www.cvlibs.net/datasets/kitti/) | Custom | 检测、深度与里程计基线 | [Paper](https://www.cvlibs.net/publications/Geiger2012CVPR.pdf) | 自动驾驶研究里最经典的锚点基准。 |
| 2 | nuScenes | Sensor | [Site](https://www.nuscenes.org/) | Custom | 三维检测与跟踪 | [Paper](https://arxiv.org/abs/1903.11027) | 现代多模态自动驾驶数据集中引用频率极高。 |
| 3 | Waymo Open Dataset | Sensor | [Site](https://waymo.com/open/) | Custom / terms of use | 大规模感知与轨迹预测 | [Paper](https://arxiv.org/abs/1912.04838) | 大规模三维感知论文里最常见的参考数据之一。 |
| 4 | Argoverse 2 | Sensor | [Site](https://www.argoverse.org/av2.html) | Unknown | 轨迹预测与地图感知 | [Paper](https://arxiv.org/abs/2301.00493) | 在 forecasting、tracking 和 HD map 任务中都很有代表性。 |
| 5 | BDD100K | Visual | [Site](https://bdd-data.berkeley.edu/) | Custom | 多任务街景感知 | [Paper](https://arxiv.org/abs/1805.04687) | 同时覆盖检测、车道线、可行驶区域、分割与跟踪。 |
| 6 | PandaSet | Sensor | [Site](https://pandaset.org/) | Custom / terms | 学术与工业都常用的驾驶感知 | [Docs](https://pandaset.org/) | 因为获取门槛相对友好，所以被大量用于原型和对比实验。 |
| 7 | A2D2 | Sensor | [Site](https://www.a2d2.audi/a2d2/en.html) | Unknown | 多传感器城市街景理解 | [Docs](https://www.a2d2.audi/a2d2/en.html) | Audi 发布的公开数据，包含相机、LiDAR 与语义标注。 |
| 8 | ONCE | LiDAR + camera | [Site](https://once-for-auto-driving.github.io/) | Unknown | 大规模三维目标检测 | [Docs](https://once-for-auto-driving.github.io/) | 在常见 benchmark 三件套之外，属于很有价值的 LiDAR 资源。 |
| 9 | CODA | Sensor | [Site](https://coda-dataset.github.io/) | Unknown | 长尾与 corner-case 驾驶场景 | [Docs](https://coda-dataset.github.io/) | 专门强调稀有场景和困难样本。 |
| 10 | DAIR-V2X | Cooperative sensor | [Site](https://thudair.baai.ac.cn/index) | Unknown | 车路协同感知 | [Docs](https://thudair.baai.ac.cn/index) | V2X 与协同三维感知方向的高信号基准。 |
| 11 | nuPlan | Sensor + maps | [GitHub](https://github.com/motional/nuplan-devkit) | Unknown | 闭环规划与仿真评测 | [Paper](https://arxiv.org/abs/2106.11810) | 现代自动驾驶论文里非常重要、但之前缺失的 planning benchmark。 |
| 12 | OpenLane-V2 | Sensor + topology | [GitHub](https://github.com/OpenDriveLab/OpenLane-V2) | Unknown | 车道拓扑与结构化道路理解 | [Docs](https://github.com/OpenDriveLab/OpenLane-V2) | 面向车道、交通元素与拓扑关系推理的高信号 benchmark。 |
| 13 | DriveLM | Vision + language | [GitHub](https://github.com/OpenDriveLab/DriveLM) | Unknown | 语言驱动的自动驾驶场景推理 | [Paper](https://arxiv.org/abs/2312.14150) | 自动驾驶场景中的 VLM 推理 benchmark 里最常见的一类资源。 |
| 14 | Bench2Drive | Driving benchmark | [Site](https://thinklab-sjtu.github.io/Bench2Drive/) | Unknown | 闭环端到端驾驶评测 | [Paper](https://arxiv.org/abs/2406.03877) | 在 end-to-end driving 和 planning 对比中越来越常见。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [nuScenes Benchmarks](https://www.nuscenes.org/object-detection)
- [Waymo Open Challenges](https://waymo.com/open/challenges/)
- [Argoverse](https://www.argoverse.org/)
- [Bench2Drive](https://thinklab-sjtu.github.io/Bench2Drive/)

## 收录说明

- 本页优先覆盖在自动驾驶感知、跟踪、轨迹预测、高清地图与协同感知论文中长期高频出现的数据集。
- 更广义的视频、三维和街景视觉资源仍建议与 [Video-3D](../Video-3D/README_ZH.md) 和 [CV](../CV/README_ZH.md) 结合查看。
