# 音乐音频（Music-Audio）

覆盖音乐音频、MIR、转录、源分离、标签学习与符号-音频联合建模的数据目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | NSynth | Audio | [Site](https://magenta.tensorflow.org/datasets/nsynth) | CC BY 4.0 | 神经音频合成与音乐表征学习 | [Paper](https://arxiv.org/abs/1704.01279) | 它是可控音乐音频合成和表征学习里最基础的一批数据集之一。 |
| 2 | MAESTRO | Audio + MIDI | [Site](https://magenta.tensorflow.org/datasets/maestro) | CC BY-NC-SA 4.0 | 钢琴转录与符号-音频联合建模 | [Paper](https://arxiv.org/abs/1810.12247) | 现代钢琴转录和音乐生成论文里最常见的数据集之一。 |
| 3 | Lakh MIDI Dataset | MIDI | [Site](https://colinraffel.com/projects/lmd/) | CC BY 4.0 | 符号音乐生成与表征学习 | [Docs](https://colinraffel.com/projects/lmd/) | 它是长序列音乐建模和 MIDI 生成研究里最常被复用的符号音乐语料之一。 |
| 4 | MUSDB18 | Audio | [Site](https://sigsep.github.io/datasets/musdb.html) | Mixed / track-specific CC terms | 音乐源分离与 demixing 评测 | [Paper](https://arxiv.org/abs/1804.06267) | 现代音乐源分离论文几乎都会报告它。 |
| 5 | FMA (Free Music Archive) | Audio | [GitHub](https://github.com/mdeff/fma) | Mixed / artist-chosen audio licenses + metadata CC BY 4.0 | 开放音乐风格分类与 MIR 基线 | [Paper](https://arxiv.org/abs/1612.01840) | 它是带完整音频与元数据的经典开放音乐数据集之一。 |
| 6 | Million Song Dataset | Audio features + metadata | [Site](https://millionsongdataset.com/) | Mixed / metadata-specific terms | 大规模 MIR 与音乐推荐 | [Paper](https://www.ee.columbia.edu/~dpwe/pubs/BertEWL11-msd.pdf) | 它是覆盖百万歌曲特征与元数据的基础资源，在 MIR 和推荐系统论文里都极高频。 |
| 7 | MTG-Jamendo Dataset | Audio | [Site](https://mtg.github.io/mtg-jamendo-dataset/) | Mixed / metadata CC BY-NC-SA 4.0 + track-specific CC audio | 音乐自动标注、情绪主题与风格标签学习 | [Paper](https://archives.ismir.net/ismir2019/paper/000055.pdf) | 这是音乐标签学习里高频出现的一组强 benchmark。 |
| 8 | MagnaTagATune | Audio | [Site](https://mirg.city.ac.uk/codeapps/the-magnatagatune-dataset) | Unknown | 音乐标签学习与自动标注 | [Paper](https://archives.ismir.net/ismir2009/paper/000044.pdf) | MIR 和音频标签学习研究里寿命很长、被反复引用的经典数据集。 |
| 9 | Slakh2100 | Audio + MIDI | [Site](https://www.slakh.com/) | Unknown | 多轨音乐源分离与转录 | [Paper](https://archives.ismir.net/ismir2019/paper/000036.pdf) | 合成多轨音乐数据中最常被用于分离、转录和音乐生成的一批资源之一。 |
| 10 | MedleyDB | Audio + multitrack stems | [Site](https://medleydb.weebly.com/) | CC BY-NC-SA | 多轨 MIR、旋律提取与源分离 | [Paper](https://archives.ismir.net/ismir2014/poster/000040.pdf) | 它是旋律标注、多轨 stems 与乐器感知 MIR 评测里非常标准的基准。 |
| 11 | OpenMIC-2018 | Audio | [Site](https://zenodo.org/records/1432913) | CC BY 4.0 | 复调乐器识别 | [Paper](https://ismir2018.ircam.fr/doc/pdfs/248_Paper.pdf) | 音乐混合场景下乐器标签学习最常见的一批开放 benchmark 之一。 |
| 12 | MusicNet | Audio + labels | [Site](https://zenodo.org/records/5120004) | CC BY 4.0 | 监督式音乐转录与音符级标注 | [Paper](https://arxiv.org/abs/1611.09827) | 它是古典音乐音符转录和音乐表征学习里被引用最多的一类数据集之一。 |
| 13 | IRMAS | Audio | [Site](https://www.upf.edu/web/mtg/irmas) | CC BY-NC-SA 3.0 | 主导乐器识别 | [Paper](https://ismir2012.ismir.net/event/papers/049-ismir-2012.pdf) | 它是现实音乐混合场景下乐器识别的经典 benchmark。 |
| 14 | VocalSet | Audio | [Site](https://zenodo.org/records/1442513) | CC BY 4.0 | 歌唱声音建模与技巧分类 | [Paper](https://arxiv.org/abs/1804.05080) | 它是开放歌唱声音研究里最强的一类数据集之一，常用于技巧、音色和合成研究。 |
| 15 | RWC Music Database | Audio + MIDI + lyrics | [Site](https://staff.aist.go.jp/m.goto/RWC-MDB/) | Custom / research-use application | 跨流派、乐器和整曲的 MIR 基准 | [Docs](https://staff.aist.go.jp/m.goto/RWC-MDB/) | 它是 MIR 历史上最经典的大型音乐数据库家族之一，至今仍常出现在基线和评测表中。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [Audio-Understanding 总览](../Audio-Understanding/README_ZH.md)
- [MIREX](https://www.music-ir.org/mirex/wiki/MIREX_HOME)
- [MUSDB18](https://sigsep.github.io/datasets/musdb.html)
- [OpenMIC-2018](https://zenodo.org/records/1432913)

## 收录说明

- 这个分类是从 `Audio-Understanding` 中独立出来的，因为音乐音频、MIR、转录、标签学习、源分离和歌唱声音研究已经形成了非常稳定的独立子领域。
- 更通用的声音事件、音频描述和音频语言资源仍然保留在 [Audio-Understanding](../Audio-Understanding/README_ZH.md)。
