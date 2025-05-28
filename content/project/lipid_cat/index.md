---
date: "2025-05-26T00:00:00Z"
external_link: ""
image:
  caption:
  focal_point: Smart
links:
- icon: 
  icon_pack: 
  name: Read More
  url: https://byang.netlify.app/project/lipid_cat/

slides:
summary: A Comprehensive Resource for Contaminant Identification in LC-MS Lipidomics
tags:
- research
- software

title: Lipid CAT
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---
### Introduction
Lipidomics provides crucial insights into cellular processes and disease through the comprehensive analysis of lipids, primarily employing Liquid Chromatography (LC) and Mass Spectrometry (MS). A persistent challenge in these MS-based analyses is the presence of contaminants originating from experimental materials. These contaminants complicate signal interpretation and can lead to misidentification of true analytes. Unlike other MS-based fields with established contaminant databases (e.g., CRAPome for proteomics, MaConDa for metabolomics), lipidomics has lacked a dedicated software solution for contaminant identification. We introduce Lipid CAT (Contaminant Analysis Tool), novel software that matches unknown MS/MS spectra against a specialized contaminant database, significantly improving lipidomics data accuracy.

### RESULT
* 200 ubiquitous contaminants (from 268 features) were detected in plasticware, while 53 contaminants (from 55 features) were found in glassware
* These contaminants interfere with lipid characterization and quantification, but only 3.9%of them could be reliably identified through publicly MS databases
* An MS2 data processing workflow was developed, specifically compatible with identifying consensus spectra for low-abundance contaminants
* A contaminant MS database was established, along with a user-friendly web application


#### METHODS
To enhance lipid identification, we developed Lipid CAT. First, Folch extraction of water blanks was performed, followed by reversed-phase UHPLC QTOF (quadrupole-time-of-flight) MS analysis, to compare polypropylene and borosilicate glass labware from various manufacturers. An HDBSCAN-based data processing workflow, suitable for compounds with varying abundances, was used to acquire MS information from representative database was built. We also developed a web application using React and Python to facilitate contaminant identification for users. Finally, the ubiquity of these contaminants was validated using other mass spectrometry platforms (6546 Q-TOF, Orbitrap Exploris 240).

### ACKNOWLEDGMENTS
This work was supported by grants from the Natural Sciences and Engineering Research Council of Canada, Canadian Institutes of Health Research, Canada Foundation for Innovation, Genome Canada, Alberta Innovates and Mitacs.

### REFERENCE
Campello, R., et al. (2013). PAKDD. 7819, 160–172.
Röst, H. L., et al. (2016). Nature Methods. 13, 9, 741–748.
Canez, C. R., et al. (2024). Analytical Chemistry. 96, 8, 3544–3552.
Canez, C. R., et al. (2024). Analytical Chemistry. 96, 21, 8373–8380.
