---
title: "An Experience-Buffer Framework for Explainable Satisfaction Prediction with LLMs"
section: wip
sitemap: false
excerpt: ""
order: 2
authors: 'with <a href="https://www.shanhhuang.com/" target="_blank">Shan Huang</a>, <a href="https://tongwang-ai.github.io" target="_blank">Tong Wang</a>, and Jinyong Ma (ByteDance)'
---

Satisfaction models typically trade off accuracy for interpretability. We introduce a framework that learns a compact, segment-specific library of satisfaction rules and uses it to steer a large language model at prediction time, without updating any model weights. Customers are first grouped into behavioral segments; within each segment, candidate explanations for satisfaction outcomes are generated and filtered using a prediction-consistency test; the surviving explanations are then distilled into an editable "experience buffer" optimized against held-out performance. In a field partnership with a leading short-video platform, the learned buffer meaningfully improves satisfaction prediction over standard baselines, with gains that replicate across model sizes. Because the rules are human-readable and segment-specific, the resulting predictor also serves as an auditable diagnostic tool for what drives satisfaction in each customer segment.
