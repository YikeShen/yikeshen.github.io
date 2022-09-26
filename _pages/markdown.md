---
permalink: /markdown/
title: "Bioinformatics Collaboration"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---
![](microbiome-omics fig.png)
## Introduction

* Microbiome sequencing price has dropped substantially. More researchers and companies are interested in learning about microbiome in humans, environment, and animals. Shotgun sequencing has enabled in-depth learning of microbial community structure, pathway, functional potential, and active functions. One answer we ALL want to know about microbiome: Who is there, what are they doing? 
* Shotgun data is easier to obtain now than before with high throughput sequencing platforms like Illumina NovaSeq6000. However, it is challenging to analyze the data for researchers who don't have coding experience. First, the data generated from shotgun sequencing is huge, usually ranging from 3G to 20G, more than 40 million reads per sample for shotgun metagenome. Shotgun metatreanscriptome is even more challenging, with more than 20G and 150 million reads per sample. The mid-files generated in computation multiply output size. It's easy to have 100 samples metagenome take 4T of storage space, and 160 samples metatranscriptome take 30T of storage space (including intermediate files). Second, because of large data, computation time can exponentially increase. For example, shotgun metagenome assembly and mapping can take up to 20 hours per sample. Shotgun metatranscriptome rRNA, adapter, human genome, and human transcriptome removal take an average of 90 hours of computation time. The computation also consumes large memory(100G). Third, data processing is time-consuming and requires access to supercomputing clusters. Finally, data processing also involves proficient use of python and unix in Linux system.
* A side note: I often see people using human databases for environmental samples in shotgun metagenomic sequencing. It is not wrong, but you are only mapping up to 20% of your environmental sample reads into the human database. Analyze shotgun metagenomic sequencing for environmental samples are more challenging. I recommend the researchers identify the goal of the research and use assembly based approaches. 
* I am happy to collaborate with your microbiome projects. I can offer my insights on what computation resources you need and help you process the data with potential options. If you are a student, I am happy to guide you on how to learn those bioinformatics tools and pipelines. Please email me for collaborations.  

### Typical Microbiome Sequencing

| Sequencing         | Typical steps                                                             |
| --------         | ------------------------------------------------------------ |
| Shotgun metagenome| QC, host removal(if needed), mapping or assembly, species and pathway profiling, and more |
| Shotgun metatranscriptome| QC, rRNA removal, host removal (if needed) mapping or assembly, gene expression, and more |
| Amplicon sequencing| QC, OTU table, alpha and beta diversity, community structure|

