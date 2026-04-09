# Robotics-RL

Offline RL, robot manipulation, trajectory data, and simulation environments for robotics learning.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | D4RL | RL trajectories | [GitHub](https://github.com/Farama-Foundation/D4RL) | CC BY 4.0 (datasets) / Apache-2.0 (code) | Offline reinforcement learning | [Paper](https://arxiv.org/abs/2004.07219) | The default anchor benchmark for offline RL comparisons. |
| 2 | RLBench | Multimodal robot demos | [GitHub](https://github.com/stepjam/RLBench) | Unknown | Vision-based robot manipulation | [Paper](https://arxiv.org/abs/1909.12271) | Large task suite built on CoppeliaSim for manipulation learning. |
| 3 | Meta-World | Simulation tasks | [Site](https://metaworld.farama.org/) | Unknown | Multi-task and meta-RL for manipulation | [Paper](https://arxiv.org/abs/1910.10897) | Canonical benchmark for many-task robotic manipulation learning. |
| 4 | RoboNet | Robot videos + actions | [Site](https://www.robonet.wiki/) | Unknown | Robot learning from large cross-lab data | [Paper](https://arxiv.org/abs/1910.11215) | Collects trajectories from multiple labs and robot platforms. |
| 5 | BridgeData V2 | Robot trajectories | [Site](https://rail-berkeley.github.io/bridgedata/) | Unknown | Generalist visuomotor policy learning | [Docs](https://rail-berkeley.github.io/bridgedata/) | A major real-world manipulation dataset from Berkeley's bridge-data line. |
| 6 | Open X-Embodiment Dataset | Multi-robot trajectories | [Site](https://robotics-transformer-x.github.io/) | Unknown | Cross-robot imitation and generalist robotics models | [Docs](https://robotics-transformer-x.github.io/) | High-signal multi-institution dataset used in RT-X style work. |
| 7 | CALVIN | Multimodal robot data | [GitHub](https://github.com/mees/calvin) | Unknown | Long-horizon robot instruction following | [Paper](https://arxiv.org/abs/2112.03227) | Common benchmark for language-conditioned long-horizon manipulation. |
| 8 | LIBERO | Manipulation tasks | [Site](https://libero-project.github.io/main.html) | Unknown | Lifelong and compositional robot learning | [Docs](https://libero-project.github.io/main.html) | Designed for continual learning and task composition in robotics. |
| 9 | ManiSkill | Simulation tasks | [GitHub](https://github.com/haosulab/ManiSkill) | Unknown | Scalable robot learning in simulation | [Docs](https://maniskill.readthedocs.io/en/latest/) | High-throughput manipulation environment family with modern tooling. |
| 10 | MineRL | Game trajectories | [Site](https://minerl.readthedocs.io/en/latest/) | Unknown | Large-scale imitation and RL from Minecraft | [Paper](https://arxiv.org/abs/1907.13440) | A standard long-horizon game environment and dataset for embodied RL. |
| 11 | DROID | Robot trajectories | [Site](https://droid-dataset.github.io/) | Unknown | Large-scale real-world robot manipulation and visuomotor pretraining | [Docs](https://droid-dataset.github.io/droid/the-droid-dataset) | A high-signal real-world manipulation dataset that complements BridgeData V2 and Open X-Embodiment. |
| 12 | robomimic v0.1 | Robot demos | [Site](https://robomimic.github.io/) | Unknown | Offline imitation learning for robot manipulation | [Docs](https://robomimic.github.io/docs/v0.4/datasets/robomimic_v0.1.html) | One of the most common open demonstration datasets in robot imitation-learning papers. |
| 13 | RoboSet | Robot demos | [Site](https://robopen.github.io/roboset/) | Unknown | Real-world robot manipulation demonstrations | [Docs](https://robopen.github.io/roboset/teleoperation.html) | Compact but high-signal teleoperation data used in modern manipulation-policy papers. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [D4RL](https://github.com/Farama-Foundation/D4RL)
- [Open X-Embodiment](https://robotics-transformer-x.github.io/)
- [Meta-World](https://metaworld.farama.org/)

## Selection Note

- This page includes both trajectory datasets and task environments because robotics and RL work is often organized around datasets plus simulators together.
- Preference is given to resources that remain standard in offline RL, imitation learning, robot manipulation, and embodied policy papers.
- Navigation-, instruction-, and egocentric-centered embodied resources are now expanded separately in [Embodied-AI](../Embodied-AI/README.md).
