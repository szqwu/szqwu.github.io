---
title: "Novel View Synthesis as Video Completion"
collection: publications
category: manuscripts
permalink: /publications/FrameCrafter
excerpt: '**Qi Wu**, Khiem Vuong, Minsik Jeon, Srinivasa Narasimhan, Deva Ramanan'
date: 2026-04-11
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2604.08500'
codeurl: 'https://github.com/szqwu/FrameCrafter'
pageurl: 'https://frame-crafter.github.io/'
teaser: framecrafter-teaser.png
---

Abstract
======
We tackle the problem of sparse novel view synthesis (NVS) using video diffusion models; given K (≈ 5) multi-view images of a scene and their camera poses, we predict the view from a target camera pose. Many prior approaches leverage generative image priors encoded via diffusion models. However, models trained on single images lack multi-view knowledge. We instead argue that video models already contain implicit multi-view knowledge and so should be easier to adapt for NVS. Our key insight is to formulate sparse NVS as a low frame-rate video completion task. However, one challenge is that sparse NVS is defined over an unordered set of inputs, often too sparse to admit a meaningful order, so the models should be invariant to permutations of that input set. To this end, we present FrameCrafter, which adapts video models (naturally trained with coherent frame orderings) to permutation-invariant NVS through several architectural modifications, including per-frame latent encoding, query-centered camera conditioning, and the removal of temporal positional encoding. With only ~1% trainable parameters and 1K training scenes, FrameCrafter achieves competitive performance on standard NVS benchmarks. As video foundation models continue to advance, our framework enables their improvements to directly translate into stronger NVS performance.
