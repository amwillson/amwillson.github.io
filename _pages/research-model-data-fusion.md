---
layout: archive
title: "Model-data fusion as hypothesis testing"
permalink: /research/model-data-fusion/
author_profile: true
---

To improve forecasts of terrestrial ecosystems, my research seeks to improve how ecological processes are represented in process models by confronting model predictions with empirical data. By combining theory and empirical research to represent the processes underlying ecosystem function, mechanistic models allow us to make quantitative predictions, even under conditions that have no historical analog (Malmborg <i>et al.</i> 2024). However, model predictions can be inaccurate because of our incomplete knowledge about which processes govern ecosystem functioning and how to best represent those processes mathematically. Comparing model predictions with data is commonly used to measure prediction accuracy (<i>i.e.</i>, model benchmarking) and to improve model parameterization, but using model-data fusion for testing and refining the ecological hypotheses within models is less common.

I implemented this paradigm in a case study of temperate forest ecosystems in the northeastern U.S. by confronting a forest ecosystem model with 50 years of empirically estimated aboveground biomass. This study system is interesting because many of the tree species in this region are near their historical range limits, leading to questions about the relationship between species' climate niches and individual tree phsyiological tolerances to climatic variation. I found that the representation of the relationship between climate and individual tree growth in the model is unsupported by empirical data. I traced this to the model's hypothesis that tree growth will be reduced near the species' range limits. This indicates that our understanding of how individual tree climate tolerances scale up to the relationship between climate and species range limits is oversimplified, highlighting a need to incorporate more physiological detail on climate-tree growth relationships in this forest model.

<figure style="display: flex; align-items: flex-start; gap: 20px; margin: 20px auto; max-widdth: 90%; justify-content: center">
  <img src="/images/linkages_conceptual.png" alt="Figure 3" style="max-width: 60%; height; auto; flex-shrink: 0;">
  <figcaption style="font-style: italic; flex: 1; min-width: 100px; align-self: center;">
    Conceptual diagram of hypotheses embedded in the forest mechanistic model, LINKAGES. (a) Trees are recruited 
  </figcaption>
</figure>
