# Candida-omics

*Work in Progress*

This repository contains analysis pipelines and resources for **multi-omic integration** of data from our study on **recurrent vulvovaginal candidiasis (RVVC)** — commonly known as recurrent vaginal yeast infection.  

---

## Background

Recurrent vulvovaginal candidiasis (RVVC) affects **5%–10% of women**, significantly impacting reproductive health and quality of life.  

An introduction to the cohort and our investigation of bulk transcriptomics data can be found here:  
 [DOI: 10.1111/aji.70040](https://doi.org/10.1111/aji.70040)

---

## Data Overview

This repository will bring together multiple omics layers generated from the same cohort, including:

-  Bulk transcriptomics  
-  Shotgun metagenome sequencing  
-  Metabolomics   
-  Clinical data  

---

## Analysis

### Quality Control and Normalization

0. [QC-Tissue-Metagenome](https://vildeka.github.io/Candida-omics/src/QC_Tissue_Metagenomics.html)
1. [QC-Luminal-Metagenome](https://vildeka.github.io/Candida-omics/QC_Luminal_Metagenomics)
2. [QC-Metabolome](https://vildeka.github.io/Candida-omics/QC_Metabolomics)
3. [QC-Transcriptome](https://vildeka.github.io/Candida-omics/QC_Transcriptomics)

### PCA and Feature Selection
1. [FS-Luminal-Metagenome](https://vildeka.github.io/Candida-omics/Feature_selection_Metagenomics)
2. [FS-Metabolome](https://vildeka.github.io/Candida-omics/Feature_Selection_Metabolomics)
3. [FS-Transcriptome](https://vildeka.github.io/Candida-omics/Feature_selection_Transcriptomics)

### Unsupervised Factor Analysis (MOFA)
1. [MOFA](https://vildeka.github.io/Candida-omics/MOFA)


### Supervised sPLS-DA Analysis (DIABLO)
1. [sPLS-DA-Metagenome](https://vildeka.github.io/Candida-omics/src/Feature_selection_Metagenomics)
2. [sPLS-DA-Metabolome](https://vildeka.github.io/Candida-omics/src/Feature_Selection_Metabolomics)
3. [sPLS-DA-Transcriptome](https://vildeka.github.io/Candida-omics/src/Feature_selection_Transcriptomics) <br />
1. [01_DIABLO-Prepp](https://vildeka.github.io/Candida-omics/01_DIABLO_prepp)
2. [02_DIABLO-models](https://vildeka.github.io/Candida-omics/02_DIABLO_models)


*(More analysis pipelines and results will be added as the project progresses.)*

---

