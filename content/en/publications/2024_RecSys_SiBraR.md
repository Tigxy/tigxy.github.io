---
title: "A Multimodal Single-Branch Embedding Network for Recommendation in Cold-Start and Missing Modality Scenarios"

abstract: "Most recommender systems adopt collaborative filtering (CF) and provide recommendations based on past collective interactions. Therefore, the performance of CF algorithms degrades when few or no interactions are available, a scenario referred to as cold-start. To address this issue, previous work relies on models leveraging both collaborative data and side information on the users or items. Similar to multimodal learning, these models aim at combining collaborative and content representations in a shared embedding space. In this work we propose a novel technique for multimodal recommendation, relying on a multimodal Single-Branch embedding network for Recommendation (SiBraR). Leveraging weight-sharing, SiBraR encodes interaction data as well as multimodal side information using the same single-branch embedding network on different modalities. This makes SiBraR effective in scenarios of missing modality, including cold start. Our extensive experiments on large-scale recommendation datasets from three different recommendation domains (music, movie, and e-commerce) and providing multimodal content information (audio, text, image, labels, and interactions) show that SiBraR significantly outperforms CF as well as state-of-the-art content-based RSs in cold-start scenarios, and is competitive in warm scenarios. We show that SiBraR's recommendations are accurate in missing modality scenarios, and that the model is able to map different modalities to the same region of the shared embedding space, hence reducing the modality gap."

shortname: sibrar
image: assets/images/papers/2024_SiBraR.png
image_preview: assets/images/paper-previews/2024_SiBraR.png
authors:
- name: ganhoer
  suffix: "*"
- name: moscati
  suffix: "*"
- hausberger
- nawaz
- schedl

journal_short: RecSys
year: 2024
month: 10

bibentry: inproceedings
key: ganhoer_moscati2024sibrar
bib:
  journal:
  booktitle: Proceedings of the 18th ACM Conference on Recommender Systems (RecSys)
  editor: 
  publisher: Association for Computing Machinery
  address: New York, NY, USA
  url: https://doi.org/10.1145/3640457.3688138
  doi: 10.1145/3640457.3688138
  volume: 
  number: 
  pages: 380–390
  month: 
  location: Bari, Italy

links:
  preprint: https://arxiv.org/abs/2409.17864
  publisher: https://dl.acm.org/doi/10.1145/3640457.3688138
  youtube: 
  pdf: 
  blog: https://medium.com/@christian.ganhoer/a-brief-guide-on-sibrar-4a2476b5b73a
  code: https://github.com/hcai-mms/SiBraR---Single-Branch-Recommender
  external-webpage: https://hcai.at/publications/2024_11_RecSys_ganhor_moscati_sibrar/
---
