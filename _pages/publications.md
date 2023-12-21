---
layout: archive
title: "Publication Work"
permalink: /publications/
author_profile: true
---

My research work resulted in the following outputs (the first two listed are from my undergrad, currently under review; the third was accepted at NLLP@EMNLP'23).

- **Open Information Extraction** (In-review)\
    _Co-first-author, Conference paper (long)_ \
    _2023_
    - Proposes novel embedding methods that increase performance by 24.9%, 27.3% and 14.9% on Precision, Recall and F1 scores, being the first to integrate linguistic features with a Seq2Seq PLM (here, [T5](https://arxiv.org/abs/1910.10683)) for the task.
    - Contributes a synthetic dataset that boosted performance by 73.7% and 37.9% on Recall and F1 scores over the Seq2Seq version of the current largest annotated dataset, the latter which we show to be very flawed.
    - First to use a feature that significantly reduces compute resources by using 72% less tags compared to its counterpart, while maintaining the same performance boost!
    - Extends [Amazon's work](https://arxiv.org/abs/2101.05779) on structured prediction tasks to include OIE, thus being the first to study how SP pre-training affects OIE performance.
    - This work was supervised by Dr. Mansi Radke.
    
- **Open Link Prediction in Open Knowledge Graphs** (In-review) \
    _First author, Workshop paper (short)_ \
    _2023_
    - Demonstrates how inductive graph neural networks enhance entity-mention node vectors to improve reasoning in the Open Link Prediction task in [OLPBench](https://drive.google.com/file/d/1y0kShFhvThPYD70_8ZqiOVLehKCcptHJ/view).
    - Investigates the effect of the hashing trick and of FP-16 precision.
    - Conductes ablation studies with semantic node features.

- **Evaluating LLMs in the Legal Domain** [[Paper](https://aclanthology.org/2023.nllp-1.22/)] \
    _December '23_
    _Venue_: Natural Legal Language Processing (NLLP) Workshop, co-located with EMNLP 2023 (orally presented on December 7 in Singapore) \
 Thanmay J, **Fauzan F**, Luqman F "Large Language Models are legal but they are not: Making the case for a powerful LegalLLM”, _Proceedings of the Natural Legal Language Processing Workshop 2023_, pages 223–229 \
  - Benchmarked performance of various LLMs over the LEDGAR dataset by zero-shot prompting.
