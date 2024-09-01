---
title: "Rq-rag: Learning to refine queries for retrieval augmented generation"
collection: publications
category: conferences
permalink: /publication/rq_rag
excerpt: '**Chi-Min Chan**, Chunpu Xu, Ruibin Yuan, Hongyin Luo, Wei Xue, Yike Guo, Jie Fu <br> _Conference On Language Modeling_ (**COLM**) 2024'
paperurl: 'https://arxiv.org/abs/2404.00610'
weight: 1
---


Large Language Models (LLMs) exhibit remarkable capabilities but are prone to generating inaccurate or hallucinatory responses. This limitation stems from their reliance on vast pretraining datasets, making them susceptible to errors in unseen scenarios. To tackle these challenges, Retrieval-Augmented Generation (RAG) addresses this by incorporating external, relevant documents into the response generation process, thus leveraging non-parametric knowledge alongside LLMs' in-context learning abilities. However, existing RAG implementations primarily focus on initial input for context retrieval, overlooking the nuances of ambiguous or complex queries that necessitate further clarification or decomposition for accurate responses. To this end, we propose learning to Refine Query for Retrieval Augmented Generation (RQ-RAG) in this paper, endeavoring to enhance the model by equipping it with capabilities for explicit rewriting, decomposition, and disambiguation. Our experimental results indicate that our method, when applied to a 7B Llama2 model, surpasses the previous state-of-the-art (SOTA) by an average of 1.9\% across three single-hop QA datasets, and also demonstrates enhanced performance in handling complex, multi-hop QA datasets. 




