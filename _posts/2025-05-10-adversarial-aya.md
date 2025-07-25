---
layout: post
title: "Adversarial AYA: Multilingual Robustness of Vision-Language Models"
date: 2025-05-10 00:00:00 +0000
image: /images/adversarial-aya.png  # optional
categories: other
rank: 2
author: "Drishti Sharma"
authors: "Waseem, <strong>Drishti Sharma</strong>, Srimoyee, Ahmad Mustafa, Sarthak, Vivek, Manoj"
code: https://huggingface.co/datasets/hwaseem04/Aya-testing
excerpt: "This project investigates the cross-lingual transferability of adversarial attacks on vision-language models (VLMs). Using a custom multilingual dataset of 6.7K samples spanning six languages (English, Bengali, German, Korean, Russian, Chinese), we test the robustness of models like Aya, Gemma, and PaLI-Gemma against perturbations generated only in English. We implement PGD, MIM, and DIM attacks and evaluate their success using multilingual Sentence-BERT similarity. Results show that English-only attacks transfer effectively to other languages, revealing significant multilingual vulnerabilities in current VLMs and underscoring the need for targeted robustness benchmarks."
---
