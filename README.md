# Applied Trustworthy AI

A collection of theoretical research and practical implementations focusing on the reliability, fairness, robustness, and interpretability of modern Artificial Intelligence models.

## 📌 Overview
This repository contains a series of assignments and projects exploring the core pillars of Trustworthy AI. It covers a wide range of topics, from mitigating spurious correlations and defending against adversarial attacks to auditing model fairness, evaluating differential privacy, and implementing Explainable AI (XAI) techniques.

## 🚀 Core Implementations
* **Robustness & Generalization:** Overcoming spurious correlations using Empirical Risk Minimization (ERM) and Just Train Twice (JTT) algorithms on biased datasets (e.g., Colored MNIST).
* **Adversarial Attacks:** Implementation of Black-box (SimBA) and White-box (FGSM, PGD) attacks on ResNet models (CIFAR-10) to demonstrate neural network vulnerabilities.
* **Explainable AI (XAI):** 
  * Interpreting tabular/image model decisions using LIME and Partial Dependence Plots (PDP).
  * Visualizing CNN attention maps using Grad-CAM, Guided Grad-CAM, and FinerGrad-CAM to audit model reasoning.
* **Algorithmic Fairness:** Auditing the COMPAS dataset for demographic bias and implementing mitigation strategies (Pre-processing, Post-processing, In-processing) while exploring the mathematical trade-offs of fairness metrics.
* **Privacy & Federated Learning:** Evaluating Membership Inference Attacks (MIA) in Cross-Silo Federated Learning and implementing Differential Privacy (DP-SGD) to balance privacy and model utility.
* **Causal Inference:** Designing Structural Causal Models (SCM) to compute Average Treatment Effects (ATE) and counterfactual fairness.

## 🛠️ Tech Stack
* **Language:** Python (Jupyter Notebooks)
* **Frameworks:** PyTorch, scikit-learn, Fairlearn / AIF360
* **Concepts:** XAI, Federated Learning, Differential Privacy, Causality, Adversarial Robustness
