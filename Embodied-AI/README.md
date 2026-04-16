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
| 11 | Matterport3D | Visual + 3D scenes | [Site](https://niessner.github.io/Matterport/) | Custom / access agreement | Indoor 3D scene understanding and embodied pretraining | [Paper](https://arxiv.org/abs/1709.06158) | Foundational scanned-environment dataset behind many later embodied and 3D benchmarks. |
| 12 | Room-to-Room (R2R) | Vision + language | [Site](https://bringmeaspoon.org/) | Mixed / task data + Matterport terms | Vision-language navigation in real buildings | [Paper](https://arxiv.org/abs/1711.07280) | The canonical VLN benchmark built on Matterport3D scenes. |
| 13 | Room-Across-Room (RxR) | Multilingual vision + language | [GitHub](https://github.com/google-research-datasets/RxR) | CC BY 4.0 | Multilingual and densely grounded vision-language navigation | [Paper](https://arxiv.org/abs/2010.07954) | Extends VLN beyond English with longer instructions and denser temporal grounding. |
| 14 | CVDN | Vision + dialogue | [GitHub](https://github.com/mmurray/cvdn) | Mixed / dialog data + Matterport terms | Cooperative embodied dialogue navigation | [Paper](https://arxiv.org/abs/1907.04957) | A canonical benchmark for multi-turn embodied dialogue grounded in navigation. |
| 15 | Touchdown | Vision + language | [GitHub](https://github.com/lil-lab/touchdown) | CC BY 4.0 | Street-view navigation and spatial reasoning | [Paper](https://arxiv.org/abs/1811.12354) | A standard outdoor language-navigation benchmark beyond indoor Matterport-style settings. |
| 16 | ProcTHOR | 3D scenes + simulation | [Site](https://procthor.allenai.org/) | Apache-2.0 (repo) | Large-scale procedurally generated embodied environments | [Paper](https://arxiv.org/abs/2206.06994) | Commonly cited as the scalable data engine behind newer embodied training and evaluation pipelines. |
| 17 | REVERIE | Vision + language | [GitHub](https://github.com/YuankaiQi/REVERIE) | Unknown | Embodied object grounding plus navigation | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Qi_REVERIE_Remote_Embodied_Visual_Referring_Expression_in_Real_Indoor_Environments_CVPR_2020_paper.pdf) | A canonical benchmark where an agent must navigate and identify a referred object in Matterport scenes. |
| 18 | ScanRefer | Vision + language + 3D | [GitHub](https://github.com/daveredrum/ScanRefer) | CC BY-NC-SA 3.0 | 3D visual grounding from natural language | [Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/3408_ECCV_2020_paper.php) | A foundational language-grounded 3D localization benchmark built on ScanNet. |
| 19 | ScanQA | Vision + language + 3D | [GitHub](https://github.com/ATR-DBI/ScanQA) | CC BY-NC-SA 3.0 | Embodied and 3D scene question answering | [Paper](https://arxiv.org/abs/2112.10482) | A standard 3D QA benchmark for spatial reasoning over indoor RGB-D scenes. |
| 20 | OpenEQA | Vision + language | [GitHub](https://github.com/facebookresearch/open-eqa) | MIT | Embodied question answering with exploration or episodic memory | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Majumdar_OpenEQA_Embodied_Question_Answering_in_the_Era_of_Foundation_Models_CVPR_2024_paper.html) | A strong modern benchmark for foundation models answering questions about environments they explore or observe. |
| 21 | EmbodiedScan | Ego-centric RGB-D + language | [GitHub](https://github.com/InternRobotics/EmbodiedScan) | CC BY-NC-SA 4.0 | Holistic 3D embodied perception and language grounding | [Paper](https://arxiv.org/abs/2312.16170) | One of the most complete recent ego-centric 3D perception suites for embodied AI. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [Habitat Challenge](https://aihabitat.org/challenge/)
- [ALFRED](https://askforalfred.com/)
- [TEACh](https://github.com/alexa/teach)
- [OpenEQA](https://github.com/facebookresearch/open-eqa)

## Selection Note

- This page prioritizes embodied datasets centered on navigation, instruction following, egocentric perception, and language-conditioned behavior.
- Simulator-heavy RL environments and broader robot trajectory resources remain complementary with [Robotics-RL](../Robotics-RL/README.md).
