---
layout: page
title: TRAI
description: Learn to Unlearn - Towards Responsible AI (2025–2028, Novo Nordisk Foundation)
img: assets/img/trai.png
importance: 1
category: work
related_publications: false
---

**TRAI – Learn to Unlearn: Towards Responsible AI**

| | |
| --- | --- |
| **Period** | 2025 – 2028 |
| **Funding** | 2.95M DKK |
| **Funder** | Novo Nordisk Foundation, Denmark |
| **Principal Investigator** | Vinay Chakravarthi Gogineni |

### Overview

Modern AI models memorize the data they are trained on. When individuals exercise their right to be forgotten under the GDPR, when training data turns out to be erroneous, biased or harmful, or when regulations such as the EU AI Act require specific information to be removed, that information has to be erased from the trained model itself. Retraining from scratch without the data is usually far too costly, which makes **machine unlearning**, the removal of the influence of specific data from an already-trained model, a key building block for responsible AI.

### Our approach: selective unlearning

Majority of the existing unlearning methods erase the targeted information blindly, updating the model as if everything learned from the forget data should be removed. But data samples share knowledge: what a model learns from one sample often also represents general patterns present across many others. Erasing blindly damages this shared, generalized knowledge and degrades the model's performance on the data it should still handle well.

In TRAI, we develop **selective unlearning** methods. Instead of erasing everything associated with the targeted data, we identify and remove only the information that is specific to it, while preserving the generalized knowledge shared across different data samples. The result is a model that has genuinely forgotten what it should, without losing what it should keep.

### Goals

- Develop principled, efficient methods that separate sample-specific knowledge from shared, generalized knowledge in trained models.
- Unlearn targeted information while preserving the model's utility on retained data.
- Provide AI systems that comply with the GDPR and the AI Act and support fairness, transparency and trustworthy decision-making.
