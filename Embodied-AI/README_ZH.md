# 具身智能（Embodied-AI）

覆盖具身导航、语言条件任务执行、第一视角感知与通用机器人行为的数据集目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Habitat-Matterport 3D (HM3D) | Visual + 3D scenes | [Site](https://aihabitat.org/datasets/hm3d/) | Custom / non-commercial research | 具身导航与三维场景先验 | [Paper](https://arxiv.org/abs/2109.08238) | 面向 Habitat 系具身训练的大规模室内三维场景数据。 |
| 2 | ALFRED | Vision + language | [Site](https://askforalfred.com/) | Unknown | 长时程家庭环境指令执行 | [Paper](https://arxiv.org/abs/1912.01734) | AI2-THOR 体系里最经典的具身指令跟随基准之一。 |
| 3 | TEACh | Vision + dialogue | [GitHub](https://github.com/alexa/teach) | CDLA-Sharing 1.0 (data) | 具身对话与交互式任务完成 | [Paper](https://arxiv.org/abs/2110.00534) | 不只是一条指令，而是加入澄清与多轮交互。 |
| 4 | BEHAVIOR-1K | Simulation + language | [Site](https://behavior.stanford.edu/behavior-1k) | Unknown | 真实日常活动的具身仿真 | [Docs](https://behavior.stanford.edu/behavior-1k) | 活动覆盖面很广，适合通用具身评测。 |
| 5 | Ego4D | Visual | [Site](https://ego4d-data.org/) | Custom | 第一视角感知与技能理解 | [Paper](https://arxiv.org/abs/2110.07058) | 具身感知研究里最有代表性的第一视角视频数据家族之一。 |
| 6 | Ego-Exo4D | Visual | [Site](https://ego-exo4d-data.org/) | Custom | 第一/第三视角技能对齐 | [Docs](https://ego-exo4d-data.org/) | 配对的 ego-exo 视角有利于动作 grounding 与机器人迁移。 |
| 7 | Open X-Embodiment Dataset | Multi-robot trajectories | [Site](https://robotics-transformer-x.github.io/) | Unknown | 跨机器人模仿学习与通用策略学习 | [Docs](https://robotics-transformer-x.github.io/) | RT-X 风格工作背后最关键的多机构机器人数据混合之一。 |
| 8 | DROID | Robot trajectories | [Site](https://droid-dataset.github.io/) | Unknown | 真实机器人操作预训练 | [Docs](https://droid-dataset.github.io/droid/the-droid-dataset) | 面向通用 visuomotor policy 的高信号真实操作数据。 |
| 9 | CALVIN | Multimodal robot data | [GitHub](https://github.com/mees/calvin) | Unknown | 语言条件长时程操作 | [Paper](https://arxiv.org/abs/2112.03227) | 用语言目标串联多个机器人技能的经典基准。 |
| 10 | LIBERO | Manipulation tasks | [Site](https://libero-project.github.io/main.html) | Unknown | 持续学习与组合式机器人学习 | [Docs](https://libero-project.github.io/main.html) | 在 continual 与 compositional embodied learning 中很常见。 |
| 11 | Matterport3D | Visual + 3D scenes | [Site](https://niessner.github.io/Matterport/) | Custom / access agreement | 室内三维场景理解与具身预训练 | [Paper](https://arxiv.org/abs/1709.06158) | 后续很多具身智能与三维场景 benchmark 都建立在它之上。 |
| 12 | Room-to-Room (R2R) | Vision + language | [Site](https://bringmeaspoon.org/) | Mixed / task data + Matterport terms | 真实建筑中的视觉语言导航 | [Paper](https://arxiv.org/abs/1711.07280) | 它几乎就是 VLN 方向里最 canonical 的 benchmark。 |
| 13 | Room-Across-Room (RxR) | Multilingual vision + language | [GitHub](https://github.com/google-research-datasets/RxR) | CC BY 4.0 | 多语言且密集标注的视觉语言导航 | [Paper](https://arxiv.org/abs/2010.07954) | 它把 VLN 从英文扩展到了多语言，并显著强化了时序 grounding。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [Habitat Challenge](https://aihabitat.org/challenge/)
- [ALFRED](https://askforalfred.com/)
- [TEACh](https://github.com/alexa/teach)

## 收录说明

- 本页优先覆盖导航、指令执行、第一视角感知和语言条件行为等具身智能核心数据集。
- 更偏模拟器、离线 RL 与机器人轨迹的大类资源仍可与 [Robotics-RL](../Robotics-RL/README_ZH.md) 互补查看。
