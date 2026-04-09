# 机器人与强化学习（Robotics-RL）

覆盖离线强化学习、机器人操作、轨迹与仿真环境的数据目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | D4RL | RL trajectories | [GitHub](https://github.com/Farama-Foundation/D4RL) | CC BY 4.0 (datasets) / Apache-2.0 (code) | 离线强化学习 | [Paper](https://arxiv.org/abs/2004.07219) | 离线 RL 对比里最常见的标准锚点基准。 |
| 2 | RLBench | Multimodal robot demos | [GitHub](https://github.com/stepjam/RLBench) | Unknown | 视觉机器人操作 | [Paper](https://arxiv.org/abs/1909.12271) | 基于 CoppeliaSim 的大规模机器人任务套件。 |
| 3 | Meta-World | Simulation tasks | [Site](https://metaworld.farama.org/) | Unknown | 多任务与元强化学习操作 | [Paper](https://arxiv.org/abs/1910.10897) | 机器人多任务操作学习中最经典的数据与环境之一。 |
| 4 | RoboNet | Robot videos + actions | [Site](https://www.robonet.wiki/) | Unknown | 跨实验室机器人学习 | [Paper](https://arxiv.org/abs/1910.11215) | 汇集多个实验室与平台的真实机器人轨迹。 |
| 5 | BridgeData V2 | Robot trajectories | [Site](https://rail-berkeley.github.io/bridgedata/) | Unknown | 通用视觉运动策略学习 | [Docs](https://rail-berkeley.github.io/bridgedata/) | Berkeley bridge-data 系列中高频使用的真实操作数据。 |
| 6 | Open X-Embodiment Dataset | Multi-robot trajectories | [Site](https://robotics-transformer-x.github.io/) | Unknown | 跨机器人模仿学习与通用机器人模型 | [Docs](https://robotics-transformer-x.github.io/) | RT-X 风格工作中最有代表性的多机构开放数据集之一。 |
| 7 | CALVIN | Multimodal robot data | [GitHub](https://github.com/mees/calvin) | Unknown | 长时程机器人指令执行 | [Paper](https://arxiv.org/abs/2112.03227) | 语言条件长序列操作任务里的经典基准。 |
| 8 | LIBERO | Manipulation tasks | [Site](https://libero-project.github.io/main.html) | Unknown | 持续学习与组合式机器人学习 | [Docs](https://libero-project.github.io/main.html) | 面向 continual learning 和 task composition 设计。 |
| 9 | ManiSkill | Simulation tasks | [GitHub](https://github.com/haosulab/ManiSkill) | Unknown | 大规模仿真机器人学习 | [Docs](https://maniskill.readthedocs.io/en/latest/) | 现代机器人操作仿真环境中的高吞吐代表。 |
| 10 | MineRL | Game trajectories | [Site](https://minerl.readthedocs.io/en/latest/) | Unknown | Minecraft 中的大规模模仿学习与 RL | [Paper](https://arxiv.org/abs/1907.13440) | 长时程游戏环境和具身 RL 里非常经典的资源。 |
| 11 | DROID | Robot trajectories | [Site](https://droid-dataset.github.io/) | Unknown | 大规模真实机器人操作与视觉运动预训练 | [Docs](https://droid-dataset.github.io/droid/the-droid-dataset) | 面向通用机器人学习的高信号真实轨迹数据，可与 BridgeData V2 和 Open X-Embodiment 互补。 |
| 12 | robomimic v0.1 | Robot demos | [Site](https://robomimic.github.io/) | Unknown | 机器人操作的离线模仿学习 | [Docs](https://robomimic.github.io/docs/v0.4/datasets/robomimic_v0.1.html) | 离线模仿学习论文里最常出现的人类示范数据家族之一。 |
| 13 | RoboSet | Robot demos | [Site](https://robopen.github.io/roboset/) | Unknown | 真实机器人操作示范 | [Docs](https://robopen.github.io/roboset/teleoperation.html) | 规模不算最大，但在近期 manipulation policy 论文里是高信号真实遥操作数据。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [D4RL](https://github.com/Farama-Foundation/D4RL)
- [Open X-Embodiment](https://robotics-transformer-x.github.io/)
- [Meta-World](https://metaworld.farama.org/)

## 收录说明

- 本页同时收录轨迹数据与任务环境，因为机器人和 RL 研究往往本来就是“数据集 + 仿真器/环境”一起定义的。
- 优先覆盖在离线 RL、模仿学习、机器人操作与具身策略论文中长期高频使用的资源。
- 更偏导航、指令执行和第一视角感知的具身资源，现已单独扩展到 [Embodied-AI](../Embodied-AI/README_ZH.md)。
