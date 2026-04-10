# 多模态（Multimodal）

覆盖视觉语言、图文推理、OCR 感知问答与多模态指令微调的数据集目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Visual Genome | English | [Site](https://visualgenome.org/home) | Unknown | 密集图文对齐 | [Paper](https://arxiv.org/abs/1602.07332) | 包含场景图、属性与区域描述。 |
| 2 | Flickr30k Entities | English | [Site](https://bryanplummer.com/Flickr30kEntities/) | Custom / Flickr Terms of Use | 图文对齐与检索 | [Paper](https://aclanthology.org/Q14-1006/) | 细粒度短语 grounding 基准。 |
| 3 | VQAv2 | English | [Site](https://visualqa.org/) | Unknown | 视觉问答 | [Paper](https://arxiv.org/abs/1612.00837) | 开放式视觉问答标准基准。 |
| 4 | OK-VQA | English | [Site](https://okvqa.allenai.org/) | Unknown | 融合外部知识的视觉问答 | [Paper](https://arxiv.org/abs/1906.00067) | 在多模态 benchmark 工具链里经常被提到。 |
| 5 | GQA | English | [Site](https://cs.stanford.edu/people/dorarad/gqa/) | CC BY 4.0 | 组合式视觉推理 | [Paper](https://arxiv.org/abs/1902.09506) | 比传统 VQA 更强调可控推理。 |
| 6 | NLVR2 | English | [Site](https://lil.nlp.cornell.edu/nlvr/) | Custom / terms of service | 视觉语言推理 | [Paper](https://arxiv.org/abs/1811.00491) | 通过双图像配对做自然语言推理。 |
| 7 | TextVQA | English | [Site](https://textvqa.org/) | Unknown | OCR 感知问答 | [Paper](https://arxiv.org/abs/1904.08920) | 需要理解图像中的文本内容。 |
| 8 | TextCaps | English | [Site](https://textvqa.org/textcaps) | Unknown | 结合场景文本的图像描述 | [Paper](https://arxiv.org/abs/2003.12462) | 适合 OCR 驱动的 captioning。 |
| 9 | ScienceQA | English | [Site](https://scienceqa.github.io/) | CC BY-NC-SA 4.0 | 多模态科学问答 | [Paper](https://arxiv.org/abs/2209.09513) | 包含文本、图片与中小学科学题。 |
| 10 | LLaVA-Instruct-150K | English | [Site](https://llava-vl.github.io/) | Unknown | 多模态指令微调 | [Paper](https://arxiv.org/abs/2304.08485) | 开源 VLM 中最常见的指令数据之一。 |
| 11 | M3IT | Multilingual | [GitHub](https://github.com/LAION-AI/multimodal-instruction-tuning) | Unknown | 开放多模态指令微调 | [Docs](https://github.com/LAION-AI/multimodal-instruction-tuning) | 汇总多个公开视觉语言任务。 |
| 12 | MMBench | Multilingual | [Site](https://mmbench.opencompass.org.cn/home) | Unknown | 多模态评测与比较 | [Docs](https://mmbench.opencompass.org.cn/home) | 在 OpenCompass issue 中是高频 benchmark。 |
| 13 | Objaverse-XL | Visual | [Site](https://objaverse.allenai.org/) | Unknown | 面向 3D 文件的多模态预训练 | [Paper](https://arxiv.org/abs/2307.05663) | 适合需要物体网格和 3D 资产的系统。 |
| 14 | COCO Captions | English | [Site](https://cocodataset.org/) | Mixed / custom | 图像描述与视觉语言预训练 | [Paper](https://arxiv.org/abs/1504.00325) | 多模态 captioning 论文里最默认的参考数据集之一。 |
| 15 | Conceptual Captions | English | [GitHub](https://github.com/google-research-datasets/conceptual-captions) | Unknown | 大规模图文预训练 | [Paper](https://aclanthology.org/P18-1238/) | 很多开放视觉语言预训练基线都会使用的网页级图文语料。 |
| 16 | Visual7W | English | [Site](https://ai.stanford.edu/~yukez/visual7w/) | Unknown | grounded 视觉问答与多模态推理 | [Paper](https://openaccess.thecvf.com/content_cvpr_2016/html/Zhu_Visual7W_Grounded_Question_CVPR_2016_paper.html) | 同时提供 pointing 和文本问答，是经典 grounded QA 基准。 |
| 17 | VizWiz-VQA | English | [Site](https://vizwiz.org/tasks-and-datasets/vqa/) | CC BY 4.0 | 面向可访问性的视觉问答 | [Paper](https://openaccess.thecvf.com/content_cvpr_2018/html/Gurari_VizWiz_Grand_Challenge_CVPR_2018_paper.html) | 常被用来评估真实用户拍摄图片和不可回答问题下的鲁棒性。 |
| 18 | MathVista | English | [Site](https://mathvista.github.io/) | Unknown | 视觉数学推理 | [Paper](https://arxiv.org/abs/2310.02255) | 近两年 VLM 论文里默认会报告的一类高难度 reasoning benchmark。 |
| 19 | MMStar | Multimodal | [Site](https://mmstar-benchmark.github.io/) | Unknown | 视觉依赖与数据泄漏感知评测 | [Paper](https://arxiv.org/abs/2403.20330) | 当前多模态评测工具链里支持度很高的 benchmark。 |
| 20 | MME | Multimodal | [GitHub](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation) | Unknown | 快速感知与认知能力评测 | [Paper](https://arxiv.org/abs/2306.13394) | 在多模态模型报告中几乎是最常见的 quick check 之一。 |
| 21 | MM-Vet | English | [GitHub](https://github.com/yuweihao/MM-Vet) | Unknown | 多模态综合能力评测 | [Paper](https://arxiv.org/abs/2308.02490) | 近两年多模态模型报告里高频出现的高难度 benchmark。 |
| 22 | RefCOCO / RefCOCO+ / RefCOCOg | English | [GitHub](https://github.com/lichengunc/refer) | Mixed / source-dataset terms | 指代表达 grounding 与理解 | [Paper](https://arxiv.org/abs/1511.02283) | 它是 visual grounding 和 referring segmentation 论文里最经典的一组指代表达数据集。 |
| 23 | VCR | English | [Site](https://visualcommonsense.com/) | Custom / dataset license | 视觉常识推理 | [Paper](https://arxiv.org/abs/1811.10830) | 它是超越表层感知、强调 cognition-level visual reasoning 的经典 benchmark。 |
| 24 | SNLI-VE | English | [GitHub](https://github.com/necla-ml/SNLI-VE) | Mixed / source-dataset terms | 视觉蕴含推理 | [Paper](https://arxiv.org/abs/1901.06706) | 它是建立在 SNLI 和 Flickr30k 之上的标准 visual entailment 数据集。 |
| 25 | ChartQA | English | [GitHub](https://github.com/vis-nlp/ChartQA) | Unknown | 图表问答与图表推理 | [Paper](https://aclanthology.org/2022.findings-acl.177/) | 它是图表理解方向最常见的数据集之一，要求模型同时结合视觉信息和逻辑推理。 |
| 26 | InfographicVQA | English | [Site](https://www.docvqa.org/datasets/infographicvqa) | Unknown | 面向信息图的 OCR 密集型问答 | [Paper](https://arxiv.org/abs/2104.12756) | 它强调在复杂信息图版面上做问答，而不是只处理自然图片。 |
| 27 | CLEVR | English | [Site](https://cs.stanford.edu/people/jcjohns/clevr/) | CC BY 4.0 | 诊断式视觉推理 | [Paper](https://arxiv.org/abs/1612.06890) | 它是组合式视觉推理里最经典的合成 benchmark 之一，适合做可控能力分析。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [MMMU](https://mmmu-benchmark.github.io/)
- [MMBench](https://mmbench.opencompass.org.cn/home)
- [SEED-Bench](https://github.com/AILab-CVC/SEED-Bench)
- [POPE](../Benchmarks/README_ZH.md)
- [GAIA](https://huggingface.co/gaia-benchmark)
