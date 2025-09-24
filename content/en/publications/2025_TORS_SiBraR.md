---
title: "Single-Branch Network Architectures to Close the Modality Gap in Multimodal Recommendation"

abstract: "Traditional recommender systems rely on collaborative filtering, using past user–item interactions to help users discover new items in a vast collection. In cold start, i.e., when interaction histories of users or items are not available, content-based recommender systems use side information instead. Hybrid recommender systems (HRSs) often employ multimodal learning to combine collaborative and side information, which we jointly refer to as modalities. Though HRSs can provide recommendations when some modalities are missing, their quality degrades. In this work, we utilize single-branch neural networks equipped with weight sharing, modality sampling, and contrastive loss to provide accurate recommendations even in missing modality scenarios by narrowing the modality gap. We compare these networks with multi-branch alternatives and conduct extensive experiments on three datasets. Six accuracy-based and four beyond-accuracy-based metrics help assess the recommendation quality for the different training paradigms and their hyperparameters in warm-start and missing modality scenarios. We quantitatively and qualitatively study the effects of these different aspects on bridging the modality gap. Our results show that single-branch networks achieve competitive performance in warm-start scenarios and are significantly better in missing modality settings. Moreover, our approach leads to closer proximity of an item's modalities in the embedding space."

shortname: tors-sibrar
image: assets/images/papers/2025_TORS_SiBraR.png
authors:
- ganhoer
- moscati
- hausberger
- nawaz
- schedl

journal_short: TORS
year: 2025
month: 09

bibentry: article
key: ganhoer_moscati2024sibrar
bib:
  journal: ACM Transactions on Recommender Systems (TORS)
  booktitle: 
  editor: 
  publisher: Association for Computing Machinery
  address: New York, NY, USA
  url: 
  doi: 
  volume: 
  number: 
  pages: 
  month: 
  location: 

links:
  preprint: https://arxiv.org/abs/2509.18807
  publisher: 
  youtube: 
  pdf: /assets/pdfs/2025_TORS_SiBraR.pdf
  blog: 
  code: https://github.com/hcai-mms/single-branch-networks
  external-webpage: 
---
