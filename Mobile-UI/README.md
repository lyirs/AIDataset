# Mobile-UI

Mobile UI understanding, screen grounding, and Android agent datasets and benchmarks.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Screen2Words | English | [GitHub](https://github.com/google-research-datasets/screen2words) | Unknown | Mobile UI summarization and screen captioning | [Paper](https://arxiv.org/abs/2108.03353) | Foundational large-scale captioning set for language-grounded mobile UI understanding. |
| 2 | Widget Caption | English | [GitHub](https://github.com/google-research-datasets/widget-caption) | CC BY 4.0 | UI element captioning and functionality description | [Paper](https://arxiv.org/abs/2010.04295) | A standard supervision source for describing widget functionality in grounded mobile UI understanding. |
| 3 | ScreenQA | English | [GitHub](https://github.com/google-research-datasets/screen_qa) | CC BY 4.0 | Question answering over app screens | [Paper](https://arxiv.org/abs/2209.08199) | Large screenshot QA dataset built on Rico and widely reused in screen-understanding evaluation. |
| 4 | Screen Annotation | Mobile UI | [GitHub](https://github.com/google-research-datasets/screen_annotation) | CC BY 4.0 | Dense UI element annotation and screen parsing | [Paper](https://arxiv.org/abs/2402.04615) | Key supervision source for ScreenAI-style UI understanding models. |
| 5 | RICO | Mobile UI | [Site](https://www.interactionmining.org/archive/rico) | Unknown | Mobile UI structure and screen understanding | [Paper](https://arxiv.org/abs/1803.10702) | Classic large-scale Android app dataset used across UI understanding and mobile-agent papers. |
| 6 | RICO Semantics | Mobile UI | [GitHub](https://github.com/google-research-datasets/rico_semantics) | CC-BY-SA-4.0 | UI semantics and icon grounding | [Paper](https://arxiv.org/abs/2202.13274) | Adds fine-grained semantic labels, icon annotations, and grounding signals on top of RICO. |
| 7 | UIBert Datasets | Mobile UI | [GitHub](https://github.com/google-research-datasets/uibert) | CC BY 4.0 | UI grounding and similar-element retrieval | [Paper](https://arxiv.org/abs/2107.13731) | Rico-derived AppSim and RefExp datasets are common references for UI representation learning. |
| 8 | MoTIF | English | [GitHub](https://github.com/aburns4/MoTIF) | Unknown | Mobile task automation with feasibility feedback | [Paper](https://arxiv.org/abs/2202.02312) | A classic mobile-app task dataset with feasibility labels and follow-up feedback for more realistic instruction execution. |
| 9 | Android in the Wild (AITW) | English | [Site](https://research.google/pubs/android-in-the-wild-a-large-scale-dataset-for-android-device-control/) | Unknown | Large-scale mobile device control from demonstrations | [Paper](https://arxiv.org/abs/2307.10088) | Large-scale Android control corpus with 715k episodes from crowdsourced demonstrations. |
| 10 | AndroidControl | English | [GitHub](https://github.com/google-research/google-research/tree/master/android_control) | Apache-2.0 (repo) | Android control fine-tuning from human demonstrations | [Paper](https://arxiv.org/abs/2406.03679) | Official Google dataset release with 15k+ demonstrations across 833 apps. |
| 11 | AndroidWorld | English | [GitHub](https://github.com/google-research/android_world) | Apache-2.0 | Mobile device agents and Android interaction | [Paper](https://arxiv.org/abs/2405.14573) | One of the clearest official environments for smartphone-use agents. |
| 12 | LlamaTouch | English | [GitHub](https://github.com/LlamaTouch/LlamaTouch) | Unknown | Faithful mobile UI task automation evaluation | [Paper](https://arxiv.org/abs/2404.16054) | A strong real-device testbed with 496 tasks and essential-state matching for scalable mobile-agent evaluation. |
| 13 | META-GUI | English | [Site](https://x-lance.github.io/META-GUI-Leaderboard/) | Unknown | Multimodal conversational agents on mobile GUI | [Paper](https://arxiv.org/abs/2205.11029) | Early public dataset for GUI-grounded multi-turn mobile assistant interaction. |
| 14 | GUICourse | English | [GitHub](https://github.com/RUCBM/GUICourse) | CC BY 4.0 (data) / MIT (code) | GUI grounding, action prediction, and GUI chat supervision | [Paper](https://arxiv.org/abs/2406.11317) | High-signal suite spanning GUIEnv, GUIAct, and GUIChat for versatile GUI agents. |
| 15 | AMEX | Mobile UI | [HF](https://huggingface.co/datasets/Yuxiang007/AMEX) | Unknown | Multi-annotation mobile GUI agents | [Paper](https://arxiv.org/abs/2407.17490) | A recent dataset focused on richer multi-annotation supervision for mobile GUI agents. |
| 16 | GUI Odyssey | Mobile UI | [GitHub](https://github.com/OpenGVLab/GUI-Odyssey) | Unknown | Cross-app mobile GUI navigation | [Paper](https://arxiv.org/abs/2406.08451) | A comprehensive dataset for training and evaluating cross-app mobile navigation agents. |
| 17 | MobileAgentBench | English | [Site](https://mobileagentbench.github.io/) | Unknown | Controlled mobile-agent benchmarking across real apps | [Paper](https://arxiv.org/abs/2406.08184) | Strong benchmark with app-level tasks designed for reproducible mobile-agent evaluation. |
| 18 | MobileBench | Chinese / English mobile | [GitHub](https://github.com/XiaoMi/MobileBench) | Unknown | Multi-app mobile-agent evaluation | [Paper](https://arxiv.org/abs/2407.00993) | Widely referenced mobile-agent benchmark from Xiaomi for multi-app workflows. |

## Related Benchmarks

- [Computer-Use overview](../Computer-Use/README.md)
- [Agent overview](../Agent/README.md)
- [Benchmarks overview](../Benchmarks/README.md)
- [AndroidWorld](https://github.com/google-research/android_world)
- [MobileAgentBench](https://mobileagentbench.github.io/)

## Selection Note

- This page focuses on mobile screenshots, UI semantics, Android control trajectories, and smartphone-agent benchmarks.
- Browser and desktop computer-use resources remain in [Computer-Use](../Computer-Use/README.md).
- If this category keeps growing, it should be split into `Mobile-Understanding` and `Mobile-Agent`.
