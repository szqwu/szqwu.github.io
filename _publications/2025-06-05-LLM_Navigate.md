---
title: "Navigating Motion Agents in Dynamic and Cluttered Environments through LLM Reasoning"
collection: publications
category: none
permalink: /publications/LLM_Navigate
excerpt: 'Yubo Zhao\*, **Qi Wu**\*, Yifan Wang, Xinhang Liu, Yu-Wing Tai, Chi-Keung Tang'
date: 2025-06-05
venue: 'arXiv'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2503.07323'
# codeurl: 'https://github.com/PeterYYZhang/few-shot-self-prompt-SAM'
# citation: 'Wu, Qi, Yuyao Zhang, and Marawan Elbatel. "Self-prompting large vision models for few-shot medical image segmentation." MICCAI workshop on domain adaptation and representation transfer. Cham: Springer Nature Switzerland, 2023.'
---

Abstract
======
This paper advances motion agents empowered by large language models (LLMs) toward autonomous navigation in dynamic and cluttered environments, significantly surpassing first and recent seminal but limited studies on LLM's spatial reasoning, where movements are restricted in four directions in simple, static environments in the presence of only single agents much less multiple agents. Specifically, we investigate LLMs as spatial reasoners to overcome these limitations by uniformly encoding environments (e.g., real indoor floorplans), agents which can be dynamic obstacles and their paths as discrete tokens akin to language tokens. Our training-free framework supports multi-agent coordination, closed-loop replanning, and dynamic obstacle avoidance without retraining or fine-tuning. We show that LLMs can generalize across agents, tasks, and environments using only text-based interactions, opening new possibilities for semantically grounded, interactive navigation in both simulation and embodied systems.