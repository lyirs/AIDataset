# Computer-Use

Browser, desktop, and cross-platform GUI-grounded datasets and benchmarks for computer-use agents.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Mind2Web | English | [Site](https://osu-nlp-group.github.io/Mind2Web/) | Unknown | Real web navigation from human traces | [Paper](https://arxiv.org/abs/2306.06070) | Strong browser-agent dataset built from real-world websites. |
| 2 | Online-Mind2Web | English | [GitHub](https://github.com/OSU-NLP-Group/Online-Mind2Web) | MIT | Live web-agent evaluation on real websites | [Paper](https://arxiv.org/abs/2504.01382) | A live, maintained successor-style benchmark with 300 tasks across 136 popular websites. |
| 3 | WebCanvas / Mind2Web-Live | English | [GitHub](https://github.com/iMeanAI/WebCanvas) | MIT | Online web-agent evaluation with intermediate states | [Paper](https://arxiv.org/abs/2406.12373) | Adds Mind2Web-Live with 542 dynamic web tasks and intermediate evaluation states for more realistic online assessment. |
| 4 | WebArena | English | [Site](https://webarena.dev/) | Unknown | Browser agents on realistic websites | [Paper](https://arxiv.org/abs/2307.13854) | One of the main modern benchmarks for web agents. |
| 5 | MiniWoB++ | English | [Site](https://miniwob.farama.org/) | Apache-2.0 | Lightweight web UI control | [Docs](https://miniwob.farama.org/) | Standard starting point for browser-like agent interaction. |
| 6 | WebLINX | English | [Site](https://mcgill-nlp.github.io/weblinx/) | Unknown | Grounded web-agent learning from demonstrations | [Docs](https://mcgill-nlp.github.io/weblinx/) | Captures realistic human web interactions and trajectories. |
| 7 | BrowserGym | Interactive Web | [GitHub](https://github.com/ServiceNow/BrowserGym) | Apache-2.0 | Browser-agent training environments | [Docs](https://github.com/ServiceNow/BrowserGym) | Unifies several browser tasks under a common gym-style interface. |
| 8 | WorkArena | Enterprise Web | [Site](https://servicenow.github.io/WorkArena/) | Unknown | Enterprise workflow automation agents | [Docs](https://servicenow.github.io/WorkArena/) | Useful for realistic business-process and web workflow agents. |
| 9 | VisualWebArena | English | [GitHub](https://github.com/web-arena-x/visualwebarena) | MIT | Multimodal browser agents with visual grounding | [Paper](https://arxiv.org/abs/2401.13649) | Extends WebArena with screenshot-grounded web tasks. |
| 10 | WebVoyager | English | [GitHub](https://github.com/MinorJerry/WebVoyager) | Apache-2.0 | End-to-end real-world web navigation | [Paper](https://arxiv.org/abs/2401.13919) | A highly visible benchmark for multimodal agents interacting with live websites. |
| 11 | BrowseComp | English | [Site](https://openai.com/index/browsecomp/) | Unknown | Hard web browsing and multi-hop fact finding | [Paper](https://cdn.openai.com/pdf/5e10f4ab-d6f7-442e-9508-59515c65e35d/browsecomp.pdf) | Official OpenAI benchmark for persistent browsing agents on hard-to-find web facts. |
| 12 | AssistantBench | English | [Site](https://assistantbench.github.io/) | Unknown | Realistic long-horizon web assistance | [Paper](https://arxiv.org/abs/2407.15711) | Adds time-consuming multi-website tasks that expose planning, search, and memory failures in web assistants. |
| 13 | OmniACT | GUI screenshots + actions | [HF](https://huggingface.co/datasets/Writer/omniact) | Unknown | Desktop and web GUI action grounding | [Paper](https://arxiv.org/abs/2402.17553) | A widely reused static benchmark for converting screen instructions into executable PyAutoGUI-style actions. |
| 14 | OSWorld | English | [Site](https://os-world.github.io/) | Unknown | Desktop and OS-level multimodal agents | [Docs](https://os-world.github.io/) | High-signal benchmark for computer-use style agents. |
| 15 | WindowsAgentArena | English | [Site](https://microsoft.github.io/WindowsAgentArena/) | MIT | Windows desktop agents and OS workflows | [GitHub](https://github.com/microsoft/WindowsAgentArena) | Official Microsoft benchmark platform for multimodal agents on Windows. |
| 16 | OS-Atlas Data | GUI screenshots + grounding | [HF](https://huggingface.co/datasets/OS-Copilot/OS-Atlas-data) | Unknown | Cross-platform GUI grounding pretraining | [Paper](https://arxiv.org/abs/2410.23218) | A large GUI grounding corpus spanning desktop, mobile, and web screenshots for computer-use action models. |
| 17 | ScreenSpot | GUI screenshots | [HF](https://huggingface.co/datasets/rootsautomation/ScreenSpot) | Apache-2.0 | GUI grounding on desktop and mobile screens | [Paper](https://arxiv.org/abs/2401.10935) | Widely used benchmark for localizing target UI elements from screenshots. |
| 18 | ScreenSpot-Pro | GUI screenshots | [GitHub](https://github.com/likaixin2000/ScreenSpot-Pro-GUI-Grounding) | MIT | High-resolution GUI grounding for computer-use agents | [Paper](https://arxiv.org/abs/2504.07981) | Standard reference for measuring GUI grounding quality in desktop and professional software settings. |

## Related Benchmarks

- [Agent overview](../Agent/README.md)
- [Mobile-UI overview](../Mobile-UI/README.md)
- [Benchmarks overview](../Benchmarks/README.md)
- [WebArena](https://webarena.dev/)
- [Online-Mind2Web](https://github.com/OSU-NLP-Group/Online-Mind2Web)
- [WebCanvas](https://github.com/iMeanAI/WebCanvas)
- [OSWorld](https://os-world.github.io/)
- [AssistantBench](https://assistantbench.github.io/)
- [OS-Atlas](https://osatlas.github.io/)
- [ScreenSpot-Pro](https://github.com/likaixin2000/ScreenSpot-Pro-GUI-Grounding)

## Selection Note

- This page focuses on browser, desktop, and cross-platform computer-use resources.
- Mobile UI understanding and smartphone-agent resources now live in [Mobile-UI](../Mobile-UI/README.md).
- The browser-agent cluster is becoming dense; if it grows much further, it should be split into a dedicated web-agent category.
