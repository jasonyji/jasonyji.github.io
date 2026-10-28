---
title: "LLMs in Product Selection for Small E-commerce"
section: working
order: 3
authors: 'with <a href="https://www.shanhhuang.com/" target="_blank">Shan Huang</a>'
status: "Ready for Submission"
paperurl: "https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5822963"
presentations:  # newest first
  - year: 2026
    name: "INFORMS Marketing Science Conference"
    url: "https://novasbe.maglr.com/2026-isms-marketing-science-conference"
    location: "Nova SBE, Lisbon, Portugal"
  - year: 2025
    name: "INFORMS Annual Meeting"
    url: "https://meetings.informs.org/wordpress/annual/"
    location: "Atlanta, GA, USA"
figure: /images/research_images/Product_Selection.png
figure_alt: "Diagram of the FACES framework: Stage I key-factor identification and Stage II hierarchical comparative evaluation"
---

Product selection is critical to the success of small businesses, yet data-driven decision-making is often prohibitively costly in resource-constrained settings. Recent advances in large language models (LLMs) offer a promising alternative for supporting such decisions without requiring extensive data or model training. In this paper, we propose **F**actor-**A**ware **C**omparative **E**valuation for **S**election (**FACES**), a training-free, two-stage LLM-based decision framework that emphasizes comparative reasoning rather than pointwise prediction. FACES first induces a compact set of decision factors from historical campaign outcomes and then applies factor-conditioned, hierarchical comparative evaluation within carefully constructed reference groups to rank new candidates. Using real-world data from a representative small e-commerce firm engaged in international trade via Google Ads, we show that LLMs equipped with carefully constructed reference groups and comparative prompts substantially outperform pointwise LLM prompting approaches and competitive machine-learning benchmarks in predicting product-selection outcomes. We further find that larger reference groups can degrade performance, and that alternative information inclusion strategies in reference group construction lead to systematically different decision outcomes. These results provide actionable guidance for small businesses facing cold-start product selection challenges and offer new insights into how LLMs exploit relational structure in decision-making tasks.
