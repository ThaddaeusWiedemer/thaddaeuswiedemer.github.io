---
title: In Search of Forgotten Domain Generalization
abstract: "Out-of-Domain (OOD) generalization is the ability of a model trained on one or more domains to generalize to unseen domains. In the ImageNet era of computer vision, evaluation sets for measuring a model's OOD performance were designed to be strictly OOD with respect to style. However, the emergence of foundation models and expansive web-scale datasets has obfuscated this evaluation process, as datasets cover a broad range of domains and risk test domain contamination. In search of the forgotten domain generalization, we create large-scale datasets subsampled from LAION -- LAION-Natural and LAION-Rendition -- that are strictly OOD to corresponding ImageNet and DomainNet test sets in terms of style. Training CLIP models on these datasets reveals that a significant portion of their performance is explained by in-domain examples. This indicates that the OOD generalization challenges from the ImageNet era still prevail and that training on web-scale data merely creates the illusion of OOD generalization. Furthermore, through a systematic exploration of combining natural and rendition datasets in varying proportions, we identify optimal mixing ratios for model generalization across these domains. Our datasets and results re-enable meaningful assessment of OOD robustness at scale -- a crucial prerequisite for improving model robustness."
authors:
- Prasanna Mayilvahanan
- Roland S Zimmermann
- admin
- Evgenia Rusak
- Attila Juhos
- Matthias Bethge
- Wieland Brendel
date: '2024-10-10'
publication: 'ICLR 2025 (Spotlight)'
publication_types:
- paper-conference
# url_pdf: https://arxiv.org/abs/2410.08258
url_pdf: https://openreview.net/forum?id=Fk3eod9aaD
url_code: https://github.com/brendel-group/clip-dg
url_project: https://brendel-group.github.io/clip-dg/
---
