# Multimodal

Vision-language, visual reasoning, OCR-aware VQA, and multimodal instruction-tuning datasets.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Visual Genome | English | [Site](https://visualgenome.org/home) | Unknown | Dense image-text grounding | [Paper](https://arxiv.org/abs/1602.07332) | Scene graphs, attributes, and region captions. |
| 2 | Flickr30k Entities | English | [Site](https://bryanplummer.com/Flickr30kEntities/) | Custom / Flickr Terms of Use | Image-text grounding and retrieval | [Paper](https://aclanthology.org/Q14-1006/) | Fine-grained phrase grounding benchmark. |
| 3 | VQAv2 | English | [Site](https://visualqa.org/) | Unknown | Visual question answering | [Paper](https://arxiv.org/abs/1612.00837) | Standard VQA benchmark for open questions. |
| 4 | OK-VQA | English | [Site](https://okvqa.allenai.org/) | Unknown | Knowledge-aware visual QA | [Paper](https://arxiv.org/abs/1906.00067) | Frequently referenced in multimodal benchmark tooling. |
| 5 | GQA | English | [Site](https://cs.stanford.edu/people/dorarad/gqa/) | CC BY 4.0 | Compositional VQA and reasoning | [Paper](https://arxiv.org/abs/1902.09506) | Better control over reasoning steps than VQA. |
| 6 | NLVR2 | English | [Site](https://lil.nlp.cornell.edu/nlvr/) | Custom / terms of service | Visual reasoning with language grounding | [Paper](https://arxiv.org/abs/1811.00491) | Pairs statements with two-image reasoning. |
| 7 | TextVQA | English | [Site](https://textvqa.org/) | Unknown | OCR-aware question answering | [Paper](https://arxiv.org/abs/1904.08920) | Requires reading scene text. |
| 8 | TextCaps | English | [Site](https://textvqa.org/textcaps) | Unknown | Captioning with scene text | [Paper](https://arxiv.org/abs/2003.12462) | Useful for OCR-grounded captioning models. |
| 9 | ScienceQA | English | [Site](https://scienceqa.github.io/) | CC BY-NC-SA 4.0 | Multimodal science QA | [Paper](https://arxiv.org/abs/2209.09513) | Includes text, images, and grade-school science questions. |
| 10 | LLaVA-Instruct-150K | English | [Site](https://llava-vl.github.io/) | Unknown | Multimodal instruction tuning | [Paper](https://arxiv.org/abs/2304.08485) | Popular open instruction set for VLMs. |
| 11 | M3IT | Multilingual | [GitHub](https://github.com/LAION-AI/multimodal-instruction-tuning) | Unknown | Open multimodal instruction tuning | [Docs](https://github.com/LAION-AI/multimodal-instruction-tuning) | Unifies many public vision-language tasks. |
| 12 | MMBench | Multilingual | [Site](https://mmbench.opencompass.org.cn/home) | Unknown | Multimodal benchmark-style evaluation | [Docs](https://mmbench.opencompass.org.cn/home) | A repeated point of discussion in OpenCompass issues. |
| 13 | Objaverse-XL | Visual | [Site](https://objaverse.allenai.org/) | Unknown | 3D-ready multimodal pretraining and grounding | [Paper](https://arxiv.org/abs/2307.05663) | Useful when multimodal systems need object files beyond images. |
| 14 | COCO Captions | English | [Site](https://cocodataset.org/) | Mixed / custom | Image captioning and vision-language pretraining | [Paper](https://arxiv.org/abs/1504.00325) | Still the default captioning reference set in many multimodal papers. |
| 15 | Conceptual Captions | English | [GitHub](https://github.com/google-research-datasets/conceptual-captions) | Unknown | Web-scale image-text pretraining | [Paper](https://aclanthology.org/P18-1238/) | A standard open image-text corpus behind many VLM pretraining baselines. |
| 16 | Visual7W | English | [Site](https://ai.stanford.edu/~yukez/visual7w/) | Unknown | Grounded visual QA and multimodal reasoning | [Paper](https://openaccess.thecvf.com/content_cvpr_2016/html/Zhu_Visual7W_Grounded_Question_CVPR_2016_paper.html) | A widely used grounded QA set with pointing and textual question answering. |
| 17 | VizWiz-VQA | English | [Site](https://vizwiz.org/tasks-and-datasets/vqa/) | CC BY 4.0 | Accessibility-focused visual question answering | [Paper](https://openaccess.thecvf.com/content_cvpr_2018/html/Gurari_VizWiz_Grand_Challenge_CVPR_2018_paper.html) | Commonly used to test robustness to real user photos and unanswerable questions. |
| 18 | MathVista | English | [Site](https://mathvista.github.io/) | Unknown | Visual mathematical reasoning | [Paper](https://arxiv.org/abs/2310.02255) | One of the default reasoning-heavy VLM benchmarks in recent papers. |
| 19 | MMStar | Multimodal | [Site](https://mmstar-benchmark.github.io/) | Unknown | Visual dependency and leakage-aware evaluation | [Paper](https://arxiv.org/abs/2403.20330) | High-signal benchmark supported by current multimodal eval toolkits. |
| 20 | MME | Multimodal | [GitHub](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation) | Unknown | Quick perception-vs-cognition evaluation | [Paper](https://arxiv.org/abs/2306.13394) | Near-ubiquitous quick check in multimodal model reports. |
| 21 | MM-Vet | English | [GitHub](https://github.com/yuweihao/MM-Vet) | Unknown | Integrated multimodal capability evaluation | [Paper](https://arxiv.org/abs/2308.02490) | A very common high-difficulty benchmark in recent multimodal model reports. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [MMMU](https://mmmu-benchmark.github.io/)
- [MMBench](https://mmbench.opencompass.org.cn/home)
- [GAIA](https://huggingface.co/gaia-benchmark)
