# Computer-Use

Browser, desktop, mobile, and GUI-grounded datasets and benchmarks for computer-use agents.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Mind2Web | English | [Site](https://osu-nlp-group.github.io/Mind2Web/) | Unknown | Real web navigation from human traces | [Paper](https://arxiv.org/abs/2306.06070) | Strong browser-agent dataset built from real-world websites. |
| 2 | WebArena | English | [Site](https://webarena.dev/) | Unknown | Browser agents on realistic websites | [Paper](https://arxiv.org/abs/2307.13854) | One of the main modern benchmarks for web agents. |
| 3 | MiniWoB++ | English | [Site](https://miniwob.farama.org/) | Apache-2.0 | Lightweight web UI control | [Docs](https://miniwob.farama.org/) | Standard starting point for browser-like agent interaction. |
| 4 | WebLINX | English | [Site](https://mcgill-nlp.github.io/weblinx/) | Unknown | Grounded web-agent learning from demonstrations | [Docs](https://mcgill-nlp.github.io/weblinx/) | Captures realistic human web interactions and trajectories. |
| 5 | BrowserGym | Interactive Web | [GitHub](https://github.com/ServiceNow/BrowserGym) | Apache-2.0 | Browser-agent training environments | [Docs](https://github.com/ServiceNow/BrowserGym) | Unifies several browser tasks under a common gym-style interface. |
| 6 | WorkArena | Enterprise Web | [Site](https://servicenow.github.io/WorkArena/) | Unknown | Enterprise workflow automation agents | [Docs](https://servicenow.github.io/WorkArena/) | Useful for realistic business-process and web workflow agents. |
| 7 | VisualWebArena | English | [GitHub](https://github.com/web-arena-x/visualwebarena) | MIT | Multimodal browser agents with visual grounding | [Paper](https://arxiv.org/abs/2401.13649) | Extends WebArena with screenshot-grounded web tasks. |
| 8 | WebVoyager | English | [GitHub](https://github.com/MinorJerry/WebVoyager) | Apache-2.0 | End-to-end real-world web navigation | [Paper](https://arxiv.org/abs/2401.13919) | A highly visible benchmark for multimodal agents interacting with live websites. |
| 9 | BrowseComp | English | [Site](https://openai.com/index/browsecomp/) | Unknown | Hard web browsing and multi-hop fact finding | [Paper](https://cdn.openai.com/pdf/5e10f4ab-d6f7-442e-9508-59515c65e35d/browsecomp.pdf) | Official OpenAI benchmark for persistent browsing agents on hard-to-find web facts. |
| 10 | OSWorld | English | [Site](https://os-world.github.io/) | Unknown | Desktop and OS-level multimodal agents | [Docs](https://os-world.github.io/) | High-signal benchmark for computer-use style agents. |
| 11 | WindowsAgentArena | English | [Site](https://microsoft.github.io/WindowsAgentArena/) | MIT | Windows desktop agents and OS workflows | [GitHub](https://github.com/microsoft/WindowsAgentArena) | Official Microsoft benchmark platform for multimodal agents on Windows. |
| 12 | ScreenSpot | GUI screenshots | [HF](https://huggingface.co/datasets/rootsautomation/ScreenSpot) | Apache-2.0 | GUI grounding on desktop and mobile screens | [Paper](https://arxiv.org/abs/2401.10935) | Widely used benchmark for localizing target UI elements from screenshots. |
| 13 | ScreenSpot-Pro | GUI screenshots | [GitHub](https://github.com/likaixin2000/ScreenSpot-Pro-GUI-Grounding) | MIT | High-resolution GUI grounding for computer-use agents | [Paper](https://arxiv.org/abs/2504.07981) | Standard reference for measuring GUI grounding quality in desktop and professional software settings. |
| 14 | Screen2Words | English | [GitHub](https://github.com/google-research-datasets/screen2words) | Unknown | Mobile UI summarization and screen captioning | [Paper](https://arxiv.org/abs/2108.03353) | Foundational large-scale captioning set for language-grounded mobile UI understanding. |
| 15 | ScreenQA | English | [GitHub](https://github.com/google-research-datasets/screen_qa) | CC BY 4.0 | Question answering over app screens | [Paper](https://arxiv.org/abs/2209.08199) | Large screenshot QA dataset built on Rico and widely reused in screen-understanding evaluation. |
| 16 | Screen Annotation | Mobile UI | [GitHub](https://github.com/google-research-datasets/screen_annotation) | CC BY 4.0 | Dense UI element annotation and screen parsing | [Paper](https://arxiv.org/abs/2402.04615) | Key supervision source for ScreenAI-style UI understanding models. |
| 17 | RICO | Mobile UI | [Site](https://www.interactionmining.org/archive/rico) | Unknown | Mobile UI structure and screen understanding | [Paper](https://arxiv.org/abs/1803.10702) | Classic large-scale Android app dataset used across UI understanding and mobile-agent papers. |
| 18 | RICO Semantics | Mobile UI | [GitHub](https://github.com/google-research-datasets/rico_semantics) | CC-BY-SA-4.0 | UI semantics and icon grounding | [Paper](https://arxiv.org/abs/2202.13274) | Adds fine-grained semantic labels, icon annotations, and grounding signals on top of RICO. |
| 19 | UIBert Datasets | Mobile UI | [GitHub](https://github.com/google-research-datasets/uibert) | CC BY 4.0 | UI grounding and similar-element retrieval | [Paper](https://arxiv.org/abs/2107.13731) | Rico-derived AppSim and RefExp datasets are common references for UI representation learning. |
| 20 | Android in the Wild (AITW) | English | [Site](https://research.google/pubs/android-in-the-wild-a-large-scale-dataset-for-android-device-control/) | Unknown | Large-scale mobile device control from demonstrations | [Paper](https://arxiv.org/abs/2307.10088) | Large-scale Android control corpus with 715k episodes from crowdsourced demonstrations. |
| 21 | AndroidControl | English | [GitHub](https://github.com/google-research/google-research/tree/master/android_control) | Apache-2.0 (repo) | Android control fine-tuning from human demonstrations | [Paper](https://arxiv.org/abs/2406.03679) | Official Google dataset release with 15k+ demonstrations across 833 apps. |
| 22 | AndroidWorld | English | [GitHub](https://github.com/google-research/android_world) | Apache-2.0 | Mobile device agents and Android interaction | [Paper](https://arxiv.org/abs/2405.14573) | One of the clearest official environments for smartphone-use agents. |
| 23 | META-GUI | English | [Site](https://x-lance.github.io/META-GUI-Leaderboard/) | Unknown | Multimodal conversational agents on mobile GUI | [Paper](https://arxiv.org/abs/2205.11029) | Early public dataset for GUI-grounded multi-turn mobile assistant interaction. |
| 24 | GUICourse | English | [GitHub](https://github.com/RUCBM/GUICourse) | CC BY 4.0 (data) / MIT (code) | GUI grounding, action prediction, and GUI chat supervision | [Paper](https://arxiv.org/abs/2406.11317) | High-signal suite spanning GUIEnv, GUIAct, and GUIChat for versatile GUI agents. |
| 25 | MobileAgentBench | English | [Site](https://mobileagentbench.github.io/) | Unknown | Controlled mobile-agent benchmarking across real apps | [Paper](https://arxiv.org/abs/2406.08184) | Strong benchmark with app-level tasks designed for reproducible mobile-agent evaluation. |
| 26 | MobileBench | Chinese / English mobile | [GitHub](https://github.com/XiaoMi/MobileBench) | Unknown | Multi-app mobile-agent evaluation | [Paper](https://arxiv.org/abs/2407.00993) | Widely referenced mobile-agent benchmark from Xiaomi for multi-app workflows. |

## Related Benchmarks

- [Agent overview](../Agent/README.md)
- [Benchmarks overview](../Benchmarks/README.md)
- [WebArena](https://webarena.dev/)
- [OSWorld](https://os-world.github.io/)
- [ScreenSpot-Pro](https://github.com/likaixin2000/ScreenSpot-Pro-GUI-Grounding)

## Selection Note

- This page combines interactive environments, benchmark suites, and GUI grounding datasets because computer-use research depends on all three.
- Browser, desktop, and mobile resources were split out of [Agent](../Agent/README.md) once they became a distinct high-density cluster.
