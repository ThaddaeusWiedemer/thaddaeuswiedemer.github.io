---
title: Pretraining Frequency Predicts Compositional Generalization of CLIP on Real-World Tasks
abstract: "We investigate the success conditions for compositional generalization of CLIP models on real-world data through performance prediction. Prior work shows that CLIP requires exponentially more pretraining data for linear performance gains on individual concepts. This sample-inefficient scaling could be mitigated if CLIP systematically understood new inputs as compositions of learned components, allowing rare observation to be mapped to common concepts. To explore CLIP's compositional generalization ability, we filter retrieval corpora for samples with object combinations not present in the pretraining corpus. We show that CLIP's performance on these samples can be accurately predicted from the pretraining frequencies of individual objects. Our findings demonstrate that CLIP learns to disentangle objects observed in its pretraining data and can recompose them straightforwardly. Additionally, we are the first to show how this ability scales with pretraining data. For data curation in practice, our results suggest that balancing object occurrences improves generalization, which should benefit CLIP's efficiency and accuracy without scaling data volume."
authors:
  - admin
  - Yash Sharma
  - Ameya Prabhu
  - Matthias Bethge
  - Wieland Brendel
date: 2025-02-17
publication: NeurIPS 2024 Workshop
# url_pdf: https://arxiv.org/pdf/2502.18326
url_pdf: https://openreview.net/pdf?id=NDXoM1wYgl
---
