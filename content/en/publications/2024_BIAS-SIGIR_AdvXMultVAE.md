---
title: "Simultaneous Unlearning of Multiple Protected User Attributes From Variational Autoencoder Recommenders Using Adversarial Training"

abstract: "In widely used neural network-based collaborative filtering models, users’ history logs are encoded into latent embeddings that represent the users’ preferences. In this setting, the models are capable of mapping users’ protected attributes (e.g., gender or ethnicity) from these user embeddings even without explicit access to them, resulting in models that may treat specific demographic user groups unfairly and raise privacy issues. While prior work has approached the removal of a single protected attribute of a user at a time, multiple attributes might come into play in real-world scenarios. In the work at hand, we present AdvXMultVAE which aims to unlearn multiple protected attributes (exemplified by gender and age) simultaneously to improve fairness across demographic user groups. For this purpose, we couple a variational autoencoder (VAE) architecture with adversarial training (AdvMultVAE) to support simultaneous removal of the users’ protected attributes with continuous and/or categorical values. Our experiments on two datasets, LFM-2b-100k and Ml-1m, from the music and movie domains, respectively, show that our approach can yield better results than its singular removal counterparts (based on AdvMultVAE) in effectively mitigating demographic biases whilst improving the anonymity of latent embeddings."

shortname: advx-multvae
image: assets/images/papers/2024_07_BIAS-SIGIR_Escobedo_advxmultvae.png
image_preview: assets/images/paper-previews/2024_07_BIAS-SIGIR_Escobedo_advxmultvae.png
authors:
- escobedo-ticona
- ganhoer
- brandl
- augstein
- schedl

journal_short: BIAS@SIGIR
year: 2024
month: 07

bibentry: inproceedings
bib:
  journal:
  booktitle: "Proceedings of the 5th International Workshop on Algorithmic Bias in Search and Recommendation (BIAS @ SIGIR 2024)"
  editor: 
  publisher: 
  address: 
  location: Washington D.C., USA
  doi: 10.1007/978-3-031-71975-2_7
  url: https://doi.org/10.1007/978-3-031-71975-2_7
  volume: 
  number: 
  pages: 
  month: July

links:
  preprint: https://arxiv.org/abs/2410.20965
  publisher: https://link.springer.com/chapter/10.1007/978-3-031-71975-2_7
  youtube: 
  pdf: 
  blog: 
  code: https://github.com/hcai-mms/advx-multvae
  external-webpage: https://hcai.at/publications/2024_07_BIAS-SIGIR_Escobedo_advxmultvae/

---
