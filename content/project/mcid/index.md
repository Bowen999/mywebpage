---
date: "2023-9-01T00:00:00Z"
external_link: ""
image:
  caption:
  focal_point: Smart
links:
- icon: 
  icon_pack: 
  name: Read More
  url: https://bowen999.netlify.app/project/lime/
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/Bowen999/LIME

slides:
summary: Metabolite library and annotation tools
tags:
- research
- softwares
title: LIME & MCID2.0
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

### LIME
Modern mass spectrometers can detect thousands of compounds in the biological samples with unprecedented sensitivity. And metabolomics is a technique to compare and discover the different of compounds (metabolites) in different samples. As a study primarily concerned with compounds in organisms, metabolomics is regarded as the most phenotype-reflective omics. One of the most challenging phases in metabolomics analysis is the annotation and identification of the compounds. Although many databases have been created and a huge number of compounds are present, there is not a complete overlap and no uniform naming standards among them, making manual large-scale searching become a highly time-consuming and error-prone task.  

Therefore, we developed two automated tools for metabolite identification, **MCID 2.0** and **LIME**.

## LIME
LIME is a high-throughput metabolite annotation tool for post-processed liquid chromatography-mass spectrometry (LC-MS) metabolomic data. MS1 Features (m/z, retention time) that uploaded are searched for in LIME-integrated databases and sorted by score. The database of LIME includes 286,268 unique chemical structures when ignoring stereochemistry and charge, which were integrated from [Human Metabolome Database (HMDB)](https://hmdb.ca), [Chemical Entities of Biological Interest (ChEBI)](https://www.ebi.ac.uk/chebi/), and [LIPID MAPS](https://www.lipidmaps.org), three mainstream metabolite databases. InChIKey, a fixed-length format derived from [IUPAC International Chemical Identifier (InChI)](https://www.inchi-trust.org/) by hash, was used as the unique identifier of LIME.  


![Figure_1](https://user-images.githubusercontent.com/87933959/199609825-10a8c7fd-0634-41ff-bda9-bce508a09de2.png)
![Figure_2](https://user-images.githubusercontent.com/87933959/199610248-461960f7-0d4a-4c49-8b4b-c06d50a1c2c3.png)


## MCID 2.0 

*	Integrated metabolites from the KEGG database to upgrade the initial MCID 1.0
*	Predicted products of primary metabolites across 76 biochemical reactions, to establish the one-reaction database
*	Currently developing a web app to facilitate metabolite identification 


The test demo of MCID 2.0 is available at [http://111.229.151.228:5000](http://111.229.151.228:5000
).



