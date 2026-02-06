---
layout: archive
title: "Research"
permalink: /research/
author_profile: false
mathjax: true
---
## Research Papers

My research focuses on **decision-focused methods for stochastic optimization**. A recurring theme in my work is that **better prediction does not necessarily lead to better decisions**.

Many of my papers can be viewed as a sequence of **“STOP” messages** to the traditional predict-then-optimize paradigm.

---



1. **Decision-Focused Optimal Transport**  
   Suhan Liu, **Mo Liu**  
   [\[arXiv\]](https://arxiv.org/abs/2602.02800)

-  "STOP" using L2 norm for optimal transport
-  "STOP" using Wasserstein distance — we need a **decision-focused divergence**.  

- "STOP" using \(\frac{\mu+\nu}{2}\) as the average of two probability measures — we need a **decision-focused average**.


   We propose a new metric, termed **decision-focused divergence**, to quantify the distance between two distributions through the lens of downstream decision quality.

   * The estimation error bound is **independent of the dimension** of the distributions.
   * In the **newsvendor problem**, the decision-focused divergence is **zero** whenever the critical quantiles coincide, even if the distributions differ.
   * For any random vector \(X\) and random variable \(Y\), the decision-focused divergence between \(X\) and \(X \times Y\) is **zero**.

---

1. **Decision-Focused Bias Correction for Fluid Approximation**  
   Can Er, **Mo Liu**. _To be submitted._  
   [\[arXiv\]](https://arxiv.org/pdf/2512.15726)

- "STOP" using fluid approximation for capacity planning — we need decision-corrected arrival rates


   This paper revisits fluid approximations in queueing systems and multi-product newsvendor problems from a decision-centric perspective.

   * **Fluid approximation can be biased with respect to decision-making.**
   * Should one plug in a time-varying arrival rate to replace the original demand arrival distribution when designing capacity for multi-server systems? (Short answer: No.)
   * Does a decision-corrected fluid approximation always exist? (Short answer: No.)
   * Does a (vectorized) point prediction always exist for multi-product multi-customer newsvendor problems? (Short answer: No.)
   * We provide **necessary and sufficient conditions** for the existence of the decision-corrected arrival rate.

---


1. **Decision-Focused Sequential Experiment Design: A Directional Uncertainty-Guided Approach**  
   Beichen Wan, **Mo Liu**, Paul Grigas, Zuo-Jun Max Shen. _Working paper._  
   [\[arXiv\]](https://arxiv.org/abs/2602.05340)  
   Preliminary version at [\[NeurIPS 2025 Workshop\]](https://openreview.net/pdf?id=d0YZKGB649)  
   [\[Poster\]](https://moliu15.github.io/files/decision-focused-design_poster.pdf)

   
- "STOP" quantifying prediction uncertainty for data collection — we need decision-focused uncertainty quantification

   Traditional uncertainty quantification is often **decision-blind**. We introduce a **directional uncertainty measure** that explicitly accounts for the downstream optimization problem and guides data collection toward decision-relevant regions.

   * Simply quantifying prediction uncertainty can be decision-blind.
   * The proposed criterion is computationally tractable and does not require solving optimization oracles.
   * Under certain distributions, it yields **smaller sample complexity** than decision-blind designs.
   * We establish strong consistency and convergence guarantees.

---


1. **Marginal Value of One Data Point in Assortment Personalization**  
   **Mo Liu**, Junyu Cao, Zuo-Jun Max Shen. _Resubmitted to Management Science._  
   [\[SSRN\]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4487888)  
   [\[Slides\]](https://moliu15.github.io/files/INFORMS_value_of_information.pdf)

-  "STOP" assuming more (i.i.d.) data leads to higher revenue — better prediction can worsen decisions

   We study the **marginal value of adding a single data point** in personalized assortment optimization.

   * The marginal revenue contribution of a new customer can be **negative**.
   * By evaluating marginal contributions, we identify informative customers and reduce the training set size by about **80%** while maintaining similar revenue.

---

<span style="font-size: 1.6em; font-weight: 700;">Other Work on Decision-Focused Learning and Predict-then-Optimize</span><br>

1. **Active Learning For Contextual Linear Optimization: A Margin-Based Approach**  
   **Mo Liu**, Paul Grigas, Heyuan Liu, Zuo-Jun Max Shen. _Major Revision at Management Science._  
   [\[arXiv\]](http://arxiv.org/abs/2305.06584)  
   [\[Slides\]](https://moliu15.github.io/files/MBALSPO_INFORMS_New.pdf)

   * How to identify **informative samples** for decision-making
   * **Best Student Paper Nominee** at INFORMS Workshop on Data Science 2023
   * **Second Place Poster Prize** at [YinzOR 2023](https://yinzor.cmuinforms.org/)

1. **Learning from Click Transition Data: Effectiveness of Greedy Pricing Policy under Dynamic Product Availability**  
   **Mo Liu**, Junyu Cao, Zuo-Jun Max Shen. _Major Revision at Management Science._  
   [\[SSRN\]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4158054)

   * **Finalist** at 2023 INFORMS Service Science Student Competition
   * **Fan Favorite Flash Talk** at [YinzOR 2023](https://yinzor.cmuinforms.org/)

1. **Inventory Management with LLM: Automated Decision-Making for Order Timing and Quantity**  
   **Mo Liu**, Yumo Bai, Meng Qi, Zuo-Jun Max Shen. _Major Revision at Service Science._  
   [\[SSRN\]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3888897)

1. **A Re-solving Heuristic for Dynamic Assortment Optimization with Knapsack Constraints**  
   Xi Chen, **Mo Liu**, Yining Wang, Yuan Zhou. _Accepted by Production and Operations Management._  
   [\[arXiv\]](https://arxiv.org/pdf/2407.05564)

---

## Patent 

Joint machine learning and dynamic optimization with time series data to forecast optimal decision making and outcomes over multiple periods\\
Zachary Xue, **Mo Liu**, Markus Ettl, Shivaram Subramanian. [ \[link\] ](https://patents.google.com/patent/US20240220855A1/en)




## Selected Talks

* North Carolina State University, Operations Research Seminar, March 2025
* Business Analytics, Artificial Intelligence, and Cherry Blossom Conference at JHU, March 2025
* INFORMS Annual Meeting, 2024
* Duke Fuqua School of Business, 2024
* Purdue Operations Conference, 2024
* Revenue management and pricing conferenece 2024, Los Angeles
* POMS Annual Meeting 2024, Minneapolis


* INFORMS Workshop on Data Science, 2023
* INFORMS Service Science Student Competition, 2023
* INFORMS Annual Meeting Talk, 2023
* Purdue Operations Conference, 2023
* CMU YinzOR Student Competition, 2023
* International Conference Stochastic Programming, 2023
* MSOM Conference,  2023
* IBM Research Intern Talk, 2022
* INFORMS Annual Meeting, 2022
* INFORMS Annual Meeting, 2020



