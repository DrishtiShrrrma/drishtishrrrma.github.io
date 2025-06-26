---
layout: post
title: "M-REWARDBENCH: Evaluating Reward Models in Multilingual Settings"
date: 2025-05-01 00:00:00 +0000
image: /images/mrewardbench.png  # optional thumbnail image
categories: research
author: "Drishti Sharma"
authors: "Srishti Gureja, Lester J. Miranda, Shayekh Bin Islam, Rishabh Maheshwary, <strong>Drishti Sharma</strong>, Gusti Winata"
venue: "ACL 2025 (Main Conference)"
advisors: "Nathan Lambert, Sebastian Ruder, Sara Hooker, Marzieh Fadaee"
link: https://your-paper-link.com  # replace with actual link
code: https://github.com/your-org/mrewardbench  # replace with actual repo
dataset: https://huggingface.co/datasets/your-dataset  # replace with dataset
leaderboard: https://leaderboard-site.com/mrewardbench  # replace if available
excerpt: "A multilingual benchmark evaluating 25 reward models across chat, safety, reasoning, and translation tasks."
---

This work presents **M-REWARDBENCH**, the first large-scale benchmark for evaluating reward models (RMs) in multilingual settings, covering 23 languages across 8 scripts and 5 language families.

The benchmark assesses four core capabilities:

1. Chat  
2. Safety  
3. Reasoning  
4. Translation  

using 2.87k human-aligned preference instances.

A total of 25 reward models—spanning Classifier, Generative, and Implicit (DPO-trained) types—are evaluated.

### Key findings:

- Generative RMs (e.g., GPT-4 Turbo) achieve the highest multilingual performance and cross-lingual consistency, with only a 3% average performance drop compared to English.
- Classifier and Implicit RMs exhibit larger drops (~8–13%) and greater volatility, especially in subjective categories like chat and safety.
- Translation quality, language resource availability, and script type (e.g., Latin, Cyrillic) significantly impact RM performance.
- For translation, the benchmark incorporates easy and hard subsets from the MAPLE dataset across four directions (en↔zh, en↔de), showing that harder tasks consistently reduce accuracy.
- Performance improves by 1–3% when using higher-quality translations (Google Translate over NLLB-3.3B).

