---
layout: post
title: "Lexical Reranking of Semantic Retrieval (LeSeR) for Regulatory QA"
date: 2025-04-15 00:00:00 +0000
image: /images/leser.png  # optional thumbnail, update or remove if unused
categories: research
author: "Drishti Sharma"
authors: "Jebish Purbey, <strong>Drishti Sharma</strong>, Siddhant Gupta, Khawaja Murad, Siddartha Pullakhandam, Ram Mohan Rao Kadiyala"
venue: "COLING 2025 (RegNLP Track, 4th Place)"
link: https://your-paper-link.com  # replace with actual paper link
code: https://github.com/your-org/leser  # optional
excerpt: "A hybrid semantic-lexical retrieval pipeline for regulatory QA, achieving top performance in COLING 2025 RegNLP track."
---

This work introduces **LeSeR** (Lexical Reranking of Semantic Retrieval), a hybrid method that first performs dense semantic retrieval using fine-tuned embedding models on query-passage pairs, and then reranks the results using BM25, a classical lexical retrieval algorithm.

This two-stage decoupled pipeline improves both recall and precision, outperforming standalone dense or lexical methods.

We evaluated multiple embedding models—**Stella**, **BGE**, **CDE**, and **MPNet**—with fine-tuning using **Multiple Negative Symmetric Ranking (MNSR)** Loss. Among these, **BGE_MNSR integrated with LeSeR (BGE_LeSeR)** achieved the best retrieval performance:

- **Recall@10**: 0.8201  
- **mAP@10**: 0.6655  

For answer generation, the best combination was **BGE_LeSeR + Qwen2.5 7B**, achieving the highest **RePASs score (0.4340)**, demonstrating strong entailment, obligation coverage, and minimal contradiction.
