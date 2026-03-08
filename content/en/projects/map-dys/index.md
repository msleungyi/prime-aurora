---
title: "Mapping Dyslexia Subtypes (MAP-DyS): Exploring the Multiverse of Developmental Dyslexia Subtyping Methods"
date: 2026-03-06
draft: false
summary: An interactive Shiny app that visualises the analytical decision space of developmental dyslexia subtyping methods.
links:
  - icon: 🟢
    icon_pack: fas
    name: Shiny App
    url: https://dyslexiaproject.shinyapps.io/dyslexia_subtypes/
  - type: preprint
    url: https://www.medrxiv.org/content/10.1101/2025.07.23.25332032v1
  - type: dataset
    url: https://github.com/kristantodan12/Dyslexia_subtyping
  - type: code
    url: https://github.com/kristantodan12/Dyslexia_subtyping
  
tags:
  - Developmental Dyslexia
  - Reading Research
  - Research Methods
  - Open Science
  - Reproducibility
# image:
#   caption: "Image credit: [**Unsplash**](https://unsplash.com)"

---

## Why Study Dyslexia Subtypes?

Researchers have been attempting to divide individuals with developmental dyslexia into subtypes based on shared cognitive profiles (for example, phonological deficits or visual processing difficulties). The goal is to better understand the mechanisms underlying reading difficulties and to design more targeted interventions.

However, studies often use different analytical choices when identifying these subtypes. These choices include:

- the theoretical framework guiding the classification  
- how data are preprocessed or standardised  
- which cognitive measures are included  
- which statistical methods are used (e.g., clustering, classification rules)

Because these decisions vary across studies, researchers may arrive at different subtype structures even when analysing similar data.

This raises an important methodological question:

> How much of the variation in dyslexia subtypes comes from real differences between individuals, and how much comes from differences in research decisions?

---

## What Is the MAP-DyS Project?

The **Mapping Dyslexia Subtypes (MAP-DyS)** project aims to make this methodological variability visible.

We conducted a systematic review of dyslexia subtyping studies and mapped the key analytical decisions used across the literature. These decisions include:

- theoretical models of dyslexia  
- data preprocessing approaches  
- performance measures (e.g., accuracy vs. reaction time)  
- statistical classification methods  
- reported subtype prevalence

Using this information, we constructed a “multiverse” of possible analytical pathways used in dyslexia subtyping research.

We then developed an interactive [Shiny app (MAP-DyS)](https://dyslexiaproject.shinyapps.io/dyslexia_subtypes/) that allows users to explore this decision space and see how different analytical choices relate to different subtype outcomes.

---

## What Does the App Do?

The MAP-DyS app allows users to:

- explore how dyslexia subtyping methods vary across studies  
- visualise analytical decision pathways used in the literature  
- compare different methodological approaches  
- reflect on how research design choices influence conclusions

By making these methodological choices transparent, the tool helps researchers better understand the analytical variability in dyslexia research.

---

## Why This Matters

Subtyping research plays an important role in many fields of psychology and biomedicine. However, if methodological choices strongly influence results, then comparing findings across studies becomes difficult.

Tools like our MAP-DyS app help researchers:

- critically evaluate existing research  
- design more transparent studies  
- understand how methodological decisions shape scientific conclusions

Although this use case study focuses on developmental dyslexia, the framework can be applied to subtyping research in many other areas of biomedicine and psychology.

---

## Learn More

For the full methodological details and results, feel free to check out our preprint:

[**Leung, A. Y., Kristanto, D., Gießing, C., Ioannidis, J. P. A., Hildebrandt, A., & Schmalz, X. (2025).**  
*The multiverse of developmental dyslexia subtyping: The “Mapping Dyslexia Subtypes” (MAP-DyS) app for analytical decision-making.*](https://www.medrxiv.org/content/10.1101/2025.07.23.25332032v1)

---

### Acknowledgement

This project was co-led by myself and Dr. Daniel Kristanto, funded by the META-REP Priority Programme (Phase 1), "Treasure Box for Early-Career Researchers (ECR)". We thank the theoretical and methodological input of our collaborators, Prof. John Ioannidis, Prof. Andrea Hildebrandt, Dr. Xenia Schmalz, Dr. Carsten Gießing. We also thank our research assistant, Mr. Peter Roßmeier, for assisting in data curation and aggregation.