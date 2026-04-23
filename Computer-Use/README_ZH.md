# 计算机使用（Computer-Use）

覆盖浏览器、桌面与跨平台 GUI grounding 的 computer-use agent 数据与评测目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Mind2Web | English | [Site](https://osu-nlp-group.github.io/Mind2Web/) | Unknown | 基于真实轨迹的网页导航 | [Paper](https://arxiv.org/abs/2306.06070) | 由真实网站轨迹构建的高信号浏览器代理数据集。 |
| 2 | Online-Mind2Web | English | [GitHub](https://github.com/OSU-NLP-Group/Online-Mind2Web) | MIT | 真实网站上的在线网页代理评测 | [Paper](https://arxiv.org/abs/2504.01382) | 它是持续维护的 live web-agent benchmark，包含 136 个热门网站上的 300 个任务。 |
| 3 | WebCanvas / Mind2Web-Live | English | [GitHub](https://github.com/iMeanAI/WebCanvas) | MIT | 带中间状态的在线网页代理评测 | [Paper](https://arxiv.org/abs/2406.12373) | 它引入 Mind2Web-Live，包含 542 个动态网页任务和中间评测状态，更贴近真实在线环境。 |
| 4 | WebArena | English | [Site](https://webarena.dev/) | Unknown | 真实网站上的浏览器代理 | [Paper](https://arxiv.org/abs/2307.13854) | 它是当前网页代理研究里最常见的 benchmark 之一。 |
| 5 | MiniWoB++ | English | [Site](https://miniwob.farama.org/) | Apache-2.0 | 轻量级网页 UI 控制 | [Docs](https://miniwob.farama.org/) | 它是浏览器式代理交互最经典的入门环境之一。 |
| 6 | WebLINX | English | [Site](https://mcgill-nlp.github.io/weblinx/) | Unknown | 基于演示轨迹的网页代理学习 | [Docs](https://mcgill-nlp.github.io/weblinx/) | 它收集了更真实的人类网页交互与轨迹信号。 |
| 7 | BrowserGym | Interactive Web | [GitHub](https://github.com/ServiceNow/BrowserGym) | Apache-2.0 | 浏览器代理训练环境 | [Docs](https://github.com/ServiceNow/BrowserGym) | 它用统一的 gym 风格接口整合多种 browser tasks。 |
| 8 | WorkArena | Enterprise Web | [Site](https://servicenow.github.io/WorkArena/) | Unknown | 企业流程自动化代理 | [Docs](https://servicenow.github.io/WorkArena/) | 它很适合评测真实业务流程与网页工作流代理。 |
| 9 | VisualWebArena | English | [GitHub](https://github.com/web-arena-x/visualwebarena) | MIT | 带视觉 grounding 的浏览器代理 | [Paper](https://arxiv.org/abs/2401.13649) | 它在 WebArena 基础上加入截图和视觉感知网页任务。 |
| 10 | WebVoyager | English | [GitHub](https://github.com/MinorJerry/WebVoyager) | Apache-2.0 | 真实网站上的端到端网页导航 | [Paper](https://arxiv.org/abs/2401.13919) | 它是评测多模态网页代理与实时网站交互能力时最常见的 benchmark 之一。 |
| 11 | BrowseComp | English | [Site](https://openai.com/index/browsecomp/) | Unknown | 高难网页浏览与多跳事实定位 | [Paper](https://cdn.openai.com/pdf/5e10f4ab-d6f7-442e-9508-59515c65e35d/browsecomp.pdf) | 它是 OpenAI 官方浏览代理 benchmark，强调持续搜索和难定位事实。 |
| 12 | AssistantBench | English | [Site](https://assistantbench.github.io/) | Unknown | 真实长链路网页助手评测 | [Paper](https://arxiv.org/abs/2407.15711) | 它加入更耗时、跨多个网站的任务，能暴露网页助手的规划、搜索和记忆失败。 |
| 13 | OmniACT | GUI screenshots + actions | [HF](https://huggingface.co/datasets/Writer/omniact) | Unknown | 桌面与网页 GUI 动作 grounding | [Paper](https://arxiv.org/abs/2402.17553) | 它是把屏幕指令转换为 PyAutoGUI 风格可执行动作的高频静态 benchmark。 |
| 14 | OSWorld | English | [Site](https://os-world.github.io/) | Unknown | 桌面与操作系统级多模态代理 | [Docs](https://os-world.github.io/) | 它是 computer-use 风格代理评测中的高信号资源。 |
| 15 | WindowsAgentArena | English | [Site](https://microsoft.github.io/WindowsAgentArena/) | MIT | Windows 桌面代理与系统工作流 | [GitHub](https://github.com/microsoft/WindowsAgentArena) | 它是微软官方推出的 Windows 多模态代理 benchmark 平台。 |
| 16 | OS-Atlas Data | GUI screenshots + grounding | [HF](https://huggingface.co/datasets/OS-Copilot/OS-Atlas-data) | Unknown | 跨平台 GUI grounding 预训练 | [Paper](https://arxiv.org/abs/2410.23218) | 它是覆盖桌面、移动与网页截图的大规模 GUI grounding 语料，常用于 computer-use action model。 |
| 17 | ScreenSpot | GUI screenshots | [HF](https://huggingface.co/datasets/rootsautomation/ScreenSpot) | Apache-2.0 | 桌面与移动屏幕上的 GUI grounding | [Paper](https://arxiv.org/abs/2401.10935) | 它是从截图中定位目标 UI 元素时最常用的 benchmark 之一。 |
| 18 | ScreenSpot-Pro | GUI screenshots | [GitHub](https://github.com/likaixin2000/ScreenSpot-Pro-GUI-Grounding) | MIT | 面向 computer-use agent 的高分辨率 GUI grounding | [Paper](https://arxiv.org/abs/2504.07981) | 它已成为桌面代理与专业软件 GUI grounding 评测的重要参考。 |

## 相关评测

- [Agent 总览](../Agent/README_ZH.md)
- [Mobile-UI 总览](../Mobile-UI/README_ZH.md)
- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [WebArena](https://webarena.dev/)
- [Online-Mind2Web](https://github.com/OSU-NLP-Group/Online-Mind2Web)
- [WebCanvas](https://github.com/iMeanAI/WebCanvas)
- [OSWorld](https://os-world.github.io/)
- [AssistantBench](https://assistantbench.github.io/)
- [OS-Atlas](https://osatlas.github.io/)
- [ScreenSpot-Pro](https://github.com/likaixin2000/ScreenSpot-Pro-GUI-Grounding)

## 收录说明

- 本页主要覆盖浏览器、桌面与跨平台的 computer-use 资源。
- 移动端界面理解与 smartphone-agent 资源现已拆分到 [Mobile-UI](../Mobile-UI/README_ZH.md)。
- 浏览器代理方向已经开始变得很密集；如果继续增长，后续可以单独拆成 Web-Agent 类。
