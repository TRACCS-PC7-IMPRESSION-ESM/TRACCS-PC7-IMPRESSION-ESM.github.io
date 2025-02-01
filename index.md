---
layout: default
---

<div>
<img src="{{site.baseurl}}/img/PC7_structure.png" width="100%" />
</div>

## Project objectives

The Projet Ciblé IMPRESSION-ESM is one of the 10 Projets Ciblés of the PEPR "TRAnsforming Climate Modelling for Climate Services" ([TRACCS](https://pepr-traccs.fr)). IMPRESSION-ESM aims to improve the representation of climate physics in the two French Earth System Models (ESMs) by working on processes already included in these models and adding those that are still missing. One key objective is also to contribute to the training of the next generation of climate professionals.

IMPRESSION-ESM focuses on processes essential to the physics of the Earth's climate: atmospheric deep convection, the role of land-surface heterogeneities in the water cycle and their interactions with the atmosphere, snow processes at high latitudes and over ice sheets, ocean mixing processes, multiphase thermodynamics and rheology of sea ice, and finally air-sea and ocean-sea-ice-icebergs interactions.

In order to better understand the climate system, increase our confidence in future climate projections, and provide high-quality climate information, the fundamental research conducted by IMPRESSION-ESM involves several types of activities:

- The development of theoretical, numerical, and computational models (or parameterizations) to be included in ESMs ;
- The analysis of reference numerical simulations, generally at high resolution, and targeted observations;
- The exploration of techniques based on Artificial Intelligence.

Further information can be found [here](https://pepr-traccs.fr/projet/pc7-impression-esm/)

## News
{% for post in site.posts %}
   - {{ post.date | date_to_string }} » [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
