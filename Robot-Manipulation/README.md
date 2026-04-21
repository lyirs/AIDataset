# Robot-Manipulation

Real-world robot manipulation datasets, teleoperation corpora, and trajectory collections for imitation learning and generalist visuomotor policies.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | RoboNet | Robot videos + actions | [Site](https://www.robonet.wiki/) | Unknown | Robot learning from large cross-lab data | [Paper](https://arxiv.org/abs/1910.11215) | Collects trajectories from multiple labs and robot platforms. |
| 2 | BridgeData V2 | Robot trajectories | [Site](https://rail-berkeley.github.io/bridgedata/) | Unknown | Generalist visuomotor policy learning | [Docs](https://rail-berkeley.github.io/bridgedata/) | A major real-world manipulation dataset from Berkeley's bridge-data line. |
| 3 | Open X-Embodiment Dataset | Multi-robot trajectories | [Site](https://robotics-transformer-x.github.io/) | Unknown | Cross-robot imitation and generalist robotics models | [Docs](https://robotics-transformer-x.github.io/) | High-signal multi-institution dataset used in RT-X style work. |
| 4 | DROID | Robot trajectories | [Site](https://droid-dataset.github.io/) | Unknown | Large-scale real-world robot manipulation and visuomotor pretraining | [Docs](https://droid-dataset.github.io/droid/the-droid-dataset) | A high-signal real-world manipulation dataset that complements BridgeData V2 and Open X-Embodiment. |
| 5 | RH20T | Multimodal robot trajectories | [Site](https://rh20t.github.io/) | Mixed / CC BY-SA 4.0 + CC BY-NC 4.0 | Contact-rich real-world manipulation | [Paper](https://arxiv.org/abs/2307.00595) | High-signal multimodal dataset with vision, force, audio, and dexterous contact-rich manipulation trajectories. |
| 6 | FMB | Real-world robot manipulation | [Site](https://functional-manipulation-benchmark.github.io/dataset/index.html) | CC BY 4.0 | Functional manipulation benchmarking | [Paper](https://arxiv.org/abs/2401.08553) | A real-world benchmark and dataset built around reusable functional tasks and skill composition. |
| 7 | RoboMIND | Multi-embodiment robot trajectories | [Site](https://x-humanoid-robomind.github.io/) | Unknown | Multi-embodiment manipulation pretraining | [Paper](https://arxiv.org/abs/2412.13877) | A newer large-scale benchmark and dataset spanning multiple embodiments and more than 100k demonstrations. |
| 8 | AgiBot World Colosseo | Robot trajectories | [Site](https://agibot-world.com/) | CC BY-NC-SA 4.0 | Large-scale bimanual manipulation pretraining | [Paper](https://arxiv.org/abs/2503.06669) | A fast-rising large-scale platform and dataset for bimanual embodied manipulation. |
| 9 | robomimic v0.1 | Robot demos | [Site](https://robomimic.github.io/) | Unknown | Offline imitation learning for robot manipulation | [Docs](https://robomimic.github.io/docs/v0.4/datasets/robomimic_v0.1.html) | One of the most common open demonstration datasets in robot imitation-learning papers. |
| 10 | RoboSet | Robot demos | [Site](https://robopen.github.io/roboset/) | Unknown | Real-world robot manipulation demonstrations | [Docs](https://robopen.github.io/roboset/teleoperation.html) | Compact but high-signal teleoperation data used in modern manipulation-policy papers. |
| 11 | FurnitureBench | Real-world robot demos | [GitHub](https://github.com/clvrai/furniture-bench) | MIT (repo) / dataset terms unclear | Long-horizon real-world manipulation benchmarking | [Paper](https://arxiv.org/abs/2305.12821) | A widely cited real-world benchmark for complex furniture-assembly manipulation. |
| 12 | RoboTurk | Robot demos | [Site](https://roboturk.stanford.edu/realrobotdataset.html) | Unknown | Crowdsourced robot teleoperation demonstrations | [Paper](https://arxiv.org/abs/1811.02790) | An early but still influential large-scale human-teleoperated manipulation dataset. |
| 13 | ALOHA | Robot teleoperation + demos | [GitHub](https://github.com/tonyzhaozh/aloha) | MIT | Low-cost bimanual teleoperation and imitation-learning data collection | [Paper](https://arxiv.org/abs/2304.13705) | One of the most cited open low-cost bimanual data-collection systems in recent robot manipulation work. |
| 14 | Language Table | Vision + language + robot trajectories | [GitHub](https://github.com/google-research/language-table) | Apache-2.0 | Language-conditioned tabletop manipulation | [Paper](https://arxiv.org/abs/2210.06407) | A standard dataset and benchmark for open-vocabulary visuolinguomotor learning with language-conditioned manipulation. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [Robotics-RL overview](../Robotics-RL/README.md)
- [Embodied-AI overview](../Embodied-AI/README.md)
- [Open X-Embodiment Dataset](https://robotics-transformer-x.github.io/)
- [DROID](https://droid-dataset.github.io/)
- [RH20T](https://rh20t.github.io/)
- [AgiBot World Colosseo](https://agibot-world.com/)

## Selection Note

- This page emphasizes data-centric robot manipulation resources, especially real-world trajectories, teleoperation corpora, and large-scale visuomotor collections.
- Simulation-heavy RL suites and control-oriented environments remain in [Robotics-RL](../Robotics-RL/README.md).
