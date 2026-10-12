---
title: "LTM"
date: 2026-10-08T06:29:21Z
categories: ["new_post"]
draft: false
---

##### **In Progress..**

# Large Tabular Models: Generative AI for the Data That Runs Business

1. Most generative AI is built for text, images, and video, but the most valuable enterprise data lives in tables such as transactions, customer records, and telemetry.
2. Granica is building **Large Tabular Models (LTMs)**, foundation models that learn natively from structured and relational enterprise data.
3. The LTM name follows the LLM analogy, a term introduced by van Breugel and van der Schaar for generative models trained on tabular data.
4. An LTM learns the **distribution of rows**, meaning how a record's columns tend to take their values together.
5. That single learned distribution supports several enterprise tasks at once, such as plausibly filling in missing entries.
6. Unlike an LLM, an LTM is used to answer **statistical queries** over the rows it generates, so preserving the true probabilities and correlations is essential.
7. An imperfect fit that is harmless for an LLM can be fatal for an LTM, for example reporting a 45% cash-payment rate when the true figure is 70%.
8. Granica's research, led by Stanford's Prof. Andrea Montanari, goes beyond model architecture to data selection, augmentation, representation learning, and information-preserving compression.
9. This builds on Granica's self-optimizing data infrastructure, which combines information theory, probabilistic modeling, and distributed systems to cut data costs at scale.
10. For infrastructure engineers, the takeaway is that reliable, cost-efficient data and training platforms are what make LTMs practical in production.

*Sources: [Granica Research, "Large Tabular Models: The Next Frontier"](https://www.granica.ai/large-tabular-models); [van Breugel & van der Schaar, ICML 2024](https://arxiv.org/abs/2405.01147v2)*