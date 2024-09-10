---
title: "MotionLLM: Multimodal Motion-Language Learning with Large Language Models"
collection: publications
category: none
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: '**Qi Wu**\*, Yubo Zhao\*, Yifan Wang\*, Yu-Wing Tai, Chi-Keung Tang'
date: 2024-05-28
venue: 'arXiv'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://arxiv.org/pdf/2405.17013'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

Abstract
=====
Recent advancements in Multimodal Large Language Models (MM-LLMs) have demonstrated promising potential in terms of generalization and robustness when applied to different modalities. While previous works have already achieved 3D human motion generation using various approaches including language modeling, they mostly use specialized architecture and are restricted to single-human motion generation. Inspired by the success of MM-LLMs, we propose MotionLLM, a simple and general framework that can achieve single-human, multi-human motion generation, and motion captioning by fine-tuning pre-trained LLMs. Specifically, we encode and quantize motions into discrete LLM-understandable tokens, which results in a unified vocabulary consisting of both motion and text tokens. With only 1--3% parameters of the LLMs trained by using adapters, our single-human motion generation achieves comparable results to those diffusion models and other trained-from-scratch transformer-based models. Additionally, we show that our approach is scalable and flexible, allowing easy extension to multi-human motion generation through autoregressive generation of single-human motions. Project page: https://knoxzhao.github.io/MotionLLM/