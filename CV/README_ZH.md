# 计算机视觉（CV）

图像分类、检测、分割、场景理解、RGB-D 感知与细粒度识别方向的核心视觉数据集目录。

[英文版](README.md) | [返回首页](../README_ZH.md)

| 序号 | 数据集 | 语言 | 链接 | 许可 | 适用方向 | 论文/文档 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | ImageNet | Visual | [Site](https://www.image-net.org/) | Research only / custom | 大规模图像分类 | [Docs](https://www.image-net.org/) | 视觉预训练时代的基础资源。 |
| 2 | COCO | Visual | [Site](https://cocodataset.org/) | Mixed / custom | 检测、分割与图像描述 | [Paper](https://arxiv.org/abs/1405.0312) | 现代检测模型最常用基准之一。 |
| 3 | Open Images | Visual | [Site](https://storage.googleapis.com/openimages/web/index.html) | CC BY 2.0 + annotation terms | 大规模检测与关系识别 | [Paper](https://arxiv.org/abs/1811.00982) | Google 发布的大规模开放图像集合。 |
| 4 | CIFAR-10/100 | Visual | [Site](https://www.cs.toronto.edu/~kriz/cifar.html) | Unknown | 轻量级分类基线 | [Docs](https://www.cs.toronto.edu/~kriz/cifar.html) | 适合快速实验和教学演示。 |
| 5 | Cityscapes | Visual | [Site](https://www.cityscapes-dataset.com/) | Custom | 城市场景分割 | [Paper](https://arxiv.org/abs/1604.01685) | 高质量街景细粒度标注。 |
| 6 | ADE20K | Visual | [Site](https://groups.csail.mit.edu/vision/datasets/ADE20K/) | Custom | 场景解析与语义分割 | [Paper](https://arxiv.org/abs/1608.05442) | 覆盖丰富场景类别与像素标签。 |
| 7 | LVIS | Visual | [Site](https://www.lvisdataset.org/) | Unknown | 长尾实例分割 | [Paper](https://arxiv.org/abs/1908.03195) | 适合稀有类别识别研究。 |
| 8 | Objects365 | Visual | [Site](https://www.objects365.org/) | Unknown | 大规模检测预训练 | [Paper](https://arxiv.org/abs/1901.07518) | 在 COCO 之外补充更广物体覆盖。 |
| 9 | BDD100K | Visual | [Site](https://bdd-data.berkeley.edu/) | Custom | 自动驾驶多任务训练 | [Paper](https://arxiv.org/abs/1805.04687) | 包含检测、车道线、可行驶区域与跟踪。 |
| 10 | SA-1B | Visual | [GitHub](https://github.com/facebookresearch/segment-anything) | Research license | 基础分割模型训练 | [Paper](https://arxiv.org/abs/2304.02643) | Segment Anything 配套的十亿级掩码数据。 |
| 11 | PASCAL VOC | Visual | [Site](https://www.robots.ox.ac.uk/~vgg/projects/pascal/VOC/) | Mixed / source-image terms | 检测与语义分割基线 | [Docs](https://www.robots.ox.ac.uk/~vgg/projects/pascal/VOC/) | COCO 之前最经典的视觉基准，至今仍用于历史可比性实验。 |
| 12 | Places365 | Visual | [Site](https://places2.csail.mit.edu/) | Non-commercial research / educational only | 场景识别与场景预训练 | [Docs](https://places2.csail.mit.edu/) | 表征学习论文里常见的 scene recognition 锚点。 |
| 13 | NYU Depth V2 | Visual | [Site](https://cs.nyu.edu/~fergus/datasets/nyu_depth_v2.html) | Unknown | 室内 RGB-D 分割与深度理解 | [Docs](https://cs.nyu.edu/~fergus/datasets/nyu_depth_v2.html) | 带密集标注的经典室内 RGB-D 基准。 |
| 14 | SUN RGB-D | Visual | [Site](https://rgbd.cs.princeton.edu/) | Unknown | 室内场景理解与 3D 目标检测 | [Docs](https://rgbd.cs.princeton.edu/) | 室内感知与 RGB-D 迁移研究中的高频数据集。 |
| 15 | Mapillary Vistas | Visual | [Site](https://www.mapillary.com/dataset/vistas/) | Custom / research-use terms | 街景分割与域泛化 | [GitHub](https://github.com/mapillary/mapillary_vistas) | 在地域与天气多样性上明显强于很多老街景数据集。 |
| 16 | iNaturalist Open Dataset | Visual | [GitHub](https://github.com/inaturalist/inaturalist-open-data) | Mixed / observation-specific CC terms | 细粒度识别与长尾分类 | [Docs](https://www.inaturalist.org/pages/developers) | challenge 版本在 FGVC 和生物识别论文中仍很常见。 |
| 17 | WIDER FACE | Visual | [Site](https://mmlab.ie.cuhk.edu.hk/projects/WIDERFace/) | Unknown | 真实场景人脸检测 | [Docs](https://mmlab.ie.cuhk.edu.hk/projects/WIDERFace/) | 许多对比实验里默认会出现的困难人脸检测基准。 |
| 18 | CUB-200-2011 | Visual | [Site](https://www.vision.caltech.edu/datasets/cub_200_2011/) | Non-commercial research / educational only | 细粒度分类与部位定位 | [Docs](https://www.vision.caltech.edu/datasets/cub_200_2011/) | 带部位和属性标注的经典 FGVC 锚点数据集。 |
| 19 | CelebA | Visual | [Site](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) | Non-commercial research only | 人脸属性识别与人脸分析 | [Paper](https://openaccess.thecvf.com/content_iccv_2015/html/Liu_Deep_Learning_Face_ICCV_2015_paper.html) | 人脸识别、编辑、生成等方向里都极常见的经典数据集。 |
| 20 | Food-101 | Visual | [Site](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/) | Unknown | 食物识别与迁移学习 | [Paper](https://arxiv.org/abs/1409.0575) | 领域图像分类里最常见的数据集之一。 |
| 21 | Oxford-IIIT Pet | Visual | [Site](https://www.robots.ox.ac.uk/~vgg/data/pets/) | CC BY-SA 4.0 | 宠物细粒度分类与分割 | [Paper](https://www.robots.ox.ac.uk/~vgg/publications/2012/Parkhi12/) | 小中规模迁移学习和分割实验中长期高频出现。 |
| 22 | Oxford 102 Flowers | Visual | [Site](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/) | Unknown | 花卉细粒度分类 | [Paper](https://www.robots.ox.ac.uk/~vgg/publications/2008/Nilsback08/) | FGVC 和视觉语言迁移论文里都很常见。 |
| 23 | ImageNet-C | Visual | [GitHub](https://github.com/hendrycks/robustness) | Unknown | 图像腐蚀鲁棒性评测 | [Paper](https://arxiv.org/abs/1903.12261) | 现在仍是很多视觉和基础模型论文里的默认 robustness 检查。 |
| 24 | ImageNetV2 | Visual | [GitHub](https://github.com/modestyachts/ImageNetV2) | Unknown | 分布偏移下的 ImageNet 评测 | [Paper](https://arxiv.org/abs/1902.10811) | 常被用来测试模型是否泛化到原始验证集之外。 |
| 25 | ObjectNet | Visual | [Site](https://objectnet.dev/) | Unknown | 去偏置的真实世界识别偏移评测 | [Paper](https://papers.neurips.cc/paper_files/paper/2019/file/97af07a14cacba681feacf3012730892-Paper.pdf) | 很适合检验视角、背景变化下的真实识别能力。 |
| 26 | V3Det | Visual | [Site](https://v3det.openxlab.org.cn/) | Unknown | 开放词表目标检测 | [Paper](https://arxiv.org/abs/2304.03752) | 面向现代 open-world perception 的大类别检测 benchmark，近年引用频率很高。 |
| 27 | PACO | Visual | [GitHub](https://github.com/facebookresearch/paco) | Unknown | 部件与属性识别 | [Paper](https://arxiv.org/abs/2301.01795) | 让视觉感知从框和掩码进一步扩展到物体部件与属性层面。 |
| 28 | ImageNet-A | Visual | [GitHub](https://github.com/hendrycks/natural-adv-examples) | MIT | 自然对抗鲁棒性评测 | [Paper](https://arxiv.org/abs/1907.07174) | 它是很多 ImageNet 系模型在合成腐蚀之外的标准压力测试。 |
| 29 | ImageNet-R | Visual | [GitHub](https://github.com/hendrycks/imagenet-r) | MIT | 渲染分布偏移鲁棒性评测 | [Paper](https://arxiv.org/abs/2006.16241) | 在 CLIP、ViT 和 robustness 对比表里非常常见。 |
| 30 | FGVC-Aircraft | Visual | [Site](https://www.robots.ox.ac.uk/~vgg/data/fgvc-aircraft/) | Non-commercial research only | 细粒度飞机识别 | [Paper](https://arxiv.org/abs/1306.5151) | 和 birds、pets、flowers 一样，属于细粒度识别里的 canonical 数据集。 |
| 31 | DTD | Visual | [Site](https://www.robots.ox.ac.uk/~vgg/data/dtd/) | Research only / custom | 纹理识别与材质表征学习 | [Paper](https://arxiv.org/abs/1311.3618) | 在纹理识别、迁移学习和表征学习论文里仍然很常见。 |
| 32 | VisDA-2017 | Visual | [Site](http://ai.bu.edu/visda-2017/) | Unknown | 合成到真实域迁移 | [Paper](https://arxiv.org/abs/1710.06924) | 它是视觉领域 simulation-to-reality domain adaptation 最经典的大规模 benchmark 之一。 |
| 33 | DomainNet | Visual | [Site](http://ai.bu.edu/M3SDA/) | Non-commercial research / fair use notice | 多源域迁移与域泛化 | [Paper](https://arxiv.org/abs/1812.01754) | 六个视觉域组成的大规模跨域基准，在 transfer 论文里长期高频出现。 |
| 34 | ImageNet-Sketch | Visual | [GitHub](https://github.com/HaohanWang/ImageNet-Sketch) | Unknown | 素描风格分布偏移评测 | [Paper](https://arxiv.org/abs/1905.13549) | 常和 ImageNet-A、R、V2、ObjectNet 一起出现在 robustness 对比表中。 |
| 35 | Office-Home | Visual | [Site](https://www.hemanthdv.org/officeHomeDataset.html) | Non-commercial research / fair use notice | 域迁移与域泛化 | [Paper](https://openaccess.thecvf.com/content_cvpr_2017/html/Venkateswara_Deep_Hashing_Network_CVPR_2017_paper.html) | 四个视觉域组成的经典 benchmark，在 transfer learning 对比表里到现在仍然非常常见。 |
| 36 | PACS | Visual | [Site](https://domaingeneralization.github.io/) | Unknown | 大风格偏移下的域泛化 | [Paper](https://openaccess.thecvf.com/content_ICCV_2017/html/Li_Deeper_Broader_and_ICCV_2017_paper.html) | Art-Painting、Cartoon、Photo、Sketch 四域组成的 canonical DG benchmark，很多论文仍会优先报告它。 |
| 37 | CompCars | Visual | [Site](https://mmlab.ie.cuhk.edu.hk/datasets/comp_cars/) | Non-commercial research only | 细粒度车辆识别与属性预测 | [Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/html/Yang_A_Large-Scale_Car_2015_CVPR_paper.html) | 它提供车型、视角、部件和验证任务，是车辆视觉里长期高频使用的数据集。 |
| 38 | SUN397 | Visual | [Site](https://3dvision.princeton.edu/projects/2010/SUN/) | Research only / custom | 场景识别与 scene-centric 迁移 | [Paper](https://3dvision.princeton.edu/projects/2010/SUN/paper.pdf) | 它至今仍是和 Places 系数据并列出现的 canonical scene recognition benchmark。 |
| 39 | COCO-Stuff | Visual | [GitHub](https://github.com/nightrome/cocostuff) | Mixed / COCO terms + CC BY 4.0 annotations | thing 与 stuff 联合语义分割 | [Paper](https://arxiv.org/abs/1612.03716) | 它把 COCO 扩展成稠密场景标签资源，在 semantic、panoptic 和 open-vocabulary segmentation 论文里都很常见。 |
| 40 | Office-31 | Visual | [Site](https://faculty.cc.gatech.edu/~judy/domainadapt/) | Unknown | 经典小规模域迁移 | [Paper](http://www.cs.uml.edu/~saenko/projects/eccv10.pdf) | 它虽然更老，但现在很多 DA 论文仍会把它和 Office-Home、VisDA、DomainNet 一起报告。 |
| 41 | PASCAL-Context | Visual | [Site](https://cs.stanford.edu/~roozbeh/pascal-context/) | Mixed / PASCAL VOC 2010 terms | 全场景语义分割与上下文建模 | [Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Mottaghi_The_Role_of_2014_CVPR_paper.pdf) | 它是基于 VOC 扩展出的经典稠密标注 benchmark，很多 scene parsing 论文至今仍会报告。 |
| 42 | NABirds | Visual | [Site](https://dl.allaboutbirds.org/nabirds) | Unknown | 细粒度鸟类识别 | [Paper](https://openaccess.thecvf.com/content_cvpr_2015_workshops/w19/html/Horn_Building_a_Bird_2015_CVPR_paper.html) | 它比 CUB 更大、分类层级更丰富，在 FGVC 研究里长期高频出现。 |
| 43 | Stanford Dogs | Visual | [Site](http://vision.stanford.edu/aditya86/ImageNetDogs/main.html) | Unknown | 细粒度犬种识别 | [Paper](http://people.csail.mit.edu/khosla/papers/fgvc2011.pdf) | 它是犬种识别方向最经典的 benchmark 之一，在细粒度分类和迁移学习里仍然常见。 |

## 相关评测

- [Benchmarks 总览](../Benchmarks/README_ZH.md)
- [ImageNet Challenge](https://www.image-net.org/challenges/LSVRC/index.php)
- [COCO Detection Challenge](https://cocodataset.org/#detection-2020)
- [RobustBench](https://robustbench.github.io/)
- [Papers with Code Vision Benchmarks](https://paperswithcode.com/area/computer-vision)

## 收录说明

- 本页优先覆盖在 CVPR、ICCV、ECCV 以及基础模型论文中长期高频出现的数据集。
- 如果某个视觉方向的 canonical 顶会数据集缺席，应视为后续整理需要优先补齐的缺口。
- 遥感、高空影像与地理空间视觉资源，现已进一步拆分到 [Remote-Sensing](../Remote-Sensing/README_ZH.md)。
