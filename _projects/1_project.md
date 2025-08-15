---
layout: page
title: Towards better species distribution models
description: Incorporating biological realism in to how we model species distributions
img: 
importance: 1
category: work
related_publications: false
---

A core part of my research has focused on how to better incorporate biological realism to species distribution models (SDMs). I do this via two approaches which I will describe below.

### Incorporating measures of physiological fitness into correlative species distribution models

Correlative species distribution models have long used environmental temperature as the primary determinant of species habitat or niche. However, in the case of many species, temperature doesn't act in a vacuum. Physiological theory has shown evidence for how temperature in symphony with dissolved oxygen can define available habitat for marine species. This is commonly referred to as temperature-induced hypoxia and is measured by metabolic index<sup>[1]</sup>. While this single measure gives valuable insights into habitat availability for species, it requires species-specific parameters of hypoxia which are normally derived using laboratory physiological experiments. This can be both time consuming and expensive. 
In Bandara et al. (2024), we demonstrated that the inclusion of a statistical interaction between temperature and dissolved oxygen can at times match or even exceed the performance of metabolic index under certain circumstances. Another outcome of our work was showing that the utility of metabolic index might be as a baseline indicator of suitable habitat and that once this baseline is surpassed (for example, at the cold range edge of a species), it's informativeness drops off. 

### Improving how we model species distributions via process-based frameworks

As mentioned in the previous section, the major issue with correlative species distribution models is that they run into issues when one tries to utilize them beyond their original spatio-temporal capacities. It is because they link the environment directly to the biogeography of the species and not the processes that direct the biogeography itself. 
Process-based models attempt to link demographic rates to the environment using a hypothetical or experimentally observed formula. Then these demographic rates inform how the species inhabits a landscape.
This is a powerful framework that can theoretically result in versatile predictions even going beyond the current environmental stress that a species might be facing since we have approximated a biological realism in to how the species might respond to changes in this stress. However, the major caveat with these modeling frameworks have always been the significant amount of data and computing power required to run them. But with the invent of long-term data collecting efforts and exponential increases in computing power, they are now a reality and used to inform species models in different capacities. 
**Dynamic Range Models (DRM)** are a class of process-based models that use a hierarchical bayesian framework to describe species distributions.
My specific project is to build a DRM for black sea bass (_Centropristis striata_) in the Northeast US. While this project is a natural extension of our work published in 2024, the specific goals is to find the links between demographic processes such as recruitment, dispersal, and mortality of black sea bass. We then hope to apply these findings to a separate project with the hopes of identifying climate resilient management strategies for black sea bass in the NEUS. 


## References

[1] Deutsch, C., Ferrel, A., Seibel, B., Pörtner, H., & Huey, R. B. (2015). Climate change tightens a metabolic constraint on marine habitats. _Science_, 348(6239), 1132–1135. https://doi.org/10.1126/science.aaa1605

