---
title: "Re-SearchTerms: Terminology Variations in Metascience"
date: 2026-02-13
draft: false
summary: An interactive Shiny app and NLP-driven analysis of 2,211 definitions
  to improve conceptual clarity in open scholarship.
links:
  - icon: 🟢
    icon_pack: fas
    name: Shiny App
    url: https://msleungyi.shinyapps.io/Re-SearchTerms_v2/
  - type: preprint
    url: https://doi.org/10.31219/osf.io/qsp7x_v2
  - type: dataset
    url: https://osf.io/vtqgn/
  - type: code
    url: https://osf.io/vtqgn/
  - icon: ▶️
    icon_pack: fas
    name: Video Tutorials
    url: https://www.youtube.com/playlist?list=PLSLpkUCilSvrPyKLTgc8KWtMx7tPiiLVp
tags:
  - Research Toolkit
  - Metascience
  - Open Science
  - NLP
  - Reproducibility
# image:
#   caption: "Image credit: [**Unsplash**](https://unsplash.com)"

---

## What Is Re-SearchTerms?

Have you ever noticed that even when we talk about the same word or the same concept, what each person has in mind might not be exactly the same?

In scientific research, there are terms we frequently use - for example, "replication", "open science", or "transparency". It might be the case that we assume that many of us share the same understanding. In reality, scientists from different fields, and even those within the same field, do not always define these terms in the same way. Sometimes these differences are merely a matter of word choices, but other times they reflect fundamental variations in how different scholars understand a concept. For readers of academic articles, this can inevitably lead to confusion.

I remember when I first started my undergraduate studies in Chinese Language Education and was introduced to the concept of "developmental dyslexia". When writing a thesis, defining the core concepts of the topic is a crucial step. Back then, as an undergraduate, the common approach was simply to find the most "authoritative" definition, which usually meant directly quoting from an authoritative dictionary or a scholarly journal from a prestigious university.

However, as I continued my studies, I realised how difficult it is to determine what truly counts as an "authoritative" definition. Definitions of a term often shift across different scholarly domains or evolve over time. This is a natural part of academic growth. When I delved deeper into the definition of "dyslexia", I discovered that scholars from different regions and eras held varying perspectives.

Having these differences isn't necessarily a bad thing; after all, the essence of scientific research is to encourage a diversity of ideas. It is because we see these inconsistencies in the literature that we are prompted to pause and deeply reflect on what a concept truly means.

Therefore, as part of my doctoral research, I designed and developed this Shiny app, **Re-SearchTerms**. This Shiny App was created to help everyone pause and examine the definitions of academic terms to see how their language and usage vary across the board.

---

## Why Does This Matter?

Scientific progress depends on shared understanding.  
When terminology varies across fields, researchers may:

- Talk past each other  
- Refer to different things under the same label, or use different labels to refer to the same thing (also known as the "jingle-jangle fallacies")
- Draw conclusions that appear contradictory  
- Struggle to replicate findings  

In interdisciplinary fields especially, inconsistent definitions can slow progress and create confusion. But of course, inconsistent definitions may also reflect areas of knowledge that are under exploration. So, we are not saying that terms should always be defined consistently. The key here is to pause and ask:

> - What do we *really* mean when we use a certain term, especially when we try to define a term in scientific communication?
> - Are there multiple ways to define a term? If so, why? When? And how?
> - If we need to define a term in our research, but there are more than one definitions available in the literature, which one should we use? Or is it necessary for us to define the term on our own?
> - If we want to define a term on our own, or to cite an existing definition proposed in another paper, which wording must be retained in our paraphrasing?

Many would agree with me that wordings in term definitions are very important. What researchers write in scientific papers are records of knowledge. We accumulate knowledge via documenting it in words. Accuracy has always been very important when conveying scientific knowledge. That is the rationale behind the app's name: the "Re-" in "Re-SearchTerms" means "once more", "think twice"; "re-search" means "search again". "Re-SearchTerms" means "think twice, and search the meanings of research terms again"!

---

## What Does the App Do?

Re-SearchTerms allows users to:

### Explore Multiple Definitions  
Browse definitions of key scientific terms collected from:
- Academic articles  
- Glossaries (e.g., open scholarship initiatives)  
- Reference sources  

### Compare Across Sources  
See how definitions differ depending on:
- Discipline  
- Research tradition  
- Publication source  

### Visualise Conceptual Relationships  
Using natural language processing (NLP), the app:
- Maps word co-occurrence patterns  
- Displays definition similarity networks  
- Shows how concepts cluster together  

This turns abstract terminology into interactive, explorable knowledge.

---

## How It Works (In Simple Terms!)

Re-SearchTerms uses computational text analysis to:

- Break definitions into meaningful word units  
- Detect overlap between definitions  
- Calculate semantic similarity  
- Build interactive network graphs  

You don’t need technical knowledge to use it — the tool is designed to support reflection, not overwhelm users with statistics. But if any colleauges would like to adapt the app for their own use (e.g., compare terms in a specific domain), the codes and datasets have been made available for reproduction.

---

## Who Is It For?

Re-SearchTerms is useful for:

### Students  
- Clarify terminology before writing essays or theses  
- Understand how terms vary across disciplines  

### Researchers  
- Select definitions deliberately in manuscripts  
- Identify conceptual inconsistencies  
- Reflect on measurement alignment (When developing measurements, we need to define the operationalised definition of the target construct. But first, we have to understand the construct's the conceptual meaning.)

### Educators  
- Teach methodological literacy  
- Show how scientific language evolves  
- Foster critical thinking about concepts  

### Interdisciplinary Teams  
- Align terminology before collaborative projects  
- Prevent misunderstandings early

---

## A Metascience Tool

Re-SearchTerms is part of a broader effort in **metascience** — the study of how science works.

By improving conceptual clarity, the app contributes to:

- Research transparency  
- Replicability  
- Better interdisciplinary communication  
- More thoughtful scientific writing  

Complementing the search for consensual and authoritative definitions, Re-SearchTerms encourages reflection and informed choice when seeking conceptual clarity.

---

## Current Scope

The current dataset includes:

- 2,000+ collected definitions  
- 200+ scientific concepts  
- Multiple disciplinary sources  

The platform is designed to grow over time and integrate community contributions.

---

## Looking Ahead

Future developments aim to:

- Expand disciplinary coverage
- Support teaching modules  
- Enable collaborative definition annotation  

The long-term vision is a living infrastructure for conceptual transparency in science.

---

## Video Tutorials

[Full Series of Video Tutorials](https://www.youtube.com/playlist?list=PLSLpkUCilSvrPyKLTgc8KWtMx7tPiiLVp)

This short video tutorial walks you through the key features of Re-SearchTerms:
{{< youtube id="_fueLK6ROpw" title="Re-SearchTerms App Overview" >}}

---

## Try It

[Launch the App](/link-to-app)  
[Explore the Code on OSF](/https://osf.io/vtqgn/)

---

## In a Nutshell

Re-SearchTerms helps us slow down, look carefully at the words we use, and build clearer, more transparent research together.

The paper relevant to this research is now accepted at *Meta-Psychology*. If you are interested, you may read the preprint version of the paper [here](https://doi.org/10.31219/osf.io/qsp7x_v2).

If you are interested in adapting Re-SearchTerms to your own field, dataset, or educational context, I would be delighted to explore potential collaborations. Please feel free to get in touch to discuss how the app could be tailored to your specific needs.
