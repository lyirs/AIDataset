# 移动界面（Mobile-UI）

覆盖移动端界面理解、屏幕 grounding 与 Android agent 数据和评测目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Screen2Words | English | [GitHub](https://github.com/google-research-datasets/screen2words) | Unknown | 移动端 UI 摘要与屏幕描述 | [Paper](https://arxiv.org/abs/2108.03353) | 它是把移动界面转成自然语言摘要时最基础、最常被复用的大规模数据集之一。 |
| 2 | Widget Caption | English | [GitHub](https://github.com/google-research-datasets/widget-caption) | CC BY 4.0 | UI 元素描述与功能说明生成 | [Paper](https://arxiv.org/abs/2010.04295) | 它是移动端控件功能描述学习里最标准的一类监督数据。 |
| 3 | ScreenQA | English | [GitHub](https://github.com/google-research-datasets/screen_qa) | CC BY 4.0 | 面向 App 截图的问答 | [Paper](https://arxiv.org/abs/2209.08199) | 它是在 Rico 截图上构建的大规模 Screen QA 数据，常被用于 screen understanding 评测。 |
| 4 | Screen Annotation | Mobile UI | [GitHub](https://github.com/google-research-datasets/screen_annotation) | CC BY 4.0 | 密集 UI 元素标注与屏幕解析 | [Paper](https://arxiv.org/abs/2402.04615) | 它是 ScreenAI 一类 UI 理解模型的重要监督来源。 |
| 5 | RICO | Mobile UI | [Site](https://www.interactionmining.org/archive/rico) | Unknown | 移动端 UI 结构与界面理解 | [Paper](https://arxiv.org/abs/1803.10702) | 它是 Android UI 理解和 mobile-agent 论文里最经典的大规模数据集之一。 |
| 6 | RICO Semantics | Mobile UI | [GitHub](https://github.com/google-research-datasets/rico_semantics) | CC-BY-SA-4.0 | UI 语义与图标 grounding | [Paper](https://arxiv.org/abs/2202.13274) | 它在 RICO 上补充了细粒度语义标签、图标标注和 grounding 信号。 |
| 7 | UIBert Datasets | Mobile UI | [GitHub](https://github.com/google-research-datasets/uibert) | CC BY 4.0 | UI grounding 与相似元素检索 | [Paper](https://arxiv.org/abs/2107.13731) | 它包含 AppSim 和 RefExp 两类 Rico 衍生数据，是 UI 表征学习里的经典基准。 |
| 8 | MoTIF | English | [GitHub](https://github.com/aburns4/MoTIF) | Unknown | 带可行性反馈的移动任务自动化 | [Paper](https://arxiv.org/abs/2202.02312) | 它是较早把任务可行性、后续澄清反馈和真实移动操作结合起来的经典数据集。 |
| 9 | Android in the Wild (AITW) | English | [Site](https://research.google/pubs/android-in-the-wild-a-large-scale-dataset-for-android-device-control/) | Unknown | 基于演示的大规模移动设备控制 | [Paper](https://arxiv.org/abs/2307.10088) | 它包含 71.5 万条众包演示轨迹，是当前最关键的 Android 控制数据之一。 |
| 10 | AndroidControl | English | [GitHub](https://github.com/google-research/google-research/tree/master/android_control) | Apache-2.0 (repo) | 基于人类演示的 Android 控制微调 | [Paper](https://arxiv.org/abs/2406.03679) | 它是 Google 官方发布的数据，包含 833 个应用上的 1.5 万多条控制演示。 |
| 11 | AndroidWorld | English | [GitHub](https://github.com/google-research/android_world) | Apache-2.0 | 手机设备代理与 Android 交互 | [Paper](https://arxiv.org/abs/2405.14573) | 它是当前最清晰、最官方的 smartphone-use agent 环境之一。 |
| 12 | LlamaTouch | English | [GitHub](https://github.com/LlamaTouch/LlamaTouch) | Unknown | 高保真移动 UI 自动化评测 | [Paper](https://arxiv.org/abs/2404.16054) | 它在真实移动环境中提供 496 个任务，并用 essential-state matching 做可扩展评测。 |
| 13 | META-GUI | English | [Site](https://x-lance.github.io/META-GUI-Leaderboard/) | Unknown | 面向移动 GUI 的多模态对话代理 | [Paper](https://arxiv.org/abs/2205.11029) | 它是较早公开的 GUI-grounded 多轮移动助手数据集。 |
| 14 | GUICourse | English | [GitHub](https://github.com/RUCBM/GUICourse) | CC BY 4.0 (data) / MIT (code) | GUI grounding、动作预测与 GUI 对话监督 | [Paper](https://arxiv.org/abs/2406.11317) | 它把 GUIEnv、GUIAct、GUIChat 组合成一套较完整的 GUI agent 训练数据。 |
| 15 | AMEX | Mobile UI | [HF](https://huggingface.co/datasets/Yuxiang007/AMEX) | Unknown | 多标注移动 GUI 智能体数据 | [Paper](https://arxiv.org/abs/2407.17490) | 它强调更丰富的多标注 supervision，用于训练和评测移动 GUI agent。 |
| 16 | GUI Odyssey | Mobile UI | [GitHub](https://github.com/OpenGVLab/GUI-Odyssey) | Unknown | 跨应用移动 GUI 导航 | [Paper](https://arxiv.org/abs/2406.08451) | 它是面向 cross-app navigation agent 的综合型移动端数据集。 |
| 17 | MobileAgentBench | English | [Site](https://mobileagentbench.github.io/) | Unknown | 跨真实应用的可控移动端 Agent 评测 | [Paper](https://arxiv.org/abs/2406.08184) | 它用 app-level 任务构建了更可复现的 mobile-agent benchmark。 |
| 18 | MobileBench | Chinese / English mobile | [GitHub](https://github.com/XiaoMi/MobileBench) | Unknown | 多应用移动 Agent 评测 | [Paper](https://arxiv.org/abs/2407.00993) | 它是小米发布、在多应用工作流场景中被频繁引用的 mobile-agent benchmark。 |

## 相关评测

- [Computer-Use 总览](../Computer-Use/README_ZH.md)
- [Agent 总览](../Agent/README_ZH.md)
- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [AndroidWorld](https://github.com/google-research/android_world)
- [MobileAgentBench](https://mobileagentbench.github.io/)

## 收录说明

- 本页主要覆盖移动端截图、UI 语义、Android 控制轨迹与 smartphone-agent benchmark。
- 浏览器和桌面方向的 computer-use 资源保留在 [Computer-Use](../Computer-Use/README_ZH.md)。
- 如果这个分类继续增长，后续应拆成 `Mobile-Understanding` 和 `Mobile-Agent`。
