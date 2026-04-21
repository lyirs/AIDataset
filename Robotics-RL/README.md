# Robotics-RL

Offline RL, robot-learning benchmarks, simulation environments, and control-oriented policy suites for robotics research.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | D4RL | RL trajectories | [GitHub](https://github.com/Farama-Foundation/D4RL) | CC BY 4.0 (datasets) / Apache-2.0 (code) | Offline reinforcement learning | [Paper](https://arxiv.org/abs/2004.07219) | The default anchor benchmark for offline RL comparisons. |
| 2 | RLBench | Multimodal robot demos | [GitHub](https://github.com/stepjam/RLBench) | Unknown | Vision-based robot manipulation | [Paper](https://arxiv.org/abs/1909.12271) | Large task suite built on CoppeliaSim for manipulation learning. |
| 3 | robosuite | Simulation tasks | [Site](https://robosuite.ai/) | Unknown | Modular robot learning simulation and benchmarking | [Paper](https://arxiv.org/abs/2009.12293) | One of the most reused simulation frameworks for robot manipulation and imitation learning. |
| 4 | Meta-World | Simulation tasks | [Site](https://metaworld.farama.org/) | Unknown | Multi-task and meta-RL for manipulation | [Paper](https://arxiv.org/abs/1910.10897) | Canonical benchmark for many-task robotic manipulation learning. |
| 5 | CALVIN | Multimodal robot data | [GitHub](https://github.com/mees/calvin) | Unknown | Long-horizon robot instruction following | [Paper](https://arxiv.org/abs/2112.03227) | Common benchmark for language-conditioned long-horizon manipulation. |
| 6 | LIBERO | Manipulation tasks | [Site](https://libero-project.github.io/main.html) | Unknown | Lifelong and compositional robot learning | [Docs](https://libero-project.github.io/main.html) | Designed for continual learning and task composition in robotics. |
| 7 | ManiSkill | Simulation tasks | [GitHub](https://github.com/haosulab/ManiSkill) | Unknown | Scalable robot learning in simulation | [Docs](https://maniskill.readthedocs.io/en/latest/) | High-throughput manipulation environment family with modern tooling. |
| 8 | RoboHive | Robot-learning environments | [Site](https://sites.google.com/view/robohive/) | Apache-2.0 | Unified benchmark suite for robot learning | [Paper](https://arxiv.org/abs/2310.06828) | Brings together hands, arms, and locomotion-style benchmarks under a single robot-learning framework. |
| 9 | DexArt | Dexterous manipulation benchmark | [Site](https://www.chenbao.tech/dexart/) | Apache-2.0 | Generalizable dexterous manipulation | [Paper](https://arxiv.org/abs/2305.05706) | A standard articulated-object dexterous manipulation benchmark in recent hand-manipulation work. |
| 10 | Isaac Lab | Simulation framework | [Site](https://isaac-sim.github.io/IsaacLab/) | BSD-3-Clause + Apache-2.0 (repo) | GPU-accelerated robot learning workflows | [Paper](https://arxiv.org/abs/2511.04831) | Now a major NVIDIA-backed stack for RL, imitation learning, and sim-to-real robotics research. |
| 11 | MineRL | Game trajectories | [Site](https://minerl.readthedocs.io/en/latest/) | Unknown | Large-scale imitation and RL from Minecraft | [Paper](https://arxiv.org/abs/1907.13440) | A standard long-horizon game environment and dataset for embodied RL. |
| 12 | MimicGen | Simulated robot demos | [Site](https://mimicgen.github.io/) | Unknown | Scalable robot demonstration generation | [Paper](https://arxiv.org/abs/2310.17596) | Generates large demonstration corpora from a small set of human source trajectories. |
| 13 | RoboCasa | Simulation tasks | [GitHub](https://github.com/robocasa/robocasa) | CC BY 4.0 (assets and datasets) / MIT (code) | Everyday-task generalist robot simulation | [Paper](https://arxiv.org/abs/2406.02523) | A high-signal modern benchmark for large-scale household manipulation. |
| 14 | VIMA-Bench | Multimodal robot tasks | [GitHub](https://github.com/vimalabs/VIMABench) | MIT (benchmark repo) | Multimodal prompt-conditioned robot manipulation | [Paper](https://arxiv.org/abs/2210.03094) | A standard benchmark for generalization in prompt-based robot manipulation. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [Robot-Manipulation overview](../Robot-Manipulation/README.md)
- [D4RL](https://github.com/Farama-Foundation/D4RL)
- [Meta-World](https://metaworld.farama.org/)
- [RoboCasa](https://github.com/robocasa/robocasa)
- [robosuite](https://robosuite.ai/)
- [Isaac Lab](https://isaac-sim.github.io/IsaacLab/)

## Selection Note

- This page now prioritizes offline RL anchors, simulation-heavy robot-learning suites, and benchmark-style environments.
- Larger real-world robot trajectory corpora and manipulation data collections are now expanded separately in [Robot-Manipulation](../Robot-Manipulation/README.md).
- Navigation-, instruction-, and egocentric-centered embodied resources are now expanded separately in [Embodied-AI](../Embodied-AI/README.md).
