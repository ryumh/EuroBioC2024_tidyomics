# EuroBioC 2024 tidyomics

This is GitHub Repository for EuroBioC 2024 Demo titled

"Integrating DNA methylation with RNA-seq in lungs: Demonstrating the tidyomics ecosystem"

**Presenters:** Min Hyung Ryu, Stefano Mangiola\
Presented on September 4, 2024, Oxford, UK

## Abstract

Advanced technologies in genomics, epigenomics, transcriptomics, spatial analysis, and multi-omics have transformed biomedical research, offering both opportunities and challenges in data handling, exploration, analysis, integration, and interpretation. Here, we present the *tidyomics* software ecosystem ([https://github.com/tidyomics),](https://github.com/tidyomics),) bridging Bioconductor to the tidy R paradigm. This ecosystemaims to streamline omic analysis, ease learning, and encourage cross-disciplinary collaborations. The primary aim of this demonstration is to exhibit the tidyomics ecosystem, which is an open-source initiative designed to develop and integrate software tools that enable a tidy data analysis framework for Bioconductor omics objects. Tidyomics represents a comprehensive and interoperable software ecosystem for various omics technologies that encompass diverse omics analysis frameworks. The interactive workshop will focus on manipulating and integrating epigenetic (i.e., DNA methylation) and transcriptomics (i.e., RNA-seq data) datasets. We will use public datasets acquired through Genomic Data Common in the Cancer Genome Atlas Program (TCGA) to showcase how data are easily manipulated using tidy analysis packages. Specifically, we will demonstrate how to systemically link CpG sites to the nearest gene(s) and their gene expression profile. By the end of the demo, attendees will become familiar with tidyomics functionalities to aid in manipulating, integrating, and analyzing multiple omics data types in the Bioconductor ecosystem.

## Code description

`Get_public_data.Rmd`: This Rmarkdown file documents how TCGA database can be queried and downloaded onto your computer. For computation efficiency during the demo, two rds files were saved in a parent data directory hiden from the GitHub.

`EuroBioC2024_Tidyomics_Demo.rmd`: This Rmarkdown file documents the workflow demonstrated during the workshop and additional comments and notes.
