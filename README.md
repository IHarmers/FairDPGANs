# FairDPGANs (2026)
## Differentially Private and Fairness-Aware Generative Adversarial Networks
#### By Ilse Harmers & Mina Alishahi

This repository contains the code for our paper on a novel collection of fairness-aware and differentially private GANs, dubbed FairDPGANs. 

## Abstract

Synthetic data generation offers a promising approach for sharing sensitive tabular data while mitigating privacy and fairness concerns. However, existing generative approaches typically address either formal privacy guarantees or fairness during training, rather than both simultaneously. To address this gap, we introduce *FairDPGANs*, a family of generative adversarial networks that integrate group-fairness constraints into the training of a differentially private GAN. We evaluate several FairDPGAN variants against state-of-the-art private and fairness-aware GANs using three benchmark datasets and multiple privacy budgets. Our evaluation considers group and individual fairness, classifier and dataset utility, and privacy. The results show that incorporating fairness constraints can improve the group fairness of classifiers trained on synthetic data while largely preserving the privacy protection provided by the differentially private baseline, although these improvements generally involve a trade-off in utility. Among the evaluated models, *FairDPGAN Dis* with disparate impact losses, particularly with $\lambda_f = 0.5$ and $\lambda_f = 1.5$, provides the most balanced fairness-privacy trade-offs. We further investigate individual fairness preprocessing (IFP) and find that its effect on group fairness is inconsistent, while it can improve individual fairness and classifier utility for selected models. The results show that formal differential privacy and fairness objectives can be incorporated within the same tabular data generation framework, although their effects on fairness, privacy, and utility need to be considered jointly.

## Contact

For the full data release of this work, please contact i.harmers@student.ou.nl.
