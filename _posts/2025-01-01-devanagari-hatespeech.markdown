---
layout: post
title: "Detection of Language, Hate Speech, and Targets using LLMs in Devanagari Script"
date: 2025-10-05 00:00:00 +0000
image: /images/devanagari-hatespeech.png  # optional image
categories: research
author: "Drishti Sharma"
authors: "<strong>Drishti Sharma</strong> et al."
venue: "COLING 2025 (CHiPSAL Track)"
link: https://your-paper-link.com  # replace with actual link
code: https://github.com/your-org/devanagari-hatespeech  # optional
excerpt: "A multilingual system for Devanagari-script languages addressing language ID, hate speech detection, and target classification using LLM ensembles."
---

This work presents a modular multilingual NLP system for five Devanagari-script languages—**Hindi, Nepali, Marathi, Sanskrit, and Bhojpuri**—designed to tackle three tasks:

1. **Language identification**  
2. **Hate speech detection**  
3. **Hate speech target classification**

Each task is addressed using a distinct set of models and strategies:

- **Language Identification**: An ensemble of fine-tuned IndicBERT V2, MuRIL, and Gemma-2 9B models achieves high accuracy via majority voting with fallback logic.

- **Hate Speech Detection**: Another ensemble combines IndicBERT V2, Gemma-2 9B, and Gemma-2 27B, all fine-tuned using **Odds Ratio Preference Optimization (ORPO)**. BERT-based models also use **focal loss** (α = 0.35, γ = 4.0) to counter severe class imbalance.

- **Target Classification**: The best result was achieved by a single Gemma-2 27B model fine-tuned with ORPO, without ensembling.

All decoder-only models were trained using **4-bit LoRA** for memory-efficient optimization.

### Results

- **Sub-task A (Lang ID)**: F1 = 0.9980  
- **Sub-task B (Hate Detection)**: F1 = 0.7652  
- **Sub-task C (Target Classification)**: F1 = 0.6804  

These results demonstrate the effectiveness of task-specific, resource-conscious LLM design for low-resource, script-sensitive language processing.
