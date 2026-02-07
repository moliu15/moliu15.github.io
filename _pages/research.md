---
layout: archive
title: "Research"
permalink: /research/
author_profile: false
mathjax: true
---

<style>
/* ===== Research Page Styling ===== */
:root{
  --paper-accent: #3b82f6;   /* title color */
  --paper-accent-2: #7c3aed; /* alt accent */
  --paper-text: #111827;
  --paper-muted: #6b7280;
  --paper-border: rgba(17,24,39,.12);
  --paper-bg: rgba(255,255,255,.72);
  --paper-bg-2: rgba(255,255,255,.92);
  --paper-shadow: 0 10px 30px rgba(17,24,39,.08);
  --paper-radius: 18px;
}

.research-wrap{
  max-width: 980px;
  margin: 0 auto;
}

.research-lead{
  font-size: 1.05rem;
  line-height: 1.65;
  color: var(--paper-text);
  margin-bottom: 1.25rem;
}

.research-lead strong{
  font-weight: 700;
}

.paper-list{
  list-style: none;
  counter-reset: paper;
  padding-left: 0;
  margin: 1.25rem 0 0;
}

.paper-list > li{
  counter-increment: paper;
  margin: 0 0 1.05rem;
}

.paper-card{
  position: relative;
  border: 1px solid var(--paper-border);
  border-radius: var(--paper-radius);
  background: linear-gradient(180deg, var(--paper-bg-2), var(--paper-bg));
  box-shadow: var(--paper-shadow);
  padding: 1.05rem 1.1rem 1.0rem 1.1rem;
  overflow: hidden;
}

.paper-card::before{
  content: counter(paper);
  position: absolute;
  top: 14px;
  right: 16px;
  width: 38px;
  height: 38px;
  display: grid;
  place-items: center;
  border-radius: 999px;
  font-weight: 800;
  font-size: 0.95rem;
  color: white;
  background: linear-gradient(135deg, var(--paper-accent), var(--paper-accent-2));
  box-shadow: 0 10px 20px rgba(59,130,246,.25);
}

.paper-title{
  margin: 0.1rem 3.1rem 0.25rem 0; /* leave room for number badge */
  font-size: 1.2rem;
  line-height: 1.35;
}

.paper-title .paper-title-text{
  color: var(--paper-accent);
  font-weight: 800;
}

.paper-meta{
  margin: 0.2rem 0 0.7rem;
  color: var(--paper-muted);
  font-size: 0.98rem;
}

.paper-meta em{
  font-style: italic;
}

.paper-card a{
  text-decoration: none;
  border-bottom: 1px solid rgba(59,130,246,.35);
}
.paper-card a:hover{
  border-bottom-color: rgba(59,130,246,.9);
}

.stop-list{
  margin: 0.75rem 0 0.8rem 0;
  padding-left: 1.2rem;
}

.stop-list li{
  margin: 0.35rem 0;
}

.stop-quote{
  font-style: italic;               /* different style than bold */
  color: var(--paper-text);
}

.stop-quote strong{
  font-style: normal;
  font-weight: 800;
}

.paper-explain{
  margin-top: 0.55rem;
  padding: 0.75rem 0.9rem;
  border-left: 4px solid rgba(59,130,246,.55);
  background: rgba(59,130,246,.06);
  border-radius: 12px;
}

.paper-explain p{
  margin: 0.2rem 0;
}

.paper-points{
  margin: 0.55rem 0 0.15rem 0;
  padding-left: 1.2rem;
}

.paper-points li{
  margin: 0.35rem 0;
}

.paper-points strong{
  font-weight: 800;
}

.section-label{
  margin: 1.6rem 0 0.55rem;
  font-size: 1.15rem;
  font-weight: 900;
  letter-spacing: .2px;
  color: var(--paper-text);
}

.section-label .chip{
  display: inline-block;
  padding: 0.32rem 0.6rem;
  border-radius: 999px;
  background: rgba(124,58,237,.10);
  color: #5b21b6;
  border: 1px solid rgba(124,58,237,.18);
}

.other-list{
  list-style: none;
  counter-reset: other;
  padding-left: 0;
  margin: 0.8rem 0 0;
}

.other-list > li{
  counter-increment: other;
  margin: 0 0 0.9rem;
}

.other-card{
  position: relative;
  border: 1px solid var(--paper-border);
  border-radius: var(--paper-radius);
  background: rgba(255,255,255,.75);
  box-shadow: 0 10px 26px rgba(17,24,39,.06);
  padding: 0.9rem 1.0rem 0.85rem 1.0rem;
}

.other-card::before{
  content: counter(other);
  position: absolute;
  top: 12px;
  right: 14px;
  width: 34px;
  height: 34px;
  display: grid;
  place-items: center;
  border-radius: 999px;
  font-weight: 800;
  font-size: 0.92rem;
  color: #111827;
  background: rgba(17,24,39,.06);
  border: 1px solid rgba(17,24,39,.10);
}
</style>

<div class="research-wrap" markdown="1">

## Research Papers

<div class="research-lead" markdown="1">
My research focuses on **decision-focused methods for stochastic optimization**. A recurring theme in my work is that **better prediction does not necessarily lead to better decisions**.

Many of my papers can be viewed as a sequence of **“STOP” messages** to the traditional predict-then-optimize paradigm.
</div>

<ol class="paper-list">

<li>
<div class="paper-card" markdown="1">

<div class="paper-title">
<strong><span class="paper-title-text">Decision-Focused Optimal Transport</span></strong>  
</div>

<div class="paper-meta" markdown="1">
Suhan Liu, **Mo Liu**  _To be submitted._ [\[arXiv\]](https://arxiv.org/abs/2602.02800)
</div>

<ul class="stop-list">
  <li><span class="stop-quote">"STOP" using L2 norm for optimal transport</span></li>
  <li><span class="stop-quote">"STOP" using Wasserstein distance — we need a <strong>decision-focused divergence</strong>.</span></li>
  <li><span class="stop-quote">"STOP" using $\frac{\mu+\nu}{2}$ as the average of two probability measures — we need a <strong>decision-focused average</strong>.</span></li>
</ul>

<div class="paper-explain" markdown="1">
We propose a new metric, termed **decision-focused divergence**, to quantify the distance between two distributions.

<ul class="paper-points">
  <li>The estimation error bound is <strong>independent of the dimension</strong> of the distributions.</li>
  <li>In the <strong>newsvendor problem</strong>, the decision-focused divergence is <strong>zero</strong> whenever the critical quantiles coincide, even if the distributions differ.</li>
  <li>For any random vector $X$ and random variable $Y$, the decision-focused divergence between $X$ and $X \times Y$ is <strong>zero</strong>.</li>
</ul>
</div>

</div>
</li>

<li>
<div class="paper-card" markdown="1">

<div class="paper-title">
<strong><span class="paper-title-text">Decision-Focused Bias Correction for Fluid Approximation</span></strong>  
</div>

<div class="paper-meta" markdown="1">
Can Er, **Mo Liu**. _To be submitted._  [\[arXiv\]](https://arxiv.org/pdf/2512.15726)
</div>

<ul class="stop-list">
  <li><span class="stop-quote">"STOP" using fluid approximation for capacity planning — we need decision-corrected arrival rates</span></li>
</ul>

<div class="paper-explain" markdown="1">
This paper revisits fluid approximations in queueing systems and multi-product newsvendor problems from a capacity-sizing perspective.

<ul class="paper-points">
  <li><strong>Fluid approximation can be biased with respect to decision-making.</strong></li>
  <li>Should one plug in a time-varying arrival rate to replace the original demand arrival distribution when designing capacity for multi-server systems? (Short answer: No.)</li>
  <li>Does a decision-corrected fluid approximation always exist? (Short answer: No.)</li>
  <li>Does a (vectorized) point prediction always exist for multi-product multi-customer newsvendor problems? (Short answer: No.)</li>
  <li>We provide <strong>necessary and sufficient conditions</strong> for the existence of the decision-corrected arrival rate.</li>
</ul>
</div>

</div>
</li>

<li>
<div class="paper-card" markdown="1">

<div class="paper-title">
<strong><span class="paper-title-text">Decision-Focused Sequential Experiment Design: A Directional Uncertainty-Guided Approach</span></strong>  
</div>

<div class="paper-meta" markdown="1">
Beichen Wan, **Mo Liu**, Paul Grigas, Zuo-Jun Max Shen. _Working paper._  [\[arXiv\]](https://arxiv.org/abs/2602.05340)  Preliminary version at [\[NeurIPS 2025 Workshop\]](https://openreview.net/pdf?id=d0YZKGB649)  [\[Poster\]](https://moliu15.github.io/files/decision-focused-design_poster.pdf)
</div>

<ul class="stop-list">
  <li><span class="stop-quote">"STOP" quantifying prediction uncertainty for data collection — we need decision-focused uncertainty quantification</span></li>
</ul>

<div class="paper-explain" markdown="1">
Traditional uncertainty quantification is often **decision-blind**. We introduce a **directional uncertainty measure** that aligns with downstream optimization problem.

<ul class="paper-points">
  <li>Simply quantifying prediction uncertainty can be decision-blind.</li>
  <li>The proposed criterion is computationally tractable and does not require solving optimization oracles.</li>
  <li>Under certain distributions, it yields <strong>smaller sample complexity</strong> than decision-blind designs.</li>
  <li>We establish strong consistency and convergence guarantees.</li>
</ul>
</div>

</div>
</li>

<li>
<div class="paper-card" markdown="1">

<div class="paper-title">
<strong><span class="paper-title-text">Marginal Value of One Data Point in Assortment Personalization</span></strong>  
</div>

<div class="paper-meta" markdown="1">
**Mo Liu**, Junyu Cao, Zuo-Jun Max Shen. _Resubmitted to Management Science._  [\[SSRN\]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4487888)  [\[Slides\]](https://moliu15.github.io/files/INFORMS_value_of_information.pdf)
</div>

<ul class="stop-list">
  <li><span class="stop-quote">"STOP" assuming more (i.i.d.) data leads to higher revenue — better prediction can worsen decisions</span></li>
</ul>

<div class="paper-explain" markdown="1">
We study the **marginal value of adding a single data point** in personalized assortment optimization.

<ul class="paper-points">
  <li>The marginal revenue contribution of a new customer can be <strong>negative</strong>.</li>
  <li>By evaluating marginal contributions, we identify informative customers and reduce the training set size by about <strong>80%</strong> while maintaining similar revenue.</li>
</ul>
</div>

</div>
</li>

</ol>

<div class="section-label">
<span class="chip">Other Work on Decision-Focused Learning and Predict-then-Optimize</span><br>
</div>




<ol class="other-list">

<li>
<div class="paper-card other-card" markdown="1">

<div class="paper-title">
<strong><span class="paper-title-text">Active Learning For Contextual Linear Optimization: A Margin-Based Approach</span></strong>  
</div>

<div class="paper-meta" markdown="1">
**Mo Liu**, Paul Grigas, Heyuan Liu, Zuo-Jun Max Shen. _Major Revision at Management Science._  [\[arXiv\]](http://arxiv.org/abs/2305.06584)  [\[Slides\]](https://moliu15.github.io/files/MBALSPO_INFORMS_New.pdf)
</div>

<div class="paper-explain" markdown="1">
<ul class="paper-points">
  <li>How to identify <strong>informative samples</strong> for decision-making.</li>
  <li><strong>Best Student Paper Nominee</strong> at INFORMS Workshop on Data Science 2023.</li>
  <li><strong>Second Place Poster Prize</strong> at [YinzOR 2023](https://yinzor.cmuinforms.org/).</li>
</ul>
</div>

</div>
</li>

<li>
<div class="paper-card other-card" markdown="1">

<div class="paper-title">
<strong><span class="paper-title-text">Learning from Click Transition Data: Effectiveness of Greedy Pricing Policy under Dynamic Product Availability</span></strong>  
</div>

<div class="paper-meta" markdown="1">
**Mo Liu**, Junyu Cao, Zuo-Jun Max Shen. _Major Revision at Management Science._  [\[SSRN\]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4158054)
</div>

<div class="paper-explain" markdown="1">
<ul class="paper-points">
  <li><strong>Finalist</strong> at 2023 INFORMS Service Science Student Competition.</li>
  <li><strong>Fan Favorite Flash Talk</strong> at [YinzOR 2023](https://yinzor.cmuinforms.org/).</li>
</ul>
</div>

</div>
</li>

<li>
<div class="paper-card other-card" markdown="1">

<div class="paper-title">
<strong><span class="paper-title-text">Inventory Management with LLM: Automated Decision-Making for Order Timing and Quantity</span></strong>  
</div>

<div class="paper-meta" markdown="1">
**Mo Liu**, Yumo Bai, Meng Qi, Zuo-Jun Max Shen. _Major Revision at Service Science._  [\[SSRN\]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3888897)
</div>

</div>
</li>

<li>
<div class="paper-card other-card" markdown="1">

<div class="paper-title">
<strong><span class="paper-title-text">A Re-solving Heuristic for Dynamic Assortment Optimization with Knapsack Constraints</span></strong>  
</div>

<div class="paper-meta" markdown="1">
Xi Chen, **Mo Liu**, Yining Wang, Yuan Zhou. _Accepted by Production and Operations Management._  [\[arXiv\]](https://arxiv.org/pdf/2407.05564)
</div>

</div>
</li>

</ol>

---

</div>





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



