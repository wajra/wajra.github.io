---
layout: page
title: Tools for fisheries data collection
description: Improving data collection workflows for high seas fisheries
img: assets/img/project_04_banner_img_large.jpg
importance: 4
category: fun
giscus_comments: false
related_publications: false
---

High seas fisheries are some of the most intensively fished in the world. Since these fisheries usually target species that are defined as straddling stocks (species who migrate between different parts of the ocean that are both international waters and territorial)[^1], some of them are governed by international commissions. The Indian Ocean Tuna Commission (IOTC) is such a governing body that governs tuna and tuna-like species for the Indian Ocean[^2].
I was part of a 6-month pilot study for a project that explored methods to implement a low cost catch recording system that recorded the length, date/time, location of each tuna caught. This project was conducted by the Ministry of Fisheries with Pelagikos pvt. ltd as a consulting partner. Scientific observers were deployed to several tuna-fishing vessels with digital cameras (Coolpix models). The observers recorded each tuna landing by taking the species, length, and photograph. I wrote a program that extracted all the metadata from these image files and assigned them to each catch. The code for the Python scripts used in this pilot study can be found [here](https://github.com/wajra/image-meta-data-extraction)


## References

[^1]: Palacios-Abrantes, J., Santos, B. S., Frölicher, T. L., Reygondeau, G., Sumaila, U., Wabnitz, C. C. C., & Cheung, W. W. L. (2025b). Climate change drives shifts in straddling fish stocks in the world’s ocean. _Science Advances_, 11(31). https://doi.org/10.1126/sciadv.adq5976
[^2]: Sinan, H., Andriamahefazafy, M., & Robertson, K. (2022). David against Goliath? The rise of coastal states at the Indian Ocean Tuna commission. _Frontiers in Marine Science_, 9. https://doi.org/10.3389/fmars.2022.983391