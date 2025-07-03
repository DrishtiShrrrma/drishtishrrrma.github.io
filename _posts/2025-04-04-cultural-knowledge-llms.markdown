---
layout: post
title: "Improving Multilingual Capabilities with Cultural and Local Knowledge in LLMs"
date: 2025-03-02 00:00:00 +0000
image: /images/cultural-llms.png  # optional
categories: other
author: "Drishti Sharma"
authors: "Ram Mohan Rao Kadiyala, Siddartha Pullakhandam, Siddhant Gupta, <strong>Drishti Sharma</strong>, Jebish Purbey, Kanwal Mehreen, Muhammad Arham, Hamza Farooq"
link: https://arxiv.org/pdf/2504.09753  # optional
code: https://github.com/your-org/cultural-llms  # optional
excerpt: " This research was conducted in collaboration with [Traversaal.ai](https://traversaal.ai/) and supported through their research grant program. We fine-tuned seven open-source language models, including Qwen-2.5-14B-Instruct and Phi-4, using 485,000 culturally grounded English-Hindi instruction pairs covering regional norms, idioms, and daily context. The result: up to a 3% average improvement on multilingual benchmarks outperforming even larger models without any architectural changes or vocabulary expansion. Our work shows that lightweight, culturally informed tuning can significantly boost multilingual performance while keeping models efficient. You can explore the [model](https://huggingface.co/large-traversaal/Mantra-14B), [preprint manuscript](https://arxiv.org/pdf/2504.09753), [demo](https://huggingface.co/spaces/large-traversaal/Mantra-14B-Demo), and [user logs] (https://huggingface.co/datasets/large-traversaal/mantra-14b-user-interaction-log) on Hugging Face."
---

This work explores the role of **cultural and local knowledge** in enhancing multilingual LLM performance.

We instruction-tuned **seven open-source LLMs** using a dataset of **485,000 culturally-informed English-Hindi instruction pairs**, covering domains such as:

- Social norms  
- Local customs  
- Regional metaphors  
- Daily linguistic context

### Key contributions:

- Demonstrated consistent gains in translation quality, instruction alignment, and cultural contextuality.
- Evaluated models on both standard multilingual benchmarks and custom regional knowledge probes.
- Highlighted limitations of generic pretraining for culturally sensitive reasoning.

The study underscores the value of **localized, bilingual instruction tuning** for improving cross-cultural fluency in LLMs.
