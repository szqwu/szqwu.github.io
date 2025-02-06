---
title: "Motion-Agent: A Conversational Framework for Human Motion Generation with LLMs"
collection: publications
category: none
permalink: /publications/Motion-Agent
excerpt: '**Qi Wu**\*, Yubo Zhao\*, Yifan Wang, Xinhang Liu, Yu-Wing Tai, Chi-Keung Tang'
date: 2025-02-06
venue: 'ICLR'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://arxiv.org/pdf/2405.17013'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

Abstract
=====
While previous approaches to 3D human motion generation have achieved notable success, they often rely on extensive training and are limited to specific tasks. To address these challenges, we introduce Motion-Agent, an efficient conversational framework designed for general human motion generation, editing, and understanding. Motion-Agent employs an open-source pre-trained language model to develop a generative agent, MotionLLM, that bridges the gap between motion and text. This is accomplished by encoding and quantizing motions into discrete tokens that align with the language model's vocabulary. With only 1--3\% of the model's parameters fine-tuned using adapters, MotionLLM delivers performance on par with diffusion models and other transformer-based methods trained from scratch. By integrating MotionLLM with GPT-4 without additional training, Motion-Agent is able to generate highly complex motion sequences through multi-turn conversations, a capability that previous models have struggled to achieve. Motion-Agent supports a wide range of motion-language tasks, offering versatile capabilities for generating and customizing human motion through interactive conversational exchanges. Project page: https://knoxzhao.github.io/Motion-Agent/