# 音频理解（Audio-Understanding）

覆盖声音事件识别、音频描述、音频语言学习与通用音频基础模型评测的数据目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | AudioSet | Audio | [Site](https://research.google.com/audioset/) | Custom | 大规模音频事件识别 | [Paper](https://arxiv.org/abs/1709.04396) | 音频事件学习里最基础、最具代表性的大规模弱标注数据集。 |
| 2 | FSD50K | Audio | [Site](https://zenodo.org/records/4060432) | Mixed / clip-specific CC + dataset CC BY | 声音事件分类 | [Paper](https://arxiv.org/abs/2010.00475) | 通用音频表征学习和 sound event tagging 里很高频的 benchmark。 |
| 3 | ESC-50 | Audio | [GitHub](https://github.com/karolpiczak/ESC-50) | CC BY-NC | 环境声音分类 | [Paper](https://dl.acm.org/doi/10.1145/2733373.2806390) | 小规模音频分类里几乎人人都会拿来比较的经典基准。 |
| 4 | UrbanSound8K | Audio | [Site](https://urbansounddataset.weebly.com/urbansound8k.html) | Unknown | 城市场景与环境声音分类 | [Docs](https://urbansounddataset.weebly.com/urbansound8k.html) | 环境音和城市声音识别里长期高频使用的经典数据集。 |
| 5 | VGGSound | Audio + video | [Site](https://www.robots.ox.ac.uk/~vgg/data/vggsound/) | CC BY 4.0 | 大规模野外音频识别 | [Paper](https://www.robots.ox.ac.uk/~vgg/publications/2020/Chen20/chen20.pdf) | 大类别音频识别里非常常见，也适合做音视频 grounding。 |
| 6 | Clotho | English | [Site](https://zenodo.org/records/3490684) | Mixed / source-specific + non-commercial captions | 音频描述与音频文本检索 | [Paper](https://arxiv.org/abs/1910.09387) | 音频描述方向的核心数据集之一，也在检索页交叉收录。 |
| 7 | AudioCaps | English | [Site](https://audiocaps.github.io/) | Unknown | 音频描述与音频语言 grounding | [Docs](https://audiocaps.github.io/) | 音频语言研究里最标准的两大 captioning 数据集之一。 |
| 8 | WavCaps | English | [GitHub](https://github.com/XinhaoMei/WavCaps) | Academic-only / source-specific | 大规模音频语言预训练 | [Paper](https://arxiv.org/abs/2303.17395) | 面向 audio-language 多模态学习的高信号弱标注 caption 数据集。 |
| 9 | AIR-Bench | Audio + language | [GitHub](https://github.com/OFA-Sys/AIR-Bench) | Unknown | 音频语言模型评测 | [Paper](https://arxiv.org/abs/2402.07729) | 近两年音频 foundation model 和 chat-style audio model 常见的强 benchmark。 |
| 10 | MMAU | Audio + language | [Site](https://sakshi113.github.io/mmau_homepage/) | Unknown | 统一音频理解与推理评测 | [Paper](https://arxiv.org/abs/2410.19168) | 把语音、环境声音和音乐理解统一到同一个现代 benchmark 中。 |
| 11 | NSynth | Audio | [Site](https://magenta.tensorflow.org/datasets/nsynth) | CC BY 4.0 | 神经音频合成与音乐表征学习 | [Paper](https://arxiv.org/abs/1704.01279) | 它是可控音乐音频合成和表征学习里最基础的一批数据集之一。 |
| 12 | MAESTRO | Audio + MIDI | [Site](https://magenta.tensorflow.org/datasets/maestro) | CC BY-NC-SA 4.0 | 钢琴转录与符号-音频联合建模 | [Paper](https://arxiv.org/abs/1810.12247) | 现代钢琴转录和音乐生成论文里最常见的数据集之一。 |
| 13 | MUSDB18 | Audio | [Site](https://sigsep.github.io/datasets/musdb.html) | Mixed / track-specific CC terms | 音乐源分离与 demixing 评测 | [Paper](https://arxiv.org/abs/1804.06267) | 现代音乐源分离论文几乎都会报告它。 |
| 14 | FMA (Free Music Archive) | Audio | [GitHub](https://github.com/mdeff/fma) | Mixed / artist-chosen audio licenses + metadata CC BY 4.0 | 开放音乐风格分类与 MIR 基线 | [Paper](https://arxiv.org/abs/1612.01840) | 它是带完整音频与元数据的经典开放音乐数据集之一。 |
| 15 | MTG-Jamendo Dataset | Audio | [Site](https://mtg.github.io/mtg-jamendo-dataset/) | Mixed / metadata CC BY-NC-SA 4.0 + track-specific CC audio | 音乐自动标注、情绪主题与风格标签学习 | [Paper](https://archives.ismir.net/ismir2019/paper/000055.pdf) | 这是音乐标签学习里高频出现的一组强 benchmark。 |
| 16 | MagnaTagATune | Audio | [Site](https://mirg.city.ac.uk/codeapps/the-magnatagatune-dataset) | Unknown | 音乐标签学习与自动标注 | [Paper](https://archives.ismir.net/ismir2009/paper/000044.pdf) | MIR 和音频标签学习研究里寿命很长、被反复引用的经典数据集。 |
| 17 | DESED | Audio | [Site](https://project.inria.fr/desed/) | Mixed / source-specific | 家庭环境声音事件检测 | [Paper](https://hal.science/hal-03230036/document) | 它是很多现代 DCASE 声音事件检测 benchmark 背后的核心数据集家族。 |
| 18 | Slakh2100 | Audio + MIDI | [Site](https://www.slakh.com/) | Unknown | 多轨音乐源分离与转录 | [Paper](https://archives.ismir.net/ismir2019/paper/000036.pdf) | 合成多轨音乐数据中最常被用于分离、转录和音乐生成的一批资源之一。 |
| 19 | TAU Urban Acoustic Scenes 2020 Mobile | Audio | [Site](https://dcase-repo.github.io/dcase_datalist/datasets/scenes/tau_asc_2020_mobile_dev.html) | Other (Non-Commercial) | 声学场景分类 | [Paper](https://arxiv.org/abs/2005.14623) | 它是 DCASE 体系里现代声学场景分类论文最常见的默认 benchmark 之一。 |
| 20 | SONYC-UST | Audio | [Site](https://dcase-repo.github.io/dcase_datalist/datasets/sounds/sonyc.html) | CC BY 4.0 | 城市声音标签学习与噪声监测 | [Paper](https://arxiv.org/abs/2009.05188) | 这是弱多标签城市声音识别和城市声学监测里很高频的数据集。 |
| 21 | OpenMIC-2018 | Audio | [Site](https://zenodo.org/records/1432913) | CC BY 4.0 | 复调乐器识别 | [Paper](https://ismir2018.ircam.fr/doc/pdfs/248_Paper.pdf) | 音乐混合场景下乐器标签学习最常见的一批开放 benchmark 之一。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [Search-Retrieval 总览](../Search-Retrieval/README_ZH.md)
- [Speech-Audio 总览](../Speech-Audio/README_ZH.md)
- [DCASE Challenge](https://dcase.community/challenge2024/)
- [MTEB](https://github.com/embeddings-benchmark/mteb)

## 收录说明

- 本页会同时收录经典数据集和较新的评测套件，因为现代音频基础模型论文通常会把两类资源一起报告。
- 更偏语音识别、语音翻译和说话人方向的资源仍然保留在 [Speech-Audio](../Speech-Audio/README_ZH.md)。
