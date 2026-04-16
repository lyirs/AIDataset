# Audio-Understanding

Sound event recognition, audio captioning, audio-language learning, and general non-music audio foundation-model evaluation datasets.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | AudioSet | Audio | [Site](https://research.google.com/audioset/) | Custom | Large-scale audio event recognition | [Paper](https://arxiv.org/abs/1709.04396) | The foundational large-scale weakly labeled audio-event dataset. |
| 2 | FSD50K | Audio | [Site](https://zenodo.org/records/4060432) | Mixed / clip-specific CC + dataset CC BY | Sound event classification | [Paper](https://arxiv.org/abs/2010.00475) | A high-frequency benchmark for general audio representation learning and sound event tagging. |
| 3 | ESC-50 | Audio | [GitHub](https://github.com/karolpiczak/ESC-50) | CC BY-NC | Environmental sound classification | [Paper](https://dl.acm.org/doi/10.1145/2733373.2806390) | One of the most reused small-scale audio classification benchmarks. |
| 4 | UrbanSound8K | Audio | [Site](https://urbansounddataset.weebly.com/urbansound8k.html) | Unknown | Urban acoustic scene and event classification | [Docs](https://urbansounddataset.weebly.com/urbansound8k.html) | A classic benchmark for environmental audio and urban sound recognition. |
| 5 | VGGSound | Audio + video | [Site](https://www.robots.ox.ac.uk/~vgg/data/vggsound/) | CC BY 4.0 | Large-scale audio recognition in the wild | [Paper](https://www.robots.ox.ac.uk/~vgg/publications/2020/Chen20/chen20.pdf) | A widely used large-category audio benchmark with strong audio-visual grounding. |
| 6 | Clotho | English | [Site](https://zenodo.org/records/3490684) | Mixed / source-specific + non-commercial captions | Audio captioning and audio-text retrieval | [Paper](https://arxiv.org/abs/1910.09387) | A core captioning dataset that is also cross-listed in retrieval. |
| 7 | AudioCaps | English | [Site](https://audiocaps.github.io/) | Unknown | Audio captioning and audio-language grounding | [Docs](https://audiocaps.github.io/) | One of the two most standard captioning datasets in audio-language research. |
| 8 | WavCaps | English | [GitHub](https://github.com/XinhaoMei/WavCaps) | Academic-only / source-specific | Large-scale audio-language pretraining | [Paper](https://arxiv.org/abs/2303.17395) | A high-signal weakly labeled caption dataset for audio-language multimodal learning. |
| 9 | AIR-Bench | Audio + language | [GitHub](https://github.com/OFA-Sys/AIR-Bench) | Unknown | Audio-language model evaluation | [Paper](https://arxiv.org/abs/2402.07729) | A strong recent benchmark family for audio foundation and chat-style models. |
| 10 | MMAU | Audio + language | [Site](https://sakshi113.github.io/mmau_homepage/) | Unknown | Unified audio understanding and reasoning evaluation | [Paper](https://arxiv.org/abs/2410.19168) | Covers speech, sound, and music understanding in a single modern benchmark. |
| 11 | DESED | Audio | [Site](https://project.inria.fr/desed/) | Mixed / source-specific | Sound event detection in domestic environments | [Paper](https://hal.science/hal-03230036/document) | The core dataset family behind many modern DCASE sound event detection benchmarks. |
| 12 | TAU Urban Acoustic Scenes 2020 Mobile | Audio | [Site](https://dcase-repo.github.io/dcase_datalist/datasets/scenes/tau_asc_2020_mobile_dev.html) | Other (Non-Commercial) | Acoustic scene classification | [Paper](https://arxiv.org/abs/2005.14623) | A default modern benchmark for acoustic-scene papers via DCASE. |
| 13 | SONYC-UST | Audio | [Site](https://dcase-repo.github.io/dcase_datalist/datasets/sounds/sonyc.html) | CC BY 4.0 | Urban sound tagging and city-noise monitoring | [Paper](https://arxiv.org/abs/2009.05188) | Widely reused for weak multilabel urban audio tagging and city-scale acoustic monitoring. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [Search-Retrieval overview](../Search-Retrieval/README.md)
- [Speech-Audio overview](../Speech-Audio/README.md)
- [Music-Audio overview](../Music-Audio/README.md)
- [DCASE Challenge](https://dcase.community/challenge2024/)
- [MTEB](https://github.com/embeddings-benchmark/mteb)

## Selection Note

- This page mixes classic datasets and newer benchmark suites because modern audio foundation-model papers typically report both.
- Music-centric MIR, transcription, tagging, and source-separation resources now live in [Music-Audio](../Music-Audio/README.md).
- Speech-centric corpora remain in [Speech-Audio](../Speech-Audio/README.md).
