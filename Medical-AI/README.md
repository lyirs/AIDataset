# Medical-AI

Clinical, biomedical, imaging, and healthcare-focused datasets with careful attention to access constraints.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | MIMIC-IV | English | [Site](https://physionet.org/content/mimiciv/) | Credentialed Health Data License 1.5.0 | ICU and hospital clinical modeling | [Docs](https://physionet.org/content/mimiciv/) | One of the core de-identified EHR resources for clinical ML and health NLP. |
| 2 | eICU-CRD | English | [Site](https://physionet.org/content/eicu-crd/) | Credentialed Health Data License 1.5.0 | Multi-center ICU outcome modeling | [Docs](https://physionet.org/content/eicu-crd/) | A long-running multi-hospital intensive care dataset complementary to MIMIC. |
| 3 | MIMIC-CXR-JPG | English | [Site](https://physionet.org/content/mimic-cxr-jpg/) | Credentialed Health Data License 1.5.0 | Chest X-ray vision-language modeling | [Paper](https://arxiv.org/abs/1901.07042) | A foundational chest radiology benchmark with reports and structured labels. |
| 4 | MedNLI | English | [Site](https://physionet.org/content/mednli/1.0.0/) | Credentialed Health Data License 1.5.0 | Clinical natural language inference | [Docs](https://physionet.org/content/mednli/1.0.0/) | Widely used clinical NLI set derived from physician-annotated sentence pairs. |
| 5 | CheXpert | English | [Site](https://stanfordmlgroup.github.io/competitions/chexpert/) | Unknown | Chest radiograph classification | [Docs](https://stanfordmlgroup.github.io/competitions/chexpert/) | A standard chest X-ray benchmark in medical vision papers. |
| 6 | BraTS | English | [Site](https://www.med.upenn.edu/cbica/brats/) | Unknown | Brain tumor segmentation | [Docs](https://www.med.upenn.edu/cbica/brats/) | The canonical MRI brain tumor segmentation benchmark family. |
| 7 | The Cancer Imaging Archive | Medical imaging | [Site](https://www.cancerimagingarchive.net/) | Mixed / collection-specific | Medical imaging retrieval and cancer imaging ML | [Docs](https://www.cancerimagingarchive.net/) | A central public archive for many widely reused oncology imaging collections. |
| 8 | PMC Open Access Subset | Biomedical literature | [Site](https://pmc.ncbi.nlm.nih.gov/tools/openftlist/) | Mixed / article-specific OA licenses | Biomedical literature pretraining | [Docs](https://pmc.ncbi.nlm.nih.gov/tools/openftlist/) | A core source for open biomedical full text and literature mining. |
| 9 | PubMedQA | English | [GitHub](https://github.com/pubmedqa/pubmedqa) | MIT | Biomedical question answering | [Docs](https://github.com/pubmedqa/pubmedqa) | A high-signal benchmark for yes-no-maybe reasoning over biomedical abstracts. |
| 10 | MedMCQA | English | [GitHub](https://github.com/medmcqa/medmcqa) | MIT | Medical exam question answering | [Docs](https://github.com/medmcqa/medmcqa) | A large-scale medical entrance-exam QA benchmark for factual and clinical reasoning. |
| 11 | n2c2 Clinical NLP Challenge Sets | English clinical notes | [Site](https://n2c2.dbmi.hms.harvard.edu/data-sets) | Custom / data use agreement | Clinical NLP benchmarking across shared tasks | [Docs](https://n2c2.dbmi.hms.harvard.edu/data-sets) | A canonical collection of clinical NLP shared tasks with challenge-specific access constraints. |
| 12 | Medical Segmentation Decathlon | Medical imaging | [Site](https://medicaldecathlon.com/) | CC BY-SA 4.0 | General-purpose medical image segmentation | [Paper](https://arxiv.org/abs/2106.05735) | A broad multi-organ segmentation benchmark family widely used in medical imaging papers. |
| 13 | MIMIC-III | English | [Site](https://physionet.org/content/mimiciii/) | Credentialed Health Data License 1.5.0 | Clinical time-series and EHR modeling | [Docs](https://physionet.org/content/mimiciii/) | The classic predecessor to MIMIC-IV and still one of the most cited clinical ML datasets. |
| 14 | NIH ChestX-ray14 | English | [Site](https://nihcc.app.box.com/v/ChestXray-NIHCC) | Unknown | Chest X-ray classification and localization | [Paper](https://arxiv.org/abs/1705.02315) | A foundational large-scale chest radiograph benchmark in medical vision. |
| 15 | ISIC Archive | Medical imaging | [Site](https://www.isic-archive.com/) | Mixed / challenge-specific | Skin lesion analysis and dermoscopy | [Docs](https://challenge.isic-archive.com/data/) | One of the most widely reused public resources for skin lesion classification and segmentation. |
| 16 | CAMELYON16 | Digital pathology | [Site](https://camelyon16.grand-challenge.org/) | Unknown | Lymph node metastasis detection in whole-slide images | [Paper](https://jamanetwork.com/journals/jama/article-abstract/2763118) | A canonical pathology benchmark for weak labels, localization, and slide-level classification. |
| 17 | TCGA | Cancer genomics | [Site](https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga) | Mixed / open + controlled access | Cancer genomics and multi-omics modeling | [Docs](https://gdc.cancer.gov/resources-tcga-users) | A landmark cancer genomics program still central to biomedical multi-omics work. |
| 18 | LIDC-IDRI | Medical imaging | [Site](https://www.cancerimagingarchive.net/collection/lidc-idri/) | CC BY 3.0 | Lung nodule detection and segmentation | [Docs](https://www.cancerimagingarchive.net/collection/lidc-idri/) | A canonical public CT benchmark for lung nodule detection, annotation, and CAD research. |
| 19 | UK Biobank | Biomedical multimodal data | [Site](https://www.ukbiobank.ac.uk/about-us/how-we-work/access-to-uk-biobank-data/) | Custom / application-based access | Population-scale health modeling | [Docs](https://www.ukbiobank.ac.uk/use-our-data/apply-for-access/) | One of the most important large-scale biomedical resources, but access is application-gated. |
| 20 | PadChest | Spanish radiology + images | [Site](https://bimcv.cipf.es/bimcv-projects/padchest/) | Custom / research use agreement | Chest radiology vision-language learning | [Docs](https://bimcv.cipf.es/bimcv-projects/padchest/padchest-dataset-research-use-agreement/) | A high-signal chest X-ray dataset with reports and rich labels from Spanish radiology practice. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [CBLUE](https://github.com/CBLUEbenchmark/CBLUE)
- [BioASQ](http://bioasq.org/)
- [CheXpert Leaderboard](https://stanfordmlgroup.github.io/competitions/chexpert/)
- [ISIC Challenge](https://challenge.isic-archive.com/data/)

## Selection Note

- This page mixes open and credentialed-access resources because medical AI research depends heavily on both public benchmarks and restricted clinical datasets.
- If access is gated by credentialing or challenge terms, the table keeps that restriction visible rather than pretending the data is frictionless.
