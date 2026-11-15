# Contextual Stochastic Optimization with Decision-Dependent Uncertainty

**Master's Research Project | Academic Year 2026–2027**  
**CentraleSupélec · Université Paris-Saclay**

| Project information | Details |
|---|---|
| **Topic** | Contextual Stochastic Optimization |
| **Research focus** | Decision-Dependent Uncertainty and Performative Optimization |
| **Program** | M2 Operations Research and Risk Analytics (ORRA) |
| **Academic supervisor** | Prof. Yiping Fang |
| **Academic year** | 2026–2027 |
| **Final defense** | 15 April 2027 |
| **Status** | **Research in progress** |


## 1. Literature Review

The following six papers form the initial reading set. They provide complementary foundations; they do not all study the same uncertainty model.

| Paper | Main connection to this project |
|---|---|
| [Dahan, Sela & Amin — *Network Inspection for Detecting Strategic Attacks*](https://arxiv.org/abs/1705.00349v4) | Strategic infrastructure inspection, security games, and bilevel optimization. |
| [Elmachtoub & Grigas — *Smart “Predict, then Optimize”*](https://arxiv.org/abs/1710.08005v5) | Decision quality versus predictive accuracy; SPO and SPO+ learning objectives. |
| [Perdomo, Zrnic, Mendler-Dünner & Hardt — *Performative Prediction*](https://arxiv.org/abs/2002.06673v4) | Decision-induced distribution shift, repeated retraining, and performative stability. |
| [Sadana et al. — *A Survey of Contextual Optimization Methods for Decision-Making under Uncertainty*](https://arxiv.org/abs/2306.10374v2) | A taxonomy and common conceptual framework for contextual optimization methods. |
| [Handina, Diao, Wierman & Mazumdar — *Strategic Decision Focused Learning*](https://arxiv.org/abs/2609.14907v1) | Prediction and equilibrium-aware decisions in strategic settings; current independent reproduction activity. |
| [Xie, Abdin & Fang — *From Frequentist to Bayesian Contextual Optimization*](https://arxiv.org/abs/2609.27534v1) | Bayesian contextual optimization, model uncertainty, and decision-focused posterior learning. |

## 4. Current Activity: Independent SDFL Reproduction

I am studying and independently reimplementing the Infrastructure Security Game from:

**Handina, T., Diao, Y., Wierman, A., & Mazumdar, E. (2026). *Strategic Decision Focused Learning*.**

[arXiv:2609.14907v1](https://arxiv.org/abs/2609.14907v1)

This activity is being developed in Python and Google Colab to better understand the paper's methodology, data processing, predictive modeling, Stackelberg security-game optimization, and the relationship between prediction error and realized strategic utility.

### Experimental Setting in the Original Paper

The paper's infrastructure experiment uses New York City subway ridership data for 123 Manhattan stations, covering 2022–2024, organized into 8-hour windows.

Its methods include PTO, ZOC, KKT, and Hybrid.

**Data source:** [MTA Subway Hourly Ridership: 2020–2024](https://data.ny.gov/Transportation/MTA-Subway-Hourly-Ridership-2020-2024/wujg-7c2s).
