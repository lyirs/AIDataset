# 机器人与强化学习（Robotics-RL）

覆盖离线强化学习、机器人学习 benchmark、仿真环境与控制导向策略套件的数据目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | D4RL | RL trajectories | [GitHub](https://github.com/Farama-Foundation/D4RL) | CC BY 4.0 (datasets) / Apache-2.0 (code) | 离线强化学习 | [Paper](https://arxiv.org/abs/2004.07219) | 离线 RL 对比里最常见的标准锚点基准。 |
| 2 | RLBench | Multimodal robot demos | [GitHub](https://github.com/stepjam/RLBench) | Unknown | 视觉机器人操作 | [Paper](https://arxiv.org/abs/1909.12271) | 基于 CoppeliaSim 的大规模机器人任务套件。 |
| 3 | robosuite | Simulation tasks | [Site](https://robosuite.ai/) | Unknown | 模块化机器人学习仿真与评测 | [Paper](https://arxiv.org/abs/2009.12293) | 它是机器人操作与模仿学习里最常被复用的仿真框架之一。 |
| 4 | Meta-World | Simulation tasks | [Site](https://metaworld.farama.org/) | Unknown | 多任务与元强化学习操作 | [Paper](https://arxiv.org/abs/1910.10897) | 机器人多任务操作学习中最经典的数据与环境之一。 |
| 5 | CALVIN | Multimodal robot data | [GitHub](https://github.com/mees/calvin) | Unknown | 长时程机器人指令执行 | [Paper](https://arxiv.org/abs/2112.03227) | 语言条件长序列操作任务里的经典基准。 |
| 6 | LIBERO | Manipulation tasks | [Site](https://libero-project.github.io/main.html) | Unknown | 持续学习与组合式机器人学习 | [Docs](https://libero-project.github.io/main.html) | 面向 continual learning 和 task composition 设计。 |
| 7 | ManiSkill | Simulation tasks | [GitHub](https://github.com/haosulab/ManiSkill) | Unknown | 大规模仿真机器人学习 | [Docs](https://maniskill.readthedocs.io/en/latest/) | 现代机器人操作仿真环境中的高吞吐代表。 |
| 8 | RoboHive | Robot-learning environments | [Site](https://sites.google.com/view/robohive/) | Apache-2.0 | 统一机器人学习 benchmark 套件 | [Paper](https://arxiv.org/abs/2310.06828) | 它把灵巧手、机械臂和更多机器人学习环境整合进一套统一框架。 |
| 9 | DexArt | Dexterous manipulation benchmark | [Site](https://www.chenbao.tech/dexart/) | Apache-2.0 | 可泛化灵巧手操作 | [Paper](https://arxiv.org/abs/2305.05706) | 它是近年灵巧手操作与 articulated object benchmark 中最常见的一类资源。 |
| 10 | Isaac Lab | Simulation framework | [Site](https://isaac-sim.github.io/IsaacLab/) | BSD-3-Clause + Apache-2.0 (repo) | GPU 加速机器人学习流程 | [Paper](https://arxiv.org/abs/2511.04831) | 它已成为 NVIDIA 路线下 RL、模仿学习与 sim-to-real 研究的重要基础设施。 |
| 11 | MineRL | Game trajectories | [Site](https://minerl.readthedocs.io/en/latest/) | Unknown | Minecraft 中的大规模模仿学习与 RL | [Paper](https://arxiv.org/abs/1907.13440) | 长时程游戏环境和具身 RL 里非常经典的资源。 |
| 12 | MimicGen | Simulated robot demos | [Site](https://mimicgen.github.io/) | Unknown | 可扩展机器人示范数据生成 | [Paper](https://arxiv.org/abs/2310.17596) | 它能从少量人工轨迹自动扩展出更大规模的机器人示范数据。 |
| 13 | RoboCasa | Simulation tasks | [GitHub](https://github.com/robocasa/robocasa) | CC BY 4.0 (assets and datasets) / MIT (code) | 日常家庭任务的通用机器人仿真 | [Paper](https://arxiv.org/abs/2406.02523) | 它是近两年最有代表性的家庭场景大规模机器人操作 benchmark 之一。 |
| 14 | VIMA-Bench | Multimodal robot tasks | [GitHub](https://github.com/vimalabs/VIMABench) | MIT (benchmark repo) | 多模态提示条件机器人操作 | [Paper](https://arxiv.org/abs/2210.03094) | 它是评测 prompt-based robot manipulation 泛化能力时最常见的 benchmark 之一。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [Robot-Manipulation 总览](../Robot-Manipulation/README_ZH.md)
- [D4RL](https://github.com/Farama-Foundation/D4RL)
- [Meta-World](https://metaworld.farama.org/)
- [RoboCasa](https://github.com/robocasa/robocasa)
- [robosuite](https://robosuite.ai/)
- [Isaac Lab](https://isaac-sim.github.io/IsaacLab/)

## 收录说明

- 本页现在更强调离线 RL 锚点、仿真环境以及 benchmark 式机器人学习资源。
- 更大规模的真实机器人轨迹语料和操作数据集，现已单独扩展到 [Robot-Manipulation](../Robot-Manipulation/README_ZH.md)。
- 更偏导航、指令执行和第一视角感知的具身资源，现已单独扩展到 [Embodied-AI](../Embodied-AI/README_ZH.md)。
