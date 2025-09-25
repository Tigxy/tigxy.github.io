---
title: "ProtoMF: Prototype-based Matrix Factorization for Effective and Explainable Recommendations"

abstract: "Recent studies show the benefits of reformulating common machine learning models through the concept of prototypes -- representatives of the underlying data, used to calculate the prediction score as a linear combination of similarities of a data point to prototypes. Such prototype-based formulation of a model, in addition to preserving (sometimes enhancing) the performance, enables explainability of the model's decisions, as the prediction can be linearly broken down into the contributions of distinct definable prototypes. Following this direction, we extend the idea of prototypes to the recommender system domain by introducing ProtoMF, a novel collaborative filtering algorithm. ProtoMF learns sets of user/item prototypes that represent the general consumption characteristics of users/items in the underlying dataset. Using these prototypes, ProtoMF then represents users and items as vectors of similarities to the corresponding prototypes. These user/item representations are ultimately leveraged to make recommendations that are both effective in terms of accuracy metrics, and explainable through the interpretation of prototypes' contributions to the affinity scores. We conduct experiments on three datasets to assess both the effectiveness and the explainability of ProtoMF. Addressing the former, we show that ProtoMF exhibits higher Hit~Ratio and NDCG compared to other relevant collaborative filtering approaches. As for the latter, we qualitatively show how ProtoMF can provide explainable recommendations and how its explanation capabilities can expose the existence of statistical biases in the learned representations, which we exemplify for the case of gender bias."

shortname: ProtoMF
image: assets/images/papers/2022_recsys_protomf.png
image_preview: assets/images/paper-previews/2022_recsys_protomf.png

authors:
- melchiorre
- rekab-saz
- ganhoer
- schedl

journal_short: RecSys
year: 2022
month: 09

bibentry: article
bib:
  journal:
  booktitle: Proceedings of the 16th ACM Conference on Recommender Systems (RecSys)
  editor: 
  publisher: Association for Computing Machinery
  address: New York, NY, USA
  doi: 10.1145/3523227.3546756
  url: https://doi.org/10.1145/3523227.3546756
  volume: 
  number: 
  pages: 246–-256
  month: 
  location: Seattle, WA, USA

links:
  preprint:
  publisher: https://dl.acm.org/doi/abs/10.1145/3523227.3546756
  youtube: 
  pdf: /assets/pdfs/2022_recsys_protomf.pdf
  blog: 
  code: https://github.com/hcai-mms/ProtoMF
  external-webpage: https://hcai.at/publications/2022_ProtoMF/

---

