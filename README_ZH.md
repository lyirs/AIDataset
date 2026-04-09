# AIDataset

一个覆盖主要 AI 研究方向的数据集、评测与数据门户目录，包括 NLP、计算机视觉、多模态、语音与音频理解、时间序列、图学习、推荐系统、检索、LLM、Agent、机器人、具身智能、自动驾驶、遥感、科学 AI、医疗 AI 等方向。

[英文版](README.md)

## 项目概览

- 25 个分类目录
- 407 条主条目
- 链接整理与核验日期：2026-04-09

## 收录规则

- 只收录对训练、评测或研究导航有明确价值的公开数据集、benchmark 或发现型门户。
- 优先收录那些在顶会论文、教程和强基线对比表中持续高频出现的数据集。
- 优先使用官方站点、官方 GitHub 仓库、Hugging Face 数据集页或可信公共门户。
- 许可信息按上游公开信息填写；无法确认时明确写成 `Unknown`。
- 部分安全评测和 benchmark 资源本质上是 eval registry 或 failure taxonomy，不会冒充成 raw dataset。
- 本仓库只是索引，不镜像也不再分发任何数据文件。

## 分类导航

| 分类 | 方向说明 | 英文 | 中文 | 数量 |
| --- | --- | --- | --- | --- |
| 自然语言处理（NLP） | 文本方向数据集，覆盖 NER、QA、摘要、推理、分类、多语迁移与语言理解。 | [英文](NLP/README.md) | [中文](NLP/README_ZH.md) | 29 |
| 计算机视觉（CV） | 图像方向数据集，覆盖分类、检测、分割、grounding、场景理解、RGB-D 与细粒度识别。 | [英文](CV/README.md) | [中文](CV/README_ZH.md) | 31 |
| 视频与三维（Video-3D） | 视频、第一视角、点云、3D 场景与形状数据。 | [英文](Video-3D/README.md) | [中文](Video-3D/README_ZH.md) | 14 |
| 自动驾驶（Autonomous-Driving） | 自动驾驶感知、三维检测、跟踪、预测、地图与协同感知数据。 | [英文](Autonomous-Driving/README.md) | [中文](Autonomous-Driving/README_ZH.md) | 17 |
| 遥感（Remote-Sensing） | 卫星、航拍、高空、多光谱、SAR 与地理空间制图数据。 | [英文](Remote-Sensing/README.md) | [中文](Remote-Sensing/README_ZH.md) | 14 |
| 多模态（Multimodal） | 视觉语言、VQA、图文对齐、图表与 OCR 感知推理、多模态指令数据。 | [英文](Multimodal/README.md) | [中文](Multimodal/README_ZH.md) | 21 |
| 语音与音频（Speech-Audio） | ASR、语音翻译、说话人或语言识别、情感语音与语音生成数据。 | [英文](Speech-Audio/README.md) | [中文](Speech-Audio/README_ZH.md) | 19 |
| 音频理解（Audio-Understanding） | 声音事件、音频描述、音频语言学习与音频基础模型评测数据。 | [英文](Audio-Understanding/README.md) | [中文](Audio-Understanding/README_ZH.md) | 10 |
| 时间序列（Time-Series） | 预测、分类、异常检测、临床时序与时空序列数据。 | [英文](Time-Series/README.md) | [中文](Time-Series/README_ZH.md) | 13 |
| 文档 AI（Document-AI） | OCR、版面分析、表单、票据、表格、图表与文档问答数据。 | [英文](Document-AI/README.md) | [中文](Document-AI/README_ZH.md) | 20 |
| 代码（Code） | 代码生成、修复、执行、仓库理解与软件工程 Agent 数据。 | [英文](Code/README.md) | [中文](Code/README_ZH.md) | 16 |
| 搜索与检索（Search-Retrieval） | embedding、检索、reranking、跨语言 IR、RAG grounding 与多模态或音频文本检索数据。 | [英文](Search-Retrieval/README.md) | [中文](Search-Retrieval/README_ZH.md) | 18 |
| 图学习（Graph-Learning） | 节点、链路、图级、分子图、知识图谱、异构图与时序图学习数据。 | [英文](Graph-Learning/README.md) | [中文](Graph-Learning/README_ZH.md) | 12 |
| 推荐系统（Recommender-Systems） | 协同过滤、排序、CTR、新闻推荐、bandit 与工业推荐数据。 | [英文](Recommender-Systems/README.md) | [中文](Recommender-Systems/README_ZH.md) | 12 |
| 大语言模型（LLM） | 预训练语料、指令微调、合成监督、偏好数据与对齐数据。 | [英文](LLM/README.md) | [中文](LLM/README_ZH.md) | 12 |
| 大语言模型评测（LLM-Evals） | 覆盖指令遵循、推理、真实性、聊天与长上下文能力的大语言模型评测数据。 | [英文](LLM-Evals/README.md) | [中文](LLM-Evals/README_ZH.md) | 21 |
| 智能体（Agent） | 工具调用、网页代理、computer use、软件工程代理与环境交互数据。 | [英文](Agent/README.md) | [中文](Agent/README_ZH.md) | 20 |
| 机器人与强化学习（Robotics-RL） | 离线强化学习、模仿学习、机器人操作、轨迹与仿真器主导的机器人学习数据。 | [英文](Robotics-RL/README.md) | [中文](Robotics-RL/README_ZH.md) | 13 |
| 具身智能（Embodied-AI） | 具身导航、指令执行、第一视角感知与语言条件行为数据。 | [英文](Embodied-AI/README.md) | [中文](Embodied-AI/README_ZH.md) | 13 |
| 科学 AI（Scientific-AI） | 分子、蛋白质、材料、反应与科学文献数据。 | [英文](Scientific-AI/README.md) | [中文](Scientific-AI/README_ZH.md) | 18 |
| 医疗 AI（Medical-AI） | 临床、生物医学 NLP、放射、病理、医学影像与医疗场景数据。 | [英文](Medical-AI/README.md) | [中文](Medical-AI/README_ZH.md) | 20 |
| 金融与法律（Finance-Legal） | 金融、监管、法律推理、抽取、文件分析、合同理解与合规数据。 | [英文](Finance-Legal/README.md) | [中文](Finance-Legal/README_ZH.md) | 14 |
| 综合评测（Benchmarks） | 覆盖 NLP、CV、多模态、检索、代码、Agent 与通用平台的跨领域评测套件。 | [英文](Benchmarks/README.md) | [中文](Benchmarks/README_ZH.md) | 12 |
| 数据门户（Data-Portals） | 面向 AI 数据与 benchmark 的注册表、搜索入口与发现型门户。 | [英文](Data-Portals/README.md) | [中文](Data-Portals/README_ZH.md) | 8 |
| 安全评测（Safety-Evals） | 面向 LLM 与 Agent 的安全评测、风险 taxonomy、红队资源与安全 benchmark。 | [英文](Safety-Evals/README.md) | [中文](Safety-Evals/README_ZH.md) | 10 |

## 来源类型

- GitHub：官方组织仓库、任务仓库、评测仓库与维护者仓库。
- 公共门户：Hugging Face、OpenML、OpenDataLab、UCI、OpenSLR、NIST 等。
- 官方站点：任务主页、数据集着陆页、项目官网与榜单页面。
