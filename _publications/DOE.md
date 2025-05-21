---
title: "Optimal Design of Physical and Numerical Experiments for Computer Code Calibration"
collection: publications
category: manuscripts
permalink: /publication/DOE
excerpt: ' '
date: 2024-06-24
venue: 'HAL'
slidesurl: ' '
paperurl: 'https://theses.hal.science/UNIV-UT3/hal-04615127v2'
bibtexurl: ' '
citation: 'Adama Barry, François Bachoc, Sarah Bouquet, Miguel Munoz Munoz Zuniga, Clémentine Prieur. &quot;Optimal Design of Physical and Numerical Experiments for Computer Code Calibration. 2024.&quot; <i>⟨hal-04615127v2⟩ 1</i>. 1(1).'
---
We address the problem of Bayesian calibration of an expensive computer code assumed without model discrepancy. In a calibration process with costly measurement acquisition and high computing time of the computer code, the estimation accuracy and cost mitigation must guide the selection of the design of physical experiments and of numerical experiments. To this end, we propose a hybrid approach to select both designs of physical and numerical experiments with the aim to approximate the posterior density of calibration parameters. We first build an initial Gaussian process emulator which we use to calculate an optimal physical experimental design criterion. Then, after selecting the physical experimental design, we combine physical observations with available computer code evaluations to sequentially add new points to the design of numerical experiments in order to improve the Gaussian process emulator for the calibration purpose. We introduce three new criteria for selecting the design of physical experiments based on posterior density or computer code variation and two new criteria for selecting the design of numerical experiments inspired by the Sequential Uncertainty Reduction (SUR) paradigm. A performance analysis and comparison with state-of-the-art methods is proposed for two test cases and a more realistic one involving the calibration of a harmonic oscillator.