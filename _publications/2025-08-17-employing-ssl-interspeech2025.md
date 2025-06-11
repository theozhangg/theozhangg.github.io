---
title: "Employing self-supervised learning models for cross-linguistic child speech maturity classification"
collection: publications
permalink: /publication/employing-ssl
excerpt: 'Speech technology systems struggle with many downstream tasks for child speech due to small training corpora and the difficulties that child speech pose. We apply a novel dataset, SpeechMaturity, to state-of-the-art transformer models to address a fundamental classification task: identifying child vocalizations.'
date: 2025-08-17
venue: 'Interspeech 2025'
paperurl: 'https://arxiv.org/abs/2506.08999'
citation: '@misc{zhang2025employingselfsupervisedlearningmodels,
      title={Employing self-supervised learning models for cross-linguistic child speech maturity classification}, 
      author={Theo Zhang and Madurya Suresh and Anne S. Warlaumont and Kasia Hitczenko and Alejandrina Cristia and Margaret Cychosz},
      year={2025},
      eprint={2506.08999},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2506.08999}, 
}'
---

Speech technology systems struggle with many downstream tasks for child speech due to small training corpora and the difficulties that child speech pose. We apply a novel dataset, SpeechMaturity, to state-of-the-art transformer models to address a fundamental classification task: identifying child vocalizations. Unlike previous corpora, our dataset captures maximally ecologically-valid child vocalizations across an unprecedented sample, comprising children acquiring 25+ languages in the U.S., Bolivia, Vanuatu, Papua New Guinea, Solomon Islands, and France. The dataset contains 242,004 labeled vocalizations, magnitudes larger than previous work. Models were trained to distinguish between cry, laughter, mature (consonant+vowel), and immature speech (just consonant or vowel). Models trained on the dataset outperform state-of-the-art models trained on previous datasets, achieved classification accuracy comparable to humans, and were robust across rural and urban settings. 