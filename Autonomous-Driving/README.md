# Autonomous-Driving

Datasets for driving perception, 3D detection, tracking, mapping, forecasting, and cooperative vehicle sensing.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | KITTI | Sensor | [Site](https://www.cvlibs.net/datasets/kitti/) | Custom | Detection, depth, and odometry baselines | [Paper](https://www.cvlibs.net/publications/Geiger2012CVPR.pdf) | The classic self-driving anchor benchmark. |
| 2 | nuScenes | Sensor | [Site](https://www.nuscenes.org/) | Custom | 3D detection and tracking | [Paper](https://arxiv.org/abs/1903.11027) | One of the most widely cited modern multimodal driving datasets. |
| 3 | Waymo Open Dataset | Sensor | [Site](https://waymo.com/open/) | Custom / terms of use | Large-scale perception and forecasting | [Paper](https://arxiv.org/abs/1912.04838) | A default reference point for 3D perception at scale. |
| 4 | Argoverse 2 | Sensor | [Site](https://www.argoverse.org/av2.html) | Unknown | Motion forecasting and map-aware perception | [Paper](https://arxiv.org/abs/2301.00493) | Strong benchmark family for forecasting, tracking, and HD map tasks. |
| 5 | BDD100K | Visual | [Site](https://bdd-data.berkeley.edu/) | Custom | Multi-task street-scene perception | [Paper](https://arxiv.org/abs/1805.04687) | Covers detection, lanes, drivable area, segmentation, and tracking. |
| 6 | PandaSet | Sensor | [Site](https://pandaset.org/) | Custom / terms | Research and commercial-friendly driving perception | [Docs](https://pandaset.org/) | Popular because it is comparatively easy to access for both academia and industry. |
| 7 | A2D2 | Sensor | [Site](https://www.a2d2.audi/a2d2/en.html) | Unknown | Multi-sensor urban scene understanding | [Docs](https://www.a2d2.audi/a2d2/en.html) | Audi's public dataset with cameras, LiDAR, and semantic labels. |
| 8 | ONCE | LiDAR + camera | [Site](https://once-for-auto-driving.github.io/) | Unknown | Large-scale 3D object detection | [Docs](https://once-for-auto-driving.github.io/) | A useful LiDAR-centric alternative to the usual benchmark trio. |
| 9 | CODA | Sensor | [Site](https://coda-dataset.github.io/) | Unknown | Corner cases and long-tail driving scenes | [Docs](https://coda-dataset.github.io/) | Designed to surface rare events that are often missing in cleaner datasets. |
| 10 | DAIR-V2X | Cooperative sensor | [Site](https://thudair.baai.ac.cn/index) | Unknown | Vehicle-infrastructure cooperative perception | [Docs](https://thudair.baai.ac.cn/index) | High-signal benchmark for V2X and cooperative 3D perception. |
| 11 | nuPlan | Sensor + maps | [GitHub](https://github.com/motional/nuplan-devkit) | Unknown | Closed-loop planning and simulation benchmarking | [Paper](https://arxiv.org/abs/2106.11810) | A major missing planning benchmark in modern autonomous-driving papers. |
| 12 | OpenLane-V2 | Sensor + topology | [GitHub](https://github.com/OpenDriveLab/OpenLane-V2) | Unknown | Lane topology and structured road understanding | [Docs](https://github.com/OpenDriveLab/OpenLane-V2) | High-signal benchmark for reasoning over lanes, traffic elements, and topology. |
| 13 | DriveLM | Vision + language | [GitHub](https://github.com/OpenDriveLab/DriveLM) | Unknown | Language-grounded driving reasoning | [Paper](https://arxiv.org/abs/2312.14150) | A canonical benchmark for VLM-style reasoning in driving scenes. |
| 14 | Bench2Drive | Driving benchmark | [Site](https://thinklab-sjtu.github.io/Bench2Drive/) | Unknown | Closed-loop end-to-end driving evaluation | [Paper](https://arxiv.org/abs/2406.03877) | Increasingly common in end-to-end driving and planning comparisons. |
| 15 | SemanticKITTI | LiDAR | [Site](https://semantic-kitti.org/) | CC BY-NC-SA 4.0 | LiDAR semantic segmentation and scene completion | [Paper](https://arxiv.org/abs/1904.01416) | The default LiDAR segmentation benchmark in many autonomous-driving papers. |
| 16 | KITTI-360 | Sensor + 3D scenes | [Site](https://www.cvlibs.net/datasets/kitti-360/) | CC BY-NC-SA 3.0 | Unified 2D/3D urban scene understanding and mapping | [Paper](https://arxiv.org/abs/2109.13410) | A successor-scale extension of KITTI used across perception, mapping, and novel-view tasks. |
| 17 | ApolloScape | Sensor | [GitHub](https://github.com/ApolloScapeAuto/dataset-api) | Unknown | Multi-task driving perception and trajectory prediction | [Paper](https://arxiv.org/abs/1803.06184) | Official toolkit hub for a historically influential large-scale driving dataset family. |
| 18 | Talk2Car | Vision + language | [Site](https://talk2car.github.io/) | CC BY-NC-SA 4.0 | Language-grounded driving command understanding | [Paper](https://arxiv.org/abs/1909.10838) | A canonical benchmark for grounding passenger instructions in real driving scenes. |
| 19 | BDD-X | Vision + language | [GitHub](https://github.com/JinkyuKimUCB/BDD-X-dataset) | Research / educational / non-profit only | Explainable driving decisions and textual rationales | [Paper](https://arxiv.org/abs/1807.11546) | A high-signal benchmark for action explanations and justification in autonomous driving. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [nuScenes Benchmarks](https://www.nuscenes.org/object-detection)
- [Waymo Open Challenges](https://waymo.com/open/challenges/)
- [Argoverse](https://www.argoverse.org/)
- [Bench2Drive](https://thinklab-sjtu.github.io/Bench2Drive/)

## Selection Note

- This page prioritizes datasets that remain central in driving perception, tracking, motion forecasting, HD-map, and cooperative-sensing papers.
- Broader video and 3D resources still remain complementary with [Video-3D](../Video-3D/README.md) and [CV](../CV/README.md).
