# 语音与音频（Speech-Audio）

覆盖语音识别、语音翻译、说话人识别、口语语言识别与语音生成的数据集目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | LibriSpeech | English | [Site](https://www.openslr.org/12/) | CC BY 4.0 | 自动语音识别 | [Paper](https://arxiv.org/abs/1503.02595) | 来自有声书的英文朗读语音。 |
| 2 | Common Voice | Multilingual | [Site](https://commonvoice.mozilla.org/en/datasets) | CC0-1.0 | 多语言语音识别与采集 | [Docs](https://commonvoice.mozilla.org/en/datasets) | 社区众包的开放语音语料。 |
| 3 | VoxCeleb | English | [Site](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/) | Custom | 说话人验证与分离 | [Paper](https://arxiv.org/abs/1706.08612) | 来自真实访谈场景的名人语音。 |
| 4 | AISHELL-1 | Chinese | [Site](https://www.openslr.org/33/) | Apache-2.0 | 中文语音识别 | [Docs](https://www.openslr.org/33/) | 中文普通话 ASR 常用基准。 |
| 5 | AISHELL-2 | Chinese | [Site](https://www.openslr.org/62/) | CC BY-NC-ND 4.0 | 更大规模中文语音识别 | [Docs](https://www.openslr.org/62/) | 更接近商业录音场景。 |
| 6 | FLEURS | Multilingual | [HF](https://huggingface.co/datasets/google/fleurs) | CC BY 4.0 | 多语言语音识别 | [Paper](https://arxiv.org/abs/2205.12446) | 统一脚本来源下覆盖 100+ 语言。 |
| 7 | GigaSpeech | English | [GitHub](https://github.com/SpeechColab/GigaSpeech) | Unknown | 大规模语音识别 | [Paper](https://arxiv.org/abs/2106.06909) | 适合长时长英语语音训练。 |
| 8 | TED-LIUM Release 3 | English | [Site](https://lium.univ-lemans.fr/en/logicielscorpus/) | CC BY-NC-ND 3.0 | 演讲和 TED 语音识别 | [Paper](https://arxiv.org/abs/1805.04699) | 长语音识别研究中的常用资源。 |
| 9 | MUSAN | Audio | [Site](https://www.openslr.org/17/) | CC BY 4.0 | 噪声与数据增强 | [Paper](https://arxiv.org/abs/1510.08484) | 常用于语音鲁棒性实验。 |
| 10 | MUST-C / IWSLT Speech Translation | Multilingual | [Site](https://ict.fbk.eu/must-c/) | Custom | 语音翻译 | [Paper](https://aclanthology.org/N19-1202/) | 来自 speech translation 数据集需求信号。 |
| 11 | IEMOCAP | English | [Site](https://sail.usc.edu/iemocap/) | Custom / registration | 情感语音与多模态情绪建模 | [Paper](https://sail.usc.edu/iemocap/Busso_2008_iemocap.pdf) | 经典多说话人情绪语音库。 |
| 12 | VoxLingua107 | Multilingual | [Site](https://bark.phon.ioc.ee/voxlingua107/) | Unknown | 口语语言识别 | [Paper](https://arxiv.org/abs/2011.12998) | 来自音频数据集请求的高价值补充。 |
| 13 | Congolese Swahili Speech Corpora | Swahili | [Site](https://gamayun.translatorswb.org/data/) | Unknown | 低资源语音识别与采集 | [Docs](https://gamayun.translatorswb.org/data/) | 有助于补足低资源语言覆盖。 |
| 14 | Switchboard-1 Release 2 | English | [Site](https://catalog.ldc.upenn.edu/LDC97S62) | Custom / LDC terms | 对话式语音识别与口语对话研究 | [Docs](https://catalog.ldc.upenn.edu/LDC97S62) | 电话对话 ASR 里最经典的数据集之一，至今仍常被引用。 |
| 15 | LibriTTS | English | [Site](https://www.openslr.org/60/) | CC BY 4.0 | 语音合成与 TTS | [Paper](https://arxiv.org/abs/1904.02882) | 由 LibriSpeech 扩展而来，是最常用的开放 TTS 语料之一。 |
| 16 | VoxPopuli | Multilingual | [GitHub](https://github.com/facebookresearch/voxpopuli) | CC BY-NC 4.0 | 多语言 ASR、语音自监督与语音翻译 | [Paper](https://arxiv.org/abs/2101.00390) | 近年多语言语音论文里反复出现的政治演讲大规模语料。 |
| 17 | WenetSpeech | Chinese | [GitHub](https://github.com/wenet-e2e/WenetSpeech) | Unknown | 大规模普通话语音识别 | [Paper](https://arxiv.org/abs/2110.03370) | 中文 ASR 强基线里很高频的一个大规模普通话数据集。 |
| 18 | ML-SUPERB 2.0 | Multilingual speech | [Site](https://multilingual.superbbenchmark.org/challenge-interspeech2025/challenge_overview) | Apache-2.0 | 多语言 ASR 与语言识别评测 | [Paper](https://arxiv.org/abs/2406.08641) | 现在最清晰、也最贴近现代多语言语音模型的 benchmark suite 之一。 |
| 19 | MLS (Multilingual LibriSpeech) | Multilingual | [Site](https://openslr.org/94/) | CC BY 4.0 | 多语言 ASR 与语音研究 | [Paper](https://arxiv.org/abs/2012.03411) | 一个标准的大规模多语言语音语料，在 ASR 和语音基础模型论文里都很常见。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [Audio-Understanding 总览](../Audio-Understanding/README_ZH.md)
- [MTEB](https://github.com/embeddings-benchmark/mteb)
- [ML-SUPERB 2.0](https://multilingual.superbbenchmark.org/challenge-interspeech2025/challenge_overview)
- [GAIA](https://huggingface.co/gaia-benchmark)

## 收录说明

- 本页现在更强调语音主线资源，比如 ASR、语音翻译、说话人或语言识别，以及语音生成。
- 更偏通用音频事件、音频描述和音频语言的资源，现已单独扩展到 [Audio-Understanding](../Audio-Understanding/README_ZH.md)。
