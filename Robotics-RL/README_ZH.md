# 机器人与强化学习（Robotics-RL）

覆盖离线强化学习、机器人学习 benchmark、仿真环境与控制导向策略套件的数据目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | D4RL | RL trajectories | [GitHub](https://github.com/Farama-Foundation/D4RL) | CC BY 4.0 (datasets) / Apache-2.0 (code) | 离线强化学习 | [Paper](https://arxiv.org/abs/2004.07219) | 离线 RL 对比里最常见的标准锚点基准。 |
| 2 | RLBench | Multimodal robot demos | [GitHub](https://github.com/stepjam/RLBench) | Unknown | 视觉机器人操作 | [Paper](https://arxiv.org/abs/1909.12271) | 基于 CoppeliaSim 的大规模机器人任务套件。 |
| 3 | Meta-World | Simulation tasks | [Site](https://metaworld.farama.org/) | Unknown | 多任务与元强化学习操作 | [Paper](https://arxiv.org/abs/1910.10897) | 机器人多任务操作学习中最经典的数据与环境之一。 |
| 4 | CALVIN | Multimodal robot data | [GitHub](https://github.com/mees/calvin) | Unknown | 长时程机器人指令执行 | [Paper](https://arxiv.org/abs/2112.03227) | 语言条件长序列操作任务里的经典基准。 |
| 5 | LIBERO | Manipulation tasks | [Site](https://libero-project.github.io/main.html) | Unknown | 持续学习与组合式机器人学习 | [Docs](https://libero-project.github.io/main.html) | 面向 continual learning 和 task composition 设计。 |
| 6 | ManiSkill | Simulation tasks | [GitHub](https://github.com/haosulab/ManiSkill) | Unknown | 大规模仿真机器人学习 | [Docs](https://maniskill.readthedocs.io/en/latest/) | 现代机器人操作仿真环境中的高吞吐代表。 |
| 7 | MineRL | Game trajectories | [Site](https://minerl.readthedocs.io/en/latest/) | Unknown | Minecraft 中的大规模模仿学习与 RL | [Paper](https://arxiv.org/abs/1907.13440) | 长时程游戏环境和具身 RL 里非常经典的资源。 |
| 8 | MimicGen | Simulated robot demos | [Site](https://mimicgen.github.io/) | Unknown | 可扩展机器人示范数据生成 | [Paper](https://arxiv.org/abs/2310.17596) | 它能从少量人工轨迹自动扩展出更大规模的机器人示范数据。 |
| 9 | RoboCasa | Simulation tasks | [GitHub](https://github.com/robocasa/robocasa) | CC BY 4.0 (assets and datasets) / MIT (code) | 日常家庭任务的通用机器人仿真 | [Paper](https://arxiv.org/abs/2406.02523) | 它是近两年最有代表性的家庭场景大规模机器人操作 benchmark 之一。 |
| 10 | VIMA-Bench | Multimodal robot tasks | [GitHub](https://github.com/vimalabs/VIMABench) | MIT (benchmark repo) | 多模态提示条件机器人操作 | [Paper](https://arxiv.org/abs/2210.03094) | 它是评测 prompt-based robot manipulation 泛化能力时最常见的 benchmark 之一。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [Robot-Manipulation 总览](../Robot-Manipulation/README_ZH.md)
- [D4RL](https://github.com/Farama-Foundation/D4RL)
- [Meta-World](https://metaworld.farama.org/)
- [RoboCasa](https://github.com/robocasa/robocasa)

## 收录说明

- 本页现在更强调离线 RL 锚点、仿真环境以及 benchmark 式机器人学习资源。
- 更大规模的真实机器人轨迹语料和操作数据集，现已单独扩展到 [Robot-Manipulation](../Robot-Manipulation/README_ZH.md)。
- 更偏导航、指令执行和第一视角感知的具身资源，现已单独扩展到 [Embodied-AI](../Embodied-AI/README_ZH.md)。
