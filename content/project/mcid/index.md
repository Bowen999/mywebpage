---
date: "2023-12-01T00:00:00Z"
external_link: ""
image:
  caption:
  focal_point: Smart
links:
- icon: 
  icon_pack: 
  name: Read More
  url: https://byang.netlify.app/project/mcid/
- icon: 
  icon_pack: 
  name: Poster
  url: https://github.com/Bowen999/mywebpage/blob/main/content/project/mcid/Poster_CanMetCon2024.pdf

slides:
summary: An evidence-based metabolome library for metabolite identification
tags:
- research
- softwares
title: MyCompoundID 2.0
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

# Introduction
Metabolites play an important role in various biological functions, and the development of analytical chemistry techniques, especially Liquid Chromatography-Mass Spectrometry (LC-MS), has made high-throughput detection of metabolites possible. However, a major challenge in the field is that currently **only about 30% of features** detected by LC-MS can be identified, most features are “dark matter” due to the absence of corresponding matches in databases. To tackle these issues, the MyCompoundID (MCID) was developed. It employs the prediction of biochemical reaction products to expand metabolites coverage, and has been widely used, garnering over 610 citations. However, the last update to MCID was nine years ago. Recognizing advancements in metabolomics in recent years, especially as **new metabolites from different species** have been discovered, and **new cheminformatics methods** have been developed, we have updated and introduced MCID 2.0, the new version of this tool, to improve the accuracy of predicted products and to expand their application scope.

![Workflow](./workflow.png)

# Novel Aspects
* Expand the coverage of compounds and species to accommodate different research subjects
* Construct a scalable and maintainable rule-based reaction product prediction pipeline
* Provide a more modern, user-friendly interface applicable to various scenarios

# Preliminary Results 
MCID 2.0, an advanced cross-platform tool for metabolite identification, is developed. It features a new evidence-based metabolome database to enhance LC-MS feature identification coverage. 
![Software](./software.png)

We have divided our initial databases into six sections based on the type of organisms they cover, which include **Humans, Plants, Livestock, Microbes, Marine organisms, and KEGG** (a comprehensive library). After excluding lipids and disregarding stereo structures, we predicted the one-step reaction outcomes for each of these initial libraries to construct one-reaction libraries. Subsequently, we used these one-reaction libraries as substrates to predict their one-step reaction products, creating two-reaction libraries.
![Initial libraries](./initial_libraries.png)

To facilitate the prediction of reaction products, we developed a **maintainable and scalable reaction pipeline** using [RDKit](https://www.rdkit.org). This pipeline utilizes the [Simplified Molecular Input Line Entry System (SMILES)](https://www.daylight.com/dayhtml/doc/theory/theory.smiles.html) to represent molecular structures and [SMILES Inferred Reaction Knowledge Syntax (SMIRKS)](https://www.daylight.com/dayhtml/doc/theory/theory.smirks.html) to denote reaction rules, allowing for rapid integration of new chemical transformation rules and their application to new datasets. In addition, we have **established rules for 76 common biochemical reactions**, which are currently being applied to the initial libraries.
![Initial libraries](./products.png)

By predicting products from these reactions, the number increases and covers a greater chemical space. This expansion can help explain some LC-MS features that were previously unannotated in the original datasets.
![num_of_comp](./num_of_comp.png)
