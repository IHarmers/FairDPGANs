# FairDPGANs (2026)
## Differentially Private and Fairness-Aware Generative Adversarial Networks
#### By Ilse Harmers & Mina Alishahi

This repository contains the code for our paper on a novel collection of fairness-aware and differentially private GANs, dubbed FairDPGANs. 

## Abstract

Synthetic data generation offers a promising approach for sharing sensitive tabular data while mitigating privacy and fairness concerns. However, existing generative approaches typically address either formal privacy guarantees or fairness during training, but rarely both simultaneously. We introduce \textit{FairDPGANs}, a family of generative adversarial networks that integrate group-fairness constraints into the training of a differentially private GAN. We evaluate several FairDPGAN variants against private and fairness-aware GANs using three benchmark datasets and multiple privacy budgets, considering group and individual fairness, classifier and dataset utility, and privacy. The results show that fairness constraints can improve the group fairness of classifiers trained on synthetic data while largely preserving the privacy protection of the differentially private baseline, although with some loss in utility. Among the evaluated models, \textit{FairDPGAN Dis}, particularly with $\lambda_f = 0.5$ and $\lambda_f = 1.5$, provides the most balanced fairness-privacy trade-offs. We also investigate individual fairness preprocessing (IFP), which shows inconsistent effects on group fairness but can improve individual fairness and classifier utility for selected models. These results show that formal differential privacy and fairness objectives can be combined within the same tabular data generation framework.

## Contact

For the full data release of this work, please contact i.harmers@student.ou.nl.
