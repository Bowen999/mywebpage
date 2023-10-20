---
date: "2023-10-20T00:00:00Z"
external_link: ""
image:
  caption:
  focal_point: Smart
links:
- icon: 
  icon_pack: 
  name: Read More
  url: https://bowenyang.netlify.app/project/cat/
- icon: github
  icon_pack: fab
  name: Code
  url: http://www.catbridge.work/

slides:
summary: A comprehensive longitudinal multi-omics analysis toolkit
tags:
- research
- softwares
title: CAT Bridge
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

### Description
With advancements in sequencing and mass spectrometry technologies, multi-omics data can now be easily acquired for understanding complex biological systems. Nevertheless, substantial challenges remain in determining the association between gene-metabolite pairs  due to the complexity of cellular networks. Here, we introduce CAT Bridge (freely available at http://catbridge.work), a user-friendly platform for longitudinal multi-omics analysis to efficiently identify transcripts associated with metabolites using time-series omics data. To evaluate the association of gene-metabolite pairs, CAT Bridge incorporated a range of methods harnessing cause-and-effect relationships and similarity computation, many of which are used in omic analyses for the first time. Additionally, CAT Bridge featured an artificial intelligence assistant to assist users interpreting the assoication results. We applied  CAT Bridge to self-generated (chili pepper) and public (human) time-series transcriptome and metabolome datasets. CAT Bridge successfully identified genes involved in the biosynthesis of capsaicin in Capsicum chinense L. Furthermore, case study results showed that the convergent cross mapping (CCM) method outperforms traditional approaches in longitudinal multi-omics analyses. CAT Bridge simplifies access to various established methods for longitudinal multi-omics analysis, and enabling researchers to swiftly identify associated gene-metabolite pairs for further validation.## Input
input file should be a CSV file, first column is m/z, second column is retention time.  
<img width="912" alt="Screenshot 2022-11-02 at 5 55 53 PM" src="https://user-images.githubusercontent.com/87933959/199610047-fc034120-bc9e-438f-a54f-bccca7fe9be6.png">

## Output
### Putitave identity table
<img width="1070" alt="Screenshot 2022-11-02 at 5 56 36 PM" src="https://user-images.githubusercontent.com/87933959/199610151-ef3c2539-6698-4c04-9416-2e5b6ffbc11a.png">


### Statistical analysis 
![Figure_1](https://user-images.githubusercontent.com/87933959/199609825-10a8c7fd-0634-41ff-bda9-bce508a09de2.png)
![Figure_2](https://user-images.githubusercontent.com/87933959/199610248-461960f7-0d4a-4c49-8b4b-c06d50a1c2c3.png)


