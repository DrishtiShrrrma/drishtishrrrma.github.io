---
layout: post
title: "Behind Maya: Building a Multilingual Vision Language Model"
date: 2025-06-10 00:00:00 +0000
image: /images/maya.png  # optional, update or remove
categories: research
author: "Drishti Sharma"
authors: "<strong>Drishti Sharma</strong> et al."
venue: "VLMs4ALL Workshop @ CVPR 2025"
link: https://your-paper-link.com  # replace with actual paper link
code: https://github.com/your-org/maya  # optional
excerpt: "Introducing Maya, a multilingual vision-language model designed for low-resource language and cultural representation."
---

This work introduces **Maya**, an open-source multilingual vision-language model (VLM) designed to address the underperformance of existing VLMs in low-resource languages and diverse cultural contexts.

Maya is built on two major contributions:

1. A multilingual image-text pretraining dataset with **4.4M samples** across 8 languages — English, Chinese, French, Spanish, Russian, Hindi, Japanese, and Arabic — created using a hybrid translation framework that combines Aya 35B, BLEU/N-gram scoring, and balanced sampling from the LLaVA dataset.

2. A multilingual multimodal model architecture using **SigLIP** as the vision encoder (replacing CLIP for multilingual adaptability and variable patch size support) and **Aya-23 8B** as the LLM, which supports 23 languages and an 8K context window.

Visual features are projected through a 2-layer MLP with GELU activation to align with language space, following techniques from LLaVA 1.5.

**Maya outperforms PALO-7B** on LLaVA-Bench-In-The-Wild, offering a strong multilingual alternative to existing VLMs.
