# Speech-Audio

Speech recognition, speech translation, speaker recognition, spoken language ID, and speech generation datasets.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | LibriSpeech | English | [Site](https://www.openslr.org/12/) | CC BY 4.0 | Automatic speech recognition | [Paper](https://arxiv.org/abs/1503.02595) | Read English speech from audiobooks. |
| 2 | Common Voice | Multilingual | [Site](https://commonvoice.mozilla.org/en/datasets) | CC0-1.0 | Multilingual ASR and collection | [Docs](https://commonvoice.mozilla.org/en/datasets) | Community-recorded open speech corpus. |
| 3 | VoxCeleb | English | [Site](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/) | Custom | Speaker verification and diarization | [Paper](https://arxiv.org/abs/1706.08612) | Celebrity interview audio in the wild. |
| 4 | AISHELL-1 | Chinese | [Site](https://www.openslr.org/33/) | Apache-2.0 | Chinese ASR | [Docs](https://www.openslr.org/33/) | Standard Mandarin speech benchmark. |
| 5 | AISHELL-2 | Chinese | [Site](https://www.openslr.org/62/) | CC BY-NC-ND 4.0 | Larger-scale Chinese ASR | [Docs](https://www.openslr.org/62/) | Commercial-style Mandarin recordings. |
| 6 | FLEURS | Multilingual | [HF](https://huggingface.co/datasets/google/fleurs) | CC BY 4.0 | Multilingual speech recognition | [Paper](https://arxiv.org/abs/2205.12446) | Covers 100+ languages from one script source. |
| 7 | GigaSpeech | English | [GitHub](https://github.com/SpeechColab/GigaSpeech) | Unknown | Large-scale ASR | [Paper](https://arxiv.org/abs/2106.06909) | Podcast and audiobook scale English speech. |
| 8 | TED-LIUM Release 3 | English | [Site](https://lium.univ-lemans.fr/en/logicielscorpus/) | CC BY-NC-ND 3.0 | Lecture and TED-talk ASR | [Paper](https://arxiv.org/abs/1805.04699) | Widely used for long-form speech recognition. |
| 9 | MUSAN | Audio | [Site](https://www.openslr.org/17/) | CC BY 4.0 | Noise and augmentation data | [Paper](https://arxiv.org/abs/1510.08484) | Common for speech robustness experiments. |
| 10 | MUST-C / IWSLT Speech Translation | Multilingual | [Site](https://ict.fbk.eu/must-c/) | Custom | Speech translation | [Paper](https://aclanthology.org/N19-1202/) | Added after speech-translation requests surfaced in dataset issues. |
| 11 | IEMOCAP | English | [Site](https://sail.usc.edu/iemocap/) | Custom / registration | Speech emotion and affect modeling | [Paper](https://sail.usc.edu/iemocap/Busso_2008_iemocap.pdf) | A standard multimodal emotion corpus. |
| 12 | VoxLingua107 | Multilingual | [Site](https://bark.phon.ioc.ee/voxlingua107/) | Unknown | Spoken language identification | [Paper](https://arxiv.org/abs/2011.12998) | High-signal addition from audio dataset requests. |
| 13 | Congolese Swahili Speech Corpora | Swahili | [Site](https://gamayun.translatorswb.org/data/) | Unknown | Low-resource ASR and speech collection | [Docs](https://gamayun.translatorswb.org/data/) | Useful for underrepresented language coverage. |
| 14 | Switchboard-1 Release 2 | English | [Site](https://catalog.ldc.upenn.edu/LDC97S62) | Custom / LDC terms | Conversational ASR and spoken dialogue | [Docs](https://catalog.ldc.upenn.edu/LDC97S62) | A classic telephone-conversation benchmark still cited in conversational speech recognition papers. |
| 15 | LibriTTS | English | [Site](https://www.openslr.org/60/) | CC BY 4.0 | Text-to-speech and speech synthesis | [Paper](https://arxiv.org/abs/1904.02882) | One of the most common open TTS corpora derived from LibriSpeech. |
| 16 | VoxPopuli | Multilingual | [GitHub](https://github.com/facebookresearch/voxpopuli) | CC BY-NC 4.0 | Multilingual ASR, speech SSL, and speech translation | [Paper](https://arxiv.org/abs/2101.00390) | One of the most reused multilingual political-speech corpora in recent speech papers. |
| 17 | WenetSpeech | Chinese | [GitHub](https://github.com/wenet-e2e/WenetSpeech) | Unknown | Large-scale Mandarin ASR | [Paper](https://arxiv.org/abs/2110.03370) | A high-signal large Mandarin corpus that shows up often in Chinese ASR baselines. |
| 18 | ML-SUPERB 2.0 | Multilingual speech | [Site](https://multilingual.superbbenchmark.org/challenge-interspeech2025/challenge_overview) | Apache-2.0 | Multilingual ASR and language-ID benchmarking | [Paper](https://arxiv.org/abs/2406.08641) | One of the clearest modern benchmark suites for multilingual speech models. |
| 19 | MLS (Multilingual LibriSpeech) | Multilingual | [Site](https://openslr.org/94/) | CC BY 4.0 | Multilingual ASR and speech research | [Paper](https://arxiv.org/abs/2012.03411) | A standard large multilingual speech corpus used across ASR and speech-foundation-model papers. |
| 20 | CoVoST 2 | Multilingual | [HF](https://huggingface.co/datasets/facebook/covost2) | CC BY-NC 4.0 | Multilingual speech translation | [Paper](https://arxiv.org/abs/2007.10310) | One of the standard speech translation resources for massively multilingual and low-resource ST. |
| 21 | AMI Meeting Corpus | English | [Site](https://groups.inf.ed.ac.uk/ami/) | CC BY 4.0 | Meeting ASR, diarization, and summarization | [Docs](https://groups.inf.ed.ac.uk/ami/download/) | Canonical multi-party meeting corpus for meeting transcription, diarization, and spoken summarization. |
| 22 | SLURP | English | [GitHub](https://github.com/pswietojanski/slurp) | Mixed / text CC BY 4.0 + audio CC BY-NC 4.0 | Spoken language understanding | [Paper](https://aclanthology.org/2020.emnlp-main.588/) | A high-signal benchmark for end-to-end SLU with intents, slots, and paired audio. |
| 23 | Fisher English Training Speech | English | [Site](https://catalog.ldc.upenn.edu/LDC2004S13) | LDC User Agreement for Non-Members | Conversational telephone-speech ASR | [Docs](https://catalog.ldc.upenn.edu/LDC2005S13) | Part 1 and Part 2 together remain core resources in conversational ASR and speech translation pipelines. |
| 24 | SPGISpeech | English | [HF](https://huggingface.co/datasets/kensho/spgispeech) | Custom / Kensho terms | Financial-domain ASR | [Paper](https://arxiv.org/abs/2104.02014) | A widely reused large-scale professionally transcribed earnings-call corpus for robust English ASR. |
| 25 | VCTK Corpus | English | [Site](https://datashare.ed.ac.uk/handle/10283/3443) | CC BY 4.0 | Multi-speaker TTS and voice conversion | [Paper](https://doi.org/10.1109/ICSDA.2013.6709856) | One of the most common English multi-speaker corpora for speech synthesis, speaker adaptation, and voice conversion. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [Audio-Understanding overview](../Audio-Understanding/README.md)
- [MTEB](https://github.com/embeddings-benchmark/mteb)
- [ML-SUPERB 2.0](https://multilingual.superbbenchmark.org/challenge-interspeech2025/challenge_overview)
- [GAIA](https://huggingface.co/gaia-benchmark)

## Selection Note

- This page now prioritizes speech-centric resources such as ASR, speech translation, speaker or language ID, and speech generation.
- General audio event, captioning, and audio-language resources are expanded separately in [Audio-Understanding](../Audio-Understanding/README.md).
