# Embodied-AI

Datasets for embodied navigation, language-conditioned task completion, egocentric perception, and generalist robot behavior.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Habitat-Matterport 3D (HM3D) | Visual + 3D scenes | [Site](https://aihabitat.org/datasets/hm3d/) | Custom / non-commercial research | Embodied navigation and 3D scene priors | [Paper](https://arxiv.org/abs/2109.08238) | Large-scale indoor scenes built for Habitat-style embodied training. |
| 2 | ALFRED | Vision + language | [Site](https://askforalfred.com/) | Unknown | Long-horizon household instruction following | [Paper](https://arxiv.org/abs/1912.01734) | One of the canonical embodied instruction-following benchmarks in AI2-THOR. |
| 3 | TEACh | Vision + dialogue | [GitHub](https://github.com/alexa/teach) | CDLA-Sharing 1.0 (data) | Embodied dialogue and interactive task completion | [Paper](https://arxiv.org/abs/2110.00534) | Adds clarifications and multi-turn interaction rather than one-shot instructions only. |
| 4 | BEHAVIOR-1K | Simulation + language | [Site](https://behavior.stanford.edu/behavior-1k) | Unknown | Everyday embodied activities in realistic simulation | [Docs](https://behavior.stanford.edu/behavior-1k) | Broad activity coverage makes it useful for general-purpose embodied evaluation. |
| 5 | Ego4D | Visual | [Site](https://ego4d-data.org/) | Custom | Egocentric perception and skill understanding | [Paper](https://arxiv.org/abs/2110.07058) | Large first-person video benchmark family with strong embodied relevance. |
| 6 | Ego-Exo4D | Visual | [Site](https://ego-exo4d-data.org/) | Custom | First- and third-person skill grounding | [Docs](https://ego-exo4d-data.org/) | Paired ego-exo views help with action grounding and robot learning transfer. |
| 7 | Open X-Embodiment Dataset | Multi-robot trajectories | [Site](https://robotics-transformer-x.github.io/) | Unknown | Cross-robot imitation and generalist policy learning | [Docs](https://robotics-transformer-x.github.io/) | A major multi-institution robot-data mixture behind RT-X style work. |
| 8 | DROID | Robot trajectories | [Site](https://droid-dataset.github.io/) | Unknown | Real-world robot manipulation pretraining | [Docs](https://droid-dataset.github.io/droid/the-droid-dataset) | High-signal real-world data for generalist visuomotor policies. |
| 9 | CALVIN | Multimodal robot data | [GitHub](https://github.com/mees/calvin) | Unknown | Language-conditioned long-horizon manipulation | [Paper](https://arxiv.org/abs/2112.03227) | A standard benchmark for chaining multiple robot skills from language goals. |
| 10 | LIBERO | Manipulation tasks | [Site](https://libero-project.github.io/main.html) | Unknown | Lifelong and compositional robot learning | [Docs](https://libero-project.github.io/main.html) | Common reference point for continual and compositional embodied learning. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [Habitat Challenge](https://aihabitat.org/challenge/)
- [ALFRED](https://askforalfred.com/)
- [TEACh](https://github.com/alexa/teach)

## Selection Note

- This page prioritizes embodied datasets centered on navigation, instruction following, egocentric perception, and language-conditioned behavior.
- Simulator-heavy RL environments and broader robot trajectory resources remain complementary with [Robotics-RL](../Robotics-RL/README.md).
