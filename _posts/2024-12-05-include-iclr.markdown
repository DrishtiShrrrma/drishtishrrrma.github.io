---
layout: post
title: "INCLUDE: Evaluating Multilingual Language Understanding with Regional Knowledge"
date: 2025-05-05 00:00:00 +0000
image: /images/include.png  # optional
categories: [research]
author: "Drishti Sharma"
authors: "Angelika Romanou, Negar Foroutan, Anna Sotnikova, Zeming Chen, Sree Harsha Nelaturu, Shivalika Singh,......,<strong>Drishti Sharma</strong>,....., Marzieh Fadaee, Sara Hooker, Antoine Bosselut"
venue: "ICLR 2025 (Spotlight)"
link: https://arxiv.org/pdf/2411.19799  # replace with paper or arXiv link
code: https://github.com/your-org/include  # optional
dataset: https://huggingface.co/datasets/your-dataset  # optional
excerpt: "This work introduces INCLUDE, a multilingual benchmark developed to assess LLMs on regional knowledge and cultural grounding across 44 languages and 15 scripts. Comprising 197,243 MCQs derived from 1,926 real-world exams conducted in 52 countries, the benchmark spans domains such as law, history, culture, and GK. INCLUDE is organized into two subsets: INCLUDE-BASE, which is comprehensive and large-scale, and INCLUDE-LITE, a lightweight version suitable for smaller models or quicker evaluations. The benchmark evaluates a variety of LLMs, including GPT-4o, GPT-3.5, Claude, Gemini, Mistral, Yi, and others. Among these, GPT-4o demonstrated the highest overall accuracy, though all models showed significant performance drops in underrepresented languages and non-Latin scripts. Notably, altering the prompt language or applying instruction tuning had minimal impact on performance."
---

This work presents **INCLUDE**, a large-scale multilingual benchmark designed to evaluate large language models (LLMs) on regional knowledge and cultural grounding across 44 languages and 15 scripts.

INCLUDE contains **197,243 multiple-choice questions** sourced from **1,926 real-world exams** administered in 52 countries. These questions span diverse domains, including:

- Law  
- History  
- Culture  
- General Knowledge  

The benchmark is split into two subsets:

- **INCLUDE-BASE**: comprehensive and large-scale  
- **INCLUDE-LITE**: lightweight and suitable for smaller models or quick evaluations

We evaluated a range of LLMs, including:

- **GPT-4o**, **GPT-3.5**, **Claude**, **Gemini**, **Mistral**, **Yi**, and others.

### Key Findings:

- GPT-4o achieves the highest overall accuracy.
- All models exhibit substantial performance degradation in **underrepresented languages** and **non-Latin scripts**.
- Changing the prompt language (e.g., English vs. native) and instruction tuning had limited effect on overall performance.

INCLUDE aims to surface both **linguistic and cultural blind spots** in multilingual LLMs, encouraging more inclusive and globally-aware model development.
