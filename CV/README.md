# CV

Core image datasets for classification, detection, segmentation, scene understanding, RGB-D perception, and fine-grained recognition.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | ImageNet | Visual | [Site](https://www.image-net.org/) | Research only / custom | Large-scale image classification | [Docs](https://www.image-net.org/) | Foundational vision pretraining resource. |
| 2 | COCO | Visual | [Site](https://cocodataset.org/) | Mixed / custom | Detection, segmentation, and captions | [Paper](https://arxiv.org/abs/1405.0312) | Core benchmark for modern detection stacks. |
| 3 | Open Images | Visual | [Site](https://storage.googleapis.com/openimages/web/index.html) | CC BY 2.0 + annotation terms | Large-scale detection and relations | [Paper](https://arxiv.org/abs/1811.00982) | Google-scale open image collection. |
| 4 | CIFAR-10/100 | Visual | [Site](https://www.cs.toronto.edu/~kriz/cifar.html) | Unknown | Lightweight classification baselines | [Docs](https://www.cs.toronto.edu/~kriz/cifar.html) | Handy for quick experiments and teaching. |
| 5 | Cityscapes | Visual | [Site](https://www.cityscapes-dataset.com/) | Custom | Urban scene segmentation | [Paper](https://arxiv.org/abs/1604.01685) | Fine annotations for street scenes. |
| 6 | ADE20K | Visual | [Site](https://groups.csail.mit.edu/vision/datasets/ADE20K/) | Custom | Scene parsing and segmentation | [Paper](https://arxiv.org/abs/1608.05442) | Dense labels across many scene types. |
| 7 | LVIS | Visual | [Site](https://www.lvisdataset.org/) | Unknown | Long-tail instance segmentation | [Paper](https://arxiv.org/abs/1908.03195) | Useful for rare-category recognition. |
| 8 | Objects365 | Visual | [Site](https://www.objects365.org/) | Unknown | Detection pretraining at scale | [Paper](https://arxiv.org/abs/1901.07518) | Broad object coverage beyond COCO. |
| 9 | BDD100K | Visual | [Site](https://bdd-data.berkeley.edu/) | Custom | Autonomous driving multi-task training | [Paper](https://arxiv.org/abs/1805.04687) | Detection, lanes, drivable area, tracking. |
| 10 | SA-1B | Visual | [GitHub](https://github.com/facebookresearch/segment-anything) | Research license | Segmentation foundation-model training | [Paper](https://arxiv.org/abs/2304.02643) | 1B masks released with Segment Anything. |
| 11 | PASCAL VOC | Visual | [Site](https://www.robots.ox.ac.uk/~vgg/projects/pascal/VOC/) | Mixed / source-image terms | Detection and semantic segmentation baselines | [Docs](https://www.robots.ox.ac.uk/~vgg/projects/pascal/VOC/) | The canonical pre-COCO benchmark still used for legacy comparability. |
| 12 | Places365 | Visual | [Site](https://places2.csail.mit.edu/) | Non-commercial research / educational only | Scene recognition and scene-centric pretraining | [Docs](https://places2.csail.mit.edu/) | A standard scene-recognition anchor in representation-learning papers. |
| 13 | NYU Depth V2 | Visual | [Site](https://cs.nyu.edu/~fergus/datasets/nyu_depth_v2.html) | Unknown | Indoor RGB-D segmentation and depth understanding | [Docs](https://cs.nyu.edu/~fergus/datasets/nyu_depth_v2.html) | Foundational indoor RGB-D benchmark with dense labels. |
| 14 | SUN RGB-D | Visual | [Site](https://rgbd.cs.princeton.edu/) | Unknown | Indoor scene understanding and 3D object detection | [Docs](https://rgbd.cs.princeton.edu/) | Widely used for indoor perception and RGB-D transfer. |
| 15 | Mapillary Vistas | Visual | [Site](https://www.mapillary.com/dataset/vistas/) | Custom / research-use terms | Street-scene segmentation and domain generalization | [GitHub](https://github.com/mapillary/mapillary_vistas) | Adds stronger geographic and weather diversity than older street-scene sets. |
| 16 | iNaturalist Open Dataset | Visual | [GitHub](https://github.com/inaturalist/inaturalist-open-data) | Mixed / observation-specific CC terms | Fine-grained and long-tail recognition | [Docs](https://www.inaturalist.org/pages/developers) | Challenge editions remain common in FGVC and biodiversity recognition papers. |
| 17 | WIDER FACE | Visual | [Site](https://mmlab.ie.cuhk.edu.hk/projects/WIDERFace/) | Unknown | Face detection in the wild | [Docs](https://mmlab.ie.cuhk.edu.hk/projects/WIDERFace/) | Still the default hard face-detection benchmark in many comparisons. |
| 18 | CUB-200-2011 | Visual | [Site](https://www.vision.caltech.edu/datasets/cub_200_2011/) | Non-commercial research / educational only | Fine-grained classification and part localization | [Docs](https://www.vision.caltech.edu/datasets/cub_200_2011/) | A long-running FGVC anchor with part and attribute annotations. |
| 19 | CelebA | Visual | [Site](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) | Non-commercial research only | Face attributes and face analysis | [Paper](https://openaccess.thecvf.com/content_iccv_2015/html/Liu_Deep_Learning_Face_ICCV_2015_paper.html) | A canonical face-attribute dataset used in recognition, editing, and generative baselines. |
| 20 | Food-101 | Visual | [Site](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/) | Unknown | Food recognition and transfer learning | [Paper](https://arxiv.org/abs/1409.0575) | Still one of the most common domain-specific image classification datasets. |
| 21 | Oxford-IIIT Pet | Visual | [Site](https://www.robots.ox.ac.uk/~vgg/data/pets/) | CC BY-SA 4.0 | Fine-grained pet classification and segmentation | [Paper](https://www.robots.ox.ac.uk/~vgg/publications/2012/Parkhi12/) | A standard small-to-medium benchmark for transfer learning and segmentation. |
| 22 | Oxford 102 Flowers | Visual | [Site](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/) | Unknown | Fine-grained flower classification | [Paper](https://www.robots.ox.ac.uk/~vgg/publications/2008/Nilsback08/) | Frequently reused in FGVC and vision-language transfer papers. |
| 23 | ImageNet-C | Visual | [GitHub](https://github.com/hendrycks/robustness) | Unknown | Corruption robustness evaluation | [Paper](https://arxiv.org/abs/1903.12261) | Still the default robustness check in many vision and foundation-model papers. |
| 24 | ImageNetV2 | Visual | [GitHub](https://github.com/modestyachts/ImageNetV2) | Unknown | Distribution-shifted ImageNet evaluation | [Paper](https://arxiv.org/abs/1902.10811) | Commonly reported to test generalization beyond the original ImageNet validation set. |
| 25 | ObjectNet | Visual | [Site](https://objectnet.dev/) | Unknown | Bias-controlled real-world recognition shift | [Paper](https://papers.neurips.cc/paper_files/paper/2019/file/97af07a14cacba681feacf3012730892-Paper.pdf) | A strong test of viewpoint and background shift for real-world object recognition. |
| 26 | V3Det | Visual | [Site](https://v3det.openxlab.org.cn/) | Unknown | Open-vocabulary object detection | [Paper](https://arxiv.org/abs/2304.03752) | A high-signal large-category detection benchmark for modern open-world perception. |
| 27 | PACO | Visual | [GitHub](https://github.com/facebookresearch/paco) | Unknown | Part and attribute recognition | [Paper](https://arxiv.org/abs/2301.01795) | Expands beyond boxes and masks toward richer object-part and attribute reasoning. |
| 28 | ImageNet-A | Visual | [GitHub](https://github.com/hendrycks/natural-adv-examples) | MIT | Natural adversarial robustness evaluation | [Paper](https://arxiv.org/abs/1907.07174) | A standard post-ImageNet stress test beyond synthetic corruptions. |
| 29 | ImageNet-R | Visual | [GitHub](https://github.com/hendrycks/imagenet-r) | MIT | Rendition shift robustness evaluation | [Paper](https://arxiv.org/abs/2006.16241) | Commonly reported in CLIP, ViT, and robustness comparison tables. |
| 30 | FGVC-Aircraft | Visual | [Site](https://www.robots.ox.ac.uk/~vgg/data/fgvc-aircraft/) | Non-commercial research only | Fine-grained aircraft recognition | [Paper](https://arxiv.org/abs/1306.5151) | A canonical FGVC benchmark alongside birds, pets, and flowers. |
| 31 | DTD | Visual | [Site](https://www.robots.ox.ac.uk/~vgg/data/dtd/) | Research only / custom | Texture recognition and material-style representation learning | [Paper](https://arxiv.org/abs/1311.3618) | Still common in texture, transfer, and representation-learning papers. |
| 32 | VisDA-2017 | Visual | [Site](http://ai.bu.edu/visda-2017/) | Unknown | Synthetic-to-real domain adaptation | [Paper](https://arxiv.org/abs/1710.06924) | The canonical large-scale benchmark for visual domain adaptation from simulation to reality. |
| 33 | DomainNet | Visual | [Site](http://ai.bu.edu/M3SDA/) | Non-commercial research / fair use notice | Multi-source domain adaptation and domain generalization | [Paper](https://arxiv.org/abs/1812.01754) | A standard large-scale six-domain benchmark for cross-domain transfer. |
| 34 | ImageNet-Sketch | Visual | [GitHub](https://github.com/HaohanWang/ImageNet-Sketch) | Unknown | Sketch-style distribution shift evaluation | [Paper](https://arxiv.org/abs/1905.13549) | Frequently reported alongside ImageNet-A, R, V2, and ObjectNet in robustness tables. |
| 35 | Office-Home | Visual | [Site](https://www.hemanthdv.org/officeHomeDataset.html) | Non-commercial research / fair use notice | Domain adaptation and domain generalization | [Paper](https://openaccess.thecvf.com/content_cvpr_2017/html/Venkateswara_Deep_Hashing_Network_CVPR_2017_paper.html) | A long-running four-domain benchmark that still appears in transfer-learning comparison tables. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [ImageNet Challenge](https://www.image-net.org/challenges/LSVRC/index.php)
- [COCO Detection Challenge](https://cocodataset.org/#detection-2020)
- [RobustBench](https://robustbench.github.io/)
- [Papers with Code Vision Benchmarks](https://paperswithcode.com/area/computer-vision)

## Selection Note

- This page prioritizes datasets that remain common in CVPR, ICCV, ECCV, and foundation-model papers.
- If a canonical top-conference vision dataset is missing, it should be treated as a gap to fill in later curation passes.
- Overhead, satellite, and geospatial benchmarks are now expanded separately in [Remote-Sensing](../Remote-Sensing/README.md).
