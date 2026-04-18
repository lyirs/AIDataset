# 机器人操作（Robot-Manipulation）

覆盖真实机器人操作数据、遥操作语料与轨迹集合的数据目录，重点服务于模仿学习和通用视觉运动策略。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | RoboNet | Robot videos + actions | [Site](https://www.robonet.wiki/) | Unknown | 跨实验室机器人学习 | [Paper](https://arxiv.org/abs/1910.11215) | 汇集多个实验室与平台的真实机器人轨迹。 |
| 2 | BridgeData V2 | Robot trajectories | [Site](https://rail-berkeley.github.io/bridgedata/) | Unknown | 通用视觉运动策略学习 | [Docs](https://rail-berkeley.github.io/bridgedata/) | Berkeley bridge-data 系列中高频使用的真实操作数据。 |
| 3 | Open X-Embodiment Dataset | Multi-robot trajectories | [Site](https://robotics-transformer-x.github.io/) | Unknown | 跨机器人模仿学习与通用机器人模型 | [Docs](https://robotics-transformer-x.github.io/) | RT-X 风格工作中最有代表性的多机构开放数据集之一。 |
| 4 | DROID | Robot trajectories | [Site](https://droid-dataset.github.io/) | Unknown | 大规模真实机器人操作与视觉运动预训练 | [Docs](https://droid-dataset.github.io/droid/the-droid-dataset) | 面向通用机器人学习的高信号真实轨迹数据，可与 BridgeData V2 和 Open X-Embodiment 互补。 |
| 5 | robomimic v0.1 | Robot demos | [Site](https://robomimic.github.io/) | Unknown | 机器人操作的离线模仿学习 | [Docs](https://robomimic.github.io/docs/v0.4/datasets/robomimic_v0.1.html) | 离线模仿学习论文里最常出现的人类示范数据家族之一。 |
| 6 | RoboSet | Robot demos | [Site](https://robopen.github.io/roboset/) | Unknown | 真实机器人操作示范 | [Docs](https://robopen.github.io/roboset/teleoperation.html) | 规模不算最大，但在近期 manipulation policy 论文里是高信号真实遥操作数据。 |
| 7 | FurnitureBench | Real-world robot demos | [GitHub](https://github.com/clvrai/furniture-bench) | MIT (repo) / dataset terms unclear | 长时程真实机器人操作评测 | [Paper](https://arxiv.org/abs/2305.12821) | 它是复杂家具装配类真实机器人长任务 benchmark 中最常被引用的一类资源。 |
| 8 | RoboTurk | Robot demos | [Site](https://roboturk.stanford.edu/realrobotdataset.html) | Unknown | 众包遥操作机器人示范 | [Paper](https://arxiv.org/abs/1811.02790) | 这是早期但影响很大的大规模遥操作机器人示范数据集。 |
| 9 | ALOHA | Robot teleoperation + demos | [GitHub](https://github.com/tonyzhaozh/aloha) | MIT | 低成本双臂遥操作与模仿学习数据采集 | [Paper](https://arxiv.org/abs/2304.13705) | 它是近两年最常被引用的开放低成本双臂数据采集系统之一。 |
| 10 | Language Table | Vision + language + robot trajectories | [GitHub](https://github.com/google-research/language-table) | Apache-2.0 | 语言条件桌面操作 | [Paper](https://arxiv.org/abs/2210.06407) | 它是开放词汇 visuolinguomotor learning 和语言条件机器人操作里的标准数据集与 benchmark。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [Robotics-RL 总览](../Robotics-RL/README_ZH.md)
- [Embodied-AI 总览](../Embodied-AI/README_ZH.md)
- [Open X-Embodiment Dataset](https://robotics-transformer-x.github.io/)
- [DROID](https://droid-dataset.github.io/)

## 收录说明

- 本页更强调数据导向的机器人操作资源，尤其是真实轨迹、遥操作语料和大规模视觉运动数据集。
- 更偏仿真、离线 RL 和控制评测的资源仍然保留在 [Robotics-RL](../Robotics-RL/README_ZH.md)。
