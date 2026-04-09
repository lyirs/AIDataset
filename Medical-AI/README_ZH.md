# 医疗 AI（Medical-AI）

覆盖临床、医学文本、医学影像与医疗场景数据的目录，并特别关注访问限制。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | MIMIC-IV | English | [Site](https://physionet.org/content/mimiciv/) | Credentialed Health Data License 1.5.0 | ICU 与住院临床建模 | [Docs](https://physionet.org/content/mimiciv/) | 临床 ML 和医疗 NLP 里最核心的去标识化 EHR 资源之一。 |
| 2 | eICU-CRD | English | [Site](https://physionet.org/content/eicu-crd/) | Credentialed Health Data License 1.5.0 | 多中心 ICU 结局建模 | [Docs](https://physionet.org/content/eicu-crd/) | 多医院 ICU 数据，对 MIMIC 形成重要补充。 |
| 3 | MIMIC-CXR-JPG | English | [Site](https://physionet.org/content/mimic-cxr-jpg/) | Credentialed Health Data License 1.5.0 | 胸部 X 光视觉语言建模 | [Paper](https://arxiv.org/abs/1901.07042) | 胸部放射影像里最常被引用的基础 benchmark 之一。 |
| 4 | MedNLI | English | [Site](https://physionet.org/content/mednli/1.0.0/) | Credentialed Health Data License 1.5.0 | 临床自然语言推断 | [Docs](https://physionet.org/content/mednli/1.0.0/) | 医生标注句对构成的高频 clinical NLI 数据集。 |
| 5 | CheXpert | English | [Site](https://stanfordmlgroup.github.io/competitions/chexpert/) | Unknown | 胸部影像分类 | [Docs](https://stanfordmlgroup.github.io/competitions/chexpert/) | 医学视觉论文里最经典的胸片分类基准之一。 |
| 6 | BraTS | English | [Site](https://www.med.upenn.edu/cbica/brats/) | Unknown | 脑肿瘤分割 | [Docs](https://www.med.upenn.edu/cbica/brats/) | MRI 脑肿瘤分割领域最 canonical 的 benchmark 家族。 |
| 7 | The Cancer Imaging Archive | Medical imaging | [Site](https://www.cancerimagingarchive.net/) | Mixed / collection-specific | 医学影像检索与肿瘤影像建模 | [Docs](https://www.cancerimagingarchive.net/) | 许多高频肿瘤影像 collection 的官方公共档案入口。 |
| 8 | PMC Open Access Subset | Biomedical literature | [Site](https://pmc.ncbi.nlm.nih.gov/tools/openftlist/) | Mixed / article-specific OA licenses | 生物医学文献预训练 | [Docs](https://pmc.ncbi.nlm.nih.gov/tools/openftlist/) | 生物医学全文开放语料和文献挖掘的重要来源。 |
| 9 | PubMedQA | English | [GitHub](https://github.com/pubmedqa/pubmedqa) | MIT | 生物医学问答 | [Docs](https://github.com/pubmedqa/pubmedqa) | 面向 biomedical abstract 的 yes-no-maybe 推理 benchmark。 |
| 10 | MedMCQA | English | [GitHub](https://github.com/medmcqa/medmcqa) | MIT | 医学考试问答 | [Docs](https://github.com/medmcqa/medmcqa) | 大规模医学考试 QA 数据集，适合事实与临床推理评测。 |
| 11 | n2c2 Clinical NLP Challenge Sets | English clinical notes | [Site](https://n2c2.dbmi.hms.harvard.edu/data-sets) | Custom / data use agreement | 临床 NLP 共享任务评测 | [Docs](https://n2c2.dbmi.hms.harvard.edu/data-sets) | 最具代表性的临床 NLP 挑战赛数据集合之一，访问通常受 challenge 条款约束。 |
| 12 | Medical Segmentation Decathlon | Medical imaging | [Site](https://medicaldecathlon.com/) | CC BY-SA 4.0 | 通用医学图像分割 | [Paper](https://arxiv.org/abs/2106.05735) | MICCAI 风格医学分割论文里高频出现的多器官、多模态 benchmark 家族。 |
| 13 | MIMIC-III | English | [Site](https://physionet.org/content/mimiciii/) | Credentialed Health Data License 1.5.0 | 临床时序与 EHR 建模 | [Docs](https://physionet.org/content/mimiciii/) | MIMIC-IV 的经典前代版本，也是临床 ML 论文里引用率极高的数据集。 |
| 14 | NIH ChestX-ray14 | English | [Site](https://nihcc.app.box.com/v/ChestXray-NIHCC) | Unknown | 胸片分类与病灶定位 | [Paper](https://arxiv.org/abs/1705.02315) | 医学视觉里最基础、最常见的大规模胸部 X 光 benchmark 之一。 |
| 15 | ISIC Archive | Medical imaging | [Site](https://www.isic-archive.com/) | Mixed / challenge-specific | 皮肤病灶分析与皮肤镜图像建模 | [Docs](https://challenge.isic-archive.com/data/) | 皮肤病灶分类和分割研究中复用率极高的公开资源。 |
| 16 | CAMELYON16 | Digital pathology | [Site](https://camelyon16.grand-challenge.org/) | Unknown | 全切片淋巴结转移检测 | [Paper](https://jamanetwork.com/journals/jama/article-abstract/2763118) | 病理 WSI 里的经典 benchmark，常用于弱监督、定位和切片级分类。 |
| 17 | TCGA | Cancer genomics | [Site](https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga) | Mixed / open + controlled access | 癌症基因组与多组学建模 | [Docs](https://gdc.cancer.gov/resources-tcga-users) | 这是癌症多组学研究里最具标志性的 landmark 项目之一。 |
| 18 | LIDC-IDRI | Medical imaging | [Site](https://www.cancerimagingarchive.net/collection/lidc-idri/) | CC BY 3.0 | 肺结节检测与分割 | [Docs](https://www.cancerimagingarchive.net/collection/lidc-idri/) | 肺部 CT 结节检测、标注和 CAD 研究里最经典的公开 benchmark 之一。 |
| 19 | UK Biobank | Biomedical multimodal data | [Site](https://www.ukbiobank.ac.uk/about-us/how-we-work/access-to-uk-biobank-data/) | Custom / application-based access | 人群级健康建模 | [Docs](https://www.ukbiobank.ac.uk/use-our-data/apply-for-access/) | 这是当今最重要的大规模生物医学资源之一，但访问需申请并受协议约束。 |
| 20 | PadChest | Spanish radiology + images | [Site](https://bimcv.cipf.es/bimcv-projects/padchest/) | Custom / research use agreement | 胸部放射视觉语言学习 | [Docs](https://bimcv.cipf.es/bimcv-projects/padchest/padchest-dataset-research-use-agreement/) | 来自西班牙胸部放射实践的高信号胸片数据集，带报告和丰富标签。 |
| 21 | VinDr-CXR | English | [Site](https://physionet.org/content/vindr-cxr/) | Credentialed Health Data License 1.5.0 | 胸部 X 光检测与放射科医生框标注定位 | [Paper](https://arxiv.org/abs/2012.15029) | 它是 CheXpert 之后非常重要的胸片 benchmark，但需要完成 PhysioNet 资质访问。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [CBLUE](https://github.com/CBLUEbenchmark/CBLUE)
- [BioASQ](http://bioasq.org/)
- [CheXpert Leaderboard](https://stanfordmlgroup.github.io/competitions/chexpert/)
- [ISIC Challenge](https://challenge.isic-archive.com/data/)

## 收录说明

- 本页会同时收录开放数据与需资质访问的数据，因为医学 AI 研究高度依赖这两类资源。
- 如果某个数据需要 credentialing 或 challenge terms，表格会明确保留这种限制，而不会假装它是零门槛访问。
