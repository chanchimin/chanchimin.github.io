---
title: "Exploring the Impact of Model Scaling on Parameter-Efficient Tuning"
collection: publications
category: conferences
permalink: /publication/rq_rag
excerpt: 'Yusheng Su\*, **Chi-Min Chan\***, Jiali Cheng, Yujia Qin, Yankai Lin, Shengding Hu, Zonghan Yang, Ning Ding, Xingzhi Sun, Guotong Xie, Zhiyuan Liu, Maosong Sun <br> _Empirical Methods in Natural Language Processing_ (**EMNLP**) 2023'
paperurl: 'https://aclanthology.org/2023.emnlp-main.931/'
weight: 1.5
---


Parameter-efficient tuning (PET) methods can effectively drive extremely large pre-trained language models (PLMs) by training only minimal parameters. Different PET methods utilize different manually designed tunable modules. In small PLMs, there are usually noticeable performance differences among PET methods. Nevertheless, as the model scale increases, the performance differences become marginal. Hence, we hypothesize that model scaling mitigates the impact of design differences on PET methods. To investigate this hypothesis, we introduce a more flexible PET method called Arbitrary PET (APET) method. The APET method is compatible with a tunable module, which consists of any number of parameters distributed in arbitrary positions. Then, we utilize it and conduct experiments on 11 NLP tasks across 3 representative PLMs. Our investigations reveal that model scaling (1) mitigates the effects of the positions of tunable parameters on performance, and (2) enables tuning methods to achieve performance comparable to full-parameter fine-tuning by optimizing fewer tunable parameters. Intriguingly, we also observe that tuning methods optimize the similar number of tunable parameters to exceed random guess performance on different tasks. We collectively discuss this phenomenon and the two aforementioned findings from an optimization perspective to understand the underlying mechanisms. These conclusions enhance our understanding of the impact of model scaling on PET and assist in designing more effective and efficient PET methods for PLMs of different scales. 



