---
title: "Reproducing Malcomb et al"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - Error
  - Uncertainty
  - Reproduction
---

## Reproducing the Malcomb et al Vulnerability Model Study in Malawi

In my reanalysis of Malcomb's study, I decided to change the vulnerability calculation to a multiplicative rather than additive one. The original study calculated vulnerability as a product of (40-AdaptiveCapacity) + LivelihoodSensitivy + DroughtExposure + FloodRisk. My reanalysis calculates and visualizes a vulnerability score that is the product of (40-Adaptive Capacity) * LivelhoodSensitivity * (DroughtExposure + Flood Risk). 

It is impossible for studies to be completely objective; that is why reproduction analyses are crucial in understanding the ways in which data can be skewed depending on the decisions of the researchers. Altering the way in which the vulnerability score is calculated demnonstrates a different way of looking at the data and categorizing vulnerability; comparing visualizations is useful in understanding the impact of quantifying vulnerability using different equations. Because the multiplicative score generates much higher numbers in a larger range, the vulnerability maps classify high vulnerability more selectively. This may be useful in aiming to identify regions that are *especially* vulnerable to climate change. This reanalysis helps for the consideration of different vulnerability equations depending on the goal of the research. In Malcomb et al's study, the researchers aim to create a vulnerability model to inform policy makers of the areas in Malawi that need the most aid due to climate change vulnerability. Selecting the *most* vulnerable areas using a multiplicative score may better address this purpose.

Find my report [here](https://audreyrpark.github.io/01-RPr-Malcomb-2014.html/) and my research compendium [here](https://github.com/audreyrpark/RPr-Chakraborty-2021).