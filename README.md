# Causal ML for treatment effect estimation

 Valentyn Melnychuk
<melnychuk@lmu.de>

*Version: MZES Social Science Data Lab, 2026-10-14*

## Abstract

In this talk, I introduce causal machine learning as a practical toolkit for estimating treatment effects and counterfactuals from observational data. Here, I formalize the potential-outcomes setup and explain why individual treatment effects are not directly observable, which motivates causal identification. I then walk through the key assumptions — consistency, overlap/positivity, and exchangeability — and show how they connect to common causal frameworks (potential outcomes, SCMs, and causal graphs). Building on that foundation, I cover the main estimands (ATE and heterogeneous effects such as CATE) and compare widely used CATE estimators, from plug-in learners (S-/T-learners) to orthogonal and doubly robust approaches based on pseudo-outcomes and residualization (e.g., IPW/RA/DR and R-learning). I conclude the talk with an overview of state-of-the-art works in causal ML and a discussion of open practical challenges such as uncertainty quantification, model selection under limited data, and hidden confounding.


📝 [Slides 1]()


## About the Instructor

Valentyn Melnychuk is a PhD candidate at the Institute of AI in Management, LMU Munich. His research focuses on causal inference and data-driven decision-making. In particular, he develops methods that combine causal inference with probabilistic modelling, with a particular emphasis on uncertainty quantification, representation learning, generative models, and robustness to confounding or violated assumptions.
