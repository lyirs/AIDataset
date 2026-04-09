# Recommender-Systems

Datasets for collaborative filtering, ranking, click-through prediction, news recommendation, bandit feedback, and industrial recommendation evaluation.

[中文说明](README_ZH.md) | [Back to Home](../README.md)

| # | Dataset | Language | Link | License | Best For | Paper/Docs | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | MovieLens | Ratings + tags | [Site](https://grouplens.org/datasets/movielens/) | Custom / README terms | Collaborative filtering baselines | [Docs](https://grouplens.org/datasets/movielens/) | Still the default academic starting point for explicit-feedback recommendation. |
| 2 | MIND | English news + click logs | [Site](https://msnews.github.io/) | Microsoft Research License Terms | News recommendation | [Paper](https://aclanthology.org/2020.acl-main.331/) | Large-scale recommendation benchmark built from Microsoft News behavior logs. |
| 3 | Yelp Open Dataset | English reviews + business metadata | [Site](https://business.yelp.com/data/resources/open-dataset/) | Custom / educational use | Local recommendation and review modeling | [Docs](https://business.yelp.com/data/resources/open-dataset/) | Combines reviews, businesses, photos, check-ins, and rich business attributes. |
| 4 | Criteo Display Advertising Challenge | CTR logs | [Site](https://ailab.criteo.com/display-advertising-challenge-criteo/) | Custom / competition terms | CTR prediction and ranking | [Docs](https://ailab.criteo.com/display-advertising-challenge-criteo/) | Classic large-scale display advertising benchmark and precursor to later Criteo releases. |
| 5 | Avazu CTR Prediction | CTR logs | [Site](https://www.kaggle.com/c/avazu-ctr-prediction) | Custom / competition terms | Large-scale ad click prediction | [Docs](https://www.kaggle.com/c/avazu-ctr-prediction) | Popular sparse categorical benchmark for feature engineering and CTR models. |
| 6 | Open Bandit Dataset | Bandit logs | [Site](https://research.zozo.com/data.html) | Unknown | Off-policy evaluation in recommendation | [Paper](https://arxiv.org/abs/2008.07146) | Real-world logged bandit feedback from a large fashion e-commerce platform. |
| 7 | KuaiRec | Video recommendation logs | [Site](https://kuairec.com/) | Unknown | Dense-feedback recommendation evaluation | [Paper](https://doi.org/10.1145/3511808.3557220) | Nearly fully observed interaction matrix from Kuaishou. |
| 8 | KuaiRand | Sequential recommendation logs | [Site](https://kuairand.com/) | Unknown | Debiased sequential recommendation | [Paper](https://doi.org/10.1145/3511808.3557624) | Includes randomly exposed items for counterfactual and unbiased recommendation research. |
| 9 | YOOCHOOSE / RecSys Challenge 2015 | Session clicks | [Site](https://recsys.acm.org/recsys15/challenge/) | Unknown | Session-based recommendation | [Docs](https://recsys.acm.org/recsys15/challenge/) | Canonical session recommendation benchmark from the RecSys Challenge 2015. |
| 10 | Amazon Reviews'23 | Reviews + metadata + graphs | [Site](https://amazon-reviews-2023.github.io/) | Unknown | Large-scale item retrieval and recommendation | [Paper](https://arxiv.org/abs/2403.03952) | Modern large-scale benchmark with review text, item metadata, and item-link structure. |

## Related Benchmarks

- [Benchmarks overview](../Benchmarks/README.md)
- [RecSys Challenges](https://recsys.acm.org/challenges/)
- [MIND](https://msnews.github.io/)
- [Open Bandit Dataset](https://research.zozo.com/data.html)

## Selection Note

- This page prioritizes canonical academic and industrial benchmarks for collaborative filtering, ranking, CTR prediction, bandit evaluation, and session or news recommendation.
- Text-rich recommendation resources can also overlap with [NLP](../NLP/README.md) and [Search-Retrieval](../Search-Retrieval/README.md).
