# 计算机使用（Computer-Use）

覆盖浏览器、桌面、移动端与 GUI grounding 的 computer-use agent 数据与评测目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Mind2Web | English | [Site](https://osu-nlp-group.github.io/Mind2Web/) | Unknown | 基于真实轨迹的网页导航 | [Paper](https://arxiv.org/abs/2306.06070) | 由真实网站轨迹构建的高信号浏览器代理数据集。 |
| 2 | WebArena | English | [Site](https://webarena.dev/) | Unknown | 真实网站上的浏览器代理 | [Paper](https://arxiv.org/abs/2307.13854) | 它是当前网页代理研究里最常见的 benchmark 之一。 |
| 3 | MiniWoB++ | English | [Site](https://miniwob.farama.org/) | Apache-2.0 | 轻量级网页 UI 控制 | [Docs](https://miniwob.farama.org/) | 它是浏览器式代理交互最经典的入门环境之一。 |
| 4 | WebLINX | English | [Site](https://mcgill-nlp.github.io/weblinx/) | Unknown | 基于演示轨迹的网页代理学习 | [Docs](https://mcgill-nlp.github.io/weblinx/) | 它收集了更真实的人类网页交互与轨迹信号。 |
| 5 | BrowserGym | Interactive Web | [GitHub](https://github.com/ServiceNow/BrowserGym) | Apache-2.0 | 浏览器代理训练环境 | [Docs](https://github.com/ServiceNow/BrowserGym) | 它用统一的 gym 风格接口整合多种 browser tasks。 |
| 6 | WorkArena | Enterprise Web | [Site](https://servicenow.github.io/WorkArena/) | Unknown | 企业流程自动化代理 | [Docs](https://servicenow.github.io/WorkArena/) | 它很适合评测真实业务流程与网页工作流代理。 |
| 7 | VisualWebArena | English | [GitHub](https://github.com/web-arena-x/visualwebarena) | MIT | 带视觉 grounding 的浏览器代理 | [Paper](https://arxiv.org/abs/2401.13649) | 它在 WebArena 基础上加入截图和视觉感知网页任务。 |
| 8 | WebVoyager | English | [GitHub](https://github.com/MinorJerry/WebVoyager) | Apache-2.0 | 真实网站上的端到端网页导航 | [Paper](https://arxiv.org/abs/2401.13919) | 它是评测多模态网页代理与实时网站交互能力时最常见的 benchmark 之一。 |
| 9 | BrowseComp | English | [Site](https://openai.com/index/browsecomp/) | Unknown | 高难网页浏览与多跳事实定位 | [Paper](https://cdn.openai.com/pdf/5e10f4ab-d6f7-442e-9508-59515c65e35d/browsecomp.pdf) | 它是 OpenAI 官方浏览代理 benchmark，强调持续搜索和难定位事实。 |
| 10 | OSWorld | English | [Site](https://os-world.github.io/) | Unknown | 桌面与操作系统级多模态代理 | [Docs](https://os-world.github.io/) | 它是 computer-use 风格代理评测中的高信号资源。 |
| 11 | WindowsAgentArena | English | [Site](https://microsoft.github.io/WindowsAgentArena/) | MIT | Windows 桌面代理与系统工作流 | [GitHub](https://github.com/microsoft/WindowsAgentArena) | 它是微软官方推出的 Windows 多模态代理 benchmark 平台。 |
| 12 | ScreenSpot | GUI screenshots | [HF](https://huggingface.co/datasets/rootsautomation/ScreenSpot) | Apache-2.0 | 桌面与移动屏幕上的 GUI grounding | [Paper](https://arxiv.org/abs/2401.10935) | 它是从截图中定位目标 UI 元素时最常用的 benchmark 之一。 |
| 13 | ScreenSpot-Pro | GUI screenshots | [GitHub](https://github.com/likaixin2000/ScreenSpot-Pro-GUI-Grounding) | MIT | 面向 computer-use agent 的高分辨率 GUI grounding | [Paper](https://arxiv.org/abs/2504.07981) | 它已成为桌面代理与专业软件 GUI grounding 评测的重要参考。 |
| 14 | Screen2Words | English | [GitHub](https://github.com/google-research-datasets/screen2words) | Unknown | 移动端 UI 摘要与屏幕描述 | [Paper](https://arxiv.org/abs/2108.03353) | 它是把移动界面转成自然语言摘要时最基础、最常被复用的大规模数据集之一。 |
| 15 | ScreenQA | English | [GitHub](https://github.com/google-research-datasets/screen_qa) | CC BY 4.0 | 面向 App 截图的问答 | [Paper](https://arxiv.org/abs/2209.08199) | 它是在 Rico 截图上构建的大规模 Screen QA 数据，常被用于 screen understanding 评测。 |
| 16 | Screen Annotation | Mobile UI | [GitHub](https://github.com/google-research-datasets/screen_annotation) | CC BY 4.0 | 密集 UI 元素标注与屏幕解析 | [Paper](https://arxiv.org/abs/2402.04615) | 它是 ScreenAI 一类 UI 理解模型的重要监督来源。 |
| 17 | RICO | Mobile UI | [Site](https://www.interactionmining.org/archive/rico) | Unknown | 移动端 UI 结构与界面理解 | [Paper](https://arxiv.org/abs/1803.10702) | 它是 Android UI 理解和 mobile-agent 论文里最经典的大规模数据集之一。 |
| 18 | RICO Semantics | Mobile UI | [GitHub](https://github.com/google-research-datasets/rico_semantics) | CC-BY-SA-4.0 | UI 语义与图标 grounding | [Paper](https://arxiv.org/abs/2202.13274) | 它在 RICO 上补充了细粒度语义标签、图标标注和 grounding 信号。 |
| 19 | UIBert Datasets | Mobile UI | [GitHub](https://github.com/google-research-datasets/uibert) | CC BY 4.0 | UI grounding 与相似元素检索 | [Paper](https://arxiv.org/abs/2107.13731) | 它包含 AppSim 和 RefExp 两类 Rico 衍生数据，是 UI 表征学习里的经典基准。 |
| 20 | Android in the Wild (AITW) | English | [Site](https://research.google/pubs/android-in-the-wild-a-large-scale-dataset-for-android-device-control/) | Unknown | 基于演示的大规模移动设备控制 | [Paper](https://arxiv.org/abs/2307.10088) | 它包含 71.5 万条众包演示轨迹，是当前最关键的 Android 控制数据之一。 |
| 21 | AndroidControl | English | [GitHub](https://github.com/google-research/google-research/tree/master/android_control) | Apache-2.0 (repo) | 基于人类演示的 Android 控制微调 | [Paper](https://arxiv.org/abs/2406.03679) | 它是 Google 官方发布的数据，包含 833 个应用上的 1.5 万多条控制演示。 |
| 22 | AndroidWorld | English | [GitHub](https://github.com/google-research/android_world) | Apache-2.0 | 手机设备代理与 Android 交互 | [Paper](https://arxiv.org/abs/2405.14573) | 它是当前最清晰、最官方的 smartphone-use agent 环境之一。 |
| 23 | META-GUI | English | [Site](https://x-lance.github.io/META-GUI-Leaderboard/) | Unknown | 面向移动 GUI 的多模态对话代理 | [Paper](https://arxiv.org/abs/2205.11029) | 它是较早公开的 GUI-grounded 多轮移动助手数据集。 |
| 24 | GUICourse | English | [GitHub](https://github.com/RUCBM/GUICourse) | CC BY 4.0 (data) / MIT (code) | GUI grounding、动作预测与 GUI 对话监督 | [Paper](https://arxiv.org/abs/2406.11317) | 它把 GUIEnv、GUIAct、GUIChat 组合成一套较完整的 GUI agent 训练数据。 |
| 25 | MobileAgentBench | English | [Site](https://mobileagentbench.github.io/) | Unknown | 跨真实应用的可控移动端 Agent 评测 | [Paper](https://arxiv.org/abs/2406.08184) | 它用 app-level 任务构建了更可复现的 mobile-agent benchmark。 |
| 26 | MobileBench | Chinese / English mobile | [GitHub](https://github.com/XiaoMi/MobileBench) | Unknown | 多应用移动 Agent 评测 | [Paper](https://arxiv.org/abs/2407.00993) | 它是小米发布、在多应用工作流场景中被频繁引用的 mobile-agent benchmark。 |

## 相关评测

- [Agent 总览](../Agent/README_ZH.md)
- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [WebArena](https://webarena.dev/)
- [OSWorld](https://os-world.github.io/)
- [ScreenSpot-Pro](https://github.com/likaixin2000/ScreenSpot-Pro-GUI-Grounding)

## 收录说明

- 这一页同时保留交互环境、benchmark suite 和 GUI grounding 数据，因为 computer-use 研究本来就同时依赖这三类资源。
- 浏览器、桌面与移动端相关资源已从 [Agent](../Agent/README_ZH.md) 中拆出，形成独立高密度方向。
