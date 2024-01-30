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
- icon: chrome
  icon_pack: fab
  name: Website
  url: http://111.229.151.228:5000
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/Bowen999/LIME

slides:
summary: Metabolite library and annotation tools
tags:
- research
- softwares
title: MCID 2.0 & LIME
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

Metabolites play an important role in various biological functions, and the development of analytical chemistry techniques, especially Liquid Chromatography-Mass Spectrometry (LC-MS), has made high-throughput detection of metabolites possible. However, a major challenge in the field is that currently only about 30% of features detected by LC-MS can be identified, most features are "dark matter" due to the absence of corresponding matches in databases. Also, although many databases have been created and a huge number of compounds are present, there are no uniform naming standards among them, making manual large-scale searching a highly time-consuming and error-prone task.  

To tackle these issues, we integrated resources from different databases through [InChIKey](https://www.inchi-trust.org), and predicting biochemical reaction products using [RDKit](https://www.rdkit.org) to construct 1 reaction and 2 reaction libraries. This approach expands the identification coverage. Following this concept, we are developing **[MCID 2.0](http://111.229.151.228:5000)** and **[LIME](https://github.com/Bowen999/LIME)**.


![Figure_1](./mcid.png)
![Figure_1](https://user-images.githubusercontent.com/87933959/199609825-10a8c7fd-0634-41ff-bda9-bce508a09de2.png)
![Figure_2](https://user-images.githubusercontent.com/87933959/199610248-461960f7-0d4a-4c49-8b4b-c06d50a1c2c3.png)





