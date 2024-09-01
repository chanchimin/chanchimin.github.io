---
title: "AgentMonitor: A Plug-and-Play Framework for Predictive and Secure Multi-Agent Systems"
collection: publications
category: manuscripts
permalink: /publication/agentmonitor
excerpt: '**Chi-Min Chan**, Jianxuan Yu, Weize Chen, Chunyang Jiang, Xinyu Liu, Weijie Shi, Zhiyuan Liu, Wei Xue, Yike Guo <br> _Arxiv_ 2024'
paperurl: 'https://arxiv.org/abs/2408.14972'
weight: 1
---

The rapid advancement of large language models (LLMs) has led to the rise of LLM-based agents. Recent research shows that multi-agent systems (MAS), where each agent plays a specific role, can outperform individual LLMs. However, configuring an MAS for a task remains challenging, with performance only observable post-execution. Inspired by scaling laws in LLM development, we investigate whether MAS performance can be predicted beforehand. We introduce AgentMonitor, a framework that integrates at the agent level to capture inputs and outputs, transforming them into statistics for training a regression model to predict task performance. Additionally, it can further apply real-time corrections to address security risks posed by malicious agents, mitigating negative impacts and enhancing MAS security. Experiments demonstrate that an XGBoost model achieves a Spearman correlation of 0.89 in-domain and 0.58 in more challenging scenarios. Furthermore, using AgentMonitor reduces harmful content by 6.2% and increases helpful content by 1.8% on average, enhancing safety and reliability.

